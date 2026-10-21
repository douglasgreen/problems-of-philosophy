# Chapter 14 — Existence and Ontological Commitment

> “A curious thing about the ontological problem is its simplicity. It can be put in three Anglo-Saxon monosyllables: ‘What is there?’ It can be answered, moreover, in a word — ‘Everything’ — and everyone will accept this answer as true. However, this is merely to say that there is what there is.”
> — W. V. O. Quine, “On What There Is” (1948)

> “The acceptance of a new kind of entities is represented in the language by the introduction of a framework of new forms of expressions to be used according to a new set of rules. … The question of the existence of the entities can then be answered by reference to the framework.”
> — Rudolf Carnap, “Empiricism, Semantics, and Ontology” (1950)

---

Part II ended with a diagnosis: the *criterion* of knowledge is *internal* to the practice of inquiry, and the demand for an external justification is a demand that cannot be met. Part III begins with the question that the diagnosis makes urgent: if the standards of inquiry are internal to the practice, **what are the standards of existence?**

This is the question of **ontology** — the study of what there is. It is the oldest question in philosophy (“What is there?”), and it is the one that has been most transformed by the analytic tradition. The transformation is not a *solution*: it is a *method* — the method of *ontological commitment*, of *regimentation*, of *parsimony*, and of *deflation*. The method is the subject of this chapter.

The chapter proceeds in seven movements. §1 examines the *logic* of existence: is existence a property, a quantifier, or a presupposition? §2 examines the *history* of the debate — Meinong, Russell, and the neo-Meinongian revival. §3 presents *Quine's criterion*, the most influential account of ontological commitment. §4 examines *parsimony*, the criterion by which ontologies are compared. §5 examines *fictionalism*, the strategy that tries to avoid the commitments. §6 examines the *meta*-debate — naturalized ontology versus fundamental metaphysics versus deflationism. §7 examines the *methodology*, including the indispensability argument and the “ontological turn” in anthropology. §8 gives an honest verdict.

The connecting thread is a single question, which is the *metaphysical* form of the criterion problem: **what are the standards of existence, and how do we choose among them?** The answer, we shall see, is not a single criterion but a *structure* — and the structure is contested in a way that the structure of knowledge (Ch. 13) was not.

---

## 1. The Logic of Existence

### 1.1 Kant's thesis

The *starting point* of the modern debate is Kant's *Critique of Pure Reason*, and the thesis is stated with unusual force:

> “Being is evidently not a real predicate, that is, a concept of something which could be added to the concept of a thing. It is merely the positing of a thing, or of certain determinations in it.” (A598/B626)

**The argument.**

$$
\begin{array}{ll}
1. & \text{A *real* predicate adds to the *concept* of the subject.} \\
2. & \text{The *concept* of a thing is *complete* before we ask whether it *exists*.} \\
3. & \text{If existence were a *real* predicate, the *concept* of a *nonexistent* thing would be *incomplete*, and the *addition* of existence would *change* the *concept*.} \\
4. & \text{But the *concept* of a *hundred* *thalers* is the *same* whether they *exist* or not.} \\
\hline
5. & \therefore \text{Existence is *not* a *real* predicate.}
\end{array}
$$

**The *application*.** The argument is the *refutation* of the *ontological* argument (Ch. 2, §6.1; Ch. 50, §3): the *ontological* argument *treats* existence as a *perfection* — a *property* that a *being* can *have* or *lack* — and Kant's *thesis* *denies* that existence is a *property* in the *relevant* sense.

**The *problem*.** The *argument* *proves* *too* *much*. If existence is *not* a *property*, what *is* it? The *thesis* is *negative*; it *does* not *say* what existence *is*, and the *positive* *account* is the *subject* of the rest of the chapter.

### 1.2 Frege's quantifier

The *positive* *account* is due to Frege (*Foundations of Arithmetic*, 1884, §53; *Grundgesetze*, 1893, §21), and it is the *foundation* of modern logic.

**The *thesis*.** Existence is a **second-order** *property*: it is a *property* of *concepts*, not of *objects*.

**The *analysis*.**

| Sentence | Analysis | What it says |
|---|---|---|
| “Horses exist” | $\exists x\, \mathrm{Horse}(x)$ | The *concept* HORSE has *instances* |
| “Unicorns do not exist” | $\neg\exists x\, \mathrm{Unicorn}(x)$ | The *concept* UNICORN has *no* *instances* |
| “Some horses are white” | $\exists x\,(\mathrm{Horse}(x) \wedge \mathrm{White}(x))$ | The *concept* HORSE-AND-WHITE has *instances* |

**The *virtue*.** The *analysis* *dissolves* the *puzzle* of *negative* *existentials*. “Unicorns do not exist” is *not* a *claim* *about* a *particular* *unicorn* (which would *require* the *unicorn* to *exist* in order to be *talked* *about*); it is a *claim* *about* the *concept* UNICORN — that it is *empty*.

**The *form*.** The *existential* *quantifier* $\exists$ is the *formal* *counterpart* of the *ordinary* *word* “exists,” and the *formula* $\exists x\, Fx$ is *true* iff the *domain* *contains* at least one *thing* that is $F$.

**The *consequence*.** The *word* “exists” is *not* a *predicate* of *objects*; it is a *quantifier* over *objects*. The *grammar* of “exists” is *misleading*: it *looks* like a *predicate* (“$a$ exists” *looks* like “$a$ is red”), but the *logical* *form* is *different*.

### 1.3 The problem of the domain

The *quantifier* *analysis* *raises* a *question* that it does *not* *answer*: **what is the domain?**

**The *question*.** The *formula* $\exists x\, \mathrm{Unicorn}(x)$ is *false* — but *false* *relative* to *what* *domain*? If the *domain* is “everything,” the *formula* is *false* (there are no unicorns). If the *domain* is “everything that *can* be *talked* *about*,” the *formula* *may* be *true* (there *are* unicorns *in* *fiction*).

**The *options*.

| Domain | What it contains | Proponents |
|---|---|---|
| **The actual** | Everything that *exists* | Quine; the *naturalistic* *tradition* |
| **The possible** | Everything that *could* *exist* | Lewis (1986); the *modal* *realists* |
| **The Meinongian** | Everything that *can* be *an* *object* *of* *thought* | Meinong; Parsons; Zalta |
| **The fictional** | Everything that *is* *talked* *about* *in* *fiction* | the *fictionalists* |

**The *crux*.** The *choice* of *domain* *determines* the *ontology*, and the *choice* is *not* *settled* by the *logic*. The *logic* *presupposes* the *domain*, and the *domain* is the *subject* of the *metaphysical* *debate*.

### 1.4 Free logic and the existence predicate

The *standard* *first-order* *logic* *assumes* that *every* *singular* *term* *refers* (the *“existential* *import”* *assumption*). The *assumption* is *false* for *empty* *names* (“Sherlock Holmes,” “Vulcan,” “the present King of France”), and the *logic* that *drops* the *assumption* is **free logic**.

**The *distinction*.**

| Formula | Reading | Entails $E!a$? |
|---|---|---|
| $\exists x\,(x = a)$ | There is something identical to $a$ | Yes (in *classical* logic) |
| $E!a$ | $a$ *exists* | — |
| $\forall x\, E!x$ | Everything exists | — |

**The *view*.** In *negative* *free* *logic*, $\exists x\,(x = a)$ does *not* *entail* $E!a$: the *quantifier* ranges over *all* *objects*, *including* the *nonexistent* ones, and the *predicate* $E!$ *marks* the *subset* that *exists*.

