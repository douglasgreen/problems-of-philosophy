# Working on this book

This is a collaborative, single-author philosophy textbook: *The Problems of Philosophy*, written to be read aloud. The chapters are in `chapters/`, and the conventions below are the ones the book actually uses. The authority for the house style is `chapters/00-introduction.md` (especially its §5, "How a chapter is built", and §7, "Conventions"); the chapters that have already been revised (6–11) are the practical reference.

## Repository layout

| File | Content |
|---|---|
| `chapters/00-introduction.md` | The Introduction (unnumbered) |
| `chapters/01-…` – `chapters/54-…` | Chapters 1–54 |
| `chapters/55-…` – `chapters/59-…` | Appendices A–E |
| `outline.md`, `metadata.yaml` | Book-level metadata |
| `AGENTS.md` | This file |

**The chapter number equals the file number** (`01-what-philosophy-is.md` is Chapter 1; `11-testimony.md` is Chapter 11; `54-value-of-philosophy.md` is Chapter 54); the Introduction is unnumbered and lives in `00-introduction.md`. File names are `NN-kebab-case-title.md` with the title in lower case and an em dash replaced by a hyphen. Never renumber a file to fix a citation; fix the citation.

## Pandoc conversion

Due to the large number of formulas, rendering is best done with MathML:

```
pandoc -f markdown -s --mathml -t html chapters/00-introduction.md
```

Render a chapter after every change to its mathematics. Pandoc prints `Could not convert TeX math` for any formula it cannot parse (usually an unclosed `\text{…}` or a missing `\\` at the end of a row); there must be no such warnings. The HTML output is the only reliable way to see whether emphasis, bold, and tables survive the conversion.

## Writing conventions

### Typography

- **Curly quotation marks and apostrophes everywhere**: “ ” and ’. Chapters 1–3, 5, 7, 10, and 11 use them throughout; a straight `"` or `'` is a defect to be fixed on the next pass (Chapter 4 alone still has 162 straight double quotes).
- **Spaced em dash** for parentheticals and breaks: “a discipline of systematic analysis — the disciplined study of…”.
- **En dash** for ranges (“Chs. 5–13”, “1980s–1990s”, “X–XII”) and for compounds that join two coordinated terms (“mind–body”, “prose–poetry”). Never a hyphen between numbers.
- **Ellipsis** as “…”, never three dots.
- **Titles**: books, journals, and works in italics (*The Problems of Philosophy*); articles and chapters in quotation marks (“Against Gullibility”), with the quoted title *not* italicised.
- **Citations**: “Ch. 11, §2.2” (note the space after §), “Chs. 3–4”, “I.1, 980a21”, “(1912)”.
- Use ordinary spaces; there are no non-breaking spaces, no hyphenation tricks, no Markdown line breaks inside a paragraph.

### Italics

Three uses only, as §7 of the Introduction states: a technical term **on its first occurrence**, **emphasis**, and — in Parts II–VII — the **keyword of a sentence**. Italicise deliberately: the point is a countable set of marks, not a wash of italics on every content word. Within a display formula, write plain text inside `\text{…}`; the revised chapters contain no emphasis markers in mathematics.

### Bold

- Bold names the move and is closed immediately after the lead phrase: **The objection.** The rest of the paragraph is plain text.
- Bold labels the leading cell of table rows, and marks the numbered claims that open a section in the Introduction and Part I.
- A bold span is never left open. Before finishing, check that every line has an even number of `**`; an odd count means the paragraph will render entirely bold.

### Pronouns and spelling

- The generic agent is *she/her* in a little over half the cases and *he/his* in the rest, alternating **by chapter**, not by sentence.
- American English: -ize/-ization (formalization, recognize), behavior, defense, center, skeptical, program, license (noun) / practice (verb) / practice (noun), labor, analyze, judgment. American spellings are the house style everywhere in the book’s own prose, including headings, tables, and formulas. The one exception is quoted material and citations: a quotation keeps the spelling of the source, and a title keeps the spelling of the work. So Hume’s *Enquiry*, Moore’s “A Defence of Common Sense,” and Lakatos’s “Research Programmes” are left alone, while the prose around them is American.
- No footnotes anywhere. Citations live in parentheses in the body and in the Further Reading list.

### The shape of a chapter

Each chapter follows the same architecture (Introduction §5):

