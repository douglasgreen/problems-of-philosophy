# Chapter 10 — Induction, Probability, and Inference to the Best Explanation

> “All reasonings concerning matter of fact seem to be founded on the relation of Cause and Effect. … But if we would be thoroughly acquainted with the nature of this relation, we must enquire … how we arrive at the knowledge of cause and effect.”
> — Hume, *An Enquiry Concerning Human Understanding*, IV.i

> “Induction is the glory of science and the scandal of philosophy.”
> — C. D. Broad, *The Mind and Its Place in Nature* (1925), p. 168

---

Chapter 9 followed the tradition’s claim that some knowledge is independent of experience, and it found the claim to be thin, fallible, and narrower than the rationalists hoped. This chapter follows the *other* source of justification — experience — and finds it in a condition that has been called, with only slight exaggeration, the *scandal* of philosophy: we cannot justify the inference from what we have observed to what we have not, and yet the whole of empirical knowledge depends on it.

The problem of induction is the *empirical* counterpart of the problem of the a priori, and the two are, at bottom, the same problem. The a priori was asked to justify the *non-empirical*; induction is asked to justify the *ampliative*. In both cases, the justification must somehow do more than the premises permit — and in both cases, the demand for a non-circular justification has not been met. The difference is that the a priori could retreat to a *thin* conception (a kind of warrant, not a foundation), and induction has no such retreat available: it is the *only* way of getting beyond experience, and if it is unjustified, the whole of empirical knowledge is unjustified.

The chapter proceeds in eight movements. §1 states Hume’s problem in its epistemic and metaphysical forms. §2 surveys the classical attempts at a solution — Mill, Reichenbach, Strawson, Popper. §3 presents Goodman’s *new riddle*, which shows that the problem is deeper than Hume thought. §4 presents the Bayesian framework, the best formal tool we have. §5 presents the problem of the priors, which is the residue of the problem within the Bayesian framework. §6 presents inference to the best explanation, the most important ampliative inference in philosophy and science. §7 turns to statistical reasoning, the *practical* form of the problem, and to the everyday epistemology of evidence. §8 gives an honest verdict.

---

## 1. Hume’s Problem

### 1.1 The setting: the fork

Hume’s *Enquiry* (1748) opens with a distinction that structures the whole of his epistemology: the **fork** between **relations of ideas** and **matters of fact**.

- **Relations of ideas** are the propositions of mathematics, logic, and definition. Their truth is *demonstrable*: the contrary implies a contradiction. (“Three times five is equal to half of thirty.”)
- **Matters of fact** are the propositions of empirical science and ordinary life. Their truth is *not* demonstrable: the contrary is always conceivable. (“The sun will rise tomorrow.”)

The fork is the ancestor of the analytic/synthetic distinction (Ch. 9, §2), and it is the setting for the problem.

### 1.2 The epistemic form

The problem is stated most sharply in *Enquiry* IV.ii:

> “All inferences from experience suppose, as their foundation, that the future will resemble the past, and that similar powers will be conjoined with similar sensible qualities. If there be any suspicion that the course of nature may change, and that the past may be no rule for the future, all experience becomes useless, and can give rise to no inference or conclusion.”

**The argument.**

$$
\begin{array}{ll}
1. & \text{Every inductive inference presupposes the uniformity principle: that the future will resemble the past.} \\
2. & \text{The uniformity principle cannot be known by demonstration (its denial is conceivable).} \\
3. & \text{The uniformity principle cannot be known by experience without circularity (the appeal to experience presupposes the principle).} \\
\hline
4. & \therefore \text{The uniformity principle is not justified.} \\
5. & \text{Every inductive inference presupposes it.} \\
\hline
6. & \therefore \text{No inductive inference is justified.}
\end{array}
$$

The structure of the argument is *not* that induction sometimes fails. It is that the *justification* of induction cannot be given without presupposing what is to be justified. The argument is a **circle**, and the question is whether the circle is *vicious*.

**The formal statement.** The inductive principle can be stated as a schema:

$$
(\mathrm{IP}) \quad \text{If } F \text{ has been observed in } n \text{ instances, and no } \neg F \text{ has been observed, then the next } F \text{ will be } F.
$$

The justification of (IP) cannot be deductive: (IP)’s negation is conceivable (the uniformities could break down). The justification cannot be inductive: any inductive argument for (IP) uses (IP). The justification cannot be *a priori*: (IP) is not a relation of ideas. So (IP) is unjustified, and every inference that presupposes it is unjustified.

### 1.3 The metaphysical form

The *epistemic* form says: induction is unjustified. The *metaphysical* (or *descriptive*) form says: there is **no necessary connection** in nature, and the “power” by which one event produces another is a projection of the mind.

**The argument.**

$$
\begin{array}{ll}
1. & \text{We never observe necessary connections between events; we observe only constant conjunctions.} \\
2. & \text{The idea of necessary connection must be derived from an impression (the empiricist principle).} \\
3. & \text{There is no impression of necessary connection in the objects.} \\
\hline
4. & \therefore \text{The idea of necessary connection is derived from a feeling in the mind (the “determination” to pass from the impression of one object to the idea of its usual attendant).} \\
5. & \text{That feeling is the source of the idea.} \\
\hline
6. & \therefore \text{Necessary connection is not a feature of the world, but a feature of our psychology.}
\end{array}
$$

The two forms are connected. If there is no necessary connection in nature, then the “uniformity of nature” is not a *fact* that could ground induction; it is a *habit* of the mind. The *epistemic* problem is that induction is unjustified; the *metaphysical* problem is that there is nothing in the world for induction to track.

### 1.4 The “skeptical solution”

Hume’s *skeptical solution* is the second half of his treatment of the problem, and it is frequently overlooked. His own response is *naturalistic* rather than *justificatory*.

> “Nature, by an absolute and uncontrollable necessity, has determined us to judge as well as to breathe and feel.” (*Treatise of Human Nature* I.iv.1)
> “Custom is the great guide of human life.” (*Enquiry* V.i)

The response is: we *cannot help* reasoning inductively, because custom and habit determine our inferences. The skeptical *conclusion* is not refuted; it is *lived with*. This is the **mitigated skepticism** that Hume recommends at the end of the *Enquiry* (XII.iii): a skepticism that is “durable” and “useful” because it is *tempered* by nature.

The structure of the response is a **genetic** explanation, not a justification. It tells us *why* we reason inductively, not *whether* we are *right* to. Whether the explanation is *satisfying* is the central question of the chapter.

### 1.5 The argument’s status

The Humean argument is one of the most discussed in the history of philosophy, and its status is contested. Three issues.

**(i) Is the argument *valid*?** The argument is valid if the premises are true. Premise 1 (every inductive inference presupposes uniformity) is contested: some philosophers (Norton 2003) argue that inductive inferences are *local* rather than *global*, and that the uniformity principle is not a premise of every inductive argument. Premise 3 (the circularity) is the crux: is the appeal to experience *viciously* circular, or is it *virtuously* circular (Ch. 8, §3)?

**(ii) Is the argument *sound*?** The soundness depends on the *conception of justification* that the argument presupposes. If justification must be *non-circular* and *certain*, then the argument is sound and induction is unjustified. If justification can be *circular* (in a virtuous way) or *fallible*, then the argument is not sound. The argument is *internal* to a *foundationalist* conception of justification (Ch. 8, §2), and it loses its force on a *coherentist* or *reliabilist* conception.

**(iii) Is the argument *a reductio*?** The argument proves that induction is unjustified on the assumption that all justification must be deductive or empirical. If the assumption is false — if there is a *third* kind of justification (e.g., *pragmatic*, *reliabilist*, *virtue-theoretic*) — then the argument shows only that induction is not justified *in the foundationalist sense*. This is the strategy of the responses in §2.

---

## 2. The Classical Attempts

### 2.1 Mill: the methods and the uniformity principle

Mill’s *A System of Logic* (1843) is the most ambitious attempt to *systematize* induction. His contribution is twofold.

**(i) The methods of experimental inquiry.** Mill codified five methods:

| Method | Principle | Form |
|---|---|---|
| **Agreement** | If two instances agree in $A$ and $a$ (and differ in the other factors), then $A$ is the cause of $a$ | $\frac{ABC \to abc;\ ADE \to ade}{\therefore A \text{ causes } a}$ |
| **Difference** | If two instances differ only in $A$, and differ in $a$, then $A$ is the cause of $a$ | $\frac{ABC \to abc;\ BC \to bc}{\therefore A \text{ causes } a}$ |
| **Concomitant variation** | If $A$ varies with $a$, then $A$ is causally related to $a$ | $A \propto a$ |
| **Residues** | Subtract the known causes from the phenomenon; the residue is due to the remaining antecedents | — |
| **Joint method** | Agreement + difference | — |