**The *virtue*.** The *view* *allows* *statements* *about* *nonexistent* *objects* to be *true* (“Sherlock Holmes is a *detective*”) without *committing* to their *existence*.

**The *objection*.** The *view* *reintroduces* the *predicate* that *Kant* *denied*. If $E!$ is a *predicate*, the *Kantian* *argument* *applies*: what does it *add* to the *concept*? The *free* *logician*’s *reply*: $E!$ *adds* the *property* of *being* *in* the *actual* *world*, and the *property* is *real* (it is the *difference* *between* Sherlock and Aristotle). The *reply* is *contested*, and it is the *core* of the *Meinongian* *revival* (§2.4).

### 1.5 Thin versus thick existence

The *debate* *between* the *Fregean* and the *free-logic* *accounts* is a *debate* *between* two *conceptions* of *existence*.

| Conception | What existence is | The question “what exists?” | Proponents |
|---|---|---|---|
| **Thin** | The *quantifier*; no *content* *beyond* *being* *in* the *domain* | Answered by *regimentation* | Quine; the *naturalists* |
| **Thick** | A *substantive* *property* (actuality, concreteness, fundamentality) | Answered by *metaphysics* | the *fundamentalists*; the *Meinongians* |

**The *thin* *conception*.** Existence is *cheap*: to *exist* is *just* to be *included* in the *domain* of the *quantifier*. The *question* “does $x$ exist?” is *answered* by *regimenting* the *theory* and *reading* *off* the *domain*. The *consequence*: the *ontological* *debate* is a *debate* *about* *theories*, not *about* *the* *world*.

**The *thick* *conception*.** Existence is *substantive*: to *exist* is to *have* a *particular* *status* (actuality, concreteness, fundamentality). The *question* “does $x$ exist?” is *answered* by *metaphysical* *inquiry*, and the *inquiry* is *not* *reducible* to *regimentation*.

**The *stakes*.** The *choice* *determines* the *method* of *ontology*. The *thin* *conception* *implies* that ontology is *conceptual* *engineering* (§6.2); the *thick* *conception* *implies* that ontology is *substantive* *metaphysics* (§6.3).

---

## 2. Meinong, Russell, and the Nonexistent

### 2.1 Meinong's theory

Alexius Meinong (*Über Gegenstandstheorie*, 1904) developed the *most* *radical* *theory* of *nonexistent* *objects* in the *history* of philosophy.

**The *principle* *of* *independence*.** The *Sosein* (the “being-so,” the *properties*) of an *object* is *independent* of its *Sein* (its *being*, its *existence*).

**The *structure*.**

$$
\text{Object} \ \to \ \begin{cases} \text{Sein (being)} \ \to \ \begin{cases} \text{Existenz (existence)} \\ \text{Subsistenz (subsistence)} \end{cases} \\ \text{Sosein (being-so)} \ \to \ \text{the properties} \end{cases}
$$

**The *examples*.** The *golden* *mountain* is *golden* (it has the *Sosein* of *goldenness*) even though it does not *exist* (it lacks *Existenz*). The *round* *square* is *round* and *square* (it has *both* *Soseins*) even though it is *contradictory*.

**The *principle* *of* *unrestricted* *comprehension*.** For *every* *condition* $F$, there is an *object* that *is* $F$. The *principle* is the *Meinongian* *analogue* of the *naive* *comprehension* *principle* in *set* *theory*, and it is *subject* to the *same* *problems* (Russell’s *paradox*; §2.3).

### 2.2 Russell's critique

Bertrand Russell’s “On Denoting” (1905) is the *most* *famous* *critique* of *Meinong*, and it is the *origin* of the *theory* of *descriptions* (Ch. 12, §2).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{Meinong: “the round square” is an *object* that is *both* round and square.} \\
2. & \text{“The round square is square” is *true* (by Meinong’s *principle*).} \\
3. & \text{“The round square is not square” is *also* *true* (it is *round*, and nothing can be both a *square* and *not* a *square* … or so Russell *argues*).} \\
4. & \text{The *contradiction* is *unacceptable*.} \\
\hline
5. & \therefore \text{Meinong’s *theory* is *false*.}
\end{array}
$$

**The *alternative*.** Russell’s *theory* of *descriptions* *analyses* “the round square” as a *quantifier* — $\exists x\,(\mathrm{Round}(x) \wedge \mathrm{Square}(x) \wedge \forall y(\ldots \to y = x))$ — which is *false* (there is no such *object*). The *apparent* *reference* to a *nonexistent* *object* is *dissolved* by the *analysis*, and the *contradiction* *disappears*.

**The *slogan*.** “The *round* *square*” is an *incomplete* *symbol*; it has *no* *meaning* *in* *isolation*.

**The *legacy*.** Russell’s *critique* *established* the *Fregean* *orthodoxy*: existence is a *quantifier*, and *apparent* *reference* to *nonexistent* *objects* is *parasitic* on *descriptions* that *fail* *to* *denote*.

### 2.3 The McX objection

The *critique* has its *own* *problems*, and the *most* *famous* is the **McX objection**.

**The *argument*.** If “the *round* *square*” is an *object* that *is* *round* and *square*, then it *is* a *square*, and it *is* *not* a *square* (because it is *round*). The *contradiction* is *unacceptable*.

**The *reply*.** The *Meinongian* *reply* distinguishes *nuclear* and *extranuclear* *properties* (Parsons 1980), or *encoding* and *exemplifying* (Zalta 1983).

| *Distinction* | *Nuclear* / *encoding* | *Extranuclear* / *exemplifying* |
|---|---|---|
| **What it is** | The *properties* that *constitute* the *object* | The *properties* that the *object* *has* *in* *reality* |
| **The *round* *square* | *Encodes* *roundness* and *squareness* | *Exemplifies* neither |
| **The *golden* *mountain* | *Encodes* *goldenness* and *mountainhood* | *Exemplifies* neither |

**The *consequence*.** The *contradiction* *disappears*: the *round* *square* *encodes* the *contradictory* *properties*, but it does not *exemplify* them. The *encoding* is a *different* *relation* from *exemplification*, and the *contradiction* is *confined* to the *encoding*.

**The *objection*.** The *distinction* is *ad hoc*: it is *introduced* to *save* the *theory*, and it is *not* *independently* *motivated*. (This is the *ad hocness* *objection* of Ch. 3, §1.6, and it is *serious*.)

### 2.4 The neo-Meinongian revival

The *theory* has been *revived* in the *contemporary* *literature* by Parsons (*Nonexistent Objects*, 1980), Zalta (*Abstract Objects*, 1983; *Intensional Logic and the Metaphysics of Intentionality*, 1988), and Priest (*Towards Non-Being*, 2005).

**The *arguments*.**

**(i) The *phenomenology* of *intentionality*.** We *think* *about* *nonexistent* *objects* (Sherlock Holmes, the fountain of youth, the golden mountain). The *thoughts* are *about* *something*, and the *something* must be a *constituent* of the *thought*. (This is the *Russellian* *intuition* of Ch. 12, §1.4, *turned* *against* Russell.)

**(ii) The *logic* of *fiction*.** Statements *about* *fiction* (“Sherlock Holmes lives at 221B”) are *true*, and the *truth* *requires* a *referent*. The *Meinongian* *offers* the *referent* (a *nonexistent* *object*), and the *alternative* (the *fictionalist* *paraphrase*) is *unavailable* or *unintuitive*.

**(iii) The *principle* of *comprehension*.** The *principle* is *intuitive*: for *every* *description*, there is an *object* that *satisfies* it. The *denial* of the *principle* (Russell’s *analysis*) is *revisionary*, and the *revision* is *not* *independently* *motivated*.

**The *costs*.**

