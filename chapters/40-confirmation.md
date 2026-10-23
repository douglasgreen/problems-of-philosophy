# Chapter 40 — Confirmation, Theory Choice, and Scientific Realism

> “The criterion of the scientific status of a theory is its falsifiability, or refutability, or testability.”
> — Karl Popper, *Conjectures and Refutations* (1963), Ch. 1

> “The positive argument for realism is that it is the only philosophy that does not make the success of science a miracle.”
> — Hilary Putnam, *Mathematics, Matter and Method* (1975), p. 73

> “The history of science is a graveyard of successful theories — phlogiston, caloric, the luminiferous ether, vital force, the electromagnetic aether, the ontologies of Newtonian mechanics. If the past is any guide, our current theories will join them.”
> — Larry Laudan, “A Confutation of Convergent Realism” (1981), in effect

---

Chapter 39 examined the *structure* of scientific knowledge — the laws, the kinds, the models. This chapter examines the *epistemology* of that knowledge: **how do we know that a theory is true, or probable, or at least worth believing?**

The question has a *peculiar* shape, because the *answer* is *less* secure *for* science than *for* almost any other domain. In *perception* (Ch. 5), the *perceptual* *belief* has the *world* *pressing* on it. In *mathematics* (Ch. 43), the *proof* *compels*. In *science*, the *theory* is *underdetermined* by the *evidence* (the *evidence* *never* *forces* a *unique* *theory*), the *observation* is *theory-laden* (the *data* are *never* *pure*), the *history* is a *graveyard* (the *successful* *theories* are *refuted*), and the *community* is *social* (the *consensus* is *negotiated*, and *sometimes* *manufactured*). If *any* *knowledge* *claim* is *vulnerable* to *skepticism*, the *scientific* *claim* is.

The chapter's *thesis* is that the *vulnerability* is *real* and *survivable*. The *assessment* of *theories* is a *complex*, *multi-dimensional*, *fallible* *practice* — and the *practice* is *justified* not by a *single* *criterion* (the *falsifiability*, the *Bayesian* *posterior*, the *consensus*) but by the *convergence* of *criteria* (the *empirical* *success*, the *explanatory* *power*, the *unification*, the *novel* *prediction*, the *social* *criticism*), and the *convergence* is *strong* *enough* to *ground* a *qualified* *realism* — a *realism* that is *selective* (it is *about* the *working* *posits*, not the *whole* *theory*), *structural* (it is *about* the *relations*, not the *intrinsic* *natures*), *probabilistic* (it is *about* the *degree* of *belief*, not the *certainty*), and *social* (it is *sustained* by the *institutions* of *criticism*).

The chapter proceeds in nine movements. §1 examines *confirmation* and the *ravens*. §2 examines *theory choice* and the *historicist* challenge. §3 examines *underdetermination*. §4 examines the *theory-ladenness* of observation. §5 examines *Bayesian* confirmation and its *problems*. §6 examines *scientific* *realism* and its *rivals*. §7 examines the *demarcation* problem. §8 examines *expert* *consensus* and the *social* *epistemology* of science. §9 gives an *honest* verdict.

---

## 1. The Problem of Confirmation

### 1.1 The naive account

**The *thesis***. A *hypothesis* is *confirmed* by its *positive* *instances* (the *observations* that *agree* with it), and *disconfirmed* by its *negative* *instances*.

**The *structure***.

$$
E \ \text{confirms} \ H \quad \text{iff} \quad E \ \text{is a positive instance of} \ H
$$

**The *example***. The *hypothesis* “all ravens are black” is *confirmed* by each *black* *raven*, and *disconfirmed* by each *non-black* *raven*.

**The *virtue***. The *account* *fits* the *ordinary* *practice* (the *observations* that *agree* with the *hypothesis* *support* it), and it is *simple* (the *confirmation* is the *agreement*).

### 1.2 Hempel's paradox of the ravens

**The *argument*** (Hempel, “Studies in the Logic of Confirmation,” 1945; *Aspects of Scientific Explanation*, 1965, Ch. 1).

**The *equivalence* *condition***. If $E$ *confirms* $H$, and $H$ is *logically* *equivalent* to $H'$, then $E$ *confirms* $H'$.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The hypothesis “all ravens are black” } (H_1) \text{ is logically equivalent to “all non-black things are non-ravens” } (H_2). \\
2. & \text{A white shoe is a positive instance of } H_2 \text{ (it is a non-black thing that is a non-raven).} \\
3. & \text{By the equivalence condition, the white shoe confirms } H_2, \text{ and therefore } H_1. \\
\hline
4. & \therefore \text{A white shoe confirms “all ravens are black” (the paradox).}
\end{array}
$$

**The *consequence***. The *naive* *account* *implies* that the *irrelevant* *observations* (the *white* *shoe*, the *red* *herring*, the *distant* *galaxy*) *confirm* the *hypothesis*, and the *implication* is *counterintuitive*.

### 1.3 The Bayesian resolution

**The *thesis*** (the *Bayesian* *reconstruction*; Howson & Urbach, *Scientific Reasoning: The Bayesian Approach*, 3rd ed., 2006, Ch. 2; the *contemporary* *literature*).

**The *definition***.

$$
E \ \text{confirms} \ H \quad \text{iff} \quad P(H \mid E) > P(H) \quad \text{iff} \quad P(E \mid H) > P(E \mid \neg H)
$$

**The *resolution***. The *white* *shoe* *does* *confirm* the *hypothesis*, but the *confirmation* is *tiny* (the *likelihood* *ratio* $P(E \mid H) / P(E \mid \neg H)$ is *close* to 1, because the *white* *shoe* is *slightly* *more* *likely* under the *hypothesis* than under the *negation*), and the *tiny* *confirmation* is *epistemically* *insignificant*.

**The *argument* (the *quantitative* *form*).

$$
\frac{P(H \mid E)}{P(H)} = \frac{P(E \mid H)}{P(E)} = \frac{P(E \mid H)}{P(E \mid H)P(H) + P(E \mid \neg H)P(\neg H)}
$$

For the *white* *shoe*, $P(E \mid H)$ and $P(E \mid \neg H)$ are *both* *close* to 1 (the *white* *shoe* is *almost* *certain* *whatever* the *ravens* are *like*), and the *ratio* is *close* to 1, and the *confirmation* is *negligible*.

**The *virtue***. The *resolution* *preserves* the *equivalence* *condition* (the *white* *shoe* *does* *confirm*), and it *explains* the *intuition* (the *confirmation* is *too* *small* to *matter*), and it *avoids* the *paradox* (the *paradox* is the *confusion* of the *qualitative* *confirmation* with the *quantitative* *significance*).

**The *objections***.

**(i) The *‘*no* *equivalence*’* *objection* (Good, “The White Shoe Is a Red Herring,” 1967; the *contemporary* *literature*). The *white* *shoe* *does* *confirm* the *hypothesis*, and the *amount* of *confirmation* is *not* *negligible* (the *Bayesian* *resolution* *depends* on the *priors*, and the *priors* are *contested*; the *different* *priors* *yield* the *different* *amounts*). The *objection* *relativizes* the *resolution* to the *prior*.

**The *reply***. The *confirmation* is *relative* to the *prior* (the *Bayesian* *insight*), and the *reply* *accepts* the *relativity* (the *confirmation* is *always* *relative* to the *background* *knowledge*). The *reply* is *contested*.

**(ii) The *‘*no* *paradox*’* *objection*. The *paradox* is *not* a *paradox* (the *white* *shoe* *does* *confirm*, and the *intuition* is *wrong*), and the *resolution* *dissolves* the *paradox* by *denying* the *intuition*. The *objection* *supports* the *Bayesian* *account*, and it is *contested* (the *intuition* is *strong*).

### 1.4 The grue problem revisited

**The *problem*** (Goodman, *Fact, Fiction, and Forecast*, 1955, Ch. 3; Ch. 10, §3).

**The *argument***. The *evidence* (the *observed* *green* *emeralds*) *confirms* the *hypothesis* “all emeralds are green,” and it *also* *confirms* the *hypothesis* “all emeralds are grue” (the *grue* *hypothesis* *agrees* with the *evidence* *before* the *time* $T$), and the *two* *hypotheses* *make* the *incompatible* *predictions* *after* $T$.

**The *consequences***. The *Bayesian* *resolution* *fails* (the *two* *hypotheses* *have* the *same* *likelihood* on the *evidence*, and the *difference* *must* be *in* the *priors*), and the *priors* *are* *contested* (the *naturalness* of the *predicates*; Ch. 15, §5.1), and the *entrenchment* (the *Goodman* *solution*) is *circular* (the *entrenchment* *presupposes* the *successful* *projections*, and the *success* *presupposes* the *entrenchment*).

**The *state* of the problem*** (Ch. 10, §3.6). The *problem* is *unresolved*, and the *Bayesian* *account* *relocates* the *problem* to the *priors*, and the *natural* *kinds* *provide* a *partial* *solution* (the *projectible* *predicates* *track* the *natural* *kinds*; Ch. 39, §3), and the *solution* *presupposes* the *realism* *about* the *natural* *kinds*.

### 1.5 The problem of old evidence

**The *problem*** (Glymour, *Theory and Evidence*, 1980, Ch. 3; the *contemporary* *literature*). The *Bayesian* *account* *cannot* *explain* the *confirmation* by the *evidence* that is *already* *known* (the *old* *evidence*): the *evidence* has *already* been *conditionalized* *on*, and the *conditional* *probability* $P(H \mid E)$ *is* *equal* to $P(H)$, and the *confirmation* *is* *zero*, and the *consequence* *is* *absurd* (the *perihelion* *of* *Mercury* *confirmed* the *general* *relativity*, and the *perihelion* *was* *known* *before* the *theory*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The Bayesian confirmation requires } P(H \mid E) > P(H) \text{ (the definition).} \\
2. & \text{If } E \text{ is already known, the agent has already conditionalized on } E, \text{ and } P(H \mid E) = P(H). \\
\hline
3. & \therefore \text{The old evidence confirms nothing (the problem).}
\end{array}
$$

**The *responses***.

**(i) The *‘*counterfactual*’* *response*** (Garber, “Old Evidence and Logical Omniscience in Bayesian Confirmation Theory,” 1983). The *confirmation* is *measured* by the *counterfactual* *credence* (the *credence* the *agent* *would* *have* *had* if she *had* *not* *known* the *evidence*), and the *reply* *grounds* the *confirmation* in the *counterfactual*.

**The *objection***. The *counterfactual* is *not* *well*-*defined* (the *different* *counterfactual* *scenarios* *yield* the *different* *confirmations*), and the *reply* is *contested*.

**(ii) The *‘*learning*’* *response*** (Howson, “Some Recent Objections to the Bayesian Theory of Support,” 1984; Howson & Urbach 2006, Ch. 6). The *confirmation* is the *learning* of the *relation* between $H$ and $E$ (the *agent* *learns* that $H$ *entails* $E$, and the *learning* *boosts* the *credence* in $H$), and the *reply* *grounds* the *confirmation* in the *logical* *relation*, not the *evidence*.