The methods are the *logic* of experimental science, and they are still taught (Ch. 18, §1.4; Ch. 38, §1.2). Their limitation is that they *presuppose* the causal structure they are meant to discover: the methods identify a cause only if the relevant variables are already in the list, and the list is supplied by *theory*, not by the methods.

**(ii) The uniformity principle.** Mill’s justification of the methods is the **principle of the uniformity of nature**: “the course of nature is uniform.” Mill acknowledges that the principle is *itself* an induction, and he argues that it is justified by *its* success. The argument is circular, and Mill knows it:

> “The proposition that the course of nature is uniform is the fundamental principle, or rather the general axiom, of Induction itself. … It is itself an instance of induction, and not the most obvious one.” (*System of Logic*, III.iii.1)

Mill’s response is to *embed* the circularity in a *hierarchy* of inductions: the particular inductions are justified by the uniformity principle, and the uniformity principle is justified by the *most general* inductions (the laws of physics). The hierarchy is a *coherentist* structure, and it is the ancestor of the **reflective equilibrium** (Ch. 3, §4) and the **web of belief** (Ch. 8, §3).

The problem: the hierarchy does not *terminate*. The most general inductions are justified by the uniformity principle, and the uniformity principle is justified by the most general inductions. The circle is *large*, but it is still a circle.

### 2.2 Reichenbach: the pragmatic vindication

Hans Reichenbach (*Experience and Prediction*, 1938, Ch. 5; *The Theory of Probability*, 1949, §80) offered the most influential *pragmatic* response.

**The argument.**

$$
\begin{array}{ll}
1. & \text{Either nature is uniform (the future resembles the past) or it is not.} \\
2. & \text{If nature is uniform, induction will succeed (the inductive method will converge on the truth).} \\
3. & \text{If nature is not uniform, no method will succeed.} \\
\hline
4. & \therefore \text{If any method succeeds, induction succeeds.} \\
5. & \text{We have no better method.} \\
\hline
6. & \therefore \text{It is rational to use induction.}
\end{array}
$$

The argument is a *pragmatic* justification: it does not show that induction is *likely to succeed*; it shows that induction is the *best bet*, because it is the only method that *could* succeed if any method could.

**The objections.**

**(i) The “if any method succeeds” clause.** The argument presupposes that induction is the *only* method that could succeed. But this is *false*: a method that predicts the *violation* of uniformity (the “counter-inductive” method) would succeed if nature is *not* uniform. The argument is silent on the comparison between induction and its rivals.

**(ii) The “long run” problem.** Reichenbach’s vindication is *asymptotic*: induction converges on the truth in the *limit* of infinite evidence. But finite agents do not have infinite evidence, and the *short-run* behavior of induction is not justified by the long-run convergence. (This is the “short-run” objection, and it is serious.)

**(iii) The “definition” problem.** The argument is *conditional*: *if* the future is uniform, induction works. But the skeptic’s question is precisely whether the future *is* uniform. The argument does not answer the question; it *brackets* it.

**(iv) The “generality” problem.** The argument is a version of **Pascal’s wager**: it recommends a bet on the basis of a *possibility*, not a *probability*. The recommendation is rational only if the *expected value* of the bet is higher than the alternatives, and the expected value depends on the probability of uniformity, which is precisely what is in question.

Reichenbach’s argument is the most *robust* of the classical attempts, and it is still discussed. Its *honest* assessment: it is a *pragmatic* justification, not an *epistemic* one; it tells us what to do, not what to believe.

### 2.3 Strawson: the dissolution

P. F. Strawson (*Introduction to Logical Theory*, 1952, Ch. 9) offered a *dissolution* rather than a justification.

**The argument.**

> “It is an analytic proposition that it is reasonable to have a degree of belief in a statement which is proportional to the strength of the evidence in its favour. … The question of justification … is a question of the *meaning* of ‘reasonable’, not a question of fact.” (Strawson 1952, pp. 256–257, paraphrased)

The claim: “induction is justified” is *analytic*. To be *reasonable* is, *by definition*, to reason inductively. The demand for a *further* justification of induction is *incoherent*, because it asks for a justification of the standard by which justifications are assessed.

**The objections.**

**(i) The “persuasive definition” objection.** The argument *defines* “reasonable” in a way that makes induction reasonable *by fiat*. But the skeptic can *deny* the definition: she can say, “I use ‘reasonable’ differently, and on my usage, induction is not reasonable.” The argument is a *stipulation*, not a *justification*.

**(ii) The “circularity” objection.** The argument is circular: it *assumes* that induction is the standard of reasonableness, and it concludes that induction is reasonable. The circle is *not* made virtuous by being *semantic*.

**(iii) The “skeptic’s question” objection.** The skeptic’s question is not “is induction *called* reasonable?” but “is induction *truth-conducive*?” The dissolution *changes the subject*: it answers a *verbal* question, not the *epistemic* one.

The dissolution is *elegant* and *unsatisfying*. Its value is *diagnostic*: it shows that the *demand* for a justification of induction may rest on a *false* picture of justification — the picture on which justification must be *external* to the practice. (This is the *quietist* response, Ch. 6, §6.5, applied to induction.)

### 2.4 Popper: falsificationism

Karl Popper (*The Logic of Scientific Discovery*, 1934/1959) offered the most *radical* response: **there is no induction**, and there is no need for it.

**The argument.**

1. Science proceeds by **conjecture and refutation**: we propose hypotheses, and we test them by deducing observable consequences and checking whether the consequences obtain.
2. The logic of testing is **deductive**: *modus tollens*. If $H$ implies $O$, and $\neg O$, then $\neg H$. No induction is involved.
3. The *confirmation* of a hypothesis is not a *probabilistic* relation; it is a *negative* result: the hypothesis *survives* the test, and it is *corroborated*, not *confirmed*.
4. There is no *inductive* inference from the observed to the unobserved; there is only the *deductive* testing of conjectures.

**The objections.**

**(i) The “prediction” problem.** To test a hypothesis, we must *derive* an observable consequence. The derivation is deductive, but the *observation* of the consequence is not: we must *identify* the observation as an instance of the predicted type, and the identification is *inductive*. (This is the “Duhem–Quine” problem, and the “theory-ladenness” of observation; Ch. 40, §§3–4.)

**(ii) The “corroboration” problem.** Popper says that a corroborated hypothesis is *preferable* to a falsified one. But *why*? The preference is a *methodological* rule, and the rule is *not* justified by *deductive* logic. If the preference is justified, it is justified by an *inductive* argument (the future will resemble the past: corroborated hypotheses have tended to be true).

**(iii) The “acceptance” problem.** Popper says that we *accept* corroborated hypotheses *provisionally*. But *acceptance* is a *practical* attitude, and the *rationality* of the acceptance requires a *justification* — the very justification that Popper denies.

**(iv) The “no knowledge” problem.** If there is no induction, there is no *knowledge* of the unobserved. The most that we can have is *corroboration*, which is not knowledge. This is a *skeptical* consequence, and Popper accepts it: “we do not know, we can only guess.” Whether this is *acceptable* is a matter of philosophical temperament.

Popper’s response is the most *consistent* of the classical attempts: it *accepts* the Humean conclusion and *rejects* the premise that science needs induction. Its *cost* is that it makes *knowledge* of the unobserved impossible — which is a high price to pay for consistency.

### 2.5 The comparative table

| Response | Core move | What it preserves | What it gives up | Status |
|---|---|---|---|---|
| **Hume** | Custom and habit | The practice of induction | The justification | Naturalistic; the problem remains |
| **Mill** | The uniformity principle | The methods; the hierarchy | The non-circularity | Circular; coherentist |
| **Reichenbach** | Pragmatic vindication | The rationality of the practice | The epistemic justification | Conditional; the long run |
| **Strawson** | Analytic dissolution | The meaning of “reasonable” | The skeptic’s question | Verbal; unsatisfying |
| **Popper** | Falsificationism | The deductive logic of testing | The knowledge of the unobserved | Consistent; skeptical |

The table is the *classical* map. The *modern* map is the subject of §§3–6.

---

## 3. Goodman’s New Riddle

### 3.1 The riddle

Nelson Goodman’s *Fact, Fiction, and Forecast* (1955), Ch. 3, introduced the most important development in the problem of induction since Hume. The riddle is a *counterexample* to the *simple* account of confirmation (Ch. 40, §1.4).

**The definition.** A thing is **grue** if and only if it is green and examined before time $T$, or blue and not examined before $T$. (Take $T$ to be some future time, e.g., 2100.)