**(i) The *ontology* is *profligate*.** The *theory* *posits* an *object* for *every* *description*, including *contradictory* ones. The *ontology* is *infinite* and *unstructured*.

**(ii) The *logic* is *non-classical*.** The *theory* *requires* a *paraconsistent* *logic* (for the *contradictory* *objects*) or a *free* *logic* (for the *empty* *names*), and the *logic* is *contested* (Ch. 35, §5).

**(iii) The *epistemology* is *mysterious*.** How do we *know* *about* *nonexistent* *objects*? The *answer* (we *grasp* them *directly*, by *intentional* *relation*) is *not* an *explanation*; it is a *label*.

**The *state* of the debate.** The *neo-Meinongian* *programme* is a *minority* *position*, but it is *taken* *seriously*, and it has *generated* a *large* *literature*. The *orthodox* *position* (Russell, Quine) is *dominant*, but it has *not* *refuted* the *alternative*; it has *out-argued* it in the *mainstream*, and the *argument* is *not* *over*.

---

## 3. Quine's Criterion

### 3.1 The criterion

Quine’s “On What There Is” (1948) is the *most* *influential* *essay* on *ontological* *commitment* in the *analytic* *tradition*.

**The *criterion*.**

> “To be assumed as an entity is, purely and simply, to be reckoned as the value of a variable. … We look to the bound variables of a theory to see what the theory says there is.”

**The *formula*.** A theory $T$ is *ontologically* *committed* to the $F$s iff $T$ *entails* $\exists x\, Fx$ — *and* the *commitment* cannot be *eliminated* by a *paraphrase* that *avoids* the *quantifier*.

$$
T \models \exists x\, Fx \ \wedge \ \text{no paraphrase } T' \text{ of } T \text{ lacks the commitment}
$$

**The *examples*.**

| Sentence | Commitment | Why |
|---|---|---|
| “There are horses” | Horses | $\exists x\, \mathrm{Horse}(x)$ |
| “Pegasus” (as a *name*) | A *nonexistent* *object*? | $\exists x\,(x = \text{Pegasus})$ — *problematic* |
| “Pegasus” (as a *description*) | Nothing | $\neg\exists x\, \mathrm{Pegasus}(x)$ — *no* *commitment* |
| “There is a prime number between 4 and 6” | Numbers | $\exists x\,(\mathrm{Prime}(x) \wedge \ldots)$ |

**The *virtue*.** The *criterion* *transforms* ontology from a *question* *about* *the* *world* into a *question* *about* *theories*. The *ontological* *commitments* of a *theory* are *read* *off* the *quantifiers*, and the *reading* is *mechanical*.

**The *problem*.** The *criterion* *presupposes* that the *theory* is *regimented* into *first-order* *logic* with *quantifiers*. The *regimentation* is *not* *unique*, and the *choice* of *regimentation* *determines* the *commitments* (§3.3).

### 3.2 Regimentation

The *criterion* *requires* that the *theory* be *regimented* — *translated* into a *formal* *language* with *quantifiers*, *predicates*, and *variables*.

**The *process*.**

1. **Identify the theory**: the *body* of *claims* to be *analysed*.
2. **Define the predicates**: the *vocabulary* of the *theory*.
3. **Formalize the claims**: the *sentences* in *first-order* *logic*.
4. **Read off the commitments**: the *values* *of* the *bound* *variables*.

**The *paradigm*.** Quine’s *own* *example* is the *theory* of *physical* *objects*. The *theory* *quantifies* over *physical* *objects* and *space-time* *points*; the *commitment* is to *both*.

**The *reduction*.** The *commitments* can be *reduced* by *paraphrase*: the *space-time* *points* can be *reduced* to *quadruples* of *real* *numbers*, and the *real* *numbers* can be *reduced* to *sets*. The *reduction* is *not* *elimination*: the *sets* remain.

### 3.3 The translation problem

The *most* *serious* *objection* to Quine’s *criterion* is the **translation** *problem*.

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{Ontological commitment is a *property* of a *theory* *in* a *regimented* *language*.} \\
2. & \text{A *theory* can be *regimented* in *different* *ways*, with *different* *ontologies*.} \\
3. & \text{Example: *arithmetic* can be *regimented* with *numbers* ($\exists n\, \mathrm{Prime}(n)$) or with *sets* ($\exists s\,(\mathrm{Set}(s) \wedge \ldots)$).} \\
4. & \text{The *two* *regimentations* are *equivalent* (they *entail* the *same* *observational* *consequences*).} \\
\hline
5. & \therefore \text{The *ontology* is *not* *determined* by the *theory*; it is *determined* by the *translation*.}
\end{array}
$$

**The *consequence*.** The *ontology* is *relative* to the *translation* *scheme*. This is Quine’s **ontological relativity** (1968) and Putnam’s **equivalence thesis** (1975, 1983).

**The *proxy* *function*.** The *argument* is *formal*: for any *theory* $T$ with *domain* $D$, and any *one-to-one* *function* $f$ from $D$ onto $D'$, the *theory* $T'$ obtained by *replacing* each *element* of $D$ with its *image* under $f$ is *isomorphic* to $T$. The *two* *theories* are *empirically* *indistinguishable*, and the *ontologies* are *different*.

**The *implication*.** The *question* “does $x$ *really* *exist*?” is *not* *answered* by the *theory*; it is *answered* by the *choice* of *translation*. The *choice* is *pragmatic*, not *metaphysical*.

**The *objection*.** The *argument* *proves* *too* *much*: it *undermines* the *distinction* *between* *realism* and *anti-realism* (Ch. 22, §1). If *every* *ontology* is *translation-relative*, the *debate* *between* the *platonist* and the *nominalist* is *verbal*.

**The *reply*. Quine’s *own* *reply* is *naturalistic*: the *choice* of *translation* is *made* by *science*, and the *choice* is *justified* by the *virtues* of the *theory* (simplicity, strength, explanatory power). The *reply* *reintroduces* the *criteria* of §4, and it *relocates* the *problem* to the *choice* of *criteria*.

### 3.4 The indispensability argument

The *most* *influential* *application* of *Quine’s* *criterion* is the **indispensability* *argument**, developed by Quine (“Carnap and Logical Truth,” 1960; *Word and Object*, 1960) and Putnam (“Philosophy of Mathematics: A Report,” 1964; “Mathematics without Foundations,” 1967).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{We ought to have *ontological* *commitment* to all and only the *entities* that are *indispensable* to our *best* *scientific* *theories*.} \\
2. & \text{Mathematical entities (numbers, sets, functions) are *indispensable* to our *best* *scientific* *theories*.} \\
\hline
3. & \therefore \text{We ought to have *ontological* *commitment* to *mathematical* *entities*.}
\end{array}
$$

**The *defence* *of* *premise* 1.** The *premise* is the *naturalistic* *thesis*: ontology is *continuous* with science, and the *standards* of *ontology* are the *standards* of *science*. The *argument* is an *instance* of *IBE* (Ch. 10, §6): the *best* *explanation* of the *success* of *science* *requires* the *entities*.

**The *defence* *of* *premise* 2.** The *premise* is *empirical*: the *formulation* of *physics* (quantum mechanics, general relativity, statistical mechanics) *uses* *mathematics* *essentially*. The *use* is *not* *eliminable* *in* *practice*, and the *nominalist* *reformulations* (Field 1980) are *either* *artificial* *or* *incomplete*.

**The *objections*.

**(i) The *nominalist* *reformulation* (Field 1980).** Field *argues* that *physics* can be *reformulated* *without* *mathematics*, and the *reformulation* *shows* that *mathematics* is *not* *indispensable*. The *argument* is *contested*: the *reformulation* is *artificial*, *incomplete*, and *does* not *preserve* the *explanatory* *power* of the *mathematical* *formulation*.

