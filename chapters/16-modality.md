# Chapter 16 — Modality: Necessity, Essence, and Possible Worlds

> “It is necessary that $2+2=4$; it is possible that there be a sea battle tomorrow; it is impossible that the same thing be red and green all over.”
> — the everyday data of modality, in three sentences

> “The hypothesis is that there exist infinitely many worlds. … I am ready to state the incredulous stare as an objection.”
> — David Lewis, *On the Plurality of Worlds* (1986), p. 133

> “Essence is not modality. … To say what a thing is is not to say what it might or must be.”
> — Kit Fine, “Essence and Modality” (1994), in effect the entire paper

---

Chapter 15 ended with a *promissory note*. The debate about properties — universals, tropes, naturalness, dispositions — *presupposed* a *category* that it did not *explain*: the category of the **possible** and the **necessary**. Universals *ground* necessary connections (Ch. 18, §5); natural properties *ground* the projectibility of predicates (Ch. 10, §3); dispositions *ground* causal powers (Ch. 18, §4); essences *ground* identity and kind-membership (Ch. 26, §2). Each of these is a *modal* notion, and none of them can be understood without an account of modality itself.

This chapter supplies that account. It is the *framework* chapter of Part III: the category of modality is the category within which the other metaphysical debates *take place*, and the questions of this chapter — what is necessity, what is an essence, what is a possible world, how do we know what is possible — are the questions the rest of the part *assumes*.

The chapter has three *layers*.

- **Formal**: the logic of modality — the modal operators, the systems of modal logic, the semantics of possible worlds (§§1–2).
- **Metaphysical**: the nature of necessity, essence, and possible worlds — the realism/ersatzism debate, the essentialist and grounding programs, the problem of *de re* modality (§§2–4).
- **Epistemological**: how we know the modal facts — conceivability, two-dimensionalism, the empirical challenge, modal skepticism (§§5–6).

The chapter *closes* with the *applications* (§7) and an *honest verdict* (§8). The thesis it defends is *not* a *solution* but a *diagnosis*: modality is *real*, it is *indispensable*, and its *metaphysics* and its *epistemology* are *both* unresolved — but the *shape* of the disagreement has been clarified by the twentieth century, and the clarification is a *genuine* achievement.

---

## 1. The Logic and Metaphysics of Modality

### 1.1 The modal operators

The *formal* *core* of modality is the pair of operators:

$$
\Box p \quad \text{(“it is necessary that } p \text{”)}, \qquad \Diamond p \quad \text{(“it is possible that } p \text{”)}
$$

They are *interdefinable*:

$$
\Diamond p \equiv \neg\Box\neg p, \qquad \Box p \equiv \neg\Diamond\neg p.
$$

The *interdefinability* is a *theorem* of the standard systems, and it is *philosophically* *significant*: it shows that necessity and possibility are *two faces* of a *single* *notion*, and it *raises* the question of which is the *prior* notion.

**The *modal square*.** The *four* *combinations* form a *square* of *opposition*, and the *square* is *valid* in the *standard* *systems*:

| | Affirmation | Denial |
|---|---|---|
| **Universal** | $\Box p$ | $\Box\neg p$ |
| **Particular** | $\Diamond p$ | $\Diamond\neg p$ |

The *relations*: $\Box p$ *entails* $\Diamond p$ (if it is *necessary*, it is *possible*); $\Box p$ *excludes* $\Box\neg p$ (if it is *necessary*, it is not *necessarily* *false*). The *square* is the *formal* *skeleton* of the *modal* *discourse*.

**The *philosophical* *question*.** The *operators* are *formal* *devices*; the *philosophical* *question* is *what* they *mean*. The *three* *main* *answers* — *possible* *worlds*, *essence*, and *primitivism* — are the *subject* of §§2–3.

### 1.2 *De dicto* and *de re*

The *most* *important* *distinction* in the *logic* of *modality* is between *de dicto* and *de re*.

**Definition.**

- **De dicto** *modality* is *modality* *applied* to a *dictum* (a *sentence*, a *proposition*): “*it is necessary that* $2+2=4$.”
- **De re** *modality* is *modality* *applied* to a *thing* (a *res*): “*Socrates is necessarily mortal*” — the *necessity* is *attributed* to *the* *thing*, not to the *sentence*.

**The *formal* *distinction*.**

| Sentence | Form | Content |
|---|---|---|
| “It is necessary that the inventor of bifocals is American” | $\Box A(f)$ | *Every* *possible* *world* *contains* *an* *American* *inventor* *of* *bifocals* |
| “The inventor of bifocals is necessarily American” | $\exists x\,(\text{Bifocals}(x) \wedge \Box A(x))$ | The *actual* *inventor* *of* *bifocals* *is* *American* *in* *every* *world* |

The *two* *are* *not* *equivalent*: the *first* *can* be *true* (some *American* *invents* *bifocals* *in* *every* *world*) while the *second* is *false* (the *actual* *inventor* *could* have *emigrated*). The *distinction* is *the* *source* of the *problem* of *de re* *modality*.

**The *history*.** The *distinction* *goes* *back* to Aristotle (*De Interpretatione* 9, 17a–18a; *Prior Analytics* I.13), and it is *developed* by the *medieval* *logicians* (Ockham, Buridan, Albert of Saxony) under the *headings* of *modal* *propositions* *de* *dicto* and *de* *re*. The *medieval* *debate* was *sophisticated*, and it *anticipated* the *contemporary* *discussion* in *detail*. (See Knuuttila 1993; the *Stanford* *Encyclopedia* entry, “Medieval Theories of Modality,” by Knuuttila.)

**The *contemporary* *significance*.** The *distinction* is *central* to the *debate* about *essentialism* (§3): the *essentialist* *holds* that some *properties* are *essential* *to* a *thing* — that the *thing* has them *necessarily* — and the *claim* is a *de re* *claim*. The *anti-essentialist* *holds* that *all* *necessity* is *de dicto* — a *feature* of *sentences* and *concepts*, not of *things*.

### 1.3 Relative modality and the varieties of the modal

The *modal* *operators* are *univocal* in the *formal* *systems*, but the *philosophical* *notion* is *not* *univocal*. There are *several* *kinds* of *necessity*, and they *nest* (Ch. 16, §5).

**The *table*.**

| Kind | What it is | Example | Logic |
|---|---|---|---|
| **Logical** | True in *all* *logically* *possible* *worlds* | $p \vee \neg p$ | S5 (or stronger) |
| **Metaphysical** | True in *all* *metaphysically* *possible* *worlds* | Water is H₂O; Hesperus is Phosphorus | S5 |
| **Nomological** | True in *all* *worlds* with the *same* *laws* | Nothing travels faster than light | S5 (relative) |
| **Conceptual** | True in *all* *worlds* *consistent* with the *concepts* | All bachelors are unmarried | S5 (contested) |
| **Epistemic** | True *for* *all* the *agent* *knows* | It *might* be raining (for all I know) | S4 / S5 |
| **Deontic** | True in *all* *worlds* *permitted* by the *norms* | One *ought* *not* to *torture* | KD (weak) |
| **Doxastic** | True in *all* *worlds* *consistent* with the *beliefs* | For all she believes, $p$ | KD45 |

**The *nesting*.** The *relations* *among* the *varieties* are *controversial*, but the *standard* *picture* is a *nesting*:

$$
\text{Logical} \ \supset \ \text{Metaphysical} \ \supset \ \text{Nomological}
$$

**The *claim*.** Every *logically* *necessary* *truth* is *metaphysically* *necessary*; every *metaphysically* *necessary* *truth* is *nomologically* *necessary* (in *our* *world*). The *converse* *does* not *hold*: some *metaphysical* *necessities* are *not* *logical* (Water is H₂O is *metaphysically* *necessary*, but not *logically* — it is *conceivable* that water is not H₂O); some *nomological* *necessities* are *not* *metaphysical* (the *laws* *could* have *been* *different* — or *could* they? The *debate* is *the* *subject* of Ch. 39, §1).

**The *dispute*.** The *nesting* is *not* *settled*. Some *philosophers* (e.g., Chalmers 1996, Ch. 4) *hold* that the *metaphysical* *modalities* are *grounded* in the *conceptual*; others (Kripke 1980; Fine 1994) *hold* that the *metaphysical* *modalities* are *autonomous*, and that the *conceptual* *modalities* are a *species* of the *metaphysical*. The *dispute* is *connected* to the *nature* of *essence* (§3).

### 1.4 Quine's attack

The *most* *influential* *attack* on *de re* *modality* is Quine’s, in *three* *papers*: “The Problem of Interpreting Modal Logic” (1947), “Reference and Modality” (1953/1961), and “Three Grades of Modal Involvement” (1953).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{De re modality requires that a thing have a property necessarily, independently of how it is described.} \\
2. & \text{But the truth of a de re modal claim depends on the description under which the thing is considered.} \\
3. & \text{Example: the number of planets is necessarily greater than 7, but 9 is not necessarily greater than 7 (it is necessarily equal to 9, and only contingently equal to the number of planets … wait, actually 9 is necessarily greater than 7). The classic example is different: Cicero is necessarily Cicero, but Tully is not necessarily Cicero (if the names are not known to be co-referential).} \\
4. & \text{The dependence shows that de re modality presupposes an Aristotelian essentialism — a distinction between essential and accidental properties.} \\
5. & \text{Essentialism is unintelligible: there is no fact of the matter about which properties are essential.} \\
\hline
6. & \therefore \text{De re modality is unintelligible; quantified modal logic is ill-founded.}
\end{array}
$$