$$
\mathrm{Grue}(x) \leftrightarrow [(\mathrm{Green}(x) \wedge \mathrm{ExaminedBefore}(x, T)) \vee (\mathrm{Blue}(x) \wedge \neg\mathrm{ExaminedBefore}(x, T))]
$$

**The riddle.** All emeralds observed so far have been green. All emeralds observed so far have also been grue (because they were green and examined before $T$). The evidence confirms both hypotheses:

- $H_1$: All emeralds are green.
- $H_2$: All emeralds are grue.

But the hypotheses make *different* predictions about the *next* emerald. $H_1$ predicts it will be green. $H_2$ predicts it will be *blue* — provided that the next emerald is examined *after* $T$ (if it is examined before $T$, the two hypotheses agree, which is why the divergence shows up only in the *future*). Goodman’s point is not that the hypotheses differ on every case, but that they differ on the cases beyond $T$, and that the evidence is silent about which of them to prefer.

**The problem.** The two hypotheses are *equally supported* by the evidence, but they make *incompatible* predictions. If both are confirmed, then the evidence confirms a contradiction. The *simple* account of confirmation — “a hypothesis is confirmed by its instances” — is *false*.

### 3.2 The structure of the problem

Goodman’s riddle is *deeper* than Hume’s, and in a specific sense.

- **Hume’s problem** is about the *justification* of induction: even if the future resembles the past, we cannot *justify* the inference.
- **Goodman’s problem** is about the *form* of the inference: even if the future resembles the past, there are *infinitely many* ways of describing the resemblance, and the evidence does not *select* among them.

Goodman’s own formulation: the problem is not “why induct?” but “which inductions?” The *rules* of induction must select the *projectible* predicates — the ones that support counterfactuals and predictions — from the *non-projectible* ones. “Green” is projectible; “grue” is not. The question is: *what makes a predicate projectible?*

### 3.3 Goodman’s solution: entrenchment

Goodman’s answer is **entrenchment**: a predicate is projectible if it has been *used* in successful inductions in the past.

**The argument.** The predicates that have been *entrenched* in the language — “green,” “blue,” “hot,” “heavy” — are the ones that have *worked* in prediction and explanation. The predicates that have not been entrenched — “grue,” “bleen” — are *artificial*, and they are not projectible.

**The argument stated.**

$$
\begin{array}{ll}
1. & \text{A predicate is projectible iff it is entrenched.} \\
2. & \text{A predicate is entrenched iff it has been used in successful inductions.} \\
\hline
3. & \therefore \text{Projectibility is a historical property of predicates.}
\end{array}
$$

**The advantage.** The solution is *naturalistic*: it grounds projectibility in the *actual practice* of science, not in a *mysterious* faculty or a *metaphysical* essence. The solution is *history-sensitive*: it explains why “green” is projectible and “grue” is not — because “green” has a history, and “grue” does not.

### 3.4 The objections

**(i) The “sociology” objection.** Entrenchment is a *sociological* fact, not an *epistemic* one. Why should the *history of usage* track the *truth*? The entrenchment of “green” is a fact about our language, not a fact about the world. The solution is *descriptive*, not *normative*.

**(ii) The “new predicates” objection.** Science *introduces* new predicates — “quark,” “gene,” “electron,” “black hole” — which are not entrenched at their introduction, but which are *projectible*. The solution cannot explain *why* a new predicate is projectible from the moment it is introduced. (Goodman’s reply: the new predicates are *definable* in terms of entrenched predicates; the entrenchment is *inherited*. But the reply is *ad hoc*, and it does not handle *radically* new predicates.)

**(iii) The “circularity” objection.** Entrenchment is defined in terms of *successful projection*, and successful projection is defined in terms of *entrenchment*. The circle is *vicious*: the solution assumes what it is supposed to explain.

**(iv) The “relativism” objection.** If projectibility is relative to a *language*, and languages are *conventional*, then projectibility is *relative*, and the *objectivity* of induction is lost. Goodman’s later work (*Ways of Worldmaking*, 1978) embraces this: “we make worlds” by choosing the *versions* that are *right*, and *rightness* is a matter of *fit*, not of *correspondence*. Whether this is a *solution* or a *capitulation* is contested.

### 3.5 The responses

**(i) The “natural kinds” response (Quine 1969).** The projectible predicates are the ones that *correspond to natural kinds* — the *real* divisions in nature. The response is *realist*: the projectibility is grounded in the *structure of the world*, not in the *history of the language*. The problem: the *natural kinds* are themselves *contested*, and the *reduction* of projectibility to natural kinds is a *promissory note* (Ch. 39, §3).

**(ii) The “causal” response.** The projectible predicates are the ones that *figure in causal laws* (Ch. 18, §7). The response is *naturalistic*: the projectibility is grounded in the *causal structure* of the world. The problem: the *causal* response *presupposes* the *inductive* inference (the causal laws are *discovered* by induction), and the circle returns.

**(iii) The “Bayesian” response.** The projectibility of a predicate is a *matter of the prior probability* of the hypotheses that use it. “Green” hypotheses have *higher priors* than “grue” hypotheses, because the *simplicity* of the predicate is a *guide* to its prior probability. The response is *formal*, and it *relocates* the problem to the priors (§5).

**(iv) The “pragmatic” response.** The projectible predicates are the ones that *serve our purposes* — prediction, explanation, control. The response is *pragmatic*, and it *gives up* the *epistemic* justification (Ch. 32, §4).

### 3.6 The status of the riddle

Goodman’s riddle is *not solved*, and it is *not likely to be*. The riddle has *shifted* the problem of induction from the *justification* of the inference to the *selection* of the predicates, and the *selection* is as hard as the *justification*.

The riddle’s enduring contribution is *negative*: it shows that the *simple* account of confirmation is *false*, and that the *form* of inductive inference is *not* given by the evidence alone. The *positive* contribution — entrenchment, natural kinds, causal structure — is *promising*, but *incomplete*.

The riddle’s *methodological* lesson is the one Ch. 3, §1.6 stated: **a theory that has to be patched is on the defensive**. The simple account of confirmation was patched by entrenchment, and the patch generated the *new* problem of *which* predicates are entrenched. The problem is *structural*, not *local*.

---

## 4. The Bayesian Framework

### 4.1 The axioms

The **Bayesian framework** is the most important formal tool in contemporary epistemology. It represents the subject’s *degrees of belief* (credences) as a probability function.

**The probability axioms** (Kolmogorov):

$$
\begin{array}{ll}
(\mathrm{P1}) & P(A) \geq 0 \text{ for all } A. \\
(\mathrm{P2}) & P(\Omega) = 1, \text{ where } \Omega \text{ is the sure event.} \\
(\mathrm{P3}) & P(A \cup B) = P(A) + P(B) \text{ if } A \cap B = \emptyset.
\end{array}
$$

**The theorems.**

$$
\begin{array}{ll}
(\mathrm{T1}) & P(\neg A) = 1 - P(A). \\
(\mathrm{T2}) & P(A \cup B) = P(A) + P(B) - P(A \cap B). \\
(\mathrm{T3}) & \text{(Total probability)} \quad P(B) = \sum_i P(B \mid A_i) P(A_i), \text{ for a partition } \{A_i\}.
\end{array}
$$

### 4.2 Conditional probability and Bayes’ theorem

**Conditional probability** is defined as:

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}, \quad \text{provided } P(B) > 0.
$$

**Bayes’ theorem** follows:

$$
P(H \mid E) = \frac{P(E \mid H) P(H)}{P(E)}.
$$

In the *hypothesis-testing* context:

- $P(H)$ is the **prior**: the credence in $H$ before the evidence.
- $P(E \mid H)$ is the **likelihood**: the probability of the evidence given the hypothesis.
- $P(E)$ is the **marginal likelihood** (or *evidence*): the probability of the evidence under all hypotheses.
- $P(H \mid E)$ is the **posterior**: the credence in $H$ after the evidence.

The theorem is the *engine* of Bayesian confirmation: it says how the evidence *should* change the credence.

### 4.3 Conditionalization

The **diachronic** norm of Bayesianism is **conditionalization**: when the subject learns $E$ (and nothing else), her new credence in $H$ should be her old conditional credence:

$$
P_{\text{new}}(H) = P_{\text{old}}(H \mid E).
$$

The rule is the *dynamic* counterpart of the *static* axioms. It says how credences should *change* over time.

**The Dutch book argument** (Lewis 1999; Teller 1973; van Fraassen 1984). The argument is a *pragmatic* justification of conditionalization:

$$
\begin{array}{ll}
1. & \text{If a subject’s credences violate conditionalization, a bookie can construct a set of bets that guarantees a sure loss (a “Dutch book”) regardless of the truth of the propositions.} \\
2. & \text{A rational subject will not accept a sure loss.} \\
\hline
3. & \therefore \text{A rational subject’s credences satisfy conditionalization.}
\end{array}
$$

The **synchronic** version (Ramsey, de Finetti) argues the same for the probability axioms: a subject whose credences violate the axioms can be “Dutch-booked.”

**The objections.**

**(i) The “pragmatic” objection.** The argument shows that *if* you want to avoid a sure loss, you should be coherent. But *why* should you want to avoid a sure loss? The *epistemic* rationality of credences is not the same as the *pragmatic* rationality of betting. (The argument is a *pragmatic* justification, not an *epistemic* one.)

**(ii) The “accuracy” response** (Joyce 1998; Pettigrew 2016). The *accuracy-first* program argues that credences should be *accurate* — close to the truth — and that the *probabilistic* credences are the *only* ones that cannot be *accuracy-dominated*: any departure from the axioms can be beaten on accuracy by a credence function that respects them. The argument is *epistemic* rather than *pragmatic*, and it is one of the most important developments in the field in the last few decades. (The argument is contested; see the essays in Pettigrew and Weisberg 2019.)

**(iii) The “conditionalization” objection.** Conditionalization is *not* the only update rule. **Jeffrey conditionalization** (Jeffrey 1965) handles the case where the subject’s evidence is *uncertain*; **Adams conditioning** handles the case where the evidence is a *conditional*; and the **“reflection” principle** (van Fraassen 1984) adds a constraint on *future* credences. The rule is *contested*, and the *choice* among the rules is a *substantive* issue.

### 4.4 Bayesian confirmation

The Bayesian account of **confirmation**:

$$
E \text{ confirms } H \iff P(H \mid E) > P(H).
$$

Equivalently:

$$
E \text{ confirms } H \iff P(E \mid H) > P(E \mid \neg H).
$$

The evidence confirms the hypothesis if it is *more likely* under the hypothesis than under its negation.

**The properties.**

- **Confirmation is relative to the prior**: the same evidence can confirm one hypothesis and disconfirm another, depending on the priors.
- **Confirmation is a matter of degree**: the *amount* of confirmation is the *difference* between the posterior and the prior.
- **Confirmation is not *deductive*: the evidence does not *entail* the hypothesis; it *raises its probability*.

**The application to induction.** The Bayesian framework *reconstructs* induction as a *sequence* of conditionalizations. The “inductive principle” is *not* a premise; it is *encoded* in the *prior* and the *likelihood*. The *justification* of induction becomes the *justification* of the prior, which is the subject of §5.

### 4.5 The ravens paradox

A *test case* for the Bayesian framework, and for confirmation theory generally.

**Hempel’s paradox** (1945). The hypothesis $H$: “All ravens are black.” The evidence $E_1$: “This raven is black.” The evidence $E_2$: “This white shoe is white.” (Ch. 40, §1.2.)

By the *equivalence condition* (if $E$ confirms $H$, and $H$ is logically equivalent to $H'$, then $E$ confirms $H'$), $H$ is equivalent to $H'$: “All non-black things are non-ravens.” $E_2$ is an instance of $H'$ (a white shoe is a non-black thing that is a non-raven). So $E_2$ confirms $H$.

The conclusion is *counterintuitive*: a white shoe confirms “All ravens are black.”

**The Bayesian resolution.** The confirmation is *real* but *tiny*. The *likelihood* $P(E_2 \mid H)$ is *slightly* higher than $P(E_2 \mid \neg H)$: if all ravens are black, then a white object you observe is very slightly *more* likely to be a shoe and *less* likely to be a non-black raven. The *amount* of confirmation is *negligible*, because the *prior* probability of $E_2$ is *high* and the *ratio* is *near 1*.

The Bayesian resolution *dissolves* the paradox: the white shoe *does* confirm the hypothesis, but the confirmation is *so small* that it is *epistemically insignificant*. (The resolution is not *universally* accepted: some philosophers argue that the *equivalence condition* itself is the artificial assumption, and that confirmation is not a relation between a statement and a piece of evidence at all. Good (1967) pressed the Bayesian reply himself — the title of his note, *The White Shoe Is a Red Herring*, states the view that the confirmation is real but negligible — and the debate continues.)

---

## 5. The Problem of the Priors

### 5.1 The problem

The Bayesian framework *relocates* the problem of induction to the **priors**. The posterior is a *function* of the prior and the likelihood; the *justification* of the posterior depends on the *justification* of the prior. If the prior is *arbitrary*, the posterior is *arbitrary*, and the Bayesian framework does not justify *anything*.

The problem is the *Bayesian* form of Hume’s problem. Hume asked: how can experience justify the inference to the unobserved? The Bayesian asks: how can the prior be justified *without* experience? The *prior* is the *inductive principle* in *quantitative* form: it encodes the *weight* that the subject gives to the *uniformity* of nature.

### 5.2 Subjectivism

The **subjectivist** (de Finetti 1974; Savage 1954; Jeffrey 1965) response: the prior is *subjective*, and that is *fine*. The *only* constraint on the prior is *coherence* (the probability axioms). The *justification* of the prior is *not* an *epistemic* matter; it is a *personal* matter — the prior expresses the subject’s *beliefs*, and there is no *further* justification.

**The convergence theorems.** The subjectivist’s *consolation* is the *washing out* of the priors: as the evidence accumulates, the posteriors of *different* priors *converge*, provided the priors are *not* dogmatic (they do not assign probability 1 to a hypothesis that is false). The *limit* of the posterior is *independent* of the prior.

**The objections.**

**(i) The “short-run” objection.** The convergence is *asymptotic*: it holds in the *limit* of infinite evidence. Finite agents do not have infinite evidence, and the *short-run* posteriors *do* depend on the priors. The convergence theorem is *cold comfort* for *finite* inquirers.

**(ii) The “dogmatism” objection.** The convergence theorem requires the priors to be *non-dogmatic* (they must not assign probability 1 to a false hypothesis). But *some* priors *are* dogmatic, and the *requirement* of non-dogmatism is *itself* a *substantive* constraint that needs justification.

**(iii) The “no justification” objection.** The subjectivist *gives up* the *epistemic* justification of the prior. The framework *constrains* the *updating*, but it does not *justify* the *starting point*. The problem of induction is *not solved*; it is *relocated*.

### 5.3 Objectivism

The **objectivist** (Jeffreys 1939; Jaynes 2003; Williamson 2010) response: the prior can be *determined* by *principles of rationality*, not by *subjective choice*.

**The principle of indifference.** If there is *no evidence* favoring one hypothesis over another, the hypotheses should be assigned *equal* probability.

$$
P(H_1) = P(H_2) = \cdots = P(H_n) = \frac{1}{n}.
$$

**The maximum entropy principle.** The prior should be the *maximum entropy* distribution consistent with the evidence — the *least informative* distribution, in the sense of *information theory*.

**The objections.**

**(i) Bertrand’s paradox.** The principle of indifference is *partition-dependent*: the same situation can be described by *different* partitions, and the principle assigns *different* probabilities to the *same* hypothesis, depending on the partition. (The classic example: a circle, a random chord, the probability that the chord is longer than the side of the inscribed equilateral triangle — the answer is $1/3$, $1/2$, or $1/4$, depending on how the chord is “chosen.”)

**(ii) The “language-dependence” objection.** The maximum entropy prior is *language-dependent*: the *entropy* of a distribution is defined relative to a *measure*, and the measure is fixed by the *vocabulary* in which the hypotheses are stated. The *same* hypothesis can be stated in *different* vocabularies, and the *entropy* is *different*. (This is the *Bayesian* version of Goodman’s riddle.)

**(iii) The “no neutral prior” objection.** There is *no* prior that is *genuinely* neutral. Every prior *encodes* some *assumption* about the world — about *simplicity*, *uniformity*, *natural kinds* — and the assumption is *not* derived from the evidence. The *objectivist* prior is *not* neutral; it is *a* prior, with *a* set of assumptions.

### 5.4 The residue

The problem of the priors is *unresolved*, and it is the *residue* of the problem of induction within the Bayesian framework.

**What the framework *does* provide.**

- A *formal* account of *confirmation*, *evidence*, and *update*.
- A *normative* standard for *consistency* (the axioms) and *dynamic coherence* (conditionalization).
- A *language* for *comparing* hypotheses and *quantifying* uncertainty.

**What the framework *does not* provide.**

- A *justification* of the *prior*.
- A *solution* to the *problem of induction*.
- A *guarantee* that the posterior is *true*.

