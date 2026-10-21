# Chapter 33 — Paradox, Vagueness, and the Limits of Concepts

> “This sentence is false.”
> — the Liar, in its plainest form

> “One cannot step into the same river twice, for fresh waters are ever flowing in upon you.”
> — Heraclitus, fragment DK B12, the earliest statement of vagueness, or of something worse

> “The limits of my language mean the limits of my world.”
> — Ludwig Wittgenstein, *Tractatus Logico-Philosophicus* (1921), §5.6

---

Chapter 32 examined *truth*, and it *ended* with a *question* that the *theory* of *truth* *cannot* *avoid*: the **Liar**. The sentence “this sentence is false” is, by the *Tarskian* *schema*, *both* *true* and *false*, and the *schema* that *defines* the *truth* *predicate* *generates* the *contradiction*.

This chapter examines the *paradox* and its *family*. The *paradoxes* are *not* a *quirk* of the *truth* *predicate*; they are a *symptom* of the *limits* of *concepts* — of the *boundaries* that *every* *concept* has, and that *cannot* be *drawn* *without* *generating* a *contradiction* or a *sorites*. The *limit* is the *condition* of the *concept*, and the *paradoxes* are the *place* where the *condition* becomes *visible*.

The chapter's *thesis* is that the *paradoxes* are *real*, that the *solutions* are *all* *costly*, and that the *most* *important* *philosophical* *response* is *not* a *solution* but a *diagnosis* — the *recognition* that *some* *concepts* are *essentially* *contested* (Ch. 1, §6), that *some* *boundaries* are *vague* (Ch. 31, §5), and that *some* *concepts* are *revisable* (the *conceptual* *engineering* *programme*). The *diagnostic* *method* is the *most* *important* *tool* in the *philosophy* of *language*, and it is the *subject* of the *second* *half* of the *chapter*.

The chapter proceeds in eight movements. §1 states the *family* of *paradoxes*. §2 examines the *semantic* *solutions*. §3 examines *vagueness* and *higher*-*order* *vagueness*. §4 examines the *diagnostic* *toolkit*. §5 examines *conceptual* *engineering*. §6 examines the *limits* of *thought*. §7 examines the *ethics* of *concepts*. §8 gives an *honest* *verdict*.

---

## 1. The Family of Paradoxes

### 1.1 The Liar

**The *paradox*** (Eubulides, 4th c. BCE; the *Epimenides*; the *medieval* *insolubilia*; the *contemporary* *literature*).

**The *sentence***. Let $L$ be the sentence:

> “$L$ is false.”

**The *Tarskian* *schema***. For any *sentence* $S$ with *content* $p$:

$$
(\mathrm{T}) \quad T(\ulcorner S \urcorner) \leftrightarrow p
$$

**The *derivation***. Apply (T) to $L$, whose *content* is $\neg T(\ulcorner L \urcorner)$:

$$
(\mathrm{L}) \quad T(\ulcorner L \urcorner) \leftrightarrow \neg T(\ulcorner L \urcorner)
$$

**The *contradiction***. $p \leftrightarrow \neg p$ is *classically* *unsatisfiable*: the *schema* *assigns* the *sentence* *both* *truth* *values*, and the *principle* of *bivalence* is *violated*.

**The *paradox***. The *derivation* *uses* only the *Tarskian* *schema* (the *definition* of *truth*) and *classical* *logic*. The *schema* is *the* *most* *incontrovertible* *principle* of *semantics*, and the *logic* is *the* *most* *incontrovertible* *principle* of *reasoning*. The *two* *generate* the *contradiction*, and *neither* can be *rejected* *without* *cost*.

**The *significance***. The *paradox* is *not* a *puzzle* about a *bizarre* *sentence*. It is a *proof* that the *classical* *semantics* (the *Tarskian* *schema* + the *classical* *logic*) is *inconsistent* when *applied* to a *language* that *contains* its *own* *truth* *predicate*. The *significance* is *systemic*: the *inconsistency* *threatens* the *whole* *semantics* (Ch. 32, §5).

### 1.2 The family

**The *family* of *paradoxes* is *large*, and the *members* *differ* in their *structure*.

| Paradox | The *sentence* *form* | The *mechanism* |
|---|---|---|
| **Liar** | “This sentence is false” | The *negation* of the *truth* *predicate* |
| **Strengthened Liar** | “This sentence is not true” | The *negation* of the *truth* *predicate* (the *“not”* *attaches* to *truth*) |
| **Truth-teller** | “This sentence is true” | The *unconstrained* *truth* *predicate* (both *true* and *false* are *consistent*) |
| **Curry** | “If this sentence is true, then $p$” | The *conditional* *with* the *truth* *predicate* as *antecedent* |
| **Yablo** | An *infinite* *sequence* of *sentences*, each *saying* all *subsequent* *are* *false* | The *self*-*reference* is *eliminated* (the *infinite* *regress*) |
| **Knower** | “This sentence is not known” | The *knowledge* *predicate* (factive) |
| **Knowability** | “All *truths* are *knowable*” | The *Fitch* *argument* (the *conjunction* *of* *truth* and *ignorance*) |
| **Surprise examination** | The *teacher* *announces* an *exam* *next* *week* that *will* be *unexpected* | The *backward* *induction* |
| **Preface** | The *author* *believes* *each* *claim* and *believes* *some* *are* *false* | The *inconsistency* of *conjunctive* *belief* |
| **Lottery** | The *ticket* *will* *not* *win* (for *each* *ticket*) | The *individual* *knowledge* vs. the *collective* *ignorance* |

**The *family* *structure***. The *paradoxes* *share* a *pattern*: a *concept* (truth, knowledge, belief, prediction) is *defined* by a *schema* (the *Tarskian* *schema*, the *knowledge* *schema*), and the *schema* *generates* a *contradiction* when the *concept* is *applied* to *itself*.

**The *significance***. The *paradoxes* are *not* *isolated*; they are *manifestations* of a *single* *structural* *problem*: the *self*-*application* of a *concept* to *itself* *generates* a *contradiction* when the *concept* has a *certain* *structure* (the *negation* *involved* in the *definition*).

### 1.3 Curry's paradox

**The *sentence***. Let $C$ be the sentence:

> “If $C$ is true, then $p$.”

where $p$ is *any* *sentence* (e.g., “Germany won the Second World War”).

**The *Tarskian* *schema***. Apply (T) to $C$:

$$
(\mathrm{C}) \quad T(\ulcorner C \urcorner) \leftrightarrow (T(\ulcorner C \urcorner) \to p)
$$

**The *derivation***.

$$
\begin{array}{ll}
1. & T(C) \leftrightarrow (T(C) \to p) \quad \text{(the *schema*)} \\
2. & T(C) \to (T(C) \to p) \quad \text{(from 1)} \\
3. & T(C) \to p \quad \text{(from 2, *contraction*)} \\
4. & (T(C) \to p) \to T(C) \quad \text{(from 1)} \\
5. & T(C) \quad \text{(from 3, 4, *modus ponens*)} \\
6. & p \quad \text{(from 3, 5, *modus ponens*)}
\end{array}
$$

**The *consequence***. The *argument* *derives* *any* *sentence* $p$ (including a *contradiction*) from the *Tarskian* *schema* and *classical* *logic*. The *consequence* is *trivialism* (every *sentence* is *true*), and it is *more* *devastating* than the *Liar* (the *Liar* *generates* a *contradiction*, and *Curry* *generates* *everything*).

**The *significance***. Curry's paradox *shows* that the *problem* is *not* *specific* to the *negation* (the *Liar* *uses* the *negation*), and the *solution* *must* *address* the *conditional* *structure* (the *contraction* *principle*, the *modus ponens*). The *paradox* *rules* out a *large* *class* of *solutions* (the *solutions* that *keep* the *classical* *conditional* and the *contraction*).

### 1.4 Yablo's paradox

**The *construction*** (Yablo, “Paradox without Self-Reference,” 1993). Let $S_1, S_2, \ldots$ be an *infinite* *sequence* of *sentences*:

$$
S_n: \quad \text{“For all } m > n, \ S_m \text{ is false.”}
$$

**The *paradox***. Assume the *classical* *semantics* (each $S_n$ *true* or *false*).

- If $S_1$ is *true*, then all $S_n$ ($n > 1$) are *false*. In particular $S_2$ is *false*. But $S_2$ says all $S_n$ ($n > 2$) are *false*; if $S_2$ is *false*, some $S_n$ ($n > 2$) is *true*. Say $S_3$ is *true*. Then $S_3$ says all $S_n$ ($n > 3$) are *false*, so $S_4$ is *false* — and so on. But $S_2$ *false* means some $S_n$ ($n > 2$) is *true*, and $S_3$ *true* means $S_4, S_5, \ldots$ are all *false*. Then $S_2$ is *false* (consistent) — but wait, $S_1$ *true* says all $S_n$ ($n > 1$) are *false*, so $S_3$ is *false*. *Contradiction*.
- If $S_1$ is *false*, then some $S_n$ ($n > 1$) is *true*. Say $S_2$ is *true*. Then all $S_n$ ($n > 2$) are *false*. In particular $S_3$ is *false*, so some $S_n$ ($n > 3$) is *true*, say $S_4$. Then all $S_n$ ($n > 4$) are *false*, so $S_5$ is *false*, so some $S_n$ ($n > 5$) is *true* … But $S_2$ is *true*, and $S_2$ says all $S_n$ ($n > 2$) are *false* — so $S_4$ must be *false*. *Contradiction*.

**The *significance***. The *paradox* *does* *not* *use* *self*-*reference* (no *sentence* *refers* to itself), and it *shows* that the *problem* is *not* *specific* to the *self*-*reference*. The *problem* is the *truth* *predicate* *itself*, and the *solutions* that *target* the *self*-*reference* (the *hierarchical* *solutions*; §2.1) are *bypassed*.

**The *objections***. The *paradox* *is* *contested* (the *“*Yablo* *is* *really* *self*-*referential*”* *objection*; the *“*the* *infinite* *sequence* *is* *not* *a* *single* *language*”* *objection*). The *debate* is *unresolved*.

