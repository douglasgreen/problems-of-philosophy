# Appendix A — A Logic and Probability Primer

> “Logic must take care of itself.”
> — Ludwig Wittgenstein, *Tractatus Logico-Philosophicus* (1921), 5.473

> “Logic is the hygiene the mathematician practises to keep his ideas healthy and strong.”
> — Hermann Weyl, “The Mathematical Way of Thinking” (1940)

> “Probability is the very guide of life.”
> — Joseph Butler, *The Analogy of Religion* (1736), Introduction

> “The degree of a belief is … measurable by the odds at which we would bet on it.”
> — after Frank Ramsey, “Truth and Probability” (1926)

---

## §1 What This Appendix Is For

This appendix is a **translation manual**, not a logic course. It exists because the chapters of this book use two formal engines — the predicate calculus and the probability calculus — and because the philosophical literature you will read next uses three more — modal logic, the Bayesian apparatus, and elementary decision theory. You can read this book without this appendix. You cannot audit its arguments without the first two, and you cannot read the journals without the other three.

Two warnings, both from the book’s own methodology.

**First, formalization is an instrument, not a credential.** Writing an argument in symbols does not make it good; it makes it *visible*. The most common failure of formal work in philosophy is not a mistake in the algebra but a mistake in the translation — the symbolization of a claim that the author did not mean. Chapter 35, §6 catalogues the abuses; the first is the substitution of a tractable formula for a difficult thought.

**Second, the formalism cuts both ways.** The chapters on logic and mathematics (Chs. 35–36, 43) argue that logic is *revisable* and that its epistemology is contested. So this appendix should be read as a set of *working conventions*, not as a metaphysically privileged notation. Where the conventions are controversial — the material conditional, the classical treatment of vagueness, the standard semantics for counterfactuals — the text says so and points to the chapter where the controversy is aired.

**A note on notation.** Throughout, Roman letters $p, q, r, \dots$ are **sentence letters** (atoms of the object language), and Greek letters $\phi, \psi, \chi, \dots$ are **metavariables** ranging over arbitrary formulas. A formula in a schema is a *template*: replace the metavariables uniformly and you get an instance. The distinction matters when a schema is quantified, as in “every instance of $\phi \to \phi$ is a theorem.”

---

## §2 Propositional Logic

### 2.1 Syntax

The **alphabet** has sentence letters $p, q, r, \dots$ (infinitely many), the **connectives**

$$
\neg \quad \wedge \quad \vee \quad \to \quad \leftrightarrow
$$

and the parentheses. The **well-formed formulas** (wffs) are defined recursively:

$$
\begin{array}{ll}
\text{(i)} & \text{Every sentence letter is a wff.} \\
\text{(ii)} & \text{If } \phi \text{ is a wff, so is } \neg\phi. \\
\text{(iii)} & \text{If } \phi, \psi \text{ are wffs, so are } (\phi \wedge \psi), (\phi \vee \psi), (\phi \to \psi), (\phi \leftrightarrow \psi). \\
\text{(iv)} & \text{Nothing else is a wff.}
\end{array}
$$

**Conventions for reading.** Drop outermost parentheses; rank the connectives $\neg > \wedge > \vee > \to > \leftrightarrow$; associate $\to$ to the right, so $p \to q \to r$ means $p \to (q \to r)$. Thus

$$
\neg p \vee q \to r \quad \text{means} \quad ((\neg p \vee q) \to r).
$$

**Scope.** The *scope* of a connective is the smallest wff it governs. Scope is the source of most translation errors in philosophy; §3.4 returns to it.

### 2.2 Semantics and truth tables

A **valuation** is a function $v$ from sentence letters to $\{T, F\}$, extended to all wffs by the clauses

$$
\begin{array}{c|c}
\phi & \neg\phi \\ \hline
T & F \\
F & T
\end{array}
\qquad
\begin{array}{cc|c|c|c|c}
\phi & \psi & \phi \wedge \psi & \phi \vee \psi & \phi \to \psi & \phi \leftrightarrow \psi \\ \hline
T & T & T & T & T & T \\
T & F & F & T & F & F \\
F & T & F & T & T & F \\
F & F & F & F & T & T
\end{array}
$$

Four definitions follow, and they are the ones the book uses throughout.

| The *notion* | The *definition* | The *chapter* |
|---|---|---|
| **Tautology** | True on every valuation | Ch. 35, §2 |
| **Contradiction** | False on every valuation | – |
| **Contingent** | True on some, false on others | – |
| **Entailment** $\Gamma \models \phi$ | Every valuation making all of $\Gamma$ true makes $\phi$ true | Ch. 2, §2 |
| **Equivalence** $\phi \equiv \psi$ | $\models \phi \leftrightarrow \psi$ | – |
| **Consistency** | Some valuation makes all of $\Gamma$ true | Ch. 2, §2 |

**Two equivalences worth memorising.** *De Morgan*:

$$
\neg(\phi \wedge \psi) \equiv \neg\phi \vee \neg\psi, \qquad \neg(\phi \vee \psi) \equiv \neg\phi \wedge \neg\psi
$$

and *exportation*, which is the formal core of the conditional:

$$
(\phi \wedge \psi) \to \chi \ \equiv \ \phi \to (\psi \to \chi)
$$

### 2.3 Validity, entailment, equivalence, consistency

The four notions are interdefinable, and it is worth seeing the circle because it explains why proofs in this book can move from any one to any other:

$$
\Gamma \models \phi \iff \Gamma \cup \{\neg\phi\} \text{ is inconsistent} \iff \models (\textstyle\bigwedge\Gamma) \to \phi
$$

The first equivalence is the basis of **reductio ad absurdum**; the second is the basis of **conditional proof**. Both are used constantly in the chapters on scepticism (Ch. 6), on the criterion (Ch. 13), and on religion (Ch. 50).

**Compactness** (propositional and first-order): if every finite subset of $\Gamma$ is consistent, $\Gamma$ is consistent. This is the theorem behind the Löwenheim–Skolem results (§3.6) and behind some of the puzzles about infinite belief sets.

### 2.4 Natural deduction: a compact kit

Truth tables decide validity; they do not show *why* a conclusion follows. For that, a natural-deduction system is more useful, and the versions used in this book are standard. The rules:

| The *rule* | The *from* | The *infer* | The *name* |
|---|---|---|---|
| $\wedge$I | $\phi$, $\psi$ | $\phi \wedge \psi$ | conjunction introduction |
| $\wedge$E | $\phi \wedge \psi$ | $\phi$ (or $\psi$) | simplification |
| $\vee$I | $\phi$ | $\phi \vee \psi$ | addition |
| $\vee$E | $\phi \vee \psi$; $\phi \vdash \chi$; $\psi \vdash \chi$ | $\chi$ | dilemma |
| $\to$E | $\phi \to \psi$, $\phi$ | $\psi$ | *modus ponens* |
| $\to$I | $\phi \vdash \psi$ | $\phi \to \psi$ | conditional proof |
| $\neg$E | $\phi$, $\neg\phi$ | $\bot$ | contradiction |
| RAA | $\neg\phi \vdash \bot$ | $\phi$ | *reductio* (classical) |
| $\bot$E | $\bot$ | $\phi$ | *ex falso* |
| $\leftrightarrow$I | $\phi \vdash \psi$; $\psi \vdash \phi$ | $\phi \leftrightarrow \psi$ | biconditional proof |
| $\leftrightarrow$E | $\phi \leftrightarrow \psi$, $\phi$ | $\psi$ | modus ponens for $\equiv$ |

