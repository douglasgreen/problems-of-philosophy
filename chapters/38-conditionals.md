# Chapter 37 — Conditionals, Counterfactuals, and Explanation in Language

> “If ‘if’ were the same as ‘⊃’, we should have no need of the word ‘if’ at all: we could write ‘⊃’ and be done with it. But we cannot, and the fact that we cannot is the beginning of wisdom about conditionals.”
> — a paraphrase of the observation that organizes the field, after Grice and Strawson

> “A counterfactual is true iff, in the nearest possible world in which its antecedent is true, its consequent is true.”
> — David Lewis, *Counterfactuals* (1973), the central thesis, in a sentence

> “The but-for test is the ordinary person’s test of causation, and it is also the law’s test, and it is also the philosopher’s test. Its simplicity is its virtue and its undoing.”
> — a formulation of the predicament, after Hart and Honoré

---

Part V has examined *language* — meaning (Ch. 31), truth (Ch. 32), paradox (Ch. 33), speech acts (Ch. 34), logic (Ch. 35), and the *a priori* (Ch. 36). This chapter examines the *single* *linguistic* *device* that *connects* the *whole* of the *part* to the *whole* of the *book*: the **conditional**.

The *conditional* — the “if … then …” — is the *most* *studied* *construction* in the *philosophy* of *language*, and it is *studied* *because* it is *indispensable* and *unanalyzable*. It is *indispensable* because it is the *form* in which *laws* are stated (Ch. 39), *dispositions* are described (Ch. 15, §5.3), *causes* are identified (Ch. 18, §2), *reasons* are given (Ch. 28), *promises* are made (Ch. 34), and *responsibility* is attributed (Ch. 27). It is *unanalyzable* because the *material* *conditional* (the *truth*-*functional* *analysis*) *fails* to *capture* the *ordinary* “if,” and *no* *alternative* has *achieved* *consensus*.

The *thesis* is that the *conditionals* are *not* a *single* *phenomenon* but a *family* — the *material*, the *indicative*, the *subjunctive*, the *counterfactual*, the *causal*, the *generic* — and that the *family* is *unified* by the *role* of *the* *conditional* in *inference* and *explanation* rather than by a *single* *semantics*. The *chapter’s* *diagnosis* is that the *debate* has *moved* from the *semantics* (the *truth* *conditions*) to the *pragmatics* (the *assertion* *conditions*) and to the *epistemology* (the *probabilistic* and *causal* *roles*), and that the *move* is *progress*: the *conditionals* are *understood* *best* when they are *understood* as *tools* of *reasoning* rather than as *descriptions* of *states* of *affairs*.

The chapter proceeds in eight movements. §1 examines the material conditional and its paradoxes. §2 examines the indicative/subjunctive distinction and the strict conditional. §3 examines the Stalnaker–Lewis semantics. §4 examines the probabilistic and causal approaches. §5 examines counterfactuals in science, law, and morals. §6 examines generics, dispositions, and *ceteris paribus* claims. §7 examines the circularity worry. §8 gives an honest verdict.

---

## 1. The Material Conditional and the Paradoxes of Implication

### 1.1 The truth table

**The *definition***. The *material* *conditional* is *true* whenever the *antecedent* is *false* or the *consequent* is *true*.

$$
p \to q \quad \equiv_{\text{df}} \quad \neg p \vee q
$$

**The *truth* *table***.

| $p$ | $q$ | $p \to q$ |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | **T** |
| F | F | **T** |

**The *virtue***. The *material* *conditional* is *truth*-*functional* (the *truth* *value* is *determined* by the *truth* *values* of the *components*), and it is the *only* *truth*-*functional* *connective* that *preserves* *modus* *ponens* and *modus* *tollens* (the *Fregean* *argument*).

**The *significance***. The *material* *conditional* is the *foundation* of *classical* *logic* (Ch. 35, §2.1), and its *adequacy* to the *ordinary* “if” is the *question* of the *chapter*.

### 1.2 The paradoxes

**The *paradoxes* of *material* *implication***.

| The *paradox* | The *formula* | The *reading* | The *problem* |
|---|---|---|---|
| **Vacuity** | $\neg p \to (p \to q)$ | If not $p$, then if $p$ then $q$ | The *false* *antecedent* *makes* the *conditional* *true* |
| **Explosion** | $(p \wedge \neg p) \to q$ | A contradiction implies anything | The *irrelevant* *consequent* |
| **Positive paradox** | $p \to (q \to p)$ | A true proposition is implied by anything | The *irrelevant* *antecedent* |
| **Negative paradox** | $\neg p \to (p \to q)$ | A false proposition implies anything | The *irrelevant* *consequent* |

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *material* *conditional* is *true* whenever the *antecedent* is *false* (the *definition*).} \\
2. & \text{The *ordinary* “if” is *not* *true* whenever the *antecedent* is *false* (the *intuition*).} \\
\hline
3. & \therefore \text{The *material* *conditional* is *not* the *ordinary* “if” (the *paradoxes*).}
\end{array}
$$

**The *intuition***. “If it rains tomorrow, I will eat my hat” *seems* *false* (the *speaker* *does* not *intend* to *eat* the *hat*), and the *material* *conditional* *makes* it *true* *whenever* it *does* not *rain*. The *intuition* *conflicts* with the *truth* *table*.

### 1.3 The pragmatist response

**The *thesis*** (Grice, “Logic and Conversation,” 1975, §3; “Indicative Conditionals,” 1989, Ch. 4; the *contemporary* *literature*). The *material* *conditional* *is* the *meaning* of “if,” and the *apparent* *conflict* with the *intuition* is *pragmatic* (the *assertion* of a *conditional* *carries* an *implicature* that the *speaker* *does* not *know* the *antecedent* *to* be *false*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *material* *conditional* *captures* the *truth* *conditions* of "if".} \\
2. & \text{The *assertion* of a *conditional* *carries* the *implicature* that the *antecedent* is *possible* (the *maxim* of *quantity*: the *speaker* *would* *not* *assert* a *vacuous* *conditional*).} \\
3. & \text{The *implicature* *explains* the *intuition* (the *assertion* *seems* *false* because it *implicates* something *false*).} \\
\hline
4. & \therefore \text{The *material* *conditional* *is* the *conditional* (the *pragmatist* *response*).}
\end{array}
$$

**The *virtue***. The *response* *preserves* the *truth*-*functionality* (the *classical* *logic*), and it *explains* the *intuition* *without* *revising* the *semantics*.

**The *objections***.

**(i) The *‘*conditional* *assertion*’* *objection* (Edgington, “On Conditionals,” 1995; the *contemporary* *literature*). The *conditional* *assertion* is *not* a *mere* *implicature* (the *speaker* *who* *asserts* “if $p$ then $q$” *does* not *assert* $p \to q$; she *asserts* something *weaker*, the *conditional* *belief*; the *conditional* *assertion* *has* *different* *assertion* *conditions*).

**The *reply***. The *conditional* *assertion* *expresses* the *conditional* *belief* (the *degree* of *belief* in $q$ *given* $p$), and the *belief* *is* the *content* (the *Adams* *thesis*; §4.1). The *reply* *distinguishes* the *assertion* from the *proposition*, and it is *contested*.

**(ii) The *‘*nesting*’* *objection* (Gibbard, “Two Recent Theories of Conditionals,” 1981; the *contemporary* *literature*). The *material* *conditional* *cannot* *handle* the *nested* *conditionals* (“If $p$, then if $q$ then $r$”), and the *nesting* *requires* a *non*-*truth*-*functional* *semantics*.

**The *reply***. The *material* *conditional* *can* be *nested* (the *semantics* *allows* the *nesting*), and the *intuition* is *explained* by the *implicature* (the *nested* *implicature*). The *reply* is *contested*.

### 1.4 The state of the material conditional

**The *assessment***. The *material* *conditional* is *defensible* as the *semantics* of “if” and *indefensible* as the *analysis* of the *ordinary* *use*.