**The *charge*.** Quine’s *objection* is *not* that *de re* *modality* is *false*; it is that it is *unintelligible* — that there is *no* *principled* *way* to *distinguish* *essential* from *accidental* *properties*, and the *distinction* *presupposes* a *metaphysics* that *empiricism* *cannot* *underwrite*.

**The *context*.** The *argument* is *part* of Quine’s *broader* *attack* on *intensional* *notions* (meaning, analyticity, modality). The *target* is the *logical* *positivist* *program*, which *held* that *necessity* is *linguistic* (analyticity), and Quine *argues* that the *program* *fails* *because* *analyticity* *fails* (Ch. 9, §2.4). The *attack* on *de re* *modality* is the *extension* of the *attack* on *analyticity*.

### 1.5 The Barcan formula and the quantified turn

The *formal* *response* to Quine is the *development* of *quantified* *modal* *logic* by Ruth Barcan Marcus (1946, 1947, 1961), Carnap (1946, 1947), and Kripke (1959, 1963).

**The Barcan formula.**

$$
(\mathrm{BF}) \quad \Diamond \exists x\, Fx \to \exists x\, \Diamond Fx
$$

**The *reading*.** If it is *possible* that there be an $F$, then there is *something* that is *possibly* $F$. The *formula* *says* that the *domain* of *objects* is the *same* in *every* *possible* *world* — that there are *no* *worlds* with *new* *objects*.

**The *converse* Barcan formula.**

$$
(\mathrm{CBF}) \quad \exists x\, \Diamond Fx \to \Diamond \exists x\, Fx
$$

The *converse* is *valid* in *the* *standard* *systems* with *constant* *domains*, but it is *controversial* because it *implies* that *everything* *exists* *necessarily* (if $x$ *exists*, then $\Diamond \exists y (y = x)$, and by CBF, $\exists y \Diamond(y = x)$, which is *satisfied* by $x$ *itself*, so $x$ *exists* *necessarily*). The *implication* is *false* on the *standard* *view* (there are *contingent* *beings*), and the *rejection* of CBF is *one* of the *motivations* for *varying* *domains* (Kripke 1963; Fine 1978).

**The *significance*.** The *formal* *development* *vindicated* *de re* *modality* *as* a *legitimate* *logical* *notion*: the *semantics* *can* *handle* *quantification* *across* *worlds*, and the *objections* of Quine *were* *answered* *at* the *formal* *level*. The *philosophical* *question* — *which* *properties* are *essential* — *remained*, and it is the *subject* of §3.

### 1.6 What survived Quine

The *debate* *following* Quine *produced* a *consensus* on *three* *points*.

**(i) De re modality is formally legitimate.** The *quantified* *modal* *logic* *works*, and the *formal* *objections* *are* *answered*.

**(ii) De re modality requires an account of essence.** The *semantics* *does* not *tell* us *which* *properties* are *essential*; the *question* is *metaphysical*, and it *requires* a *theory* *of* *essence*.

**(iii) Quine's challenge is not refuted; it is relocated.** The *challenge* — *what* *makes* a *property* *essential* — is *not* *answered* by the *formalism*; it is *answered* (if at all) by the *essentialist* *program* (§3).

---

## 2. Possible Worlds

### 2.1 The Leibnizian picture and Kripke semantics

The *idea* of *possible* *worlds* *goes* *back* to Leibniz, who *defined* a *possible* *world* as a *maximal* *consistent* *set* of *compossible* *substances*, and who *held* that *God* *actualized* the *best* *of* the *possible* *worlds* (*Theodicy*, 1710; *Monadology*, 1714).

**The *Leibnizian* *biconditional*.**

$$
\Box p \ \leftrightarrow \ \text{the proposition that } p \text{ is true in every possible world}
$$

$$
\Diamond p \ \leftrightarrow \ \text{the proposition that } p \text{ is true in at least one possible world}
$$

**The *modern* *development*.** Kripke (“Semantical Considerations on Modal Logic,” 1963) *gave* the *biconditional* a *rigorous* *semantics*.

**The *Kripke* *frame*.** A *frame* is a *pair* $\langle W, R \rangle$, where $W$ is a *non-empty* *set* of *worlds* and $R \subseteq W \times W$ is an *accessibility* *relation*. A *model* is a *frame* *plus* a *valuation* $\llbracket \cdot \rrbracket$ *assigning* *truth* *values* to *atomic* *formulas* at *worlds*.

**The *semantic* *clauses*.**

$$
\llbracket \Box \phi \rrbracket^w = 1 \ \text{iff} \ \forall v \in W \ (wRv \to \llbracket \phi \rrbracket^v = 1)
$$

$$
\llbracket \Diamond \phi \rrbracket^w = 1 \ \text{iff} \ \exists v \in W \ (wRv \wedge \llbracket \phi \rrbracket^v = 1)
$$

**The *systems*.** The *accessibility* *relation* *determines* the *modal* *system*:

| System | Condition on $R$ | Axiom |
|---|---|---|
| **K** | None | $\Box(p \to q) \to (\Box p \to \Box q)$ |
| **T** | Reflexive | $\Box p \to p$ |
| **S4** | Reflexive, transitive | $\Box p \to \Box\Box p$ |
| **S5** | Reflexive, symmetric, transitive (universal) | $\Diamond p \to \Box\Diamond p$ |

**The *interpretation*.** S5 is the *standard* *logic* for *metaphysical* *modality*, and the *reason* is *philosophical*: if the *worlds* are *genuinely* *possible*, then the *accessibility* *relation* is *universal* (any *world* is *accessible* from any *other*), and the *modal* *facts* are *absolute*.

**The *consequence*.** The *possible-worlds* *semantics* *reduces* *modal* *notions* to *non-modal* *notions* (quantification, truth-at-a-world, the *relation* $R$). The *reduction* is *the* *contemporary* *orthodoxy*, and the *question* is *whether* the *reduction* *is* *metaphysically* *innocent* or *whether* it *commits* us to *possible* *worlds*.

### 2.2 Lewis's modal realism

The *most* *ambitious* and *most* *controversial* *answer* is David Lewis’s **modal realism** (*Counterfactuals*, 1973; “Possible Worlds,” 1973; *On the Plurality of Worlds*, 1986).

**The *thesis*.** Possible worlds are *concrete* *entities*, *like* the *actual* *world* — *spatiotemporally* *connected*, *causally* *isolated* *wholes* — of *which* there are *infinitely* *many*. The *actual* *world* is *one* *among* them; it is *not* *metaphysically* *special*, only *indexically* *special* (it is *ours*).

**The *slogan*.** “The *actual* *world* is *the* *world* *we* *inhabit*; the *other* *worlds* are *the* *worlds* *we* *do* *not* *inhabit*.”

**The *theses*.**

1. **Possibilism.** There are *non-actual* *possible* *worlds*.
2. **Concreteness.** They are *concrete* (they *contain* *objects*, *events*, *space*, *time*).
3. **Plurality.** There are *infinitely* *many*.
4. **Isolation.** They are *causally* and *spatiotemporally* *isolated* from *one* *another*.
5. **Reduction.** Modal *claims* are *analyzed* in *terms* of *quantification* *over* *worlds*:

$$
\Box p \ \leftrightarrow \ \forall w \in W \ (p \ \text{is true at} \ w)
$$

**(The *analysis* is *circular* if $W$ is *defined* *modally*; Lewis *defines* $W$ as the *set* of *all* *concrete* *worlds*, and the *definition* is *not* *modal*.)**

**The *arguments*.**

**(i) The *utility* argument.** Modal realism *offers* a *unified* *semantics* for *modality*, *counterfactuals*, *propositions*, *properties*, *supervenience*, and *content*. The *rival* *theories* *provide* *only* *fragments*, and the *fragments* *do* not *fit* *together*.

**(ii) The *parsimony* argument.** The *rival* *theories* *posit* *abstract* *entities* (ersatz worlds) *plus* a *primitive* *modal* *relation*. Lewis *posits* *only* *concrete* *worlds* *plus* the *ordinary* *relations* *among* them. The *trade* is *favorable*: *fewer* *kinds* of *entity*, *more* *instances* of a *familiar* *kind*.

**(iii) The *analysis* argument.** The *ordinary* *analysis* of *modality* *via* *possible* *worlds* *is* *correct*. The *only* *question* is *what* *possible* *worlds* *are*. Lewis’s *answer* — *concrete* *wholes* — *preserves* the *analysis* *without* *mystery*.

**The *objections*.** The *criticisms* are *severe* and *well-known*; the *most* *important* are:

**(i) The *incredulous* *stare*.** The *theory* *offends* *common* *sense*: there are *no* *other* *worlds*. (Lewis’s *reply*: the *offense* is *philosophical* *prejudice*, not *argument*. The *reply* is *rhetorically* *effective* and *epistemically* *unsatisfying*.)

**(ii) The *epistemic* *objection*.** If the *other* *worlds* are *causally* *isolated*, we *cannot* *have* *causal* *contact* *with* them, and *causal* *contact* is *required* for *knowledge*. (Lewis’s *reply*: we *know* *modal* *facts* *by* *ordinary* *methods* — *logic*, *conceptual* *analysis*, *counterfactual* *reasoning* — and the *methods* *access* the *worlds* *via* the *analysis*. The *reply* is *contested*; the *epistemic* *objection* is *the* *strongest* *against* *modal* *realism*.)