The framework is a *tool*, not a *foundation*. It *organizes* the problem; it does not *solve* it. The *honest* position is the one Ch. 4, §3.6 recommended: *specify the costs*, *specify the alternatives*, and *calibrate the confidence*.

### 5.5 The meta-induction

A *recent* development: the **meta-induction** (Schurz 2008, 2019). The argument is *not* a justification of a *particular* inductive method; it is a justification of the *strategy* of *following the most successful predictor*.

**The argument.**

1. Consider a *population* of prediction methods (including induction, counter-induction, and any other method).
2. The *meta-inductivist* predicts what the *most successful* method predicts.
3. **Theorem**: for every possible world, there is a meta-inductivistic strategy whose *long-run* success is (approximately) *optimal* among all the accessible methods in that world, and which dominates the success of every non-inductive strategy.
4. Therefore, there is a strategy that is *universally optimal* — a strategy that is the *best* strategy *whatever* the uniformity of nature.

(The meta-induction of Schurz is not to be confused with the *pessimistic meta-induction*, a different argument about scientific realism; see the Optional threads below.)

**The significance.** The meta-induction is one of the *strongest* responses to Hume in the contemporary literature, because it does not *presuppose* the uniformity of nature. The *theorem* is a *mathematical* result, and it is *independent* of the *metaphysics* of induction.

**The limitations.** (i) The theorem is *asymptotic*: it holds in the *long run*, and the *short-run* success is *not* guaranteed. (ii) The theorem is *comparative*: it shows that the meta-inductivist is *no worse* than the best method, not that it is *good*. (iii) The theorem *presupposes* that the *success* of the methods is *measurable* and *comparable*, and the presupposition is *substantive*.

The meta-induction is *promising*, and it is the most important *new* idea in the field. Whether it is a *solution* to Hume is contested.

---

## 6. Inference to the Best Explanation

### 6.1 The structure

**Inference to the best explanation** (IBE) is the ampliative inference from the fact that a hypothesis *explains* the evidence to the conclusion that the hypothesis is *true* (or *probably true*).

**The schema.**

$$
\begin{array}{ll}
1. & H_1 \text{ explains } E \text{ better than any available alternative.} \\
2. & \text{If a hypothesis explains } E \text{ better than any available alternative, it is probably true.} \\
\hline
3. & \therefore H_1 \text{ is probably true.}
\end{array}
$$

The schema was introduced in Ch. 2, §5.3, and it is the subject of the most important debate in the philosophy of science.

### 6.2 Lipton’s account

Peter Lipton (*Inference to the Best Explanation*, 1991/2004) offers the most influential account.

**The “loveliest” explanation.** The best explanation is the *loveliest*: the one that provides the *most understanding*. The *likeliest* explanation (the one most probably true) is *not* always the *loveliest*, and the *gap* between them is the *problem* of IBE.

**The two models.**

| Model | What it infers | What it selects |
|---|---|---|
| **Likeliest** | The most probable explanation | The hypothesis with the highest posterior |
| **Loveliest** | The most explanatory explanation | The hypothesis with the most understanding |

**The argument.** The *loveliest* explanation is a *guide* to the *likeliest*: the *explanatory virtues* (simplicity, scope, mechanism, unification) are *reliable indicators* of the *posterior probability*. The *guide* is *fallible*, but it is *the best we have*.

**The problem.** The *guide* relation is *not* a *justification*. The *loveliest* explanation may be *false*, and the *inference* from the *loveliness* to the *likelihood* is *itself* an *inductive* inference — which is *precisely* what IBE is supposed to *justify*. The *circularity* is the *central* problem of IBE.

### 6.3 The circularity problem

The *circularity* has two forms.

**(i) The “epistemic” circle.** IBE is justified by its *track record* — it has *worked* in the past. But the *track record* is an *inductive* argument (the future will resemble the past), and the *inductive* argument is *justified* by IBE. The circle is *vicious*.

**(ii) The “explanatory” circle.** The *explanatory virtues* are *defined* by their *role* in IBE. The *simplicity* of a hypothesis is *not* an *independent* property; it is the property that *makes the hypothesis explanatory*. The *definition* is *circular*, and the *justification* is *vacuous*.

**The responses.**

**(i) The “external” justification.** IBE is justified by *something else* — *pragmatic* success, *evolutionary* history, or *reliability*. The justification is *not* an IBE, and the circle is *broken*. (The problem: the *external* justification is *itself* a *philosophical* thesis, and it is *contested*.)

**(ii) The “internal” justification.** IBE is *self-justifying*: the *explanatory virtues* are *constitutive* of *rationality*, and the *demand* for an *external* justification is *incoherent*. (This is the *Strawsonian* strategy, and it has the *same* problems as the *Strawsonian* response to Hume.)

**(iii) The “Bayesian” response.** IBE is *reducible* to Bayesianism: the *explanatory virtues* are *proxies* for the *likelihood* $P(E \mid H)$, and the *best explanation* is the one with the *highest posterior*. The *circularity* is *dissolved*, because the *justification* is *Bayesian*, not *explanatory*. (The problem: the *reduction* is *contested*; see §6.4.)

### 6.4 The Bayesian response and its critics

The **Bayesian** response to IBE is the most important *reduction* in the field.

**The argument** (Lipton 2004; Okasha 2000). The *explanatory virtues* are *correlated* with the *likelihood*:

- **Simplicity**: simpler hypotheses have *higher priors* (a *contested* claim; the *Bayesian* has no *independent* justification for the simplicity prior).
- **Scope**: hypotheses with *greater scope* have *greater likelihood* (they predict *more* of the evidence).
- **Mechanism**: hypotheses with a *mechanism* have *greater likelihood* (the mechanism *explains* the evidence).

The *correlation* is *not* an *identity*. The *explanatory virtues* are *not* *sufficient* for the *posterior*, and the *Bayesian* reconstruction is *not* a *reduction*.

**The qualification** (Weisberg 2009). The compatibility of IBE and Bayesianism is *not* free. On Weisberg’s view, *subjectivist* Bayesianism can accommodate IBE only if IBE is made *subservient* to conditionalization in a way that robs IBE of much of its substance and interest; the *objectivist* Bayesian is the better partner.

**The critics** (Douven 1999; Cabrera 2017) argue that IBE is *not* reducible:

- **The “explanatory” content**: the *explanatory* relation is *not* a *probabilistic* relation. The *understanding* provided by an explanation is *not* captured by the *posterior*.
- **The “loveliest” problem**: the *loveliest* explanation may be *less* likely than a *less lovely* one. The *Bayesian* reconstruction *cannot* explain *why* we should prefer the *loveliest*.
- **The “empirical” evidence**: some *scientific* inferences are *explanatory* but *not* *Bayesian* — e.g., the *inference* to the *existence* of *unobservable* entities (Ch. 40, §5).
- **The “residue”**: some explanatory considerations have *no* place in the Bayesian framework at all. Cabrera (2017) argues that they belong to a *context of pursuit* — they determine whether a hypothesis is *worth pursuing* rather than whether it is *credible*.

The *debate* is *unresolved*, and it is *one* of the *deepest* in the *philosophy of science*.

### 6.5 The van Fraassen challenge

Bas van Fraassen (*The Scientific Image*, 1980, Ch. 5) offers the most *radical* challenge to IBE.

**The argument.**

1. The *explanatory virtues* (simplicity, scope, mechanism) are *pragmatic*: they make a theory *useful*, *attractive*, or *easy to use*.
2. *Pragmatic* virtues are *not* *epistemic*: they do not *increase* the *probability* that a theory is *true*.
3. Therefore, IBE is *not* a *truth-conducive* inference; it is a *heuristic* for *theory choice*.

**The constructive empiricism.** Van Fraassen’s *positive* view: science aims at *empirical adequacy* (saving the phenomena), not at *truth*. The *unobservable* entities are *not* required by the aim of science: the scientist may *accept* them without *believing* in them (Ch. 40, §5.7). The aim of science is *neither* *explanation* nor *prediction*; it is *empirical adequacy*, and *prediction* is an indispensable *by-product* rather than the goal.

**The objections.**

**(i) The “inference” objection.** The *constructive empiricist* *herself* uses IBE: the *inference* from the *success* of science to the *adequacy* of the theory is an *explanatory* inference. The *position* is *self-undermining*.

**(ii) The “empirical” objection.** The *explanatory virtues* *do* seem to *track* the *truth*: the *history* of science is a *history* of *explanatory* theories that *turned out* to be *true* (or *approximately true*). The *correlation* is *not* *perfect*, but it is *not* *zero*.