**The *objection***. The *reply* *changes* the *subject* (the *confirmation* is the *learning* *of* the *entailment*, not the *evidence*), and the *reply* is *contested*.

**(iii) The *‘*no* *problem*’* *response***. The *old* *evidence* *does* *confirm* the *theory* (the *theory* *explains* the *evidence*, and the *explanation* *is* the *confirmation*), and the *Bayesian* *account* *needs* the *explanation* *relation* (the *likelihood* *includes* the *explanatory* *power*; Ch. 38, §3). The *reply* *connects* the *confirmation* to the *explanation*, and it is *contested*.

### 1.6 The catch-all problem

**The *problem*** (the *contemporary* *literature*; the *Bayesian* *account*). The *denominator* of the *Bayes* *theorem* requires the *sum* over the *alternatives*:

$$
P(E) = P(E \mid H)P(H) + P(E \mid H_1)P(H_1) + P(E \mid H_2)P(H_2) + \cdots
$$

and the *sum* *requires* the *specification* of the *catch*-*all* $(H_1 \vee H_2 \vee \cdots)$, and the *catch*-*all* is *not* *specifiable* (the *space* of the *alternatives* is *open*, and the *unconceived* *alternatives* are *not* *in* the *sum*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The Bayesian confirmation requires the probability } P(E) \text{ (the marginal likelihood).} \\
2. & \text{The } P(E) \text{ requires the specification of the catch-all (the alternatives).} \\
3. & \text{The catch-all is not specifiable (the unconceived alternatives).} \\
\hline
4. & \therefore \text{The Bayesian account presupposes the unavailable totality (the problem).}
\end{array}
$$

**The *responses***.

**(i) The *‘*relative*’* *response*** (the *contemporary* *literature*). The *confirmation* is *relative* to the *specified* *alternatives* (the *agent* *compares* the *hypotheses* she *has*, and the *comparison* is *valid* *relative* to the *set*), and the *reply* *relativizes* the *confirmation* to the *set*.

**The *virtue***. The *reply* *fits* the *practice* (the *scientists* *compare* the *available* *theories*), and it *avoids* the *totality*.

**The *objection***. The *relativity* *undermines* the *realism* (the *confirmation* *depends* on the *set* of the *alternatives*, and the *set* is *contingent*), and the *objection* is *contested* (the *realism* can *accept* the *relativity*; the *confirmation* is *always* *relative* to the *background*).

**(ii) The *‘*unconceived*’* *response*** (Stanford, *Exceeding Our Grasp*, 2006, Ch. 2). The *catch*-*all* is *not* a *problem* *for* the *confirmation*; it is a *problem* for the *realism* (the *unconceived* *alternatives* *undermine* the *confidence* in the *current* *theories*; §3.4). The *reply* *relocates* the *problem*, and it is *promising*.

### 1.7 The state of the confirmation debate

**The *assessment***. The *confirmation* is *real*, and the *Bayesian* *account* is the *most* *developed*, and the *account* *faces* the *technical* *problems* (the *priors*, the *old* *evidence*, the *catch*-*all*).

| The *problem* | The *status* | The *response* |
|---|---|---|
| **The ravens** | *Resolved* (tiny confirmation) | The Bayesian |
| **Grue** | *Relocated* (to the priors) | The natural kinds |
| **Old evidence** | *Contested* | The counterfactual / the learning |
| **Catch-all** | *Contested* | The relative / the unconceived |

**The *most* *defensible* *position***. A *qualified* *Bayesianism*: the *confirmation* is the *raising* of the *credence* (the *Bayesian* *insight*), and the *credence* is *relative* to the *prior* (the *subjectivist* *insight*), and the *prior* is *constrained* by the *natural* *kinds* and the *explanatory* *power* (the *objectivist* *insight*; Ch. 10, §5), *qualified* by the *admission* that the *old* *evidence* and the *catch*-*all* *remain* *unresolved*.

---

## 2. Theory Choice and the Historicist Challenge

### 2.1 The logical empiricist picture

**The *thesis*** (Hempel, *Aspects*, 1965, Ch. 8; Carnap, *The Logical Foundations of Probability*, 1950; the *logical* *empiricist* *tradition*). The *theory* *choice* is *rational* *inference* (the *confirmation* is the *logical* *relation* between the *evidence* and the *theory*), and the *criteria* are *formal* (the *confirmation*, the *simplicity*, the *explanatory* *power*), and the *criteria* are *objective*.

**The *structure***.

$$
\text{TheoryChoice}(T_1, T_2) = f(\text{confirmation}, \text{simplicity}, \text{scope}, \ldots)
$$

**The *virtue***. The *picture* *grounds* the *theory* *choice* in the *epistemic* *norms*, and it *avoids* the *relativism* (the *norms* are *objective*).

**The *objections*** (the *historicist* *challenge*; §2.2–2.4). The *picture* *misdescribes* the *scientific* *practice* (the *theory* *choice* *involves* the *paradigm*, the *tradition*, the *sociological* *factors*), and the *norms* are *not* *sufficient* to *determine* the *choice* (the *underdetermination*; §3), and the *historicist* *challenge* *undermines* the *rationality* *of* the *science*.

### 2.2 Kuhn and the paradigms

**The *thesis*** (Kuhn, *The Structure of Scientific Revolutions*, 1962; 4th ed., 2012). The *science* *develops* through the *paradigms* (the *shared* *exemplars*, the *models*, the *standards*), and the *development* *has* the *structure*: the *normal* *science* → the *anomaly* → the *crisis* → the *revolution* → the *new* *paradigm*.

**The *structure***.

| The *phase* | The *activity* | The *example* |
|---|---|---|
| **Pre-paradigm** | The *competing* *schools* (no *consensus*) | The *pre-Newtonian* *optics* |
| **Normal science** | The *puzzle-solving* *within* the *paradigm* | The *Newtonian* *mechanics* |
| **Anomaly** | The *failure* of the *paradigm* to *solve* a *puzzle* | The *perihelion* *of* *Mercury* |
| **Crisis** | The *proliferation* of the *anomalies* and the *alternatives* | The *quantum* *crisis* (the *1920s*) |
| **Revolution** | The *replacement* of the *paradigm* | The *Copernican* *revolution* |

**The *incommensurability***. The *paradigms* are *incommensurable* (the *terms* *change* *meaning*, the *standards* *change*, the *problems* *change*), and the *choice* *between* them is *not* *determined* by the *neutral* *evidence* (the *evidence* is *paradigm*-*laden*; §4), and the *conversion* is *not* *rational* *inference* (it is the *Gestalt* *switch*, the *persuasion*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The paradigms determine the meaning of the terms and the standards of the assessment (the incommensurability).} \\
2. & \text{The evidence is paradigm-laden (it cannot be described neutrally).} \\
3. & \text{The choice between the paradigms cannot be determined by the neutral evidence.} \\
\hline
4. & \therefore \text{The theory choice is not determined by the norms (the Kuhnian challenge).}
\end{array}
$$

**The *virtue***. The *account* *fits* the *history* of the *science* (the *revolutions* *are* *real*, and the *paradigm* *shifts* *are* *traumatic*), and it *captures* the *social* *dimension* (the *community*, the *education*, the *exemplars*).

**The *objections***.

**(i) The *‘*no* *rationality*’* *objection* (the *contemporary* *literature*; Laudan 1977; the *“*Kuhn* *is* *a* *relativist”* *reading*). The *account* *undermines* the *rationality* of the *science* (the *choice* is *the* *conversion*, not the *argument*), and the *consequence* *is* *unacceptable*.

**The *reply*** (Kuhn 1970, 1977; the *Postscript* to the *Structure*, 1969). The *choice* *is* *rational* (it is *grounded* in the *shared* *values*: the *accuracy*, the *consistency*, the *scope*, the *simplicity*, the *fruitfulness*), and the *reply* *grounds* the *rationality* in the *values*, not the *rules*. The *reply* is *contested* (the *values* *do* not *determine* the *choice*, and the *choice* *requires* the *judgment*).

**(ii) The *‘*no* *incommensurability*’* *objection* (the *contemporary* *literature*; the *“*translatability*”* *thesis*). The *paradigms* *are* *translatable* (the *terms* *can* be *translated*, and the *standards* *can* be *compared*), and the *incommensurability* is *overstated* (the *partial* *communication* *is* *possible*, and the *choice* *is* *rational* *enough*). The *reply* *weakens* the *Kuhnian* *challenge*, and it is *contested* (the *translation* is *never* *complete*).

### 2.3 Lakatos and the research programs

**The *thesis*** (Lakatos, “Falsification and the Methodology of Scientific Research Programs,” 1970; *Philosophical Papers*, Vol. I, 1978). The *science* *develops* through the *research* *programs* (the *series* of the *theories* *sharing* a *hard* *core*), and the *programs* are *assessed* by the *progressiveness* (the *novel* *predictions*) or the *degeneration* (the *ad hoc* *patches*).

**The *structure***.

| The *element* | The *definition* | The *example* (the *Newtonian* *program*) |
|---|---|---|
| **Hard core** | The *irrefutable* *assumptions* | The *three* *laws* *of* *motion* |
| **Protective belt** | The *auxiliary* *hypotheses* (the *testable* *consequences*) | The *planetary* *perturbations* |
| **Positive heuristic** | The *guidance* for the *development* | The *successive* *models* |
| **Negative heuristic** | The *prohibition* (the *core* *is* *not* *tested*) | The *refusal* to *abandon* the *laws* |

**The *virtue***. The *account* *fits* the *history* (the *programs* *persist* *through* the *anomalies*, and the *progress* is *measured* by the *novel* *predictions*), and it *avoids* the *naive* *falsificationism* (the *core* is *not* *falsified* by the *single* *anomaly*), and it *preserves* the *rationality* (the *progressiveness* is the *objective* *criterion*).

**The *objections***.

**(i) The *‘*no* *demarcation*’* *objection* (the *contemporary* *literature*). The *account* *cannot* *distinguish* the *progressive* *programs* from the *degenerating* *ones* (the *degenerating* *program* *can* *become* *progressive*, and the *judgment* is *retrospective*), and the *criterion* is *not* *applicable* *in* *real* *time*.

**The *reply*** (Lakatos 1970; the *contemporary* *literature*). The *judgment* is *retrospective* (the *history* *decides*), and the *reply* *accepts* the *retrospectivity*, and it is *contested* (the *science* *must* *decide* *in* *real* *time*).

**(ii) The *‘*no* *core*’* *objection*. The *hard* *core* is *not* *given* (the *scientists* *disagree* *about* the *core*, and the *core* *changes*), and the *account* *presupposes* the *consensus*.

**The *reply***. The *core* is *constituted* by the *community* (the *shared* *commitments*), and the *reply* *grounds* the *core* in the *practice*. The *reply* is *contested*.

### 2.4 Feyerabend and the anarchism