**(iii) The *Humphrey* *objection*.** See §4.3. The *theory* *implies* that *the* *Humphrey* *who* *loses* the *election* *is* *not* *the* *Humphrey* *who* *wins* *in* *another* *world*; the *victory* *belongs* to a *counterpart*, not to *Humphrey* *himself*. Humphrey *found* the *implication* *absurd*.

**(iv) The *value* *objection*.** The *theory* *makes* *actuality* *arbitrary*: why *should* *we* *care* *about* *the* *actual* *world* *more* *than* *the* *others*? (Lewis’s *reply*: we *care* *because* *we* *are* *in* *it*; the *care* is *indexical*, not *metaphysical*.)

### 2.3 Ersatzism

The *mainstream* *alternative* to *modal* *realism* is **ersatzism**: possible worlds are *abstract* *representations* — *sets* of *propositions*, *maximal* *consistent* *descriptions*, *states* of *affairs*, *world-stories* — that *represent* *ways* the *world* *could* *be*.

**The *varieties*.**

| Variety | What a world is | Proponents | Problem |
|---|---|---|---|
| **Propositional** | A *maximal* *consistent* *set* of *propositions* | Adams (1974); Plantinga (1974) | The *circularity*: propositions are *defined* *modally* |
| **Linguistic** | A *maximal* *consistent* *set* of *sentences* | Carnap (1947); Jeffrey | The *language*-dependence: *which* *language*? |
| **Pictorial / magical** | A *primitive* *abstract* *representation* | Lewis’s *critique* of “magical ersatzism” | The *representation* *relation* is *mysterious* |
| **State-of-affairs** | A *maximal* *state* of *affairs* | Plantinga (1974, 1976) | The *nature* of *states* of *affairs* |

**The *argument*.** Ersatzism *preserves* the *analysis* *without* the *concrete* *worlds*. It is *more* *parsimonious* *ontologically* (abstract *entities* *instead* of *concrete* *worlds*), but it *pays* a *price*: it *needs* a *primitive* *representation* *relation* (the *abstract* *entity* *represents* a *world*), and the *relation* is *not* *explained*.

**Lewis’s *critique*** (*On the Plurality of Worlds*, 1986, Ch. 3). Ersatzism *cannot* *explain* *how* an *abstract* *entity* *represents* a *world* *without* *invoking* a *primitive* *intentionality* — a *“magic”* *relation*. The *critique* is *devastating* for the *pictorial* *variety*, and it is *a* *serious* *challenge* for the *propositional* and *linguistic* *varieties*.

**The *reply*.** The *ersatzist* *can* *accept* the *primitive* *representation* *relation*, and *argue* that the *primitive* is *less* *costly* than *concrete* *worlds*. (The *reply* is *contested*; the *debate* is *one* of the *central* *issues* *in* *contemporary* *metaphysics*.)

### 2.4 Fictionalism and conventionalism

The *third* and *fourth* *options* *avoid* the *commitment* to *worlds* *altogether*.

**Modal fictionalism** (Rosen 1990; also Ch. 14, §5). The *fictionalist* *accepts* the *possible-worlds* *discourse* as a *useful* *fiction*: “there is a possible world in which $p$” is *not* *literally* *true*, but it is *useful* for *reasoning*. The *fictionalist* *paraphrases* *modal* *claims* *as* *claims* *about* the *fiction*: “according to the *story* of *possible* *worlds*, there is a *world* in which $p$.”

**The *problems*.** (i) The *attitude* *problem*: what is the *mental* *state* of the *fictionalist*? (ii) The *inconsistency* *problem*: the *fiction* *must* be *consistent*, and the *consistency* *requires* *modality*. (iii) The *explanatory* *problem*: the *fiction* *explains* *nothing* if it is *not* *true*.

**Modal conventionalism** (Carnap 1947; Sidelle 1989; Thomasson 2015). The *conventionalist* *holds* that *modal* *facts* are *grounded* in *conventions* — *linguistic* *rules*, *conceptual* *schemes*, *practices*. The *claim* is *not* that *modality* is *arbitrary*, but that it is *constituted* by *our* *representational* *practices*.

**The *argument*.** The *conventionalist* *starts* from the *Kantian* *insight* that *necessity* is *not* *a* *feature* of the *world* *in* *itself*; it is a *feature* of *the* *way* *we* *represent* the *world*. The *conventionalist* *adds* the *naturalistic* *twist*: the *representational* *practices* are *linguistic* and *social*, and the *necessities* are *relative* to them.

**The *objection*.** The *conventionalist* *cannot* *explain* *why* *some* *conventions* *are* *correct* and *others* *are* *not*. If *all* *necessities* are *conventions*, *any* *convention* *is* *as* *good* *as* *any* *other*, and the *view* *collapses* *into* *relativism* (Ch. 13, §3). (The *reply*: the *conventions* are *constrained* by *the* *world* and by *practice*; the *reply* is *contested*.)

### 2.5 The verdict on possible worlds

The *debate* is *unresolved*, and the *positions* are *all* *costly*.

| Theory | What a world is | Strength | Weakness |
|---|---|---|---|
| **Modal realism** | A concrete whole | Unified; no primitive representation | Incredulous; epistemic access |
| **Ersatzism** | An abstract representation | Parsimonious | Primitive representation |
| **Fictionalism** | A useful fiction | Avoids commitment | Inconsistency; attitude |
| **Conventionalism** | A convention | Naturalistic | Relativism |

**The *honest* *position*.** The *possible-worlds* *analysis* is *indispensable*; the *metaphysics* of *possible* *worlds* is *contested*. The *debate* is *not* about *whether* to *use* *possible* *worlds*; it is about *what* they *are*. And the *answer* *depends* on the *general* *question* of *ontology* (Ch. 14) and on the *specific* *question* of *abstract* *objects* (Ch. 15, §6).

---

## 3. Essence and Ground

### 3.1 The revival of essentialism

The *most* *important* *development* in *post-Kripkean* *metaphysics* is the *revival* of **essentialism**: the *view* that *things* have *essential* *properties* — *properties* that *they* *could* *not* *have* *lacked* — and that the *essences* are *real*, *objective*, and *discoverable*.

**The *Kripke* *revival*.** Kripke (*Naming and Necessity*, 1980) *argued* that *identity* *statements* are *necessary* (Ch. 9, §3.3), and that the *necessities* *reveal* *essences*:

- **Origin essentialism** (Kripke 1980, pp. 110–115): a *person*'s *origin* — the *sperm* and *egg* *from* *which* *she* *came* — is *essential* *to* *her*.
- **Kind essentialism** (Putnam 1975, Kripke 1980): a *natural* *kind* *has* an *essential* *microstructure*.
- **Individual essence** (Kripke 1980, pp. 76–77): *every* *individual* has an *essential* *nature* — the *property* *of* *being* *that* *individual* — which *distinguishes* it *from* *every* *other* *possible* *individual*.

**The *Wiggins* *development*.** David Wiggins (*Sameness and Substance*, 1980; *Sameness and Substance Renewed*, 2001) *developed* a *systematic* *essentialism* *grounded* in **sortal** *concepts*: the *essence* of a *thing* is *determined* by the *sortal* *concept* *under* *which* it is *classified* (a *person*, a *tree*, a *statue*). The *sortal* *determines* the *persistence* *conditions* (Ch. 17, §4) and the *identity* *conditions*.

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{The identity statements of science and ordinary life are necessary (Ch. 9, §3.3).} \\
2. & \text{The necessities revelation of the natures of things.} \\
3. & \text{The natures are essences.} \\
\hline
4. & \therefore \text{Essentialism is true.}
\end{array}
$$

**The *objection*.** The *argument* *proves* that *some* *properties* are *necessary*, not that *essences* are *real*. (The *debate* is *about* whether the *necessary* *properties* are *grounded* in *essences* or in *conventions*, *concepts*, or *laws*.)

### 3.2 Fine's argument: essence is not modality

The *most* *important* *contemporary* *contribution* to the *theory* of *essence* is Kit Fine’s “Essence and Modality” (1994).

**The *target*.** The *standard* *account* — the **modal account** — *analyzes* *essence* in *terms* of *necessity*:

> **(MA)** $F$ is *essential* to $x$ iff $\Box(\text{if } x \text{ exists, then } Fx)$.

**Fine’s *counterexamples*.** The *modal* *account* *implies* that *any* *necessary* *property* *is* *essential*, and the *implication* is *absurd*.

**(i) The *singleton* case.** It is *necessary* that *Socrates* *is* a *member* of the *singleton* $\{\text{Socrates}\}$. But *being* a *member* of *that* *singleton* is *not* *essential* *to* *Socrates*: *Socrates* could have *existed* *without* the *singleton* (the *singleton* *depends* on *Socrates*, not *vice* *versa*). The *modal* *account* *gets* the *direction* *of* *dependence* *wrong*.

**(ii) The *necessary* *properties* *case.** It is *necessary* that *Socrates* is *not* a *number*, and *necessary* that *Socrates* is *self-identical*. But *being* *not* a *number* and *being* *self-identical* are *not* *essential* *to* *Socrates* in the *intuitive* *sense*: they do *not* *tell* *us* *what* *Socrates* *is*.