**(iii) The “pragmatic” objection.** The *distinction* between *pragmatic* and *epistemic* virtues is *not* *sharp*. The *simplicity* of a theory *is* *epistemic* (Ch. 4, §3.3): it is a *guide* to *truth*, *because* the *world* is *simple*. The *van Fraassen* *dichotomy* is *contested*.

The *debate* is *unresolved*, and it is *the* *central* *disagreement* in the *philosophy of science*.

### 6.6 IBE and induction

The *relation* between IBE and induction is *close* and *contested*.

**The reductionist view.** IBE is a *form* of *induction*: the *inference* from the *explanatory success* of a theory to its *truth* is an *inductive* inference, *justified* by the *track record* of *explanatory* theories. The *problem*: the *reduction* *makes* IBE *vulnerable* to the *problem* of *induction*, and it *does not* *solve* it.

**The non-reductionist view.** IBE is a *distinct* *ampliative* inference: it is *not* *justified* by *induction*, and it is *not* *reducible* to it. The *problem*: the *non-reductionist* *owes* an *account* of *what* *justifies* IBE, and the *account* is *not* *available*.

**The pessimistic view.** IBE is *neither* *reducible* *nor* *justified*: it is a *heuristic* that *works* in *practice*, and the *demand* for a *justification* is *misplaced*. (This is the *quietist* *response*, and it is *honest* but *unsatisfying*.)

The *honest* position: IBE is *indispensable* in *science* and in *philosophy*, and it is *not* *justified* by a *non-circular* *argument*. The *justification* of IBE is *the same* *problem* as the *justification* of *induction*, and the *solution* is *not* *available*.

---

## 7. Statistical Reasoning and the Everyday Epistemology of Evidence

### 7.1 The base-rate fallacy

The *most* *important* *practical* *consequence* of the *Bayesian* *framework* is the *analysis* of *statistical* *reasoning*.

**The base-rate fallacy** (Kahneman & Tversky 1973). *Subjects* *neglect* the *base rate* (the *prior probability*) and *focus* on the *likelihood* (the *diagnostic* information). The *classic* *example*:

> A *taxi* *cab* *was* *involved* in a *hit-and-run* *accident* at *night*. Two *cab* *companies* *operate* in the *city*: the *Green* *Cab* *Company* (85% of the *cabs*) and the *Blue* *Cab* *Company* (15%). A *witness* *identified* the *cab* as *Blue*. The *court* *tested* the *witness’s* *reliability* under the *same* *conditions* and *concluded* that the *witness* *correctly* *identified* the *color* 80% of the *time* and *incorrectly* 20% of the *time*. What is the *probability* that the *cab* *was* *Blue*?

**The Bayesian answer.**

$$
P(\text{Blue} \mid \text{witness says Blue}) = \frac{P(\text{witness says Blue} \mid \text{Blue}) P(\text{Blue})}{P(\text{witness says Blue})}.
$$

$$
P(\text{witness says Blue}) = (0.80)(0.15) + (0.20)(0.85) = 0.12 + 0.17 = 0.29.
$$

$$
P(\text{Blue} \mid \text{witness says Blue}) = \frac{(0.80)(0.15)}{0.29} = \frac{0.12}{0.29} \approx 0.41.
$$

The *posterior* is *41%*, *not* *80%*. The *witness* is *reliable*, but the *base rate* *dominates*: the *Green* *cabs* are *so* *numerous* that the *posterior* is *still* *more likely* *Green*.

**The *lesson*.** The *intuitive* *answer* (80%) is *wrong*. The *correct* *answer* requires the *Bayesian* *calculation*, and the *calculation* is *not* *intuitive*. The *base-rate fallacy* is the *practical* *form* of the *problem* of the *priors*: the *prior* is *not* *optional*, and the *failure* to *include* it *distorts* the *posterior*.

### 7.2 The prosecutor's fallacy

The **prosecutor’s fallacy** is the *converse* *error*: the *confusion* of $P(E \mid H)$ with $P(H \mid E)$.

**The example.** A *prosecutor* *argues*: “The *probability* that a *random* *person* would *match* the *DNA* *evidence* is *1 in a million*. Therefore, the *probability* that the *defendant* is *innocent* is *1 in a million*.”

The *fallacy*: the *prosecutor* *confuses* the *likelihood* $P(\text{match} \mid \text{innocent})$ with the *posterior* $P(\text{innocent} \mid \text{match})$. The *posterior* depends on the *prior* — the *base rate* of *innocence* in the *population* — and the *prior* is *usually* *high*.

**The calculation.** Suppose the *prosecutor’s* figure is right: $P(\text{match} \mid \text{innocent}) = 10^{-6}$, and $P(\text{match} \mid \text{guilty}) = 1$. If the *prior* *probability* of *guilt* is *1 in 10* (for a *defendant* *selected* *by* *other* *evidence*), the *posterior* is:

$$
P(\text{guilty} \mid \text{match}) = \frac{P(\text{match} \mid \text{guilty})\, P(\text{guilty})}{P(\text{match} \mid \text{guilty})\, P(\text{guilty}) + P(\text{match} \mid \text{innocent})\, P(\text{innocent})} = \frac{(1)(0.1)}{(1)(0.1) + (10^{-6})(0.9)} \approx \frac{0.1}{0.1 + 10^{-6}} \approx 0.99999.
$$

The *posterior* is *high*, but *only* *because* the *prior* is *high*. If the *defendant* is *selected* at *random*, so that the *prior* *probability of guilt* is *1 in a million*, the *posterior* is *only* *50%*: the DNA evidence is then *equally* likely under either hypothesis.

**The legal consequence.** The *prosecutor’s fallacy* has *led* to *wrongful* *convictions* (the *Sally Clark* case, the *Lucia de Berk* case, and *many* *others*). The *Royal Statistical Society* (2001) *issued* a *public* *warning* about the *misuse* of *statistics* in *court*. The *fallacy* is *not* a *mere* *academic* *curiosity*; it is a *cause* of *injustice*.

### 7.3 The everyday epistemology of evidence

The *Bayesian* *framework* is *not* *only* a *tool* for *statisticians*; it is a *model* of *everyday* *reasoning*.

**The heuristics.** The *heuristics* *identified* by *Tversky* and *Kahneman* — *availability*, *representativeness*, *anchoring* — are *fast* and *frugal*, and they are *usually* *reliable*. They are *not* *irrational*: they are *adapted* to the *environment* in which *human* *beings* *evolved*. The *question* is *whether* they are *reliable* in the *modern* *environment*, where the *statistical* *structure* is *different*.

**The “frequency” *format*** (Gigerenzer 2002). The *base-rate* *fallacy* *disappears* when the *problem* is *presented* in *frequencies* rather than *probabilities*. The *example*: “Out of 1,000 *people*, 10 have the *disease*. Of the 10, 8 *test* *positive*. Of the 990 *without* the *disease*, 99 *test* *positive*. What is the *probability* that a *person* who *tests* *positive* has the *disease*?” The *frequency* *format* *makes* the *Bayesian* *calculation* *intuitive*: the *answer* is $8/(8+99) \approx 7.5\%$.

**The *lesson*.** The *rationality* of *everyday* *reasoning* is *not* a *matter* of *innate* *ability*; it is a *matter* of *representation*. The *same* *problem* can be *easy* or *hard* *depending* on the *format*, and the *format* is *teachable*. The *epistemic* *virtue* is *not* “*be* *rational*”; it is “*learn* the *formats* that *make* *rationality* *possible*.”

### 7.4 The rationality debate

The *empirical* *findings* have *generated* a *philosophical* *debate* about *rationality*.

| Position | Claim | Proponents |
|---|---|---|
| **The “heuristics and biases” *program*** | Humans are *systematically* *irrational*; the *heuristics* *produce* *predictable* *errors* | Kahneman, Tversky |
| **The “ecological” *program*** | Humans are *ecologically* *rational*; the *heuristics* are *adapted* to the *environment* | Gigerenzer, Todd |
| **The “dual-process” *program*** | Humans have *two* *systems*: a *fast*, *automatic* *system* and a *slow*, *deliberative* *system* | Kahneman, Stanovich |
| **The “bounded” *program*** | Rationality is *bounded* by *computational* *limits*; the *norms* must be *feasible* | Simon |

The *debate* is *unresolved*, and it is *connected* to the *theory* of *justification* (Ch. 8, §5): if *justification* requires *reliability*, and the *heuristics* are *reliable* in the *ecologically* *relevant* *environment*, then the *heuristics* are *justified*. If *justification* requires *accuracy* in the *modern* *environment*, the *heuristics* are *not* *justified*.