### 1.5 The Knower and Fitch's paradox

**The *Knower***. Let $K$ be the *sentence* “$K$ is not known,” and let $K(\cdot)$ be the *knowledge* *predicate* (the *factive* *predicate*: $K(\ulcorner p \urcorner) \to p$).

$$
(\mathrm{K}) \quad K \leftrightarrow \neg K(\ulcorner K \urcorner)
$$

**The *derivation***. Assume $K$. Then $K$ is *true*, so $\neg K(\ulcorner K \urcorner)$ (the *content* of $K$), and $K$ is *not* *known*. But we *assumed* $K$ and *derived* its *content* — if the *derivation* *counts* as *knowledge*, $K$ is *known*, and the *contradiction* *follows*. Assume $\neg K$. Then $K(\ulcorner K \urcorner)$ (the *negation* of the *content*), so $K$ is *known*, and by *factivity*, $K$ is *true*, and the *contradiction* *follows*.

**The *consequence***. The *Knower* *shows* that the *knowledge* *predicate* *generates* the *paradox* *independently* of the *truth* *predicate*, and it *threatens* the *epistemology* (Ch. 7, §4.2) as well as the *semantics*.

**Fitch's *paradox*** (Fitch, “A Logical Analysis of Some Value Concepts,” 1963).

$$
\begin{array}{ll}
1. & \text{Assume the *knowability* *principle*: } \forall p\, (p \to \Diamond K p). \\
2. & \text{Consider } p \wedge \neg K p \text{ (a *truth* that is *not* known).} \\
3. & \text{By (1), } \Diamond K(p \wedge \neg K p). \\
4. & \text{By the *distribution* of *knowledge* over *conjunction*: } K(a \wedge b) \to (Ka \wedge Kb). \\
5. & \text{So } \Diamond(Kp \wedge K\neg Kp). \\
6. & \text{By *factivity*: } K\neg Kp \to \neg Kp. \\
7. & \text{So } \Diamond(Kp \wedge \neg Kp) \text{ — a *contradiction*.} \\
\hline
8. & \therefore \text{The *knowability* *principle* is *false* (some *truths* are *unknowable*).}
\end{array}
$$

**The *consequence***. The *paradox* *shows* that the *anti*-*realist* *claim* (all *truths* are *knowable*; Ch. 22, §1.3) is *inconsistent* with the *elementary* *logic* of *knowledge*, and it *supports* the *realist* *position* (some *truths* are *unknowable*).

### 1.6 The pragmatic paradoxes

**The *thesis***. *Some* *paradoxes* are *not* *semantic* (they do not involve *truth* *values*) but *pragmatic* (they involve the *act* of *assertion*).

**Moore's *paradox*** (Moore, *Commonplace Book*, 1912; the *contemporary* *literature*).

> “It is raining, but I do not believe that it is raining.”

**The *structure***. The *sentence* is *not* a *contradiction* (it *can* be *true*: the *speaker* *may* be *wrong* about her *own* *belief*), but the *assertion* is *absurd* (the *speaker* *cannot* *sincerely* *assert* the *conjunction*, because the *assertion* *expresses* the *belief* in the *first* *conjunct*, and the *second* *conjunct* *denies* it).

**The *significance***. The *paradox* *shows* that the *assertion* *has* a *norm* (the *truth*-*norm*, or the *belief*-*norm*; Ch. 32, §9.3), and the *norm* *constrains* what can be *asserted*, *independently* of the *truth* *conditions*. The *thesis* is *central* to the *speech*-*act* *theory* (Ch. 34).

**The *preface* *paradox*** (Makinson, “The Paradox of the Preface,” 1965).

> The *author* *believes* each *claim* in the *book*, and *believes* (on the *basis* of *induction*) that *some* *claim* is *false*.

**The *structure***. The *beliefs* are *individually* *justified*, and the *conjunction* is *inconsistent*. The *paradox* *shows* that the *belief* *is not* *closed* under *conjunction* (the *conjunction* *principle* is *false*; the *contemporary* *literature*; Ch. 8, §6.2).

**The *lottery* *paradox*** (Kyburg, *Probability and the Logic of Rational Belief*, 1961).

> The *subject* *believes* that the *ticket* will *not* *win* (for *each* *ticket*), and *believes* that *some* *ticket* will *win*.

**The *structure***. The *beliefs* are *individually* *justified* (the *probabilities* *support* each), and the *conjunction* is *inconsistent* (some *ticket* *wins*). The *paradox* *shows* that the *belief* *is not* *closed* under *conjunction*, and it *connects* the *logic* of *belief* to the *probability* *theory* (Ch. 10, §4).

### 1.7 The set-theoretic and semantic paradoxes

**The *set*-*theoretic* *paradoxes***. The *paradoxes* are *not* *specific* to *language*; they *arise* in *set* *theory* and in *semantics*.

**(i) Russell's *paradox*** (Russell, *The Principles of Mathematics*, 1903, §78; the *letter* to Frege, 1902).

$$
R = \{x : x \notin x\} \quad \Rightarrow \quad R \in R \leftrightarrow R \notin R
$$

**(ii) Cantor's *theorem***. The *power* *set* of any *set* has *strictly* *greater* *cardinality* than the *set* (the *diagonal* *argument*). Applied to the *universal* *set* (the *set* of all *sets*), the *theorem* *generates* a *contradiction* (the *universal* *set* would have a *larger* *power* *set*, which is *impossible*).

**(iii) Burali-Forti***. The *ordinal* of all *ordinals* is an *ordinal*, and it is *larger* than *itself* (the *contradiction*).

**(iv) Grelling–Nelson***. A *predicate* is **heterological** if it does *not* *apply* to itself (“long” is *not* long, “short” is *short*). Is “heterological” *heterological*?

**(v) Berry***. “The *least* *integer* *not* *nameable* in *fewer* than *nineteen* *syllables*” — the *phrase* has *fewer* than *nineteen* *syllables*, and it *names* the *integer*, contradiction.

**The *significance***. The *paradoxes* *show* that the *classical* *logic* and the *naive* *comprehension* *principle* (the *principle* that every *condition* *defines* a *set*) are *inconsistent*, and the *inconsistency* is *not* *specific* to *language* (the *set*-*theoretic* *paradoxes* are *independent* of the *truth* *predicate*).

**The *solutions***. The *solutions* are *technical* (the *iterative* *conception* of *set*, the *type* *theory*, the *Zermelo–Fraenkel* *axioms*; Ch. 43, §7), and they are *incomplete* (the *iterative* *conception* *avoids* the *paradoxes* by *denying* the *universal* *set*, and the *denial* *requires* a *justification*; Ch. 15, §6.4).

---

## 2. The Semantic Solutions

### 2.1 Tarski's hierarchy

**The *thesis*** (Tarski, “The Concept of Truth in Formalized Languages,” 1933; “The Semantic Conception of Truth,” 1944). The *truth* *predicate* *cannot* be *defined* *within* a *language* (the *undefinability* *theorem*; the *Tarskian* *theorem*); it can be *defined* only *for* a *language*, *within* a *metalanguage*.

**The *structure***. The *language* is *stratified* into *levels*:

$$
\mathcal{L}_0 \ \to \ \mathcal{L}_1 \ \to \ \mathcal{L}_2 \ \to \ \cdots
$$

The *language* $\mathcal{L}_{n+1}$ *contains* the *truth* *predicate* *for* $\mathcal{L}_n$, and the *truth* *predicate* *for* $\mathcal{L}_{n+1}$ is *contained* only in $\mathcal{L}_{n+2}$.

**The *diagnosis***. The *Liar* *sentence* (“this sentence is false”) *cannot* be *formulated* in the *hierarchy*: the “false” *must* *belong* to a *higher* *level* than the *sentence* it *applies* to, and the *self*-*application* is *blocked* by the *level* *distinction*.

**The *virtue***. The *hierarchy* *avoids* the *paradox*, and it *provides* a *rigorous* *definition* of *truth* *for* the *formal* *languages*.

**The *objections***.

**(i) The *‘*no* *natural* *language*’* *objection* (the *most* *serious*; the *contemporary* *literature*). The *natural* *language* *contains* its *own* *truth* *predicate* (we *say* “everything she said is true,” and the *“*true*”* *applies* to the *whole* *language*), and the *hierarchy* *does* not *model* the *natural* *language*.

**The *reply***. The *hierarchy* is an *idealisation* (the *natural* *language* *approximates* it), and the *reply* *abandons* the *description* of *natural* *language*. The *reply* is *contested*.

**(ii) The *‘*no* *unity*’* *objection*. The *hierarchy* *fragments* the *truth* *predicate* (there is no *single* *truth* *predicate*, but a *sequence*), and the *unity* of the *concept* is *lost*.

**The *reply***. The *levels* are *unified* by the *schema* (the *T*-schema *holds* at *each* *level*), and the *reply* *grounds* the *unity* in the *schema*. The *reply* is *contested*.

### 2.2 Kripke's fixed-point theory

**The *thesis*** (Kripke, “Outline of a Theory of Truth,” 1975). The *truth* *predicate* is *partial*: some *sentences* are *true*, some *false*, and some *neither* (the *truth*-*value* *gap*). The *extension* and the *anti*-*extension* are *defined* by a *monotone* *operator*, and the *fixed* *point* *assigns* *truth* *values* to the *grounded* *sentences*.

**The *structure***. Let $(\mathcal{E}, \mathcal{A})$ be the *pair* of the *extension* (the *true* *sentences*) and the *anti*-*extension* (the *false* *sentences*), with $\mathcal{E} \cap \mathcal{A} = \emptyset$. The *operator* $\Phi$ *takes* the *pair* to a *new* *pair*:

$$
\Phi(\mathcal{E}, \mathcal{A}) = (\{p : p \text{ is *true* on the *hypothesis* } \mathcal{E} \wedge \neg p \text{ false on } \mathcal{A}\}, \ldots)
$$

The *operator* is *monotone* (the *extension* *grows*), and the *fixed* *point* is *reached* by *iteration*.