**A worked derivation** (*modus tollens*):

$$
\begin{array}{lll}
1. & p \to q & \text{premise} \\
2. & \neg q & \text{premise} \\
3. & \quad p & \text{assumption for RAA} \\
4. & \quad q & \text{1, 3 by } \to\text{E} \\
5. & \quad \bot & \text{2, 4 by } \neg\text{E} \\
6. & \neg p & \text{3–5 by RAA}
\end{array}
$$

**A second** (*disjunctive syllogism*):

$$
\begin{array}{lll}
1. & p \vee q & \text{premise} \\
2. & \neg p & \text{premise} \\
3. & \quad p & \text{assumption} \\
4. & \quad \bot & \text{2, 3 by } \neg\text{E} \\
5. & \quad q & \text{4 by } \bot\text{E} \\
6. & \quad q & \text{assumption (second case)} \\
7. & q & \text{1, 3–5, 6–6 by } \vee\text{E}
\end{array}
$$

**The metatheorems you should know exist** (Ch. 35, §1–2): the system is **sound** (whatever it proves is valid) and **complete** (whatever is valid it proves) for propositional and first-order logic without identity. With identity, soundness and completeness survive; *decidability* does not (§3.6).

### 2.5 The material conditional

The truth table gives $\phi \to \psi$ the value $F$ only when $\phi$ is true and $\psi$ false. This is the **material conditional**, and it is the source of three famous discomforts.

| The *discomfort* | The *instance* | The *diagnosis* |
|---|---|---|
| **Vacuous truth** | “If $2+2=5$, then Paris is in France” is true | The antecedent is false; the conditional inherits $T$ |
| **Paradoxes of implication** | $p \to (q \to p)$ is a tautology | Any true proposition follows from any proposition |
| **The conditional's tautology** | $(p \to q) \vee (q \to p)$ is a tautology | Of any two indicative conditionals, one is true |

The moral is not that the material conditional is wrong; it is that *it formalises one sense of “if”* — the sense in which “if $\phi$ then $\psi$” is refuted only by $\phi$-true-$\psi$-false. Chapter 37 is about the other senses: indicative conditionals, counterfactuals, causal conditionals, and the semantics of “because.” Chapter 35, §5 discusses whether a **relevant** logic (which rejects $p \to (q \to p)$) is the right response. For most philosophical purposes the material conditional is what you want; the skill is knowing when it is not.

### 2.6 Valid forms and invalid forms

The table is not exhaustive, but it covers what appears in this book.

| The *form* | The *schema* | The *status* | The *name* |
|---|---|---|---|
| *Modus ponens* | $\phi \to \psi; \ \phi \ \therefore \ \psi$ | Valid | – |
| *Modus tollens* | $\phi \to \psi; \ \neg\psi \ \therefore \ \neg\phi$ | Valid | – |
| Disjunctive syllogism | $\phi \vee \psi; \ \neg\phi \ \therefore \ \psi$ | Valid | – |
| Hypothetical syllogism | $\phi \to \psi; \ \psi \to \chi \ \therefore \ \phi \to \chi$ | Valid | – |
| Constructive dilemma | $\phi \vee \psi; \ \phi \to \chi; \ \psi \to \theta \ \therefore \ \chi \vee \theta$ | Valid | – |
| Affirming the consequent | $\phi \to \psi; \ \psi \ \therefore \ \phi$ | **Invalid** | The classic fallacy |
| Denying the antecedent | $\phi \to \psi; \ \neg\phi \ \therefore \ \neg\psi$ | **Invalid** | – |
| Affirming a disjunct | $\phi \vee \psi; \ \phi \ \therefore \ \neg\psi$ | **Invalid** | – |
| Quantifier shift | $\forall x \exists y Rxy \ \therefore \ \exists y \forall x Rxy$ | **Invalid** | §3.4 |

**The counterexample method.** To show a form invalid, describe a possible situation in which the premises are true and the conclusion false. To show it valid, you need a proof or a truth table; a single confirming case proves nothing. This asymmetry — *one counterexample refutes a universal claim; a thousand examples do not establish it* — is the engine of Chapters 2 and 45.

---

## §3 Predicate Logic

### 3.1 Syntax

Add to the alphabet: **variables** $x, y, z, \dots$ (infinitely many), **individual constants** $a, b, c, \dots$, **predicate letters** $F, G, H, \dots$ (each with an arity), the **quantifiers** $\forall$ and $\exists$, and optionally **function symbols** $f, g, \dots$.

| The *category* | The *examples* | The *role* |
|---|---|---|
| **Terms** | $a$, $x$, $f(a)$ | Name objects |
| **Atomic formulas** | $Fa$, $Rxy$, $x = y$ | Say of objects |
| **Formulas** | $\forall x(Fx \to Gx)$, $\exists y \neg Rya$ | Quantify |
| **Sentences** | Formulas with no free variables | Have truth values in a model |

**Free and bound.** An occurrence of $x$ is *bound* if it lies within the scope of a quantifier $\forall x$ or $\exists x$; otherwise *free*. A *sentence* has no free variables. Substitution of a term $t$ for $x$ in $\phi$ requires that $t$ be **substitutable** — that no variable in $t$ become bound by a quantifier in $\phi$. The failure of this condition is the formal counterpart of the “capture” errors that produce fallacies in ordinary reasoning.

### 3.2 Semantics and models

A **model** for a first-order language is a pair $\mathcal{M} = \langle D, I \rangle$: a non-empty **domain** $D$ and an **interpretation** $I$ assigning to each constant an element of $D$, to each $n$-ary predicate a subset of $D^n$, and to each function symbol a function $D^n \to D$. A **variable assignment** $g$ maps variables to elements of $D$; satisfaction $\mathcal{M} \models \phi[g]$ is defined recursively, with

$$
\mathcal{M} \models \forall x \phi[g] \iff \text{for every } d \in D, \ \mathcal{M} \models \phi[g(x \mapsto d)]
$$

$$
\mathcal{M} \models \exists x \phi[g] \iff \text{for some } d \in D, \ \mathcal{M} \models \phi[g(x \mapsto d)]
$$

**Truth in a model** is satisfaction by every assignment. **Logical truth** is truth in every model; **validity** is truth in every model on every assignment; **entailment** $\Gamma \models \phi$ is: every model in which all of $\Gamma$ are true makes $\phi$ true.

### 3.3 Identity and definite descriptions

Identity is a distinguished binary predicate with the axioms of reflexivity and the **substitutivity of identicals** (Leibniz’s law):

$$
\forall x (x = x), \qquad \forall x \forall y \big( x = y \to (\phi(x) \to \phi(y)) \big)
$$

The quantifier “exactly one” is the workhorse:

$$
\exists x \Big( Fx \wedge \forall y (Fy \to y = x) \Big)
$$

and “at least two” is