**(ii) The *meta*-*induction* (Maddy 1992; Ch. 40, §5).** The *history* of *science* is a *history* of *successful* *theories* that *posited* *entities* that *turned* *out* *not* to *exist* (phlogiston, caloric, the luminiferous ether). The *induction*: our *current* *theories* *probably* *posit* *entities* that *do* not *exist*. The *argument* *undermines* the *indispensability* *argument* *for* *mathematics*, *unless* the *mathematical* *entities* are *different* (they are *abstract*, not *causal*).

**(iii) The *epistemic* *access* *problem* (Benacerraf 1973; Ch. 43, §1).** The *argument* *shows* that we *ought* to *believe* in *mathematical* *entities*, but it *does* not *show* *how* we *can* *know* *about* them. The *gap* is the *same* as the *access* *problem* of Ch. 9, §7.2.

**(iv) The *pragmatic* *objection* (Maddy 1997).** The *argument* *confuses* *ontological* *commitment* with *methodological* *acceptance*. The *scientist* *uses* *mathematics* *without* *believing* in *mathematical* *entities*, just as the *instrumentalist* *uses* *the* *theory* *without* *believing* *in* the *unobservable* *entities*.

**The *state* of the debate.** The *indispensability* *argument* is the *most* *influential* *argument* for *mathematical* *platonism*, and it is *not* *decisive*. The *debate* is *unresolved*, and it is *one* of the *central* *issues* in the *philosophy* of *mathematics* (Ch. 43).

---

## 4. Parsimony and the Ethics of Multiplication

### 4.1 Ockham's razor

The *criterion* of *parsimony* is the *oldest* *methodological* *principle* in *ontology*.

**The *formula*.** *Entia non sunt multiplicanda praeter necessitatem* — “entities are not to be multiplied beyond necessity” (Ockham, *Summa Logicae*, 1323, I.12; the *attribution* is *traditional*, and the *formula* is *not* *Ockham’s* *exact* *words*).

**The *interpretations*.**

| Interpretation | Claim | Problem |
|---|---|---|
| **Ontological** | Do not *posit* *unnecessary* *entities* | What is “necessary”? |
| **Methodological** | Prefer the *simpler* *theory* | “Simple” is *theory-relative* (Ch. 4, §3.3) |
| **Epistemic** | Simplicity is a *guide* to *truth* | The *connection* is *contested* |
| **Pragmatic** | Simplicity is a *virtue* of *theories*, not a *guide* to *truth* | It *does* not *justify* *belief* |

**The *problem*.** The *principle* is *not* a *decision* *procedure*. It *tells* us to *prefer* the *simpler* *theory*, but it *does* not *tell* us *which* *theory* is *simpler*, and the *answer* *depends* on the *choice* of *criteria* (Ch. 4, §3.3).

### 4.2 The varieties of parsimony

The *criterion* has *several* *dimensions*, and the *dimensions* *can* *conflict*.

| Kind | What it counts | Example |
|---|---|---|
| **Quantitative** | The *number* of *entities* | Two *kinds* of *entity* vs. three |
| **Qualitative** | The *number* of *kinds* | *Physical* *objects* vs. *physical* *objects* + *souls* |
| **Ideological** | The *number* of *primitive* *predicates* | The *vocabulary* of the *theory* (Sider 2011) |
| **Structural** | The *complexity* of the *laws* | The *axioms* of the *theory* |

**Sider’s *contribution*.** Theodore Sider (*Writing the Book of the World*, 2011) *argues* that the *ideological* *parsimony* is *as* *important* as the *ontological*. The *cost* of a *theory* is *not* *only* the *entities* it *posits*; it is *also* the *primitive* *vocabulary* it *requires*. The *point* is *important*: a *theory* that *posits* *few* *entities* but *requires* *many* *primitive* *predicates* *may* be *less* *parsimonious* than a *theory* that *posits* *more* *entities* with a *smaller* *ideology*.

**The *example*.** The *debate* *between* *presentism* and *eternalism* (Ch. 17, §1): the *presentist* *posits* *fewer* *times* (only the *present*), but *requires* a *primitive* *tense* *operator*; the *eternalist* *posits* *more* *times* (all of *them*), but *avoids* the *primitive* *tense*. The *two* *theories* are *compared* on *both* *dimensions*, and the *comparison* is *not* *obvious*.

### 4.3 The ethics of multiplication

The *opposite* *pole* to *Ockham* is the *“ethics* *of* *multiplication”* — the *view* that *positing* *entities* is *not* a *vice* but a *virtue*, when the *entities* *earn* their *keep*.

**The *proponents*.** William James (*A Pluralistic Universe*, 1909): the *universe* is *plural*, and the *multiplicity* is *real*. Goodman (*Ways of Worldmaking*, 1978): there are *many* *worlds*, and the *multiplication* is *creative*. Lewis (*On the Plurality of Worlds*, 1986): the *modal* *realist* *posits* *infinitely* *many* *concrete* *worlds*, and the *parsimony* *objection* is *answered* by the *explanatory* *power* of the *theory*.

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{Parsimony is a *virtue* only if it *tracks* *truth*.} \\
2. & \text{The *tracking* is *not* *guaranteed}: some *true* *theories* are *complex*, and some *simple* *theories* are *false*.} \\
3. & \text{The *choice* *between* *simple* and *complex* *theories* is an *IBE*, and the *IBE* *weighs* *parsimony* against the *other* *virtues*.} \\
\hline
4. & \therefore \text{The *multiplication* is *justified* when the *explanatory* *gain* *outweighs* the *ontological* *cost*.}
\end{array}
$$

**The *example*.** Lewis’s *modal* *realism* (Ch. 16, §2) *posits* an *infinite* *plurality* of *concrete* *worlds*. The *cost* is *enormous*; the *benefit* is a *unified* *semantics* *for* *modality*, *counterfactuals*, and *propositions*. The *debate* is *about* whether the *benefit* *outweighs* the *cost*, and the *answer* is *contested*.

### 4.4 Against parsimony

The *most* *radical* *critique* of *parsimony* is due to Michael Huemer (“When Is Parsimony a Virtue?”, 2009).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{There is *no* *evidence* that the *world* is *simple*.} \\
2. & \text{The *history* of *science* shows that the *world* is *more* *complex* than the *simple* *theories* *predicted* (quantum mechanics, relativity, evolution).} \\
3. & \text{The *virtue* of *parsimony* is *not* *truth-conducive*; it is a *heuristic* *for* *theory* *construction*.} \\
\hline
4. & \therefore \text{Parsimony is *not* a *guide* to *truth*.}
\end{array}
$$

**The *reply* (Sober 2015).** Parsimony is *not* a *claim* that the *world* is *simple*; it is a *methodological* *rule* for *choosing* *among* *theories* *that* *fit* the *data* *equally* *well*. The *rule* is justified by *statistical* *theory* (the *bias–variance* *tradeoff*; Ch. 4, §3.3), and the *justification* is *local*, not *global*.

**The *state* of the debate.** The *status* of *parsimony* is *contested*, and the *debate* is *connected* to the *status* of *IBE* (Ch. 10, §6). The *honest* *position*: parsimony is *a* *virtue*, *not* *the* *virtue*, and its *weight* *depends* on the *domain* and the *theory*.

---

## 5. Fictionalism

### 5.1 The strategy

**Fictionalism** is the *strategy* of *accepting* a *domain* of *discourse* *without* *accepting* its *ontological* *commitments*.

