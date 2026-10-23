# Chapter 3 — The Instruments of Analysis

> “Philosophy is a battle against the bewitchment of our intelligence by means of language.”
> — Wittgenstein, *Philosophical Investigations*, §109

> “A philosopher who has not thought about a problem for a long time is like a man who has been told to paint a picture and has been given no brushes.”
> — a formulation of the warning, in the sententious tradition of Austin and his predecessors

Chapter 2 gave us the anatomy of an argument. But arguments do not fall from the sky. Before an argument can be assessed, a question must be isolated, a concept must be clarified, a case must be constructed, a theory must be formalized, a practice must be reconstructed, a belief’s origin must be examined, or a pseudo-problem must be diagnosed. These are the **instruments of analysis**, and every philosopher uses them. Most use them badly, because they have never been taught what the instruments are, what they are for, or when they break.

This chapter is a field guide to seven instruments:

1. **Conceptual analysis** — the analysis of concepts into conditions.
2. **Thought experiments** — the construction of cases to test concepts and theories.
3. **Formalization** — the representation of claims in formal languages.
4. **Reflective equilibrium** — the method of adjusting judgments and principles to coherence.
5. **Genealogy and debunking** — the examination of belief-origins for epistemic purposes.
6. **Phenomenology, ordinary language, and experimental philosophy** — the three empirical-adjacent methods available to the armchair.
7. **Negative capability** — the technique of dissolving a problem rather than solving it.

Each instrument has a characteristic rationale, characteristic achievements, and characteristic failure modes. The master skill is not *in* using any one of them, but in **knowing which to use, when to stop, and what nothing can do for you.**

---

## 1. Conceptual Analysis

### 1.1 The classical model

The oldest and most characteristic instrument of philosophy is **conceptual analysis**: the attempt to specify the conditions under which a concept applies.

The standard form is a biconditional. For a concept $K$ and a set of conditions $F_1, \dots, F_n$:

$$
\forall x\, (Kx \leftrightarrow (F_1 x \wedge F_2 x \wedge \cdots \wedge F_n x))
$$

Each condition is **individually necessary** (if $Kx$ then $Fx$) and **jointly sufficient** (if all the $F$s then $Kx$). The classical example, from the *Theaetetus* via Gettier, is knowledge:

$$
\forall x\, (\text{Knowledge}(x) \leftrightarrow (\text{Belief}(x) \wedge \text{Truth}(x) \wedge \text{Justification}(x)))
$$

The instrument has an impressive record. The theory of descriptions (Russell 1905) analyzes a class of sentences previously thought to be ontologically committed to things that do not exist (Ch. 12, §2). The analysis of knowledge as justified true belief survived two millennia before Gettier (Ch. 7, §2). The analysis of the virtues, the analysis of causation, the analysis of *person*, the analysis of *freedom* — each is a genuine intellectual achievement, even where it failed.

There is something right about the classical model that we must keep in view: **you cannot argue well about a concept you cannot state.** If you cannot say what you mean by “justice,” you cannot say whether a proposal is just. Analysis is the price of intelligibility.

### 1.2 The criteria of adequacy

When is an analysis a *good* analysis? The classical criteria are worth stating precisely, because they are what the search for counterexamples is testing.

| Criterion | What it demands | Common failure |
|---|---|---|
| **Extensional adequacy** | The analysans applies to exactly the right things | Counterexamples (Gettier) |
| **Informativity** | The analysans is not a mere synonym of the analysandum | Trivial analysis (“knowledge is *knowing* …”) |
| **Non-circularity** | The analysans does not covertly use the analysandum | The regress of justification (Ch. 8, §1) |
| **Simplicity / economy** | No superfluous conditions | Ad hoc clauses added to save a theory |
| **Explanatory power** | The analysis explains the *point* of the concept — why we have it, what work it does | Definitions that are extensionally correct but theoretically empty |
| **Conservatism** | The analysis does not revise the concept beyond recognition | Analysis becomes replacement (see §1.5) |

The tensions between these criteria generate the **paradox of analysis**, first formulated crisply by Langford (1942) on Moore’s behalf: *if the analysans is synonymous with the analysandum, the analysis is trivial; if not, the analysis cannot be correct, since it is not the same concept.* The attempted escapes are instructive:

- **Frege’s sense/reference distinction** (Ch. 31, §2) lets us say that the analysans has the *same referent* as the analysandum but a different *sense*. The analysis is informative because it presents the same concept differently.
- **Carnap’s explication** (1950) abandons exact synonymy entirely. We *replace* a vague concept with a precise one, subject to the constraints that the replacement be similar enough, exact, fruitful, and simple. On this view the analysis is judged as a *proposal*, not as a discovery.
- **Jackson’s “modest conceptual analysis”** (1998) holds that the analysis is a claim about the *possible* cases to which the concept applies, and that this is as informative as the nature of the concept requires.

None of these escapes is decisive. The paradox of analysis is a permanent of the instrument, and the honest response is to be explicit about which conception of analysis you are operating with.

### 1.3 The method of cases

The standard procedure for testing an analysis is the **method of cases**. Take the proposed conditions; construct or discover a possible situation in which the conditions are met but the concept does not apply (a **false positive**), or in which the concept applies but the conditions are not met (a **false negative**).

```
Proposed analysis: Kx ↔ Fx ∧ Gx ∧ Hx

False positive:  ¬Kx  but  Fx ∧ Gx ∧ Hx     → conditions insufficient
False negative:   Kx  but  ¬(Fx ∧ Gx ∧ Hx)  → conditions not necessary
```

The method is **the engine of analytic philosophy**, and its iterations are the history of most debates. Gettier’s cases are false positives (justified true belief without knowledge). Putnam’s Twin Earth is a false negative (meaning does not supervene on internal state; Ch. 25, §4.1). Ramsey’s parrot (in BonJour’s reconstruction) and Putnam’s robot dog are further specimens: the literature is a zoo of imaginative cases.

**The methodological problem.** The method presupposes that we have reliable intuitions about whether a case falls under a concept. But:

- Intuitions conflict, and there is no neutral arbiter.
- Intuitions may be *performance errors* rather than data.
- A counterexample can be accommodated by adding a clause, and an ad hoc clause can save any theory (§1.6).

Max Deutsch (2010, 2015) has pressed the sharpest version of the objection: strictly speaking, there are no counterexamples, because **being a counterexample is an epistemic status, not a semantic one.** A case is a counterexample only if it is *correctly judged* to be an instance or non-instance, and the judgment may be mistaken. On his view, the correct response to an apparent counterexample is not automatic rejection of the analysis but a *potentially revisionary* adjustment — sometimes we should trust the analysis and revise the intuition.

Whether Deutsch is right is contested (the standard reply: intuitions about cases are not *indefeasible*, but they are *default evidence*, and defaults can be defeated only by argument, not by methodology). What is not contested is that the method’s authority depends on a **calibration story**: an account of when the intuition is likely to be reliable and when it is likely to be noise. We shall need such a story in §2 and §6.

### 1.4 The classical model’s challengers

The classical model has been under attack from four directions. Each attack is serious, and each has a partial reply.

**(i) Family resemblance (Wittgenstein).** For many concepts — *game*, *art*, *number*, *person* — there is no set of conditions shared by all instances. Instead there is a network of overlapping similarities: “a complicated network of similarities overlapping and criss-crossing” (*PI* §66). The concept is held together by *use*, not by a hidden essence. If Wittgenstein is right, the search for necessary and sufficient conditions is doomed for a wide class of concepts, and the right analysis is a *description of the network*.

*Reply*: family resemblance may be a feature of *some* concepts and not others; the paradigm cases (knowledge, causation, truth) may still have classical structures. The work of Rosch (1975) and subsequent prototype theory suggested that many concepts are *graded* — there are better and worse instances — which is incompatible with the classical model. But gradedness is compatible with a *classical core plus a prototype periphery* (the “dual-process” or “core-plus-prototype” view). The debate is far from settled.

