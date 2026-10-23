# Chapter 35 — Formal Logic and Its Philosophical Pay-Off

> “Logic is the anatomy of thought.”
> — John Locke, *An Essay Concerning Human Understanding* (1690), IV.xvii.4, in a sentence he did not quite mean

> “The logician’s task is to make the form of the argument visible. The philosopher’s task is to decide whether anybody could have meant what the form says.”
> — a formulation of the division of labor, after Russell and Quine

> “Logic is not a body of doctrine, but a mirror-image of the world. Logic is transcendental.”
> — Ludwig Wittgenstein, *Tractatus Logico-Philosophicus* (1921), §6.13

---

Part V examined *language* — meaning, truth, paradox, and speech acts. This chapter examines the *skeleton* of language: **logical form**.

The *skeleton* is not the *body*. An argument is *valid* in virtue of its *form*, not its *content*; but the *form* is *not given* by the *surface grammar* (Ch. 12, §2), and the *formalization* is a *translation* (Ch. 3, §3.3), and the *translation* is *contestable*. The *chapter* is therefore *not* a *textbook* of logic (Appendix A supplies the mechanics). It is an *inquiry* into the *philosophical* *pay-off* of the *formal* *apparatus*: what the *apparatus* *reveals*, what it *conceals*, and what it *presupposes*.

The *thesis* is *threefold*. First, the *value* of formal logic is *not* that it *proves* *things* — the *proofs* are *easy* once the *formalization* is *settled* — but that it *forces* the *formalization* to be *explicit*, and the *explicitness* is where the *philosophical* *work* is done. Second, *formal* *results* (the *limitative* *theorems*, the *correspondence* *results*, the *non-classical* *logics*) *constrain* philosophical *theories*, and a *theory* that *ignores* them is *not* *merely* *unfashionable* but *inconsistent*. Third, logic is *not* *immune* from *revision* (the *Quinean* *challenge*), but the *revision* is *constrained* by the *meanings* of the *connectives*, and the *constraint* is *the* *philosophical* *question* the *chapter* *leaves* *open* for Ch. 36.

The *chapter* proceeds in seven movements. §1 states the *pay-off* *question*. §2 supplies the *compact* *toolkit* (the *propositional* and the *predicate* logic). §3 examines the *modal*, *epistemic*, and *deontic* logics and their *philosophical* *readings*. §4 examines the *probability* *calculus* and its *interpretations*. §5 examines the *non-classical* logics. §6 examines the *misuse* of *formalism*. §7 examines the *revisability* of *logic*.

---

## 1. Why a Philosopher Needs Logic

### 1.1 The three roles

**The *question***. What does *formal* *logic* *do* for *philosophy*?

**The *three* *roles***.

| Role | The *function* | The *example* |
|---|---|---|
| **Testing** | The *mechanical* *check* of *validity* | The *validity* of the *ontological* *argument* (Ch. 2, §6.1) |
| **Exposing** | The *detection* of *hidden* *structure* | The *quantifier* *analysis* of the *descriptions* (Ch. 12, §2) |
| **Constraining** | The *limitative* *results* that *constrain* *theories* | The *Gödel* *incompleteness* *theorems* (Ch. 43) |

**The *thesis***. The *testing* *role* is the *least* *important* (the *checking* is *easy* once the *form* is *fixed*), the *exposing* *role* is the *most* *important* (the *form* is *not* *given*), and the *constraining* *role* is the *most* *philosophically* *consequential* (the *results* *rule* *out* *theories).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The validity check presupposes a formalization (the translation of the argument).} \\
2. & \text{The formalization is not unique (the same argument can be formalized in different logics).} \\
3. & \text{The choice of logic determines the verdict (Ch. 3, §3.3).} \\
\hline
4. & \therefore \text{The philosophical work is in the choice, not in the check}.
\end{array}
$$

**The *significance***. The *chapter* is *not* about *how* to *prove* *things* (the *proofs* are *in* Appendix A); it is about *what* the *proofs* *assume*.

### 1.2 Validity and form

**The *definition***. An *argument* is **valid** iff *every* *interpretation* on which the *premises* are *true* is one on which the *conclusion* is *true*.

**The *structure***.

$$
\Gamma \models \phi \quad \text{iff} \quad \forall v\, (\text{if } v \models \Gamma, \text{ then } v \models \phi)
$$

**The *distinction***.

| The *notion* | The *domain* | The *definition* |
|---|---|---|
| **Semantic validity** | The *interpretations* | The *truth* *preservation* (the *definition* above) |
| **Syntactic validity** | The *derivations* | The *provability* in a *proof* *system* ($\Gamma \vdash \phi$) |
| **Soundness** | The *relation* | $\Gamma \vdash \phi \Rightarrow \Gamma \models \phi$ |
| **Completeness** | The *relation* | $\Gamma \models \phi \Rightarrow \Gamma \vdash \phi$ |

**The *significance***. The *soundness* and the *completeness* *are* *theorems* (the *metalogical* *results*), and they are *not* *obvious* (the *completeness* of the *first*-*order* *logic* (Gödel 1929) is a *theorem*; the *incompleteness* (Gödel 1931) is the *theorem* that *arithmetic* *cannot* be *both* *complete* and *consistent*).

**The *consequence***. The *formal* *apparatus* *does* not *merely* *check* *arguments*; it *proves* *theorems* *about* the *apparatus*, and the *theorems* *constrain* what the *apparatus* can *do*.

### 1.3 The Russellian paradigm

**The *example***. "The present King of France is bald" (Ch. 12, §2). The *surface* *grammar* (a *subject* + a *predicate*) *suggests* a *singular* *proposition* (the *king*, the *baldness*), and the *analysis* *reveals* a *quantificational* *structure*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The surface grammar suggests a singular proposition (a subject term denoting an object).} \\
2. & \text{The analysis reveals a quantificational structure (the existential, the universal, the identity).} \\
3. & \text{The difference changes the consequences (the sentence is false, not truth-valueless; the existential import disappears).} \\
\hline
4. & \therefore \text{The formal analysis does philosophical work (it dissolves the puzzle).}
\end{array}
$$

**The *significance***. The *example* is the *paradigm* of the *formal* *pay-off*: the *apparatus* *makes* *visible* a *structure* that the *grammar* *conceals*, and the *visibility* *is* the *dissolution* of a *philosophical* *problem* (Ch. 3, §7).

### 1.4 The limits of the method

**The *limits***.

**(i) The *translation* *problem*** (Ch. 3, §3.3). The *formalization* *is* a *translation*, and the *translation* is *not* *unique*; the *choice* *determines* the *verdict*.

**(ii) The *loss* *of* *content***. The *formalization* *abstracts* *from* the *content*, and the *content* *may* be *what* *matters* (the *“*if*”* *is* *not* *the* *material* *conditional*; Ch. 37).

**(iii) The *pseudo*-*precision***. The *notation* *can* *make* a *claim* *look* *exact* without *making* it *informative* (Ch. 3, §3.3).

**(iv) The *one* *logic* *assumption***. The *assumption* that there is *one* *correct* *logic* is *contested* (the *logical* *pluralism*; §5.5).

**The *consequence***. The *apparatus* is a *tool*, not a *foundation* (Ch. 3, §3); the *tool* *is* *powerful*, and its *power* *is* *the* *power* *to* *make* *assumptions* *explicit*.

---

## 2. The Compact Toolkit: Propositional and Predicate Logic

### 2.1 The connectives

**The *vocabulary***.

| The *connective* | The *notation* | The *reading* | The *intuition* |
|---|---|---|---|
| **Negation** | $\neg p$ | Not $p$ | The *falsity* of $p$ |
| **Conjunction** | $p \wedge q$ | $p$ and $q$ | Both |
| **Disjunction** | $p \vee q$ | $p$ or $q$ | At least one (inclusive) |
| **Conditional** | $p \to q$ | If $p$ then $q$ | Not ($p$ and not $q$) |
| **Biconditional** | $p \leftrightarrow q$ | $p$ iff $q$ | Same truth value |

**The *material* *conditional***. The *truth* *table*.

| $p$ | $q$ | $p \to q$ |
|---|---|---|
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |

**The *paradoxes* of *material* *implication***. The *conditional* is *true* whenever the *antecedent* is *false* (the *“*vacuous* *truth*”*), and the *reading* *conflicts* with the *ordinary* *use* of “if” (the *“*if*”* *is* *not* *the* *material* *conditional*; Ch. 37, §1).

**The *significance***. The *divergence* between the *formal* *conditional* and the *ordinary* “if” is *the* *most* *important* *example* of the *translation* *problem*, and it *motivates* the *non*-*classical* *conditionals* (§5.2).

### 2.2 Validity and the truth tables

**The *definitions***.

| The *notion* | The *definition* | The *example* |
|---|---|---|
| **Tautology** | True on every valuation | $p \vee \neg p$ |
| **Contradiction** | False on every valuation | $p \wedge \neg p$ |
| **Contingency** | True on some, false on others | $p$ |
| **Logical equivalence** | $\phi \leftrightarrow \psi$ is a tautology | $\neg(p \wedge q) \leftrightarrow (\neg p \vee \neg q)$ |
| **Logical consequence** | $\Gamma \models \phi$ | $p \to q, p \models q$ |

**The *tool***. The *truth* *tables* *decide* the *validity* of the *propositional* *arguments* (the *finite* *decision* *procedure*), and the *decision* is *mechanical*.

### 2.3 Natural deduction

**The *rules***. The *proof* *system* has the *introduction* and *elimination* *rules* for *each* *connective*.

| The *connective* | The *introduction* | The *elimination* |
|---|---|---|
| **Conjunction** | $p, q \vdash p \wedge q$ | $p \wedge q \vdash p$ |
| **Conditional** | $[p] \cdots q \vdash p \to q$ | $p \to q, p \vdash q$ |
| **Disjunction** | $p \vdash p \vee q$ | $p \vee q, [p] \cdots r, [q] \cdots r \vdash r$ |
| **Negation** | $[p] \cdots \bot \vdash \neg p$ | $p, \neg p \vdash \bot$ |
| **Biconditional** | $[p] \cdots q, [q] \cdots p \vdash p \leftrightarrow q$ | $p \leftrightarrow q, p \vdash q$ |

**The *classical* *principles***. The *classical* *logic* *adds* the *principles* that *fail* in the *intuitionistic* *logic* (§5.1).

| The *principle* | The *formula* | The *status* |
|---|---|---|
| **Excluded middle** | $p \vee \neg p$ | *Classical* (not intuitionistic) |
| **Double negation elimination** | $\neg\neg p \to p$ | *Classical* (not intuitionistic) |
| **Peirce's law** | $((p \to q) \to p) \to p$ | *Classical* (not intuitionistic) |
| **Explosion** | $p \wedge \neg p \to q$ | *Classical* (not relevant or paraconsistent) |

**The *significance***. The *classical* *principles* are *theorems* of the *classical* *logic*, and the *question* of *whether* they are *valid* (of *the* *logic*) is the *central* *question* of §5 and §7.

### 2.4 Predicate logic

**The *vocabulary***.

| The *symbol* | The *reading* | The *example* |
|---|---|---|
| **Universal** | $\forall x\, Fx$ | All $F$s |
| **Existential** | $\exists x\, Fx$ | Some $F$ |
| **Identity** | $a = b$ | $a$ is the same as $b$ |
| **Predicates** | $F, G, R$ | The *properties*, the *relations* |
| **Function symbols** | $f, g$ | The *functions* |

**The *scope***. The *scope* of a *quantifier* is the *subformula* it *governs*, and the *scope* *distinguishes* the *readings* of the *ambiguous* *sentences*.

| The *sentence* | The *reading* | The *formula* |
|---|---|---|
| “Everyone loves someone” | Everyone has some beloved | $\forall x \exists y\, Lxy$ |
| “Someone is loved by everyone” | One person is universally beloved | $\exists y \forall x\, Lxy$ |

**The *identity* and the *descriptions***. The *Russellian* *analysis* (Ch. 12, §2) uses the *identity* and the *quantifiers*, and the *analysis* is the *paradigm* of the *predicate*-*logical* *pay-off*.

**The *metalogical* *results***.

| The *result* | The *content* | The *significance* |
|---|---|---|
| **Soundness** | $\Gamma \vdash \phi \Rightarrow \Gamma \models \phi$ | The *proof* *system* *preserves* *truth* |
| **Completeness** | $\Gamma \models \phi \Rightarrow \Gamma \vdash \phi$ | The *semantics* *is* *captured* by the *proof* *system* (Gödel 1929) |
| **Compactness** | If every *finite* *subset* of $\Gamma$ is *satisfiable*, $\Gamma$ is | The *infinite* *sets* *behave* *like* the *finite* *ones* *for* *satisfiability* |
| **Löwenheim–Skolem** | If $\Gamma$ has an *infinite* *model*, it has a *countable* one | The *cardinality* is *not* *expressible* in the *first*-*order* *logic* |
| **Undecidability** | The *validity* of the *first*-*order* *formulas* is *undecidable* (Church–Turing 1936) | No *mechanical* *procedure* for the *validity* |

**The *significance***. The *metalogical* *results* *constrain* what the *first*-*order* *logic* can *express* (the *cardinality*, the *finiteness*, the *well*-*foundedness*), and the *constraints* are *philosophically* *consequential* (the *ontology* of *mathematics*; Ch. 43, §2).

### 2.5 What the first-order logic cannot express

**The *limitations***.

| The *notion* | The *expressibility* | The *consequence* |
|---|---|---|
| **Finiteness** | *Not* first-order (by compactness) | The *finite* *domains* *are* *not* *definable* |
| **Countability** | *Not* first-order (by Löwenheim–Skolem) | The *cardinality* *is* *not* *absolute* |
| **Well-foundedness** | *Not* first-order | The *natural* *numbers* *have* *non-standard* *models* (the *non-standard* *arithmetic*) |
| **Transitive closure** | *Not* first-order | The *ancestral* *relation* *requires* *the* *second*-*order* *logic* |
| **“Most”** | *Not* first-order | The *quantifier* “most” *requires* a *generalized* *quantifier* |

**The *significance***. The *limitations* *motivate* the *extensions* (the *second*-*order* *logic*, the *generalized* *quantifiers*, the *infinitary* *logic*), and the *extensions* *raise* the *question* of *whether* the *logic* *is* *the* *logic* (the *logical* *pluralism*; §5.5).

---

## 3. Modal, Epistemic, and Deontic Logics

### 3.1 The possible-worlds semantics

**The *frame***. A *frame* is a *pair* $\langle W, R \rangle$ (the *worlds*, the *accessibility* *relation*), and a *model* *adds* a *valuation*.

**The *semantic* *clauses***.

$$
\llbracket \Box \phi \rrbracket^w = 1 \ \text{iff} \ \forall v \in W\, (wRv \to \llbracket \phi \rrbracket^v = 1)
$$

**The *correspondence*** (the *Sahlqvist* *results*). Each *axiom* *corresponds* to a *condition* on the *accessibility* *relation*.

| The *axiom* | The *formula* | The *frame* *condition* | The *reading* |
|---|---|---|---|
| **K** | $\Box(p \to q) \to (\Box p \to \Box q)$ | *(valid on all frames)* | The *minimal* *logic* |
| **T** | $\Box p \to p$ | *Reflexive* | The *factivity* (what is *necessary* is *actual*) |
| **4** | $\Box p \to \Box\Box p$ | *Transitive* | The *positive* *introspection* |
| **5** | $\Diamond p \to \Box\Diamond p$ | *Euclidean* | The *negative* *introspection* |
| **D** | $\Box p \to \Diamond p$ | *Serial* | The *consistency* (obligation implies permission) |

**The *systems***.

| The *system* | The *axioms* | The *relation* | The *standard* *reading* |
|---|---|---|---|
| **K** | K | — | The *minimal* *modal* *logic* |
| **T** | K + T | Reflexive | The *alethic* *modality* (necessity) |
| **S4** | K + T + 4 | Reflexive, transitive | The *provability* (Gödel–Löb), the *knowledge* |
| **S5** | K + T + 4 + 5 | Equivalence | The *metaphysical* *necessity*, the *knowledge* |

**The *significance***. The *correspondence* *shows* that the *axioms* *are* *philosophical* *theses* *about* the *relation*, and the *theses* are *not* *merely* *formal* (Ch. 16, §1.3).