**The *diagnosis***. The *Liar* is *ungrounded* (it *does* not *receive* a *truth* *value* *at* *any* *stage* of the *construction*), and it is *neither* *true* *nor* *false*. The *truth*-*teller* (“this sentence is true”) is *also* *ungrounded*, and the *theory* *correctly* *leaves* it *undetermined*.

**The *virtue***. The *theory* *models* the *natural* *language* (the *truth* *predicate* *is* *partial*), and it *avoids* the *hierarchy* (the *language* *contains* its *own* *truth* *predicate*).

**The *objections***.

**(i) The *strengthened* *Liar* (the *most* *serious*; the *contemporary* *literature*). Consider the *sentence* “this sentence is *not* *true*.” If the *sentence* is *ungrounded*, it is *not* *true*, and therefore it is *true* (by its *own* *content*). The *contradiction* *returns*, and the *fixed*-*point* *theory* *cannot* *avoid* it.

**The *reply*** (the *contemporary* *literature*; the *“*super*-*valuationist*”* *account*; the *revision* *theory*; §2.3–2.4). The *strengthened* *Liar* *requires* a *non*-*classical* *treatment* of the *truth* *predicate* (the *super*-*valuation*, the *revision*, the *paraconsistent*), and the *reply* *extends* the *fixed*-*point* *theory*. The *reply* is *contested*.

**(ii) The *‘*no* *bivalence*’* *objection*. The *theory* *abandons* *bivalence* (some *sentences* are *neither* *true* *nor* *false*), and the *abandonment* *conflicts* with the *classical* *logic*.

**The *reply***. The *bivalence* is *not* *fundamental* (the *truth*-*value* *gap* is a *feature* of the *language*), and the *reply* *grounds* the *logic* in the *semantics*. The *reply* is *contested*.

### 2.3 Supervaluationism and the revision theory

**Supervaluationism*** (Fine, “Vagueness, Truth and Logic,” 1975; the *application* to the *Liar*; the *contemporary* *literature*).

**The *thesis***. The *sentence* is *true* iff it is *true* on *all* the *admissible* *precisifications* of the *truth* *predicate*, and *false* iff it is *false* on *all* the *precisifications*.

**The *structure***.

$$
\text{True}(p) \quad \text{iff} \quad \forall \text{ precisifications } \pi\, (\text{True}_\pi(p))
$$

**The *virtue***. The *theory* *preserves* the *classical* *logic* for the *determinate* *cases*, and it *handles* the *Liar* (the *Liar* is *true* on *some* *precisifications* and *false* on *others*, so it is *neither* *super*-*true* *nor* *super*-*false*).

**The *objections***. The *higher*-*order* *vagueness* (§3.2), and the *strengthened* *Liar* (the *precisifications* *are* *themselves* *subject* to the *paradox*).

**The *revision* *theory*** (Gupta, “Truth and Paradox,” 1982; Gupta & Belnap, *The Revision Theory of Truth*, 1993).

**The *thesis***. The *truth* *predicate* is *defined* by a *revision* *procedure*: the *extension* is *revised* *at* each *stage*, and the *process* *may* *not* *converge* (the *Liar* *oscillates* *between* *true* and *false*).

**The *virtue***. The *theory* *models* the *dynamic* *character* of *truth* (the *truth* *is* *not* a *fixed* *point* but a *stable* *pattern*), and it *handles* the *strengthened* *Liar* (the *oscillation* *is* *the* *pattern*).

**The *objections***. The *stability* *is* *not* *truth* (the *oscillating* *sentence* *is* *not* *true* or *false* in the *ordinary* *sense*), and the *theory* *abandons* the *bivalence*.

### 2.4 Contextualism

**The *thesis*** (Burge, “Semantical Paradox,” 1979; Simmons, *Universality and the Liar*, 1993; Glanzberg, “The Liar in Context,” 2001; the *contemporary* *literature*). The *truth* *predicate* is *context*-*sensitive*: the *extension* of the *predicate* *depends* on the *context* of the *utterance*, and the *Liar* *sentence* *changes* the *context* (it *raises* the *level* of the *truth* *predicate*).

**The *structure***.

$$
\text{True}(p, c) \quad \text{(the *truth* *depends* on the *context* } c)
$$

**The *virtue***. The *theory* *preserves* the *unity* of the *truth* *predicate* (it is a *single* *predicate*, with *context*-*dependent* *extension*), and it *handles* the *Liar* (the *sentence* *changes* the *context*, and the *sentence* *is* *true* *relative* to the *new* *context*).

**The *objections***.

**(i) The *‘*no* *stable* *content*’* *objection*. The *content* of the *Liar* *changes* with the *context*, and the *sentence* *does* not *express* a *stable* *proposition* (the *content* *is* *unstable*).

**The *reply*** (the *contemporary* *literature*). The *content* is *stable* *enough* *for* the *assertion*, and the *context*-*sensitivity* is a *feature* of the *truth* *predicate* (like the *indexicals*; Ch. 12, §4). The *reply* is *contested*.

**(ii) The *‘*no* *diagnosis*’* *objection*. The *theory* *describes* the *phenomenon* (the *context* *shifts*), but it *does* not *explain* *why* the *shift* *happens*, and the *explanation* is *required* for the *solution*.

**The *reply***. The *shift* is *explained* by the *semantics* of the *truth* *predicate* (the *predicate* *is* *indexical*), and the *reply* *grounds* the *explanation* in the *semantics*. The *reply* is *contested*.

### 2.5 Dialetheism

**The *thesis*** (Priest, *In Contradiction*, 1987; *Beyond the Limits of Thought*, 1995; Routley, *Exploring Meinong's Jungle*, 1980). *Some* *contradictions* are *true* (**dialetheias**), and the *Liar* is *one* of them (the *Liar* *sentence* is *both* *true* and *false*).

**The *structure***. The *logic* is **paraconsistent** (a *contradiction* does *not* *entail* *everything*; the *principle* of *explosion* is *rejected*).

$$
(\mathrm{LP}) \quad p, \neg p \not\vdash q
$$

**The *argument*** (Priest 1987, Ch. 1).

$$
\begin{array}{ll}
1. & \text{The *semantic* *paradoxes* are *valid* *arguments* (the *derivations* are *classically* *valid*).} \\
2. & \text{The *conclusions* are *contradictions* (the *Liar* is *both* *true* and *false*).} \\
3. & \text{The *contradictions* are *true* (the *dialetheist* *accepts* them).} \\
\hline
4. & \therefore \text{The *Liar* is a *true* *contradiction* (the *dialetheism*).}
\end{array}
$$

**The *virtue***. The *theory* *saves* the *classical* *derivations* (the *arguments* are *valid*) and the *Tarskian* *schema* (the *schema* *holds*), and it *avoids* the *ad* *hoc* *restrictions* (the *hierarchy*, the *truth*-*value* *gap*).

**The *objections***.

**(i) The *‘*trivialism*’* *objection* (the *most* *serious*). If a *contradiction* *is* *true*, and the *logic* *rejects* *explosion*, the *theory* *avoids* *trivialism* only by *rejecting* the *classical* *logic* (the *disjunctive* *syllogism*, the *modus* *ponens*, the *transitivity* of *entailment*). The *cost* is *very* *high*.

**The *reply*** (Priest 1987, Ch. 5). The *logic* *LP* *preserves* the *intuitive* *inferences* (the *modus* *ponens*, the *disjunctive* *syllogism*) for the *consistent* *cases*, and the *reply* *grounds* the *logic* in the *practice*. The *reply* is *contested*.

**(ii) The *Curry* *objection*. The *dialetheist* *must* *block* *Curry's* *paradox* *without* *blocking* the *Liar*, and the *blocking* *requires* a *restriction* on the *conditional* (the *contraction* *principle*), and the *restriction* *is* *ad* *hoc* (the *Curry* *paradox* *does* *not* *involve* the *negation*).

**The *reply*** (Priest 1987, Ch. 6). The *conditional* *is* *restricted* (the *dialetheist* *uses* a *relevant* *logic*), and the *reply* *grounds* the *restriction* in the *theory* of *conditionals* (Ch. 37). The *reply* is *contested*.

**(iii) The *‘*no* *reason*’* *objection*. The *dialetheist* *accepts* the *contradiction* *without* a *reason* (the *contradiction* is *true* because the *derivation* *shows* it), and the *acceptance* is *the* *consequence* of the *theory*, *not* a *justification*. The *objection* is *contested* (the *reply*: the *truth* of the *contradiction* is *justified* by the *validity* of the *derivation*).

### 2.6 The state of the semantic solutions

**The *assessment***. The *solutions* are *all* *costly*, and the *choice* *depends* on the *weight* given to the *classical* *logic*, the *Tarskian* *schema*, and the *natural* *language*.

| Solution | The *strength* | The *weakness* |
|---|---|---|
| **Tarski's hierarchy** | Rigorous; classical | The natural language |
| **Kripke's fixed point** | Models the partiality | The strengthened Liar |
| **Supervaluationism** | Preserves classical logic | Higher-order vagueness |
| **Revision theory** | Dynamic | Abandons bivalence |
| **Contextualism** | Preserves the unity | The content is unstable |
| **Dialetheism** | Saves the schema | The classical logic |

**The *most* *defensible* *position***. A *qualified* *contextualism* *combined* with a *fixed*-*point* *semantics*: the *truth* *predicate* is *context*-*sensitive* (the *contextualist* *insight*), the *truth* *is* *partial* (the *Kripkean* *insight*), and the *strengthened* *Liar* is *handled* by the *context* *shift* (the *contextualist* *insight*), *qualified* by the *admission* that the *combination* is *incomplete*.

---

## 3. Vagueness and Higher-Order Vagueness

### 3.1 The phenomenon

**The *datum***. **Vagueness** is the *phenomenon* of a *predicate* having **borderline cases** — cases where it is *unclear* whether the *predicate* *applies*, and *no* *amount* of *information* *settles* the matter.

**The *sorites*** (Ch. 31, §5.1). The *heap* *paradox*: 1 grain is not a heap, and if $n$ grains are not a heap, $n+1$ are not, so no number is a heap.

**The *theories***. The *theories* of *vagueness* (epistemicism, supervaluationism, degree, contextualism) are *all* *live* (Ch. 31, §5.6), and *none* is *decisive*.

### 3.2 Higher-order vagueness

**The *phenomenon***. The *boundary* *between* the *definite* cases and the *borderline* cases is *itself* *vague*: there is *no* *sharp* *boundary* *between* “definitely a heap” and “borderline,” and there is *no* *sharp* *boundary* *between* “definitely definitely a heap” and “definitely borderline,” and so on.

**The *argument*** (Wright, “Is Higher-Order Vagueness Coherent?”, 1992; the *contemporary* *literature*).

$$
\begin{array}{ll}
1. & \text{The *epistemicist* *posits* a *sharp* *boundary} n \text{ (the *last* *non}-*heap).} \\
2. & \text{The *boundary* \text{ is } *knowable* \text{ (the } *epistemicist* \text{ } *accepts* \text{ } *knowledge* \text{ of } *some* \text{ } *sharp* \text{ } *boundary*).} \\
3. & \text{The *higher}-*order* *boundary* \text{ (the } *boundary* \text{ between the } *definite* \text{ and the } *borderline*) \text{ is } *also* \text{ } *sharp* \text{ (by the } *epistemicist* \text{ } *assumption*).} \\
4. & \text{The } *higher*-*order* *sorites* \text{ *generates* a } *contradiction* \text{ (the } *boundary* \text{ is } *not* \text{ } *sharp* \text{ *at* *any* *level*).} \\
\hline
5. & \therefore \text{The *epistemicism* *fails* (the *boundary* *cannot* be *sharp* *without* \text{ } *higher*-*order* \text{ } *vagueness*).}
\end{array}
$$