1. **Epigraphs** — two to five block quotations, three being the norm, from across the history of the subject and arranged so that they disagree. Each is followed by an attribution line beginning “— ” with author, italic title, year, and locator.
2. **A framing section** — the question, the senses in which it can be asked, the constraints on an answer.
3. **A roadmap** — a paragraph of the form “The chapter proceeds in eight movements. §1 … §8 …”.
4. **Numbered sections**, `## 1.` to `## 8.`, with `### N.M` subsections; the first subsection of each section states the position and its structure.
5. **§8, The State of the Debate** — *What is settled*, *What is open*, *The methodological lesson*, *The dialectical map* (a table of every position with its core claim, its strength, and its weakness). Chapters 6 and 7 name their eighth section for their subject instead, but keep the four subsections.
6. **`## Optional threads`** — short cross-cutting notes: non-Western alternatives, empirical literature, connections to distant chapters.
7. **`## Summary`** — one bullet per major claim.
8. **`## Study Questions`** — ten to sixteen, running from the elementary to the genuinely open; never comprehension checks.
9. **`## Further Reading`** — tiered and annotated, grouped by topic, with the primary texts first.
10. **A closing block** — a `> *A closing note.*` paragraph and a `> *And a bridge.*` paragraph that hands the reader to the next chapter. The next chapter's opening refers back, so the two must agree.

### Mathematics

- Display mathematics in `$$ … $$`, inline mathematics in `$…$`.
- Arguments are typeset as `\begin{array}{ll}` with numbered rows (`1. & \text{…} \\`), a `\hline` before the concluding row, and `\therefore` in the conclusion:

```
$$
\begin{array}{ll}
1. & \text{The premise is true.} \\
2. & \text{The inference is invalid.} \\
\hline
3. & \therefore \text{The conclusion does not follow.}
\end{array}
$$
```

- Every `\text{…}` must be closed, and every row except the last must end with ` \\`. An unclosed brace makes pandoc refuse the whole formula.
- No Markdown emphasis inside math; it renders as literal asterisks.

### Tables

Pipe tables with a header row and a `|---|---|` separator. Bold the leading cell of each row. Keep cells short; a table is for comparisons, not for prose. Tables are the one place where the book is allowed to be terse.

### Cross-references

- Format: “Ch. 11, §2.2” for another chapter, “§5.3” within the same chapter, “Ch. 26, §§3.2 and 4.1” for several sections.
- Section numbers are stable. Before citing a section, open it and check that it says what the citation claims. A cross-reference points to a claim, not to a topic.
- Chapter 11 refers back to Chapter 10 and forward to Chapter 12; Chapter 12 opens by taking up Chapter 11's bridge. Keep those hand-offs consistent.

### A revision checklist

1. **Verify every fact and citation against a source** (see the TinyFish section below). A citation that cannot be verified is worse than no citation; remove it or replace it with one that can.
2. **Check every cross-reference** — the target section must exist and must support the claim attributed to it.
3. **Check the logic** — premises must support the conclusion, the verdict must follow from the sections above it, and the summary must not claim more than the chapter argues.
4. **Check the typography** — curly quotes, balanced `**` and `*`, no stray asterisks in the rendered HTML, en dashes in ranges, spaced em dashes.
5. **Check the mathematics** — pandoc renders it without warnings.
6. **Check the hand-offs** — the roadmap, the summary, the closing note, the bridge, and the next chapter's opening.

## Web Search with TinyFish

TinyFish is this project's web and external-knowledge toolkit; it is free and the most token-efficient way to check a fact, a citation, or a bibliographic detail. Prefer it to any native web-search or web-fetch tool. When searching the web using TinyFish in OpenCode, adhere strictly to the invocation formats below. **Do not guess parameter names**: the tool catalogue is the source of truth, and the signatures change.

### Locating the tools

The server is named `tinyfish`. Inside the code-mode runtime the tools are reached as `tools.tinyfish.<name>` (some harnesses expose them as `tinyfish__<name>`). Before calling a tool you have not used in this session, look up its live signature:

```js
const r = await search({ query: "tinyfish search fetch_content" });
return r.items;   // each item has .path and .signature
```

`path` is the exact tool path; `signature` is the exact argument list. Code mode has **no filesystem access** — use the shell and edit tools for files, and the TinyFish tools only for the web.

### 1. `search` — find the page

`tools.tinyfish.search({ … })` takes a single JSON object:

| Parameter | Type | Notes |
|---|---|---|
| `query` | string, **required** | The search keywords (1–2000 chars). |
| `purpose` | string, optional | What the results are for; it improves ranking. |
| `location` | string, optional | 2-letter ISO country code (`"US"`). |
| `language` | string, optional | 2-letter ISO code (`"en"`). |
| `include_domains` / `exclude_domains` | string, optional | Comma-separated domain lists. |
| `domain_type` | string, optional | `"web"` (default), `"news"`, or `"research_paper"`. |
| `after_date` / `before_date` | string, optional | `"YYYY-MM-DD"` window. |
| `recency_minutes` | integer, optional | e.g. `1440` for the past 24 hours. Do **not** combine with `after_date`/`before_date`. |
| `pub_year_min` / `pub_year_max` | integer, optional | Publication-year window for `domain_type: "research_paper"` only. |
| `page` | integer, optional | 0–10. |

Returns `{ query, results: [{ position, title, url, snippet, site_name, date? }], total_results, page }`.

Correct example:

```js
const res = await tools.tinyfish.search({
  query: "Fricker 'Telling and Trusting' critical notice of Coady Mind 1995",
  purpose: "Verify the bibliographic details of a citation used in Chapter 11"
});
```

Rules that matter:

- For academic citations prefer `domain_type: "research_paper"` (with `pub_year_min`/`pub_year_max`); it has better provenance than general web results.
- `recency_minutes` and `after_date`/`before_date` are mutually exclusive.
- Run independent searches **in parallel** in one code-mode block with `Promise.allSettled`, and print only what you need.

### 2. `fetch_content` — read the page

`tools.tinyfish.fetch_content({ … })` takes `urls` (an array of 1–10 URLs) plus these options:

| Parameter | Type | Notes |
|---|---|---|
| `urls` | array of URI, **required** | Up to ten URLs, fetched in parallel. |
| `purpose` | string, optional | How the content will be used; it tailors the extraction. |
| `format` | string, optional | `"markdown"` (default), `"html"`, or `"json"`. |
| `links` / `image_links` / `iframe_links` | boolean | Also return outbound links / image / iframe URLs. |
| `page_metadata` | boolean | Return title, description, author, published date, etc. |
| `ttl` | integer, optional | Cache tolerance in seconds (`0` forces a live fetch). |
| `per_url_timeout_ms` | integer, optional | Per-URL wall-clock budget. |
| `include_selectors` / `exclude_selectors` | array of strings | CSS selectors to scope or strip. |
| `if_none_match` / `if_modified_since` | string, optional | Conditional request (one URL only). |
| `include_etag_and_last_modified` | boolean | Return validators. |

**Always pass `format`, `links`, `image_links`, `iframe_links`, and `page_metadata` explicitly.** In this harness a call that omits them is rejected with a schema error before it reaches the network.

Returns `{ results: [{ url, final_url, title, text, … }], errors: [{ url, error }] }`.

Correct example:

```js
const r = await tools.tinyfish.fetch_content({
  urls: ["https://plato.stanford.edu/entries/disagreement/"],
  purpose: "Check the list of proponents of the steadfast view",
  format: "markdown",
  links: false,
  image_links: false,
  iframe_links: false,
  page_metadata: false
});
```

Practical notes:

- The `text` field can be a hundred kilobytes. **Do not print it whole**: take the JSON string, `indexOf` the passage you need, and print a window around it.
- Some sites block crawlers (`bot_blocked`) and some direct PDF links do not extract. Fall back to the `search` snippet, try `format: "html"`, or use `domain_type: "research_paper"`.
- A URL that is blocked is reported in `errors` while the other URLs still succeed; check both arrays.

### 3. Other TinyFish tools

- `run_web_automation` — interactive pages (clicking, navigating, filling forms). It takes several minutes and is metered. If it errors or times out, **the run may still be executing**: do not retry blindly; check with `get_run` or `list_runs`.
- `start_deep_research` / `get_deep_research` — slow and billed; use only when the user asks for deep research or a cited report.
- `list_monitors`, `get_monitor`, `run_monitor`, `cancel_monitor` — scheduled re-checks; only on request.
- `get_search_usage` / `list_fetch_usage` — history and audit; only on request.

If a tool returns an insufficient-credits or subscription message, show the user the upgrade or top-up link from the error as a clickable markdown link, exactly as given, and ask them to open it; do not paraphrase the URL away or silently fall back to a weaker tool.