**(iii) The *order* *of* *explanation* *case.** The *modal* *account* *derives* *essence* *from* *necessity*; but *intuitively*, *necessity* *derives* *from* *essence*. *It is* *necessary* *that* *Socrates* is *human* *because* *being* *human* is *essential* *to* *Socrates* — *not* the *other* *way* *around*. The *modal* *account* *inverts* the *explanatory* *order*.

**Fine’s *positive* *account*.** Essence is *defined* in *terms* of **real definition**:

> **(RD)** $F$ is *essential* to $x$ iff it is *part* of the *real* *definition* of $x$ that $x$ is $F$.

The *notion* of *real* *definition* is *primitive*: it is *not* *analyzable* in *terms* of *necessity*, and it is *not* *reducible* to *conceptual* *analysis*. The *definition* *tells* *us* *what* the *thing* *is*, and the *necessity* *follows* from the *definition*, not *vice* *versa*.

**The *consequence*.** The *essence* *of* a *thing* is *not* the *set* of its *necessary* *properties*; it is the *set* of *properties* that *constitute* *its* *nature*. The *distinction* is *crucial*, and it is the *foundation* of the *contemporary* *essentialist* *program*.

### 3.3 Grounding

The *most* *important* *metaphysical* *notion* *in* *contemporary* *essentialism* is **grounding** (Fine 2001, 2012; Rosen 2010; Schaffer 2009; Correia and Schnieder 2012).

**The *notion*.** Grounding is the *relation* of *metaphysical* *dependence*: $A$ *grounds* $B$ (written $A < B$) iff $B$ *obtains* *in* *virtue* *of* $A$, or $A$ *makes* $B$ *obtain*, or $B$ *is* *grounded* in $A$.

**The *examples*.**

| Grounded | Ground |
|---|---|
| The *existence* of the *set* $\{Socrates\}$ | The *existence* of *Socrates* |
| The *truth* of “the rose is red” | The *rose*’s *being* *red* |
| The *dispositional* *properties* of a thing | Its *categorical* *basis* (contested) |
| The *mental* *state* | The *physical* *state* (contested) |
| The *moral* *fact* | The *natural* *fact* (contested; Ch. 44) |

**The *properties* of *grounding*.**

1. **Irreflexive**: nothing *grounds* *itself*.
2. **Asymmetric**: if $A$ *grounds* $B$, $B$ does *not* *ground* $A$.
3. **Transitive**: if $A$ *grounds* $B$ and $B$ *grounds* $C$, then $A$ *grounds* $C$.
4. **Explanatory**: the *ground* *explains* the *grounded*.

**The *role* in *essentialism*.** Grounding *connects* *essence* to *necessity*: the *essence* *of* a *thing* *grounds* its *necessary* *properties*. The *necessity* is *not* *brute*; it is *explained* by the *essence*, and the *essence* is *explained* by the *real* *definition*.

**The *objection*.** The *notion* of *grounding* is *contested* (Ch. 21, §6; Ch. 22, §2): is it a *real* *relation*, or a *notational* *variant* of *explanation*? If it is *real*, what *are* its *relata*? If it is *explanatory*, what *distinguishes* it from *causal* or *deductive* *explanation*? The *answers* are *contested*, and the *debate* is *one* of the *most* *active* *areas* of *contemporary* *metaphysics*.

### 3.4 The source of necessity

The *deepest* *question* in the *theory* of *modality* is: **what* *is* the *source* of *necessity*?

**The *four* *answers*.**

| Answer | What grounds necessity | Proponents | Problem |
|---|---|---|---|
| **Essentialist** | The *essences* of things | Kripke; Fine; Lowe | The *nature* of *essence* |
| **Conventionalist** | *Conventions* / *concepts* / *rules* | Carnap; Sidelle; Thomasson | *Relativism* |
| **Primitivist** | *Necessity* is *primitive* | Lewis; van Inwagen | *Unexplanatory* |
| **Theological** | The *nature* of *God* | Leibniz; Plantinga | *Contested* *premise* |

**The *essentialist* *answer* *in* *detail*.** The *necessity* of “Socrates is human” is *grounded* in the *essence* of *Socrates*: *being* *human* is *part* of *what* *it* *is* *to* *be* *Socrates*. The *necessity* of “water is H₂O” is *grounded* in the *essence* of *water*: *being* H₂O is *part* of *what* *it* *is* *to* *be* *water*. The *necessity* is *not* *a* *feature* of the *sentence*; it is a *feature* of the *thing*.

**The *conventionalist* *answer* *in* *detail*.** The *necessity* is *grounded* in the *conventions* of *our* *language*: “All bachelors are unmarried” is *necessary* *because* the *meaning* of “bachelor” *includes* *unmarriedness*. The *answer* *works* for *analytic* *truths*, and it *fails* for *Kripkean* *necessities* (water is H₂O is *not* *analytic*). The *conventionalist* *reply*: the *Kripkean* *necessities* are *grounded* in the *conventions* *that* *fix* *the* *reference* of “water” (Ch. 12, §3), and the *reference-fixing* *is* *conventional*. The *reply* *relocates* the *problem* to the *conventions*, and the *relocation* is *not* *satisfying*.

**The *primitivist* *answer*.** *Necessity* is *primitive*: it is *not* *grounded* in *anything*. The *answer* is *honest*, and it is *unexplanatory*. (The *primitivist* *can* *argue* that the *demand* for a *further* *ground* is *the* *criterion* *problem* *again* (Ch. 13, §1), and that the *demand* *cannot* be *met*.)

**The *state* of the debate.** The *essentialist* *answer* is the *dominant* *contemporary* *position*, and it is *contested*. The *debate* is *connected* to the *debate* about *grounding* (§3.3), about *laws* (Ch. 18, §5), and about *realism* (Ch. 22).

### 3.5 The objections to essentialism

**(i) The *epistemic* *objection*.** If *essences* are *real* *and* *objective*, how do we *know* them? The *answer* (Fine 1994; Lowe 2008) is that the *knowledge* is *a* *priori* — the *real* *definitions* are *grasped* by *reason* — and the *answer* *revisits* the *problems* of Ch. 9, §3.6.

**(ii) The *ideological* *objection*.** Essentialism has *historical* *associations* with *biological* *essentialism* (species have *fixed* *natures*), *gender* *essentialism* (women have *fixed* *natures*), and *racial* *essentialism*. The *associations* are *politically* *dangerous*, and the *contemporary* *essentialists* *distance* *themselves* from them (Ch. 42, §3; Ch. 11, §4). The *distance* is *real*, but the *terminology* *carries* *baggage*, and the *baggage* *must* be *acknowledged*.

**(iii) The *circularity* *objection*.** The *essentialist* *explains* *necessity* by *essence*, and *essence* by *real* *definition*, and the *real* *definition* is *not* *independently* *characterized*. The *charge* is *the* *same* as the *charge* against *grounding* (§3.3): the *primitive* is a *label*, not an *explanation*.

---

## 4. *De Re* Modality and Identity Across Worlds

### 4.1 The problem of transworld identity

The *problem* is *simple* to *state* and *hard* to *solve*.

**The *question*.** When we say “Socrates *might* have been a *carpenter*,” we are *comparing* the *actual* *Socrates* with a *possible* *Socrates* — a *counterpart*, or *the* *same* *individual* *in* *another* *world*. What *makes* the *possible* *Socrates* *the* *same* *individual* *as* the *actual* *Socrates*?

**The *two* *answers*.**

| Answer | What it is | Proponents |
|---|---|---|
| **Transworld identity** | The *same* *individual* *exists* *in* *many* *worlds* | Kripke; Plantinga; Stalnaker |
| **Counterpart theory** | The *individual* *exists* *in* *one* *world*; the *other* *worlds* *contain* *counterparts* | Lewis |

### 4.2 Counterpart theory

Lewis’s **counterpart theory** (“Counterpart Theory and Quantified Modal Logic,” 1968; *On the Plurality of Worlds*, 1986, Ch. 4) is the *most* *systematic* *alternative* to *transworld* *identity*.

**The *thesis*.** No *individual* *exists* *in* *more* *than* *one* *world*. What *we* *call* “Socrates in another world” is a *counterpart* of *Socrates* — a *different* *individual*, in *that* *world*, who *resembles* *Socrates* *in* the *relevant* *respects*.

**The *formalism*** (simplified).

- A *world* is a *concrete* *whole* (§2.2).
- A *counterpart* *relation* $C$ *holds* *between* *individuals* *in* *different* *worlds*.
- *Modal* *claims* are *analyzed* *in* *terms* of *counterparts*:

$$
\Box Fx \ \text{is true at} \ w \ \text{iff} \ \forall v \ \forall y \ (C(y, x, v) \to Fy \ \text{at} \ v)
$$

**The *virtue*.** The *theory* *avoids* the *problems* of *transworld* *identity*: there is *no* *mysterious* *relation* of *identity* *across* *worlds*, because there is *no* *identity* *across* *worlds*. The *counterpart* *relation* is a *similarity* *relation*, and *similarity* is *familiar*.

**The *cost*.** The *theory* *changes* the *subject*. “Socrates *might* have been a *carpenter*” is *analyzed* as “there is a *counterpart* of *Socrates* who is a *carpenter*” — and the *analysis* is *not* *what* we *meant*. We *meant* that *Socrates* — *the* *very* *man* — *might* have *been* a *carpenter*; the *counterpart* *theory* *says* that *someone* *else* *might* have *been* a *carpenter*, and the *someone* *else* is *not* *Socrates*.

### 4.3 The Humphrey objection