**The *epistemic* *lesson*.** The *rationality* of *everyday* *reasoning* is *not* a *single* *property*; it is a *relation* between the *agent*, the *environment*, and the *norms*. The *Bayesian* *framework* is a *normative* *ideal*, and the *heuristics* are *approximations* to the *ideal*. The *question* is *whether* the *approximations* are *good* *enough* — and the *answer* *depends* on the *stakes* (Ch. 7, §6.3).

### 7.5 The *workshop*: the *medical* *test*

A *worked* *example* that *combines* the *Bayesian* *framework* with the *base-rate* *fallacy*.

**The *problem*.** A *disease* affects *1* in *1,000* *people*. A *test* is *99%* *sensitive* (it *detects* the *disease* in *99%* of *cases*) and *95%* *specific* (it *correctly* *identifies* *healthy* *people* in *95%* of *cases*). A *person* *tests* *positive*. What is the *probability* that she has the *disease*?

**The *Bayesian* *calculation*.**

$$
P(D \mid +) = \frac{P(+ \mid D) P(D)}{P(+ \mid D) P(D) + P(+ \mid \neg D) P(\neg D)}.
$$

$$
P(D \mid +) = \frac{(0.99)(0.001)}{(0.99)(0.001) + (0.05)(0.999)} = \frac{0.00099}{0.00099 + 0.04995} \approx \frac{0.00099}{0.05094} \approx 0.0194.
$$

The *posterior* is *1.94%* — *less* than *2%*.

**The *lesson*.** The *test* is *highly* *accurate* (99% *sensitive*, 95% *specific*), but the *posterior* is *low*, because the *base rate* is *low*. The *intuitive* *answer* (“the *test* is *99%* *accurate*, so the *probability* is *99%*”) is *wrong* by a *factor* of *50*. The *base-rate* *fallacy* is *not* a *rare* *error*; it is the *default* *error*.

**The *practical* *consequence*.** The *medical* *test* *example* is *routinely* *misused* in *screening* *programs* and in *public* *health* *communication*. The *correct* *interpretation* of a *positive* *test* *requires* the *prior* — and the *prior* is *the* *base* *rate*, which is *usually* *not* *stated*.

---

## 8. The State of the Debate

### 8.1 What is settled

- **Hume’s problem is real.** There is no *non-circular* justification of induction *in the foundationalist sense*.
- **The problem is structural.** It is not a *quirk* of *induction*; it is a *feature* of *ampliative* inference *in general* (Ch. 2, §2.4).
- **The Bayesian framework is the best formal tool.** It *organizes* the problem, *quantifies* the uncertainty, and *constrains* the update.
- **The problem of the priors is the residue.** The framework *relocates* the problem; it does not *solve* it.
- **IBE is indispensable.** It is the *engine* of *science* and *philosophy*, and it is *not* *reducible* to *Bayesianism* *without* *remainder*.
- **Statistical reasoning is a practical skill.** The *base-rate* *fallacy* and the *prosecutor’s* *fallacy* are *real*, *consequential*, and *teachable*.

### 8.2 What is open

- **The justification of the priors.** Is the prior *subjective* (de Finetti), *objective* (Jeffreys, Jaynes), or *neither* (the meta-induction)?
- **The relation between IBE and Bayesianism.** Is IBE *reducible* to the *Bayesian* *framework*, or is it a *distinct* *inference*?
- **The status of the explanatory virtues.** Are they *epistemic* (truth-conducive) or *pragmatic* (useful)?
- **The rationality of the heuristics.** Are the *heuristics* *rational* (ecological) or *irrational* (biases)?
- **The *solution* to Hume.** Is the *meta-induction* a *solution*, or is it a *sophisticated* *restatement* of the *problem*?

### 8.3 The methodological lesson

The chapter is a case study in the method of Part I.

- **Conceptual analysis** (§1 of Ch. 3) generated the *classical* distinction between *demonstrative* and *probable* reasoning.
- **Thought experiments** (§2 of Ch. 3) — the *grue* case, the *ravens* paradox, the *taxi* cab — are the *engine* of the debate.
- **Formalization** (§3 of Ch. 3) — the *probability* *axioms*, *Bayes’ theorem*, *conditionalization* — is essential for the *Bayesian* *framework*.
- **Reflective equilibrium** (§4 of Ch. 3) is the method by which the *intuitions* and the *theories* are adjusted.
- **Genealogy and debunking** (§5 of Ch. 3) — the *evolutionary* *debunking* of *induction* — is a *serious* *challenge*.
- **Negative capability** (§7 of Ch. 3) is the *response* to the *residue*: the *humility* to hold the *question* open.

The *honest* verdict: the problem of induction is a *field in transition*. The *classical* attempts are *untenable*; the *Bayesian* *framework* is *promising* but *incomplete*; the *meta-induction* is *the most important new idea*, and it is *contested*. The *unresolved* character is *instructive*: it shows what philosophical progress looks like — not a *settled answer*, but a *sharper understanding* of what the *question* is.

### 8.4 The dialectical map

| Position | Core claim | Strength | Weakness |
|---|---|---|---|
| **Humean skepticism** | Induction is unjustified | *Honest* about the *circle* | *No* *guidance* for *practice* |
| **Mill** | The uniformity principle is the foundation | *Systematic* | *Circular* |
| **Reichenbach** | Pragmatic vindication | *Robust* | *Conditional*; the *long run* |
| **Strawson** | Analytic dissolution | *Elegant* | *Verbal* |
| **Popper** | Falsificationism | *Consistent* | *No* *knowledge* of the *unobserved* |
| **Goodman** | Entrenchment | *Naturalistic* | *Sociological*; *circular* |
| **Bayesianism** | The prior + the likelihood | *Formal*; *normative* | *Relocates* the *problem* |
| **Meta-induction** | The optimal *strategy* | *Universal* | *Asymptotic*; *contested* |
| **IBE** | The best explanation | *Indispensable* | *Circular*; *not* *reducible* |

The *table* is a *map*, not a *verdict*. The *reader* who wants to *choose* a *position* must decide which *cost* is *acceptable* — and the *decision* is a *philosophical* *argument*.

---

## Optional threads

Cross-cutting material, for the reader who wants to go deeper.

**1. The *pessimistic* *meta-induction*.** The *history* of *science* is a *history* of *successful* *theories* that *turned out* to be *false* (Ch. 40, §5.3). The *pessimistic* *meta-induction* *argues* that *our* *current* *theories* are *probably* *false* *too*. The *argument* is a *form* of *induction* applied to *science* *itself*, and it is the *strongest* *challenge* to *scientific* *realism*. (It is not to be confused with the *meta-induction* of Schurz, §5.5 above, which is a *different* argument with a *different* aim.)

**2. The *problem* of *old* *evidence*.** The *Bayesian* *framework* *cannot* *confirm* a *hypothesis* *that* *entailed* the *evidence* *in* *advance* (Glymour 1980; Ch. 40, §1.5). The *problem* is *acute* for *scientific* *theories* that *predict* *known* *facts*, and the *solutions* (the *“no* *alternatives”* *response*, the *“historically* *situated”* *response*) are *contested*.

**3. The *problem* of *Newcomb*.** The *decision* *theory* *analogue* of *the* *problem* of *induction*: *causal* *decision* *theory* and *evidential* *decision* *theory* *give* *different* *advice* in *Newcomb’s* *problem*, and the *choice* *depends* on the *theory* of *induction* (the *decision* *rules* are set out in Ch. 55, §7.5).

**4. Non-Western *epistemologies* of *induction*.** The *Indian* *pramāṇa* *tradition* developed a *sophisticated* *theory* of *inference* (*anumāna*), with a *five-membered* *syllogism* (*pañcāvayava*) and a *theory* of *vyāpti* (the *invariable* *concomitance*). The *debate* between the *Nyāya* *realists* and the *Buddhist* *nominalists* is a *version* of the *problem* of *induction*, and it is *worth* *studying* as a *systematic* *alternative* (Matilal 1986; Ganeri 2001).

**5. The *epistemology* of *AI*.** The *Bayesian* *framework* is the *foundation* of *machine* *learning* (the *Bayesian* *network*, the *variational* *inference*). The *philosophical* *questions* — the *justification* of the *prior*, the *interpretation* of the *posterior*, the *nature* of the *machine*’s *uncertainty* — are *the* *same* *questions* as the *classical* *ones*, and they are *newly* *urgent* (Ch. 29, §3).

---

## Summary