$$
\exists x \exists y (Fx \wedge Fy \wedge x \neq y)
$$

**Russell’s analysis of definite descriptions** (Ch. 12, §2) treats “the $F$ is $G$” as

$$
\exists x \Big( Fx \wedge \forall y (Fy \to y = x) \wedge Gx \Big)
$$

Three consequences follow, and they are why the analysis is still taught. (i) “The present King of France is bald” is *false*, not meaningless, because the existential clause fails. (ii) “The present King of France is *not* bald” is **ambiguous** between the wide-scope reading $\neg\exists x(\dots)$ — true — and the narrow-scope reading $\exists x(Kx \wedge \dots \wedge \neg Bx)$ — false. (iii) Negative existentials (“The golden mountain does not exist”) become tractable: the sentence denies that the existential clause is satisfied, rather than predicating non-existence of a non-existent object.

**The scope warning.** The difference between wide and narrow scope is the difference between

$$
\neg\forall x \phi \quad \text{and} \quad \forall x \neg\phi
$$

which are not equivalent, and between

$$
\forall x (Fx \to Gx) \quad \text{and} \quad \forall x Fx \to \forall x Gx
$$

which are not equivalent either (the second is weaker; find the model in Exercise 12). Many philosophical disputes — about omnipotence, about omniscience and free will, about “everyone has a mother,” about legal liability — are disputes about scope in disguise.

### 3.4 Quantifier scope

**The De Morgan laws for quantifiers** (given a non-empty domain):

$$
\neg\forall x \phi \equiv \exists x \neg\phi, \qquad \neg\exists x \phi \equiv \forall x \neg\phi
$$

**The quantifier-shift fallacy.** From

$$
\forall x \exists y \, Rxy \quad (\text{everyone loves someone})
$$

one may *not* infer

$$
\exists y \forall x \, Rxy \quad (\text{someone is loved by everyone})
$$

The first says that each person has a lover; the second says there is a person whom everyone loves. The difference is a difference in *order of quantifiers*, and it is the formal core of a family of fallacies in metaphysics and theology: from “every contingent thing has a cause” to “there is a cause of every contingent thing”; from “every evil has a purpose” to “there is a purpose for every evil”; from “every event has an explanation” to “there is an explanation of every event.” The last is the step the cosmological argument must not make without argument (Ch. 50, §2.2).

### 3.5 Translation traps

The four English words that cause the most formalization errors are *all*, *some*, *only*, and *unless*.

| The *English* | The *formula* | The *trap* |
|---|---|---|
| All $F$s are $G$s | $\forall x(Fx \to Gx)$ | Not $\forall x(Fx \wedge Gx)$ — that says everything is $F$ and $G$ |
| Some $F$s are $G$s | $\exists x(Fx \wedge Gx)$ | Not $\exists x(Fx \to Gx)$ — that is true if anything is not $F$ |
| No $F$s are $G$s | $\neg\exists x(Fx \wedge Gx)$ | Equivalent to $\forall x(Fx \to \neg Gx)$ |
| Only $F$s are $G$s | $\forall x(Gx \to Fx)$ | “Only” *reverses* the order: $G$ implies $F$, not $F$ implies $G$ |
| $p$ only if $q$ | $p \to q$ | “Only if” is *necessary* condition, not sufficient |
| $p$ if $q$ | $q \to p$ | “If” introduces the antecedent, wherever it sits in the sentence |
| $p$ unless $q$ | $\neg q \to p$, i.e. $p \vee q$ | Unless = “if not” |
| Not all $F$s are $G$s | $\exists x(Fx \wedge \neg Gx)$ | “All that glitters is not gold” is ambiguous between this and $\forall x(Gx \to \neg Ax)$ |

The last row is worth dwelling on, because it is the model case of a general lesson: **English surface grammar is an unreliable guide to logical form**, and the same sentence can receive two formalizations that differ in truth value. That is not a defect of the formalization; it is evidence that the sentence was ambiguous, and the ambiguity is often the philosophical problem (Ch. 31, §5; Ch. 33, §5).

### 3.6 Metalogic you should know exists

A primer is not a course, but the following results are referred to in the chapters and you should at least know what they say.

| The *result* | The *content* | The *chapter* |
|---|---|---|
| **Soundness** | Every theorem is valid | Ch. 35, §2 |
| **Completeness** (Gödel, 1929) | Every valid formula is a theorem | Ch. 35, §2 |
| **Compactness** | A set of formulas has a model iff every finite subset does | Ch. 35, §5 |
| **Undecidability** (Church–Turing) | No algorithm decides validity in first-order logic | Ch. 35, §2; Ch. 43 |
| **Löwenheim–Skolem** | If a theory has a model, it has a countable model; if it has arbitrarily large finite models, it has an infinite model | Ch. 35, §5 |
| **Incompleteness** (Gödel, 1931) | Any consistent, recursively axiomatizable theory strong enough for arithmetic is incomplete; it cannot prove its own consistency | Ch. 43, §5 |
| **Tarski’s theorem** | Truth for a language cannot be defined within that language | Ch. 32, §7 |

The moral for philosophy is double. First, first-order logic is a *powerful* instrument: it gives us a canonical notation for scope, quantification, and identity, and it is the reason twentieth-century philosophy could state its problems with a precision that the nineteenth century could not. Second, it is not the *whole* of logic: the incompleteness theorems show that the arithmetic needed even for elementary counting outruns any finite axiom system, and the undecidability of validity means there is no mechanical test for philosophical argument. The instrument is indispensable, and it is not a substitute for judgment.

---

## §4 Validity, Soundness, and the Reconstruction of Arguments

### 4.1 The definitions

| The *notion* | The *definition* | The *comment* |
|---|---|---|
| **Argument** | A set of premises and a conclusion | – |
| **Valid** | It is impossible for the premises to be true and the conclusion false | A property of *form*, not of actual truth |
| **Sound** | Valid, and the premises are true | A property of the *argument*, relative to the world |
| **Cogent** | Sound, and the premises are warranted (justified) | The epistemic property; Ch. 7 |
| **Strong** (inductive) | The premises make the conclusion probable | A matter of degree; §6 |

**The first distinction to fix**: validity is not truth, and soundness is not knowledge. “All fish fly; all flying things are birds; so all fish are birds” is *valid* and *unsound*. “Some mammals are dogs; some dogs are pets; so some mammals are pets” is *invalid* with true premises and a true conclusion. And a sound argument whose premises you accept on bad grounds gives you a true conclusion, not knowledge — the lesson of Gettier (Ch. 7, §2) applied to argument forms.

### 4.2 The counterexample method

To test validity, ask: *can I describe a possible situation in which the premises are true and the conclusion false?* If yes, invalid; if no, provisionally valid, and the formal proof is the confirmation.

The method has three limits worth naming.

**(i) It requires the form.** You cannot test the *prose*; you test the *symbolization*. A bad translation yields a bad verdict, and the argument may be valid in the author’s intended sense and invalid in yours.

**(ii) The “possible situation” must be genuinely possible.** In modal contexts — “John could not have done otherwise” — the counterexample must respect the modal facts, which is exactly what is in dispute (Ch. 27).