The **Humphrey objection** is the *most* *famous* *objection* to *counterpart* *theory*, and it is *due* to Saul Kripke (in *lectures*, and in *Naming and Necessity*, 1980, pp. 45–47; the *named* *form* is *due* to Humphrey’s *own* *reaction*).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{Counterpart theory says that Humphrey exists in one world only; the Humphrey who wins the election is a counterpart.} \\
2. & \text{But Humphrey intuitively could have won — he, the very man, could have won.} \\
3. & \text{The counterpart theory denies the intuition: Humphrey could not have won; only a counterpart could have won.} \\
\hline
4. & \therefore \text{Counterpart theory is false.}
\end{array}
$$

**Lewis’s *reply*** (*On the Plurality of Worlds*, 1986, pp. 196–209). The *intuition* is *not* *denied*; it is *reinterpreted*. *Humphrey* *could* *have* *won* *means*: there is a *world* in which a *counterpart* of *Humphrey* *wins*, and the *counterpart* is *close* *enough* to *Humphrey* that the *modal* *claim* is *about* *Humphrey* in the *relevant* *sense*. The *reply* *accepts* that *the* *counterpart* is *not* *Humphrey*, and *argues* that the *identity* *intuition* is a *philosophical* *prejudice*.

**The *counter-reply*** (Kripke 1980; Stalnaker 1986). The *reply* *changes* the *subject*: the *intuition* is *that* *Humphrey* *himself* *could* *have* *won*, and the *reply* *replaces* the *intuition* with a *different* *claim*. The *intuition* is *not* *a* *prejudice*; it is *the* *data* that the *theory* *must* *explain*.

**The *state* of the debate.** Counterpart *theory* is *elegant*, *powerful*, and *contested*. The *Humphrey* *objection* is *the* *strongest* *argument* *against* it, and the *reply* is *contested*.

### 4.4 Haecceities and individual essences

The *alternative* to *counterpart* *theory* is *transworld* *identity* *grounded* in **haecceities** — *primitive* *thisness* — or in **individual essences** — *properties* that *uniquely* *identify* an *individual* *in* *every* *world*.

**Haecceities** (Duns Scotus, *Ordinatio* II.3.1; Adams 1979; Rosenkrantz 1993). A *haecceity* is a *non-qualitative* *property* — the *property* *of* *being* *Socrates* — that *distinguishes* *Socrates* *from* *every* *other* *individual* *in* *every* *possible* *world*. The *property* is *primitive*; it is *not* *analyzable* *into* *qualitative* *properties*.

**Individual essences** (Plantinga 1974; Kripke 1980). An *individual* *essence* is a *qualitative* *property* (or *set* of *properties*) that *uniquely* *identifies* the *individual* *in* *every* *world*. The *candidate*: *origin* *essentialism* (the *sperm* and *egg*), *or* a *complex* *of* *essential* *properties*.

**The *objection*.** The *notion* of a *haecceity* is *mysterious*: what *is* the *property* *of* *being* *Socrates*? It is *not* a *qualitative* *property* (it is *not* *shared* by *any* *other* *individual*), and it is *not* *a* *relation*. The *notion* is a *label* for the *problem*, not a *solution*.

**The *reply*.** The *notion* is *primitive*, and *primitives* are *unavoidable* (the *criterion* *problem* again; Ch. 13, §1). The *question* is *whether* the *primitive* is *more* *explanatory* than the *alternatives* (counterparts, structuralism, conventionalism).

### 4.5 The state of the debate

The *debate* *between* *counterpart* *theory* and *transworld* *identity* is *unresolved*.

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Transworld identity** | The same individual exists in many worlds | Preserves the intuition | The *identity* relation is mysterious |
| **Counterpart theory** | Different worlds contain counterparts | Avoids the mystery | The Humphrey objection |
| **Haecceitism** | Primitive thisness | Grounds transworld identity | The *mystery* of haecceity |
| **Anti-haecceitism** | Only qualitative properties matter | Parsimonious | Denies the intuition of *thisness* |

The *honest* *position*: the *debate* is *not* *settled*, and the *choice* *depends* on the *weight* *given* to *intuition*, *parsimony*, and *explanatory* *power* (Ch. 4, §3).

---

## 5. Varieties of Possibility and Impossible Worlds

### 5.1 The varieties

The *varieties* of *possibility* were *introduced* in §1.3. The *important* *point* *for* *this* *section* is that the *varieties* *nest*, and the *nesting* is *not* *fully* *settled*.

**The *nesting* *picture*.**

```
        LOGICAL POSSIBILITY
        (no contradiction)
              |
              v
        METAPHYSICAL POSSIBILITY
        (consistent with essences)
              |
              v
        NOMOLOGICAL POSSIBILITY
        (consistent with the laws)
              |
              v
        PHYSICAL / PRACTICAL POSSIBILITY
        (consistent with the circumstances)
```

**The *contested* *relations*.**

- **Logical vs. metaphysical.** Is everything *logically* *possible* *metaphysically* *possible*? The *standard* *answer* is *no*: “water is XYZ” is *logically* *possible* (no contradiction) but *metaphysically* *impossible* (water is *essentially* H₂O). The *answer* *depends* on *essentialism* (§3).
- **Metaphysical vs. nomological.** Is everything *metaphysically* *possible* *nomologically* *possible*? The *standard* *answer* is *no*: “nothing travels faster than light” is *nomologically* *necessary* but *metaphysically* *contingent* (the laws *could* have been *different*). The *answer* *depends* on the *theory* of *laws* (Ch. 18, §5; Ch. 39, §1).
- **Conceptual vs. metaphysical.** Is everything *conceptually* *possible* *metaphysically* *possible*? The *standard* *answer* is *no*: the *conceptual* *possibility* is *broader* (it is *conceivability*), and the *conceivability–possibility* *thesis* is *contested* (§6).

### 5.2 Impossible worlds

**Impossible worlds** are *representations* of *impossible* *states* of *affairs* — *states* that *violate* the *laws* of *logic* or *metaphysics*. The *idea* is *ancient* (the *Stoics* *discussed* *impossible* *objects*), and it is *revived* *contemporarily* by Nolan (“Impossible Worlds: A Modest Approach,” 1997), Priest (*Towards Non-Being*, 2005), and Berto and Jago (*Impossible Worlds*, 2019).

**The *reasons* for *positing* them.**

**(i) The *semantics* of *counterpossibles*.** *Counterpossibles* are *counterfactuals* with *impossible* *antecedents*: “If $2+2=5$, then …” The *standard* *semantics* (Lewis 1973) *makes* *all* *counterpossibles* *vacuously* *true* (because there is *no* *world* in which the *antecedent* is *true*), and the *implication* is *counterintuitive*: “If $2+2=5$, then *everything* *is* *possible*” is *not* *obviously* *true*, and some *counterpossibles* seem *substantive* (“If the *laws* of *logic* *failed*, *reasoning* *would* *collapse*”).

**(ii) The *attitudes*.** We *believe*, *desire*, and *fear* *impossible* *things* (“I *believe* that *Fermat’s Last Theorem* *is* *false*” — *before* the *proof*, the *belief* *was* *consistent*; *after* the *proof*, the *belief* *is* *impossible*, and *yet* the *attitude* *is* *real*).

**(iii) The *logic* of *fiction*.** Fictional *worlds* *can* be *impossible* (a *contradictory* *character*, a *time-travel* *story* with *inconsistencies*), and the *semantics* of *fiction* *needs* to *handle* them (Ch. 49, §4).

**The *costs*.** (i) The *ontology* *is* *profligate*: *infinitely* *many* *impossible* *worlds*, *many* of them *contradictory*. (ii) The *logic* is *non-classical* (paraconsistent), and the *non-classical* *logic* is *contested* (Ch. 35, §5). (iii) The *epistemology* is *mysterious*: how do we *know* about *impossible* *worlds*?

**The *verdict*.** Impossible *worlds* are *promising* and *incomplete*. The *debate* is *active*, and it is *connected* to the *debate* about *counterfactuals* (Ch. 37, §3) and about *fiction* (Ch. 49, §4).

### 5.3 The conceptual possibility and the a priori

The *relationship* *between* *modality* and the *a priori* was *introduced* in Ch. 9, §5. The *connection* *bear* *repeating*.

**The *claim*.** *Conceptual* *possibility* — the *possibility* *of* a *proposition* *given* *the* *meanings* *of* *its* *terms* — is *the* *link* *between* the *a priori* and the *metaphysical*. The *a priori* *knowledge* of *conceptual* *possibility* is the *basis* of the *modal* *knowledge*.

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{To know that } \Diamond p \text{ is to know that } p \text{ is not excluded by the concepts involved.} \\
2. & \text{The knowledge that } p \text{ is not excluded by the concepts is a priori (Ch. 9, §3).} \\
\hline
3. & \therefore \text{Modal knowledge is a priori (at least in part).}
\end{array}
$$

**The *objection*.** The *argument* *assumes* that *conceptual* *possibility* *entails* *metaphysical* *possibility*, and the *assumption* is *the* *conceivability–possibility* *thesis* (§6.2), which is *precisely* what is *at* *issue*.

---

## 6. Modal Epistemology

### 6.1 The problem

**The *problem*.** We *know* *modal* *facts*: that $2+2=4$ is *necessary*, that *water* *is* H₂O is *necessary*, that *Socrates* *could* have *been* a *carpenter*. How do we *know* them? The *worlds* are *not* *observed* (they are *abstract* or *concrete* *but* *isolated*); the *essences* are *not* *perceived*; the *necessities* are *not* *empirical*. The *knowledge* is *a* *priori* (Ch. 9), and the *a* *priori* is *thin* and *fallible* (Ch. 9, §3.4).