**The *consequence***. The *higher*-*order* *vagueness* *challenges* *every* *theory* that *posits* a *sharp* *boundary* (the *epistemicism*, the *classical* *semantics*), and it *supports* the *non*-*classical* *theories* (the *supervaluationism*, the *degree* *theory*, the *contextualism*).

**The *objections***.

**(i) The *‘*no* *higher*-*order* *vagueness*’* *objection* (the *epistemicist* *reply*; Williamson, *Vagueness*, 1994, Ch. 5). The *higher*-*order* *vagueness* *is* *real*, but the *boundary* *is* *still* *sharp* (the *boundary* *between* the *definite* and the *borderline* *is* *sharp*, but *unknowable*, like the *first*-*order* *boundary*). The *reply* *accepts* the *phenomenon* and *denies* the *inference*.

**(ii) The *‘*no* *level* *distinction*’* *objection* (the *contemporary* *literature*). The *epistemicist* *hierarchy* *of* *definite*-*ness* *is* *infinite*, and the *infinite* *hierarchy* *is* *incoherent* (the *infinite* *sequence* *of* *sharp* *boundaries* *has* *no* *limit*, and the *lack* *of* *limit* *undermines* the *sharpness*). The *reply* *is* *contested*.

### 3.3 The challenge for the theories

**The *table***.

| Theory | The *boundary* | The *higher*-*order* *vagueness* |
|---|---|---|
| **Epistemicism** | Sharp; unknowable | Contested (the *infinite* *hierarchy*) |
| **Supervaluationism** | Vague; the *precisifications* | The *higher*-*order* *vagueness* *is* *handled* by the *hierarchy* of *precisifications* |
| **Degree** | A *matter* of *degree* | The *degrees* *are* *themselves* *vague* |
| **Contextualism** | Context-dependent | The *context* *is* *vague* |

**The *significance***. The *higher*-*order* *vagueness* is the *most* *difficult* *problem* in the *theory* of *vagueness*, and it *threatens* every *solution* (the *classical* and the *non*-*classical*).

### 3.4 The continuum

**The *phenomenon***. The *vagueness* is *pervasive*: the *colour* *spectrum*, the *length* *scale*, the *temperature*, the *species* *boundaries*, the *moral* *categories* (the *good*, the *just*, the *brave*).

**The *argument***. The *vagueness* is *not* a *defect* of *language*; it is a *feature* of the *world* (the *continuum* of *properties*), and the *theories* of *vagueness* *must* *model* the *continuity* (Ch. 43, §7; the *continuum* *in* *mathematics*).

**The *consequence***. The *vagueness* *connects* the *philosophy* of *language* to the *metaphysics* (the *continuum*, the *natural* *kinds*; Ch. 15, §5.1) and to the *epistemology* (the *vagueness* *undermines* the *classical* *logic*; Ch. 35).

### 3.5 The state of the debate

**The *assessment***. The *vagueness* *debate* is *unresolved*, and the *most* *defensible* *position* is a *qualified* *contextualism*: the *vagueness* is a *feature* of the *context*-*sensitive* *predicates* (the *contextualist* *insight*), and the *higher*-*order* *vagueness* *is* *handled* by the *hierarchy* of *contexts* (the *reply* is *contested*), *qualified* by the *admission* that the *hierarchy* is *incomplete*.

---

## 4. The Diagnostic Toolkit

### 4.1 The four notions

**The *distinction***. The *philosophy* of *language* *distinguishes* *four* *notions* that are *often* *confused*.

| Notion | The *definition* | The *example* |
|---|---|---|
| **Ambiguity** | The *expression* has *two* (or *more*) *distinct* *meanings* | “bank” (the *river* / the *financial* *institution*) |
| **Vagueness** | The *expression* has *borderline* *cases* | “heap” |
| **Context-sensitivity** | The *content* *depends* on the *context* | “I,” “now,” “tall” |
| **Generality** | The *expression* is *general* (it *applies* to *many* *things*) | “animal” |

**The *significance***. The *distinctions* are *not* *mere* *terminological*: the *four* *notions* *require* *different* *semantic* *treatments* (the *ambiguity* *requires* a *disambiguation*, the *vagueness* a *non*-*classical* *semantics*, the *context*-*sensitivity* an *indexical* *semantics*, the *generality* a *quantificational* *semantics*).

### 4.2 The diagnostic tests

**The *tests***.

**(i) The *conjunction* *test* (for *ambiguity*). If the *conjunction* of the *two* *readings* is *contradictory* (or *absurd*), the *expression* is *ambiguous*: “the bank is on the river *and* the bank is on Main Street” — the *two* *readings* *cannot* *both* *apply* to the *same* *object*, and the *conjunction* *is* *odd* *unless* the *two* *senses* are *distinguished*.

**(ii) The *sorites* *test* (for *vagueness*). If the *expression* *generates* the *sorites* (the *borderline* *cases* *in* a *continuous* *series*), the *expression* is *vague*.

**(iii) The *stabilisation* *test* (for *context*-*sensitivity*). If the *content* *stabilises* when the *context* is *fixed*, the *expression* is *context*-*sensitive*; if the *content* *varies* *even* *when* the *context* is *fixed*, the *expression* is *ambiguous*.

**(iv) The *kind* *test* (for *generality*). If the *expression* *applies* to a *kind* (the *natural* *kind*, the *functional* *kind*), the *expression* is *general*; if it *applies* to a *particular*, it is *singular*.

**The *significance***. The *tests* are *heuristic* (they *do* not *always* *give* a *definitive* *answer*), and they are *indispensable* for the *diagnosis* of the *philosophical* *confusions*.

### 4.3 Verbal disputes

**The *thesis*** (Chalmers, “Verbal Disputes,” 2011; the *contemporary* *literature*). A *dispute* is **verbal** if it *arises* *from* the *parties* *using* the *same* *words* *with* *different* *meanings*, and the *substantive* *question* *dissolves* when the *meanings* are *specified*.

**The *method***. The *diagnostic* *procedure*.

$$
\begin{array}{ll}
1. & \text{Identify the *disputed* *term* (the *word* *that* *carries* the *disagreement*).} \\
2. & \text{Specify the *candidate* *meanings* (the *senses* *available* *in* the *language*).} \\
3. & \text{Determine whether the *parties* *agree* on the *facts* *given* the *meanings* (the *factual* *question*).} \\
4. & \text{Determine whether the *disagreement* *survives* the *specification* (the *residual* *question*).} \\
\hline
5. & \therefore \text{The *dispute* is *merely* *verbal*, *broadly* *verbal*, or *substantive* (the *classification*).}
\end{array}
$$

**The *classification***.

| Kind | The *definition* | The *example* |
|---|---|---|
| **Merely verbal** | The *parties* *agree* on the *facts*; they *use* the *words* *differently* | “Is a tomato a fruit?” |
| **Broadly verbal** | The *parties* *disagree* on the *facts*, and *on* the *meaning* | “Is the tomato a vegetable?” (the *botanical* vs. the *culinary*) |
| **Substantive** | The *parties* *agree* on the *meaning* and *disagree* on the *facts* | “Is the tomato *ripe*?” |

**The *significance***. The *method* *dissolves* the *verbal* *disputes* (Ch. 2, §1.2), and it *locates* the *substantive* *disputes* (the *disagreements* that *survive* the *specification*).

### 4.4 The limits of the diagnostic method

**The *objections***.

**(i) The *‘*no* *neutral* *vantage* *point*’* *objection*. The *specification* of the *meanings* *presupposes* a *theory* of *meaning* (the *semantic* *theory*; Ch. 31, §3), and the *theory* is *contested*. The *method* *is* *not* *neutral*.

**The *reply***. The *method* is *fallible*, and the *fallibility* is *acknowledged*; the *method* *does* *not* *require* a *neutral* *vantage* *point* (the *specification* is *defeasible*). The *reply* is *contested*.

**(ii) The *‘*no* *fact* *of* the *matter*’* *objection*. The *method* *assumes* that the *meanings* *are* *determinate* (the *specification* *has* a *definite* *answer*), and the *assumption* is *false* (the *meanings* *are* *vague*, *contested*, *revisable*).

**The *reply***. The *method* *does* *not* *require* *determinacy*; it *requires* *only* *that* the *specification* *be* *possible* (the *specification* *can* be *partial*, and the *residual* *question* is *the* *substantive* *one*). The *reply* is *contested*.