**The *structure*.**

$$
\begin{array}{ll}
1. & \text{Discourse } D \text{ is *useful* and *indispensable*.} \\
2. & \text{The *literal* *interpretation* of } D \text{ *requires* *entities* we *do* not *want* to *posit*.} \\
3. & \text{The *fictionalist* *treats* } D \text{ as a *fiction*: the *sentences* are *not* *true*, but they are *useful* *for* *prediction*, *explanation*, and *communication*.} \\
\hline
4. & \therefore \text{We *accept* } D \text{ without *ontological* *commitment*.}
\end{array}
$$

**The *varieties*.**

| Domain | Fictionalist | The *fiction* |
|---|---|---|
| **Mathematics** | Field (1980, 1989) | Numbers are *useful* *fictions* |
| **Modality** | Rosen (1990) | Possible worlds are *useful* *fictions* |
| **Morality** | Joyce (2001) | Moral facts are *useful* *fictions* |
| **Science** | van Fraassen (1980) | Unobservables are *useful* *fictions* |
| **Fiction** | Walton (1990) | Fictional *objects* are *props* in *games* of *make-believe* |

**The *distinction*.** *Hermeneutic* fictionalism *claims* that the *discourse* *is* *already* *fictional* (the *ordinary* *speaker* *is* *pretending*); *revolutionary* fictionalism *proposes* that the *discourse* *should* be *treated* as *fictional* (the *ordinary* *speaker* *is* *mistaken*, and the *fictionalist* *offers* a *revision*).

### 5.2 The problems

**The *problems* are *severe*, and they are *instructive*.

**(i) The *if-thenist* *paraphrase*.** The *fictionalist* *must* *paraphrase* the *apparent* *truths* of $D$ into *conditionals*: “if the *fiction* were *true*, then …” The *paraphrase* is *artificial*, and it *does* not *preserve* the *inferential* *role* of the *original* (the *mathematical* *proof* *uses* the *numbers* *essentially*, and the *paraphrase* *loses* the *proof*).

**(ii) The *attitude* *problem*.** What is the *mental* *state* of the *fictionalist*? Is she *believing* the *fiction*, or *pretending*? If *believing*, she is *committed* to the *entities*; if *pretending*, the *pretence* *does* not *explain* the *seriousness* of *mathematical* *practice*.

**(iii) The *inconsistency* *problem*.** The *fictionalist* *uses* the *fiction* to *explain* *why* the *fiction* *is* *useful*. The *explanation* *seems* to *require* the *truth* of the *fiction* (the *numbers* *explain* the *success* of *physics*, and the *explanation* *presupposes* the *numbers*).

**(iv) The *indispensability* *problem*.** The *fictionalist* *must* *show* that the *fiction* is *dispensable* in *principle*, and the *showing* is the *nominalization* *project* of Field, which is *incomplete*.

### 5.3 The *state* of the debate

**The *fictionalist* *programme* is *promising* and *incomplete*.

**The *strengths*.** The *programme* *captures* the *intuition* that *mathematics* and *modality* are *not* *descriptions* of *reality* in the *same* *way* as *physics*. The *intuition* is *widespread*, and the *programme* *offers* a *systematic* *articulation*.

**The *weaknesses*.** The *programme* *struggles* with the *inferential* *role* of the *fiction*, the *attitude* *problem*, and the *inconsistency* *problem*. The *struggles* are *not* *decisive*, but they are *serious*.

**The *verdict*.** Fictionalism is a *live* *option*, and it is *more* *defensible* for *some* *domains* (morality, modality) than for *others* (mathematics, physics). The *choice* *depends* on the *cost* of the *alternative* — and the *alternative* (the *realist* *commitment*) is *also* *costly*.

---

## 6. Naturalized Ontology, Fundamental Metaphysics, and Deflationism

### 6.1 The three positions

The *meta*-debate *about* ontology is a *debate* *about* the *nature* of the *inquiry*. The *three* *positions*.

| Position | Claim | Paradigm | Proponents |
|---|---|---|---|
| **Naturalized ontology** | Ontology is *continuous* with *science*; the *standards* are *scientific* | Quine | Quine; Maddy; the *naturalists* |
| **Fundamental metaphysics** | Ontology is *not* *continuous* with *science*; it *asks* what is *fundamental* | Sider; Schaffer | Sider (2011); Schaffer (2009) |
| **Deflationism** | Ontological *questions* are *verbal* or *pragmatic* | Carnap; Thomasson | Carnap (1950); Hirsch (2011); Thomasson (2015) |

**The *question*.** Which *position* is *correct*? The *answer* *determines* the *method* of *ontology*, and the *method* is the *subject* of the *rest* of the *chapter*.

### 6.2 Naturalized ontology

**The *thesis*.** Ontology is *not* a *separate* *discipline* with *its* *own* *standards*. It is *continuous* with *science*, and the *standards* of *ontology* are the *standards* of *science*.

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{The *only* *standards* of *inquiry* are the *standards* of *empirical* *science*.} \\
2. & \text{Ontology is a *form* of *inquiry*.} \\
\hline
3. & \therefore \text{The *standards* of *ontology* are the *standards* of *science*.}
\end{array}
$$

**The *consequence*.** The *ontological* *commitments* of *science* are the *ontological* *commitments* of *ontology*. The *philosophical* *debate* *between* the *platonist* and the *nominalist* is *settled* by the *science*: if *mathematics* is *indispensable*, the *platonist* *wins*.

**The *objection*.** The *view* *leaves* *no* *room* for the *distinctive* *questions* of *ontology*: what is *fundamental*? What is *real*? The *questions* are *not* *answered* by *science*, because *science* *presupposes* them.

### 6.3 Fundamental metaphysics

**The *thesis*.** Ontology is *not* *continuous* with *science*. It *asks* what is *fundamental*, and the *question* is *not* a *scientific* *question*.

**The *argument* (Sider 2011).**

$$
\begin{array}{ll}
1. & \text{Science *describes* the *world* at *many* *levels* (physics, chemistry, biology, psychology).} \\
2. & \text{The *description* *presupposes* a *structure*: some *things* are *more* *fundamental* than *others*.} \\
3. & \text{The *structure* is *not* *itself* a *scientific* *claim*; it is a *metaphysical* *claim*.} \\
\hline
4. & \therefore \text{Ontology is the *study* of the *structure*, and it is *not* *continuous* with *science*.}
\end{array}
$$

**The *apparatus*.** Sider *introduces*:
- **Structure**: the *world* has a *privileged* *description* (the *fundamental* *one*).
- **Joint-carving**: the *predicates* that *carve* *nature* *at* its *joints*.
- **Fundamentality**: some *entities* are *fundamental*; others are *derived*.
- **Grounding**: the *relation* *between* the *fundamental* and the *derived* (Ch. 21, §6).

**The *objection*.** The *apparatus* is *mysterious*: what *is* the *structure*? How do we *know* *which* *description* is *privileged*? The *answers* are *contested*, and the *view* *risks* *dogmatism*.

### 6.4 Deflationism

**The *thesis*.** Ontological *questions* are *not* *substantive*. They are *verbal* (disagreements *about* *words*) or *pragmatic* (disagreements *about* *convenience*).

**The *argument* (Carnap 1950).**

$$
\begin{array}{ll}
1. & \text{A *framework* is a *system* of *linguistic* *rules* that *introduces* a *domain* *of* *entities*.} \\
2. & \text{An *internal* *question* (“are there *numbers*?”) is *answered* *within* the *framework* (by the *rules*).} \\
3. & \text{An *external* *question* (“are there *really* *numbers*?”) is *not* a *theoretical* *question*; it is a *practical* *question* *about* *which* *framework* to *adopt*.} \\
\hline
4. & \therefore \text{Ontological *questions* are *either* *trivial* *or* *pragmatic*.}
\end{array}
$$