**(ii) Semantic externalism (Kripke, Putnam).** If the meaning of a natural kind term is fixed by the actual microstructure of the stuff, then the concept cannot be analyzed from the armchair; we must investigate the world (Ch. 12, §3; Ch. 39, §3). “Water” is whatever substance plays the right role in the actual world, and no amount of conceptual reflection can tell us whether that is H₂O or XYZ. This does not refute conceptual analysis for *normative* or *formal* concepts, but it does limit its scope for empirical ones.

**(iii) Quine’s holism.** If the analytic/synthetic distinction collapses (Ch. 36, §1.3), then the idea of an analysis that is true *in virtue of meaning alone* loses its footing. Conceptual analysis becomes a special case of theory construction, judged by the same holistic standards as science. This is the naturalistic challenge, and it is the deepest of the four.

**(iv) Experimental philosophy.** If intuitions about cases vary with culture, order of presentation, and affect, then the method of cases is empirically unreliable. This is the subject of §6.3, and we shall see that the challenge is real but has been overstated.

### 1.5 Analysis, explication, and engineering

There is a crucial distinction, often blurred, between three projects that all look like “analysis”:

| Project | Aim | Criterion of success | Paradigm |
|---|---|---|---|
| **Conceptual analysis** | Describe the concept we actually have | Extensional adequacy to pre-theoretic intuition | Gettier on knowledge |
| **Explication** | Replace a vague concept with a precise one | Fruitfulness, exactness, similarity | Carnap on probability |
| **Conceptual engineering** | Improve a concept for a purpose | Fitness for the purpose; normative argument | Haslanger on *race*; Cappelen (2018) |

The difference matters because the criteria are different. An analysis is refuted by a counterexample; an explication is not, because it was never trying to capture every case. An engineered concept is not *refuted* at all; it is *argued for* — on the grounds that the old concept served us badly, or served interests we should not serve.

The most philosophically loaded version of this distinction is Sally Haslanger’s distinction between a **descriptive** and an **ameliorative** project (2000, 2012). Analyzing *gender* descriptively tells us how the term is used; analyzing it amelioratively asks what concept we *should* have, given our purposes. Haslanger argues that the ameliorative question is prior, because the descriptive question presupposes a purpose, whether acknowledged or not. Her work on race and gender is the best contemporary example of conceptual engineering in action, and it raises the question the whole book will return to in Ch. 33, §5: **whose purposes should concepts serve?**

What must be kept clear: **engineering is not cheating.** But it is also not analysis. A philosopher who claims to be analyzing a concept while silently replacing it with a better one is committing a subtle but serious deception — sometimes self-deception. The honest practice is to declare which project is underway.

### 1.6 The ad hocness problem

Every analysis can be saved by adding a clause. The Gettier industry is the classic case: after Gettier’s two cases, a hundred analyses were proposed, each adding a fourth condition to handle a hundred new counterexamples. The question is when such additions are legitimate and when they are **ad hoc**.

The standard tests for ad hocness:

1. **Independent motivation.** Does the added condition have a rationale beyond saving the theory?
2. **Fertility.** Does it generate new, correct predictions beyond the cases that motivated it?
3. **Unification.** Does it cohere with the rest of the theory, or is it a patch?
4. **Predictive antecedent.** Was the condition specified *before* the counterexample, or only after?

This is the most important methodological skill in analytic philosophy, and it is almost never taught explicitly. A theory that has been patched ten times is not necessarily wrong; but it is *on the defensive*, and the burden of proof has shifted.

---

## 2. Thought Experiments

### 2.1 What a thought experiment is

A **thought experiment** is a description of a possible situation, presented as evidence for a philosophical conclusion. Its parts are:

1. **Setup**: the description of the case (often stipulating idealizations).
2. **Stipulation**: claims about what is true in the case, accepted by the reader.
3. **Intuition**: the reader’s spontaneous judgment about the case (e.g., “that is not knowledge”).
4. **Judgment**: the claim that the intuition is correct.
5. **Generalization**: the derivation of the philosophical consequence (e.g., “justification is not sufficient for knowledge”).

The last step is where thought experiments earn their keep and where they most often fail. The intuition is *about a case*; the conclusion is *about a concept* or *about the world*. The bridge between them requires argument, and the bridge is usually suppressed.

### 2.2 The canon

The following table lists the thought experiments that every student should know. Read the list as a map of the discipline.

| Thought experiment | Author / date | Question | Result claimed |
|---|---|---|---|
| **Gettier cases** | Gettier 1963 | What is knowledge? | JTB insufficient |
| **Twin Earth** | Putnam 1975 | What determines meaning? | Externalism: meaning isn’t in the head |
| **Mary’s room** | Jackson 1982 | Is physicalism true? | There are non-physical facts |
| **The zombie** | Chalmers 1996 | Is consciousness physical? | Conceivability of zombies → physicalism contingent |
| **The Chinese Room** | Searle 1980 | Can machines think? | Syntax insufficient for semantics |
| **Trolley / footbridge** | Foot 1967; Thomson 1976, 1985 | What makes killing wrong? | The doing/allowing distinction |
| **Frankfurt cases** | Frankfurt 1969 | Is PAP necessary for responsibility? | No |
| **The experience machine** | Nozick 1974 | What is well-being? | Not just hedonic state |
| **Twin Earth’s doppelgänger** | Burge 1979 | Is content fixed by the internal states? | Anti-individualism |
| **The ship of Theseus** | Ancient | What is persistence? | The problem of identity over time |
| **The statue and the lump** | Various | What is the relation of material constitution? | Coincident objects |
| **The woman without the concept** | Fricker 2007 | What is epistemic injustice? | Hermeneutical blind spots |

Each entry is a compressed debate. The table is worth comparing, in Ch. 2, §6, with the three classic arguments reconstructed there: a thought experiment is the *material* from which such arguments are built.

### 2.3 When is intuition evidence?

The central question is not whether thought experiments are *psychologically* compelling — they obviously are — but whether the intuitions they elicit are *epistemic* evidence for the conclusion.

Four major positions:

**(a) Conceptual competence** (Bealer 1992, 1999; Jackson 1998; Chalmers & Jackson 2001). Intuitions are the exercise of the *conceptual capacity*; to judge that a Gettier case is not knowledge is to exercise the very competence that constitutes mastery of the concept. Intuitions are therefore quasi-perceptual: they are the faculty by which we detect the structure of our concepts. On this view, the method of cases is as legitimate as perception — and in the same way.

*Objection*: the faculty of intuition looks like a *faculty-of-gap-filling*. We seem to have intuitions about everything — free will, the afterworld, the morality of cannibalism — including domains in which they are demonstrably unreliable. An epistemically clean faculty would not have this profile.

**(b) Modal intuition** (Chalmers 1996, 2009). Intuitions are a species of **conceivability**, and conceivability is evidence for **possibility** (Ch. 9, §5). The zombie is conceivable; if it is conceivable, it is metaphysically possible; if possible, physicalism is false. This is a claim about modal epistemology, and it is vulnerable at every step: the conceivability-possibility thesis is contestable (Kripkean essentialist replies; the two-dimensional framework that tries to reconcile it with a posteriori necessity).

**(c) The *seeming* model** (Huemer 2001, 2005; "phenomenal conservatism"). Intuitions are **seemings** — propositional attitudes with a distinctive phenomenology — and seemings provide *defeasible*, *default* justification. We are prima facie justified in believing what seems to be the case unless there is a defeater. This is the most modest and, many think, the most defensible account: it does not claim a special faculty, only a general principle of default justification, and it is widely used in epistemology (perception, memory, testimony treated analogously).