**The *question*.** What *justifies* *modal* *beliefs*?

### 6.2 Conceivability–possibility

The *classical* *answer* is the **conceivability–possibility* *thesis*** (CP):

$$
(\mathrm{CP}) \quad \text{If } p \text{ is ideally conceivable, then } p \text{ is metaphysically possible.}
$$

**The *proponents*.** Hume (*Treatise*, 1739–40, I.ii.2; *Enquiry*, 1748, IV.i); Yablo (“Is Conceivability a Guide to Possibility?”, 1993); Chalmers (*The Conscious Mind*, 1996, Ch. 4; “Does Conceivability Entail Possibility?”, 2002).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{If } p \text{ is ideally conceivable, then no contradiction is involved in conceiving it.} \\
2. & \text{If no contradiction is involved, then } p \text{ is metaphysically possible.} \\
\hline
3. & \therefore \text{Conceivability entails possibility.}
\end{array}
$$

**The *problems*.**

**(i) The *idealization* *problem*.** What is *ideal* *conceivability*? It is *conceivability* by a *perfect* *reasoner*, with *all* the *relevant* *information*. The *notion* is *normative* and *unavailable*; it is *an* *ideal* *toward* *which* we *strive*, and the *striving* is *fallible*.

**(ii) The *Kripkean* *counterexamples*.** Kripke (1980) *argued* that *necessary* *truths* *can* be *conceivably* *false*: “water is not H₂O” is *conceivable* (we can *imagine* a *world* where the *stuff* is XYZ), but it is *not* *metaphysically* *possible* (water is *essentially* H₂O). The *CP* *thesis* *fails*.

**The *reply* (the *two-dimensional* *framework*).** See §6.3.

**(iii) The *empirical* *counterexamples*.** The *history* of *science* is a *history* of *conceivable* *possibilities* that *turned* *out* to be *impossible* (the *luminiferous* *ether*, *phlogiston*, *perpetual* *motion*). The *conceivability* *is* *not* a *guide* to *possibility*.

**The *reply*.** The *counterexamples* *involve* *conceptual* *confusion*: the *possibilities* *were* *not* *ideally* *conceivable* (they *violated* *essential* *properties* that *were* *discovered* *later*). The *reply* *saves* *CP* by *making* the *idealization* *very* *demanding* — *so* *demanding* that it is *nearly* *vacuous*.

### 6.3 The two-dimensional framework

The *most* *sophisticated* *attempt* to *save* the *connection* *between* *conceivability* and *possibility* is the **two-dimensional* *framework*** (Chalmers 1996, Ch. 4; 2002; 2006; Jackson 1998).

**The *core* *idea*.** Every *sentence* has *two* *intensions*:

- **The primary intension**: the *function* from *epistemic* *possibilities* (ways the *world* *could* *be*, *considered* *a* *priori*) to *truth* *values*.
- **The secondary intension**: the *function* from *metaphysical* *possibilities* (ways the *world* *could* be, *considered* *counterfactually*) to *truth* *values*.

**The *application* *to* *conceivability*.** The *primary* *intension* is *accessed* by *conceivability*: if a *sentence* is *conceivably* *true*, the *primary* *intension* *yields* *true* *at* the *epistemic* *possibility*. The *secondary* *intension* *yields* *the* *metaphysical* *possibility*.

**The *analysis* of “water is H₂O.”** The *primary* *intension* is *contingent*: “water is not H₂O” is *a* *priori* *conceivable*. The *secondary* *intension* is *necessary*: “water is H₂O” is *true* *in* *all* *metaphysically* *possible* *worlds*. The *two* *intensions* *diverge*, and the *divergence* *explains* the *Kripkean* *counterexamples*.

**The *virtue*.** The *framework* *reconciles* *conceivability* with *necessity*: the *conceivability* is *evidence* for *primary* *possibility*, not *secondary*. The *framework* *is* *the* *most* *influential* *tool* *in* *contemporary* *modal* *epistemology*.

**The *problems*.** (i) The *framework* is *technical* and *contested* (Ch. 9, §5.4). (ii) The *primary* *intension* is *defined* in *terms* of *epistemic* *possibility*, and the *notion* is *itself* *contested*. (iii) The *framework* is *designed* to *save* the *conceivability* *thesis*, and the *independent* *motivation* is *not* *clear*.

### 6.4 Modal empiricism

The *most* *important* *recent* *alternative* to *modal* *rationalism* is **modal* *empiricism*** (Williamson 2007; Roca-Royes 2011; Fischer 2016; Kment 2014). The *empiricist* *holds* that *modal* *knowledge* is *grounded* in *empirical* *knowledge* — *not* in *conceivability*.

**The *counterfactual* *account* (Williamson 2007).** We *know* *modal* *facts* by *knowing* *counterfactuals*, and we *know* *counterfactuals* by *ordinary* *empirical* *reasoning* (the *same* *reasoning* that *supports* *scientific* *laws*, *causal* *claims*, and *predictions*). The *counterfactual* *knowledge* is *a* *form* of *empirical* *knowledge*, and the *modal* *knowledge* *supervenes* on it.

**The *theory-based* *account* (Fischer 2016).** *Modal* *justification* is *grounded* in *theories* — *scientific* *theories*, *philosophical* *theories*, *conceptual* *frameworks* — and the *theories* are *justified* *empirically* *and* *by* *their* *virtues* (simplicity, explanatory power; Ch. 4, §3). The *modal* *knowledge* is *a* *by-product* of *theory* *construction*.

**The *virtue*.** The *account* *avoids* the *mystery* of *a* *priori* *modal* *insight*; it *connects* *modality* to *science*; it *explains* why *modal* *knowledge* *changes* with *theory* *change*.

**The *objection*.** The *account* *seems* *too* *empirical*: the *modal* *facts* (that $2+2=4$ is *necessary*) *seem* *independent* of *empirical* *theories*. (The *reply*: the *logical* and *mathematical* *necessities* are *a* *priori*, and the *empiricist* *account* *applies* to the *metaphysical* *necessities* — water is H₂O, Socrates is essentially human — which *are* *discovered* *empirically*.)

### 6.5 Modal skepticism

The *most* *radical* *position* is **modal* *skepticism*** (van Inwagen, “Modal Epistemology,” 1998; also the *earlier* *version* in “Two Concepts of Possible Worlds,” 1986).

**The *argument*.**

$$
\begin{array}{ll}
1. & \text{Modal knowledge requires a reliable method of access to modal facts.} \\
2. & \text{There is no such method: conceivability is unreliable; counterfactual reasoning is circular; essences are mysterious.} \\
\hline
3. & \therefore \text{Modal knowledge is impossible.}
\end{array}
$$

**The *conclusion*.** The *skeptic* *does* not *deny* that there are *modal* *facts*; the *skeptic* *denies* that we *know* them. The *position* is *consistent*, and it is *uncomfortable*.

**The *objections*.** (i) The *skeptic* *uses* *modal* *reasoning* (in the *argument* *itself*), and the *use* *presupposes* the *reliability* of the *method*. (ii) The *skeptic* *cannot* *explain* the *success* of *science*, which *relies* *on* *modal* *reasoning* (laws, counterfactuals, predictions). (iii) The *skeptic* *is* *self-undermining* (the *argument* *is* *itself* a *modal* *argument*).

**The *reply*.** The *skeptic* *uses* *modal* *reasoning* *locally* (to *make* the *argument*) and *denies* it *globally*; the *distinction* is *stable* (the *skeptical* *practice* vs. the *skeptical* *position*; Ch. 13, §6.3). The *reply* is *contested*.

### 6.6 The state of the debate

The *debate* is *unresolved*.

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Modal rationalism** | Conceivability is the guide | A priori; intuitive | The idealization; the Kripkean counterexamples |
| **Two-dimensionalism** | Primary vs. secondary intensions | Reconciles conceivability with necessity | Technical; contested |
| **Modal empiricism** | Modal knowledge is empirical | Naturalistic; testable | Seems too empirical |
| **Modal skepticism** | Modal knowledge is impossible | Consistent | Self-undermining; leaves practice unexplained |

**The *honest* *position*.** Modal *knowledge* is *real*, but it is *fallible* and *theory-laden*. The *best* *account* is a *hybrid*: *a* *priori* *knowledge* of *logical* and *mathematical* *necessity*, *empirical* *knowledge* of *metaphysical* *necessity* (via *science* and *theory*), and *conceivability* as a *heuristic* — *fallible* but *indispensable*.

---

## 7. Why Modality Matters

### 7.1 Ethics

**Supervenience.** The *moral* *supervenes* on the *natural*: there can be *no* *difference* in *moral* *properties* *without* a *difference* in *natural* *properties*. The *supervenience* *thesis* is a *modal* *thesis* (it is *necessary* that the *supervenience* *holds*), and it is *fundamental* to *metaethics* (Ch. 44, §1).

**Ought implies can.** The *principle* that *obligation* *implies* *ability* is a *modal* *principle*: if one *ought* to do $x$, one *can* do $x$. The *principle* is *central* to *deontology* (Ch. 45), to *free* *will* (Ch. 27), and to the *ethics* of *responsibility*.