**(iii) The *‘*verbality* *is* *a* *matter* *of* *degree*’* *objection*. The *disputes* are *rarely* *merely* *verbal* (the *language* and the *facts* are *entangled*), and the *classification* *is* *not* *sharp* (the *higher*-*order* *vagueness* of the *classification*; §3.2).

**The *reply***. The *classification* *is* *a* *tool*, not a *conclusion* (the *classification* *guides* the *inquiry*), and the *reply* *acknowledges* the *entanglement*. The *reply* is *contested*.

### 4.5 The state of the diagnostic method

**The *assessment***. The *diagnostic* *method* is *indispensable*, and it is *not* *decisive*.

| The *method* | The *strength* | The *weakness* |
|---|---|---|
| **Conjunction test** | Simple; for ambiguity | Only for ambiguity |
| **Sorites test** | For vagueness | Only for the continuous cases |
| **Stabilisation test** | For context-sensitivity | The context is hard to fix |
| **Verbal dispute method** | For the classification | The verbality is a matter of degree |

**The *most* *defensible* *position***. The *diagnostic* *method* is a *toolkit* (it *combines* the *tests*), and the *combination* is *heuristic* (it *does* not *guarantee* the *diagnosis*), *qualified* by the *admission* that the *method* is *fallible* and the *classification* is *context*-*dependent*.

---

## 5. Conceptual Engineering

### 5.1 The programme

**The *thesis*** (Haslanger, *Resisting Reality*, 2012, Chs. 1–2; Cappelen, *Fixing Language*, 2018; Chalmers, “What Is Conceptual Engineering and What Should It Be?”, 2020; the *contemporary* *literature*). The *philosophy* *must* *not* *only* *describe* the *concepts* *we* *have*; it *must* *evaluate* and *improve* them.

**The *distinction*** (Haslanger 2000, 2012, Ch. 1; Ch. 3, §1.5).

| Project | The *question* | The *criterion* |
|---|---|---|
| **Descriptive** | What *is* the *concept* we *have*? | *Extensional* *adequacy* to the *pre*-*theoretic* *intuition* |
| **Ameliorative** | What *concept* *should* we *have*, *given* our *purposes*? | *Fitness* for the *purpose*; the *normative* *argument* |

**The *argument*. The *descriptive* *question* *presupposes* a *purpose* (whether *acknowledged* or not), and the *ameliorative* *question* is *prior*.

$$
\begin{array}{ll}
1. & \text{The *analysis* of a *concept* *serves* a *purpose* (the *classification*, the *prediction*, the *normative* *evaluation*).} \\
2. & \text{The *purpose* is *not* *given* by the *concept* (it is a *choice*).} \\
3. & \text{The *choice* *requires* a *normative* *argument* (why *this* purpose rather than *that*?).} \\
\hline
4. & \therefore \text{The *ameliorative* *question* is *prior* (the *conceptual* *engineering* *programme*).}
\end{array}
$$

**The *virtue***. The *programme* *connects* the *philosophy* of *language* to the *ethics* and the *politics* (Ch. 45, §4; Ch. 47, §7), and it *fits* the *practice* of the *feminist* and the *critical* *theory* (the *social* *construction* of *gender*, *race*, *disability*; Ch. 15, §5.3).

### 5.2 Haslanger's exemplars

**The *exemplars***.

| The *concept* | The *descriptive* *analysis* | The *ameliorative* *analysis* | The *political* *stake* |
|---|---|---|---|
| **Gender** | The *social* *role* *associated* with *sex* | The *social* *position* *in* a *system* of *domination* | The *feminist* *critique* |
| **Race** | The *social* *category* *based* on *ancestry* | The *social* *position* *in* a *system* of *racial* *oppression* | The *anti*-*racist* *critique* |
| **Disability** | The *impairment* (the *medical* *model*) | The *social* *barrier* (the *social* *model*) | The *disability* *rights* *movement* |
| **Marriage** | The *legal* *contract* | The *relationship* of *care* and *commitment* | The *LGBTQ+* *movement* |
| **Death** | The *cessation* of *biological* *function* | The *irreversible* *loss* of *consciousness* | The *organ* *donation* *debate* |

**The *argument*. The *descriptive* *analysis* of *gender* (the *social* *role*) is *inadequate* (it *fails* to *capture* the *structural* *injustice*), and the *ameliorative* *analysis* (the *social* *position* in a *system* of *domination*) is *better* (it *captures* the *injustice* and *grounds* the *critique*).

**The *significance***. The *exemplars* show that *conceptual* *engineering* is *not* an *abstraction*; it is the *philosophical* *dimension* of *political* *struggle*, and the *engineering* *has* *real* *consequences* (the *legal* *recognition*, the *social* *change*).

### 5.3 Chalmers's defence

**The *thesis*** (Chalmers, “What Is Conceptual Engineering and What Should It Be?”, 2020). The *conceptual* *engineering* is a *legitimate* *philosophical* *project*, and it *must* be *distinguished* from the *conceptual* *analysis* (the *description* of the *concept*).

**The *structure***.

| The *project* | The *question* | The *method* |
|---|---|---|
| **Analysis** | What is the *concept*? | The *reflective* *equilibrium* (Ch. 3, §4) |
| **Engineering** | What *should* the *concept* be? | The *normative* *argument* (the *fitness*, the *fruitfulness*, the *justice*) |

**The *argument*. The *engineering* *requires* a *normative* *criterion* (the *purpose*, the *value*), and the *criterion* is *not* *given* by the *concept* (it is *chosen*).

**The *virtue***. The *distinction* *clarifies* the *debate* (the *analysis* and the *engineering* are *different* *projects*, and the *confusion* of the *two* is *a* *source* of *error*), and it *grounds* the *engineering* in the *normative* *philosophy*.

**The *objections***.

**(i) The *‘*no* *change* of* *subject*’* *objection* (the *contemporary* *literature*). The *engineering* *changes* the *subject* (the *new* *concept* is *not* the *old* *one*), and the *change* *undermines* the *continuity* of the *inquiry*.

**The *reply***. The *change* is *the* *point* (the *old* *concept* *served* *interests* that *should* *not* be *served*; the *revision* is a *normative* *achievement*), and the *reply* *grounds* the *change* in the *normative* *argument*. The *reply* is *contested* (Ch. 22, §4.4).

**(ii) The *‘*whose* *concept*?’* *objection* (the *feminist* and the *decolonial* *critique*; Ch. 11, §4). The *engineering* *presupposes* a *normative* *standpoint* (the *engineer*'s), and the *standpoint* is *not* *neutral* (it *reflects* the *engineer*'s *interests*).

**The *reply***. The *standpoint* is *acknowledged* (the *engineering* is *explicitly* *normative*, and the *normativity* is *argued* *for*), and the *reply* *grounds* the *engineering* in the *democratic* *deliberation*. The *reply* is *contested*.

### 5.4 The state of conceptual engineering

**The *assessment***. The *conceptual* *engineering* is the *most* *important* *recent* *development* in the *philosophy* of *language*, and it is *contested*.

| The *version* | The *strength* | The *weakness* |
|---|---|---|
| **Haslanger (ameliorative)** | Political; normative | The change of subject |
| **Cappelen (representational devices)** | Broad; systematic | The engineering is hard to distinguish from the analysis |
| **Chalmers (normative)** | Clarifies the distinction | The normative criterion |

**The *most* *defensible* *position***. A *qualified* *ameliorative* *engineering*: the *descriptive* *analysis* *and* the *ameliorative* *engineering* are *distinct* *projects* (the *Chalmers* *insight*), the *engineering* *serves* *normative* *purposes* (the *Haslanger* *insight*), and the *purposes* are *contestable* (the *feminist* *critique*), *qualified* by the *admission* that the *engineering* *changes* the *subject* and *requires* a *normative* *argument*.

---

## 6. The Limits of Thought

### 6.1 Kant's antinomies

**The *thesis*** (Kant, *Critique of Pure Reason*, 1781/1787, A426/B454–A433/B461). *Reason*, when it *goes* *beyond* *experience*, *generates* *antinomies* (the *thesis* and the *antithesis* are *both* *demonstrable*), and the *antinomies* *show* the *limits* of *reason*.

**The *structure***.

| The *antinomy* | The *thesis* | The *antithesis* |
|---|---|---|
| **1st** | The world has a beginning in time and a limit in space | The world has no beginning and no limit |
| **2nd** | Every composite substance is made of simple parts | No composite thing is made of simple parts |
| **3rd** | There is freedom (a causality of freedom) | There is no freedom; everything is nature |
| **4th** | There is a necessary being (God) | There is no necessary being |

**The *diagnosis***. The *antinomies* *arise* *from* the *application* of the *categories* (the *forms* of *cognition*; Ch. 20, §2) *beyond* *experience*, and the *resolution* is *transcendental* *idealism* (the *world* *in* *itself* *is* *not* *a* *thing* *to* *which* the *categories* *apply*).

**The *significance***. The *antinomies* are the *epistemological* *analogue* of the *semantic* *paradoxes* (the *self*-*application* of a *concept* *generates* a *contradiction*), and the *limits* are *structural* (the *conditions* of *cognition*, the *structure* of *language*).

### 6.2 Priest and the limits of thought

**The *thesis*** (Priest, *Beyond the Limits of Thought*, 1995). *Some* *limits* are *dialetheic*: the *limit* is *both* *within* and *beyond* *thought* (the *limit* *generates* a *contradiction*, and the *contradiction* is *true*).

**The *argument***.

$$
\begin{array}{ll}
1. & \text{The *limit* of *thought* is that *beyond* *which* *thought* *cannot* *go*.} \\
2. & \text{The *limit* *can* be *thought* (we *think* about the *limit*, and we *say* what it is).} \\
3. & \text{The *thought* of the *limit* *contradicts* the *limit* (the *limit* is *beyond* *thought*, and the *thought* *reaches* it).} \\
\hline
4. & \therefore \text{The *limit* is *dialetheic* (the *contradiction* is *true*).}
\end{array}
$$

**The *virtue***. The *view* *captures* the *paradoxical* *character* of the *limit* *concepts* (the *Absolute*, the *void*, the *ineffable*), and it *fits* the *dialetheism* (§2.5).