**The *thesis*** (Feyerabend, *Against Method*, 1975; *Science in a Free Society*, 1978). There is *no* *method* (the *science* *does* not *follow* the *universal* *rules*), and the *scientific* *progress* *requires* the *violation* of the *rules* (the *counter*-*induction*, the *propaganda*, the *rhetoric*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The actual science violates the methodological rules (the Galileo case: the telescope observations contradicted the common sense, and Galileo relied on the rhetoric and the propaganda).} \\
2. & \text{The violations are not irrational (they are necessary for the progress).} \\
\hline
3. & \therefore \text{There is no universal method (the anarchism), and the science is one tradition among the many (the relativism).}
\end{array}
$$

**The *virtue***. The *account* *captures* the *actual* *practice* (the *science* is *messy*, and the *rhetoric* matters), and it *challenges* the *complacency* (the *science* is *not* *self*-*justifying*).

**The *objections***.

**(i) The *‘*no* *science*’* *objection* (the *contemporary* *literature*). The *account* *undermines* the *authority* of the *science* (the *science* is *just* *another* *tradition*), and the *consequence* *is* *unacceptable* (the *science* *works*, and the *works* *demands* the *epistemic* *authority*).

**The *reply*** (Feyerabend 1978). The *authority* is *political* (the *science* *should* be *subject* to the *democratic* *control*), and the *reply* *grounds* the *authority* in the *politics*. The *reply* is *contested*.

**(ii) The *‘*no* *alternative*’* *objection*. The *account* *offers* no *alternative* *method* (the *science* *needs* *the* *method*, and the *anarchism* *leaves* *nothing*), and the *consequence* is *nihilism*.

**The *reply*** (the *contemporary* *literature*; Chang 2022). The *methods* *are* *plural* (the *different* *methods* *for* the *different* *contexts*), and the *reply* *grounds* the *pluralism* in the *practice*. The *reply* is *contested*.

### 2.5 Laudan and the research traditions

**The *thesis*** (Laudan, *Progress and Its Problems*, 1977). The *science* *develops* through the *research* *traditions* (the *families* of the *theories* *sharing* the *metaphysical* and *methodological* *commitments*), and the *progress* is *measured* by the *problem*-*solving* *effectiveness*.

**The *structure***.

| The *element* | The *definition* | The *example* |
|---|---|---|
| **Research tradition** | The *family* of the *theories* *sharing* the *commitments* | The *Cartesian* *tradition* |
| **Problem** | The *empirical* and *conceptual* *puzzles* | The *planetary* *motion* |
| **Progress** | The *problem*-*solving* *effectiveness* | The *Newtonian* *mechanics* |

**The *virtue***. The *account* *grounds* the *progress* in the *problem*-*solving*, and it *avoids* the *Kuhnian* *incommensurability* (the *traditions* *are* *comparable* by the *problem*-*solving*) and the *Lakatosian* *retrospectivity* (the *progress* is *measurable* *in* *real* *time*).

**The *objections***.

**(i) The *‘*no* *measure*’* *objection*. The *problem*-*solving* *effectiveness* is *not* *measurable* (the *different* *problems* *have* the *different* *weights*, and the *weights* are *contested*), and the *account* *is* *incomplete*.

**The *reply*** (Laudan 1977). The *weights* are *determined* by the *tradition* (the *community* *decides*), and the *reply* *grounds* the *measure* in the *practice*. The *reply* is *contested*.

**(ii) The *‘*no* *truth*’* *objection*. The *account* *abandons* the *truth* (the *progress* is the *problem*-*solving*, not the *truth*), and the *consequence* *undermines* the *realism*.

**The *reply***. The *truth* is *not* *required* for the *progress* (the *progress* is *instrumental*), and the *reply* *grounds* the *progress* in the *practice*. The *reply* is *contested*.

### 2.6 The state of the historicist debate

**The *assessment***. The *historicist* *challenge* is *real* (the *theory* *choice* *involves* the *paradigm*, the *tradition*, the *values*, the *rhetoric*), and the *responses* are *all* *contested*.

| The *position* | The *strength* | The *weakness* |
|---|---|---|
| **Logical empiricist** | The objective norms | The description of the practice |
| **Kuhn** | The revolutions; the community | The rationality |
| **Lakatos** | The programs; the progressiveness | The retrospectivity |
| **Feyerabend** | The practice; the rhetoric | The no-science |
| **Laudan** | The problem-solving | The no-truth |

**The *most* *defensible* *position***. A *qualified* *historicism*: the *theory* *choice* *involves* the *paradigm* and the *community* (the *historicist* *insight*), and the *choice* is *rational* *relative* to the *shared* *values* (the *Kuhnian* *insight*), and the *values* *are* *not* *sufficient* to *determine* the *choice* (the *underdetermination* *insight*), and the *choice* *requires* the *judgment* (the *virtue* *insight*; Ch. 4, §3.2), *qualified* by the *admission* that the *judgment* is *not* *algorithmic* and the *rationality* is *not* *guaranteed*.

---

## 3. Underdetermination

### 3.1 The Duhem–Quine thesis

**The *thesis*** (Duhem, *The Aim and Structure of Physical Theory*, 1906; Quine, “Two Dogmas of Empiricism,” 1951; *Word and Object*, 1960).

**The *argument***. The *scientific* *hypothesis* is *never* *tested* *alone* (it is *tested* *with* the *auxiliary* *hypotheses*), and the *failure* of the *test* does *not* *show* *which* *hypothesis* is *responsible* (the *hypothesis*, the *auxiliary*, the *observation*), and the *evidence* *underdetermines* the *hypothesis*.

**The *structure***.

$$
T \wedge A \ \vdash \ O; \quad \neg O \ \therefore \ \neg T \vee \neg A
$$

**The *virtue***. The *thesis* *captures* the *holistic* *nature* of the *testing* (the *test* *involves* the *whole* *theoretical* *network*), and it *explains* the *persistence* of the *theories* through the *anomalies* (the *anomaly* can be *blamed* on the *auxiliary*).

**The *significance*.** The *thesis* *undermines* the *naive* *falsificationism* (the *single* *anomaly* does *not* *refute* the *theory*), and it *grounds* the *underdetermination* (§3.2).

### 3.2 Weak and strong underdetermination

**The *distinction***.

| The *kind* | The *claim* | The *status* |
|---|---|---|
| **Weak underdetermination** | The *evidence* does *not* *deductively* *entail* the *theory* (the *theory* is *not* *provable*) | *Trivial* (the *induction* is *not* *deduction*) |
| **Strong underdetermination** | For any *theory*, there is an *empirically* *equivalent* *rival* (the *rival* *has* the *same* *observational* *consequences*) | *Contested* (the *existence* of the *rivals*) |

**The *argument* (the *strong* *version*).

$$
\begin{array}{ll}
1. & \text{The theories have the observational consequences (the empirical content).} \\
2. & \text{The same observational consequences can be captured by the different theories (the equivalence).} \\
3. & \text{The evidence cannot distinguish the equivalent theories (the theoretical claims differ).} \\
\hline
4. & \therefore \text{The evidence underdetermines the theoretical claims (the strong underdetermination).}
\end{array}
$$

**The *examples***. The *Newtonian* *mechanics* *vs.* the *relativistic* *mechanics* (the *different* *ontologies*, the *same* *observations* *in* the *low*-*energy* *limit*); the *wave* *vs.* the *particle* *theories* *of* *light* (the *different* *ontologies*, the *same* *interference* *patterns*); the *computational* *models* (the *different* *algorithms*, the *same* *behavior*).

### 3.3 Transient and permanent underdetermination

**The *distinction*** (Laudan & Leplin, “Empirical Equivalence and Underdetermination,” 1991; the *contemporary* *literature*).

| The *kind* | The *claim* | The *example* |
|---|---|---|
| **Transient** | The *underdetermination* is *temporary* (the *future* *evidence* *distinguishes* the *theories*) | The *wave* *vs.* the *particle* *theories* (the *photoelectric* *effect* *distinguishes*) |
| **Permanent** | The *underdetermination* is *permanent* (no *possible* *evidence* *distinguishes*) | The *empirically* *equivalent* *rivals* |

**The *argument* (the *Laudan*–*Leplin* *critique*).

$$
\begin{array}{ll}
1. & \text{The strong underdetermination requires the permanent equivalence (the rivals are empirically equivalent in every respect).} \\
2. & \text{The equivalence is not established (the rivals are equivalent relative to the current auxiliaries, and the auxiliaries can be changed).} \\
\hline
3. & \therefore \text{The strong underdetermination is not established (the transient underdetermination is real, and the permanent is speculative).}
\end{array}
$$

**The *virtue***. The *critique* *weakens* the *strong* *underdetermination* (the *equivalence* is *not* *established*), and it *preserves* the *realism* (the *theory* *choice* is *justified* by the *evidence*, and the *underdetermination* is *transient*).

**The *objections***.

**(i) The *‘*unconceived*’* *objection* (Stanford, *Exceeding Our Grasp*, 2006, Ch. 2). The *problem* is *not* the *empirically* *equivalent* *rivals* (the *conceived* ones), but the *unconceived* *alternatives* (the *theories* *we* *have* *not* *imagined*), and the *unconceived* *alternatives* *undermine* the *confidence* in the *current* *theories* (the *history* of the *science* *shows* that the *alternatives* *were* *unconceived*; the *Newtonian* *mechanics* *was* *not* *challenged* by the *relativity* *until* the *twentieth* *century*).

**The *reply*** (the *contemporary* *literature*; the *Bayesian* *account*). The *unconceived* *alternatives* *lower* the *confidence* (the *prior* *mass* *is* *distributed* over the *unknown* *alternatives*), and the *reply* *grounds* the *confidence* in the *probability*, not the *certainty*. The *reply* is *contested* (the *prior* *mass* *is* *not* *specifiable*).

**(ii) The *‘*no* *equivalence*’* *objection*. The *empirically* *equivalent* *rivals* *are* *not* *genuine* *rivals* (they are the *same* *theory* *under* the *different* *descriptions*, or the *rivals* *differ* in the *theoretical* *virtues*), and the *underdetermination* *is* *not* *real*.

**The *reply***. The *rivals* *are* *genuine* (they *differ* in the *ontologies*, and the *ontologies* *matter* for the *explanation*; Ch. 38), and the *reply* *grounds* the *underdetermination* in the *theoretical* *content*. The *reply* is *contested*.

### 3.4 The unconceived alternatives

**The *thesis*** (Stanford 2006, Ch. 1). The *problem* of the *underdetermination* is *not* the *empirically* *equivalent* *rivals* (the *conceived* ones) but the *unconceived* *alternatives* (the *theories* *we* *have* *not* *imagined*), and the *history* of the *science* *shows* that the *unconceived* *alternatives* *were* *real* (the *Newtonian* *mechanics* *was* *replaced* by the *relativity*, and the *replacement* was *not* *imagined* by the *Newtonians*).

**The *argument***.

$$
\begin{array}{ll}
1. & \text{The history of the science shows that the current theories were replaced by the theories that were not imagined (the unconceived alternatives).} \\
2. & \text{The unconceived alternatives are not in the evidence (the evidence cannot distinguish the alternatives we have not imagined).} \\
3. & \text{The confidence in the current theories is undermined by the unconceived alternatives.} \\
\hline
4. & \therefore \text{The realism is undermined (the confidence is not justified), and the anti-realism is supported (the theories are the current best organizations of the evidence).}
\end{array}
$$