**The *contemporary* *version***. Eli Hirsch (*Quantifier Variance and Realism*, 2011) *argues* that the *ontological* *debates* are *verbal*: the *parties* *use* *different* *quantifier* *meanings*, and the *disagreement* *dissolves* once the *meanings* are *specified*. Amie Thomasson (*Ontology Made Easy*, 2015) *argues* that the *ontological* *questions* are *easy*: they are *answered* by *conceptual* *analysis* plus *empirical* *facts*.

**The *objection*.** The *view* *proves* *too* *much*: it *undermines* the *realism/anti-realism* *debate* (Ch. 22, §1), and it *leaves* *no* *room* for the *substantive* *questions* that *ontology* *has* *always* *asked*. The *reply*: the *substantive* *questions* are *not* *ontological*; they are *scientific* or *practical*.

### 6.5 The *state* of the *meta*-debate

The *three* *positions* are *all* *live*, and the *debate* *between* *them* is *one* of the *central* *issues* in *contemporary* *metaphysics*.

**The *most* *defensible* *position***. A *qualified* *naturalism*: ontology is *continuous* with *science* in its *standards*, but it *asks* *questions* (fundamentality, structure) that *science* *presupposes* and does not *answer*. The *position* *combines* the *naturalism* of Quine with the *ambition* of Sider, and it *avoids* the *deflationism* of Carnap.

**The *honest* *caveat***. The *position* is *not* *a* *consensus*. The *debate* is *unresolved*, and the *resolution* *depends* on *substantive* *questions* about *the* *nature* of *philosophy* (Ch. 1) and the *relation* between *philosophy* and *science* (Ch. 53).

---

## 7. The Methodology of Ontology

### 7.1 Inference to the best theory

The *method* of *ontology* is *inference* to the *best* *theory* — the *same* *method* as *science* (Ch. 10, §6), applied to the *most* *general* *questions*.

**The *structure*.**

$$
\begin{array}{ll}
1. & \text{The *candidate* *theories* are *compared* on the *criteria*: simplicity, strength, explanatory power, conservatism, coherence with science.} \\
2. & \text{The *comparison* is *holistic*: no *single* *criterion* is *decisive*.} \\
3. & \text{The *best* *theory* is the one that *scores* *best* *overall*.} \\
\hline
4. & \therefore \text{The *ontology* is *justified* by the *overall* *virtues* of the *theory*.}
\end{array}
$$

**The *virtues*.** The *criteria* are the *same* as Ch. 4, §3, with the *addition* of the *ontological* *cost* (the *entities* *posited*) and the *ideological* *cost* (the *primitive* *predicates* *required*).

**The *problem*.** The *method* is *fallible*, and the *choice* *among* *theories* is *not* *algorithmic*. The *ontology* is *justified* by the *same* *kind* of *argument* as the *scientific* *theory*, and it *inherits* the *same* *problems* (the *underdetermination* of *theory* by *evidence*, Ch. 40, §3).

### 7.2 The ontological turn in anthropology

The *most* *interesting* *recent* *development* is the **ontological turn** in *anthropology* (Viveiros de Castro 1998, 2004; Descola 2005, 2013; Holbraad 2012; Holbraad and Pedersen 2017).

**The *thesis*.** Different *cultures* have *different* *ontologies* — different *frameworks* of *what* *exists* and *what* *kinds* of *things* *there* *are*. The *anthropologist* *must* *take* the *ontologies* *seriously*, not *reduce* them to *beliefs* *about* a *single* *world*.

**The *examples*.**

- **Perspectivism** (Viveiros de Castro): in *Amazonian* *cosmologies*, *animals* and *spirits* are *persons*, and the *same* *entity* is *human* from *one* *perspective* and *animal* from *another*. The *ontology* is *not* a *belief* *about* a *single* *world*; it is a *different* *world*.
- **Animism** (Descola): in *many* *indigenous* *ontologies*, *natural* *kinds* are *not* *inert*; they are *agents* with *interiority*. The *ontology* *challenges* the *Western* *dichotomy* *between* *nature* and *culture*.

**The *philosophical* *significance*.** The *turn* *raises* the *question* of *whether* the *Western* *ontology* (the *one* *world*, *described* *by* *physics*) is *one* *ontology* *among* *many*, or the *correct* *one*. The *question* is a *version* of the *relativism* *debate* (Ch. 13, §3), and it *connects* ontology to the *criterion* *problem*.

**The *objections*.** (i) The *turn* *risks* *relativism*: if *all* *ontologies* are *equal*, *no* *ontology* is *better*. (ii) The *empirical* *status* of the *turn* is *contested*: are the *indigenous* *ontologies* *really* *ontologies*, or are they *different* *descriptions* of the *same* *world*? (iii) The *political* *stakes* are *high*: the *turn* is *used* to *criticize* the *colonial* *imposition* of *Western* *categories*, and the *critique* is *contested*.

### 7.3 The experimental philosophy of ontology

The *most* *recent* *development* is the *experimental* *study* of *folk* *ontological* *intuitions* (Rose & Schaffer 2017; Rose 2017).

**The *findings*.** The *folk* are *more* *willing* to *say* that “there are *tables*” than that “there are *numbers*,” and the *willingness* *tracks* *familiarity*, *concreteness*, and *causal* *role*. The *findings* *challenge* the *assumption* that the *folk* *concept* of *existence* is *univocal*.

**The *significance*.** If the *folk* *concept* is *heterogeneous*, the *philosophical* *debate* *between* the *naturalists* and the *deflationists* is *not* *settled* by *intuition*: the *intuitions* are *diverse*, and the *choice* *among* them is *substantive*.

**The *limits*.** The *findings* are *contested* (the *replication* *crisis*; Ch. 3, §6.3), and the *interpretation* is *not* *obvious*. The *experimental* *turn* is *promising*, but it is *not* *decisive*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **Existence is *thin* or *thick*, and the *choice* *matters*.** The *Fregean* *quantifier* and the *Meinongian* *predicate* are *both* *live*, and the *debate* *between* them is *not* *settled*.
- **The *criterion* of *ontological* *commitment* is *regimentation*, and the *regimentation* *is* *not* *unique*.** Quine’s *criterion* *relocates* the *problem* to the *translation* *scheme*.
- **The *indispensability* *argument* is the *strongest* *argument* *for* *mathematical* *platonism*, and it is *not* *decisive*.** The *nominalist* *reformulation* and the *meta-induction* are *serious* *challenges*.
- **The *parsimony* *criterion* is *real*, but it is *not* a *decision* *procedure*.** The *choice* *depends* on the *criteria*, and the *criteria* *conflict*.
- **The *fictionalist* *strategy* is *promising* and *incomplete*.** The *if-thenist* *paraphrase*, the *attitude* *problem*, and the *indispensability* *problem* are *unresolved*.
- **The *meta*-debate* (naturalism vs. fundamentalism vs. deflationism) is *unresolved*.** A *qualified* *naturalism* is the *most* *defensible* *position*.

### 8.2 What is open

- **The *nature* of *existence*.** Is it *thin* (the *quantifier*) or *thick* (a *substantive* *property*)?
- **The *status* of *nonexistent* *objects*.** Is *Meinong* *right* that they *are*, or *Russell* that they *are* *not*?
- **The *ontology* of *mathematics*.** Is *platonism* *justified* by *indispensability*, or is *fictionalism* the *better* *option*?
- **The *ontology* of *modality*.** Is *Lewis’s* *modal* *realism* *justified* by its *explanatory* *power*, or *refuted* by its *cost*? (Ch. 16)
- **The *status* of *the* *meta*-debate*.** Is ontology *substantive* or *deflationary*?
- **The *ontological* *turn*.** Are *indigenous* *ontologies* *genuine* *ontologies*, or *different* *descriptions* of the *same* *world*?