**The *objections***.

**(i) The *‘*no* *limits*’* *objection*. If the *limit* is *both* *within* and *beyond* *thought*, there is *no* *limit* (the *limit* *dissolves*), and the *dialetheism* *is* *incoherent*.

**The *reply***. The *limit* is *real* (the *contradiction* *is* *true*, and the *truth* *of* the *contradiction* *is* the *limit*), and the *reply* *grounds* the *limit* in the *dialetheic* *structure*. The *reply* is *contested*.

**(ii) The *‘*no* *empirical* *evidence*’* *objection*. The *limit* *concepts* (the *Absolute*, the *void*) are *not* *empirically* *accessible*, and the *dialetheism* *is* a *metaphysical* *speculation*.

**The *reply***. The *limit* *concepts* are *philosophical* (they *arise* from the *structure* of *language* and *thought*), and the *reply* *grounds* the *limits* in the *structure*. The *reply* is *contested*.

### 6.3 Wittgenstein and the limits of language

**The *thesis*** (Wittgenstein, *Tractatus Logico-Philosophicus*, 1921, §5.6, §6.54, §7). The *limits* of *language* are the *limits* of *the* *world*, and the *philosophy* *cannot* *speak* about the *limits* (it *shows* them).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *language* *pictures* the *world* (the *picture* *theory*; the *Tractatus* *thesis*).} \\
2. & \text{The *limits* of *the* *picture* are the *limits* of the *world* (the *picture* *cannot* *picture* its *own* *limits*).} \\
3. & \text{The *philosophy* *cannot* *speak* about the *limits* (the *attempt* *generates* *nonsense*).} \\
\hline
4. & \therefore \text{The *philosophy* *shows* the *limits* (the *Tractarian* *thesis*).}
\end{array}
$$

**The *virtue***. The *view* *captures* the *self*-*limiting* *character* of *philosophy* (the *philosophical* *problems* *arise* from the *misuse* of *language*, and the *clarity* *dissolves* them; Ch. 3, §7), and it *fits* the *therapeutic* *conception* of *philosophy*.

**The *objections***.

**(i) The *‘*self*-*refutation*’* *objection* (the *most* *famous*). The *Tractatus* *says* that the *limits* *cannot* be *said*, and the *Tractatus* *itself* *says* *something* about the *limits* (the *book* is *nonsense* by its *own* *standards*). Wittgenstein *acknowledges* the *paradox* (§6.54: the *propositions* are a *ladder* to be *thrown* *away*).

**The *reply***. The *self*-*refutation* is *the* *point* (the *book* *shows* the *limits* *by* *transgressing* them, and the *transgression* *is* the *demonstration*), and the *reply* *is* the *performative* *reading* of the *Tractatus*. The *reply* is *contested*.

**(ii) The *‘*no* *theory*’* *objection*. The *Tractatus* *offers* a *theory* (the *picture* *theory*), and the *theory* *is* *abandoned* by the *later* *Wittgenstein* (the *therapeutic* *conception*; Ch. 3, §7).

**The *reply***. The *later* *Wittgenstein* *keeps* the *therapeutic* *aim* (the *dissolution* of the *philosophical* *problems*), and the *reply* *grounds* the *continuity* in the *practice*. The *reply* is *contested*.

### 6.4 The possibility of conceptual revolutions

**The *thesis***. The *concepts* *we* *have* are *contingent* (they *have* a *history*, and they *could* be *otherwise*), and the *conceptual* *revolutions* (the *replacement* of one *conceptual* *scheme* by another) are *possible* and *real*.

**The *examples***.

| The *concept* | The *revolution* | The *consequence* |
|---|---|---|
| **The *elements*** | The *replacement* of the *four* *elements* (earth, water, air, fire) by the *periodic* *table* | The *new* *chemistry* |
| **The *species*** | The *replacement* of the *essential* *species* by the *evolutionary* *lineages* (Ch. 42, §3) | The *new* *biology* |
| **The *person*** | The *replacement* of the *rational* *substance* by the *psychological* *continuity* (Ch. 26, §3) | The *new* *ethics* |
| **The *race*** | The *replacement* of the *biological* *race* by the *social* *construction* (Ch. 15, §5.3) | The *new* *politics* |

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *conceptual* *schemes* *have* *changed* *historically* (the *scientific* *revolutions*, the *political* *revolutions*).} \\
2. & \text{The *changes* *are* *not* *merely* *verbal* (the *new* *concepts* *support* *new* *inferences*, *predictions*, and *interventions*).} \\
3. & \text{The *changes* *are* *driven* by *empirical* and *normative* *considerations*.} \\
\hline
4. & \therefore \text{The *conceptual* *revolutions* are *real* and *rationally* *assessable*.}
\end{array}
$$

**The *significance*.** The *revolutions* *support* the *conceptual* *engineering* (§5) and the *anti*-*essentialism* (the *concepts* are *not* *fixed* by the *world*; Ch. 15, §5.1), and they *raise* the *question* of *progress* (are the *new* *concepts* *better*, or merely *different*?).

**The *objections***.

**(i) The *‘*incommensurability*’* *objection*. The *conceptual* *revolutions* *make* the *older* *concepts* *incommensurable* (the *two* *schemes* *cannot* be *compared*), and the *incommensurability* *undermines* the *rational* *assessment*. The *reply* (the *comparison* is *partial*, and the *partial* *comparison* is *sufficient* for the *assessment*) is *contested*.

**(ii) The *‘*no* *progress*’* *objection* (the *contemporary* *literature*). The *revolutions* *do* not *necessarily* *improve* the *concepts* (the *new* *concepts* *may* *serve* *different* *purposes*), and the *assessment* *depends* on the *purposes* (§5.1).

### 6.5 The state of the limits debate

**The *assessment***. The *limits* debate is *unresolved*, and the *most* *defensible* *position* is a *qualified* *quietism*: the *limits* are *real* (the *paradoxes* and the *antinomies* *show* them), and the *limits* *cannot* be *transgressed* (the *attempt* *generates* *nonsense* or *contradiction*), *qualified* by the *admission* that the *limits* *can* be *shown* (the *Tractarian* *insight*) and that the *conceptual* *revolutions* *extend* the *limits* (the *engineering* *insight*).

---

## 7. The Ethics of Concepts

### 7.1 Whose concepts?

**The *question***. The *concepts* *we* *have* are *not* *neutral*: they *encode* *interests* (the *interests* of the *powerful*, the *interests* of the *community*, the *interests* of the *discipline*), and the *encoding* *raises* the *ethical* *question* (whose *concepts* *are* *they*?).

**The *argument* (the *feminist* and the *critical* *theory*; Haslanger 2012, Ch. 1; Fricker 2007, Ch. 7).

$$
\begin{array}{ll}
1. & \text{The *concepts* *are* *shaped* by *social* *practices* (the *classification*, the *norms*, the *institutions*).} \\
2. & \text{The *practices* *are* *shaped* by *power* (the *dominant* *groups* *impose* their *concepts*).} \\
3. & \text{The *imposition* *serves* *the* *interests* of the *dominant* *groups* (the *marginalized* *groups* *are* *classified* in *ways* that *serve* the *dominant*).} \\
\hline
4. & \therefore \text{The *concepts* are *ethical* and *political* (the *ethics* of *concepts*).}
\end{array}
$$

**The *virtue***. The *argument* *connects* the *philosophy* of *language* to the *political* *philosophy* (Ch. 47, §7), and it *grounds* the *conceptual* *engineering* in the *ethics* (the *engineering* *is* a *form* of *justice*).

### 7.2 Hermeneutical injustice

**The *thesis*** (Fricker, *Epistemic Injustice*, 2007, Ch. 7; Ch. 11, §4.1). The *marginalized* *groups* *suffer* a **hermeneutical* *injustice*** when the *collective* *conceptual* *resources* *do* not *include* the *concepts* *needed* to *understand* and *communicate* their *experience*.

**The *structure***.

$$
\begin{array}{ll}
1. & \text{The *group* has an *experience* (the *harassment*, the *discrimination*).} \\
2. & \text{The *concepts* for the *experience* are *absent* (the *collective* *resources* *lack* the *concept*).} \\
3. & \text{The *absence* *prevents* the *group* from *understanding* and *communicating* the *experience*.} \\
4. & \text{The *absence* *is* *not* *accidental* (it *reflects* the *marginalization* of the *group*).} \\
\hline
5. & \therefore \text{The *group* *suffers* a *hermeneutical* *injustice* (the *ethics* of *concepts*).}
\end{array}
$$

**The *examples***. The *concept* of *sexual* *harassment* (the *1970s* *feminist* *movement* *created* the *concept*), the *concept* of *marital* *rape* (the *1990s* *legal* *reforms*), the *concept* of *gaslighting* (the *2010s* *psychological* *literature*).

**The *significance***. The *injustice* *shows* that the *concepts* are *not* *neutral* (their *absence* is an *injustice*), and the *conceptual* *engineering* is a *remedy* (the *creation* of the *concept* *corrects* the *injustice*).

### 7.3 The politics of classification

**The *thesis*** (Bowker & Star, *Sorting Things Out*, 1999; the *contemporary* *literature*). The *classification* *systems* (the *medical* *classifications*, the *census* *categories*, the *legal* *categories*) *encode* *political* *choices* (who *is* *counted*, who *is* *recognized*, who *is* *excluded*), and the *choices* *are* *contestable*.

**The *examples***.

| The *classification* | The *political* *stake* | The *consequence* |
|---|---|---|
| **The *census* *race* *categories* | The *recognition* of *groups*, the *distribution* of *resources* | The *political* *representation* |
| **The *DSM* *categories* | The *medicalization* of *behaviour*, the *insurance* *coverage* | The *diagnosis* and the *treatment* |
| **The *crime* *categories* | The *definition* of *harm*, the *allocation* of *punishment* | The *criminal* *justice* |
| **The *species* *categories* | The *conservation* *policy*, the *biodiversity* | The *environmental* *protection* |