**The *significance***. The *argument* *undermines* the *realism* *more* *than* the *empirical* *equivalence* (the *conceived* *rivals* are *manageable*, and the *unconceived* *alternatives* are *not*), and it *supports* the *anti*-*realism* (the *van* *Fraassen* *constructive* *empiricism*; §6.7).

**The *objections***.

**(i) The *‘*no* *alternative*’* *objection*. The *argument* *assumes* that the *alternatives* *are* *possible* (the *space* of the *theories* *is* *large*), and the *assumption* is *not* *established* (the *scientific* *theories* *may* *converge* on a *limited* *space*).

**The *reply*** (Stanford 2006, Ch. 4). The *assumption* is *justified* by the *history* (the *revolutions* *happened*, and the *alternatives* *were* *real*), and the *reply* *grounds* the *pessimism* in the *history*. The *reply* is *contested*.

**(ii) The *‘*no* *pessimism*’* *objection* (the *contemporary* *literature*; the *realist* *reply*). The *unconceived* *alternatives* *lower* the *confidence* (the *Bayesian* *insight*), and they *do* not *undermine* the *partial* *realism* (the *selective* *realism*; §6.4), and the *reply* *preserves* the *realism* at the *cost* of the *confidence*. The *reply* is *contested*.

### 3.5 The state of the underdetermination debate

**The *assessment***. The *underdetermination* is *real* (the *weak* *version* is *trivial*, and the *strong* *version* is *contested*, and the *unconceived* *alternatives* are *serious*), and the *responses* are *all* *contested*.

| The *version* | The *strength* | The *weakness* |
|---|---|---|
| **Weak** | The trivial | The no-content |
| **Strong (transient)** | The real | The future evidence |
| **Strong (permanent)** | The anti-realist | The unestablished |
| **Unconceived** | The historical | The no-alternative |

**The *most* *defensible* *position***. A *qualified* *fallibilism*: the *underdetermination* *is* *real* (the *unconceived* *alternatives* *insight*), and the *evidence* *raises* the *probability* (the *Bayesian* *insight*), and the *confidence* *must* be *calibrated* to the *uncertainty* (the *humility* *insight*; Ch. 4, §4.1), *qualified* by the *admission* that the *realism* *survives* only in a *selective*, *structural* *form* (§6.4).

---

## 4. The Theory-Ladenness of Observation

### 4.1 The thesis

**The *thesis*** (Hanson, *Patterns of Discovery*, 1958, Ch. 1; Kuhn, *Structure*, 1962, Ch. X; Feyerabend, “How to Be a Good Empiricist,” 1963). The *observation* is *not* *neutral*: the *observation* is *shaped* by the *theory* (the *concepts*, the *expectations*, the *paradigm*), and the *same* *stimulus* *yields* the *different* *observations* *under* the *different* *theories*.

**The *examples***.

| The *example* | The *stimulus* | The *theory-laden* *observation* |
|---|---|---|
| **The duck-rabbit** | The *same* *drawing* | The *duck* or the *rabbit* (the *Gestalt* *switch*) |
| **The Ptolemaic/Copernican** | The *same* *sunrise* | The *sun's* *motion* or the *earth's* *rotation* |
| **The electron** | The *same* *cloud* *chamber* *track* | The *electron* or the *artifact* (the *theory* *decides*) |
| **The wine-tasting** | The *same* *liquid* | The *complex* *chemical* *mixture* or the *fruit* *juice* |

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The observation requires the concepts (the description of the observation uses the concepts).} \\
2. & \text{The concepts are theory-laden (they are constituted by the theory).} \\
3. & \text{The observation is theory-laden (the different theories yield the different observations).} \\
\hline
4. & \therefore \text{The observations are not neutral (the theory-ladenness thesis).}
\end{array}
$$

### 4.2 The consequences

**The *consequences***.

**(i) The *no*-*neutral*-*evidence* *thesis***. The *theory* *choice* *cannot* be *determined* by the *neutral* *evidence* (the *evidence* is *theory*-*laden*, and the *choice* *presupposes* the *theory*).

**(ii) The *no*-*crucial*-*experiment* *thesis***. The *crucial* *experiment* *cannot* be *crucial* (the *experiment* *is* *interpreted* *through* the *theory*, and the *interpretation* *presupposes* the *outcome*), and the *theories* *cannot* be *decisively* *decided*.

**(iii) The *no*-*observation*-*language* *thesis***. There is *no* *neutral* *observation* *language* (the *language* *is* *theory*-*laden*, and the *translations* *are* *not* *neutral*), and the *incommensurability* *follows* (§2.2).

### 4.3 The critique

**The *critique*** (the *contemporary* *literature*; Fodor, “Observation Reconsidered,” 1984; Ch. 5, §5.2; the *predictive* *processing* *account*).

**(i) The *perceptual* *modules***. The *perception* *is* *modular* (the *informationally* *encapsulated*, the *bottom*-*up*, the *cognitively* *impenetrable*) for the *basic* *features* (the *color*, the *shape*, the *size*), and the *modules* *are* *not* *penetrated* by the *theory* (the *illusion* *persists* *despite* the *knowledge*; the *Müller*-*Lyer* *lines* *look* *unequal* *despite* the *measured* *equality*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The basic perception is modular (the encapsulated, the bottom-up).} \\
2. & \text{The modular perception is not penetrated by the theory (the illusions persist).} \\
\hline
3. & \therefore \text{The basic observation is not theory-laden (the critique).}
\end{array}
$$

**The *virtue***. The *critique* *preserves* the *neutral* *evidence* (the *basic* *perception* *is* *not* *penetrated*), and it *grounds* the *theory* *choice* in the *perceptual* *evidence*.

**The *objections***.

**(ii) The *‘*no* *modularity*’* *objection* (the *contemporary* *literature*; the *predictive* *processing* *account*). The *perception* *is* *penetrated* *at* the *higher* *levels* (the *expectations* *shape* the *percept*; the *predictive* *processing*; Ch. 5, §5.2), and the *modularity* is *local* (the *basic* *features* are *encapsulated*, and the *object* *recognition* is *penetrated*), and the *observation* *is* *theory*-*laden* *at* the *level* of the *interpretation*.

**The *reply***. The *theory*-*ladenness* is *real* *at* the *higher* *levels* (the *interpretation*, the *description*, the *judgment*), and the *basic* *perception* *provides* a *constraint* (the *stimulus* *constrains* the *interpretation*), and the *reply* *distinguishes* the *perception* from the *interpretation*. The *reply* is *defensible* (the *evidence* is *not* *exhaustively* *theory*-*laden*, and it is *not* *neutral* either).

### 4.4 The residue

**The *residue***. The *theory*-*ladenness* *is* *real* *at* the *level* of the *description* and the *interpretation* (the *observation* *report* *is* *theory*-*laden*, and the *evidence* *is* *not* *fully* *neutral*), and the *basic* *perception* *provides* a *constraint* (the *stimulus* *is* *not* *negotiable*), and the *consequence* is a *qualified* *epistemology*: the *evidence* *constrains* the *theory* (the *constraint* is *real*), and the *evidence* *does* *not* *determine* the *theory* (the *underdetermination*), and the *theory* *choice* *requires* the *judgment*.

**The *significance***. The *residue* *connects* the *theory*-*ladenness* to the *underdetermination* (§3) and to the *Bayesian* *account* (the *evidence* *is* *the* *observation* *statement*, and the *observation* *statement* *is* *theory*-*laden*, and the *likelihood* *incorporates* the *theory*).

### 4.5 The state of the theory-ladenness debate

**The *assessment***. The *theory*-*ladenness* is *real* *at* the *higher* *levels*, and the *basic* *perception* *provides* a *constraint*.

| The *position* | The *strength* | The *weakness* |
|---|---|---|
| **Strong (Kuhn, Feyerabend)** | The no-neutral-evidence | The no-constraint |
| **Modular (Fodor)** | The neutral evidence | The higher-level penetration |
| **Qualified** | The constraint + the penetration | The level distinction |

**The *most* *defensible* *position***. A *qualified* *account*: the *perception* *provides* the *bottom*-*up* *constraint* (the *modular* *insight*), and the *interpretation* *is* *theory*-*laden* (the *Kuhnian* *insight*), and the *evidence* *is* *neither* *fully* *neutral* *nor* *fully* *negotiable* (the *qualification*), *qualified* by the *admission* that the *line* between the *perception* and the *interpretation* is *contested*.

---

## 5. Scientific Realism

### 5.1 The three components

**The *thesis***. The *scientific* *realism* is a *conjunction* of *three* *claims*.

| The *component* | The *claim* | The *status* |
|---|---|---|
| **Metaphysical** | The *world* *exists* *independently* of the *theories* (the *realism*; Ch. 22, §1) | The *background* |
| **Semantic** | The *theoretical* *terms* *refer* *literally* (the *electrons* *are* *real*, and the *terms* *refer* to them) | *Contested* (the *instrumentalism* *denies* it) |
| **Epistemic** | The *theories* *are* *approximately* *true* (we have *reason* to *believe* them) | *Contested* (the *anti*-*realism* *denies* it) |

**The *significance***. The *three* *components* are *independent* (one can be a *metaphysical* *realist* and a *semantic* *anti*-*realist*; the *van* *Fraassen* *constructive* *empiricism* is *one* *combination*), and the *debate* is *about* the *components*, not the *whole*.

### 5.2 The no-miracles argument

**The *thesis*** (Putnam, *Mathematics, Matter and Method*, 1975, p. 73; Boyd, “Realism, Underdetermination, and a Causal Theory of Evidence,” 1973; Psillos, *Scientific Realism: How Science Tracks Truth*, 1999, Ch. 4). The *success* of *science* is *miraculous* unless the *theories* *are* *approximately* *true*, and the *best* *explanation* of the *success* is the *realism*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The scientific theories are empirically successful (the prediction, the intervention, the technological application).} \\
2. & \text{The success would be a miracle if the theories were not approximately true.} \\
3. & \text{We should not accept the miracles (the inference to the best explanation).} \\
\hline
4. & \therefore \text{The theories are approximately true (the realism).}
\end{array}
$$

**The *virtue***. The *argument* *grounds* the *realism* in the *explanatory* *power*, and it *explains* the *success* (the *truth* *explains* the *success*), and it *fits* the *IBE* (Ch. 10, §6).

**The *objections***.

**(i) The *‘*no* *miracle*’* *objection* (van Fraassen, *The Scientific Image*, 1980, Ch. 2; the *contemporary* *literature*). The *argument* *is* *circular* (the *IBE* *is* *justified* by the *realism*, and the *realism* *is* *justified* by the *IBE*), and the *argument* *is* *not* *decisive* (the *success* *can* be *explained* by the *empirical* *adequacy*; §6.7).

**The *reply*** (Psillos 1999, Ch. 4). The *argument* *is* *not* *circular* (the *IBE* *is* *justified* *independently* by the *practice*, and the *realism* *is* *the* *best* *explanation*), and the *reply* *grounds* the *argument* in the *practice*. The *reply* is *contested* (the *IBE* *is* *contested*; Ch. 10, §6.3).