| The *position* | The *claim* | The *strength* | The *weakness* |
|---|---|---|---|
| **Material** | “If” = $\to$ | Truth-functional; classical | The paradoxes |
| **Pragmatist** | “If” = $\to$ + implicature | Explains the intuition | The conditional assertion |
| **Strict** | “If” = $\Box(\to)$ | Modal; necessity | The vacuities |
| **Variably strict** | “If” = the nearest world | Similarity; counterfactuals | The limit assumption |
| **Probabilistic** | “If” = conditional probability | Fits the degrees of belief | The triviality |

**The *most* *defensible* *position***. A *qualified* *pragmatism*: the *material* *conditional* *captures* the *truth* *conditions* of the *assertive* “if” (the *indicative* “if” *in* the *assertive* *context*), and the *conditional* *assertion* *expresses* a *conditional* *belief* that is *not* *fully* *captured* by the *truth* *conditions* (the *Adams* *insight*), and the *subjunctive* “if” *requires* a *different* *semantics* (§3), *qualified* by the *admission* that the *pragmatist* *response* is *incomplete*.

---

## 2. Indicative and Subjunctive Conditionals

### 2.1 The distinction

**The *distinction***. The *indicative* *conditional* (“If Oswald did not shoot Kennedy, someone else did”) and the *subjunctive* *conditional* (“If Oswald had not shot Kennedy, someone else would have”) *differ* in their *truth* *conditions*, and the *difference* *shows* that the *two* are *different* *kinds* of *conditional*.

**The *example*** (Adams, “Subjunctive and Indicative Conditionals,” 1970).

| The *conditional* | The *truth* *value* | The *reason* |
|---|---|---|
| **Indicative**: “If Oswald did not shoot Kennedy, someone else did” | *True* (the *evidence* *supports* it) | The *actual* *world* *contains* a *shooter* |
| **Subjunctive**: “If Oswald had not shot Kennedy, someone else would have” | *False* (the *intention* was *Oswald's* alone) | The *possible* *world* *differs* from the *actual* |

**The *structure***. The *indicative* *conditional* *evaluates* the *consequent* *given* the *antecedent* *in* the *actual* *world* (the *epistemic* *conditional*), and the *subjunctive* *conditional* *evaluates* the *consequent* *in* the *nearest* *world* *where* the *antecedent* *obtains* (the *counterfactual*).

**The *significance***. The *distinction* *undermines* the *uniform* *analysis* (there is *no* *single* *semantics* for both), and it *motivates* the *variably* *strict* *semantics* (the *Stalnaker*–*Lewis* *account*; §3).

### 2.2 The strict conditional

**The *thesis*** (C. I. Lewis, *A Survey of Symbolic Logic*, 1918; *Symbolic Logic*, 1932). “If $p$ then $q$” *means* “Necessarily, if $p$ then $q$” (the *strict* *conditional*, $\Box(p \to q)$).

**The *structure***.

$$
p \Rightarrow q \quad \equiv_{\text{df}} \quad \Box(p \to q)
$$

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *material* *conditional* *fails* on the *paradoxes* (the *vacuity*, the *explosion*).} \\
2. & \text{The *failure* *is* *explained* by the *absence* of *necessity* (the *material* *conditional* *is* *contingent* on the *truth* *values*).} \\
3. & \text{The *conditional* *requires* the *necessity* (the *connection* *between* the *antecedent* and the *consequent*).} \\
\hline
4. & \therefore \text{The *conditional* is the *strict* *conditional* (the *modal* *analysis*).}
\end{array}
$$

**The *virtue***. The *strict* *conditional* *captures* the *necessity* of the *connection*, and it *avoids* the *vacuous* *truth* (the *false* *antecedent* does *not* *necessitate* the *consequent*).

**The *objections***.

**(i) The *‘*vacuity*’* *objection*. The *strict* *conditional* is *still* *vacuously* *true* when the *antecedent* is *impossible* (the *impossible* *antecedent* *necessitates* *everything*), and the *vacuity* is *not* *avoided*.

**The *reply*** (the *variably* *strict* *account*; §3). The *variably* *strict* *conditional* *avoids* the *vacuity* by the *similarity* *ordering* (the *nearest* *world* *where* the *antecedent* *obtains*), and the *reply* *replaces* the *strict* *conditional* with the *variably* *strict* *one*.

**(ii) The *‘*no* *ordinary* *use*’* *objection*. The *strict* *conditional* *requires* the *modal* *analysis*, and the *ordinary* *use* of “if” is *not* *modal* (the *assertion* *does* not *require* the *necessity*).

**The *reply***. The *ordinary* *use* *is* the *epistemic* *conditional* (the *conditional* *belief*), and the *reply* *distinguishes* the *epistemic* from the *metaphysical* *modality*. The *reply* is *contested*.

### 2.3 The strictness and the conditional belief

**The *thesis***. The *indicative* *conditional* *expresses* a *conditional* *belief* (the *degree* of *belief* in the *consequent* *given* the *antecedent*), and the *conditional* *belief* is *not* a *truth*-*functional* *state* (the *Adams* *thesis*; §4.1).

**The *structure*.

$$
\text{Belief}(\text{if } p, q) = P(q \mid p)
$$

**The *virtue***. The *account* *fits* the *degrees* of *belief* (the *Bayesian* *framework*; Ch. 10, §4), and it *explains* the *assertion* *conditions* of the *indicative* *conditional*.

**The *objections***.

**(i) The *triviality* *objection* (Lewis, “Probabilities of Conditionals and Conditional Probabilities,” 1976; §4.2). The *identification* of the *conditional* *belief* with the *conditional* *probability* *trivialises* the *probability* *theory* (the *conditional* *is* *either* *trivial* or *not* *a* *proposition*).

**The *reply*** (Adams 1975; Edgington 1995). The *conditional* *is* *not* a *proposition* (there is *no* *truth* *value*), and the *triviality* *is* *avoided* by *denying* the *propositionality*. The *reply* *abandons* the *truth*-*conditional* *semantics* (Ch. 31, §3.2), and it is *contested*.

**(ii) The *‘*no* *truth* *value*’* *objection*. The *conditional* *is* *assertible* or *not* *assertible*, and the *assertibility* is *not* the *truth* (the *truth* *is* *not* the *same* as the *assertibility*; Ch. 32, §9).

**The *reply*** (the *expressivist* *account*; Gibbard 1981; the *contemporary* *literature*). The *conditional* *expresses* a *conditional* *attitude* (a *plan*, a *policy*), and the *expressivism* *grounds* the *assertion* in the *attitude*. The *reply* is *contested*.

### 2.4 The state of the distinction