**Moral necessity.** The *claim* that *some* *moral* *truths* are *necessary* (“torturing a child for fun is *necessarily* wrong”) is a *modal* *claim*, and it is *contested* (Ch. 44, §2).

### 7.2 Science

**Laws of nature.** The *laws* are *modally* *loaded*: they *support* *counterfactuals* (“if the *mass* were *doubled*, the *acceleration* would *halve*”), and they *sustain* *counterfactual* *inferences*. The *analysis* of *laws* is the *analysis* of *modality* (Ch. 18, §5; Ch. 39, §1).

**Dispositions.** The *dispositional* *properties* (solubility, charge, fragility) are *modally* *characterized*: a *soluble* *thing* *would* *dissolve* *if* *placed* in *water*. The *analysis* of *dispositions* is the *analysis* of *modality* (Ch. 15, §5.3).

**Scientific realism.** The *pessimistic* *meta-induction* (Ch. 40, §5) is a *modal* *argument*: our *current* *theories* are *probably* *false*, because *past* *theories* were *false*. The *argument* *turns* on the *modal* *notion* of *probability* and on the *modal* *notion* of *approximate* *truth*.

### 7.3 Ordinary language and action

**Ability.** “I *could* have *done* *otherwise*” is a *modal* *claim*, and it is *central* to *free* *will* (Ch. 27, §1). The *analysis* of *ability* is the *analysis* of *modal* *possibility* *relative* to *circumstances*.

**Counterfactuals.** “If I had *left* *earlier*, I *would* have *caught* the *train*” is a *modal* *claim*, and it is *central* to *responsibility*, *causation* (Ch. 18, §2), and *decision* (Ch. 28).

**Promising and intending.** “I *will* *pay* you *tomorrow*” is a *modal* *commitment*, and the *normativity* of the *commitment* is a *modal* *fact* (Ch. 34, §1).

### 7.4 The unity of the modal turn

The *applications* *show* that *modality* is not a *luxury*. It is the *framework* *category* of *metaphysics*, *epistemology*, *ethics*, and *science*. The *twentieth-century* *revival* of *modality* — Kripke, Lewis, Fine, Chalmers — is *one* of the *most* *important* *developments* in the *history* of *philosophy*, and its *consequences* are *still* *being* *worked* *out*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **Modal logic is formal.** The *quantified* *modal* *logic* is *well-founded*, and the *formal* *objections* *are* *answered*.
- **De re modality is legitimate.** The *quantified* *modal* *logic* *handles* *de re* *modality*, and the *semantics* *is* *clear*. The *philosophical* *question* of *essence* *remains*.
- **Possible worlds are indispensable.** The *analysis* *of* *modality* *in* *terms* of *possible* *worlds* is the *standard*, and the *alternatives* are *costly*.
- **Essentialism is real.** The *revival* of *essentialism* is the *dominant* *contemporary* *position*, and it is *grounded* in *Kripke’s* *necessities* and *Fine’s* *real* *definitions*.
- **Grounding is a real relation.** The *notion* of *grounding* is *central* to *contemporary* *metaphysics*, and it *connects* *essence* to *necessity*.
- **Modal knowledge is fallible.** The *conceivability–possibility* *thesis* is *contested*, the *two-dimensional* *framework* is *promising*, and *modal* *skepticism* is *live*.

### 8.2 What is open

- **The *nature* of *possible* *worlds*.** Are they *concrete* (Lewis), *abstract* (ersatz), *fictional* (fictionalism), or *conventional* (conventionalism)?
- **The *nature* of *essence*.** Is *essence* *reducible* to *necessity* (the *modal* *account*), or *primitive* (Fine)?
- **The *nature* of *grounding*.** Is it a *real* *relation*, or a *notational* *variant* of *explanation*?
- **The *source* of *necessity*.** Is it *essentialist*, *conventionalist*, *primitivist*, or *theological*?
- **The *relation* between *counterparts* and *transworld* *identity*.** Is the *counterpart* *theory* *adequate*, or is *haecceitism* *required*?
- **The *reliability* of *modal* *knowledge*.** Is *conceivability* a *guide* to *possibility*, or is *modal* *empiricism* the *better* *account*?

### 8.3 The methodological lesson

The chapter is a *case* *study* in the *method* of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *distinction* between *de* *dicto* and *de* *re*.
- **Thought experiments** (§2 of Ch. 3) — the *zombie* argument, the *singleton* case, *Humphrey’s* *counterpart* — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *modal* *logic*, the *possible-worlds* *semantics*, the *two-dimensional* *framework* — is *essential* for the *field*.
- **Reflective equilibrium** (§4 of Ch. 3) is the method by which the *intuitions* and the *theories* are adjusted.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to hold the *question* open.

The *honest* verdict: the *theory* of *modality* is a *field* in *transition*. The *formal* *core* is *settled*; the *metaphysics* is *contested*; the *epistemology* is *unresolved*. The *unresolved* character is *instructive*: it shows what philosophical progress looks like — not a *settled answer*, but a *sharper understanding* of what the *question* is.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Modal realism** | Worlds are concrete | Unified; no primitive representation | Incredulous; epistemic access |
| **Ersatzism** | Worlds are abstract | Parsimonious | Primitive representation |
| **Fictionalism** | Worlds are fictions | Avoids commitment | Inconsistency; attitude |
| **Conventionalism** | Worlds are conventions | Naturalistic | Relativism |
| **Modal account of essence** | Essence = necessity | Simple; familiar | The *singleton* case; the *order* of explanation |
| **Fine’s essentialism** | Essence = real definition | Corrects the *order* | The *nature* of *real* *definition* |
| **Counterpart theory** | No transworld identity | Avoids mystery | The Humphrey objection |
| **Haecceitism** | Primitive thisness | Grounds transworld identity | The mystery of haecceity |
| **Modal rationalism** | Conceivability is the guide | A priori; intuitive | The idealization; Kripkean cases |
| **Modal empiricism** | Modal knowledge is empirical | Naturalistic | Seems too empirical |
| **Modal skepticism** | Modal knowledge is impossible | Consistent | Self-undermining |

The *table* is a *map*, not a *verdict*. The *reader* who wants to *choose* a *position* must decide which *cost* is *acceptable* — and the *decision* is a *philosophical* *argument*.

---

## Optional threads

Cross-cutting material, for the reader who wants to go deeper.

**1. The *Barcan* *formula* and the *ontology* of *possible* *objects*.** The *validity* of BF determines whether *possibilia* are *actual* *entities* — whether there are *non-actual* *objects* (Ch. 14, §2). The *debate* is *technical*, and it is *connected* to the *debate* between *actualism* (Plantinga) and *possibilism* (Lewis). The *actualist* *must* *paraphrase* *away* the *quantification* *over* *possibilia*; the *possibilist* *accepts* it. The *choice* is *ontological*, not *logical*.

**2. Essence and *de re* modality in the *history* of philosophy.** The *medieval* *debates* on *de re* *modality*, *essentialism*, and *haecceity* (Duns Scotus, Ockham, Buridan) are *sophisticated*, and they *anticipate* the *contemporary* *debate* in *detail*. The *study* of the *history* is not *antiquarian*; it is a *source* of *arguments* (Knuuttila 1993; the *Stanford* *Encyclopedia* entry, “Medieval Theories of Modality”).

**3. Modality and *quantum* *mechanics*.** The *modal* *interpretation* of *quantum* *mechanics* (Dieks, Vermaas, Kochen) *treats* the *quantum* *state* as a *catalog* of *possibilities*, and the *measurement* as the *actualization* of *one* of them. The *view* is *contested*, and it is *connected* to the *debate* about *modality* *in* *physics* (Ch. 19, §5; Ch. 41, §4).

**4. Non-Western *theories* of *modality*.** The *Indian* *Nyāya-Vaiśeṣika* *tradition* *developed* a *sophisticated* *theory* of *possibility* and *necessity* (the *debate* on *kārya-kāraṇa*, the *svabhāva* *theory*, the *apūrva* *theory*), and the *Buddhist* *tradition* *developed* a *radical* *anti-essentialism* (the *anattā* *doctrine*, the *apoha* *theory*). The *traditions* *anticipate* the *contemporary* *debate* *between* *essentialism* and *anti-essentialism*, and they *offer* *systematic* *alternatives* (Matilal 1986; Ganeri 2001; the *essays* in *The Oxford Handbook of Indian Philosophy*, 2017).

**5. Modality and *artificial* *intelligence*.** The *AI* *systems* *reason* *counterfactually* (the *“what-if”* *prompting*, the *planning* *algorithms*), and the *philosophical* *questions* — *what* *is* the *modal* *knowledge* of an *AI*? *is* it *grounded* in *conceivability* or in *empirical* *regularities*? — are *new* and *urgent* (Ch. 29, §3). The *answers* *depend* on the *theory* of *modal* *epistemology* of §6, and the *theory* *needs* to *be* *general* *enough* to *cover* *both* *human* and *machine* *reasoners*.

---

## Summary