**(ii) The *‘*no* *success*’* *objection* (the *contemporary* *literature*; Laudan 1981). The *success* is *not* *correlated* with the *truth* (the *false* *theories* *were* *successful*: the *phlogiston* *explained* the *combustion*, and the *caloric* *explained* the *heat*), and the *argument* *fails* *on* the *empirical* *premise*.

**The *reply*** (Psillos 1999, Ch. 5; the *selective* *realism*; §5.4). The *success* is *correlated* with the *partial* *truth* (the *working* *posits* *were* *approximately* *true*, and the *idle* *posits* *were* *false*), and the *reply* *grounds* the *realism* in the *selective* *truth*. The *reply* is *contested*.

### 5.3 The pessimistic meta-induction

**The *thesis*** (Laudan, “A Confutation of Convergent Realism,” 1981; the *historical* *induction*).

**The *argument***.

$$
\begin{array}{ll}
1. & \text{The history of science is a history of successful theories that were false (the phlogiston, the caloric, the luminiferous ether, the vital force, the Newtonian mechanics).} \\
2. & \text{The current theories are probably false (by the induction).} \\
\hline
3. & \therefore \text{The realism is probably false (the pessimistic meta-induction).}
\end{array}
$$

**The *consequence***. The *argument* *undermines* the *no*-*miracles* *argument* (the *success* *does* not *imply* the *truth*, because the *false* *theories* *were* *successful*), and it *supports* the *anti*-*realism* (the *van* *Fraassen* *constructive* *empiricism*; §6.7).

**The *objections***.

**(i) The *‘*base*-*rate*’* *objection* (the *contemporary* *literature*; Lewis 2001; the *selection* *bias*). The *history* is a *biased* *sample* (the *theories* *we* *remember* are the *ones* that *were* *refuted*, and the *theories* *that* *survived* are *not* *in* the *sample*), and the *induction* *is* *not* *valid* (the *base* *rate* *is* *unknown*, and the *sample* *is* *not* *random*).

**The *reply*** (Laudan 1981; Stanford 2006, Ch. 2). The *sample* *is* *the* *successful* *theories* (the *ones* that *were* *accepted*), and the *sample* *is* *representative* (the *theories* *were* *the* *best* available), and the *reply* *grounds* the *induction* in the *sample*. The *reply* is *contested*.

**(ii) The *‘*selective*’* *reply*** (§5.4). The *argument* *only* *hits* the *idle* *posits* (the *ether*, the *caloric*), and the *working* *posits* (the *electrons*, the *atoms*) *survive* the *revolutions*, and the *reply* *grounds* the *realism* in the *selective* *truth*.

**(iii) The *‘*approximate*’* *reply* (Psillos 1999, Ch. 6; the *contemporary* *literature*). The *old* *theories* *were* *approximately* *true* (the *Newtonian* *mechanics* *is* the *limit* of the *relativity*, and the *phlogiston* *is* the *approximate* *description* of the *oxidation*), and the *reply* *grounds* the *realism* in the *approximate* *truth*.

**The *objection***. The *approximate* *truth* is *not* *well*-*defined* (the *approximation* *relation* is *not* *specified*, and the *different* *respects* *yield* the *different* *approximations*), and the *reply* is *contested*.

### 5.4 Selective realism

**The *thesis*** (Psillos 1999, Ch. 5; Kitcher, “Real Realism: The Galilean Strategy,” 2001; the *contemporary* *literature*). The *realism* *should* be *selective*: the *theories* *contain* the *working* *posits* (the *entities* that *do* *the* *explanatory* *work*) and the *idle* *posits* (the *entities* that *do* *not*), and the *realism* *applies* *only* to the *working* *posits*.

**The *structure***.

$$
\text{Realism} = \text{the truth of the working posits} \ (\text{not the idle ones})
$$

**The *virtue***. The *selective* *realism* *avoids* the *pessimistic* *meta*-*induction* (the *idle* *posits* *were* *false*, and the *working* *posits* *survive*), and it *preserves* the *no*-*miracles* *argument* (the *success* is *explained* by the *working* *posits*).

**The *objections***.

**(i) The *‘*no* *division*’* *objection* (the *contemporary* *literature*; the *holistic* *objection*). The *division* *between* the *working* and the *idle* *posits* is *not* *available* *in* *advance* (the *history* *decides*, and the *decision* is *retrospective*), and the *selective* *realism* *is* *not* *a* *predictive* *position* (it *does* not *tell* us *which* *posits* *to* *believe*).

**The *reply*** (Psillos 1999, Ch. 5; the *contemporary* *literature*). The *division* is *available* (the *working* *posits* *are* the *ones* that *support* the *novel* *predictions*, and the *novel* *predictions* *are* *the* *criterion*; the *“*divide* *et* *impera”* *strategy*), and the *reply* *grounds* the *division* in the *practice*. The *reply* is *contested*.

**(ii) The *‘*no* *preservation*’* *objection*. The *working* *posits* *do* not *always* *survive* (the *Newtonian* *gravity* *was* *a* *working* *posit*, and it *did* not *survive* the *relativity*), and the *reply* *fails*.

**The *reply*** (Psillos 1999, Ch. 6; the *structural* *realism*; §5.5). The *surviving* *content* is *structural* (the *mathematical* *form* of the *Newtonian* *gravity* *survives* in the *relativity*), and the *reply* *grounds* the *selective* *realism* in the *structure*. The *reply* is *contested*.

### 5.5 Structural realism

**The *thesis*** (Worrall, “Structural Realism: The Best of Both Worlds?,” 1989; Ladyman, “What Is Structural Realism?,” 1998; French, *The Structure of the World*, 2014; Ch. 19, §6.3).

**The *two* *forms***.

| The *form* | The *claim* | The *status* |
|---|---|---|
| **Epistemic (ESR)** | We know the *structure*, not the *intrinsic* *nature* | The *Worrall* *insight* |
| **Ontic (OSR)** | The *structure* is *all* *there* *is* (no *objects*) | The *Ladyman*–*French* *insight* |

**The *argument*** (the *Worrall* *instance*). The *Fresnel* *theory* of *light* *posited* the *ether* (the *idle* *posit*, and it *was* *false*), and the *equations* (the *structure*) *survived* in the *Maxwell* *theory*, and the *survival* *shows* that the *structure* is the *preserved* *content*.

**The *virtue***. The *structural* *realism* *avoids* the *pessimistic* *meta*-*induction* (the *structure* *survives*, and the *intrinsic* *nature* *does* not), and it *preserves* the *no*-*miracles* *argument* (the *success* is *explained* by the *structural* *truth*).

**The *objections***.

**(i) The *‘*Newman*’* *objection* (Newman, “Mr. Russell’s ‘Causal Theory of Perception’,” 1928; Ketland, “Empirical Adequacy and Ramsification,” 2004; Ch. 19, §6.4). The *structure* is *specified* *only* *up* *to* *isomorphism*, and the *claim* that the *structure* is *preserved* is *trivial* (any *set* of the *right* *cardinality* *can* *realize* *any* *structure*), and the *structural* *realism* *is* *uninformative*.

**The *reply*** (the *OSR* *response*; French 2014, Ch. 4). The *OSR* *identifies* the *structure* with the *world* (there is *no* *underlying* *nature*), and the *reply* *avoids* the *Newman* *problem*. The *reply* is *contested* (the *status* of the *objects*).

**(ii) The *‘*no* *objects*’* *objection* (the *OSR* *critique*; the *contemporary* *literature*). The *structure* *without* *objects* is *not* a *structure* (the *structure* *requires* the *relata*), and the *OSR* *is* *incoherent*.

**The *reply*** (Ladyman & Ross, *Every Thing Must Go*, 2007, Ch. 3). The *form* is the *content* (the *distinction* between the *structure* and the *objects* is a *legacy* of the *substance* *ontology*), and the *reply* *grounds* the *OSR* in the *structuralism*. The *reply* is *contested*.

### 5.6 Entity realism

**The *thesis*** (Hacking, *Representing and Intervening*, 1983, Ch. 16; Cartwright, *How the Laws of Physics Lie*, 1983, Essay 6). The *realism* *should* be *about* the *entities* (the *electrons*, the *quarks*), not the *theories* (the *laws*), and the *criterion* is the *experimental* *intervention* (the *“*if* *you* *can* *spray* *them,* *then* *they* *are* *real”*).

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The experimenters manipulate the entities (the electron beams, the quarks in the scattering).} \\
2. & \text{The manipulation requires the entities to be real (the intervention is the criterion of the reality).} \\
\hline
3. & \therefore \text{The entities are real (the entity realism).}
\end{array}
$$

**The *virtue***. The *account* *grounds* the *realism* in the *experimental* *practice* (the *intervention*, the *manipulation*), and it *avoids* the *pessimistic* *meta*-*induction* (the *entities* *survive* the *theory* *changes*), and it *fits* the *interventionist* *account* of *causation* (Ch. 18, §3).

**The *objections***.

**(i) The *‘*no* *entity*’* *objection* (the *contemporary* *literature*; Morrison, “Evidence, Theory, and the Empirical,” 1990). The *manipulation* *does* not *require* the *entity* *to* *be* *real* (the *manipulation* *requires* the *phenomenon* to be *robust*, not the *entity* to *exist*), and the *account* *is* *not* *sufficient*.

**The *reply*** (Hacking 1983, Ch. 16). The *robustness* *is* the *reality* (the *entity* is *real* if it *can* be *manipulated* *reliably*), and the *reply* *grounds* the *reality* in the *practice*. The *reply* is *contested*.

**(ii) The *‘*no* *theory*’* *objection*. The *entity* *realism* *abandons* the *theoretical* *realism* (the *laws* *are* *not* *true*, and the *theories* *are* *not* *approximately* *true*), and the *abandonment* *undermines* the *explanation* (Ch. 38, §3). The *objection* is *contested*.

### 5.7 Constructive empiricism

**The *thesis*** (van Fraassen, *The Scientific Image*, 1980, Ch. 2; *Laws and Symmetry*, 1989, Ch. 1). The *science* *aims* at the *empirical* *adequacy* (the *theories* *should* *save* the *phenomena*), not the *truth*, and the *observable*/*unobservable* *distinction* *grounds* the *position*.

**The *structure***.

$$
\text{Science aims at} \ \text{empirical adequacy} \ (\text{not truth})
$$

**The *argument***.

$$
\begin{array}{ll}
1. & \text{The theories make claims about the unobservable (the electrons, the quarks).} \\
2. & \text{The claims cannot be tested directly (the unobservable is not observable).} \\
\hline
3. & \therefore \text{The belief in the theories should be the belief in the empirical adequacy (the constructive empiricism), and the unobservable claims should be accepted without belief.}
\end{array}
$$

**The *virtue***. The *account* *avoids* the *realism* *debate* (the *aim* is *empirical* *adequacy*, and the *debate* is *dissolved*), and it *fits* the *practice* (the *scientists* *use* the *theories* *regardless* of the *belief* in the *unobservable*).

**The *objections***.

**(i) The *‘*no* *observable*’* *objection* (the *contemporary* *literature*; Churchland, “The Anti-Realist Epistemology of van Fraassen’s *The Scientific Image*,” 1985). The *observable*/*unobservable* *distinction* is *not* *sharp* (the *observable* *depends* on the *technology*, and the *technology* *depends* on the *theory*), and the *distinction* *collapses*.