**The *assessment***. The *indicative*/*subjunctive* *distinction* is *real*, and the *semantics* of the *two* is *different*.

| The *conditional* | The *semantics* | The *proponent* |
|---|---|---|
| **Indicative** | The *material* / the *conditional* *belief* / the *epistemic* | Grice; Adams; Edgington |
| **Subjunctive** | The *variably* *strict* / the *counterfactual* | Stalnaker; Lewis |
| **Both** | The *variably* *strict* (uniform) | Stalnaker (1968); Lewis (1973) |

**The *most* *defensible* *position***. A *dual* *account*: the *indicative* *conditional* *expresses* a *conditional* *belief* (the *Adams* *thesis*), and the *subjunctive* *conditional* *is* a *counterfactual* *proposition* (the *Stalnaker*–*Lewis* *semantics*), and the *two* are *distinct* (the *dual* *insight*), *qualified* by the *admission* that the *relationship* between the *two* is *contested*.

---

## 3. Stalnaker and Lewis: Possible-Worlds Semantics

### 3.1 The core idea

**The *thesis*** (Stalnaker, “A Theory of Conditionals,” 1968; Lewis, *Counterfactuals*, 1973). A *counterfactual* is *true* iff the *consequent* *obtains* in the *nearest* *worlds* *in* which the *antecedent* *obtains*.

**The *semantic* *clause***.

$$
\llbracket p \ \Box\!\to\ q \rrbracket^w = 1 \quad \text{iff} \quad \forall v \in f(w, p)\, (\llbracket q \rrbracket^v = 1)
$$

where $f(w, p)$ is the *set* of *worlds* *nearest* to $w$ *in* which $p$ *obtains*.

**The *structure***. The *similarity* *ordering* (the *“*closest*”* *worlds*) *determines* the *truth* of the *counterfactual*, and the *ordering* *depends* on the *context* (the *different* *respects* of *similarity*, the *law*, the *fact*, the *causation*).

**The *virtue***. The *semantics* *captures* the *counterfactual* *dependence*, and it *provides* a *formal* *account* of the *counterfactuals*, and it *fits* the *causal* *reasoning* (Ch. 18, §2).

### 3.2 The similarity ordering

**The *problem***. What *makes* one *world* *closer* to the *actual* *world* than another?

**The *criteria*** (Lewis 1973, §3.4; the *contemporary* *literature*).

| The *criterion* | The *weight* | The *example* |
|---|---|---|
| **The *laws*** | The *higher* *weight* (the *similarity* *of* the *laws* is *more* *important* *than* the *similarity* *of* the *particular* *facts*) | The *world* *with* the *same* *laws* *and* a *different* *coin* *toss* |
| **The *particular* *facts*** | The *lower* *weight* | The *world* *with* the *same* *facts* *and* a *different* *law* |
| **The *causal* *history*** | The *intermediate* *weight* | The *world* *where* the *antecedent* *is* *brought* *about* *differently* |

**The *argument***. The *similarity* *is* *not* *a* *single* *dimension* (the *laws*, the *facts*, the *history*), and the *ordering* *depends* on the *weights*, and the *weights* *determine* the *truth* *value* of the *counterfactual*.

**The *significance***. The *ordering* *explains* the *context*-*sensitivity* of the *counterfactuals* (the *same* *counterfactual* *can* be *true* *in* one *context* and *false* *in* another), and it *connects* the *semantics* to the *pragmatics* (Ch. 34, §5).

### 3.3 The limit assumption

**The *thesis*** (Lewis 1973, §1.4). The *counterfactual* *semantics* *requires* the *limit* *assumption*: the *antecedent* *worlds* *have* a *nearest* *world* (there is *no* *infinite* *regress* of *closer* *worlds*).

**The *argument***. If the *antecedent* is *true* in an *infinite* *sequence* of *worlds* *with* *no* *nearest* *world*, the *counterfactual* *cannot* be *evaluated* (there is *no* *set* $f(w, p)$), and the *vacuity* *returns*.

**The *responses***.

**(i) The *‘*limit* *assumption* *is* *false*’* *response* (Lewis 1973, §1.4; *non*-*well*-*founded* *ordering*). The *ordering* *can* be *non*-*well*-*founded*, and the *semantics* *is* *defined* by the *“*would* *be* *true* *in* some *world* *in* the *sequence*”* (the *limit* *assumption* is *not* *required*).

**The *reply***. The *semantics* *is* *more* *complex*, and the *reply* *avoids* the *assumption*. The *reply* is *influential* and *contested*.

**(ii) The *‘*Stalnaker* *assumption*’* *response*** (Stalnaker 1968, 1981). The *ordering* *satisfies* the *Stalnaker* *assumption* (there is a *unique* *nearest* *world*), and the *semantics* *is* *defined* by the *uniqueness*.

**The *objection***. The *uniqueness* *implies* the **conditional* *excluded* *middle*** (the *counterfactual* is *either* *true* *or* *false*, and *there* is *no* *truth*-*value* *gap*), and the *principle* is *contested* (the *indeterminacy* of the *counterfactuals*, the *“*if* *Bizet* *and* *Verdi* *had* *been* *compatriots*”* *case*; Quine, “Counterfactuals and the Logic of the World,” 1950).

**The *significance***. The *limit* *assumption* and the *conditional* *excluded* *middle* are *the* *most* *technical* *issues* in the *semantics*, and they *distinguish* the *Stalnaker* and the *Lewis* *accounts*.

### 3.4 The circularity worry

**The *problem*** (Fine, “Counterfactuals without Possible Worlds,” 2012; the *contemporary* *literature*). The *counterfactual* *semantics* *uses* the *possible* *worlds* (the *modal* *entities*; Ch. 16, §2), and the *possible* *worlds* *are* *defined* by the *counterfactuals* (the *worlds* *are* *the* *ways* the *world* *could* *be*), and the *definition* *is* *circular*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *counterfactual* is *analyzed* by the *possible* *worlds* (the *semantics*).} \\
2. & \text{The *possible* *worlds* are *defined* by the *counterfactuals* (the *worlds* *are* the *ways* the *world* *could* be; the *modality*).} \\
3. & \text{The *two* *definitions* *presuppose* each other.} \\
\hline
4. & \therefore \text{The *analysis* is *circular* (the *circularity* *worry*).}
\end{array}
$$

**The *responses***.

**(i) The *‘*no* *circularity*’* *response*** (Lewis 1973, Ch. 4; *On the Plurality of Worlds*, 1986, Ch. 4). The *possible* *worlds* are *concrete* *wholes* (Ch. 16, §2.2), and they *are* *not* defined by the *counterfactuals* (the *worlds* are *primitive*, and the *counterfactuals* *describe* the *relations* among them).

**The *reply***. The *reply* *avoids* the *circularity* by the *modal* *realism*, and the *reply* *imports* the *costs* of the *modal* *realism* (the *incredulous* *stare*, the *epistemic* *access*; Ch. 16, §2.2). The *reply* is *contested*.

**(ii) The *‘*no* *worlds*’* *response*** (Fine 2012; the *contemporary* *literature*). The *counterfactuals* *are* *primitive* (they are *not* *analyzed* by the *worlds*), and the *worlds* are *derived* (the *worlds* are *the* *models* of the *counterfactuals*).

**The *reply***. The *reply* *avoids* the *circularity* by the *primitivism*, and the *reply* *imports* the *costs* of the *primitivism* (the *unexplanatory*; Ch. 32, §7.3). The *reply* is *contested*.

### 3.5 The state of the semantics

**The *assessment***. The *variably* *strict* *semantics* is the *dominant* *account*, and it is *qualified* by the *circularity* and the *limit* *assumption*.

| The *account* | The *strength* | The *weakness* |
|---|---|---|
| **Stalnaker** | The unique nearest world | The conditional excluded middle |
| **Lewis** | The non-well-founded ordering | The limit assumption |
| **Fine** | The counterfactuals are primitive | The unexplanatory |
| **Lewis's realism** | The worlds are concrete | The incredible cost |

**The *most* *defensible* *position***. A *qualified* *Lewisian* *semantics*: the *counterfactuals* *are* *analyzed* by the *similarity* *ordering* (the *Lewis* *insight*), and the *ordering* *is* *context*-*sensitive* (the *contextualist* *insight*), and the *worlds* *are* *ersatz* (the *abstract* *representations*, not the *concrete* *wholes*; Ch. 16, §2.3), *qualified* by the *admission* that the *circularity* *worry* *remains*.

---

## 4. Probabilistic and Causal Approaches

### 4.1 Adams's thesis

**The *thesis*** (Adams, *The Logic of Conditionals*, 1975; Edgington, “On Conditionals,” 1995). The *assertibility* of an *indicative* *conditional* *equals* the *conditional* *probability* of the *consequent* *given* the *antecedent*.

**The *structure***.

$$
\text{Assertibility}(p \to q) = P(q \mid p)
$$

**The *virtue***. The *thesis* *fits* the *degrees* of *belief* (the *Bayesian* *framework*), and it *explains* the *ordinary* *use* (the *conditional* *belief* is the *degree* of *confidence* *in* $q$ *given* $p$).

**The *argument*** (the *Ramsey* *test*; Ramsey, *Foundations of Mathematics*, 1929, p. 143).

> “If two people are arguing ‘If $p$, will $q$?’ and are both in doubt as to $p$, they are adding $p$ hypothetically to their stock of knowledge and arguing on that basis about $q$.”

**The *significance***. The *Ramsey* *test* *provides* the *operational* *criterion* for the *assertion* of a *conditional*, and the *test* *grounds* the *Adams* *thesis* in the *practice* of *reasoning*.

### 4.2 The triviality results

**The *thesis*** (Lewis, “Probabilities of Conditionals and Conditional Probabilities,” 1976; “Probabilities of Conditionals and Conditional Probabilities II,” 1986). The *identification* of the *conditional* *probability* with the *probability* *of* a *conditional* *proposition* *trivialises* the *probability* *theory*.

**The *argument* (the *simplified* *form*; the *assumptions* are the *conditionalization*, the *substitution*, the *conditional* *is* a *proposition*).

$$
\begin{array}{ll}
1. & \text{Assume } P(p \to q) = P(q \mid p) \text{ (the *Adams* *thesis*).} \\
2. & \text{The *thesis* *implies* that the *conditional* is a *proposition* (the *truth*-*conditional* *semantics*).} \\
3. & \text{The *proposition* *must* be *either* the *material* *conditional* *or* a *stronger* *conditional*.} \\
4. & \text{The *material* *conditional* *fails* the *thesis* (the *triviality*).} \\
5. & \text{The *stronger* *conditional* *fails* the *substitution* (the *triviality*).} \\
\hline
6. & \therefore \text{The *thesis* *implies* the *triviality* (the *conditional* *probability* *is* *either* 0 *or* 1).}
\end{array}
$$

**The *consequence***. The *conditional* *is* *not* a *proposition* (there is *no* *truth* *value*), and the *Adams* *thesis* *requires* the *expressivism* (the *conditional* *expresses* a *conditional* *belief*, not a *proposition*).

**The *responses***.

**(i) The *‘*no* *proposition*’* *response*** (Edgington 1995). The *conditional* *is* *not* a *proposition*, and the *triviality* *is* *avoided* by the *denial* of the *propositionality*. The *reply* *abandons* the *truth*-*conditional* *semantics*, and it is *contested* (Ch. 31, §3.2).

**(ii) The *‘*restricted* *thesis*’* *response*** (the *contemporary* *literature*; Douven; the *“*Stalnaker* *conditional*”*). The *thesis* *holds* *only* for the *indicative* *conditionals* (the *subjunctive* *conditionals* *are* *propositions*), and the *restriction* *avoids* the *triviality*. The *reply* is *contested*.

**(iii) The *‘*three*-*valued*’* *response*** (the *contemporary* *literature*; McGee; the *“*Stalnaker*–*Belnap*”* *semantics*). The *conditional* *has* a *third* *truth* *value* (the *indeterminate*), and the *value* *avoids* the *triviality*. The *reply* is *contested*.

### 4.3 The causal approaches

**The *thesis*** (Pearl, *Causality*, 2000; *Causality*, 2nd ed., 2009; Spirtes, Glymour & Scheines, *Causation, Prediction, and Search*, 1993; Ch. 18, §3.2). The *counterfactuals* are *defined* by the *structural* *equations* (the *causal* *models*), and the *interventions* *specify* the *counterfactual* *worlds*.

**The *structure***.

$$
Y_x(u) = \text{the *value* of } Y \text{ *under* the *intervention* } do(X = x) \text{ *in* the *world* } u
$$

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *counterfactual* "if } X \text{ were } x, Y \text{ would be } y" \text{ is *defined* by the *intervention* (the *do*-*calculus*).} \\
2. & \text{The *intervention* is *specified* by the *structural* *equations* (the *causal* *model*).} \\
\hline
3. & \therefore \text{The *counterfactual* is *grounded* in the *causal* *model* (the *causal* *approach*).}
\end{array}
$$

**The *virtue***. The *account* *provides* a *formal* *semantics* for the *counterfactuals*, and it *fits* the *causal* *inference* (Ch. 18, §3.2), and it *avoids* the *possible*-*worlds* *ontology* (the *models* are *the* *worlds*).

**The *objections***.

**(i) The *‘*no* *structural* *equations*’* *objection*. The *structural* *equations* *presuppose* the *causal* *structure* (the *graph*, the *mechanisms*), and the *structure* is *not* *given* by the *data* (the *generality* *problem*; Ch. 8, §4.3).

**The *reply***. The *structure* is *inferred* from the *data* (the *causal* *discovery*; the *PC* *algorithm*), and the *reply* *grounds* the *structure* in the *inference*. The *reply* is *contested*.

**(ii) The *‘*no* *determinism*’* *objection*. The *structural* *equations* *presuppose* the *determinism* (the *value* of $Y$ is *determined* by the *parents*), and the *determinism* is *false* (the *quantum* *indeterminacy*; Ch. 19, §5).

**The *reply***. The *equations* *include* the *error* *terms* (the *stochastic* *equations*; the *probabilistic* *causal* *models*), and the *reply* *extends* the *framework*. The *reply* is *contested*.

### 4.4 The state of the probabilistic and causal approaches

**The *assessment***. The *probabilistic* and *causal* *approaches* are *influential*, and they *face* the *technical* *objections*.

| The *approach* | The *strength* | The *weakness* |
|---|---|---|
| **Adams** | Fits the degrees of belief | The triviality |
| **Lewis** | The formal semantics | The triviality |
| **Edgington** | The expressivism | The no-proposition |
| **Pearl** | The formal causal model | The structural equations |
| **Spirtes et al.** | The causal discovery | The generality |

**The *most* *defensible* *position***. A *qualified* *pluralism*: the *indicative* *conditional* *expresses* a *conditional* *belief* (the *Adams* *insight*), the *subjunctive* *conditional* is a *counterfactual* *proposition* (the *Lewis* *insight*), the *causal* *conditionals* are *grounded* in the *structural* *models* (the *Pearl* *insight*), and the *three* *are* *distinct* *but* *connected* (the *pluralist* *insight*), *qualified* by the *admission* that the *triviality* and the *structural* *equations* *remain* *unresolved*.

---

## 5. Counterfactuals in Science, Law, and Morals

### 5.1 Science

**The *role***. The *counterfactuals* are *indispensable* in *science* (the *laws* are *counterfactual* *supporting*; the *dispositions* are *counterfactual*; the *causal* *claims* are *counterfactual*).

**The *examples***.

| The *domain* | The *counterfactual* | The *role* |
|---|---|---|
| **Physics** | “If the mass were doubled, the acceleration would halve” | The *law* *states* the *counterfactual* *dependence* |
| **Biology** | “If the gene were silenced, the protein would not be expressed” | The *experiment* *tests* the *counterfactual* |
| **Medicine** | “If the patient had received the drug, she would have survived” | The *causal* *attribution* |
| **Economics** | “If the interest rate were raised, the inflation would fall” | The *policy* *prediction* |

**The *significance***. The *counterfactuals* *connect* the *laws* to the *interventions* (Ch. 18, §3), and the *connection* is the *foundation* of the *experimental* *method*.

### 5.2 Law

**The *role***. The *law* *uses* the *counterfactuals* to *attribute* the *causation* (the *but*-*for* *test*; Ch. 18, §8.2), and the *attribution* *determines* the *liability*.

**The *tests***.

| The *test* | The *counterfactual* | The *account* |
|---|---|---|
| **But-for** | “But for the defendant's act, the harm would not have occurred” | The *necessary* *condition* |
| **NESS** | “The act is a *necessary* *element* of a *sufficient* *set*” | The *sufficient* *set* |
| **Proximate** | “The harm was *foreseeable*” | The *normative* *limit* |

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *but*-*for* *test* *requires* the *counterfactual} \neg a \ \Box\!\to\ \neg h \text{ (the *harm* *would* *not* have *occurred* *without* the *act*).} \\
2. & \text{The *counterfactual* *requires* the *nearest* *world* (the *similarity* *ordering*; §3.2).} \\
3. & \text{The *ordering* *determines* the *attribution* (the *causal* *claim*).} \\
\hline
4. & \therefore \text{The *legal* *attribution* *presupposes* the *counterfactual* *semantics* (the *law* *is* *a* *test* *case* for the *semantics*).}
\end{array}
$$

**The *significance***. The *legal* *cases* *test* the *counterfactual* *semantics* (the *overdetermination*, the *pre-emption*, the *omission*; Ch. 18, §2.2–2.3), and the *tests* *show* that the *but*-*for* *test* *fails* for the *complex* *cases*.

### 5.3 Morals

**The *role***. The *moral* *reasoning* *uses* the *counterfactuals* (the *responsibility*, the *praise* and *blame*, the *regret*, the *“*what* *if*”* *reasoning*; Ch. 27, §8).

**The *examples***.

| The *case* | The *counterfactual* | The *moral* *stake* |
|---|---|---|
| **The *trolley*** | “If I pull the switch, one dies instead of five” | The *utilitarian* *calculation* |
| **The *negligence*** | “If the driver had braked, the accident would not have occurred” | The *responsibility* |
| **The *regret*** | “If I had acted differently, the outcome would have been better” | The *moral* *emotion* |

**The *significance***. The *moral* *counterfactuals* *connect* the *responsibility* to the *causation* (Ch. 27, §8.3), and the *connection* is the *foundation* of the *retributive* *justice* (Ch. 26, §9.3).

### 5.4 The structure of responsibility

**The *thesis***. The *responsibility* *requires* the *counterfactual* *dependence* (the *agent* *could* have *done* *otherwise*, and the *outcome* *depends* on the *action*), and the *dependence* is *the* *counterfactual* *relation*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *agent* is *responsible* for the *action* when the *action* *makes* *a* *difference* (the *difference*-*making* *condition*).} \\
2. & \text{The *difference* is *captured* by the *counterfactual} (the \textit{action} \ \Box\!\to\ \textit{outcome}). \\
3. & \text{The *counterfactual* *depends* on the *nearest* *world* (the *similarity* *ordering*).} \\
\hline
4. & \therefore \text{The *responsibility* *is* *grounded* in the *counterfactual* *dependence* (the *structure* *of* *responsibility*).}
\end{array}
$$

**The *virtue***. The *account* *connects* the *responsibility* to the *causation* (the *difference*-*making*; Ch. 18, §2), and it *fits* the *law* (the *but*-*for* *test*) and the *morals* (the *regret*).

**The *objections*.

**(i) The *‘*no* *counterfactual*’* *objection*. The *responsibility* *does* not *require* the *counterfactual* (the *Frankfurt* *cases*; Ch. 27, §3.2), and the *counterfactual* *account* *fails*.

**The *reply***. The *responsibility* *requires* the *counterfactual* *only* *for* the *difference*-*making* (the *causal* *responsibility*), and the *Frankfurt* *cases* *concern* the *attributability* (the *moral* *responsibility*), and the *reply* *distinguishes* the *two*. The *reply* is *contested*.

**(ii) The *‘*no* *nearest* *world*’* *objection*. The *counterfactual* *depends* on the *nearest* *world* (the *similarity* *ordering*), and the *ordering* is *context*-*sensitive* (the *different* *verdicts* *in* the *different* *contexts*), and the *responsibility* *should* *not* be *context*-*sensitive*.

**The *reply*** (the *contemporary* *literature*). The *responsibility* *is* *context*-*sensitive* (the *different* *standards* in the *different* *courts*), and the *reply* *grounds* the *sensitivity* in the *practice*. The *reply* is *contested*.

### 5.5 The state of the applications

**The *assessment***. The *counterfactuals* are *indispensable* in *science*, *law*, and *morals*, and the *applications* *test* the *semantics*.

| The *domain* | The *role* | The *test* *case* |
|---|---|---|
| **Science** | The laws, the dispositions | The quantum *counterfactuals* |
| **Law** | The causation, the liability | The overdetermination |
| **Morals** | The responsibility, the regret | The Frankfurt cases |

**The *most* *defensible* *position***. A *qualified* *dependence*: the *counterfactuals* *ground* the *causal* and the *moral* *responsibility* (the *difference*-*making* *insight*), and the *dependence* is *not* *sufficient* (the *attributability* *insight*), and the *combination* is *defensible*, *qualified* by the *admission* that the *counterfactual* *semantics* *remains* *contested*.

---

## 6. Generics, Dispositions, and Ceteris Paribus Claims

### 6.1 Generics

**The *phenomenon***. The *generic* *statements* (“Tigers are striped,” “Boys don't cry,” “Mosquitoes carry malaria”) *express* *generalizations* that *tolerate* *exceptions* (the *three*-*legged* *tiger*, the *boy* who *cries*).

**The *structure***.

| The *statement* | The *logical* *form* | The *exception* |
|---|---|---|
| **Universal** | $\forall x\, (\mathrm{Tiger}(x) \to \mathrm{Striped}(x))$ | The *three*-*legged* *tiger* |
| **Generic** | $\mathrm{Gen}\, x\, (\mathrm{Tiger}(x); \mathrm{Striped}(x))$ | The *three*-*legged* *tiger* *is* *tolerated* |

**The *theories***.

| The *theory* | The *claim* | The *proponent* |
|---|---|---|
| **Normalcy** | The *generic* *holds* *in* the *normal* *cases* | the *contemporary* *literature* (Nickel; the *“*normal* *case*”*) |
| **Prevalence** | The *generic* *holds* *for* *most* | the *frequency* *account* |
| **Cognitive** | The *generic* *expresses* a *cognitive* *schema* | the *psychological* *tradition* |
| **Probabilistic** | The *generic* *holds* *with* *a* *high* *probability* | the *Bayesian* *account* |

**The *significance***. The *generics* *connect* the *conditionals* to the *kind* *terms* (Ch. 15, §5.1) and to the *laws* (Ch. 39, §2), and the *connection* *shows* that the *conditional* *is* *not* a *single* *device* (the *generic* *conditional* *is* *different* from the *singular* *conditional*).

### 6.2 Dispositions

**The *phenomenon***. The *dispositions* (“The glass is fragile,” “The sugar is soluble”) *express* the *counterfactual* *properties* (the *glass* *would* *break* *if* *struck*; the *sugar* *would* *dissolve* *if* *placed* *in* *water*; Ch. 15, §5.3).

**The *structure***.

$$
\text{Fragile}(x) \quad \text{iff} \quad \forall s\, (\mathrm{Struck}(x, s) \ \Box\!\to\ \mathrm{Breaks}(x))
$$

**The *theories***.

| The *theory* | The *claim* | The *proponent* |
|---|---|---|
| **Simple conditional** | The *disposition* is the *counterfactual* | the *classical* *analysis* |
| **Causal basis** | The *disposition* is *grounded* in the *categorical* *basis* (Ch. 15, §5.3) | Armstrong; Lewis |
| **Finkish** | The *disposition* *can* be *blocked* by the *stimulus* (the *finkish* *case*) | Martin (1994); Lewis (1997) |
| **Powers** | The *disposition* is a *power* (the *essence*; Ch. 18, §6) | Bird; Mumford |

**The *finkish* *problem*** (Martin, “Dispositions and Conditionals,” 1994). The *disposition* *can* be *blocked* (the *glass* is *fragile*, and the *striking* *activates* a *protective* *device* that *prevents* the *breaking*), and the *simple* *counterfactual* *fails* (the *glass* *would* *not* *break* *if* *struck*), and the *analysis* *requires* the *idealized* *conditions* (the *ceteris* *paribus* *clause*; §6.3).

**The *significance***. The *dispositions* *connect* the *conditionals* to the *properties* (Ch. 15, §5.3) and to the *laws* (Ch. 18, §6), and the *connection* *shows* that the *conditional* is *at* the *heart* of the *metaphysics*.

### 6.3 Ceteris paribus claims

**The *phenomenon***. The *ceteris* *paribus* *claims* (“All other things being equal, if the price rises, the demand falls”) *express* *generalizations* that *hold* *under* the *idealized* *conditions* (the *special* *sciences*; Ch. 39, §2).

**The *structure***.

$$
\text{Ceteris paribus, if } P \text{ then } Q \quad \equiv \quad \Box_{\text{ideal}}(P \to Q)
$$

**The *theories***.

| The *theory* | The *claim* | The *proponent* |
|---|---|---|
| **Eliminativism** | The *ceteris* *paribus* *claims* are *not* *laws* (they are *rules* of *thumb*) | the *Humean* *orthodoxy* |
| **Anti-eliminativism** | The *claims* are *laws*, but *different* in *kind* | Cartwright; Mitchell |
| **Mechanism** | The *claims* *describe* *mechanisms* | the *mechanist* *tradition* (Ch. 21, §4.2) |

**The *significance***. The *ceteris* *paribus* *claims* *connect* the *conditionals* to the *special* *sciences* (the *biology*, the *economics*), and the *connection* *shows* that the *conditional* is *the* *form* of the *special*-*scientific* *laws*.

### 6.4 The state of the generics and dispositions

**The *assessment***. The *generics*, the *dispositions*, and the *ceteris* *paribus* *claims* are *all* *conditional* *constructions*, and the *constructions* *test* the *conditional* *semantics*.

| The *construction* | The *challenge* | The *account* |
|---|---|---|
| **Generics** | The exceptions | The normalcy / the prevalence |
| **Dispositions** | The finkish cases | The causal basis / the powers |
| **Ceteris paribus** | The idealization | The mechanism / the anti-eliminativism |

**The *most* *defensible* *position***. A *qualified* *pluralism*: the *generics*, the *dispositions*, and the *ceteris* *paribus* *claims* are *distinct* *conditional* *constructions* (the *pluralist* *insight*), and the *constructions* *share* the *counterfactual* *core* (the *unifying* *insight*), and the *core* is *the* *similarity* *ordering* (the *Lewis* *insight*), *qualified* by the *admission* that the *idealization* and the *finkish* *cases* *remain* *unresolved*.

---

## 7. Conditionals and the Analysis of Causation

### 7.1 The circularity worry

**The *problem*** (the *contemporary* *literature*; Ch. 18, §2.4). The *causation* is *analyzed* by the *counterfactuals* (the *Lewis* *analysis*; Ch. 18, §2.1), and the *counterfactuals* are *analyzed* by the *causation* (the *similarity* *ordering* *depends* on the *causal* *structure*; §3.2), and the *two* *analyses* *presuppose* each other.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *causation* is *analyzed* by the *counterfactual} (\neg c \ \Box\!\to\ \neg e; \text{ Ch. 18, §2.1}).} \\
2. & \text{The *counterfactual* is *analyzed* by the *similarity* *ordering* (the *nearest* *world*; §3.2).} \\
3. & \text{The *ordering* *depends* on the *causal* *structure* (the *legal* *regularities*, the *causal* *laws*).} \\
\hline
4. & \therefore \text{The *two* *analyses* *presuppose* each other (the *circularity* *worry*).}
\end{array}
$$

**The *consequence***. The *counterfactual* *analysis* of *causation* *fails* (the *circularity*), and the *causal* *analysis* of the *counterfactuals* *fails* (the *circularity*), and the *two* *notions* *must* be *taken* *as* *primitive* (or *analyzed* by a *third* *notion*).

### 7.2 The responses

**The *responses***.

**(i) The *‘*no* *circularity*’* *response*** (Lewis 1973, Ch. 4; *Philosophical Papers*, Vol. II, 1986, “Postscripts to ‘Causation’”). The *similarity* *ordering* *does* not *depend* on the *causal* *structure* (the *ordering* is *defined* by the *laws*, the *facts*, and the *history*; the *causal* *structure* is *derived* from the *ordering*).

**The *objection***. The *ordering* *does* *depend* on the *laws*, and the *laws* *are* *causal* (the *laws* *specify* the *causal* *mechanisms*), and the *reply* *is* *circular*. The *reply* is *contested*.

**(ii) The *‘*causal* *primitive*’* *response*** (the *contemporary* *literature*; Woodward, *Making Things Happen*, 2003, Ch. 2; Pearl 2000, Ch. 7). The *causation* is *primitive* (the *interventionist* *account*; Ch. 18, §3), and the *counterfactuals* are *defined* by the *interventions*, and the *two* *are* *distinct* (the *intervention* *is* a *causal* *notion*, and the *counterfactual* is *defined* by it).

**The *objection***. The *intervention* *presupposes* the *causation* (the *intervention* *is* a *causal* *process*), and the *reply* *is* *circular*. The *reply* is *contested*.

**(iii) The *‘*grounding*’* *response*** (the *contemporary* *literature*; Ch. 16, §3.3; Ch. 21, §6.3). The *causation* *grounds* the *counterfactuals* (the *causal* *relation* *grounds* the *counterfactual* *dependence*), and the *grounding* *is* *not* *circular* (the *two* *are* *different* *relations*).

**The *objection***. The *grounding* *is* *mysterious* (the *nature* of *grounding*; Ch. 22, §2.5), and the *reply* *is* *contested*.

### 7.3 The interventionist resolution

**The *thesis*** (Woodward 2003, Ch. 2; Ch. 18, §3.1; the *contemporary* *literature*). The *causation* is *defined* by the *intervention* (the *manipulation*), and the *counterfactuals* are *defined* by the *structural* *equations* (the *interventions*), and the *two* *are* *distinct* (the *intervention* is the *primitive*, and the *counterfactual* is *derived*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The *causation* is *defined* by the *intervention} (X \text{ causes } Y \text{ iff the *intervention* on } X \text{ changes } Y; \text{ Ch. 18, §3.1}). \\
2. & \text{The *counterfactual* is *defined* by the *intervention} (Y_x \text{ is the *value* of } Y \text{ *under* the *intervention*}; \text{ §4.3}). \\
3. & \text{The *two* *definitions* *share* the *intervention* (the *primitive*), and the *two* *are* *distinct* (the *causal* relation, the *counterfactual* *value*).} \\
\hline
4. & \therefore \text{The *circularity* is *broken* by the *intervention* (the *interventionist* *resolution*).}
\end{array}
$$

**The *virtue***. The *resolution* *breaks* the *circularity* (the *intervention* is *primitive*, and the *two* *notions* are *derived*), and it *fits* the *causal* *inference* (Ch. 18, §3.2) and the *experimental* *method* (the *manipulation*).

**The *objections***.

**(i) The *‘*no* *intervention*’* *objection*. The *intervention* *presupposes* the *causation* (the *intervention* *is* a *causal* *process*), and the *circularity* *returns*.

**The *reply***. The *intervention* is a *theoretical* *notion* (the *idealized* *manipulation*), and the *reply* *grounds* the *intervention* in the *structure* of the *model* (the *do*-*calculus*). The *reply* is *contested*.

**(ii) The *‘*no* *fundamental* *physics*’* *objection*. The *intervention* *is* *not* *available* in the *fundamental* *physics* (the *experimenter* *cannot* *manipulate* the *fundamental* *particles*), and the *resolution* *is* *limited* to the *special* *sciences* (Ch. 18, §3.2).

**The *reply***. The *resolution* is *intended* for the *special* *sciences* (the *intervention* *is* a *macroscopic* *notion*), and the *reply* *accepts* the *limitation*. The *reply* is *contested*.

### 7.4 The state of the circularity debate

**The *assessment***. The *circularity* *worry* is *unresolved*, and the *most* *defensible* *position* is a *qualified* *interventionism*: the *causation* and the *counterfactuals* *share* the *intervention* (the *primitive*; the *Woodward* *insight*), and the *two* *are* *distinct* (the *pluralist* *insight*), and the *intervention* *presupposes* the *causation* (the *circularity* *insight*; the *residual* *worry*), *qualified* by the *admission* that the *circularity* *is* *not* *fully* *broken*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **The *material* *conditional* is *not* the *ordinary* “if”.** The *paradoxes* (the *vacuity*, the *explosion*) are *decisive*, and the *pragmatist* *response* (the *implicature*) *explains* the *intuition* without *saving* the *analysis*.
- **The *indicative*/*subjunctive* *distinction* is *real*.** The *two* *conditionals* have *different* *truth* *conditions*, and the *Adams* *pair* *shows* the *difference*.
- **The *variably* *strict* *semantics* is the *dominant* *account*.** The *Stalnaker*–*Lewis* *semantics* *captures* the *counterfactual* *dependence*, and the *similarity* *ordering* is *the* *mechanism*.
- **The *triviality* *results* *constrain* the *probabilistic* *account*.** The *Lewis* *theorem* *shows* that the *Adams* *thesis* *requires* the *expressivism*, and the *propositional* *account* *fails*.
- **The *causal* *approaches* (the *structural* *equations*) *ground* the *counterfactuals* in the *causal* *models**, and the *account* *fits* the *causal* *inference*.
- **The *counterfactuals* are *indispensable* in *science*, *law*, and *morals*.** The *applications* *test* the *semantics*, and the *tests* *show* the *strengths* and the *limits*.
- **The *generics*, the *dispositions*, and the *ceteris* *paribus* *claims* are *conditional* *constructions*.** The *constructions* *share* the *counterfactual* *core*, and the *core* is *the* *similarity* *ordering*.
- **The *circularity* *worry* is *serious*.** The *causation* and the *counterfactuals* *presuppose* each other, and the *interventionist* *resolution* is *promising* and *incomplete*.