- **Hume’s problem** has two forms: the *epistemic* (induction is unjustified) and the *metaphysical* (there is no necessary connection in nature). The *epistemic* form is the *circle*: the uniformity principle cannot be justified without *presupposing* it. The *metaphysical* form is the *projection*: necessary connection is a *feeling* of the mind, not a *feature* of the world.
- **The classical attempts** — Mill, Reichenbach, Strawson, Popper — all *fail* in *characteristic* ways. Mill is *circular*; Reichenbach is *conditional*; Strawson is *verbal*; Popper is *skeptical*.
- **Goodman’s riddle** *deepens* the problem: the *evidence* does not *select* the *projectible* *predicates*. The *solution* (entrenchment) is *naturalistic* but *circular*, and the *new* *predicates* *problem* is *unresolved*.
- **The Bayesian framework** is the *best* *formal* *tool*. The *axioms*, *Bayes’ theorem*, and *conditionalization* *organize* the problem. The *justification* of the *framework* is *pragmatic* (Dutch book) or *epistemic* (accuracy). The *framework* *relocates* the problem to the *priors*.
- **The problem of the priors** is the *residue*. The *subjectivist* *response* (de Finetti) is *honest* but *unjustified*; the *objectivist* *response* (Jeffreys, Jaynes) is *ambitious* but *vulnerable* to *Bertrand’s* *paradox*. The *meta-induction* (Schurz) is the *most promising* *new* *response*, and it is *contested*.
- **IBE** is the *most important* *ampliative* *inference* in *science* and *philosophy*. Lipton’s *loveliest* *explanation*, the *circularity* *problem*, the *Bayesian* *reduction*, and the *van Fraassen* *challenge* are the *central* *issues*.
- **Statistical reasoning** is the *practical* *form* of the problem. The *base-rate* *fallacy*, the *prosecutor’s* *fallacy*, and the *frequency* *format* are the *key* *findings*. The *rationality* *debate* is *unresolved*, and the *epistemic* *lesson* is that *rationality* is a *skill* that can be *taught*.
- **The state of the debate**: the *classical* attempts are *untenable*; the *Bayesian* *framework* is *promising* but *incomplete*; the *meta-induction* is the *most important* *new* *idea*; the *problem* is *unresolved*.

---

## Study Questions

1. State Hume’s argument in *standard* form. Is it *valid*? Is it *sound*? What does the *answer* depend on?
2. Is the *uniformity* *principle* *necessary* for *induction*? What is the *best* *argument* for and *against*?
3. Evaluate Reichenbach’s *pragmatic* *vindication*. Is it a *justification* of *induction*, or a *bet* on *uniformity*?
4. Is Strawson’s *dissolution* a *solution* to the *problem* of *induction*? What is the *difference* between a *dissolution* and an *evasion*?
5. Does *falsificationism* *avoid* *induction*? What is the *role* of *induction* in *Popper’s* *account* of *testing*?
6. State Goodman’s *riddle*. Is *entrenchment* a *solution*? What are the *problems* with the *solution*?
7. State *Bayes’ theorem*. How does the *Bayesian* *framework* *reconstruct* *induction*? What is the *role* of the *prior*?
8. Is the *Dutch book* *argument* a *justification* of *probabilism*? What is the *accuracy* *argument*, and is it *better*?
9. Is the *prior* *subjective* or *objective*? What is the *best* *argument* for each *position*?
10. Is *inference* to the *best* *explanation* *reducible* to *Bayesianism*? What is the *strongest* *argument* for each *position*?
11. Is *van Fraassen’s* *constructive* *empiricism* *self-undermining*? What is the *role* of *IBE* in his *argument*?
12. What is the *base-rate* *fallacy*? Give an *example* and *calculate* the *posterior*. What is the *epistemic* *lesson*?
13. Is the *frequency* *format* a *solution* to the *base-rate* *fallacy*? What does it *show* about the *nature* of *rationality*?
14. “The problem of induction is *not* solved, but it is *relocated*.” Assess. Is *relocation* a form of *progress*?

---

## Further Reading

- **Primary**: David Hume, *An Enquiry Concerning Human Understanding* (1748), IV–V, XII; David Hume, *A Treatise of Human Nature* (1739), I.iv; Nelson Goodman, *Fact, Fiction, and Forecast* (1955), Ch. 3; John Stuart Mill, *A System of Logic* (1843), Book III.
- **On the classical responses**: Hans Reichenbach, *Experience and Prediction* (1938), Ch. 5; P. F. Strawson, *Introduction to Logical Theory* (1952), Ch. 9 (“Inductive Reasoning and Probability”); Karl Popper, *The Logic of Scientific Discovery* (1934/1959); Wesley Salmon, *The Foundations of Scientific Inference* (1967), for the survey.
- **On Goodman**: Goodman, *Fact, Fiction, and Forecast* (1955), Ch. 3; the essays in *Grue!: The New Riddle of Induction* (ed. Stalker, 1994); W. V. O. Quine, “Natural Kinds” (1969), in *Ontological Relativity and Other Essays* (1969).
- **On Bayesianism**: Richard Jeffrey, *The Logic of Decision* (1965); Bruno de Finetti, *Theory of Probability* (1974); Leonard Savage, *The Foundations of Statistics* (1954); James Joyce, “A Nonpragmatic Vindication of Probabilism” (1998); Richard Pettigrew, *Accuracy and the Laws of Credence* (2016); the essays in *The Oxford Handbook of Probability and Philosophy* (ed. Hájek and Hitchcock, 2014); and the essays in *The Open Handbook of Formal Epistemology* (ed. Pettigrew and Weisberg, 2019).
- **On the priors**: Harold Jeffreys, *Theory of Probability* (1939); E. T. Jaynes, *Probability Theory: The Logic of Science* (2003); Jon Williamson, *In Defence of Objective Bayesianism* (2010); the critique in Colin Howson and Peter Urbach, *Scientific Reasoning: The Bayesian Approach* (3rd ed., 2006).
- **On the meta-induction**: Gerhard Schurz, “The Meta-Inductivist’s Winning Strategy in the Prediction Game” (2008), and *Hume’s Problem Solved: The Optimality of Meta-Induction* (2019).
- **On IBE**: Peter Lipton, *Inference to the Best Explanation* (2nd ed., 2004); Bas van Fraassen, *The Scientific Image* (1980), Ch. 5; Igor Douven, “Inference to the Best Explanation Made Coherent” (1999), and “Abduction” in the *Stanford Encyclopedia of Philosophy*; Samir Okasha, “Van Fraassen’s Critique of Inference to the Best Explanation” (2000); Jonathan Weisberg, “Locating IBE in the Bayesian Framework” (2009); Frank Cabrera, “Can There Be a Bayesian Explanationism?” (2017); and the entry on “Inference to the Best Explanation” in the *Stanford Encyclopedia of Philosophy*.
- **On statistical reasoning**: Daniel Kahneman, Paul Slovic, and Amos Tversky (eds.), *Judgment under Uncertainty* (1982); Gerd Gigerenzer, *Reckoning with Risk* (2002); the literature on the *prosecutor’s* *fallacy* (Thompson and Schumann 1987; the Royal Statistical Society’s 2001 letter).
- **On the rationality debate**: Daniel Kahneman, *Thinking, Fast and Slow* (2011); Gerd Gigerenzer and Reinhard Selten (eds.), *Bounded Rationality: The Adaptive Toolbox* (2001); the essays in *Heuristics and Biases* (ed. Gilovich, Griffin, and Kahneman, 2002).
- **On non-Western inference**: B. K. Matilal, *Perception* (1986), and *The Character of Logic in India* (1998); Jonardon Ganeri, *Philosophy in Classical India* (2001), Chs. 3–4; the essays in *The Oxford Handbook of Indian Philosophy* (ed. Ganeri, 2017).

---

> *A closing note.* This chapter has followed the tradition’s oldest *empirical* problem — the justification of the inference from the observed to the unobserved — through the *classical* attempts, the *Goodmanian* *deepening*, the *Bayesian* *reconstruction*, and the *IBE* *alternative*. The result is *not* a *solution*, and it is *not* a *refutation* of the *problem*. It is a *clarification*: the problem is the *ampliative* *counterpart* of the *a priori* (Ch. 9), and the two are the *same* *problem* in *different* *domains*.

> *And a bridge.* The next chapter turns to *testimony* — the *social* source of *justification* that the tradition has *neglected*. If the *individual* sources (perception, memory, reason, induction) are *unable* to *justify* the *whole* of *knowledge*, the *social* source is *indispensable*. The *epistemology* of *testimony* is the *social* *form* of the *problem* of *induction*: the *trust* in *others* is the *trust* in the *uniformity* of *their* *cognition*. The next chapter examines the *reductionism* vs. *anti-reductionism* debate, the *epistemology* of *disagreement*, and the *epistemic* *injustice* that the *social* *turn* has *revealed*.