**The *reply*** (van Fraassen 1980, Ch. 2; 2001). The *distinction* is *anthropocentric* (the *observable* is *what* the *human* *senses* *can* *detect*, *directly* or *with* the *aids*), and the *reply* *grounds* the *distinction* in the *human* *nature*. The *reply* is *contested*.

**(ii) The *‘*no* *explanation*’* *objection* (the *contemporary* *literature*). The *constructive* *empiricism* *loses* the *explanation* (the *theories* *explain* *only* *if* they *are* *true*, and the *explanation* *requires* the *realism*), and the *loss* *is* *unacceptable* (Ch. 38, §3.2).

**The *reply*** (van Fraassen 1980, Ch. 5). The *explanation* is *pragmatic* (the *theories* *explain* *by* the *pragmatic* *role*, and the *explanation* *does* not *require* the *truth*), and the *reply* *grounds* the *explanation* in the *practice*. The *reply* is *contested*.

**(iii) The *‘*no* *belief*’* *objection*. The *constructive* *empiricism* *asks* the *scientists* to *use* the *theories* *without* *believing* them (the *“*acceptance”* *without* the *belief*), and the *request* is *psychologically* *implausible* and *epistemically* *unstable* (the *acceptance* *without* the *belief* is *not* a *genuine* *epistemic* *attitude*).

**The *reply*** (van Fraassen 1980, Ch. 1; 2001). The *acceptance* is a *pragmatic* *attitude* (the *commitment* to the *theory*, not the *belief* in the *truth*), and the *reply* *grounds* the *acceptance* in the *practice*. The *reply* is *contested*.

### 5.8 The state of the realism debate

**The *assessment***. The *realism* is *influential*, and the *anti*-*realism* (the *constructive* *empiricism*) is *serious*, and the *intermediate* *positions* (the *selective*, the *structural*, the *entity*) are *promising* and *incomplete*.

| The *position* | The *strength* | The *weakness* |
|---|---|---|
| **Realism (no-miracles)** | The success | The meta-induction |
| **Selective realism** | The working posits | The division |
| **Structural realism (ESR)** | The preservation | The Newman problem |
| **Structural realism (OSR)** | The structure | The no-objects |
| **Entity realism** | The intervention | The no-theory |
| **Constructive empiricism** | The empirical adequacy | The observable distinction |
| **Instrumentalism** | The prediction | The no-explanation |

**The *most* *defensible* *position***. A *qualified* *selective* *structural* *realism*: the *realism* *applies* to the *working* *posits* (the *selective* *insight*), and the *working* *posits* *survive* *through* the *structure* (the *structural* *insight*), and the *structure* is *real* but *not* *exhaustive* (the *anti*-*realist* *insight*), and the *confidence* is *calibrated* to the *underdetermination* (the *fallibilist* *insight*), *qualified* by the *admission* that the *selection* *criterion* and the *Newman* *problem* *remain* *unresolved*.

---

## 6. The Demarcation Problem

### 6.1 Popper and the falsifiability

**The *thesis*** (Popper, *The Logic of Scientific Discovery*, 1934/1959; *Conjectures and Refutations*, 1963, Ch. 1). The *criterion* of the *scientific* *status* is the *falsifiability* (the *testability*, the *refutability*), and the *pseudoscience* is the *unfalsifiable*.

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The scientific theories make the risky predictions (the testable consequences).} \\
2. & \text{The pseudoscientific theories are compatible with every observation (the no risky prediction).} \\
\hline
3. & \therefore \text{The criterion is the falsifiability (the Popperian criterion).}
\end{array}
$$

**The *virtue***. The *criterion* *captures* the *difference* between the *science* (the *testable*) and the *pseudoscience* (the *unfalsifiable*), and it *grounds* the *progress* in the *conjecture* and the *refutation* (the *critical* *method*).

**The *objections***.

**(i) The *‘*too* *strong*’* *objection*. The *criterion* *excludes* the *legitimate* *science* (the *Newtonian* *mechanics* *was* *falsified* by the *perihelion*, and it *was* *not* *abandoned*; the *evolutionary* *biology* *has* *few* *falsifiable* *predictions*), and the *criterion* *is* *too* *strong*.

**The *reply*** (Popper 1963; the *contemporary* *literature*). The *criterion* is *methodological* (the *appropriate* *response* to the *falsification*, not the *immediate* *abandonment*), and the *reply* *weakens* the *criterion* (§2.3; the *research* *programs*). The *reply* is *contested*.

**(ii) The *‘*too* *weak*’* *objection*. The *criterion* *admits* the *pseudoscience* (the *astrology* *can* be *formulated* *falsifiably*, and the *creationism* *makes* the *testable* *predictions*; the *contemporary* *literature*), and the *criterion* *is* *too* *weak*.

**The *reply*** (Popper 1963; the *contemporary* *literature*). The *astrology* *fails* the *methodological* *norms* (the *ad* *hocness*, the *no* *novel* *prediction*, the *no* *self*-*criticism*), and the *reply* *extends* the *criterion* to the *methodological* *norms*. The *reply* is *contested*.

### 6.2 The multi-criterion accounts

**The *thesis*** (Thagard, “Why Astrology Is a Pseudoscience,” 1978; *Computational Philosophy of Science*, 1988; the *contemporary* *literature*; Boudry, “The Nature of Pseudoscience,” 2013). The *demarcation* *requires* the *multiple* *criteria* (the *methodological*, the *sociological*, the *historical*), and the *criteria* *are* *not* *necessary* and *sufficient* (the *pseudoscience* is a *family* *resemblance*).

**The *structure*** (Thagard 1978).

| The *criterion* | The *demand* | The *astrology* |
|---|---|---|
| **Theoretical** | The theory *fits* the *background* | The *astrology* *ignores* the *physics* |
| **Community** | The community *tests* and *criticizes* | The *astrology* *avoids* the *falsification* |
| **Historical** | The theory *progresses* | The *astrology* *stagnates* *for* *centuries* |

**The *virtue***. The *account* *captures* the *complexity* of the *demarcation* (the *multiple* *dimensions*), and it *fits* the *historical* *cases* (the *astrology*, the *phrenology*), and it *avoids* the *single*-*criterion* *problems*.

**The *objections***.

**(i) The *‘*no* *sharp* *line*’* *objection*. The *criteria* *are* *gradual* (the *science* *and* the *pseudoscience* *differ* in *degree*, not in *kind*), and the *demarcation* *is* *not* *sharp* (the *contemporary* *literature*; the *‘*pseudoscience* *is* *not* *a* *natural* *kind’* *argument*).

**The *reply*** (Thagard 1978; the *contemporary* *literature*). The *gradual* *difference* is *real* (the *science* *is* *more* *testable*, *more* *critical*, *more* *progressive*), and the *reply* *grounds* the *difference* in the *dimensions*, not the *sharp* *line*. The *reply* is *defensible*.

**(ii) The *‘*no* *values*’* *objection*. The *demarcation* *encodes* the *values* (the *science* is *good*, and the *pseudoscience* is *bad*), and the *values* *are* *not* *objective*.

**The *reply***. The *values* are *epistemic* (the *testability*, the *criticism*, the *progress*), and the *epistemic* *values* *are* *defensible* (Ch. 39, §6). The *reply* is *contested*.

### 6.3 The political stakes

**The *question*.** Why does the *demarcation* matter?

**The *answers*.

| The *domain* | The *stake* | The *example* |
|---|---|---|
| **Education** | The *curriculum* (the *creationism* vs. the *evolution*) | The *Kitzmiller* *trial* (2005) |
| **Public policy** | The *credibility* (the *climate* *science* vs. the *denial*) | The *climate* *denial* *literature* |
| **Medicine** | The *efficacy* (the *homeopathy* vs. the *evidence*-*based* *medicine*) | The *regulation* of the *alternative* *medicine* |
| **Law** | The *admissibility* (the *expert* *testimony*) | The *Daubert* *standard* (1993) |
| **The media** | The *balanced* *coverage* (the *false* *balance*) | The *climate* *reporting* |

**The *significance***. The *demarcation* is *not* an *academic* *curiosity*; it is the *practical* *question* of the *epistemic* *authority* (the *science* *has* the *authority*, and the *pseudoscience* *claims* it), and the *stakes* are *high*.

### 6.4 The state of the demarcation debate

**The *assessment***. The *demarcation* is *real* (the *science* *and* the *pseudoscience* *differ* in the *methodological* and *sociological* *dimensions*), and the *line* is *gradual* (the *family* *resemblance*, not the *sharp* *criterion*).

| The *position* | The *strength* | The *weakness* |
|---|---|---|
| **Popper** | The falsifiability | The too strong / too weak |
| **Thagard** | The multi-criteria | The no-sharp-line |
| **The no-demarcation view** | The gradualism | The no-authority |

**The *most* *defensible* *position***. A *qualified* *multi*-*criteria* *account*: the *demarcation* is *gradual* (the *family* *resemblance*), and the *criteria* are *methodological* (the *testability*, the *criticism*, the *progress*) and *social* (the *community*, the *institutions*), and the *criteria* *are* *defensible* (the *epistemic* *values*), *qualified* by the *admission* that the *line* is *contested* and the *criteria* *are* *not* *sufficient*.

---

## 7. Expert Consensus and the Social Epistemology of Science

### 7.1 The consensus

**The *thesis*** (the *contemporary* *literature*; Oreskes, “The Scientific Consensus on Climate Change,” 2004; Anderson et al., “The European Association for the Study of Obesity,” 2019; the *survey* in the *Stanford* *Encyclopedia* *entry*, “Social Epistemology”).

**The *claim***. The *scientific* *consensus* is the *agreement* of the *relevant* *experts*, and the *agreement* is *evidence* for the *truth* of the *consensus* (the *Condorcet* *insight*; Ch. 11, §5.3), and the *evidence* is *defeasible* (the *consensus* *can* *be* *wrong*, and the *history* *shows* the *errors*).

**The *argument***.

$$
\begin{array}{ll}
1. & \text{The experts have the evidence and the training (the competence).} \\
2. & \text{The consensus aggregates the independent judgments (the Condorcet insight).} \\
3. & \text{The aggregation raises the probability of the truth (the statistical insight).} \\
\hline
4. & \therefore \text{The consensus is evidence for the truth (the epistemic authority of the consensus).}
\end{array}
$$

**The *virtue***. The *argument* *grounds* the *epistemic* *authority* of the *consensus*, and it *fits* the *epistemology* of *testimony* (Ch. 11, §1), and it *explains* the *rational* *deference* to the *science* (the *non*-*expert* *should* *defer*).

**The *objections***.