**The *significance***. The *classifications* are *not* *neutral* (they *distribute* *power* and *resources*), and the *conceptual* *engineering* is a *political* *act* (the *choice* of *classification* is a *choice* of *justice*).

### 7.4 The ethics of engineering

**The *question***. *Should* we *engineer* *concepts*? *Which* *concepts*, and *by* *what* *criteria*?

**The *criteria***.

| The *criterion* | The *question* | The *example* |
|---|---|---|
| **Fitness** | Does the *concept* *serve* the *purpose*? | The *medical* *concept* of *disability* |
| **Justice** | Does the *concept* *serve* the *marginalized*? | The *social* *concept* of *race* |
| **Fruitfulness** | Does the *concept* *advance* the *inquiry*? | The *scientific* *concepts* |
| **Conservatism** | Does the *concept* *preserve* the *continuity*? | The *ordinary* *language* |

**The *argument*. The *engineering* *requires* a *normative* *argument* (the *criteria*), and the *criteria* *conflict* (the *fitness* vs. the *conservatism*, the *justice* vs. the *fitness*), and the *choice* *is* a *judgment*.

**The *virtue***. The *criteria* *ground* the *engineering* in the *normative* *theory*, and the *criteria* *connect* the *philosophy* of *language* to the *ethics* (Ch. 44) and the *politics* (Ch. 47).

**The *objections***.

**(i) The *‘*paternalism*’* *objection*. The *engineering* *imposes* the *engineer*'s *concepts* on the *community*, and the *imposition* is *paternalistic*.

**The *reply***. The *engineering* is *democratic* (the *community* *participates* in the *choice*), and the *reply* *grounds* the *engineering* in the *deliberation*. The *reply* is *contested*.