### 8.3 The methodological lesson

The chapter is a *case* *study* in the *method* of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *Fregean* *analysis* of *existence*.
- **Thought experiments** (§2 of Ch. 3) — the *round* *square*, the *golden* *mountain*, the *Twin* *Earth* — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *quantifiers*, the *free* *logic*, the *regimentation* — is *essential* for the *criterion*.
- **Reflective equilibrium** (§4 of Ch. 3) is the method by which the *intuitions* and the *theories* are adjusted.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to hold the *question* open.

The *honest* verdict: the *theory* of *existence* is a *field* in *transition*. The *Fregean* *orthodoxy* is *dominant*, but it is *not* *settled*; the *Meinongian* *alternative* is *live*; the *fictionalist* *strategy* is *promising*; the *meta*-debate* is *unresolved*. The *unresolved* character is *instructive*: it shows what philosophical progress looks like — not a *settled answer*, but a *sharper understanding* of what the *question* is.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Frege/Quine** | Existence is a *quantifier* | *Formal*; *precise* | *Relocates* the *problem* to the *translation* |
| **Meinong** | Existence is a *predicate*; there are *nonexistent* *objects* | *Phenomenology* of *thought* | *Profligate*; *contradictory* |
| **Quine’s criterion** | Commitment is *regimentation* | *Mechanical* | *Translation* *relativity* |
| **Indispensability** | Commit to what *science* *requires* | *Naturalistic* | *Access* *problem*; *meta-induction* |
| **Parsimony** | Prefer the *simpler* *theory* | *Intuitive* | *Not* *truth-conducive* |
| **Fictionalism** | Accept *without* *commitment* | *Avoids* the *cost* | *Attitude* *problem*; *inconsistency* |
| **Naturalism** | Ontology is *continuous* with *science* | *Honest* | *Leaves* no *room* for *fundamental* *questions* |
| **Fundamentalism** | Ontology *asks* what is *fundamental* | *Ambitious* | *Mysterious* *apparatus* |
| **Deflationism** | Ontological *questions* are *verbal* | *Dissolves* the *debate* | *Proves* *too* *much* |

The *table* is a *map*, not a *verdict*. The *reader* who wants to *choose* a *position* must decide which *cost* is *acceptable* — and the *decision* is a *philosophical* *argument*.

---

> <details><summary><b>Optional threads for Ch. 14</b> (advanced / cross-cutting)</summary>
>
> **1. The *Barcan* *formula* and *ontological* *commitment* *across* *worlds*.** The *formula* $\Diamond \exists x Fx \to \exists x \Diamond Fx$ (the *Barcan* *formula*) is *valid* in *some* *modal* *logics* and *invalid* in *others*. The *validity* *determines* whether *possible* *objects* are *in* the *actual* *domain*, and the *choice* is *metaphysically* *loaded* (Ch. 16, §2). The *debate* is *connected* to the *ontology* of *modality*, and it is *one* of the *most* *technical* *issues* in the *field*.
>
> **2. The *set-theoretic* *paradoxes* and the *limits* of *comprehension*.** The *Meinongian* *principle* of *unrestricted* *comprehension* is *structurally* *parallel* to the *naive* *comprehension* *principle* in *set* *theory*, and it is *subject* to the *same* *problems* (Russell’s *paradox*, Burali-Forti, Cantor). The *solutions* (the *iterative* *conception*, the *proper* *classes*, the *paraconsistent* *logic*) are *technical* and *contested* (Ch. 43, §7).
>
> **3. The *ontology* of *fiction*.** The *debate* *between* the *fictionalists* (Walton 1990), the *Meinongians* (Parsons, Zalta), and the *“pretence”* *theorists* (Currie 1990) is a *test* *case* for the *theory* of *existence*. The *philosophical* *stakes* are *high*: the *account* of *fiction* *determines* the *account* of *reference*, *truth*, and *the* *imagination* (Ch. 49, §4).
>
> **4. Non-Western *ontologies*.** The *Buddhist* *Abhidharma* *tradition* *developed* a *sophisticated* *ontology* of *dharmas* (irreducible *elements* of *experience*) that is *strikingly* *similar* to the *contemporary* *debate* *between* *substance* and *process* *ontologies* (Ch. 20, §5). The *Nyāya-Vaiśeṣika* *school* *developed* a *realist* *ontology* of *categories* (substance, quality, action, universality, inherence) that is a *systematic* *alternative* to the *Western* *taxonomy*. The *Daoist* *tradition* *developed* a *process* *ontology* that *anticipates* *Whitehead* (Ch. 20, §4). These are *systematic* *alternatives*, not *curiosities* (Matilal 1986; Ganeri 2001; the *essays* in *The Oxford Handbook of Indian Philosophy*, 2017).
>
> **5. The *ethics* of *ontology*.** The *choice* of *ontology* is *not* *purely* *theoretical*: it *determines* *whose* *entities* are *real*, *whose* *categories* are *imposed*, and *whose* *world* is *recognized* (the *ontological* *turn*; Ch. 14, §7.2). The *ethics* of *ontology* is the *most* *underdeveloped* *area* of *metaphysics*, and it is the *most* *urgent*.
> </details>

---

## Summary

- **The *logic* of *existence* is *contested*.** The *Kantian* *thesis* (existence is not a *real* *predicate*) and the *Fregean* *analysis* (existence is a *second-order* *property*, the *quantifier*) are the *orthodoxy*. The *free-logic* *alternative* (the *existence* *predicate* $E!$) is the *revisionary* *option*.
- **The *history* of the *debate* runs from *Meinong* (nonexistent *objects*) to *Russell* (the *theory* of *descriptions*) to the *neo-Meinongian* *revival* (Parsons, Zalta, Priest). The *Meinongian* *principle* of *independence* is *intuitive*, and the *McX* *objection* is *serious*; the *neo-Meinongian* *reply* (*encoding* vs. *exemplifying*) is *contested*.
- **Quine’s *criterion*** — “to be is to be the *value* of a *bound* *variable*” — *transforms* ontology into a *question* *about* *regimented* *theories*. The *criterion* is *mechanical*, but it is *not* *unique*: the *translation* *scheme* *determines* the *commitments* (*ontological* *relativity*).
- **The *indispensability* *argument*** — we *ought* to *commit* to the *entities* *indispensable* to *science* — is the *strongest* *argument* *for* *mathematical* *platonism*, and it is *not* *decisive*. The *nominalist* *reformulation*, the *meta-induction*, and the *access* *problem* are *serious* *challenges*.
- **Parsimony** is the *oldest* *criterion* of *ontology*, and it is *not* a *decision* *procedure*. The *varieties* (quantitative, qualitative, ideological, structural) *can* *conflict*, and the *weight* of the *criterion* is *contested* (Sober vs. Huemer).
- **Fictionalism** is the *strategy* of *accepting* a *discourse* *without* *ontological* *commitment*. The *problems* (the *if-thenist* *paraphrase*, the *attitude* *problem*, the *inconsistency* *problem*) are *severe*, and the *programme* is *incomplete*.
- **The *meta*-debate* (naturalism vs. fundamentalism vs. deflationism) is *unresolved*. A *qualified* *naturalism* is the *most* *defensible* *position*: ontology is *continuous* with *science* in its *standards*, but it *asks* *questions* that *science* *presupposes*.
- **The *methodology* of *ontology* is *IBE*, with the *criteria* of Ch. 4, §3, *plus* the *ontological* and *ideological* *costs*. The *ontological* *turn* in *anthropology* *raises* the *question* of *whether* the *Western* *ontology* is *one* *among* *many*, and the *experimental* *philosophy* of *ontology* *challenges* the *assumption* of a *univocal* *folk* *concept*.