**(i) The *‘*no* *independence*’* *objection*. The *expert* *judgments* are *not* *independent* (the *shared* *training*, the *shared* *paradigm*, the *shared* *funding*), and the *dependence* *undermines* the *Condorcet* *aggregation* (Ch. 11, §5.3).

**The *reply*** (the *contemporary* *literature*). The *independence* is *approximate* (the *different* *research* *groups*, the *different* *methods*, the *different* *countries*), and the *reply* *grounds* the *aggregation* in the *diversity*. The *reply* is *contested*.

**(ii) The *‘*no* *competence*’* *objection*. The *consensus* *can* be *manufactured* (the *Merchants* of *Doubt*; Oreskes & Conway 2010), and the *manufactured* *consensus* *undermines* the *epistemic* *authority*.

**The *reply*** (Oreskes & Conway 2010). The *manufactured* *consensus* is *distinguishable* from the *genuine* one (the *genuine* *consensus* *emerges* from the *independent* *inquiry*, and the *manufactured* one *is* *imposed* by the *interests*), and the *reply* *grounds* the *distinction* in the *social* *conditions* (§7.3). The *reply* is *contested*.

### 7.2 The manufactured doubt

**The *thesis*** (Oreskes & Conway, *Merchants of Doubt*, 2010; Michaels, *Doubt Is Their Product*, 2008). The *industries* (the *tobacco*, the *fossil* *fuels*, the *chemical*) *manufacture* the *doubt* (they *fund* the *research* that *challenges* the *consensus*, and they *amplify* the *minority* *views*), and the *doubt* is *strategic* (it *delays* the *regulation*).

**The *structure***.

| The *strategy* | The *tactic* | The *example* |
|---|---|---|
| **Fund the dissent** | The *industry* *funds* the *minority* *research* | The *tobacco* *industry* |
| **Amplify the minority** | The *media* *presents* the *minority* as *balanced* | The *climate* *reporting* |
| **Question the consensus** | The *doubt* is *manufactured* | The *“*climate* *gate”* |
| **Delay the regulation** | The *uncertainty* is *emphasized* | The *fossil* *fuel* *lobbying* |

**The *argument*.

$$
\begin{array}{ll}
1. & \text{The manufactured doubt undermines the public trust in the science (the perceived uncertainty).} \\
2. & \text{The undermining delays the action (the regulation, the policy).} \\
3. & \text{The delay serves the interests of the funders (the industries).} \\
\hline
4. & \therefore \text{The manufactured doubt is a form of epistemic injustice (the testimonial and the hermeneutical; Ch. 11, §4).}
\end{array}
$$

**The *significance***. The *manufactured* *doubt* *connects* the *philosophy* of *science* to the *social* *epistemology* (Ch. 11, §6) and to the *ethics* (Ch. 51, §6), and it *shows* that the *consensus* is *not* *automatic* (it *requires* the *institutions* *and* the *trust*).

### 7.3 The epistemic authority of science

**The *thesis*** (the *contemporary* *literature*; Collins & Evans, *Rethinking Expertise*, 2007; Ballantyne, “Epistemic Trespassing,” 2019; the *contemporary* *literature*). The *scientific* *authority* is *legitimate* *relative* to the *competence* (the *expertise*), and the *non*-*expert* *should* *defer* *within* the *domain* of the *competence*, and the *deference* is *not* *unconditional* (the *expert* *can* *be* *wrong*, and the *layperson* *can* *have* the *relevant* *experience*; the *epistemic* *injustice*).

**The *structure***.

| The *kind* of *expertise* | The *definition* | The *example* |
|---|---|---|
| **Contributory** | The *expertise* *within* the *domain* | The *climate* *modeler* |
| **Interactional** | The *expertise* *about* the *experts* (the *meta*-*expertise*) | The *science* *journalist* |
| **Lay** | The *local* *experience* | The *farmer* *who* *observes* the *drought* |

**The *significance***. The *authority* *requires* the *trust* (Ch. 11, §2), and the *trust* *requires* the *calibration* (the *credibility* *tracks* the *competence*), and the *calibration* *requires* the *social* *conditions* (the *transparency*, the *accountability*; Ch. 13, §5.3).

### 7.4 The state of the social epistemology of science

**The *assessment***. The *consensus* is *evidence* (the *Condorcet* *insight*), and the *consensus* *can* be *manufactured* (the *social* *critique*), and the *authority* *requires* the *trust* and the *conditions*.

| The *position* | The *strength* | The *weakness* |
|---|---|---|
| **The consensus** | The aggregation | The no-independence |
| **The manufactured doubt** | The social critique | The no-distinction |
| **The expertise** | The competence | The no-access |
| **The epistemic injustice** | The lay experience | The no-authority |

**The *most* *defensible* *position***. A *qualified* *social* *account*: the *consensus* is *evidence* (the *aggregation*), and the *evidence* *requires* the *conditions* (the *independence*, the *criticism*, the *transparency*; Longino; Ch. 39, §6.3), and the *conditions* *are* *not* *automatic* (the *manufactured* *doubt*, the *capture*), and the *authority* *requires* the *calibration* (the *trust* *tracks* the *competence*), *qualified* by the *admission* that the *conditions* *are* *contested* and the *manufactured* *doubt* is *real*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **The confirmation is real, and the Bayesian account is the most developed.** The *ravens* are *resolved* (the *tiny* *confirmation*), and the *grue* is *relocated* (the *priors*), and the *old* *evidence* and the *catch*-*all* are *contested*.
- **The historicist challenge is real.** The *theory* *choice* *involves* the *paradigm* and the *community*, and the *values* are *shared*, and the *choice* *requires* the *judgment*.
- **The underdetermination is real.** The *unconceived* *alternatives* (Stanford) are *serious*, and the *realism* *requires* the *selective* *form*.
- **The theory-ladenness is real at the higher levels.** The *basic* *perception* *provides* a *constraint*, and the *higher* *interpretation* is *theory*-*laden*.
- **The realism is defensible in a selective, structural form.** The *no*-*miracles* *argument* and the *pessimistic* *meta*-*induction* are *both* *serious*, and the *selective* *structural* *realism* is the *most* *promising* *synthesis*.
- **The demarcation is real but gradual.** The *multi*-*criteria* *account* (Thagard) is the *most* *defensible*, and the *line* is *contested*.
- **The consensus is evidence, and it requires the social conditions.** The *manufactured* *doubt* is *real*, and the *authority* *requires* the *calibration*.

### 8.2 What is open