*Objection*: the principle is so permissive that it justifies almost anything, including conflicting intuitions. Some seemings *are* better than others, and the model needs a calibration story.

**(d) The deflationary model** (Norton 2004; Deutsch 2015). Thought experiments do not have a special evidential status at all. They are **arguments with suppressed premises**, and their epistemic warrant derives entirely from the validity of the argument and the truth of the premises. The intuition is a *symptom* of the argument’s conclusion, not its premise. On Norton’s account, a thought experiment is just argumentation in a vivid narrative dress — ordinary reasoning about empirical or conceptual matters, disguised as an experiment.

*Objection*: the deflationary account makes it hard to explain why *this* narrative, rather than *that*, generates the intuition; and it seems to make all thought experiments depend on general principles, whereas some intuitions seem to be *particular* (the Gettier intuition is about the case, not about a general principle).

**A pragmatic verdict.** For the working philosopher, the four positions are not mutually exclusive. Use the thought experiment to *generate* a hypothesis or a distinction (this is what any model does). Use it to *test* a theory against a case (this is what the method of cases does). But always do two things:

1. **Ask what the case has in common with the target question.** If the case is bizarre, the intuition may reflect *features of the case* rather than the concept.
2. **Extract the principle.** Ask: what general principle would make the intuition correct? Then assess the principle on its own merits. If the principle is false, the intuition is suspect; if the principle is true, the intuition is redundant.

This is the **principle-extraction heuristic**, and it converts an intuition into an argument, which is the only thing we know how to assess.

### 2.4 When intuition is noise

The empirical literature of the last two decades has established that intuitions are sensitive to factors irrelevant to truth. The main findings (with appropriate caution about the replication crisis, which applies here too):

| Effect | Description | Example | Source |
|---|---|---|---|
| **Framing** | Different descriptions of the same case elicit different judgments | The same trolley case, described in different words | Petrinovich & O’Neill 1996 |
| **Personal force** | Direct personal force in trolley cases shifts judgments | Footbridge vs. switch | Greene et al. 2001, 2009 |
| **Order** | Presentation order shifts judgments | Order effects on double-effect and action–omission cases | Schwitzgebel & Cushman 2012 |
| **Affect** | Emotional salience contaminates judgment | Disgust sensitivity and moral judgment | Schnall et al. 2008 (contested) |
| **Culture** | Cross-cultural variation in judgments | Gettier intuitions | Weinberg et al. 2001; see Machery et al. 2004 |
| **Expertise** | Experts may differ from novices | Free will/action cases | Knobe & Nichols 2008 |

The conclusion often drawn — that intuitions are worthless — is too strong. A better conclusion: **intuitions are defeasible data, and like all data they can be contaminated.** The calibration problem is to say which intuitions should be trusted, and there is no general answer. What is *not* acceptable is the naive practice of resting a heavy argument on a single vivid case without asking whether the case is representative, whether the framing is doing the work, and whether the performance would replicate.

**Dennett’s warning** is worth taking seriously: thought experiments are **intuition pumps** — devices for extracting intuitions by concentrating attention on some features and hiding others (Dennett 1984, *Elbow Room*, p. 12). A pump can pump up a conclusion; the question is whether the conclusion survives when the pump is turned off.

### 2.5 A worked example: why Gettier works

The Gettier cases have proved unusually robust. Why? Not merely because they are clever, but because **the intuition is underwritten by an argument the case makes salient.**

The standard structure (Smith and Jones, the job and the coins):

1. Smith has a well-justified belief that the man who will get the job has ten coins in his pocket. (Derived from evidence about Jones.)
2. In fact, Smith will get the job, and Smith has ten coins in his pocket.
3. So Smith’s belief — that "the man who will get the job has ten coins in his pocket" — is true (because of Smith, not Jones) and justified (by the evidence about Jones).
4. But Smith does not know it, because the justification is not *connected* to the truth.

The case works because it isolates a feature that our concept of knowledge clearly cares about: **the connection between justification and truth**. The intuition is not a bare "seeming"; it is a *response to the argument*, and the argument articulates the principle: *justification must be truth-tracking, not merely truth-adjacent.* This is why the Gettier cases have survived six decades of counterarguments and why they are cited in every epistemology course.

The methodological moral: **the best thought experiments wear their principles on their sleeves.** The worst ones conceal them. When you construct a case, ask what principle the case would need to be valid; when you are presented with one, ask the same question.

### Advanced thread: the metaphysics and epistemology of intuition

Three further issues, for the reader who wants to go deeper.

**1. Are intuitions sui generis states?** If intuition is a distinctive propositional attitude, it needs a distinctive epistemology. If it is just belief with a certain etiology (a product of conceptual competence, or of the imagination, or of the language faculty), then its epistemology is inherited from the broader theory of belief — which may be either good news (no weird faculty required) or bad news (no special warrant).