### 3.2 The epistemic logic

**The *reading***. $\Box$ = the *knowledge* *operator* $K_i$ (the *agent* $i$ *knows* that …), and the *relation* $R_i$ is the *epistemic* *alternativeness* (the *worlds* *compatible* with *what* *the* *agent* *knows*).

**The *axioms***.

| The *axiom* | The *formula* | The *reading* | The *status* |
|---|---|---|---|
| **K** | $K_i(p \to q) \to (K_i p \to K_i q)$ | The *closure* under *known* *entailment* | *Widely* *accepted* (with *qualifications*) |
| **T** | $K_i p \to p$ | The *factivity* | *Accepted* (the *knowledge* *is* *factive*; Ch. 7, §1.3) |
| **4** | $K_i p \to K_i K_i p$ | The *positive* *introspection* (the *KK* *principle*) | *Contested* (the *externalists* *deny* it) |
| **5** | $\neg K_i p \to K_i \neg K_i p$ | The *negative* *introspection* | *Contested* (the *“*knowing* *that* *one* *does* *not* *know*”* *is* *rare*) |

**The *problem* of *logical* *omniscience*** (Hintikka 1962; the *contemporary* *literature*). The *standard* *epistemic* *logic* *implies* that the *agents* *know* *all* *logical* *truths* (the *necessity* *rule*) and *all* the *consequences* of *their* *knowledge* (the *K* *axiom*), and the *implication* is *false* (the *agents* are *not* *logically* *omniscient*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{If } \vdash \phi, \text{ then } \vdash K_i \phi \text{ (the necessitation rule).} \\
2. & \text{If } \vdash K_i(\phi \to \psi) \text{ and } \vdash K_i \phi, \text{ then } \vdash K_i \psi \text{ (the K axiom).} \\
3. & \text{The agents do not know all the logical truths, and do not know all the consequences.} \\
\hline
4. & \therefore \text{The standard epistemic logic is an idealization (the logical omniscience is false).}
\end{array}
$$

**The *responses***.

**(i) The *impossible*-*worlds* *response*** (Hintikka 1975; Priest 2005, Ch. 1). The *agents* *have* *impossible* *worlds* *among* the *alternatives* (the *worlds* *where* the *logic* *fails*), and the *impossible* *worlds* *block* the *omniscience*.

**The *objection***. The *impossible* *worlds* *are* *contested* (the *nature* of the *impossible* *worlds*; Ch. 16, §5.2).

**(ii) The *awareness* *response*** (Fagin & Halpern 1988). The *agents* *have* an *awareness* *set* (the *concepts* *they* *have*), and the *knowledge* *requires* the *awareness* (the *agents* *do* not *know* the *formulas* *they* *cannot* *formulate*).

**The *objection***. The *awareness* *is* *ad* *hoc* (the *set* *is* *not* *explained*), and the *reply* is *contested*.

**(iii) The *procedural* *response*** (the *contemporary* *literature*; Artemov & Nogina 2005). The *knowledge* *is* *justified* by a *procedure* (the *proof*), and the *procedure* *is* *explicit* (the *logic* *of* *proofs*).

**The *objection***. The *procedural* *account* *is* *complex*, and the *reply* is *contested*.

### 3.3 The deontic logic

**The *reading***. $\Box$ = the *obligation* $O$ (it is *obligatory* that …), and the *relation* $R$ is the *deontic* *alternativeness* (the *worlds* *permitted* by the *norms*).

**The *standard* *system* *KD***. The *axioms*.

| The *axiom* | The *formula* | The *reading* |
|---|---|---|
| **K** | $O(p \to q) \to (Op \to Oq)$ | The *closure* |
| **D** | $Op \to \neg O\neg p$ | The *consistency* (the *obligations* do not *conflict*) |

**The *problem* of the *contrary*-*to*-*duty* *obligations*** (Chisholm 1963; the *gentle* *murderer*).

**The *paradox***. The *story*: (i) *it ought* to be that *you do not go* to *help*; (ii) *if* you *go*, you *ought* to *tell* them *you* are *coming*; (iii) *if* you *do not* *go*, you *ought* *not* to *tell* them; (iv) *you* *do not* *go*.

**The *formalization***.

$$
\begin{array}{ll}
1. & O\neg g \\
2. & g \to Ot \\
3. & \neg g \to O\neg t \\
4. & \neg g
\end{array}
$$

**The *problem***. From (3) and (4), $O\neg t$ (the *obligation* *not* to *tell*), and from (1) and (3), the *conditional* *is* *vacuously* *true* (the *antecedent* *is* *false*), and the *obligation* *disappears* (the *contrary*-*to*-*duty* *obligation* *is* *not* *captured*).

**The *significance***. The *paradox* *shows* that the *standard* *deontic* *logic* *cannot* *capture* the *conditional* *obligations*, and the *responses* (the *dyadic* *deontic* *logic*, the *non*-*monotonic* *deontic* *logic*) are *contested*.

**The *philosophical* *stake***. The *logic* of *obligation* *presupposes* a *theory* of *norms* (Ch. 44, §4), and the *theory* is *contested* (the *moral* *realism* vs. the *expressivism*).

### 3.4 The state of the debate

**The *assessment***. The *modal* *logics* are *formally* *rigorous*, and their *philosophical* *readings* are *contested*.

| The *logic* | The *strength* | The *weakness* |
|---|---|---|
| **Alethic (S5)** | The *metaphysical* *necessity* | The *nature* of the *worlds* |
| **Epistemic (S4)** | The *knowledge* | The *logical* *omniscience* |
| **Deontic (KD)** | The *obligation* | The *contrary*-*to*-*duty* |

**The *most* *defensible* *position***. A *qualified* *use*: the *modal* *logics* are *models* of the *concepts*, and the *models* are *idealized* (the *omniscience*, the *consistency*), and the *idealization* *is* *acceptable* *for* the *normative* *purposes* (the *logic* *is* a *tool*, not a *description* of the *agents*).

---

## 4. The Probability Calculus and Its Interpretation

### 4.1 The axioms

**The *axioms*** (Kolmogorov 1933).

$$
\begin{array}{ll}
(\mathrm{P1}) & P(A) \geq 0 \\
(\mathrm{P2}) & P(\Omega) = 1 \\
(\mathrm{P3}) & P(A \cup B) = P(A) + P(B) \text{ if } A \cap B = \emptyset
\end{array}
$$

**The *theorems***.

$$
P(\neg A) = 1 - P(A), \qquad P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

**The *conditional* *probability***.

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \qquad P(B) > 0
$$

**The *significance***. The *axioms* are *formal* (they *constrain* the *measure*, not the *interpretation*), and the *interpretation* is the *philosophical* *question* (§4.2).

### 4.2 The interpretations

**The *five* *interpretations***.

| The *interpretation* | The *claim* | The *proponent* | The *problem* |
|---|---|---|---|
| **Frequentist** | The *probability* is the *limiting* *relative* *frequency* | Venn (1866); von Mises (1919) | The *single* *case*; the *reference* *class* |
| **Propensity** | The *probability* is a *disposition* (the *tendency* to *produce* the *outcome*) | Popper (1957, 1959) | The *propensity* is *mysterious*; Humphreys' *paradox* |
| **Subjective** | The *probability* is the *degree* of *belief* (the *credence*) | Ramsey (1926); de Finetti (1937); Savage (1954) | The *priors* (Ch. 10, §5) |
| **Logical** | The *probability* is the *degree* of *confirmation* (the *logical* *relation*) | Keynes (1921); Carnap (1950) | The *principle* of *indifference*; Bertrand's *paradox* |
| **Best*-*system** | The *probability* is the *chance* *postulated* by the *best* *system* (the *Humean* *chance*) | Lewis (1980, 1994) | The *Humean* *supervenience*; the *chance* *is* *not* *fundamental* |

**The *significance***. The *interpretations* are *not* *merely* *verbal*: the *frequentist* *cannot* *assign* a *probability* to a *single* *event*, and the *subjective* *can* (the *different* *domains*, the *different* *applications*).

### 4.3 Chance and credence

**The *distinction***. The **chance** is the *objective* *probability* (a *feature* of the *world*), and the **credence** is the *subjective* *probability* (a *feature* of the *agent*).

**The *Principal* *Principle*** (Lewis 1980; “A Subjectivist's Guide to Objective Chance”).

$$
P(A \mid \text{ch}(A) = x \wedge E) = x \quad \text{(for admissible } E)
$$

**The *structure***. The *credence* *tracks* the *chance*, and the *tracking* is the *norm* of the *rational* *agent* (the *reply* to the *problem* of the *priors*: the *priors* *are* *constrained* by the *chances*; Ch. 10, §5).

**The *significance***. The *principle* *connects* the *subjective* and the *objective* *interpretations*, and it *grounds* the *rational* *credence* in the *world*.

**The *objections***.

**(i) The *admissibility* *problem*. The *principle* *requires* the *evidence* $E$ to be *admissible* (not *containing* *information* *about* the *outcome* *beyond* the *chance*), and the *admissibility* is *hard* to *define*.

**The *reply*** (Lewis 1980). The *admissibility* is *defined* *negatively* (the *evidence* is *admissible* *if* it *does* not *undermine* the *chance*), and the *reply* *grounds* the *principle* in the *best* *system*. The *reply* is *contested*.

**(ii) The *Humphreys* *paradox*** (Humphreys 1985). The *principle* *fails* when the *evidence* is *about* the *chance* *itself* (the *“*the* *chance* *has* *just* *been* *set* *to* 0.5*”*), and the *failure* *undermines* the *principle*.

**The *reply*** (the *contemporary* *literature*; Lewis 1994). The *paradox* *requires* a *restriction* on the *principle* (the *principle* *applies* *to* the *chance* *before* the *setting*), and the *reply* *is* *contested*.

### 4.4 The state of the debate

**The *assessment***. The *probability* *calculus* is *formally* *rigorous*, and the *interpretations* are *all* *defended*.

**The *most* *defensible* *position***. A *qualified* *pluralism*: the *frequentist* *works* for the *repeatable* *events*, the *propensity* *works* for the *single*-*case* *dispositions*, the *subjective* *works* for the *degrees* of *belief*, and the *best*-*system* *works* for the *objective* *chances*; the *choice* *depends* on the *domain*, and *no* *interpretation* *exhausts* the *notion*.

---

## 5. Non-Classical Logics

### 5.1 Intuitionistic logic

**The *thesis*** (Brouwer 1907, 1912; Heyting 1930; Dummett 1977). The *logic* of the *constructive* *proof* (the *BHK* *interpretation*: a *proof* of $\phi \to \psi$ is a *construction* that *turns* a *proof* of $\phi$ into a *proof* of $\psi$).

**The *principles* that *fail***.

| The *principle* | The *formula* | The *status* |
|---|---|---|
| **Excluded middle** | $p \vee \neg p$ | *Not* *valid* |
| **Double negation elimination** | $\neg\neg p \to p$ | *Not* *valid* |
| **Classical reductio** | $(\neg p \to \bot) \to p$ | *Not* *valid* |
| **Peirce's law** | $((p \to q) \to p) \to p$ | *Not* *valid* |

**The *principles* that *hold***.

| The *principle* | The *formula* |
|---|---|
| **Double negation introduction** | $p \to \neg\neg p$ |
| **Excluded middle as a negation** | $\neg\neg(p \vee \neg p)$ |
| **The disjunction property** | If $\vdash \phi \vee \psi$, then $\vdash \phi$ or $\vdash \psi$ |

**The *philosophical* *motivation***. The *anti*-*realism* (Dummett; Ch. 22, §1.3): the *truth* is *verification*-*immanent*, and the *excluded middle* *presupposes* a *verification*-*transcendent* *truth* (the *“*p*”* *may* be *true* *without* being *verified*).

**The *argument*. The *intuitionist* *logic* *is* the *logic* of the *verification*; the *classical* *logic* *is* the *logic* of the *truth*; the *choice* is *the* *choice* of the *semantics*.

**The *objections***.

**(i) The *‘*no* *theory* *of* *truth’* *objection*. The *intuitionism* *abandons* the *bivalence* (the *truth* *is* *not* *determinate*), and the *abandonment* *conflicts* with the *ordinary* *reasoning*.

**The *reply***. The *bivalence* is *not* *required* for the *reasoning* (the *intuitionist* *logic* *is* *adequate* for the *constructive* *mathematics*), and the *reply* *grounds* the *logic* in the *practice*. The *reply* is *contested*.

**(ii) The *‘*no* *classical* *mathematics*’* *objection*. The *intuitionism* *rejects* the *classical* *proofs* (the *existence* *proofs* *that* *do* not *exhibit* the *object*), and the *rejection* *undermines* the *mathematical* *practice* (Ch. 43, §2).

**The *reply*** (the *contemporary* *literature*). The *intuitionist* *mathematics* *is* *a* *legitimate* *alternative* (the *constructive* *analysis*), and the *reply* *grounds* the *mathematics* in the *alternative*. The *reply* is *contested*.

### 5.2 Relevant logic

**The *thesis*** (Anderson & Belnap 1975; the *contemporary* *literature*). The *valid* *arguments* *require* a *connection* between the *premises* and the *conclusion* (the *variable*-*sharing*), and the *classical* *conditionals* *fail* the *requirement*.

**The *principles* that *fail***.

| The *principle* | The *formula* | The *status* |
|---|---|---|
| **Explosion** | $p \wedge \neg p \to q$ | *Not* *valid* (the *“*no* *content*”*) |
| **Positive paradox** | $p \to (q \to p)$ | *Not* *valid* (the *“*irrelevant*”* *conclusion*) |
| **Negative paradox** | $\neg p \to (p \to q)$ | *Not* *valid* |
| **Disjunctive syllogism** | $p \vee q, \neg p \vdash q$ | *Not* *valid* (in the *strong* *relevant* *logics*) |

**The *virtue***. The *logic* *captures* the *intuition* that the *valid* *arguments* *must* be *relevant* (the *conclusion* *follows* from the *premises*, not from their *contradiction*), and it *fits* the *ordinary* *practice* of *reasoning*.

**The *objections***.

**(i) The *‘*no* *disjunctive* *syllogism*’* *objection*. The *rejection* of the *disjunctive* *syllogism* *is* *counterintuitive* (the *inference* is *elementary*), and the *rejection* *undermines* the *logic*.

**The *reply*** (the *contemporary* *literature*). The *disjunctive* *syllogism* *is* *valid* *for* the *consistent* *cases* (the *logic* *has* a *restricted* *form* of the *principle*), and the *reply* *grounds* the *logic* in the *consistency*. The *reply* is *contested*.

**(ii) The *‘*no* *mathematics*’* *objection*. The *rejection* of the *classical* *principles* *undermines* the *mathematical* *practice*.

**The *reply***. The *relevant* *logic* *has* a *mathematical* *interpretation* (the *relevant* *arithmetic*), and the *reply* *grounds* the *mathematics* in the *logic*. The *reply* is *contested*.

### 5.3 Paraconsistent logic

**The *thesis*** (Jaśkowski 1948; Priest 1979; the *contemporary* *literature*). The *logic* *tolerates* the *contradictions* (the *explosion* *fails*), and the *contradictions* *can* be *true* (the *dialetheism*; Ch. 33, §2.5).

**The *systems***.

| The *system* | The *truth* *values* | The *designated* | The *motivation* |
|---|---|---|---|
| **LP** (Priest) | $\{1, 0, \text{both}\}$ | $\{1, \text{both}\}$ | The *dialetheism* |
| **FDE** (Belnap–Dunn) | $\{T\}, \{F\}, \{T, F\}, \emptyset$ | $\{T\}, \{T, F\}$ | The *information* *states* |
| **Relevant** | (varies) | (varies) | The *relevance* |

**The *argument*** (Priest 1979, 1987). The *semantic* *paradoxes* *generate* *true* *contradictions* (the *Liar*), and the *logic* *must* *tolerate* them. The *paraconsistent* *logic* *is* the *logic* of the *paradoxes*.

**The *objections***.

**(i) The *‘*trivialism*’* *objection*. The *paraconsistent* *logic* *must* *reject* the *classical* *principles* (the *explosion*, the *disjunctive* *syllogism*, the *contraction*), and the *rejection* *is* *costly* (the *logic* *is* *weaker*).

**(ii) The *‘*no* *justification*’* *objection*. The *paraconsistent* *logic* *is* *justified* *only* *if* the *dialetheism* *is* *true*, and the *dialetheism* *is* *contested*.

**The *reply*** (Priest 1987). The *logic* *is* *justified* by the *paradoxes* (the *paradoxes* *are* *data*), and the *reply* *grounds* the *logic* in the *data*. The *reply* is *contested*.

### 5.4 Other non-classical logics

**The *brief* *survey***.

| The *logic* | The *motivation* | The *principle* |
|---|---|---|
| **Many-valued** | The *truth* *is* *graded* (the *vagueness*; Ch. 33, §3) | The *truth* *values* $\{0, 1, \ldots\}$ |
| **Fuzzy** | The *truth* *is* *continuous* | The *truth* *values* $[0,1]$ |
| **Free** | The *empty* *names* (the *fictional* *terms*; Ch. 25, §6) | The *existence* *predicate* (Ch. 14, §1.4) |
| **Quantum** | The *distributive* *law* *fails* (the *quantum* *events*) | The *lattice* *of* *projections* |

**The *significance***. The *proliferation* of the *logics* is *the* *logical* *pluralism* (the *thesis* that there are *many* *equally* *correct* *logics*; Beall & Restall 2006), and the *pluralism* *connects* the *logic* to the *semantics* (the *meaning* of the *connectives*) and to the *metaphysics* (the *nature* of the *truth*).

### 5.5 Logical pluralism

**The *thesis*** (Beall & Restall, *Logical Pluralism*, 2006; the *contemporary* *literature*). There is *more* than *one* *correct* *logic*, and the *correctness* is *relative* to the *notion* of *validity* (the *different* *notions* *yield* the *different* *logics*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The validity is defined relative to a notion of case (the possible world, the situation, the proof).} \\
2. & \text{The notions of case differ (the classical, the relevant, the constructive).} \\
3. & \text{The differences yield the different logics.} \\
\hline
4. & \therefore \text{The logical pluralism (the many validities).}
\end{array}
$$

**The *virtue***. The *view* *explains* the *proliferation* of the *logics* (the *different* *logics* *are* *correct* *for* *their* *notions* of *case*), and it *avoids* the *arbitrariness* of the *choice*.

**The *objections***.

**(i) The *‘*no* *disagreement*’* *objection*. If the *logics* *are* *relative* to the *notions*, the *logics* *do* not *disagree* (they *talk* *past* each other), and the *disagreement* *is* *verbal* (Ch. 33, §4.3).

**The *reply***. The *disagreement* *is* *genuine* (the *logics* *make* *conflicting* *claims* *about* the *same* *arguments*), and the *reply* *grounds* the *disagreement* in the *semantics*. The *reply* is *contested*.

**(ii) The *‘*no* *unity*’* *objection*. The *pluralism* *abandons* the *unity* of *logic* (the *one* *logic* *that* *governs* the *reasoning*), and the *consequence* *is* *unacceptable*.

**The *reply***. The *unity* is *not* *required* (the *reasoning* *is* *plural*), and the *reply* *grounds* the *pluralism* in the *practice*. The *reply* is *contested*.

### 5.6 The state of the debate

**The *assessment***. The *non-classical* *logics* *are* *all* *live*, and the *choice* *depends* on the *philosophical* *commitments*.

| The *logic* | The *strength* | The *weakness* |
|---|---|---|
| **Intuitionistic** | Constructive; anti-realist | Abandons bivalence; loses classical mathematics |
| **Relevant** | Captures relevance | Rejects disjunctive syllogism |
| **Paraconsistent** | Tolerates contradictions | Rejects explosion; weak |
| **Many-valued** | Captures gradedness | The truth values are mysterious |
| **Free** | Handles empty names | The existence predicate |
| **Quantum** | Fits quantum mechanics | The interpretation is contested |
| **Pluralism** | Explains the proliferation | The disunity |

**The *most* *defensible* *position***. A *qualified* *pluralism*: the *classical* *logic* is *correct* for the *ordinary* *reasoning* (the *classical* *notion* of *case*), the *intuitionistic* *logic* is *correct* for the *constructive* *reasoning*, the *relevant* *logic* is *correct* for the *relevant* *reasoning*, and the *pluralism* *is* *the* *meta*-*position*, *qualified* by the *admission* that the *unity* of *logic* is *lost*.

---

## 6. The Misuse of Formalism

### 6.1 The formalization fallacies

**The *fallacies*** (Ch. 3, §3.3).

| The *fallacy* | The *definition* | The *example* |
|---|---|---|
| **Translation fallacy** | The *invalidity* in *one* *formalization* does *not* *entail* the *invalidity* of the *English* *argument* | The *conditional* *arguments* (the *material* *conditional*) |
| **Pseudo-precision** | The *notation* *looks* *exact* without *adding* *content* | The *uninterpreted* *predicates* |
| **Formalization fallacy** | The *form* *is* *mistaken* for the *content* | The *quantifier* *analysis* of the *modal* *claims* |
| **The *one* *logic* *assumption*** | The *classical* *logic* is *the* *logic* | The *rejection* of the *non-classical* *arguments* *without* *argument* |

**The *significance***. The *fallacies* *show* that the *formalism* is *not* *self*-*justifying* (the *choice* of the *formalization* *is* *the* *philosophical* *work*), and the *choice* *requires* the *argument* (the *translation* *is* *defended* *independently*; Ch. 3, §3.4).

### 6.2 The quantifier scope fallacies

**The *fallacies***.

| The *fallacy* | The *invalid* *inference* | The *example* |
|---|---|---|
| **Quantifier inversion** | $\forall x \exists y\, Rxy \therefore \exists y \forall x\, Rxy$ | “Everyone loves someone, so someone is loved by everyone” (Ch. 2, §2.5) |
| **The *scope* *of* the *negation*** | $\neg\forall x\, Fx \therefore \forall x\, \neg Fx$ | “Not all are guilty, so all are innocent” |
| **The *modal* *scope*** | $\Box \exists x\, Fx \therefore \exists x\, \Box Fx$ | “Necessarily there is a God, so there is a necessary being” |

**The *significance***. The *scope* *fallacies* are *the* *most* *common* *formal* *errors* in *philosophy*, and they are *detected* by the *formalization* (the *explicitness* of the *scope*; Ch. 2, §2.5).

### 6.3 The modal fallacies

**The *fallacies*** (Ch. 16, §1.2).

| The *fallacy* | The *invalid* *inference* | The *example* |
|---|---|---|
| **Necessity of the consequent** | $p \to q, \Box q \therefore \Box p$ | The *cosmological* *arguments* (the *contingency*) |
| **Possibility to actuality** | $\Diamond p \therefore p$ | The *ontological* *arguments* (the *modal* *version*) |
| **The *de* *dicto*/*de* *re*** | $\Box \forall x\, Fx \therefore \forall x\, \Box Fx$ | The *necessity* of *origin* (Ch. 16, §1.2) |

**The *significance***. The *modal* *fallacies* *undermine* the *classical* *arguments* (the *ontological*; Ch. 2, §6.1), and the *detection* *requires* the *scope* *distinction* (the *de* *dicto* vs. the *de* *re*).

### 6.4 The conditional fallacies

**The *fallacies*** (Ch. 37, §1–2).

| The *fallacy* | The *invalid* *inference* | The *example* |
|---|---|---|
| **Affirming the consequent** | $p \to q, q \therefore p$ | The *confirmation* of a theory (Ch. 2, §2.5) |
| **Denying the antecedent** | $p \to q, \neg p \therefore \neg q$ | The *refutation* of a prediction |
| **The *material* *conditional*** | $(p \to q) \leftrightarrow (\neg p \vee q)$ | The *ordinary* “if” (the *conditional* *assertion*) |

**The *significance***. The *formal* *treatment* of the *conditionals* is *the* *most* *contested* *area* of the *logic* (the *indicative* vs. the *subjunctive*; Ch. 37, §2), and the *misuse* *of* the *material* *conditional* is the *most* *common* *error*.

### 6.5 The ‘proof by notation’

**The *vice***. The *presentation* of a *formal* *proof* as a *substitute* for the *argument* (the *notation* *does* the *work*, and the *reader* is *expected* to *accept* the *conclusion* *because* the *proof* *is* *formal*).

**The *diagnosis***. The *proof* *is* *only* *as* *good* *as* the *formalization*, and the *formalization* *is* *only* *as* *good* *as* the *translation*; the *notation* *adds* *nothing* *to* the *argument* (the *argument* is in the *translation*, not in the *symbols*).

**The *significance***. The *vice* *is* *the* *formalism* *version* of the *vice* of *cleverness* (Ch. 4, §4.2), and the *remedy* is the *honesty* about the *translation*.

### 6.6 The state of the debate

**The *assessment***. The *formal* *apparatus* is *powerful* and *dangerous*; the *power* is *the* *explicitness*, and the *danger* is the *illusion* of *rigor*.

**The *most* *defensible* *position***. The *formalism* is a *tool* (the *explicitness* is the *value*), and the *tool* *is* *justified* *only* by the *translation* (the *argument* *is* *assessed* by the *translation* *plus* the *logic*), *qualified* by the *admission* that the *translation* *is* *contestable*.

---

## 7. Logic and the A Priori

### 7.1 Quine's challenge

**The *thesis*** (Quine, “Two Dogmas of Empiricism,” 1951; *Philosophy of Logic*, 1970, Ch. 6; “Carnap and Logical Truth,” 1960). The *logical* *laws* are *not* *a* *priori*; they are *central* *beliefs* in the *web* of *belief*, and they are *revisable* (Ch. 9, §2.5).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The logical laws are not analytic (the analytic/synthetic distinction fails; Ch. 9, §2.4).} \\
2. & \text{The logical laws are central beliefs in the web (they are entrenched, not certain).} \\
3. & \text{The central beliefs are revisable (the revision is drastic, but possible).} \\
\hline
4. & \therefore \text{The logical laws are not a priori (they are revisable).}
\end{array}
$$

**The *virtue***. The *argument* *fits* the *naturalistic* *epistemology* (the *web* of *belief*; Ch. 8, §3), and it *explains* the *history* of the *logical* *revision* (the *quantum* *logic*, the *intuitionism*).

**The *objections***.

**(i) The *‘*no* *revision*’* *objection*. The *logical* *laws* *cannot* be *revised* *coherently* (the *revision* *requires* the *logic*; the *revision* *is* *self*-*undermining*). The *objection* *supports* the *a* *priori* *status* (Ch. 35, §7.2).

**(ii) The *‘*no* *alternative*’* *objection*. The *quantum* *logic* is *not* a *revision* of the *logic* (it is a *revision* of the *semantics* of the *propositions*), and the *revision* *does* not *support* the *Quinean* *thesis*. The *objection* is *contested* (Putnam 1968).

### 7.2 The meaning-variance reply

**The *thesis*** (Putnam, “Is Logic Empirical?”, 1968; “How to Be a Fallibilist,” 1983; the *contemporary* *literature*). The *quantum* *logic* is *not* a *revision* of the *logic*; it is a *revision* of the *meaning* of the *connectives*, and the *revision* *changes* the *subject*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The quantum logic rejects the distributive law ($p \wedge (q \vee r) \leftrightarrow (p \wedge q) \vee (p \wedge r)$).} \\
2. & \text{The rejection changes the meaning of the connectives (the “and”, “or” are not the classical ones).} \\
3. & \text{The change is not a revision of the logic (it is a different logic, not a revision of the same one).} \\
\hline
4. & \therefore \text{The logical laws are not revised (the meanings are changed).}
\end{array}
$$

**The *virtue***. The *reply* *preserves* the *a* *priori* *status* of the *logic* (the *connectives* *mean* what they *mean*), and it *explains* the *apparent* *revision* (the *change* is *semantic*, not *logical*).

**The *objections*.

**(i) The *‘*no* *neutrality*’* *objection*. The *reply* *presupposes* a *neutral* *notion* of *meaning* (the *classical* *connectives*), and the *presupposition* is *contestable* (the *meaning* *is* *theory*-*laden*).

**(ii) The *‘*no* *progress*’* *objection*. The *reply* *makes* the *logical* *revision* *impossible* (any *revision* *is* a *change* of *meaning*), and the *consequence* *is* *that* the *logic* *cannot* *be* *criticized*. The *objection* is *contested*.

### 7.3 The anti-exceptionalism

**The *thesis*** (Hjortland, “Anti-Exceptionalism about Logic,” 2017; Priest, *In Contradiction*, 1987, Ch. 12; the *contemporary* *literature*). The *logic* is *not* *exceptional* (it is *not* *a* *priori* *or* *analytic*); it is a *theory* *chosen* by the *same* *criteria* as the *scientific* *theories* (the *simplicity*, the *strength*, the *explanatory* *power*; Ch. 4, §3).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The logical theory is chosen by the theoretical virtues (the simplicity, the strength, the explanatory power).} \\
2. & \text{The virtues are the same as those of the scientific theories (Ch. 10, §6; Ch. 21, §9).} \\
3. & \text{The theories are revisable (the revision is driven by the data).} \\
\hline
4. & \therefore \text{The logic is not exceptional (the anti-exceptionalism).}
\end{array}
$$

**The *virtue***. The *view* *connects* the *logic* to the *scientific* *method*, and it *explains* the *revision* (the *paraconsistent* *logic* is *chosen* *because* it *handles* the *paradoxes*; Ch. 33, §2.5).

**The *objections***.

**(i) The *‘*no* *criterion*’* *objection*. The *choice* *among* the *logics* *requires* a *criterion*, and the *criterion* *presupposes* the *logic* (the *reasoning* *is* *logical*). The *objection* *is* the *criterion* *problem* (Ch. 13, §1) *applied* to the *logic*.

**(ii) The *‘*no* *data*’* *objection*. The *logic* *is* *not* *confirmed* by the *empirical* *data* (the *logical* *laws* are *not* *observations*), and the *anti*-*exceptionalism* *loses* the *distinction* between the *logic* and the *science*.

**The *reply*** (the *contemporary* *literature*). The *logical* *data* are the *intuitions* (the *logical* *intuitions*; the *“*proofs*”*), and the *data* are *defeasible* (the *intuitions* *are* *revised* by the *theoretical* *virtues*). The *reply* is *contested*.

### 7.4 The state of the debate

**The *assessment***. The *revisability* of *logic* is *unresolved*, and the *positions* are *all* *live*.

| The *position* | The *claim* | The *proponent* |
|---|---|---|
| **Quinean** | Logic is revisable, central in the web | Quine |
| **Meaning-variance** | Revision changes the meaning | Putnam |
| **Apriorist** | Logic is a priori, analytic | BonJour; Bealer |
| **Anti-exceptionalist** | Logic is theory-choice | Hjortland; Priest |
| **Conventionalist** | Logic is a framework choice | Carnap |

**The *most* *defensible* *position***. A *qualified* *anti*-*exceptionalism*: the *logic* is *revisable* (the *Quinean* *insight*), the *revision* *changes* the *meanings* (the *Putnam* *insight*), and the *revision* *is* *assessed* by the *theoretical* *virtues* (the *anti*-*exceptionalist* *insight*), *qualified* by the *admission* that the *criterion* *problem* *remains* (the *choice* *of* the *virtues* *is* *contested*).

---

## 8. The State of the Debate

### 8.1 What is settled

- **Formal logic is indispensable.** The *detection* of *hidden* *structure* (the *descriptions*, the *quantifiers*, the *modals*) and the *testing* of the *arguments* are the *core* of the *analytic* *method*.
- **The metalogical results constrain theories.** The *soundness*, the *completeness*, the *incompleteness*, and the *compactness* are *theorems*, and the *theories* that *contradict* them are *inconsistent*.
- **The modal logics have philosophical readings.** The *correspondence* between the *axioms* and the *frame* conditions *shows* that the *axioms* are *philosophical* *theses*.
- **The epistemic and deontic logics are idealizations.** The *logical* *omniscience* and the *contrary*-*to*-*duty* *obligations* are *unresolved* *problems*.
- **The probability calculus is formally rigorous, and its interpretations are contested.** The *pluralism* is the *most* *defensible* *position*.
- **The non-classical logics are all live.** The *intuitionistic*, the *relevant*, the *paraconsistent*, the *many-valued*, the *free*, and the *quantum* *logics* are *defended*.
- **The formalism is a tool, not a foundation.** The *translation* is the *philosophical* *work*, and the *notation* adds *nothing* beyond the *explicitness*.
- **The revisability of logic is unresolved.** The *Quinean*, the *meaning-variance*, the *apriorist*, the *anti*-*exceptionalist*, and the *conventionalist* *positions* are *all* *live*.

### 8.2 What is open

- **The *one* *logic*.** Is there *one* *correct* *logic*, or *many* (the *pluralism*)?
- **The *logical* *omniscience*.** How can the *epistemic* *logic* *model* the *finite* *agents*?
- **The *contrary*-*to*-*duty* *obligations*.** How can the *deontic* *logic* *model* the *conditional* *obligations*?
- **The *interpretation* of *probability*.** Is there a *single* *interpretation*, or a *pluralism*?
- **The *revisability* of the *logic*.** Is the *logic* *a* *priori*, or *revisable*?
- **The *semantics* of the *connectives*.** What *determines* the *meaning* of “and”, “or”, “not”, “if”?

### 8.3 The methodological lesson

The chapter is a case study in the method of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *distinction* between the *semantic* and the *syntactic* validity.
- **Thought experiments** (§2 of Ch. 3) — the *correspondence* between the *axioms* and the *frames*, the *countermodel* to a *formula* — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *entire* chapter — is *essential* for the *field*.
- **Reflective equilibrium** (§4 of Ch. 3) is the *method* by which the *intuitions* and the *theories* are *adjusted*.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to *hold* the *question* *open*.

The honest verdict: the theory of logic is a field in transition. The classical logic is the default, and it is contested. The non-classical logics are live, and their costs are real. The formalism is a tool, and its misuse is a vice. The revisability of logic is unresolved.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Classical logic** | The standard semantics and proof theory | Simple; complete | The paradoxes of implication |
| **Intuitionistic** | The constructive logic | Anti-realist; proof-theoretic | Abandons bivalence |
| **Relevant** | The relevance condition | Captures the implication | Rejects the disjunctive syllogism |
| **Paraconsistent** | Tolerates contradictions | Handles the paradoxes | Rejects explosion |
| **Many-valued** | Graded truth | Captures vagueness | The truth values |
| **Free** | Handles empty names | Fits the fiction | The existence predicate |
| **Quantum** | Non-distributive | Fits quantum mechanics | The interpretation |
| **Pluralism** | Many correct logics | Explains the proliferation | The disunity |
| **Quinean** | Logic is revisable | Naturalistic | The self-undermining |
| **Anti-exceptionalist** | Logic is theory-choice | Fits the practice | The criterion problem |
| **Apriorist** | Logic is a priori | The certainty | The revision |

The table is a map, not a verdict. The reader who wants to choose a position must decide which cost is acceptable — and the decision is a philosophical argument.

---

## Optional threads

Cross-cutting material, for the reader who wants to go deeper.

**1. The *limitativetheorems*.** The *Gödel* *incompleteness* (1931), the *Tarski* *undefinability* (1933), the *Church–Turing* *undecidability* (1936), and the *Löwenheim–Skolem* (1915) *are* the *most* *important* *results* in *logic*, and they *constrain* the *philosophy* of *mathematics* (Ch. 43, §2), *truth* (Ch. 32, §5), and *mind* (Ch. 23, §4). The *reader* who *wants* the *technical* *details* should *consult* Appendix A and the *standard* *textbooks* (Boolos, Burgess & Jeffrey; Enderton).

**2. The *algebraic* *semantics*.** The *Boolean* *algebras* (for the *classical* *logic*), the *Heyting* *algebras* (for the *intuitionistic*), the *De* *Morgan* *algebras* (for the *relevant*), and the *orthomodular* *lattices* (for the *quantum*) *provide* the *semantic* *structures* of the *logics*, and the *structures* *connect* the *logic* to the *algebra* and to the *physics* (Ch. 19, §5).

**3. The *logic* of *AI*.** The *automated* *theorem* *provers*, the *SAT* *solvers*, the *description* *logics*, and the *neural* *reasoners* *implement* the *logics* in *machines*, and the *philosophical* *questions* (the *logic* *of* the *machine*, the *meaning* of the *symbols*, the *common-sense* *reasoning*) are *urgent* (Ch. 29, §3; Ch. 51, §3).

**4. Non-Western *logics*.** The *Nyāya* *tradition* developed a *sophisticated* *logic* of *inference* (*anumāna*, the *five*-*membered* *syllogism*, the *vyāpti*), and the *Buddhist* *tradition* developed the *tetralemma* (the *catuṣkoṭi*; Ch. 33, §2.5) and the *apoha* *theory* of *meaning* (Ch. 31, §3). The *traditions* are *systematic* *alternatives*, not *curiosities* (Matilal 1986, 1998; Ganeri 2001; the *essays* in *The Oxford Handbook of Indian Philosophy*, 2017).

**5. The *ethics* of *logic*.** The *logical* *vices* (the *inconsistency*, the *equivocation*, the *sophistry*) are *ethical* as well as *epistemic*, and the *ethics* of *logic* *connects* the *formal* *apparatus* to the *ethics* of *discourse* (Ch. 4, §4) and to the *political* *epistemology* (Ch. 11, §6). The *connection* is *underdeveloped*, and it is *urgent*.

---

## Summary

- **The *three* *roles* of *formal* *logic*** are the *testing* (the *check* of the validity), the *exposing* (the *detection* of the hidden structure), and the *constraining* (the *limitative* *results*). The *exposing* is the *most* *important*, and the *checking* is the *least*.
- **The *Russellian* *paradigm*** is the *model* of the *formal* *pay-off*: the *analysis* of the *descriptions* reveals a *structure* that the *grammar* conceals, and the *revelation* *dissolves* a *philosophical* *puzzle*.
- **The *propositional* and the *predicate* *logics*** provide the *toolkit* (the *connectives*, the *quantifiers*, the *identity*, the *derivations*), and the *metalogical* *results* (the *soundness*, the *completeness*, the *compactness*, the *Löwenheim–Skolem*, the *undecidability*) *constrain* the *expressibility* of the *first*-*order* *logic*.
- **The *modal* *logics*** (the *K*, *T*, *S4*, *S5*) have the *philosophical* *readings* (the *alethic*, the *epistemic*, the *deontic*), and the *correspondence* between the *axioms* and the *frame* *conditions* *shows* that the *axioms* are *philosophical* *theses*.
- **The *epistemic* *logic*** *faces* the *problem* of the *logical* *omniscience*, and the *deontic* *logic* *faces* the *problem* of the *contrary*-*to*-*duty* *obligations*.
- **The *probability* *calculus*** has the *five* *interpretations* (the *frequentist*, the *propensity*, the *subjective*, the *logical*, the *best*-*system*), and the *Principal* *Principle* *connects* the *credence* to the *chance*.
- **The *non-classical* *logics*** (the *intuitionistic*, the *relevant*, the *paraconsistent*, the *many-valued*, the *free*, the *quantum*) are *all* *live*, and the *logical* *pluralism* is the *meta*-*position*.
- **The *misuse* of *formalism*** (the *translation* *fallacy*, the *pseudo*-*precision*, the *scope* *fallacies*, the *modal* *fallacies*, the *conditional* *fallacies*, the *proof* *by* *notation*) is a *standing* *danger*, and the *remedy* is the *honesty* about the *translation*.
- **The *revisability* of *logic*** is *contested* (the *Quinean*, the *meaning*-*variance*, the *apriorist*, the *anti*-*exceptionalist*, the *conventionalist* *positions*), and the *choice* *depends* on the *theory* of *meaning* and the *theory* of *knowledge*.
- **The *most* *defensible* *position*** is a *qualified* *pluralism*: the *classical* *logic* is *correct* for the *ordinary* *reasoning*, the *non-classical* *logics* are *correct* for their *notions* of *case*, and the *revisability* is *constrained* by the *meanings* of the *connectives*, *qualified* by the *admission* that the *criterion* *problem* *remains*.

---

## Study Questions

1. What are the *three* *roles* of *formal* *logic* in *philosophy*? Which is the *most* *important*, and *why*?
2. State the *definition* of *validity*. What is the *difference* between the *semantic* and the *syntactic* *validity*?
3. State the *soundness* and the *completeness* *theorems*. Why are they *important*?
4. State the *material* *conditional* and its *paradoxes*. Why does the *divergence* from the *ordinary* “if” *matter*?
5. State the *predicate* *logic* *toolkit* (the *quantifiers*, the *scope*, the *identity*). What are the *scope* *fallacies*?
6. State the *modal* *logics* (K, T, S4, S5) and the *correspondence* between the *axioms* and the *frame* *conditions*. Which *system* is the *standard* for the *metaphysical* *necessity*, and *why*?
7. State the *problem* of the *logical* *omniscience*. What are the *responses*, and which is *most* *defensible*?
8. State the *contrary*-*to*-*duty* *obligations*. Why does the *standard* *deontic* *logic* *fail*?
9. State the *five* *interpretations* of *probability*. Which is *most* *defensible*, and *why*?
10. State the *Principal* *Principle*. What is the *admissibility* *problem*?
11. State the *intuitionistic* *logic*. Which *classical* *principles* *fail*, and *why*?
12. State the *relevant* *logic*. What is the *motivation* for the *relevance* *condition*?
13. State the *paraconsistent* *logic*. Is the *dialetheism* *defensible*?
14. State the *logical* *pluralism*. Is the *view* *defensible*? What is the *disunity* *objection*?
15. State the *translation* *fallacy*, the *pseudo*-*precision* *fallacy*, and the *formalization* *fallacy*. Give an *example* of *each*.
16. State the *modal* *fallacies*. How do they *undermine* the *classical* *arguments*?
17. State *Quine's* *challenge* to the *a* *priori* *status* of *logic*. Is it *decisive*?
18. State the *meaning*-*variance* *reply*. Is it *adequate*?
19. State the *anti*-*exceptionalism*. Is the *logic* *a* *theory* *chosen* by the *theoretical* *virtues*?
20. Is the *logic* *revisable*? What does the *answer* *imply* for the *philosophy* of *mathematics* (Ch. 43) and the *philosophy* of *science* (Ch. 40)?
21. Is the *logical* *pluralism* *defensible*? What does the *answer* *imply* for the *unity* of *logic*?
22. Is the *formalism* a *tool* or a *foundation*? What does the *answer* *imply* for the *method* of *philosophy* (Ch. 3)?
23. Is the *classical* *logic* *the* *logic*? What does the *answer* *imply* for the *non-classical* *logics*?
24. Is the *probability* *interpretation* *pluralism* *defensible*? What does the *answer* *imply* for the *Bayesian* *framework* (Ch. 10)?
25. “Logic is the anatomy of thought, but the anatomy is not the patient.” Assess.

---

## Further Reading

- **Primary**: Alfred Tarski, “The Concept of Truth in Formalized Languages” (1933), in *Logic, Semantics, Metamathematics* (1956); Kurt Gödel, “On Formally Undecidable Propositions” (1931), in *From Frege to Gödel* (ed. van Heijenoort, 1967); Saul Kripke, “Semantical Considerations on Modal Logic” (1963), in *Acta Philosophica Fennica* 16; W. V. O. Quine, *Philosophy of Logic* (1970), Chs. 1 and 6.
- **On propositional and predicate logic**: George Boolos, John Burgess, and Richard Jeffrey, *Computability and Logic* (5th ed., 2007); Herbert Enderton, *A Mathematical Introduction to Logic* (2nd ed., 2001); the *survey* in the *Stanford Encyclopedia* entry, “Classical Logic” (Shapiro).
- **On modal logic**: Kripke (1963); G. E. Hughes and M. J. Cresswell, *A New Introduction to Modal Logic* (1996); Robert Stalnaker, “Possible Worlds” (1976), in *Ways a World Might Be* (2003); the *correspondence* *results* in Johan van Benthem, *Modal Logic for Open Minds* (2010); the *survey* in the *Stanford Encyclopedia* entry, “Modal Logic” (Garson).
- **On epistemic logic**: Jaakko Hintikka, *Knowledge and Belief* (1962); the *problem* of *logical* *omniscience* in the *contemporary* *literature* (Fagin & Halpern 1988; Artemov & Nogina 2005); the *survey* in the *Stanford Encyclopedia* entry, “Epistemic Logic” (Hendricks and Symons).
- **On deontic logic**: Roderick Chisholm, “Contrary-to-Duty Imperatives and Deontic Logic” (1963), in *Analysis* 24; the *contemporary* *literature* in *Deontic Logic in Computer Science* (ed. the contemporary literature); the *survey* in the *Stanford Encyclopedia* entry, “Deontic Logic” (McNamara).
- **On probability**: A. N. Kolmogorov, *Foundations of the Theory of Probability* (1933); Bruno de Finetti, *Theory of Probability* (1974); David Lewis, “A Subjectivist's Guide to Objective Chance” (1980), in *Philosophical Papers*, Vol. II (1986), and “Humean Supervenience Debugged” (1994), in *Papers in Metaphysics and Epistemology* (1999); the *survey* in the *Stanford Encyclopedia* entry, “Interpretations of Probability” (Hájek).
- **On non-classical logics**: Michael Dummett, *Elements of Intuitionism* (2nd ed., 2000); Alan Anderson and Nuel Belnap, *Entailment* (1975); Graham Priest, *An Introduction to Non-Classical Logic* (2nd ed., 2008), and *In Contradiction* (2nd ed., 2006); J. C. Beall and Greg Restall, *Logical Pluralism* (2006); the *survey* in the *Stanford Encyclopedia* entries, “Intuitionistic Logic” (Moschovakis), “Relevance Logic” (Mares), “Paraconsistent Logic” (Priest, Tanaka, and Weber), “Many-Valued Logic” (Malinowski), “Free Logic” (Nolt).
- **On the misuse of formalism**: the *advice* in Ch. 3 of this book; the *essays* in *The Philosophy of Logic* (ed. Jacquette, 2006); the *survey* in the *Stanford Encyclopedia* entry, “Logical Form” (Pietroski).
- **On the revisability of logic**: Quine (1951, 1960, 1970); Hilary Putnam, “Is Logic Empirical?” (1968), in *Mathematics, Matter and Method* (1975); the *essays* in *The Philosophy of Logic* (ed. Jacquette, 2006); Ole Hjortland, “Anti-Exceptionalism about Logic” (2017), in *Philosophical Studies* 174; the *survey* in the *Stanford Encyclopedia* entry, “Logical Pluralism” (the entry by the contemporary literature).
- **On quantum logic**: Garrett Birkhoff and John von Neumann, “The Logic of Quantum Mechanics” (1936), in *Annals of Mathematics* 37; Putnam (1968); the *critique* in Michael Dummett, “Is Logic Empirical?” (1978), in *Truth and Other Enigmas* (1978); the *survey* in the *Stanford Encyclopedia* entry, “Quantum Logic and Probability Theory” (Wilce).
- **On non-Western logics**: B. K. Matilal, *The Character of Logic in India* (1998); Jonardon Ganeri, *Philosophy in Classical India* (2001); the *essays* in *The Oxford Handbook of Indian Philosophy* (ed. Ganeri, 2017), Part IV.

---

> *A closing note.* This chapter has followed the *skeleton* of language — the propositional and the predicate *logic*, the modal, the epistemic and the deontic *logics*, the probability *calculus*, the non-classical *logics*, the *misuse* of the formalism, and the *revisability* of the logic — and it has arrived at a *conclusion* that is less a *theory* than a *diagnosis*: the *formalism* is a *powerful* *tool*, and its *power* is the *power* to *make* the *assumptions* *explicit*; the *tool* is *not* a *foundation*, and the *translation* is the *philosophical* *work*.

> *And a bridge.* The next chapter turns to the *a* *priori*, the *analyticity*, and the *philosophy* of *logic* — the *foundations* that the *formal* *apparatus* *presupposes*. If the *logic* is *revisable* (§7), the *a* *priori* is *not* *secure*; if the *logic* is *a* *priori* (§7.2), the *revision* is *not* *possible*. The *next* *chapter* *examines* the *foundations* (the *Kantian* *question*, the *Quinean* *attack*, the *revival* of the *analytic*; Ch. 9, §2), and it *asks* the *question* that the *logic* *presupposes*: *what* *is* *it* for a *truth* to be *a* *priori*, and *can* the *logic* *be* *justified*?