### 8.2 What is open

- **The *semantics* of the *indicative* *conditional.** Is the *conditional* a *proposition* (the *truth*-*conditional* *account*) or an *expression* of a *conditional* *belief* (the *expressivist* *account*)?
- **The *similarity* *ordering*.** What *determines* the *weight* of the *laws*, the *facts*, and the *history*?
- **The *limit* *assumption*.** Is there a *nearest* *world* (the *Stalnaker* *assumption*), or *only* a *sequence* (the *Lewis* *account*)?
- **The *causal* *priority*.** Is the *causation* *primitive* (the *interventionism*), or the *counterfactuals* *primitive* (the *Lewisian* *account*)?
- **The *generics* and the *dispositions*.** What is the *semantics* of the *generic* *conditional*, and the *finkish* *cases*?
- **The *circularity*.** Can the *causation* and the *counterfactuals* be *analyzed* *independently*?

### 8.3 The methodological lesson

The chapter is a case study in the method of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *distinction* between the *material*, the *indicative*, and the *subjunctive* *conditionals*.
- **Thought experiments** (§2 of Ch. 3) — the *Oswald* *pair*, the *Bizet*/*Verdi* *case*, the *finkish* *cases* — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *variably* *strict* *semantics*, the *structural* *equations*, the *triviality* *results* — is *essential* for the *field*.
- **Reflective equilibrium** (§4 of Ch. 3) is the *method* by which the *intuitions* and the *theories* are *adjusted*.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to *hold* the *question* *open*.

The honest verdict: the theory of conditionals is a field in transition. The classical positions are untenable in their pure forms; the contemporary positions are promising but incomplete; the debate is unresolved. The unresolved character is instructive: it shows what philosophical progress looks like — not a settled answer, but a sharper understanding of what the question is.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Material** | “If” = $\to$ | Truth-functional; classical | The paradoxes |
| **Pragmatist** | “If” = $\to$ + implicature | Explains the intuition | The conditional assertion |
| **Strict** | “If” = $\Box(\to)$ | Modal; necessity | The vacuities |
| **Variably strict (Stalnaker)** | The nearest world | The unique nearest world | The conditional excluded middle |
| **Variably strict (Lewis)** | The similarity ordering | The non-well-founded ordering | The limit assumption |
| **Adams** | The assertibility = the conditional probability | Fits the degrees of belief | The triviality |
| **Edgington** | The expressivism | Avoids the triviality | The no-proposition |
| **Pearl** | The structural equations | The formal causal model | The structural equations |
| **Primitivism** | The conditionals are primitive | Avoids the circularity | The unexplanatory |
| **Generic normalcy** | The generics hold in the normal cases | Fits the exceptions | The normalcy is vague |

The table is a map, not a verdict. The reader who wants to choose a position must decide which cost is acceptable — and the decision is a philosophical argument.

---

## Coda: The End of Part V

Part V began with *meaning* (Ch. 31), and it ends with *conditionals* (this chapter). The *arc* is a *return*: the *conditionals* are the *place* where the *semantics* (the *truth* *conditions*), the *pragmatics* (the *assertion* *conditions*), the *logic* (the *validity*), the *epistemology* (the *conditional* *belief*), and the *metaphysics* (the *causation*, the *dispositions*, the *laws*) *meet*. The *conditional* is the *hinge* of the *whole* *part*, and the *hinge* *shows* that the *philosophy* of *language* is *not* a *closed* *domain* but a *crossroads*.

### What Part V established

- **Meaning is a family of notions** — the sense, the reference, the use, the inferential role (Ch. 31).
- **Truth is real but thin**, and the *thinness* is *compatible* with a *robust* *metaphysics* (Ch. 32).
- **Paradox is real**, and the *solutions* are *all* *costly* (Ch. 33).
- **Speech is action**, and the *acts* are *constituted* by *social* *norms* (Ch. 34).
- **Logic is a tool**, and the *formalism* *makes* the *assumptions* *explicit* (Ch. 35).
- **The a priori is thin**, and the *logic* is the *strongest* *case* (Ch. 36).
- **Conditionals are a family**, and the *family* is *unified* by the *role* in *inference* and *explanation* (this chapter).

### What Part VI will do

Part VI turns to *science*, *explanation*, and *mathematics* — the *domains* where the *language* meets the *world* under the *most* *rigorous* *constraints*.

The *connection* is *direct*. The *conditionals* are the *form* of the *scientific* *laws* (Ch. 39, §1), the *explanation* (Ch. 38), the *confirmation* (Ch. 40), and the *mathematical* *application* (Ch. 43). The *next* *chapter* *turns* to *explanation*, and it *asks* the *question* that the *conditional* *presupposes*: *what* *is* *it* for a *theory* to *explain* the *world*?

### The hinge

The *chapter* — and *Part V* — *ends* with a *hinge*. The *hinge* is the *recognition* that the *conditionals* are *not* a *single* *semantic* *category* but a *family* of *devices* that *serve* the *reasoning*, and that the *philosophy* of *conditionals* is the *philosophy* of *reasoning* *applied* to the *connective* “if”.

**The *Ramsey* *formula***, *applied* to the *conditional*:

> “If two people are arguing ‘If $p$, will $q$?’ and are both in doubt as to $p$, they are adding $p$ hypothetically to their stock of knowledge and arguing on that basis about $q$.”

**The *closing* *thought***. The *conditional* is *the* *most* *ordinary* *and* the *most* *mysterious* *word* in the *language*: it is *the* *form* of the *prediction*, the *promise*, the *threat*, the *law*, the *disposition*, the *explanation*, and the *regret*. The *philosophy* of *conditionals* is *the* *philosophy* of *the* *possible* *and* the *actual*, *the* *general* and the *particular*, *the* *word* and the *world*. The *next* *part* *begins* from *this* *recognition*, and it *asks* *what* *explanation* *must* *be* *like* for the *recognition* to be *possible*.

---

## Summary

- **The *material* *conditional*** ($\neg p \vee q$) is *truth*-*functional* and *fails* to *capture* the *ordinary* “if” (the *paradoxes*: the *vacuity*, the *explosion*, the *positive* and *negative* *paradoxes*).
- **The *pragmatist* *response*** (Grice) *explains* the *intuition* by the *implicature* (the *speaker* *implies* that the *antecedent* is *possible*), and it *preserves* the *truth*-*functionality*.
- **The *indicative*/*subjunctive* *distinction*** (Adams) is *real*: the *indicative* *expresses* a *conditional* *belief*, and the *subjunctive* is a *counterfactual* *proposition*.
- **The *strict* *conditional*** ($\Box(p \to q)$) *captures* the *necessity*, and it *fails* on the *vacuity* (the *impossible* *antecedent* *necessitates* *everything*).
- **The *variably* *strict* *semantics*** (Stalnaker, Lewis) *analyzes* the *counterfactual* by the *nearest* *worlds* (the *similarity* *ordering*), and it *faces* the *limit* *assumption* and the *conditional* *excluded* *middle*.
- **The *probabilistic* *approach*** (Adams) *identifies* the *assertibility* with the *conditional* *probability*, and the *triviality* *results* (Lewis) *constrain* the *propositional* *account*.
- **The *causal* *approach*** (Pearl, Spirtes et al.) *grounds* the *counterfactuals* in the *structural* *equations* (the *interventions*), and it *fits* the *causal* *inference*.
- **The *counterfactuals* are *indispensable* in *science* (the *laws*), *law* (the *but*-*for* *test*), and *morals* (the *responsibility*); the *applications* *test* the *semantics*.
- **The *generics*, the *dispositions*, and the *ceteris* *paribus* *claims* are *conditional* *constructions*; the *constructions* *share* the *counterfactual* *core* (the *similarity* *ordering*), and the *finkish* *cases* and the *idealization* *remain* *unresolved*.
- **The *circularity* *worry*** (the *causation* and the *counterfactuals* *presuppose* each other) is *serious*, and the *interventionist* *resolution* is *promising* and *incomplete*.
- **The *most* *defensible* *position*** is a *qualified* *pluralism*: the *indicative* *conditionals* *express* the *conditional* *beliefs*, the *subjunctive* *conditionals* are *counterfactual* *propositions*, the *causal* *conditionals* are *grounded* in the *structural* *models*, and the *three* *are* *distinct* but *connected* (the *pluralist* *insight*), *qualified* by the *admission* that the *triviality* and the *circularity* *remain* *unresolved*.