**2. The expertise defense.** If philosophy is a skill, then philosophical intuitions may be like chess intuitions: unreliable in novices, reliable in experts. Evidence for this is thin — expert philosophers disagree as much as novices (and the experts' intuitions are the ones that formed the disagreement in the first place). This is the **expertise problem** (Ch. 9, §6), and it connects to the problem of philosophical disagreement.

**3. The evolutionary defense.** If our cognitive faculties were shaped by selection for survival, they may be reliable about medium-sized objects and unreliable about the deep structure of reality (the "evolutionary argument against naturalism," Plantinga 1993, turns on this). The counter-argument, due to Street (2006) and echoed by others, is that the debunking cuts no more deeply against philosophy than against common sense — either way, our faculties are *conditionally* reliable. The debate is a useful template for the genealogy method in §5.

---

## 3. Formalization

### 3.1 What formalization buys

**Formalization** is the rendering of claims in a formal language with explicit syntax and a formal semantics. It is the most powerful and most misused instrument in philosophy. Its benefits:

| Benefit | Explanation | Example |
|---|---|---|
| **Perspicuity** | The logical structure becomes visible | The surface grammar of "the present King of France is bald" conceals a hidden quantifier |
| **Validity-checking** | Validity can be mechanically tested | Natural deduction, semantic tableaux |
| **Ambiguity-detection** | Scope ambiguities become explicit | "Everyone loves someone" — two structures |
| **Precision** | Claims become falsifiable | Probability axioms |
| **Unification** | Common structure across theories | The $\Box$ notation for necessity, obligation, and knowledge |

The paradigm case is **Russell’s theory of descriptions**. Before Russell, it was widely held that "the present King of France is bald" presupposes the existence of a King of France, and that the proposition is neither true nor false if there is none. Russell’s analysis showed that the sentence has a coherent logical form involving quantifiers and identity, and that it is simply **false** when the existential conjunct fails (Ch. 12, §2). This is a case where the formal representation did genuine philosophical work: it dissolved a puzzle that had persisted since Frege and Meinong.

### 3.2 The basic machinery

A compact statement of what a philosopher needs:

**Quantifiers and scope.** $\forall x$ (for all $x$), $\exists x$ (there exists an $x$). Identity $x = y$. Scope matters:

| English | Structure | Content |
|---|---|---|
| "Everyone loves someone" | $\forall x \exists y \, Lxy$ | Everyone has *some* beloved |
| "Someone is loved by everyone" | $\exists y \forall x \, Lxy$ | One person is universally beloved |

The two are not equivalent, and many confused arguments trade on the ambiguity.

**Modal operators.** $\Box p$ = "it is necessary that $p$"; $\Diamond p$ = "it is possible that $p$"; $\neg\Box\neg p$ is equivalent to $\Diamond p$. The semantics uses a **possible-worlds model**: a frame $\langle W, R \rangle$ with $W$ the set of worlds and $R$ the accessibility relation; $\Box p$ is true at $w$ iff $p$ is true at all $v$ such that $wRv$.

The standard systems and their philosophical interpretations:

| System | Characteristic axiom | Philosophical reading |
|---|---|---|
| **K** | $\Box(p \to q) \to (\Box p \to \Box q)$ | Minimal logic of necessity |
| **T** | $\Box p \to p$ | Necessity is factive (what is necessary is actual) |
| **S4** | $\Box p \to \Box\Box p$ | Positive introspection: necessity is itself necessary |
| **S5** | $\Diamond p \to \Box\Diamond p$ | Negative introspection: what is possible is necessarily possible |

**S5** is the standard logic for metaphysical modality, and it is what makes Plantinga’s modal ontological argument work (Ch. 2, §6.1). Note, though, that the *appropriateness* of S5 for metaphysical necessity is a substantive assumption; some philosophers defend weaker systems, and the question of which system models which notion is itself philosophical (Ch. 35, §3).

**Epistemic logic.** Treat $K_i p$ = "agent $i$ knows that $p$"; the semantics uses an accessibility relation representing epistemic alternatives (what the agent cannot rule out). The **axiom of factivity**, $K_i p \to p$, is knowledge’s defining mark: if you know it, it is true. The **KK principle** ($K_i p \to K_i K_i p$) is controversial; externalists deny it (Ch. 35, §3.2). This is a case where formal structure makes a philosophical dispute precise.

**Deontic logic.** $O p$ = "it is obligatory that $p$"; $\mathit{Perm}\,p$ = "it is permissible" (the $P$ below is reserved for probability). The standard system **KD** includes the *consistency* axiom $O p \to \neg O\neg p$ — the obligations do not conflict — and, on the reading of Ch. 35, §3.1, the *seriality* axiom $O p \to \mathit{Perm}\,p$: obligation implies permission. But the interaction with conditionals generates **contrary-to-duty obligations** (Chisholm’s paradox): what you ought to do given that you have already done wrong. The paradox has no uncontested solution, and it is a useful reminder that formalization can reveal problems as much as solve them.

**Probability.** The Kolmogorov axioms:

$$
P(\Omega) = 1, \qquad P(A) \geq 0, \qquad P(A \cup B) = P(A) + P(B) \text{ when } A \cap B = \emptyset
$$

Conditional probability and Bayes:

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \qquad P(H \mid E) = \frac{P(E \mid H)\, P(H)}{P(E)}
$$

with the denominator expanded by the law of total probability:

$$
P(E) = \sum_i P(E \mid H_i)\, P(H_i)
$$

This is the formal core of the Bayesian framework (Ch. 10, §4), and the reader who can manipulate these equations has access to most of modern formal epistemology.

### 3.3 When formalization obfuscates

The instrument has failure modes. The most important:

**(i) The pseudo-precision fallacy.** A formalism can make a claim *look* exact without making it *any more informative*. If the predicate letters are uninterpreted, or if the domain is unspecified, the notation adds nothing. The test: can you say, in English, what the formal sentence means? If not, the formalization is decorative.

**(ii) The translation problem.** Formal validity is validity *relative to a translation*. If the English sentence has been mistranslated, the formal proof proves nothing about the English argument. "If $p$ then $q$" in English is frequently not the material conditional: it may be a conditional assertion, a counterfactual, or a causal claim. The material conditional’s paradoxes — $p \to q$ is true whenever $p$ is false, so "if pigs fly, I’m the King of France" comes out true — are a warning, not a refutation: they show that English "if" is not captured by $\to$. (On conditionals, Ch. 37.)

**(iii) The formalization fallacy.** Invalidity in one formalization does not entail invalidity in the English argument. The argument may be valid in a different, better translation. This is the most common error in student papers: a student formalizes an argument using $\to$, finds the form invalid, and declares the argument fallacious, when the argument would be valid if formalized with a modal or relevant conditional.

**(iv) The loss of content problem.** Formalizations abstract away content. Sometimes the content is what matters. "Socrates is human; therefore Socrates is mortal" is valid in predicate logic only with the added premise. The formalization *hides* the substantive question (what makes a species mortal?) behind a logical one.

**(v) The complexity problem.** Some arguments are too complex to formalize usefully; the formalization becomes longer and less comprehensible than the prose. In such cases, argument mapping (§4 of Ch. 2) is the better instrument.

### 3.4 A rule of thumb

> **Formalize when the structure is contested, when the argument is long, or when quantifier scope or iterated modality is doing work. Do not formalize as a substitute for thought.**

The best formalizations earn their keep by *changing* the debate — by revealing a distinction, generating a countermodel, or proving a limitative result (Gödel, Tarski, Russell’s paradox). The worst are elaborate equations that restate the obvious in a language only the author can read.

---

## 4. Reflective Equilibrium

### 4.1 The method

**Reflective equilibrium** is a coherentist method of justification: we justify a set of beliefs by adjusting them, in mutual interaction, until they form a coherent system. The method was described by Nelson Goodman (1955) for inductive logic — "a rule is amended if it yields an inference we are unwilling to accept; an inference is rejected if it violates a rule we are unwilling to amend" — and developed by John Rawls (1971, §9; 1975) for ethics, from which it spread to epistemology, logic, and political philosophy.

The procedure, in its simplest form:

1. **Collect considered judgments**: particular judgments made in conditions of calm, with full information, without self-interest. ("Torturing a child for fun is wrong." "I know that I have hands when I see them in good light.")
2. **Collect principles**: general claims about the domain. ("Pain is prima facie bad." "Perception is a source of knowledge.")
3. **Compare**: does the principle explain the judgment? Does the judgment confirm the principle? Where they conflict, adjust *whichever* seems less secure, in either direction.
4. **Iterate**: repeat until equilibrium — a state in which every element is mutually supported, and no further adjustment improves the coherence of the whole.

The crucial feature is that **neither pole is foundational.** The particular judgments are not infallible data; the principles are not a priori axioms. Justification is holistic.

### 4.2 Narrow and wide

Rawls distinguished **narrow** from **wide** reflective equilibrium (1975). Narrow equilibrium is achieved within a limited set of judgments and principles in a single domain (say, principles of distributive justice). Wide equilibrium incorporates *background theories* — metaphysics, epistemology, psychology, the social sciences — and can overturn a narrow equilibrium.

The distinction is important because it shows the method is not merely conservative. If the background theory changes, the equilibrium can move. For example: a narrow equilibrium in ethics might treat "moral facts" as objective; a wide equilibrium that includes a naturalistic metaphysics may require a different account of moral judgment. The method is a *comparative* one: it tells you which configuration is more coherent, not which is absolute.

The distinction also generates a **hierarchy of methods**: a wide equilibrium has authority over a narrow one, but a wide equilibrium is itself revisable in the light of a yet wider framework. There is no final equilibrium; there are better and worse ones.

### 4.3 Objections and replies

**Objection 1: Conservatism.** The method begins with our pre-theoretic judgments, which are the products of history, culture, and bias. It therefore launders prejudice. (This is the standard critique of Rawls from communitarian and critical-theory quarters, Ch. 47.)

*Reply*: the method is not confined to *existing* judgments; it can be *wide*, and it can incorporate critique. The judgments that enter the equilibrium are **considered** judgments — filtered for ignorance, haste, and self-interest — and the filtering is itself a normative process. Moreover, the equilibrium is not static: a persistent incoherence can force revision of the judgments themselves. The method is conservative in its *starting point*, not in its *conclusion*.

**Objection 2: Indeterminacy.** There are many equilibria. Different starting points converge on different systems, and there is no guarantee of uniqueness. (This is a general problem for coherentism, Ch. 8, §3.)

*Reply*: uniqueness is not required for justification. What the method provides is **comparative** justification: this system is more coherent than that one. The fact that there are multiple coherent systems is a fact about the difficulty of the domain, not a defect of the method. (The "no-contact-with-reality" objection is the standard worry for all coherence theories, and it is most acute for a purely coherentist reading of reflective equilibrium. The Rawlsian and post-Rawlsian literature has largely accepted that the method is not purely coherentist — it involves *constraints of plausibility* on the inputs.)

**Objection 3: Whose judgments?** The "we" whose considered judgments are consulted is a specific, historically situated community. The method may be a local truth-machine. This is the **parochialism objection**, and it connects to the epistemic critique in Ch. 11 (epistemic injustice) and Ch. 13 (relativism).

*Reply*: this is the strongest objection, and it has no knock-down answer. The best defense is procedural: ensure the judgments consulted come from a *diverse* set of perspectives, and treat the equilibrium as provisionally open to revision. The method is fallible, and its fallibility is a contingent matter of who is doing the equilibrating.

**Objection 4: Equilibrium is a myth.** In practice, philosophers do not equilibrate; they begin with a favored theory and adjust the judgments to fit. The method is a rationalization of intuition-mongering, not a constraint on it.

*Reply*: this is an empirical claim about philosophical practice, and it is partly true. It is also an argument for self-discipline, not against the method. The remedy is the *philosophical diary* (Ch. 4, §5): record your judgments *before* you have a theory, so you can tell whether the theory is adjusting them.

### 4.4 A worked example: the trolley and the footbridge

The standard case:

- **Switch**: A runaway trolley will kill five people. You can pull a switch to divert it onto a siding where it will kill one. Most people say: pull the switch.
- **Footbridge**: A runaway trolley will kill five people. You are on a footbridge next to a large man. The only way to stop the trolley is to push him off; he will die, the five will be saved. Most people say: do not push.

The two cases are structurally similar (kill one to save five) and intuitively divergent. The method of reflective equilibrium tries to find a principle that **generates both** judgments (or that explains why one of the judgments is wrong).

The candidate principles:

| Principle | Explains the switch verdict? | Explains the footbridge verdict? | Problem |
|---|---|---|---|
| **Maximize welfare** | Yes | No | Predicts push |
| **Doing/allowing** | Yes | Yes | Is the distinction morally fundamental? |
| **Intention/foresight (DDE)** | Yes | Yes | Controversial in its application |
| **Personal force** | Yes | Yes | Anti-consequentialist; empirical basis |
| **Rights (no using persons merely as means)** | Yes | Yes | Needs independent argument |

The equilibrium process does not simply *find* the answer; it *tests* each principle against both judgments and against the background theory. A principle that explains the switch but not the footbridge is *less coherent* than one that explains both — but a principle that explains both may be *less plausible* independently. The equilibrium is the best overall configuration.

The lesson, for the method: **reflective equilibrium is a method of comparative theory choice, not a machine for producing moral truth.** It tells you which configuration is most coherent; it does not tell you that the most coherent configuration is the true one. (Whether coherence is a guide to truth is the central question of Ch. 8, §3.)

---

## 5. Genealogy and Debunking

### 5.1 What genealogy is

**Genealogy** is the practice of explaining the *origin* and *function* of a belief, concept, or practice, and using that explanation to assess its epistemic or normative standing. Its paradigm cases are Nietzsche’s *On the Genealogy of Morality* (1887), Foucault’s histories of madness, punishment, and sexuality, and — in analytic philosophy — the "state of nature" narratives of Hobbes, Rousseau, and (in a different register) the evolutionary explanations of morality in Joyce, Street, and Kitcher.

The method’s structure is a **debunking argument**:

$$
\begin{array}{ll}
1. & \text{S’s belief that } p \text{ is produced by process } X. \\
2. & X \text{ is not truth-conducive with respect to } p \text{ (the belief would be held whether or not } p\text{).} \\
\hline
3. & \therefore \text{S’s belief is not justified (or: its justification is undermined).}
\end{array}
$$

The crucial premise is 2. The mere fact that a belief has a natural history is irrelevant to its truth; to conclude otherwise is the **genetic fallacy**. What matters is whether the history is **truth-tracking**. A belief formed by a process that would have produced it regardless of the truth is a belief without warrant, whatever its origin.

### 5.2 The debunking map

| Domain | Debunking strategy | Key figures | Status |
|---|---|---|---|
| **Morality** | Evolutionary explanation of moral beliefs without truth-tracking | Joyce 2001, 2006; Street 2006 | Live; see Ch. 44, §6 |
| **Religion** | Cognitive science of religion; by-product explanations | Barrett, Boyer, Atran | Live but contested |
| **Free will** | Situationism, Libet, predictive processing | Nelkin, Vargas; Libet 1983 | Live; see Ch. 27, §7 |
| **Mathematics** | Benacerraf’s access problem; indispensability | Benacerraf 1973 | Live; see Ch. 43 |
| **Naturalism** | Evolutionary argument against naturalism | Plantinga 1993 | Very contested |
| **Consciousness** | Illusionism: the hard problem is a meta-problem | Frankish 2016 | Live; see Ch. 24, §5 |
| **Knowledge** | Experimentalist debunking of intuition | Weinberg et al. 2001 | Contested |

The map is useful because it shows how *portable* the debunking argument is. If the moral realist can be debunked by evolution, so can the mathematician by Benacerraf, and so can the naturalist by Plantinga. The **companions-in-guilt** response (Ch. 44, §5) is the standard defense: if the debunking argument proves too much, it proves nothing.

### 5.3 The conditions for a successful debunking

A debunking argument succeeds only if:

1. **The empirical premise is true.** The genetic story must be well-supported. (Nietzsche’s genealogies are imaginative reconstructions, not history; their authority is rhetorical and diagnostic, not empirical. This is a real weakness, and it must be acknowledged.)
2. **The process is insensitive to truth.** It is not enough that the belief has a function; the function must be independent of truth. (A belief can have a survival function *and* be true; the debunking requires that the belief would be held even if false.)
3. **The scope is right.** A *local* debunking — one that targets a single faculty or domain, say our intuitions about free will — leaves the rest of our beliefs standing; but if the process is unreliable in general, the debunking is *global*, and then it threatens the debunker’s own beliefs (the self-defeat problem, §5.5). A successful debunking is therefore *targeted*: general enough to bite on the target belief, narrow enough to spare the debunker.
4. **No independent justification survives.** If the belief can be supported by other, independent evidence, the debunking of one route to it does not undermine the belief. This is the **independent-justification reply**, and it is the most common response to debunking arguments in ethics.

### 5.4 What genealogy can legitimately do

Even when it does not debunk, genealogy has real philosophical uses:

**(i) Contingency.** It can show that a belief or practice is not *necessary* — that it was otherwise, that it arose at a particular time, that it could be otherwise. This is the use Foucault makes of history: not to refute a practice, but to denaturalize it. The value is real: the sense that our arrangements are inevitable is one of the strongest barriers to criticism.

**(ii) Function.** It can show that a belief serves a purpose unrelated to its truth — social cohesion, the legitimation of power, the management of anxiety. This is not yet a debunking, but it raises the question: *is there any reason to think the belief is also true?*

**(iii) Self-image.** It can reveal that a philosopher’s own conception of his activity is at odds with the history of his discipline. This is Nietzsche’s use against the ascetic ideal, and it is a useful diagnostic against complacent rationalism.

**(iv) The genealogy as a *conditional* argument.** "If the empirical story is right, then the belief is undermined" is a conditional, and it can be valuable even if the antecedent is uncertain: it shows what *turns* on the empirical question, and it disciplines the empirical inquiry.

### 5.5 The dangers

**(i) The genealogical fallacy.** Explaining a belief is not refuting it. The history of a belief may be sordid and the belief true.

**(ii) The selective-debunking fallacy.** Debunking arguments are usually applied selectively, to beliefs the debunker dislikes. The principled application would debunk everything that shares the undermined process. The companions-in-guilt argument is the formal statement of this worry, and it is powerful.

**(iii) The speculative-empirics problem.** Many genealogies are presented with the authority of science but rest on speculation. The reader should always ask: what is the *evidence* for the genetic story, and how strong is it really?

**(iv) The self-defeat problem.** A genealogy that debunks *all* beliefs (including the belief in the genealogy) is self-undermining. This is not necessarily fatal — a *local* debunking can be acceptable while a *global* one is not — but it must be handled explicitly.

---

## 6. Phenomenology, Ordinary Language, and Experimental Philosophy

### 6.1 Phenomenology

**Phenomenology** is the descriptive study of *lived experience* — of how things appear, from the first-person perspective, prior to theoretical interpretation. Its founders (Husserl, *Ideas* 1913) proposed a method of **epoché**: the suspension of the "natural attitude" (the assumption that the world is as it seems) in order to describe the *phenomena* themselves.

The phenomenological contribution to philosophy is substantial:

- The structure of **intentionality** (Ch. 25, §1): experience is *of* something; the object-directedness of consciousness is a datum that any theory of mind must explain.
- The **phenomenology of agency**: the felt sense of "I could have done otherwise" (Ch. 27, §1), the experience of deliberation, the sense of effort.
- The **lived body** (Merleau-Ponty, *Phenomenology of Perception* 1945): the body is not an object in the world but the medium of our access to it. This is a standing corrective to Cartesian dualism and to computational theories of mind that neglect embodiment (Ch. 30, §4).
- The **phenomenology of the social world** (Husserl, Schutz): the constitution of the other, the structure of empathy, the "lifeworld."

**Limits.** First-person descriptions are not intersubjectively checkable in the way that empirical data are; they are theory-laden through and through; and the classic **phenomenological fallacy** (the object as it appears vs. the object as it is in itself) is a standing temptation. The method is best used as *constraint* rather than *proof*: a theory that cannot accommodate the experienced character of mental life is in trouble, but the experience does not by itself adjudicate between theories.

### 6.2 Ordinary language philosophy

The **ordinary language** tradition (Austin, Ryle, the later Wittgenstein, and the Oxford school of the 1950s and 60s) proposes that the distinctions embedded in everyday language are a rich source of philosophical data. The method: examine how a word is used in its ordinary contexts; observe the distinctions it encodes; test philosophical theories against those distinctions.

The paradigm is Austin’s *Sense and Sensibilia* (1962), which is a sustained examination of the claim that "we never perceive material objects." Austin shows that the argument from illusion trades on a crude picture of perception, and that the ordinary vocabulary of "looks," "seems," "appears," and "is" encodes distinctions that the theory ignores. Ryle’s *The Concept of Mind* (1949) is the same method applied to the mind–body problem: the "ghost in the machine" is a category mistake, and the way to see the mistake is to examine how mental predicates are actually used (Ch. 23, §1).

**Achievements**: speech-act theory (Ch. 34), the analysis of knowledge attributions, the "looks/seems/appears" distinction, the theory of excuses, the concept of performative contradiction.

**Limits.**

1. **Ordinary language encodes ordinary prejudices.** The vocabulary of a community reflects its history and its power relations. The feminist critique of ordinary-language philosophy (and of the "we" it invokes) is decisive on this point.
2. **Technical terms are legitimate.** The philosopher may need a concept that ordinary language does not have. "Supervenience," "de re," "ceteris paribus" — these are not ordinary words, and the fact that they are not is not an objection.
3. **The ordinary-language fallacy.** One cannot infer a metaphysical conclusion from a grammatical fact. The fact that we say "I have a pain" rather than "there is a pain in my leg" does not settle whether pains are objects, states, or processes. (This is the methodological version of the *is–ought* gap: linguistic facts constrain theories but do not entail them.)
4. **The linguistic-idealist worry.** A method that says "what we say is the measure of what there is" can slide into the view that language constitutes reality. This is a caricature of the tradition, but it is not a straw man: some of its practitioners have flirted with it.

The best use of the method is **diagnostic**: ordinary usage is evidence of distinctions we tacitly draw, and a theory that cannot accommodate them needs to say why. This is the "constraint" model, and it is more defensible than the "authority" model.

### 6.3 Experimental philosophy

**Experimental philosophy** (x-phi) uses empirical methods — surveys, reaction-time studies, and (increasingly) field experiments — to investigate the intuitions on which philosophy relies. It has two programs:

- **The negative program**: demonstrate that philosophical intuitions are unreliable (context-sensitive, culturally variable, affective, order-dependent). If the intuitions that underpin the method of cases are unreliable, the method of cases is in trouble.
- **The positive program**: use empirical data to *do* philosophy — to discover the structure of concepts, to map the diversity of intuitions, to test whether philosophical theories match actual practice.

The positive program has produced striking results. The **Knobe effect** (2003): people are more inclined to say that a side effect was brought about "intentionally" when it is bad than when it is good. The finding has been replicated across ages and, though less uniformly, across cultures, and it has generated a large literature on the "folk concept of intentional action" (Ch. 18, §5.2). The **epistemic side-effect effect** (Beebe & Buckwalter 2010) and the **folk concept of knowledge** are further examples.

The negative program is more contentious. The early cross-cultural studies (Weinberg, Nichols, Stich 2001; Machery, Mallon, Nichols, Stich 2004) suggested that Gettier intuitions and reference intuitions vary by culture. Later work complicated the picture: some findings failed to replicate (Seyedsayamdost 2015), and the interpretation of the results is contested (is the variation due to "culture" or to confounds?). The **replication crisis** in psychology has hit x-phi as well, and the field is now more cautious than it was in 2005.

**The philosophical assessment.** Even if the empirical results are robust, three questions remain:

1. **Do the results undermine the *method*, or only some *applications* of it?** If intuitions vary, we need a *calibration* story — not an abandonment of cases.
2. **Whose intuitions matter?** If expert intuitions differ from novice intuitions, which are authoritative? (The expertise defense.)
3. **Are the *data* about concepts or about *theories of* concepts?** A survey question is an operationalization, and the operationalization may not capture the target.

The most defensible position is a **methodological pluralism**: use intuition as a fallible source of data, use empirical work to calibrate it, and use argument to adjudicate when intuitions conflict. The reader should be suspicious of both the "x-phi refutes the armchair" and the "x-phi is irrelevant" poles.

### 6.4 The three methods compared

| Method | Data | Strength | Weakness |
|---|---|---|---|
| **Phenomenology** | First-person experience | Richness; constrains theory | Not intersubjectively checkable; theory-laden |
| **Ordinary language** | Usage patterns | Subtle distinctions; empirical | Encodes prejudice; not authoritative |
| **Experimental philosophy** | Survey data | Quantifiable; replicable (in principle) | Construct validity; cultural bias; replication crisis |

The lesson of the last two decades is **triangulation**: no single method is authoritative, and the best work uses all three, with explicit attention to their limits. This is not a counsel of despair; it is a counsel of humility.

---

## 7. Negative Capability: Dissolving Problems

### 7.1 The concept

In a letter of December 1817, John Keats wrote of the quality that makes a "Man of Achievement":

> “…that is, when a man is capable of being in uncertainties, mysteries, doubts, without any irritable reaching after fact and reason.”

**Negative capability** is the capacity to tolerate unresolved tension without forcing a resolution. In philosophy it names a technique as well as a virtue: the technique of *dissolving* a problem rather than solving it — showing that the question, as posed, rests on an assumption that need not be accepted, so that the question loses its grip.

The technique is associated with Wittgenstein, who described the aim of philosophy as "showing the fly the way out of the fly-bottle" (*PI* §309). But it is not uniquely Wittgensteinian: it is the method of Kant’s first *Critique* (dissolving the antinomies by distinguishing phenomena from things in themselves), of Ryle’s category-mistake diagnosis, of the logical positivists’ rejection of metaphysics, and of a great deal of ordinary-language philosophy.

### 7.2 The technique

The mechanics of dissolution:

1. **Identify the presupposition**: what does the question assume? (That the will is an agent; that knowledge is a mental state; that moral judgments encode facts; that there is a "hard problem.")
2. **Show that the presupposition is optional** — that the question’s grip depends on a framework that can be abandoned — or false, if it is.
3. **Offer a re-description** in which the question does not arise and the phenomena are still accounted for.
4. **Explain why the question *seemed* compelling**, which is the test of a good dissolution (§7.4).

The best dissolutions do not merely change the subject; they explain the *phenomenology of the old question* — why it looked unanswerable, why the alternatives seemed exhaustive.

### 7.3 Case studies

**The problem of the external world.** The classical question — how can I know that there is a world outside my mind? — presupposes that my knowledge of the external world is inferential, based on the "given." The dissolution (Wittgenstein, *On Certainty*; and the hinge-epistemology literature, Ch. 6, §6.5) is that the existence of the world is not a *proposition* I believe on evidence; it is a condition of the language-game of asking and answering questions. You cannot doubt everything at once, because doubt requires a framework of certainties. The question therefore has no application: it is not that we cannot know, but that the demand for justification does not make sense at the limit.

**The problem of other minds.** The classical question — how can I know that other people have minds? — presupposes an inferential model: I know my own mind directly, and I infer yours by analogy. The dissolution (the direct-perception view; Ch. 29, §1) is that we *see* that others are in pain: the inference is not needed, and the analogical inference is a bad account of how we actually come to know. The problem is generated by a theory of first-person knowledge, and it dissolves when the theory is replaced.

**The problem of free will** (a partial dissolution). The classical problem — how can determinism be reconciled with the ability to do otherwise? — may rest on a conception of "could have done otherwise" that is not required for responsibility. Strawson’s *Freedom and Resentment* (1962) dissolves the *theoretical* question by showing that the practice of holding responsible is grounded in reactive attitudes, not in a metaphysical fact about the will (Ch. 27, §8). Whether the dissolution succeeds is contested, but the structure is instructive: the question is replaced by a question about the practice.

**The mind–body problem** (a contested dissolution). Ryle’s ghost in the machine; the Churchlands’ eliminativism; the "phenomenal concepts" strategy. Each is a dissolution attempt, and each is contested at the point where it explains away the apparent datum.

### 7.4 The test of a good dissolution

> **A dissolution must explain the phenomenon it dissolves.** It must say why the question seemed compelling, and why the alternatives seemed exhaustive. If the dissolution simply denies the datum, it is not a dissolution; it is a denial.

This is the criterion that separates the great dissolutions from the cheap ones. Wittgenstein on the private language argument is a dissolution that (whatever its merits) *explains* why we think we have private experiences. Ryle on the mind is a dissolution that *explains* why we talk about the mind as we do. A cheap dissolution — "that’s just a confusion" — explains nothing and persuades no one.

### 7.5 Negative capability as a virtue

There is a second, more personal use of the term. Philosophy requires the ability to **hold a question open** — to work on it without forcing a premature answer. The pressure to resolve is strong: it is the pressure of the seminar paper, the examination, the publication, and the ego. Negative capability is the counter-pressure.

The virtue has three components:

1. **Tolerating uncertainty** without pretending to a certainty you do not have.
2. **Holding multiple hypotheses** simultaneously, and testing them against each other.
3. **Resisting the "irritable reaching"** for a conclusion when the evidence does not support one.

This is not relativism or quietism. It is the discipline of *not knowing what you do not know* — which is, as Socrates noticed, the beginning of wisdom. The vices it opposes — premature closure, false precision, the anxious need for a verdict — are perhaps the most common intellectual vices in philosophy.

### 7.6 The taxonomy of outcomes

We can now distinguish five fates that a philosophical question can meet. The taxonomy is useful for keeping score, and for avoiding the false dichotomy between "solved" and "unresolved."

| Outcome | What it is | Example | Sign of success |
|---|---|---|---|
| **Solved** | A correct answer is established | The analysis of definite descriptions (arguably) | Consensus, or near-consensus, among the informed |
| **Dissolved** | The question is shown not to arise | The external-world problem on hinge epistemology | The question loses its grip; the old alternatives seem unmotivated |
| **Reframed** | The question is transformed into a better one | From "What is knowledge?" to "What is the structure of epistemic justification?" | The new question is more tractable and more fruitful |
| **Deferred** | The question is well-posed but not yet answerable | "Is consciousness physical?" | A clear research program remains |
| **Abandoned** | The question is not worth pursuing | "How many angels can dance on a pin?" | A reason to think the question rests on false presuppositions or lacks import |

The taxonomy is not an algorithm. Reasonable philosophers will disagree about which category a given question falls into — and that disagreement is itself philosophical. But the taxonomy has the virtue of forcing the question: *what kind of progress have we made?*

---

## 8. Synthesis: The Instrument Panel

The seven instruments are not alternatives; they are aspects of a single activity. The following table summarizes when to use which, and what each can and cannot do.

| Instrument | Best used when | Cannot deliver | Characteristic failure |
|---|---|---|---|
| **Conceptual analysis** | The concept is functional, normative, or formal; you need to know what you are arguing about | Empirical knowledge of natural kinds | Ad hocness; the paradox of analysis |
| **Thought experiments** | Testing a theory against cases; exposing a hidden principle | Certainty; modal knowledge by itself | Intuition is contaminated |
| **Formalization** | Structure is contested; scope or modality is doing work; validity is doubtful | Content; interpretation; translation | Pseudo-precision; translation fallacy |
| **Reflective equilibrium** | Theory and judgment conflict; you need a comparative justification | A foundation; a unique answer | Conservatism; indeterminacy; parochialism |
| **Genealogy** | A belief’s authority is at issue; naturalism is in the background | A refutation by itself | The genetic fallacy; selective debunking |
| **Phenomenology / ordinary language / x-phi** | First-person data, usage, or empirical intuitions are relevant | Authority; metaphysical conclusions | Phenomenological fallacy; parochialism; replication |
| **Negative capability** | The problem may be a pseudo-problem; or the answer is not yet available | The answer itself | Evasion; quietism |

### 8.1 A worked case: the analysis of knowledge, all instruments at once

To see the instruments working together, consider the question *What is knowledge?*

1. **Conceptual analysis** (§1) proposes the classical analysis: JTB. It survives for two millennia.
2. **Thought experiments** (§2) produce Gettier cases, which refute it. The intuition is tested and articulated into a principle.
3. **Formalization** (§3) can clarify the structure of the Gettier cases — the belief and its inferential structure, the scope of the existential, the relation between justification and truth — though the case can be stated in English.
4. **Reflective equilibrium** (§4) is used to choose among the post-Gettier analyses: the judgments about a hundred cases and the principles (safety, sensitivity, no defeaters) are adjusted until they cohere.
5. **Genealogy** (§5) asks whether our concept of knowledge serves a function — perhaps the function of marking out reliable informants (Craig 1990) — and whether that function explains the structure of the concept.
6. **Phenomenology, ordinary language, x-phi** (§6) examine whether the folk concept of knowledge matches the philosophical one; whether "knows" is context-sensitive; whether the intuitions vary across cultures.
7. **Negative capability** (§7) asks whether the question is well-posed at all — whether the Gettier industry is chasing a concept that is essentially contested, or whether the "analysis of knowledge" is a pseudo-problem bequeathed by a particular tradition (the "knowledge-first" critique, Ch. 7, §4).

No single instrument settles the question. The *convergence* of the instruments is what we have instead of a proof — and it is a great deal more than nothing.

### 8.2 The meta-method

The deepest lesson of this chapter is that **there is no master method.** Philosophy has no algorithm. It has a set of tools, a set of virtues (clarity, honesty, charity, negative capability), and a community of practice that tests the tools against the hardest cases. The tools are fallible; the virtues are demanding; the community is imperfect. But the combination is the best we have — and it is a genuine form of knowledge-production, even if it is not the form we find in the sciences.

The reader who has absorbed this chapter is in a position to *use* the tools, and — more importantly — to *recognize* when they are being used badly. That is the beginning of philosophical independence.

---

## Summary

- **Conceptual analysis** seeks necessary and sufficient conditions. Its criteria are extensional adequacy, informativity, non-circularity, simplicity, explanatory power, and conservatism. It faces the paradox of analysis, the challenge from family resemblance, semantic externalism, Quinean holism, and experimental philosophy. The classical model survives as one instrument among others.
- **Thought experiments** test concepts and theories against cases. The four accounts of their evidential status — conceptual competence, modal intuition, seeming, and deflationism — disagree about *why* they work. The best practice is the **principle-extraction heuristic**: articulate the principle that would make the intuition correct, and assess the principle on its own merits.
- **Formalization** brings perspicuity, validity-checking, and precision, but it is vulnerable to pseudo-precision, the translation problem, and the formalization fallacy. Formalize when structure is contested; never as a substitute for thought.
- **Reflective equilibrium** justifies beliefs by coherence among considered judgments and principles. It can be narrow or wide, and width matters. It faces the objections of conservatism, indeterminacy, and parochialism, none of which is decisive but none of which is trivial.
- **Genealogy** explains the origin of beliefs in order to assess their authority. Its logic is the debunking argument, which requires (i) the empirical premise, (ii) truth-insensitivity, (iii) a scope that bites on the target without undermining the debunker, and (iv) the absence of independent justification. Its dangers are the genetic fallacy, selective debunking, speculative empirics, and self-defeat.
- **Phenomenology, ordinary language, and experimental philosophy** supply three kinds of empirical-adjacent data. Each is fallible in a characteristic way; the right practice is **triangulation**.
- **Negative capability** is the technique of dissolving a problem rather than solving it, and the virtue of tolerating uncertainty without forcing a verdict. A good dissolution must explain why the problem seemed compelling. Its vice is evasion.
- **No single instrument is authoritative.** The convergence of instruments is the substitute for proof, and the *taxonomy of outcomes* — solved, dissolved, reframed, deferred, abandoned — is the honest way to keep score.

---

## Study Questions

1. Give a concept that you believe has no classical analysis, and explain what kind of structure it has instead. Does the absence of necessary and sufficient conditions show that the concept is defective, or only that it is not classical?
2. Is the paradox of analysis a genuine problem, or a confusion about what analysis is for? How would you answer it?
3. Construct a thought experiment of your own to test a philosophical analysis. Then extract the principle that would make the intuition correct, and assess the principle. Does the intuition survive the assessment?
4. Is the experimental philosophy critique of the method of cases a *reductio* of the method, or a *calibration* of it? What would the calibration story look like?
5. Formalize one of the arguments in Ch. 2. Then produce a second formalization that renders the argument valid, if possible. What did the exercise teach you about the translation problem?
6. Are reflective equilibrium and conceptual analysis the same method under different descriptions? If not, what work does each do that the other cannot?
7. Apply the debunking schema to a belief you hold. Is the debunking successful? What would have to be true for it to be successful? (This is the hardest question in the chapter, and it is meant to be.)
8. When is a dissolution of a problem legitimate, and when is it evasion? Give an example of each, and state the criterion that distinguishes them.
9. Can a philosophy that is *only* negative capability — all dissolution, no construction — be a complete philosophy? What would it be missing?
10. "The instruments of analysis are instruments of clarification, not of discovery; they cannot tell us anything new about the world." Assess this claim in the light of the chapter.

---

## Further Reading

- **On conceptual analysis**: Frank Jackson, *From Metaphysics to Ethics* (1998), Chs. 2–3, for the defense; Max Deutsch, *The Myth of the Intuitive* (2015), for the critique; David Chalmers and Frank Jackson, "Conceptual Analysis and Reductive Explanation" (2001), for the two-dimensional framework.
- **On explication and engineering**: Rudolf Carnap, *Logical Foundations of Probability* (1950), Ch. 1; Sally Haslanger, *Resisting Reality* (2012), Chs. 1–2; Herman Cappelen, *Fixing Language* (2018).
- **On thought experiments**: James Robert Brown, *The Laboratory of the Mind* (1991), for the Platonist view; John Norton, "Why Thought Experiments Do Not Transcend Empiricism" (2004), for the deflationary view; Tamar Szabó Gendler, *Intuition, Imagination, and Philosophical Methodology* (2010), for the middle ground; Laurence BonJour, *Epistemic Angst* (2001), on the parrot case; Daniel Dennett, *Elbow Room* (1984), p. 12, on intuition pumps.
- **On the Gettier case**: Edmund Gettier, "Is Justified True Belief Knowledge?" (1963); the symposium in *Analysis* 23 (June 1963) and the subsequent literature; Linda Zagzebski, "The Inescapability of Gettier Problems" (1994), for the general lesson.
- **On formalization**: Graham Priest, *Logic: A Very Short Introduction* (2000); Theodore Sider, *Logic for Philosophy* (2010); Graham Priest, *An Introduction to Non-Classical Logic* (2nd ed., 2008), for the alternatives to classical logic.
- **On reflective equilibrium**: John Rawls, *A Theory of Justice* (1971), §9, and "The Independence of Moral Theory" (1975); Nelson Goodman, *Fact, Fiction, and Forecast* (1955), pp. 63–68; Norman Daniels, "Wide Reflective Equilibrium and Theory Acceptance in Ethics" (1979); the *Stanford Encyclopedia* entry, "Reflective Equilibrium" (Knight), for the survey of objections.
- **On genealogy and debunking**: Friedrich Nietzsche, *On the Genealogy of Morality* (1887); Richard Joyce, *The Evolution of Morality* (2006), and Sharon Street, "A Darwinian Dilemma for Realist Theories of Value" (2006); Guy Kahane, "Evolutionary Debunking Arguments" (2011), for the survey; Alvin Plantinga, *Warrant and Proper Function* (1993), Ch. 12, for the evolutionary argument against naturalism.
- **On phenomenology**: Edmund Husserl, *Ideas Pertaining to a Pure Phenomenology* (1913), §§27–35; Maurice Merleau-Ponty, *Phenomenology of Perception* (1945); Shaun Gallagher and Dan Zahavi, *The Phenomenological Mind* (3rd ed., 2020).
- **On ordinary language**: J. L. Austin, *Sense and Sensibilia* (1962), and *How to Do Things with Words* (1962); Gilbert Ryle, *The Concept of Mind* (1949); Wittgenstein, *Philosophical Investigations* (1953), §§1–100, 109–133, 200–242.
- **On experimental philosophy**: Joshua Knobe and Shaun Nichols (eds.), *Experimental Philosophy* (2008); Jonathan Weinberg, Shaun Nichols, and Stephen Stich, "Normativity and Epistemic Intuitions" (2001); Edouard Machery et al., "Semantics, Cross-Cultural Style" (2004); the replication discussion in *Review of Philosophy and Psychology* (2015) and *Analysis* (2016).
- **On dissolution**: Wittgenstein, *Philosophical Investigations*, §§308–309, 654–655; *On Certainty* (1969), §§1–65; Stanley Cavell, *The Claim of Reason* (1979), for the deep reading; P. M. S. Hacker, *Insight and Illusion* (1972), for the exegesis.

---

> *A closing note.* The instruments of analysis are not a recipe. They are a repertoire, and the master skill is judgment: knowing which tool the problem calls for, and knowing when to put the tools down. That judgment is not taught by any chapter; it is acquired by practice, by reading good philosophy, and by making mistakes in public. The next chapter turns to that practice — how to read, how to write, and how to be honest while doing both.