---

## Study Questions

1. State Kant’s *thesis* that existence is not a *real* *predicate*. Is the *argument* *valid*? What is the *Fregean* *alternative*?
2. Is existence *thin* or *thick*? What does the *answer* *imply* for the *method* of *ontology*?
3. State Meinong’s *principle* of *independence*. Is it *defensible*? What is Russell’s *critique*, and is it *decisive*?
4. What is the *McX* *objection*? Is the *encoding/exemplifying* *distinction* an *adequate* *reply*?
5. State Quine’s *criterion* of *ontological* *commitment*. Is it *mechanical*? What is the *translation* *problem*?
6. What is *ontological* *relativity*? Does it *undermine* the *realism/anti-realism* *debate*?
7. State the *indispensability* *argument*. Is it *sound*? What is the *strongest* *objection*?
8. Is the *nominalist* *reformulation* of *physics* *possible*? What does the *answer* *imply* for the *indispensability* *argument*?
9. Is *parsimony* a *guide* to *truth*? What is the *best* *argument* for and *against*?
10. What is the *difference* *between* *quantitative* and *qualitative* *parsimony*? Which *matters* *more*?
11. Is *fictionalism* a *defensible* *strategy*? What is the *strongest* *objection*, and is it *decisive*?
12. What is the *difference* *between* *naturalized* *ontology*, *fundamental* *metaphysics*, and *deflationism*? Which is the *most* *defensible*?
13. What is the *ontological* *turn* in *anthropology*? Does it *threaten* the *objectivity* of *ontology*?
14. What does the *experimental* *philosophy* of *ontology* *show*? Does it *challenge* the *philosophical* *debate*?
15. “Ontology is *not* a *science*, and it is *not* a *language* *game*; it is the *study* of the *conditions* of *intelligibility* of *existence*.” Assess.

---

## Further Reading

- **Primary**: W. V. O. Quine, “On What There Is” (1948), in *From a Logical Point of View* (1953); Rudolf Carnap, “Empiricism, Semantics, and Ontology” (1950), in *Meaning and Necessity* (2nd ed., 1956); Alexius Meinong, “The Theory of Objects” (1904), in *Realism and the Background of Phenomenology* (ed. Chisholm, 1960).
- **On the logic of existence**: Gottlob Frege, *Foundations of Arithmetic* (1884), §53; Immanuel Kant, *Critique of Pure Reason* (1781/1787), A598/B626; the *Stanford Encyclopedia* entry, “Existence” (Nelson); the *essays* in *The Logic of Existence* (ed. McGinn, 2000).
- **On Meinong and the neo-Meinongians**: Meinong, “The Theory of Objects” (1904); Bertrand Russell, “On Denoting” (1905); Terence Parsons, *Nonexistent Objects* (1980); Edward Zalta, *Abstract Objects* (1983), and *Intensional Logic and the Metaphysics of Intentionality* (1988); Graham Priest, *Towards Non-Being* (2005); the *essays* in *The Philosophy of Alexius Meinong* (ed. Haller, 1972).
- **On Quine**: Quine, “On What There Is” (1948), and *Word and Object* (1960), Ch. 7; Quine, *Ontological Relativity and Other Essays* (1969); the *essays* in *The Philosophy of W. V. Quine* (ed. Hahn and Schilpp, 1986); the *survey* in Alex Orenstein, *W. V. O. Quine* (2002).
- **On indispensability**: Hilary Putnam, “Philosophy of Mathematics: A Report” (1964), and “Mathematics without Foundations” (1967); Hartry Field, *Science without Numbers* (1980), and *Realism, Mathematics and Modality* (1989); Penelope Maddy, “Indispensability and Practice” (1992), and *Naturalism in Mathematics* (1997); Mark Colyvan, *The Indispensability of Mathematics* (2001); the *Stanford Encyclopedia* entry, “Indispensability Arguments in the Philosophy of Mathematics” (Colyvan).
- **On parsimony**: Elliott Sober, *Simplicity* (1975), and *Ockham’s Razors* (2015); Michael Huemer, “When Is Parsimony a Virtue?” (2009); the *essays* in *Simplicity, Complexity and Modelling* (ed. Christie, 2011); the *Stanford Encyclopedia* entry, “Simplicity” (Baker).
- **On fictionalism**: Hartry Field, *Science without Numbers* (1980); Gideon Rosen, “Modal Fictionalism” (1990); Richard Joyce, *The Myth of Morality* (2001); Bas van Fraassen, *The Scientific Image* (1980); Kendall Walton, *Mimesis as Make-Believe* (1990); the *essays* in *Fictionalism in Metaphysics* (ed. Kalderon, 2005).
- **On the meta-debate**: Carnap, “Empiricism, Semantics, and Ontology” (1950); Eli Hirsch, *Quantifier Variance and Realism* (2011); Amie Thomasson, *Ontology Made Easy* (2015); Theodore Sider, *Writing the Book of the World* (2011); Jonathan Schaffer, “On What Grounds What” (2009), in *Metametaphysics* (ed. Chalmers, Manley, and Wasserman); the *essays* in *Metametaphysics* (2009).
- **On the ontological turn**: Eduardo Viveiros de Castro, “Cosmological Deixis and Amerindian Perspectivism” (1998), and *Cannibal Metaphysics* (2014); Philippe Descola, *Beyond Nature and Culture* (2005/2013); Martin Holbraad, *Truth in Motion* (2012); Martin Holbraad and Morten Axel Pedersen, *The Ontological Turn* (2017); the *critique* in the *essays* in *The Ontological Turn: A Critical Assessment* (ed. Paleček and Risjord, 2013).
- **On the experimental philosophy of ontology**: David Rose and Jonathan Schaffer, “Folk Mereology is Teleological” (2017); David Rose, “Folk Intuitions of Objecthood” (2017); the *survey* in the *Stanford Encyclopedia* entry, “Experimental Philosophy” (Knobe and Nichols).

---

> *A closing note.* This chapter has followed the *oldest* question in philosophy — what is there? — through the *logic* of existence, the *history* of the debate, the *criterion* of commitment, the *criteria* of parsimony, the *strategy* of fictionalism, and the *meta*-debate about the *nature* of the inquiry. The result is *not* a *settled* *ontology*, and it is *not* a *refutation* of *ontology*. It is a *method*: the *method* of *ontological* *commitment*, *regimentation*, *parsimony*, and *deflation*. The *method* is the *most* *important* *contribution* of the *analytic* *tradition* to *metaphysics*, and it is the *foundation* of the *rest* of Part III.

> *And a bridge.* The next chapter turns to *universals*, *properties*, and *abstract* *objects* — the *entities* that the *criterion* of *ontological* *commitment* *finds* in *science*, *mathematics*, and *ordinary* *language*. The *question* is the *first* *application* of the *method*: *should* we *commit* to *universals* (the *realist*), *tropes* (the *particularist*), or *nothing* (the *nominalist*)? The *debate* is the *oldest* *ontological* *debate* in the *Western* *tradition* (Plato, Aristotle, Ockham), and it is *still* *live*. The *next* *chapter* *examines* it, and it *asks* *what* the *criterion* of §3 *implies* for the *answer*.