**(iii) The method is symmetric.** A valid form may have an instance whose premises are absurd; the validity of the form does not make the instance a good argument. This is the point of the *ex falso* rule and of the “paradoxes of material implication.”

### 4.3 Four questions to ask of any argument

The book’s method, in the compressed form you can carry into a seminar:

1. **What is the form?** Reconstruct the argument in the canonical notation, supplying suppressed premises explicitly (Ch. 2, §3).
2. **Is the form valid?** Proof, truth table, or countermodel. If invalid, the argument fails — and no amount of true premises will save it.
3. **Are the premises true?** This is the empirical and the evaluative question, and it is usually the one the argument’s author has done least to answer.
4. **Is a premise missing?** Most real arguments are **enthymemes**: one or more premises are suppressed. The missing premise may be the controversial one, and the reconstruction should make it explicit (Ch. 2, §3).

There is a fifth question, which is not part of logic but is part of philosophy: **is the argument worth making?** A valid proof that the number of primes is infinite is a proof of something no one doubted; a valid proof that the argument’s author is a fool is a proof of nothing at all.

### 4.4 Formalization as interpretation

The deepest point of this appendix is that **formalization is interpretation**. To symbolize an argument is to decide what its words mean, which distinctions matter, and which are noise. Two formalizations of the same paragraph may both be defensible, and the choice between them is a philosophical choice.

The paradigm is the ambiguity of “everyone loves someone” (§3.4). A second paradigm is the scope of negation in “all that glitters is not gold” (§3.5). A third is the difference between

$$
\Box (G \to \Box G) \quad \text{and} \quad G \to \Box G
$$

which is the difference between “it is a necessary truth that if God exists, God exists necessarily” and “if God exists, then God exists necessarily” — and the difference matters, because the first is a claim about the modal status of a conditional and the second is a claim about the modal status of a proposition (Ch. 50, §2.4). The formula is not the philosophy; the formula is the *skeleton* of the philosophy, and the flesh is what the translation supplies.

---

## §5 Modal Logic

### 5.1 Syntax and interdefinability

Add the **modal operators** $\Box$ (necessity) and $\Diamond$ (possibility), with recursion clauses as in §2.1. The two are interdefinable:

$$
\Diamond\phi \ \equiv \ \neg\Box\neg\phi, \qquad \Box\phi \ \equiv \ \neg\Diamond\neg\phi
$$

and the standard reading is: $\Box\phi$ is true when $\phi$ is true in **all** the relevantly accessible worlds; $\Diamond\phi$, when $\phi$ is true in **some**.

### 5.2 Kripke semantics

A **frame** is a pair $\mathcal{F} = \langle W, R \rangle$ with $W$ a non-empty set of *worlds* and $R \subseteq W \times W$ an *accessibility relation*. A **model** adds a valuation $V$ assigning to each atom a subset of $W$. Truth at a world is defined recursively; the modal clause is

$$
\mathcal{M}, w \models \Box\phi \iff \text{for every } v \in W \text{ with } wRv, \ \mathcal{M}, v \models \phi
$$

$$
\mathcal{M}, w \models \Diamond\phi \iff \text{for some } v \in W \text{ with } wRv, \ \mathcal{M}, v \models \phi
$$

**Validity in a frame** is truth at every world in every model on that frame. The correspondences between axioms and frame conditions are the backbone of the subject.

### 5.3 The systems and what they mean

| The *axiom* | The *formula* | The *frame condition* | The *philosophical reading* |
|---|---|---|---|
| **K** | $\Box(\phi \to \psi) \to (\Box\phi \to \Box\psi)$ | none | Necessity distributes over the conditional |
| **T** | $\Box\phi \to \phi$ | reflexive | What is necessary is actual |
| **4** | $\Box\phi \to \Box\Box\phi$ | transitive | Necessity is itself necessary |
| **5** | $\Diamond\phi \to \Box\Diamond\phi$ | euclidean | Modal status is not world-relative |
| **B** | $\phi \to \Box\Diamond\phi$ | symmetric | Actuality is necessarily possible |
| **D** | $\Box\phi \to \Diamond\phi$ | serial | Obligation implies permission |

| The *system* | The *axioms* | The *intended reading* |
|---|---|---|
| **K** | K | The minimal modal logic; no constraints |
| **T** | K + T | Alethic modality with actuality; some epistemic logics |
| **S4** | K + T + 4 | Necessity with positive introspection; provability (with GL) |
| **S5** | K + T + 5 | The standard logic of **metaphysical** necessity |
| **KD45** | K + D + 4 + 5 | Doxastic logic: belief is consistent, transitive, euclidean |
| **KD** | K + D | Deontic logic: obligation is consistent |

**Why S5 for metaphysics.** In S5 the modal status of a proposition does not vary between worlds: if it is possible that $\phi$ is necessary, then $\phi$ is necessary. This is what makes the modal ontological argument run (Ch. 50, §2.4): from the *possibility* of a maximally great being one infers its *necessity*, and thence its actuality. The argument is valid in S5; the disputed premise is the possibility, not the logic. Chapter 16, §2–4 examines the alternatives (contingentism, non-standard modal logics, essence-based accounts) that reject the S5 framework.

### 5.4 *De dicto* and *de re*

The distinction is the difference between

$$
\Box \exists x Fx \quad (\text{necessarily, something is } F)
$$

and

$$
\exists x \Box Fx \quad (\text{there is something that is necessarily } F)
$$

They are not equivalent, and the difference is the formal core of several metaphysical disputes. The **Barcan formula**,

$$
\forall x \Box Fx \to \Box \forall x Fx
$$

and its converse mark the boundary between **actualism** (the domain of quantification is the same at every world) and **possibilism** (it is not). Kripke’s semantics allows both, which is why the choice between them is a metaphysical choice rather than a logical one (Ch. 16, §4).

### 5.5 Epistemic and deontic readings

The same notation does different work in different readings, and the axioms tell you which reading you are in.

| The *reading* | $\Box\phi$ means | Which axioms hold | The *comment* |
|---|---|---|---|
| **Alethic** | It is necessary that $\phi$ | K, T, 4, 5 (S5) | The standard |
| **Epistemic** | The agent knows that $\phi$ | K, T, 4; **not** 5 | Negative introspection (5) fails: you may not know that you don’t know |
| **Doxastic** | The agent believes that $\phi$ | K, D, 4, 5 | Consistency (D) is idealized: real believers are inconsistent |
| **Deontic** | It is obligatory that $\phi$ | K, D; **not** T | “Ought” does not imply “is”: $\Box\phi \to \phi$ fails |
| **Provability** | It is provable that $\phi$ | K, 4, GL | Löb’s axiom replaces T |

The failure of **T** in deontic logic is the formal expression of the is–ought gap (Ch. 44, §1): from “you ought to $\phi$” nothing follows about whether you do. The failure of **5** in epistemic logic is the formal expression of a substantive epistemic fact: knowledge does not guarantee knowledge of its own limits.

### 5.6 Rigid designation and substitution

A **rigid designator** denotes the same individual in every world in which it denotes at all. Kripke’s insight (Ch. 12, §3) is that proper names and natural-kind terms are rigid, and that this explains the validity of

$$
a = b \ \to \ \Box(a = b)
$$