- **The *nature* of *confirmation*.** The *Bayesian* *account* and its *problems* (the *priors*, the *old* *evidence*, the *catch*-*all*).
- **The *theory* *choice*.** The *rationality* of the *choice*, and the *role* of the *values*.
- **The *underdetermination*.** The *unconceived* *alternatives*, and the *confidence* in the *theories*.
- **The *realism*.** The *selective*/*structural* *synthesis*, and the *Newman* *problem*.
- **The *demarcation*.** The *multi*-*criteria* *account*, and the *line*.
- **The *social* *epistemology*.** The *consensus*, the *manufactured* *doubt*, and the *expertise*.

### 8.3 The methodological lesson

The chapter is a case study in the method of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *distinction* between the *confirmation*, the *theory* *choice*, and the *realism*.
- **Thought experiments** (§2 of Ch. 3) — the *ravens*, the *grue*, the *unconceived* *alternatives*, the *pessimistic* *meta*-*induction* — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *Bayesian* *framework*, the *dynamic* *epistemic* *logic*, the *structural* *equations* — is *essential* for the *field*.
- **Reflective equilibrium** (§4 of Ch. 3) is the *method* by which the *intuitions* and the *theories* are *adjusted*.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to *hold* the *question* *open*.

The honest verdict: the epistemology of science is a field in transition. The classical positions are untenable in their pure forms; the contemporary positions are promising but incomplete; the debate is unresolved. The unresolved character is instructive: it shows what philosophical progress looks like — not a settled answer, but a sharper understanding of what the question is.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Naive confirmation** | Instances confirm | Simple | The ravens |
| **Bayesian** | The credence raises | The formal; the practice | The priors; the catch-all |
| **Logical empiricist** | The rational inference | The norms | The practice |
| **Kuhn** | The paradigms | The history | The rationality |
| **Lakatos** | The research programs | The progressiveness | The retrospectivity |
| **Feyerabend** | The anarchism | The practice | The no-science |
| **Laudan** | The problem-solving | The real time | The no-truth |
| **Strong underdetermination** | The empirical equivalence | The anti-realism | The no-equivalence |
| **Unconceived alternatives** | The history | The pessimism | The no-alternative |
| **Theory-ladenness** | The no-neutral-evidence | The interpretation | The basic perception |
| **Realism (no-miracles)** | The success | The explanation | The meta-induction |
| **Selective realism** | The working posits | The preservation | The division |
| **Structural realism** | The structure | The preservation | The Newman |
| **Constructive empiricism** | The empirical adequacy | The anti-realism | The observable |
| **Popper** | The falsifiability | The practice | The too strong / weak |
| **Thagard** | The multi-criteria | The complexity | The no-line |
| **The consensus** | The aggregation | The authority | The independence |
| **The manufactured doubt** | The social critique | The injustice | The no-distinction |

The table is a map, not a verdict. The reader who wants to choose a position must decide which cost is acceptable — and the decision is a philosophical argument.

---

## Optional threads

Cross-cutting material, for the reader who wants to go deeper.

**1. The *Bayesian* *networks* and the *causal* *discovery*.** The *causal* *Bayesian* *networks* (Ch. 18, §3.2) *provide* a *formal* *framework* for the *confirmation* and the *theory* *choice*, and the *framework* *connects* the *epistemology* of *science* to the *formal* *epistemology* (Ch. 10, §4) and to the *AI* (Ch. 51, §3). The *connection* is *promising* and *underdeveloped*.

**2. The *social* *epistemology* of the *science*.** The *consensus* (§7) *connects* the *epistemology* of *science* to the *epistemic* *injustice* (Ch. 11, §4) and to the *social* *ontology* (Ch. 25, §7), and the *manufactured* *doubt* (Oreskes & Conway) *connects* the *science* to the *political* *epistemology*. The *connection* is *urgent*.

**3. The *AI* and the *scientific* *method*.** The *machine* *learning* *models* *produce* the *predictions* and the *explanations* (the *XAI*; Ch. 38, §5), and the *epistemic* *status* of the *models* (the *confirmation*, the *realism*) is *contested* (Ch. 29, §3). The *connection* is *new* and *urgent*.

**4. Non-Western *epistemologies* of *science*.** The *Buddhist* *tradition* *developed* a *theory* of *inference* (*anumāna*) and of *testimony* (*śabda*) that *anticipates* the *confirmation* and the *theory* *choice*, and the *Nyāya* *tradition* *developed* a *sophisticated* *theory* of *evidence* and *debate*. The *traditions* are *systematic* *alternatives* (Matilal 1986, 1998; Ganeri 2001; the *essays* in *The Oxford Handbook of Indian Philosophy*, 2017).

**5. The *ethics* of the *confirmation*.** The *confirmation* *bias*, the *manufactured* *doubt*, and the *over*-*confidence* are *ethical* as well as *epistemic* *vices*, and the *ethics* of the *confirmation* *connects* the *epistemology* of *science* to the *ethics* of the *belief* (Ch. 4, §4.5) and to the *virtue* *epistemology* (Ch. 8, §7). The *connection* is *underdeveloped*.

---

## Summary

- **The *naive* *confirmation*** is *refuted* by the *ravens* (the *white* *shoe* *confirms*), and the *Bayesian* *account* *resolves* the *ravens* (the *confirmation* is *tiny*), and the *grue* *relocates* the *problem* to the *priors*, and the *old* *evidence* and the *catch*-*all* are *unresolved*.
- **The *historicist* *challenge*** (Kuhn, Lakatos, Feyerabend, Laudan) *shows* that the *theory* *choice* *involves* the *paradigm*, the *tradition*, the *values*, and the *rhetoric*, and the *rationality* of the *choice* is *relative* to the *shared* *values*.
- **The *underdetermination*** is *real* (the *strong* *version* is *contested*, and the *unconceived* *alternatives* are *serious*), and the *response* is the *fallibilism* (the *confidence* *calibrated* to the *uncertainty*).
- **The *theory-ladenness*** is *real* *at* the *higher* *levels*, and the *basic* *perception* *provides* a *constraint*, and the *evidence* is *neither* *neutral* *nor* *negotiable*.
- **The *realism*** is *defensible* in a *selective* *structural* *form*: the *working* *posits* *survive* (the *selective* *insight*), and the *structure* is *preserved* (the *structural* *insight*), and the *confidence* is *calibrated* (the *fallibilist* *insight*).
- **The *demarcation*** is *real* but *gradual* (the *multi*-*criteria* *account*), and the *line* is *contested*, and the *stakes* are *political*.
- **The *consensus*** is *evidence* (the *aggregation*), and it *requires* the *social* *conditions* (the *independence*, the *criticism*, the *transparency*), and the *manufactured* *doubt* is *real*.
- **The *most* *defensible* *position*** is a *qualified* *selective* *structural* *realism* *combined* with a *Bayesian* *fallibilism* and a *social* *epistemology*: the *realism* *applies* to the *working* *posits* (the *selective* *insight*), the *structure* is *preserved* (the *structural* *insight*), the *confidence* is *calibrated* (the *fallibilist* *insight*), and the *consensus* is *grounded* in the *social* *conditions* (the *social* *insight*), *qualified* by the *admission* that the *selection* *criterion*, the *Newman* *problem*, and the *manufactured* *doubt* *remain* *unresolved*.

---

## Study Questions

1. State the *ravens* *paradox*. Is the *Bayesian* *resolution* *adequate*?
2. State the *grue* *problem*. Does the *Bayesian* *account* *solve* it?
3. State the *old* *evidence* *problem*. Which *response* is *most* *defensible*?
4. State the *catch*-*all* *problem*. Is the *problem* *decisive* against the *Bayesian* *account*?
5. State the *Kuhnian* *challenge*. Is the *theory* *choice* *rational*?
6. State the *Lakatosian* *research* *programs*. Is the *progressiveness* *criterion* *defensible*?
7. State the *Feyerabendian* *anarchism*. Is the *position* *defensible*?
8. State the *Laudan* *problem*-*solving* *account*. Is the *account* *defensible*?
9. State the *Duhem*–*Quine* *thesis*. Is it *decisive* against the *naive* *falsificationism*?
10. State the *strong* *underdetermination*. Is the *thesis* *established*?
11. State *Stanford's* *unconceived* *alternatives*. Is the *argument* *decisive* against the *realism*?
12. State the *theory*-*ladenness* *thesis*. Is the *basic* *perception* *neutral*?
13. State the *no*-*miracles* *argument*. Is it *circular*?
14. State the *pessimistic* *meta*-*induction*. Is the *argument* *sound*?
15. State the *selective* *realism*. Is the *division* *available* *in* *advance*?
16. State the *structural* *realism* (the *ESR* and the *OSR*). Is the *Newman* *problem* *decisive*?
17. State the *entity* *realism*. Is the *intervention* *criterion* *defensible*?
18. State the *constructive* *empiricism*. Is the *observable*/*unobservable* *distinction* *defensible*?
19. State the *demarcation* *problem*. Is the *multi*-*criteria* *account* *defensible*?
20. Is the *science* *value*-*free*? What does the *answer* *imply* for the *demarcation* (Ch. 39, §6)?
21. State the *consensus* *argument*. Is the *epistemic* *authority* of the *consensus* *defensible*?
22. State the *manufactured* *doubt*. What does it *show* about the *epistemic* *injustice* (Ch. 11, §4)?
23. Is the *realism* *defensible*? What does the *answer* *imply* for the *philosophy* of *mind* (Ch. 23)?
24. Is the *underdetermination* *decisive* against the *realism*? What does the *answer* *imply* for the *confidence* in the *science*?
25. "The success of science would be a miracle if the theories were not approximately true." Assess.

---

## Further Reading

- **Primary**: Carl Hempel, “Studies in the Logic of Confirmation” (1945), in *Mind* 54, and *Aspects of Scientific Explanation* (1965), Ch. 1; Nelson Goodman, *Fact, Fiction, and Forecast* (1955), Ch. 3; Thomas Kuhn, *The Structure of Scientific Revolutions* (1962; 4th ed., 2012); Imre Lakatos, “Falsification and the Methodology of Scientific Research Programmes” (1970), in *Philosophical Papers*, Vol. I (1978); Larry Laudan, “A Confutation of Convergent Realism” (1981), in *Philosophy of Science* 48; Bas van Fraassen, *The Scientific Image* (1980); Hilary Putnam, *Mathematics, Matter and Method* (1975), p. 73; John Worrall, “Structural Realism: The Best of Both Worlds?” (1989), in *Dialectica* 43.
- **On confirmation**: Hempel (1945, 1965); Goodman (1955); the *survey* in the *Stanford Encyclopedia* entry, “Confirmation” (the entry by the contemporary literature); the *essays* in *The Oxford Handbook of Philosophy of Science* (ed. Humphreys, 2016), Part II.
- **On the Bayesian account**: Colin Howson and Peter Urbach, *Scientific Reasoning: The Bayesian Approach* (3rd ed., 2006); John Earman, *Bayes or Bust?* (1992); the *old* *evidence* *problem* in Daniel Garber, “Old Evidence and Logical Omniscience in Bayesian Confirmation Theory” (1983), in *Testing Scientific Theories* (ed. Earman, 1983); the *catch*-*all* *problem* in the *contemporary* *literature* (Shimony; the *survey* in the *Stanford Encyclopedia* entry, “Bayesian Epistemology”).
- **On the theory choice**: Kuhn (1962); Lakatos (1970); Paul Feyerabend, *Against Method* (1975), and *Science in a Free Society* (1978); Larry Laudan, *Progress and Its Problems* (1977); the *survey* in the *Stanford Encyclopedia* entries, “Thomas Kuhn” (Bird), “Historicist Theories of Scientific Rationality” (the entry by the contemporary literature).
- **On the underdetermination**: Pierre Duhem, *The Aim and Structure of Physical Theory* (1906); W. V. O. Quine, “Two Dogmas of Empiricism” (1951), in *From a Logical Point of View* (1953); Larry Laudan and Jarrett Leplin, “Empirical Equivalence and Underdetermination” (1991), in *Journal of Philosophy* 88; Kyle Stanford, *Exceeding Our Grasp* (2006); the *survey* in the *Stanford Encyclopedia* entry, “Underdetermination of Scientific Theory” (the entry by the contemporary literature).
- **On the theory-ladenness**: Norwood Russell Hanson, *Patterns of Discovery* (1958); Kuhn (1962), Ch. X; Jerry Fodor, “Observation Reconsidered” (1984), in *Philosophy of Science* 51; the *survey* in the *Stanford Encyclopedia* entry, “Theory and Observation in Science” (the entry by the contemporary literature).
- **On the realism**: Putnam (1975); van Fraassen (1980); Laudan (1981); Stathis Psillos, *Scientific Realism: How Science Tracks Truth* (1999); Jarrett Leplin (ed.), *Scientific Realism* (1984); the *survey* in the *Stanford Encyclopedia* entry, “Scientific Realism” (Chakravartty).
- **On the structural realism**: Worrall (1989); James Ladyman, “What Is Structural Realism?” (1998), in *Studies in History and Philosophy of Science* 29; Steven French, *The Structure of the World* (2014); the *Newman* *problem* in John Ketland, “Empirical Adequacy and Ramsification” (2004), in *The British Journal for the Philosophy of Science* 55; the *survey* in the *Stanford Encyclopedia* entry, “Structural Realism” (Ladyman).
- **On the entity realism**: Ian Hacking, *Representing and Intervening* (1983), Ch. 16; Nancy Cartwright, *How the Laws of Physics Lie* (1983), Essay 6; the *critique* in the *contemporary* *literature*.
- **On the demarcation**: Karl Popper, *Conjectures and Refutations* (1963), Ch. 1; Paul Thagard, “Why Astrology Is a Pseudoscience” (1978), in *PSA 1978*; the *contemporary* *literature* in *The Philosophy of Pseudoscience* (ed. Pigliucci and Boudry, 2013); the *survey* in the *Stanford Encyclopedia* entry, “Science and Pseudo-Science” (Hansson).
- **On the social epistemology of science**: Helen Longino, *Science as Social Knowledge* (1990), and *The Fate of Knowledge* (2002); Naomi Oreskes and Erik Conway, *Merchants of Doubt* (2010); the *contemporary* *literature* in *The Routledge Handbook of Social Epistemology* (ed. the contemporary literature); the *survey* in the *Stanford Encyclopedia* entry, “Social Epistemology” (Goldman and Blanchard).

---

> *A closing note.* This chapter has followed the *epistemology* of *science* — the *confirmation*, the *theory* *choice*, the *underdetermination*, the *theory*-*ladenness*, the *realism*, the *demarcation*, and the *social* *epistemology* — and it has arrived at a *conclusion* that is less a *theory* than a *diagnosis*: the *science* is *justified* not by a *single* *criterion* but by the *convergence* of the *criteria*, and the *convergence* is *strong* *enough* to *ground* a *qualified* *realism* — *selective*, *structural*, *probabilistic*, and *social* — and the *qualification* is *not* a *weakness* but the *condition* of the *scientific* *authority*.

> *And a bridge.* The next chapter turns to *space*, *time*, and the *metaphysics* of *physics* — the *domain* in which the *confirmation* and the *theory* *choice* are *most* *rigorous*, and the *realism* is *most* *contested* (the *underdetermination* of the *quantum* *interpretations*; Ch. 41, §5). If the *theories* are *underdetermined* by the *evidence* (§3), the *quantum* *mechanics* is the *paradigm* *case* (the *many* *interpretations*, the *same* *predictions*), and the *next* *chapter* *examines* the *metaphysics* of *physics*, and it *asks* the *question* that the *epistemology* of *science* *presupposes*: *what* *is* the *world* *like*, *according* to the *best* *theories*?