- **Modality** is the *framework* *category* of *metaphysics*: the *category* of the *possible* and the *necessary*. The *formal* *core* is the *modal* *operators*, the *modal* *logic*, and the *possible-worlds* *semantics*.
- **De dicto** *modality* *applies* to *sentences*; **de re** *modality* *applies* to *things*. The *distinction* is *central* to the *debate* about *essence*.
- **Quine** *attacked* *de re* *modality* as *unintelligible*, and the *formal* *response* (Barcan, Carnap, Kripke) *vindicated* it. The *philosophical* *challenge* *remains*: *what* *makes* a *property* *essential*?
- **Possible worlds** are the *standard* *tool* of *modal* *semantics*. The *metaphysics* is *contested*: **modal realism** (Lewis) is *concrete*; **ersatzism** is *abstract*; **fictionalism** is *fictional*; **conventionalism** is *conventional*.
- **The revival of essentialism** (Kripke, Wiggins) is the *dominant* *contemporary* *position*. **Fine’s argument** — *essence* is *not* *modality* — *refutes* the *modal* *account*, and *establishes* the *real* *definition* *account*.
- **Grounding** is the *relation* *that* *connects* *essence* to *necessity*, and it is *central* to *contemporary* *metaphysics*. The *source* of *necessity* is *contested* (essentialist, conventionalist, primitivist, theological).
- **De re** *modality* *across* *worlds* *raises* the *problem* of *transworld* *identity*. **Counterpart theory** *avoids* the *mystery* but *faces* the *Humphrey* *objection*; **haecceitism** *preserves* the *intuition* but *posits* a *mysterious* *entity*.
- **The varieties of possibility** *nest* (logical ⊃ metaphysical ⊃ nomological), and the *nesting* is *contested*. **Impossible worlds** are *promising* and *incomplete*, and they are *connected* to the *semantics* of *counterpossibles*.
- **Modal epistemology** is *unresolved*: **modal rationalism** *grounds* *modal* *knowledge* in *conceivability*; **modal empiricism** *grounds* it in *empirical* *theories*; **modal skepticism** *denies* it. The *two-dimensional* *framework* is the *most* *sophisticated* *reconciliation*.
- **Modality matters** for *ethics* (supervenience, ought-implies-can), *science* (laws, dispositions), and *ordinary* *action* (ability, counterfactuals). It is the *framework* *category* within which the rest of *metaphysics* *takes* place.

---

## Study Questions

1. State the *formal* *definitions* of the *modal* *operators*. What is the *modal* *square*, and what are its *philosophical* *implications*?
2. Distinguish *de dicto* from *de re* *modality*. Give an *example* of *each*, and explain why the *distinction* *matters*.
3. State Quine’s *attack* on *de re* *modality*. Is it *decisive*? What is the *best* *reply*?
4. State the *Barcan* *formula*. What does it *imply* about the *domain* of *possible* *worlds*? Is the *converse* *Barcan* *formula* *valid*?
5. State Lewis’s *modal* *realism*. Is it *defensible*? What is the *strongest* *objection*, and is the *reply* *adequate*?
6. Is *ersatzism* *preferable* to *modal* *realism*? What is the *“magical* *ersatzism”* *objection*, and is it *decisive*?
7. Is *modal* *fictionalism* a *coherent* *position*? What is the *strongest* *objection*?
8. State Fine’s *argument* that *essence* is *not* *modality*. Is it *decisive*? What is the *positive* *account*?
9. What is *grounding*? Is it a *real* *relation*? What *work* does it *do* in *essentialism*?
10. Is the *source* of *necessity* *essentialist*, *conventionalist*, or *primitivist*? Give the *strongest* *argument* for each, and state your *view* with a *calibrated* *confidence*.
11. State *counterpart* *theory*. What is the *Humphrey* *objection*, and is Lewis’s *reply* *adequate*?
12. Is *haecceitism* *defensible*? What is the *mystery* of *haecceity*, and is it *worse* than the *mystery* of *counterparts*?
13. What are the *varieties* of *possibility*? How do they *nest*? Is the *nesting* *defensible*?
14. Are *impossible* *worlds* *indispensable*? What *work* do they *do*?
15. State the *conceivability–possibility* *thesis*. Is it *defensible*? What is the *two-dimensional* *response* to the *Kripkean* *counterexamples*?
16. Is *modal* *knowledge* *a* *priori* or *empirical*? What is the *strongest* *argument* for each?
17. Is *modal* *skepticism* a *coherent* *position*? What is the *self-undermining* *worry*?
18. “Modality is not a *luxury*; it is the *framework* of metaphysics.” Assess. Give *three* *applications*.

---

## Further Reading

- **Primary**: Saul Kripke, *Naming and Necessity* (1980); David Lewis, *On the Plurality of Worlds* (1986); Kit Fine, “Essence and Modality” (1994), in *Modality and Tense* (2005); Ruth Barcan Marcus, “A Functional Calculus of First Order Based on Strict Implication” (1946), and “Essential Attribution” (1971); W. V. O. Quine, “Reference and Modality” (1953/1961), in *From a Logical Point of View* (1953), and “Three Grades of Modal Involvement” (1953).
- **On modal logic**: Saul Kripke, “Semantical Considerations on Modal Logic” (1963); G. E. Hughes and M. J. Cresswell, *A New Introduction to Modal Logic* (1996); Graham Priest, *An Introduction to Non-Classical Logic* (2nd ed., 2008); the *Stanford Encyclopedia* entry, “Modal Logic” (Garson).
- **On possible worlds**: David Lewis, *Counterfactuals* (1973), and *On the Plurality of Worlds* (1986); Robert Stalnaker, *Inquiry* (1984), and “Possible Worlds” (1976), in *Ways a World Might Be* (2003); Alvin Plantinga, *The Nature of Necessity* (1974); Robert Adams, “Theories of Actuality” (1974).
- **On essentialism**: Kit Fine, “Essence and Modality” (1994), and “The Question of Realism” (2001); David Wiggins, *Sameness and Substance Renewed* (2001); E. J. Lowe, *The Possibility of Metaphysics* (1998), and *More Kinds of Being* (2009); Penelope Mackie, *How Things Might Have Been* (2006); the *Stanford Encyclopedia* entry, “Essential vs. Accidental Properties” (Robertson and Atkins).
- **On grounding**: Kit Fine, “The Question of Realism” (2001), and “Guide to Ground” (2012); Gideon Rosen, “Metaphysical Dependence: Grounding and Reduction” (2010); Jonathan Schaffer, “On What Grounds What” (2009); the *essays* in *Metaphysical Grounding* (ed. Correia and Schnieder, 2012); the *Stanford Encyclopedia* entry, “Grounding” (Bliss and Trogdon).
- **On counterfactuals and counterparts**: David Lewis, “Counterpart Theory and Quantified Modal Logic” (1968), and *On the Plurality of Worlds* (1986), Ch. 4; Allen Hazen, “Counterpart-Theoretic Semantics for Modal Logic” (1979); Robert Stalnaker, “Counterparts and Identity” (1986); the *essays* in *The Possible and the Actual* (ed. Loux, 1979).
- **On impossible worlds**: David Lewis, “Logic for Equivocators” (1982); Daniel Nolan, “Impossible Worlds: A Modest Approach” (1997); Graham Priest, *Towards Non-Being* (2005); Francesco Berto and Mark Jago, *Impossible Worlds* (2019).
- **On modal epistemology**: Tamar Szabó Gendler and John Hawthorne (eds.), *Conceivability and Possibility* (2002); David Chalmers, “Does Conceivability Entail Possibility?” (2002), and *The Conscious Mind* (1996), Ch. 4; Stephen Yablo, “Is Conceivability a Guide to Possibility?” (1993); Timothy Williamson, *The Philosophy of Philosophy* (2007), Ch. 5; Peter van Inwagen, “Modal Epistemology” (1998); Bob Fischer, *Modal Justification via Theories* (2016); the *Stanford Encyclopedia* entry, “The Epistemology of Modality” (Vaidya).
- **On the history of modality**: Simo Knuuttila, *Modalities in Medieval Philosophy* (1993); the *Stanford Encyclopedia* entry, “Medieval Theories of Modality” (Knuuttila); Jaakko Hintikka, *Time and Necessity* (1973).
- **On non-Western theories**: B. K. Matilal, *The Character of Logic in India* (1998); Jonardon Ganeri, *Philosophy in Classical India* (2001); the *essays* in *The Oxford Handbook of Indian Philosophy* (ed. Ganeri, 2017), Part IV.

---

> *A closing note.* This chapter has followed the *framework* *category* of *metaphysics* — the possible and the necessary — through the *formal* *logic*, the *possible-worlds* *metaphysics*, the *essentialist* *revival*, the *grounding* *program*, the *problem* of *transworld* *identity*, the *varieties* of *possibility*, and the *epistemology* of the *modal*. The result is *not* a *settled* *theory* of *modality*, and it is *not* a *refutation* of *modality*. It is a *clarification*: modality is *real*, it is *indispensable*, and its *metaphysics* and its *epistemology* are *both* unresolved — but the *shape* of the disagreement has been clarified, and the clarification is a *genuine* achievement.

> *And a bridge.* The next chapter turns to *time* — the *modality* of the *temporal* *order*. If *modality* is the *category* of the *possible* and the *necessary*, *time* is the *category* of the *actual* and the *temporal*. The *two* are *connected*: the *A-theory* of *time* (Ch. 17, §1) *requires* a *primitive* *tense*, and *tense* is a *modal* *notion* (the *past* is *fixed*, the *future* is *open*); the *B-theory* *reduces* *tense* to *temporal* *position*, and the *reduction* is *the* *temporal* *analogue* of the *reduction* of *modality* to *possible* *worlds*. The *next* *chapter* *examines* the *connection*, and it *asks* the *question* the *modal* *theory* *presupposes*: *what* *is* the *temporal* *order*, and *why* does it *matter*?