**(ii) The *‘*no* *neutrality*’* *objection*. The *criteria* are *not* *neutral* (the *fitness*, the *justice* *encode* the *engineer*'s *values*), and the *engineering* is *ideological*.

**The *reply***. The *neutrality* is *not* *required* (the *engineering* is *explicitly* *normative*, and the *normativity* is *argued* *for*), and the *reply* *grounds* the *engineering* in the *transparency* and the *accountability*. The *reply* is *contested*.

### 7.5 The state of the ethics of concepts

**The *assessment***. The *ethics* of *concepts* is *unresolved*, and the *most* *defensible* *position* is a *qualified* *normativism*: the *concepts* are *ethical* and *political* (the *critical* *insight*), the *engineering* is a *form* of *justice* (the *feminist* *insight*), and the *criteria* are *plural* and *contestable* (the *pluralist* *insight*), *qualified* by the *admission* that the *engineering* is *paternalistic* and *requires* the *democratic* *deliberation*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **The *paradoxes* are *real*.** The *Liar*, *Curry*, *Yablo*, and the *Knower* are *valid* *derivations* of *contradictions* from the *Tarskian* *schema* and the *classical* *logic*.
- **The *semantic* *solutions* are *all* *costly*.** The *hierarchy*, the *fixed* *point*, the *supervaluationism*, the *revision*, the *contextualism*, and the *dialetheism* *each* *pay* a *price* (the *natural* *language*, the *strengthened* *Liar*, the *classical* *logic*).
- **The *vagueness* is *pervasive*.** The *sorites* *affects* *every* *continuous* *predicate*, and the *higher*-*order* *vagueness* *threatens* *every* *sharp*-*boundary* *theory*.
- **The *diagnostic* *method* is *indispensable*.** The *distinctions* (ambiguity, vagueness, context-sensitivity, generality) and the *tests* (conjunction, sorites, stabilisation, kind) are the *toolkit* of the *philosophy* of *language*.
- **The *conceptual* *engineering* is a *real* *research* *programme*.** The *ameliorative* *turn* (Haslanger) and the *normative* *defence* (Chalmers, Cappelen) are *influential*, and the *programme* is *contested*.
- **The *limits* of *thought* are *real*.** The *paradoxes* and the *antinomies* *show* the *limits*, and the *limits* *cannot* be *transgressed* *without* *nonsense* or *contradiction*.
- **The *ethics* of *concepts* is *urgent*.** The *hermeneutical* *injustice* and the *politics* of *classification* *show* that the *concepts* are *not* *neutral*, and the *engineering* is a *form* of *justice*.

### 8.2 What is open

- **The *solution* to the *Liar*.** The *hierarchy*, the *fixed* *point*, the *contextualism*, the *dialetheism* — *none* is *decisive*.
- **The *nature* of *vagueness*.** The *epistemicism*, the *supervaluationism*, the *degree*, the *contextualism* — *none* is *decisive*.
- **The *diagnosis* of the *verbal* *disputes*.** The *method* is *fallible*, and the *classification* is *contested*.
- **The *justification* of the *conceptual* *engineering*.** The *criteria* are *plural* and *contestable*.
- **The *limits* of *thought*.** The *quietism*, the *dialetheism*, the *Tractarian* *showing* — *none* is *decisive*.
- **The *ethics* of *concepts*.** The *paternalism* and the *neutrality* are *unresolved*.

### 8.3 The methodological lesson

The *chapter* is a *case* *study* in the *method* of *Part* I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *distinctions* among the *paradoxes*.
- **Thought experiments** (§2 of Ch. 3) — the *Liar*, the *Curry*, the *Yablo*, the *sorites* — are the *engine* of the *debate*.
- **Formalization** (§3 of Ch. 3) — the *Tarskian* *schema*, the *fixed*-*point* *operator*, the *paraconsistent* *logic* — is *essential* for the *field*.
- **Reflective equilibrium** (§4 of Ch. 3) is the *method* by which the *intuitions* and the *theories* are *adjusted*.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to *hold* the *question* *open*.

The *honest* verdict: the *theory* of *paradox* is a *field* in *transition*. The *classical* *solutions* are *untenable* in their *pure* forms; the *non*-*classical* *solutions* are *promising* but *costly*; the *diagnostic* *method* is *indispensable* but *fallible*; the *conceptual* *engineering* is *urgent* but *contested*.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Tarski** | The truth predicate is stratified | Rigorous; classical | The natural language |
| **Kripke** | Truth is partial (fixed point) | Models partiality | The strengthened Liar |
| **Supervaluationism** | Truth is super-truth | Classical for determinate cases | Higher-order vagueness |
| **Revision theory** | Truth is a dynamic process | Models the instability | Abandons bivalence |
| **Contextualism** | The truth predicate is context-sensitive | Preserves the unity | The content is unstable |
| **Dialetheism** | Some contradictions are true | Saves the schema | The classical logic |
| **Epistemicism** | Vagueness is epistemic; the boundary is sharp | Preserves classical logic | Higher-order vagueness |
| **Degree** | Truth is a matter of degree | Captures gradedness | The degrees are mysterious |
| **Conceptual engineering** | Concepts should be revised | Normative; political | Changes the subject |
| **Quietism** | The limits are shown, not said | Therapeutic | Self-undermining |

The *table* is a *map*, not a *verdict*. The *reader* who wants to *choose* a *position* must decide which *cost* is *acceptable* — and the *decision* is a *philosophical* *argument*.

---

> <details><summary><b>Optional threads for Ch. 33</b> (advanced / cross-cutting)</summary>
>
> **1. The *mathematical* *theories* of *truth*.** The *axiomatic* *theories* of *truth* (Friedman & Sheard 1987; Halbach, *Axiomatic Theories of Truth*, 2011) *provide* a *rigorous* *framework* for the *paradoxes*, and the *fixed*-*point* *theories* (Kripke; the *contemporary* *literature*) *connect* the *semantics* to the *recursion* *theory*. The *field* is *technical* and *rich*, and it *connects* the *philosophy* of *truth* to the *mathematical* *logic* (Ch. 43, §7).
>
> **2. The *paraconsistent* *logics*.** The *paraconsistent* *logics* (LP, the *relevant* *logics*, the *adaptive* *logics*) *provide* a *formal* *framework* for the *dialetheism* (Priest, Routley), and the *framework* is *contested* (the *classical* *logic* *fails*, and the *non*-*classical* *logic* is *difficult* to *motivate*). The *field* is *technical* and *central* to the *paradox* *debate*.
>
> **3. The *conceptual* *engineering* *and* *AI*.** The *AI* *systems* *classify* *people* (the *facial* *recognition*, the *risk* *assessment*), and the *classifications* *encode* *concepts* (the *race*, the *gender*, the *criminality*), and the *concepts* are *contestable* (the *algorithmic* *bias* *literature*; Ch. 51, §3). The *conceptual* *engineering* is *urgent* for the *AI* *ethics*, and the *connection* is *beginning* to be *explored*.
>
> **4. Non-Western *theories* of *paradox*.** The *Buddhist* *tradition* *developed* the *tetralemma* (the *catuṣkoṭi*: $p$, $\neg p$, $p \wedge \neg p$, $\neg p \wedge \neg\neg p$), and the *tetralemma* *anticipates* the *dialetheism* and the *paraconsistent* *logic*. The *Madhyamaka* *tradition* (Nāgārjuna) *developed* a *radical* *critique* of *all* *views* (the *śūnyatā*), and the *critique* *anticipates* the *quietist* *response* to the *paradoxes*. The *traditions* are *systematic* *alternatives* (Matilal 1986; Ganeri 2001; the *essays* in *The Oxford Handbook of Indian Philosophy*, 2017).
>
> **5. The *ethics* of *vagueness*.** The *vagueness* has *ethical* *consequences* (the *borderline* *cases* of *life*, *death*, *personhood*, *consent*), and the *ethics* of *vagueness* is *underdeveloped* (the *contemporary* *literature*; Ch. 51). The *connection* is *beginning* to be *explored*, and it is *urgent*.
> </details>

---

## Summary

- **The *Liar* and its *family*** (Curry, Yablo, the *Knower*, Fitch, Moore, the *preface*, the *lottery*) are *valid* *derivations* of *contradictions* from the *Tarskian* *schema* and the *classical* *logic*, and they *threaten* the *whole* *semantics*.
- **The *semantic* *solutions*** — Tarski's *hierarchy*, Kripke's *fixed* *point*, the *supervaluationism*, the *revision* *theory*, the *contextualism*, the *dialetheism* — are *all* *costly*, and *none* is *decisive*.
- **The *vagueness*** is *pervasive*, and the *higher*-*order* *vagueness* *threatens* every *sharp*-*boundary* *theory*.
- **The *diagnostic* *toolkit*** (ambiguity, vagueness, context-sensitivity, generality; the *conjunction*, *sorites*, *stabilisation*, *kind* *tests*; the *verbal* *dispute* *method*) is *indispensable* but *fallible*.
- **The *conceptual* *engineering*** (Haslanger, Chalmers, Cappelen) is the *most* *important* *recent* *development*: the *descriptive* *analysis* and the *ameliorative* *engineering* are *distinct* *projects*, and the *engineering* is *normative* and *contestable*.
- **The *limits* of *thought*** (Kant's *antinomies*, Priest's *dialetheism*, Wittgenstein's *Tractatus*) are *real*, and the *limits* *cannot* be *transgressed* *without* *nonsense* or *contradiction*.
- **The *ethics* of *concepts*** is *urgent*: the *hermeneutical* *injustice* and the *politics* of *classification* show that the *concepts* are *not* *neutral*, and the *engineering* is a *form* of *justice*.
- **The *most* *defensible* *position*** is a *qualified* *contextualism* *combined* with a *diagnostic* *method* and an *ameliorative* *engineering*, *qualified* by the *admission* that the *combination* is *incomplete*.

---

## Study Questions

1. State the *Liar* *paradox*. What is the *Tarskian* *schema*, and *why* does it *generate* the *contradiction*?
2. State *Curry's* *paradox*. Why is it *more* *devastating* than the *Liar*?
3. State *Yablo's* *paradox*. Does it *eliminate* *self*-*reference*? What is the *significance*?
4. State the *Knower* *paradox* and *Fitch's* *paradox*. What do they *show* about *knowledge*?
5. State *Moore's* *paradox*. What does it *show* about *assertion*?
6. State the *preface* and the *lottery* *paradoxes*. What do they *show* about *belief*?
7. State *Tarski's* *hierarchy*. What is the *‘*no* *natural* *language*’* *objection*?
8. State *Kripke's* *fixed*-*point* *theory*. What is the *strengthened* *Liar* *objection*?
9. State *supervaluationism* and the *revision* *theory*. Are they *defensible*?
10. State *contextualism*. Is the *context*-*sensitivity* *defensible*?
11. State *dialetheism*. Is the *paraconsistent* *logic* *defensible*? What is the *Curry* *objection*?
12. State *epistemicism* about *vagueness*. What is the *higher*-*order* *vagueness* *objection*?
13. State the *supervaluationist* and the *degree* *theories* of *vagueness*. Are they *defensible*?
14. Distinguish *ambiguity*, *vagueness*, *context*-*sensitivity*, and *generality*. What are the *diagnostic* *tests*?
15. State the *verbal* *dispute* *method*. Is it *defensible*? What are the *limits*?
16. State the *conceptual* *engineering* *programme*. Is it *defensible*?
17. Distinguish the *descriptive* and the *ameliorative* *projects*. Which is *prior*?
18. State the *hermeneutical* *injustice* *argument*. What does it *show* about *concepts*?
19. Is the *conceptual* *engineering* *paternalistic*? What does the *answer* *imply* for the *ethics* of *concepts*?
20. State the *limits* of *thought* *argument* (Priest). Is it *defensible*?
21. Is *Wittgenstein's* *Tractatus* *self*-*refuting*? What does the *answer* *imply* for the *limits* of *philosophy*?
22. Is the *conceptual* *revolution* *possible*? What does the *answer* *imply* for the *incommensurability* *thesis*?
23. Is the *vagueness* *epistemic* or *metaphysical*? What does the *answer* *imply* for *classical* *logic* (Ch. 35)?
24. Is the *conceptual* *engineering* a *form* of *justice*? What does the *answer* *imply* for the *relationship* between *philosophy* and *politics*?
25. “The paradoxes are not puzzles to be *solved*, but *symptoms* to be *diagnosed*.” Assess.

---

## Further Reading

- **Primary**: Eubulides, the *Liar* (the *fragments* in *The Older Sophists*, ed. Sprague, 1972); Alfred Tarski, “The Concept of Truth in Formalized Languages” (1933), in *Logic, Semantics, Metamathematics* (1956), and “The Semantic Conception of Truth” (1944), in *Philosophy and Phenomenological Research* 4; Saul Kripke, “Outline of a Theory of Truth” (1975), in *Journal of Philosophy* 72; Graham Priest, *In Contradiction* (1987), and *Beyond the Limits of Thought* (1995).
- **On the Liar and its family**: the *survey* in the *Stanford Encyclopedia* entry, “The Liar Paradox” (Beall, Glanzberg, and Ripley); the *contemporary* *literature* in *The Nature of Truth* (ed. Lynch, 2001), Part IV; Stephen Yablo, “Paradox without Self-Reference” (1993), in *Analysis* 53; Hartry Field, *Saving Truth from Paradox* (2008); J. C. Beall, *Spandrels of Truth* (2009).
- **On the semantic solutions**: Tarski (1933, 1944); Kripke (1975); Kit Fine, “Vagueness, Truth and Logic” (1975), in *Synthese* 30; Anil Gupta, “Truth and Paradox” (1982), in *Journal of Philosophical Logic* 11, and Anil Gupta and Nuel Belnap, *The Revision Theory of Truth* (1993); Tyler Burge, “Semantical Paradox” (1979), in *Journal of Philosophy* 76; Keith Simmons, *Universality and the Liar* (1993); Michael Glanzberg, “The Liar in Context” (2001), in *Philosophical Studies* 103; the *surveys* in the *Stanford Encyclopedia* entries, “The Revision Theory of Truth” (Gupta and Standefer), “Truth Values” (Shramko and Wansing), “Paraconsistent Logic” (Priest, Tanaka, and Weber).
- **On the set-theoretic paradoxes**: Bertrand Russell, *The Principles of Mathematics* (1903), §78; the *correspondence* with Frege, in *From Frege to Gödel* (ed. van Heijenoort, 1967); the *survey* in the *Stanford Encyclopedia* entry, “Russell’s Paradox” (Irvine and Deutsch); the *contemporary* *literature* in *The Oxford Handbook of the Philosophy of Mathematics and Logic* (ed. Shapiro, 2005).
- **On vagueness and higher-order vagueness**: Timothy Williamson, *Vagueness* (1994); Crispin Wright, “Is Higher-Order Vagueness Coherent?” (1992), in *Analysis* 52; Rosanna Keefe, *Theories of Vagueness* (2000); the *essays* in *Vagueness: A Reader* (ed. Keefe and Smith, 1996); the *survey* in the *Stanford Encyclopedia* entry, “Vagueness” (Sorensen).
- **On the limits of thought**: Immanuel Kant, *Critique of Pure Reason* (1781/1787), A426/B454–A433/B461; Graham Priest, *Beyond the Limits of Thought* (1995); Ludwig Wittgenstein, *Tractatus Logico-Philosophicus* (1921), §§5.6–7; the *essays* in *The New Wittgenstein* (ed. Crary and Read, 2000); the *survey* in the *Stanford Encyclopedia* entry, “Kant’s Transcendental Idealism” (Stang).
- **On conceptual engineering**: Sally Haslanger, *Resisting Reality* (2012), Chs. 1–2; Herman Cappelen, *Fixing Language* (2018); David Chalmers, “What Is Conceptual Engineering and What Should It Be?” (2020), in *Inquiry*; the *essays* in *Conceptual Engineering and Conceptual Ethics* (ed. Burgess, Cappelen, and Plunkett, 2020); the *survey* in the *Stanford Encyclopedia* entry, “Conceptual Engineering” (the entry by the contemporary literature).
- **On the ethics of concepts**: Miranda Fricker, *Epistemic Injustice* (2007), Ch. 7; Geoffrey Bowker and Susan Leigh Star, *Sorting Things Out* (1999); the *essays* in *The Routledge Handbook of Epistemic Injustice* (ed. Kidd, Medina, and Pohlhaus, 2017); the *survey* in the *Stanford Encyclopedia* entry, “Feminist Epistemology” (Anderson).
- **On non-Western theories of paradox**: B. K. Matilal, *The Character of Logic in India* (1998); Jonardon Ganeri, *Philosophy in Classical India* (2001); the *essays* in *The Oxford Handbook of Indian Philosophy* (ed. Ganeri, 2017), Part IV; the *tetralemma* *literature* (the *essays* in *Moonshadows*, ed. the Cowherds, 2011).

---

> *A closing note.* This chapter has followed the *family* of *paradoxes* — the *Liar*, *Curry*, *Yablo*, the *Knower*, *Fitch*, *Moore*, the *preface*, the *lottery* — through the *semantic* *solutions* (the *hierarchy*, the *fixed* *point*, the *supervaluationism*, the *revision*, the *contextualism*, the *dialetheism*), the *vagueness* and the *higher*-*order* *vagueness*, the *diagnostic* *toolkit*, the *conceptual* *engineering*, the *limits* of *thought*, and the *ethics* of *concepts*. The result is *not* a *solution* to the *paradoxes*, and it is *not* a *refutation* of the *paradoxes*. It is a *diagnosis*: the *paradoxes* are *real*, the *solutions* are *costly*, and the *most* *important* *response* is the *clarification* — of the *concepts*, the *boundaries*, and the *purposes* — that the *diagnostic* *method* provides.

> *And a bridge.* Part V has examined the *medium* of the *mind* — language — through *meaning* (Ch. 31), *truth* (Ch. 32), and *paradox* (this chapter). Part VI turns to *science*, *explanation*, and *mathematics* — the *domains* where the *language* *meets* the *world*, and where the *concepts* of *truth*, *meaning*, and *paradox* are *tested* by the *most* *rigorous* *practices* that *humanity* has *developed*. The *next* *chapter* *turns* to the *explanation* — the *structure* of the *scientific* *account* — and it *asks* the *question* that the *philosophy* of *language* *presupposes*: *what* *is* *it* for a *theory* to *explain* the *world*?