---

## Study Questions

1. State the *material* *conditional*. What are the *paradoxes* of *material* *implication*?
2. State the *pragmatist* *response* (Grice). Is the *implicature* *sufficient* to *save* the *material* *conditional*?
3. State the *indicative*/*subjunctive* *distinction*. What is the *Adams* *pair*, and what does it *show*?
4. State the *strict* *conditional* (C. I. Lewis). What is the *vacuity* *objection*?
5. State the *variably* *strict* *semantics* (Stalnaker, Lewis). What is the *similarity* *ordering*?
6. State the *limit* *assumption*. Is the *assumption* *defensible*?
7. State the *conditional* *excluded* *middle*. Is the *principle* *defensible*?
8. State the *Adams* *thesis* (the *conditional* *probability*). Is the *thesis* *defensible*?
9. State the *triviality* *results* (Lewis). What do the *results* *show*?
10. State the *expressivist* *response* (Edgington). Is the *response* *defensible*?
11. State the *causal* *approach* (Pearl; Spirtes et al.). Is the *structural* *equations* *approach* *defensible*?
12. State the *counterfactuals* in *science* (the *laws*). What do they *show* about the *laws*?
13. State the *counterfactuals* in *law* (the *but*-*for* *test*). What do they *show* about the *causation*?
14. State the *counterfactuals* in *morals* (the *responsibility*). What do they *show* about the *responsibility*?
15. State the *generics*. Is the *normalcy* *account* *defensible*?
16. State the *dispositions* and the *finkish* *cases*. Is the *simple* *conditional* *analysis* *defensible*?
17. State the *ceteris* *paribus* *claims*. Are they *laws*?
18. State the *circularity* *worry* (the *causation* and the *counterfactuals*). Is the *interventionist* *resolution* *adequate*?
19. Is the *causation* *primitive*, or the *counterfactuals*? What does the *answer* *imply* for the *causation* (Ch. 18)?
20. Is the *conditional* a *proposition*? What does the *answer* *imply* for the *truth* (Ch. 32)?
21. Is the *conditional* *normative*? What does the *answer* *imply* for the *logic* (Ch. 35)?
22. Is the *conditionals* *family* *unified*? What does the *answer* *imply* for the *semantics* (Ch. 31)?
23. Is the *conditional* the *hinge* of the *philosophy* of *language*? What does the *answer* *imply* for the *part* (Ch. 31–37)?
24. Is the *conditional* *empirical* or *a* *priori*? What does the *answer* *imply* for the *a* *priori* (Ch. 36)?
25. “If ‘if’ were the same as ‘$\to$’, we should have no need of the word ‘if’ at all.” Assess.

---

## Further Reading

- **Primary**: David Lewis, *Counterfactuals* (1973); Robert Stalnaker, “A Theory of Conditionals” (1968), in *Studies in Logical Theory* (ed. Rescher, 1968), and *Inquiry* (1984); Ernest Adams, *The Logic of Conditionals* (1975); Frank Ramsey, *Foundations of Mathematics* (1929), p. 143; H. P. Grice, “Logic and Conversation” (1975), in *Studies in the Way of Words* (1989), §3, and “Indicative Conditionals” (1989), in *Studies*.
- **On the material conditional and the paradoxes**: H. P. Grice, “Indicative Conditionals” (1989); Dorothy Edgington, “On Conditionals” (1995), in *Mind* 104; the *survey* in the *Stanford Encyclopedia* entry, “The Material Conditional” (the entry by the contemporary literature).
- **On the indicative/subjunctive distinction**: Ernest Adams, “Subjunctive and Indicative Conditionals” (1970), in *Foundations of Language* 6; David Lewis, *Counterfactuals* (1973), Ch. 1; Robert Stalnaker, “Indicative Conditionals” (1975), in *Context and Content* (1999); the *survey* in the *Stanford Encyclopedia* entry, “The Logic of Conditionals” (the entry by the contemporary literature).
- **On the variably strict semantics**: Stalnaker (1968); Lewis (1973); the *limit* *assumption* in Lewis (1973), §1.4, and the *response* in the *contemporary* *literature*; the *conditional* *excluded* *middle* in Stalnaker (1981), in *Context and Content* (1999); the *critique* in Nelson Goodman, “The Problem of Counterfactual Conditionals” (1947), in *Fact, Fiction, and Forecast* (1955).
- **On the probabilistic approach**: Adams (1975); Lewis, “Probabilities of Conditionals and Conditional Probabilities” (1976), in *Philosophical Papers*, Vol. II (1986), and the *second* *installment* (1986); Edgington (1995); the *survey* in the *Stanford Encyclopedia* entry, “Conditional Probability” (the entry by the contemporary literature).
- **On the causal approach**: Judea Pearl, *Causality* (2nd ed., 2009), Chs. 7–8; Peter Spirtes, Clark Glymour, and Richard Scheines, *Causation, Prediction, and Search* (2nd ed., 2000); James Woodward, *Making Things Happen* (2003), Ch. 2.
- **On counterfactuals in science, law, and morals**: David Lewis, “Counterfactual Dependence and Time's Arrow” (1979), in *Philosophical Papers*, Vol. II (1986); H. L. A. Hart and Tony Honoré, *Causation in the Law* (2nd ed., 1985); Richard Wright, “Causation in Tort Law” (1985), in *California Law Review* 73; the *essays* in *Counterfactuals and Causation* (ed. the contemporary literature).
- **On generics**: the *contemporary* *literature* in *Genericity* (ed. Mari, Beyssade, and Del Prete, 2013); the *survey* in the *Stanford Encyclopedia* entry, “Generics” (the entry by the contemporary literature).
- **On dispositions and the finkish cases**: C. B. Martin, “Dispositions and Conditionals” (1994), in *The Philosophical Quarterly* 44; David Lewis, “Finkish Dispositions” (1997), in *Papers in Metaphysics and Epistemology* (1999); the *survey* in the *Stanford Encyclopedia* entry, “Dispositions” (Choi and Fara).
- **On ceteris paribus**: Jerry Fodor, “Special Sciences” (1974); Nancy Cartwright, *How the Laws of Physics Lie* (1983); the *essays* in *Ceteris Paribus Laws* (ed. Earman, Glymour, and Mitchell, 2002).
- **On the circularity and the interventionist resolution**: Woodward (2003), Ch. 2; Pearl (2009), Ch. 7; the *survey* in the *Stanford Encyclopedia* entry, “Causation and Manipulability” (Woodward).

---

> *A closing note.* This chapter has followed the *conditional* — the *material*, the *indicative*, the *subjunctive*, the *counterfactual*, the *causal*, the *generic* — through the *truth*-*functional* *analysis* and its *paradoxes*, the *indicative*/*subjunctive* *distinction*, the *variably* *strict* *semantics*, the *probabilistic* and *causal* *approaches*, the *applications* in *science*, *law*, and *morals*, the *generics* and the *dispositions*, and the *circularity* *worry*. The result is *not* a *settled* *semantics* of the *conditional*, and it is *not* a *refutation* of the *conditional*. It is a *diagnosis*: the *conditional* is a *family* of *devices* (the *material*, the *indicative*, the *subjunctive*, the *causal*, the *generic*), and the *family* is *unified* by the *role* in *inference* and *explanation* rather than by a *single* *truth* *condition*.

> *And a bridge.* Part VI turns to *science*, *explanation*, and *mathematics*. The *conditional* is the *form* of the *scientific* *laws* (Ch. 39), the *explanation* (Ch. 38), the *confirmation* (Ch. 40), and the *mathematical* *application* (Ch. 43). The *next* *chapter* *turns* to *explanation*, and it *asks* the *question* that the *conditional* *presupposes*: *what* *is* *it* for a *theory* to *explain* the *world*?