when $a$ and $b$ are rigid. If Hesperus is Phosphorus, then necessarily Hesperus is Phosphorus — and yet “Hesperus is Phosphorus” was an *a posteriori* discovery. Hence the **necessary a posteriori**, and the collapse of the traditional identification of the necessary with the a priori.

The **substitution warning**: you may not substitute co-referential terms *salva veritate* into modal contexts unless both terms are rigid. From “It is necessary that 9 is greater than 7” and “9 = the number of planets” you may not infer “It is necessary that the number of planets is greater than 7.” The failure is not a failure of logic; it is a failure to respect the *de dicto*/*de re* distinction and the rigidity of the terms.

---

## §6 Probability

### 6.1 The axioms

A **probability space** is a triple $\langle \Omega, \mathcal{F}, P \rangle$: a set $\Omega$ of *outcomes*, a field $\mathcal{F}$ of *events* (subsets of $\Omega$ closed under complement and countable union), and a function $P : \mathcal{F} \to \mathbb{R}$ satisfying

$$
\text{(K1)} \quad P(A) \ge 0 \qquad \text{(K2)} \quad P(\Omega) = 1 \qquad \text{(K3)} \quad P\Big(\bigcup_{i} A_i\Big) = \sum_i P(A_i) \ \text{ for disjoint } A_i
$$

The axioms are due to Kolmogorov (1933); they are the *syntax* of probability, and they leave the *interpretation* open (§6.4).

### 6.2 The theorems

Everything else follows.

$$
P(\emptyset) = 0, \qquad P(A^c) = 1 - P(A), \qquad P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

$$
A \subseteq B \ \Rightarrow \ P(A) \le P(B), \qquad P(A) \le 1
$$

and the general inclusion–exclusion formula,

$$
P\Big(\bigcup_{i=1}^{n} A_i\Big) = \sum_i P(A_i) - \sum_{i<j} P(A_i \cap A_j) + \cdots + (-1)^{n+1} P\Big(\bigcap_{i=1}^{n} A_i\Big)
$$

**Independence**: $A$ and $B$ are independent iff $P(A \cap B) = P(A)P(B)$; conditional independence is $P(A \cap B \mid C) = P(A \mid C)P(B \mid C)$. The distinction between independence and conditional independence is the source of Simpson’s paradox and of a great deal of confusion in the causal inference literature (Ch. 18, §2).

### 6.3 Conditional probability and Bayes

**Conditional probability** is defined by

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \qquad P(B) > 0
$$

from which the **multiplication rule** follows: $P(A \cap B) = P(A \mid B)P(B)$. The **law of total probability**, for a partition $\{A_i\}$ of $\Omega$:

$$
P(B) = \sum_i P(B \mid A_i) P(A_i)
$$

and **Bayes’ theorem**:

$$
P(H \mid E) = \frac{P(E \mid H)\, P(H)}{P(E)} = \frac{P(E \mid H)\, P(H)}{P(E \mid H)P(H) + P(E \mid \neg H)P(\neg H)}
$$

**The odds form** is the version used throughout this book, because it separates the *prior* from the *evidence*:

$$
\underbrace{\frac{P(H \mid E)}{P(\neg H \mid E)}}_{\text{posterior odds}} = \underbrace{\frac{P(E \mid H)}{P(E \mid \neg H)}}_{\text{likelihood ratio}} \times \underbrace{\frac{P(H)}{P(\neg H)}}_{\text{prior odds}}
$$

The likelihood ratio is the *diagnostic* quantity: $> 1$ favours $H$, $< 1$ disfavours it, $= 1$ is irrelevant. The distinction between $P(E \mid H)$ and $P(H \mid E)$ is the single most important probabilistic distinction in applied philosophy, and its violation has a name (§6.5).

### 6.4 Interpretations

The axioms do not tell you what probability *is*. The four standard answers:

| The *interpretation* | The *content* | The *problem* |
|---|---|---|
| **Frequentist** | The limiting relative frequency in a reference class | The reference class problem; single-case probabilities |
| **Propensity** | A disposition of the setup to produce the outcome | The meaning of the disposition; indeterminism |
| **Subjective** (Bayesian) | A degree of belief, rationalised by coherence | The problem of the priors; unconstrained priors |
| **Logical** | A degree of entailment, or of support | The problem of the null confirmation; language dependence |

The subjective interpretation is the one this book uses most, because it is the one that models *inference*. Its classic defence is the **Dutch book argument**: if your degrees of belief violate the axioms, there is a set of bets, each of which you regard as fair, which guarantees you a loss. Coherence is thus a requirement of practical rationality.

The argument has two standard objections, and you should know both. (i) It assumes that your betting dispositions *are* your credences and that utility is linear in money; if you are risk-averse, or if money has diminishing marginal utility, incoherent credences need not be exploitable. (ii) It establishes *pragmatic* rationality, not *epistemic* rationality; the modern alternative — **accuracy-first epistemology** (Joyce, Greaves, Wallace) — argues directly that credences should be as *accurate* as possible, and derives the axioms from a scoring rule. Chapter 10, §4–5 examines the debate.

### 6.5 The fallacies

| The *fallacy* | The *error* | The *example* |
|---|---|---|
| **Base-rate neglect** | Ignoring the prior in favour of the likelihood | The medical test (§7.3) |
| **Prosecutor’s fallacy** | Confusing $P(E \mid I)$ with $P(I \mid E)$ | The DNA match (§7.3) |
| **Conjunction fallacy** | Judging $P(A \wedge B) > P(A)$ | The Linda case |
| **Gambler’s fallacy** | Believing that independent trials self-correct | “Red is due” |
| **Inverse gambler’s fallacy** | Inferring many trials from a surprising outcome | The fine-tuning argument (Ch. 50, §2.3) |
| **Reference-class** | Choosing the class that suits the conclusion | The actuarial and the clinical |
| **Catch-all** | Assigning a likelihood to $\neg H$ without a partition | The theism/naturalism debate (§7.4) |
| **Old evidence** | Forgetting that $P(E) = 1$ blocks confirmation | Glymour’s problem |

### 6.6 Confirmation

The probability calculus gives the *logic* of confirmation, but not yet a *theory* of it. The positions:

| The *theory* | The *claim* | The *problem* |
|---|---|---|
| **Hypothetico-deductivism** | $H$ is confirmed by $E$ if $H \models E$ | The raven paradox; irrelevant conjunctions |
| **Bayesianism** | $H$ is confirmed by $E$ if $P(H \mid E) > P(H)$ | Priors; the catch-all; old evidence |
| **Likelihoodism** | The evidence favours $H_1$ over $H_2$ iff $P(E \mid H_1) > P(E \mid H_2)$ | The law of likelihood; the stopping rule |
| **Falsificationism** | Science proceeds by conjecture and refutation | Duhem–Quine; the theory-ladenness of observation |

Chapter 40, §1–5 works through these; the point to carry away is that *confirmation is not deducible from the axioms* — the axioms tell you how to update, not what to count as evidence — and that the disputes about priors and catch-alls are the live edge of the field.

---

## §7 Bayesian Updating and Decision

### 7.1 Conditionalization

The **principle of conditionalization** says: on learning $E$ with certainty, your new credence in $H$ is your old conditional credence,

$$
P_{\text{new}}(H) = P_{\text{old}}(H \mid E)
$$

The **Jeffrey conditionalization** generalises to uncertain learning: if your credence in $E$ goes from $P(E)$ to $q$, then

$$
P_{\text{new}}(H) = q \cdot P_{\text{old}}(H \mid E) + (1-q) \cdot P_{\text{old}}(H \mid \neg E)
$$

**The convergence results** are the Bayesian’s best answer to the problem of the priors. Under weak conditions, conditionalizing on accumulating evidence makes posteriors converge regardless of the prior (Doob’s theorem; the Blackwell–Dubins merging-of-opinions theorem). The priors wash out — *eventually*. The objection is that “eventually” may be longer than the inquiry (Ch. 10, §4).

### 7.2 Odds form

The form to use in philosophical argument:

$$
\frac{P(H \mid E)}{P(\neg H \mid E)} = \frac{P(E \mid H)}{P(E \mid \neg H)} \times \frac{P(H)}{P(\neg H)}
$$

The virtue of the form is that it *localises* the dispute. When someone claims that the evidence strongly favours $H$, you can ask: which factor? Is the likelihood ratio large, or is the prior doing the work? And you can test the claim by varying the factor you think is contested. This is exactly what Chapter 50, §2.7 does with the cumulative case for theism.

### 7.3 Worked examples

**The medical test.** A disease has prevalence $1/1000$. The test has sensitivity $0.99$ (true positive rate) and specificity $0.95$ (true negative rate, so the false positive rate is $0.05$). A patient tests positive. What is the probability of disease?

$$
P(D \mid +) = \frac{0.99 \times 0.001}{0.99 \times 0.001 + 0.05 \times 0.999} = \frac{0.00099}{0.05094} \approx 0.0194
$$

About **1.9%**. The intuition that a positive test makes disease *likely* is the base-rate fallacy in its purest form. Note that the result does not depend on any controversial interpretation of probability; it is a theorem of the axioms plus the stated numbers.

**The prosecutor’s fallacy.** A DNA match has a random-match probability of $1$ in $10^6$; the suspect is one of $10^7$ people in the pool. The prosecutor says: the probability that the defendant is innocent given the match is $1$ in $10^6$. The correct calculation: the expected number of *innocent* matches is $10^7 \times 10^{-6} = 10$; if there is one true source, the posterior odds of guilt are roughly $1 : 10$, so the probability of guilt is about $9\%$, not $99.9999\%$. The fallacy is the confusion of $P(\text{match} \mid \text{innocent})$ with $P(\text{innocent} \mid \text{match})$.

**The miracle.** Hume’s argument (Ch. 50, §7.2) claims that the testimony for a miracle is never sufficient, because the prior is low and the testimony is imperfect. In the odds form: the prior odds against a miracle are very small, and the likelihood ratio of the testimony must be *very* large to overcome them. The Bayesian analysis does not refute Hume; it makes precise what would refute him — testimony whose reliability is high enough. Chapter 50, §7.3–7.4 discusses whether such testimony is available.

### 7.4 Objections

The Bayesian apparatus is the most-used formal tool in contemporary analytic philosophy, and it has four standing objections. You should be able to state them.

**(i) The problem of the priors.** Where do the prior probabilities come from? If they are subjective, the theory seems to license any conclusion; if they are objective, it is unclear what they are. The convergence results answer the *long-run* version, not the *short-run* (Ch. 10, §5).

**(ii) The catch-all problem.** To compute $P(E \mid \neg H)$ you need the likelihood of $E$ under *every* alternative to $H$. In real cases the alternatives are open-ended, so the likelihood is undefined or arbitrary. This is a serious problem for “theism vs. naturalism” arguments (Ch. 50, §2.7) and for any argument whose conclusion rests on the size of the catch-all.

**(iii) The problem of old evidence.** If $E$ is already known, $P(E) = 1$ and the likelihood ratio is $1$: the evidence cannot confirm. But scientists evidently treat known evidence as confirming (the perihelion of Mercury, the bending of light). Chapter 40, §4 discusses the proposed solutions (counterfactual priors, prediction, the “dynamic” version).

**(iv) The problem of logical omniscience.** Bayesian agents are assumed to know all logical consequences of their credences. Real agents do not, and the idealization is doing substantive work in some arguments — especially in the philosophy of science and in the epistemology of disagreement.

### 7.5 Decision rules

The probability calculus becomes a theory of *action* when you add utilities.

**Expected utility**: $EU(a) = \sum_i P(s_i) \, U(a, s_i)$, and the rule is: maximise $EU$.

| The *rule* | The *content* | The *use* |
|---|---|---|
| **Maximise expected utility** | Choose the act with the highest expected utility | The default; the von Neumann–Morgenstern axioms |
| **Maximin** | Choose the act whose worst outcome is best | Existential risk; Rawlsian choice (Ch. 47, §3) |
| **Maximax** | Choose the act whose best outcome is best | The gambler’s rule; rarely defensible |
| **Minimax regret** | Choose the act whose worst regret is least | Some policy contexts |
| **Precautionary** | Avoid actions with catastrophic, uncertain outcomes | The environmental cases (Ch. 51, §8.2) |

**The value of information.** If information is free and perfect, it is always worth having, because you can condition your act on it. Its value is the difference between the expected utility of the informed choice and that of the uninformed choice. In the worked example of §7.3: if you must choose between a lottery with $E = 50$ and a sure thing with $E = 60$, and a free test tells you which, the informed value is $0.5 \times 100 + 0.5 \times 60 = 80$, so the information is worth up to $20$.

**The paradoxes** are worth knowing because they mark the limits of the expected-utility model. **Allais** shows that people violate the independence axiom. **Ellsberg** shows that they prefer known to unknown probabilities (ambiguity aversion). The **St. Petersburg** game shows that expected value can be infinite while no one will pay much for it. The **Pascal wager** (Ch. 50, §5.4) shows that infinite payoffs make expected value dominate everything. Each is a case where the formal model and the considered judgment diverge, and the divergence is itself a philosophical datum.

---

## §8 A Checklist

Before you leave this appendix, make sure you can do the following. If you cannot, the chapter that uses the technique will be harder than it needs to be.

- [ ] Translate ten ordinary sentences into propositional and predicate logic, including sentences with *only*, *unless*, *all*, *some*, and *not all*.
- [ ] Construct a truth table for a three-variable formula and classify it.
- [ ] Prove a simple validity in natural deduction and give a countermodel for an invalid form.
- [ ] Distinguish validity, soundness, and cogency, with an example of each failure.
- [ ] Identify the scope ambiguity in a sentence and give the two readings.
- [ ] State what S5 adds to K, and what it commits you to about the modal status of propositions.
- [ ] State Bayes’ theorem in odds form and identify the likelihood ratio.
- [ ] Compute a posterior from a sensitivity, a specificity, and a base rate.
- [ ] State the catch-all problem and the old-evidence problem.
- [ ] Explain the difference between expected utility, maximin, and the precautionary principle.

---

## §9 The Thirty Exercises

Work them before looking at §10. The exercises are graded: §9.1–§9.4 are propositional and predicate; §9.5–§9.6 are validity and formalization; §9.7–§9.8 are modal; §9.9–§9.10 are probability and decision.

### 9.1 Propositional (1–8)

**1.** Formalize: “If it rains and the match is not cancelled, we will get wet.”

**2.** Construct the truth table for $(p \to q) \vee (q \to p)$ and classify it.

**3.** Are $(p \wedge q) \to r$ and $p \to (q \to r)$ equivalent?

**4.** Does $\{p \vee q, \ \neg p\} \models q$? Justify.

**5.** Does $\{p \to q, \ q\} \models p$? If not, give a counterexample.

**6.** Prove $p \to q, \ q \to r \ \vdash \ p \to r$.

**7.** Formalize “Unless you study, you will fail,” and explain whether “unless” is best treated as $\vee$ or as $\to$.

**8.** Show that $\neg(p \wedge q)$ and $\neg p \wedge \neg q$ are not equivalent, and state the correct equivalence.

### 9.2 Predicate (9–14)

**9.** Formalize “All philosophers are mortal” using $Px$ and $Mx$. Explain why $\forall x(Px \wedge Mx)$ is wrong.

**10.** Formalize “Some cats are not black.”

**11.** Formalize “Exactly one book is on the table,” using $Bx$ and $Tx$.

**12.** Symbolize Russell’s “The present King of France is bald” and say what truth value it has. Then give the two readings of its negation.

**13.** Does $\forall x \exists y Rxy \models \exists y \forall x Rxy$? Give a countermodel if not.

**14.** Name and diagnose the fallacy: “Everyone has a mother; therefore there is someone who is the mother of everyone.”

### 9.3 Validity and soundness (15–18)

**15.** Define validity and soundness. Give (i) an argument that is valid but unsound and (ii) an argument that is invalid but whose premises and conclusion are all true.

**16.** “The argument is valid and its premises are true, so it is sound; therefore its conclusion is knowledge.” Assess.

**17.** Assess: “If the argument is invalid, its conclusion is false.”

**18.** Reconstruct and evaluate: “Euthanasia must be wrong, because killing is always wrong, and euthanasia is killing.”

### 9.4 Formalization (19–22)

**19.** Formalize “It is necessary that if God exists, God exists necessarily,” and distinguish it from “If God exists, God exists necessarily.”

**20.** Explain the difference between $\Box \exists x Fx$ and $\exists x \Box Fx$, with an example.

**21.** Which modal system is standardly used for metaphysical modality, and why? Name one dissent.

**22.** Show that $p \to \Box \Diamond p$ (axiom B) is invalid in K, by giving a model.

### 9.5–9.6 Probability (23–30)

**23.** State the three Kolmogorov axioms and derive $P(A^c) = 1 - P(A)$.

**24.** A test has sensitivity $0.99$ and specificity $0.95$; prevalence is $1/1000$. Compute $P(D \mid +)$.

**25.** State Bayes’ theorem in odds form and explain the likelihood ratio.

**26.** A DNA match has random-match probability $1$ in $10^6$; the suspect pool is $10^7$. What is the probability of guilt given the match, roughly? What is the fallacy in saying “1 in a million”?

**27.** State the catch-all problem for Bayes’ theorem and explain why it matters for the “theism vs. naturalism” debate.

**28.** $P(H) = 0.4$, $P(E \mid H) = 0.8$, $P(E \mid \neg H) = 0.2$. Compute $P(H \mid E)$.

**29.** State the Dutch book argument, and one serious objection to it.

**30.** Act A yields $\$100$ with probability $0.5$ and $\$0$ otherwise; Act B yields $\$60$ for sure. Which has higher expected value? Does the answer settle what to do? What is a perfect free test worth?

---

## §10 The Answers

**1.** With $R$ = it rains, $C$ = the match is cancelled, $W$ = we get wet: $(R \wedge \neg C) \to W$. The scope matters: the sentence does not say “if it rains, and if the match is not cancelled, then we get wet” in the sense of three independent claims.

**2.**

$$
\begin{array}{cc|c|c|c}
p & q & p \to q & q \to p & (p \to q) \vee (q \to p) \\ \hline
T & T & T & T & T \\
T & F & F & T & T \\
F & T & T & F & T \\
F & F & T & T & T
\end{array}
$$

The formula is a **tautology**. It is the “conditional’s tautology”: of any two indicative conditionals, at least one is true. Whether that is a *virtue* of the material conditional or a *reductio* of it is Chapter 37, §2.

**3.** Yes. Exportation holds: $(\phi \wedge \psi) \to \chi \equiv \phi \to (\psi \to \chi)$. Verify by truth table or by the deduction theorem.

**4.** Yes. The only valuation making $p \vee q$ and $\neg p$ true is $p = F, q = T$, which makes $q$ true. This is disjunctive syllogism.

**5.** No. Take $p = F, q = T$: both premises are true and the conclusion false. This is **affirming the consequent**.

**6.**

$$
\begin{array}{lll}
1. & p \to q & \text{premise} \\
2. & q \to r & \text{premise} \\
3. & \quad p & \text{assumption} \\
4. & \quad q & \text{1, 3 by } \to\text{E} \\
5. & \quad r & \text{2, 4 by } \to\text{E} \\
6. & p \to r & \text{3–5 by } \to\text{I}
\end{array}
$$

**7.** With $S$ = you study, $F$ = you fail: $S \vee F$, equivalently $\neg S \to F$. “Unless” is best treated as a disjunction, because it does not assert that you will study; it asserts that studying is *sufficient* to avoid the failure. Note that “$p$ unless $q$” and “$p$ if not $q$” are the same.

**8.** By De Morgan, $\neg(p \wedge q) \equiv \neg p \vee \neg q$. Counterexample to the alleged equivalence: $p = T, q = F$ makes $\neg(p \wedge q)$ true and $\neg p \wedge \neg q$ false.

**9.** $\forall x(Px \to Mx)$. The formula $\forall x(Px \wedge Mx)$ says that *everything* is a philosopher and mortal, which is far stronger; it is false if there is a single non-philosopher.

**10.** $\exists x(Cx \wedge \neg Bx)$.

**11.** $\exists x\big(Bx \wedge Tx \wedge \forall y((By \wedge Ty) \to y = x)\big)$.

**12.** $\exists x\big(Kx \wedge \forall y(Ky \to y = x) \wedge Bx\big)$. It is **false**, because the existential clause fails. The negation is ambiguous: wide scope, $\neg\exists x(Kx \wedge \dots \wedge Bx)$, is **true**; narrow scope, $\exists x(Kx \wedge \dots \wedge \neg Bx)$, is **false**. This is Russell’s solution to the problem of negative existentials (Ch. 12, §2).

**13.** No. Let $D = \{1, 2\}$ and $R = \{(1,2), (2,1)\}$. Then every element bears $R$ to something, so $\forall x \exists y Rxy$ is true; but there is no element to which both $1$ and $2$ bear $R$, so $\exists y \forall x Rxy$ is false.

**14.** The **quantifier-shift fallacy** (or the fallacy of the converse of the Barcan formula, in modal dress): $\forall x \exists y Rxy \not\models \exists y \forall x Rxy$. The premise is true of every person and the conclusion requires a single universal mother.

**15.** (i) Valid/unsound: “All fish fly; all flying things are birds; so all fish are birds” — valid form (hypothetical syllogism on the predicates), false first premise. (ii) Invalid, all true: “Some mammals are dogs; some dogs are pets; so some mammals are pets.” Countermodel: $M = \{1\}$, $D = \{1, 2\}$, $P = \{2\}$.

**16.** The inference fails at the last step. Soundness gives you a true conclusion; it does not give you knowledge. Knowledge requires warrant and the absence of defeaters (Ch. 7, §1–3), and a sound argument can leave the conclusion believed for the wrong reason, or accepted on a premise whose warrant is defective. The Gettier cases are the canonical demonstration that true justified belief is not yet knowledge; a sound argument is a special case.

**17.** False. Invalidity is a property of form; a conclusion can be true for reasons independent of the argument. “Some dogs are mammals; so $2 + 2 = 4$” is invalid with a true conclusion.

**18.** Form: (1) All killing is wrong; (2) Euthanasia is killing; (3) Therefore euthanasia is wrong. The form is valid (universal modus ponens / Barbara). The argument is sound only if (1) is true, which is precisely the question at issue; the argument therefore begs the question against the opponent. Moreover (1) is contested by the killing/letting-die literature (Ch. 51, §2.2), and the conclusion is not entailed by the premises unless “killing” is used univocally. The argument is a *valid* reconstruction of a *question-begging* case.

**19.** $\Box(G \to \Box G)$ versus $G \to \Box G$. The first says that the conditional is a necessary truth; the second says that, given God’s existence, his existence is necessary. In S5 the two are related but not identical, and the modal ontological argument needs the first (or a premise that entails it), not the second (Ch. 50, §2.4).

**20.** $\Box\exists x Fx$ = “necessarily, something is $F$” — in every world, the domain contains an $F$. $\exists x \Box Fx$ = “there is an object which is $F$ in every world.” Example: “Necessarily, someone is the winner” versus “Someone is necessarily the winner.” The first is compatible with different winners in different worlds; the second requires a particular individual who wins in all of them. The Barcan formula marks the difference (§5.4).

**21.** **S5** is standard for metaphysical modality, because it validates the principle that the modal status of a proposition is not itself contingent: if it is possible that $\phi$ is necessary, then $\phi$ is necessary. Dissent: **contingentism** (Williamson), on which what exists, and hence what is necessary, varies between worlds; and **essence-based** accounts (Fine, Lowe) which replace possible worlds with real definitions. Chapter 16, §2–4.

**22.** Let $W = \{w, v\}$, $R = \{(w,v)\}$, and $V(p) = \{w\}$. At $w$: $p$ is true; $\Diamond p$ is false at $v$ (since $v$ has no successors), so $\Box\Diamond p$ is false at $w$. Hence $p \to \Box\Diamond p$ fails at $w$. The frame is not symmetric, which is the correspondence condition for B.

**23.** K1–K3 as in §6.1. Since $A$ and $A^c$ are disjoint and $A \cup A^c = \Omega$:

$$
1 = P(\Omega) = P(A \cup A^c) = P(A) + P(A^c)
$$

so $P(A^c) = 1 - P(A)$.

**24.** $\dfrac{0.99 \times 0.001}{0.99 \times 0.001 + 0.05 \times 0.999} = \dfrac{0.00099}{0.05094} \approx 0.0194$, about **1.9%**.

**25.** Posterior odds = prior odds × likelihood ratio: §7.2. The likelihood ratio $P(E \mid H)/P(E \mid \neg H)$ measures the *diagnosticity* of the evidence. It is the inverse of the quantity used in the prosecutor’s fallacy.

**26.** About **9%**. The expected number of innocent matches among $10^7$ people is $10$; with one true source, the posterior odds of guilt are roughly $1 : 10$. The fallacy is the confusion of $P(\text{match} \mid \text{innocent})$ with $P(\text{innocent} \mid \text{match})$.

**27.** To compute $P(E \mid \neg H)$ one needs a partition of $\neg H$ into specific alternatives, each with its own likelihood. When $\neg H$ is left as a catch-all (“all the other hypotheses”), the likelihood is undefined or arbitrarily assignable, and the theorem can be made to yield almost any conclusion. This is why cumulative-case arguments in the philosophy of religion are so fragile: the denominator is doing the work and is not specified (Ch. 50, §2.7; §7.4 above).

**28.** $P(E) = 0.8(0.4) + 0.2(0.6) = 0.32 + 0.12 = 0.44$; $P(H \mid E) = 0.32/0.44 \approx 0.727$.

**29.** If your degrees of belief violate the probability axioms, there is a set of bets, each of which you regard as fair, which guarantees you a loss; so coherence requires the axioms (Ramsey, de Finetti). Objection: the argument assumes that betting dispositions are credences and that utility is linear in money, and it establishes pragmatic rather than epistemic rationality; the accuracy-first programme is the modern alternative (§6.4).

**30.** EV(A) $= 0.5 \times 100 + 0.5 \times 0 = 50$; EV(B) $= 60$. B has the higher EV. The answer does **not** settle what to do: risk aversion, the diminishing marginal utility of money, maximin (if the downside is catastrophic), and the precautionary principle can all recommend otherwise. A perfect free test is worth up to $\$20$: the informed strategy yields $0.5 \times 100 + 0.5 \times 60 = 80$, which is $20$ more than the best uninformed choice.

---

## §11 Where to Go Next

A primer has a duty to point beyond itself. These are the five books that will take a reader from this appendix to the working literature, in ascending order of difficulty.

- **For the logic**: Graham Priest, *Logic: A Very Short Introduction* (2000) — short, opinionated, and honest about the philosophical stakes. Then Theodore Sider, *Logic for Philosophy* (2010), for the modal and probability material at the level this book uses it.
- **For the metalogic**: Peter Smith, *An Introduction to Gödel’s Theorems* (2007) — the clearest treatment of completeness, incompleteness, and undecidability for a philosophical reader.
- **For the probability**: Ian Hacking, *An Introduction to Probability and Inductive Logic* (2001) — the best single bridge from the axioms to the philosophy. Then Alan Hájek, “Interpretations of Probability” (*Stanford Encyclopedia of Philosophy*), for the state of the debate.
- **For the decision theory**: Michael Resnik, *Choices* (1987), or the relevant chapters of Paul Anand, Prasanta Pattanaik & Clemens Puppe (eds.), *The Handbook of Rational and Social Choice* (2009).
- **For the formalism’s limits**: Chapter 35 of this book, and then Stephen Read, *Relevant Logic* (1988), if the material conditional has come to seem intolerable.

> *A closing note.* The instruments in this appendix are the ones the book has used throughout: the truth table in Chapter 2, the countermodel in Chapter 6, the proof in Chapter 13, the Bayes factor in Chapter 40, the decision matrix in Chapter 51. They are not the *philosophy*; they are the *hygiene* of the philosophy. But hygiene is not nothing: a discipline that cannot state its arguments in a form that can be checked has no way of knowing whether it has understood them, and a reader who cannot compute a posterior probability has no way of knowing whether the argument in front of them is a proof or a mood. Learn the instruments. Then put them down, and think.
