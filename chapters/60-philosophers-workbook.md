# Appendix E — The Philosopher's Workbook

**What this appendix is.** The book's thesis is that philosophy is a *discipline* — a set of trainable operations, not a body of opinions. Parts I–VIII argued for that thesis. This appendix is where it becomes practice. It supplies six templates, a worked chain that runs a single problem through all six, fifty case studies across five domains, and a self-directed curriculum for using the whole apparatus without a teacher.

**What it is not.** Templates do not do philosophy; they prevent the most common ways of failing to do it. A reader who fills in every box and produces nothing worth reading has used the workbook exactly as a bad student uses a grammar book: correctly, and to no purpose. The templates are scaffolds for the *thinking*, and the thinking must be about something.

**The order of operations.** The six templates are meant to be chained in a fixed sequence, and the sequence is not arbitrary:

$$\text{isolate the question} \;\to\; \text{map the argument} \;\to\; \text{test the distinctions} \;\to\; \text{design the case} \;\to\; \text{press the objection} \;\to\; \text{write the analysis}$$

Skip a step and the later ones degrade in a predictable way. A badly isolated question produces a beautifully mapped argument for the wrong conclusion (the commonest failure in undergraduate essays). An untested distinction produces a thought experiment that does not isolate what it claims to isolate. An objection answered before it is stated in its strongest form produces a reply to a neighbor of the real problem. §E.7 shows the chain in operation.

---

## E.1 — Template 1: Question Isolation

**The principle.** Most philosophical failure is not bad argument but *unstable target*. A question that has not been isolated will drift during the analysis, so that the conclusion answers one question and the introduction announced another. Isolation is the discipline of fixing the target before firing.

### The four moves

| Move | What you do | What goes wrong without it |
|---|---|---|
| **1. Classify** | Assign the question a type: conceptual, normative, metaphysical, semantic, epistemic, meta-level, empirical-in-disguise | The question is answered by the wrong kind of evidence (a survey, a definition, a moral intuition) |
| **2. Contrast** | Specify what the question is *as opposed to*: what the rival answers are, and what would count as a third option | The question is treated as binary when it has four answers |
| **3. Expose presuppositions** | List what the question assumes; test each assumption | A false presupposition makes the question unanswerable, and you answer it anyway |
| **4. Fix the answer-form** | State what shape a satisfying answer must take, and what would count as settling it | You produce an answer that could not, even in principle, settle the question |

### The template

```plaintext
QUESTION (as posed):          ______________________________

1. CLASSIFY. This is a [conceptual / normative / metaphysical /
   semantic / epistemic / meta-] question, because the answer
   turns on ______________________.
   It is NOT a [other type] question, because ____________.

2. CONTRAST. The rival answers are:
   (a) ______________________
   (b) ______________________
   (c) ______________________  [the option everyone forgets]
   The question is not "___ or ___" but "___________".

3. PRESUPPOSITIONS.
   P1: ______________________  [true / contested / false?]
   P2: ______________________
   If P_ is false, the question becomes ____________ instead.

4. ANSWER-FORM. A satisfying answer must:
   (i)   ______________________
   (ii)  ______________________
   It would be settled by ______________________,
   and would NOT be settled by ______________________.

5. WORKING VERSION of the question (one sentence, answerable):
   ______________________
```

### Worked example: "Is AI conscious?"

**Naive form.** "Is AI conscious?" — a question with no stable target, which is why most discussions of it talk past each other.

**Move 1 (classify).** Genuinely mixed. Partly *conceptual* (what is consciousness?), partly *empirical* (does this system have the relevant properties?), partly *methodological* (what evidence would settle it?), and partly *normative* in its practical upshot (what may we do with it?). The most common error is to treat it as purely empirical and reach for a test — and then to discover that the test was a conceptual proposal in disguise.

**Move 2 (contrast).** The rival answers are not merely yes/no:
(a) Yes, and the functional facts suffice (functionalism);
(b) No — nothing functional suffices, so no current or near system has it (biological naturalism);
(c) The question is ill-formed because "consciousness" as used here has no determinate criterion (illusionism about the question, not the phenomenon);
(d) Yes, in proportion to integrated information, whatever the substrate ($\Phi$-based);
(e) We cannot know, and the correct response is a policy of precaution.

**Move 3 (presuppositions).** (i) That "consciousness" picks out one thing — contested (access vs. phenomenal, Ch. 24). (ii) That consciousness is substrate-independent or not — this is precisely the disputed premise, and it is frequently smuggled in. (iii) That there is a fact of the matter. If (iii) fails, the question becomes a normative one about how to treat systems under uncertainty, which is a different inquiry with a different method.

**Move 4 (answer-form).** A satisfying answer must (i) say what consciousness is such that the question has a determinate answer, and (ii) specify what would count as evidence. It would be settled by a theory with independent support plus a criterion of application; it would *not* be settled by behavioral indistinguishability alone (the Turing test point, Ch. 29), nor by the absence of a mechanism we happen to know.

**Move 5 (working version).** *"Given a functionalist account of consciousness, does the current evidence about large language models satisfy the criteria for access consciousness, and if not, what follows for our obligations toward them?"* — a question with a target, a method, and a scope.

### Failure modes

| Failure | Symptom | Repair |
|---|---|---|
| **Question-dodging** | The essay answers an adjacent, easier question | Write the question at the top of every page and check |
| **Question-shrinking** | A broad question is silently narrowed to a tractable one, and the narrowing is presented as the answer | State the narrowing explicitly as a stipulation |
| **Question-inflation** | A narrow question is answered with a grand theory | Ask what the question could possibly need |
| **Equivocation on the copula** | "Is X Y?" trades on *is* of identity, predication, and existence | Rewrite in the form "X is identical to Y," "$X$ has property $Y$," "$X$ exists" |
| **Empirical smuggling** | A normative question is answered with data | Classify before you collect |

**Exercise.** Take three questions — (a) "Is it wrong to eat meat?", (b) "Do numbers exist?", (c) "Is knowledge justified true belief?" — and run each through the five-step template. Then write the working version of each in a single sentence. (Expected difficulty: (b) and (c) are easier than (a), because the presuppositions are more visible.)

---

## E.2 — Template 2: Argument Mapping

**The principle.** An argument is not a list of assertions; it is a structure in which some propositions are offered as support for others. The mapping operation makes that structure explicit, which is the only way to find the *load-bearing premise* — the one premise that, if false, collapses the whole (Appendix C, §C.16.1).

### The five-step procedure

1. **Locate the conclusion.** One sentence; the thing the author wants you to believe.
2. **List the explicit premises.** Quote them. Do not paraphrase into your own view of them yet.
3. **Supply suppressed premises.** What must be true for the inference to work? Mark each as *supplied* and give the charity justification. Charity has limits: supply a premise only if the author would accept it, not one that makes the argument work.
4. **Test each inference node.** Does the conclusion follow from what is above it? Where the inference is deductive, state the form; where ampliative, state what would make it strong.
5. **Mark the load-bearing premise.** Which single premise, if false, takes the whole structure down? That is where the real dispute lies, and where the essay must go.

### The template

```plaintext
CONCLUSION (C): ______________________________________

EXPLICIT PREMISES:
  P1. ______________________________  [source: ¶__]
  P2. ______________________________  [source: ¶__]

SUPPRESSED PREMISES (supplied):
  P3*. _____________________________  [needed for step __]
  P4*. _____________________________  [needed for step __]

STRUCTURE (indent = sub-argument):
  ┌─ P1
  ├─ P2
  │    └─ P3* ──┐
  ├─ P4* ───────┴─→ (intermediate: ___) ─→ C
  └──────────────────────────────────────────

INFERENCE CHECK:
  Node 1 (P1,P2 → ?):  valid? [Y/N]  form: _________
  Node 2 (..., P3* → C): valid? [Y/N] form: _________

LOAD-BEARING PREMISE: P__ because ______________
```

### Worked example: Thomson's violinist

**The target.** Judith Jarvis Thomson, "A Defense of Abortion" (1971), argues that even if the fetus is a person with a right to life, abortion is often permissible.

**Conclusion.** In at least some cases, abortion is morally permissible even if the fetus is a person.

**Explicit premises.**

- P1. You wake to find yourself, without consent, surgically attached to a famous unconscious violinist who needs your kidneys for nine months. — the case
- P2. You may permissibly unplug yourself. — the judgment about the case
- P3. The violinist has a right to life. — granted for the argument
- P4. A right to life does not include a right to the use of another person's body without consent. — the principle

**Suppressed premise.**

- P5\*. The structure of the violinist case is relevantly analogous to pregnancy in the cases under discussion.

**Structure.** P2 is the intuition about the case; P3 and P4 are the general principles; P5\* does the bridging. The argument is an *argument from analogy*: the case is used to fix a principle, and the principle is then applied.

**Inference checks.** The inference from (P1, P2) to (P4) is an inference to a principle, not a deduction — it is *abductive* or *reflective-equilibrium* reasoning: P4 is the principle that best explains why P2 is true. The inference from (P3, P4, P5\*) to C is deductive given the analogy.

**Load-bearing premise.** **P5\***, the analogy claim. Everything hinges on whether the violinist case and pregnancy are relevantly alike — and the most natural objection is that they are not, because in the standard pregnancy case the woman is causally responsible for the fetus's dependency in a way she is not for the violinist's. Thomson anticipates this and concedes that in rape cases the analogy is tighter; her strategy is to show that the permissibility of abortion does not require the analogy to hold universally, only in a salient class of cases. Notice how mapping the argument immediately tells you where the real dispute is: not at P3 (both sides grant the fetal right to life for argument's sake), not at P2 (almost everyone grants the violinist case), but at P5\*.

### Failure modes

| Failure | Symptom | Repair |
|---|---|---|
| **Reconstruction as straw man** | The mapped argument is weaker than the original | Reconstruct it in the strongest form (steel-man); if unsure, give two versions |
| **Premise/conclusion confusion** | A disputed claim is listed as a premise when it is the conclusion | Ask: what is being *argued for*? |
| **Objection-as-premise** | An author's anticipated objection is listed as one of their premises | Distinguish the argument from its dialectical framing |
| **Over-formalization** | The argument is forced into a deductive form it never had, and then found invalid | Mark the inference type honestly (deductive, inductive, abductive, analogical) |
| **Missing the suppressed premise** | The map is valid only because a premise is left implicit, and the essay attacks the explicit ones | The suppressed premise is usually the interesting one |

**Exercise.** Reconstruct the argument of Appendix C, §7 (no-miracles) in the template's form. Identify the load-bearing premise. Then reconstruct *van Fraassen's reply* in the same form, and note where the two maps collide. (This is the single most instructive exercise in the appendix: two valid-looking maps that contradict each other, and the collision is the whole debate.)

---

## E.3 — Template 3: Distinction Testing

**The principle.** The philosopher's characteristic instrument is the distinction: a line drawn between two things that were being run together. Almost every advance in the subject is a distinction; almost every sophistry is a distinction that does no work. The skill is to tell which is which.

### The diagnostic battery

Ask six questions of any distinction you meet — or propose.

| # | Question | If the answer is "no" |
|---|---|---|
| 1 | **Does it mark a difference in truth-value?** Are there claims that are true on one side and false on the other? | The distinction is verbal or decorative |
| 2 | **Is it exclusive and exhaustive?** Does every case fall on exactly one side? | Borderline cases will carry the argument, and the distinction is doing less than claimed |
| 3 | **Is it a difference in kind or in degree?** | If degree, it cannot by itself ground a categorical moral or metaphysical verdict |
| 4 | **Is it descriptive or normative?** Does it report a difference or recommend one? | The distinction is doing persuasive work disguised as description |
| 5 | **Does it survive the cases that matter?** Test the paradigm cases, the borderline cases, and the cases the distinction was invented to handle | The distinction is ad hoc |
| 6 | **Is it doing explanatory work, or only labeling?** Does invoking it *explain* anything, or merely name the phenomenon? | The distinction is a redescription, not an analysis |

### The counterexample battery (for necessary-and-sufficient analyses)

For a proposed analysis of a concept into conditions $C_1 \dots C_n$:

```plaintext
CONCEPT: ______________   PROPOSED ANALYSIS: x is F iff C1 & C2 & ... Cn

TEST 1 — SUFFICIENCY (a case where C1..Cn hold but x is not F):
  Case: __________________________   Verdict: __________________

TEST 2 — NECESSITY (a case where x is F but some Ci fails):
  Case: __________________________   Verdict: __________________

TEST 3 — VARIABILITY (change the disputed feature; does the verdict track it?):
  Original: ____________  Varied: ____________  Verdict shift: ____

TEST 4 — KIND (what is this case a case OF? Is it the same kind of thing
  as the paradigm, or a neighboring phenomenon with a different structure?)
  Answer: ______________________________________________

TEST 5 — DEBUNK (is the intuition about the case explained by something
  other than the truth of the theory — framing, salience, moralizing)?
  Answer: ______________________________________________
```

### Worked example: the act/omission distinction

The distinction: killing is (other things equal) worse than letting die. Test it with four cases, which is how the distinction is actually used in applied ethics (Ch. 51).

| Case | Act or omission? | Intuition | Pressure on the distinction |
|---|---|---|---|
| A. Injecting a lethal dose | Act | Wrong | uncontroversial |
| B. Turning off a ventilator | Omission (on one reading) | Permissible if requested | The distinction must say why B is unlike A — the causal story is identical |
| C. Failing to rescue a drowning child when you could | Omission | Wrong | An omission can be as wrong as an act ⇒ the distinction is not *categorical* |
| D. Withholding food from a patient who wants it | Omission | Wrong | The distinction cannot bear the moral weight alone; *intention*, *duty*, and *consent* are doing separate work |

**Diagnosis.** The distinction survives test 1 (there are true claims on one side and false on the other — some omissions are permissible where the corresponding acts are not), but it *fails* test 3 as a categorical difference: it is a difference in degree and in structure, not in kind. It passes test 4 only when supplemented by other principles (the doctrine of double effect, the duty of care, the patient's consent). The correct conclusion is not that the distinction is useless but that **it is not doing the work it is often asked to do alone** — and the analysis should therefore specify which further principle carries the load in each case.

**Test 4 in particular** does most of the diagnostic work, and it is the question students skip. "Is this an act or an omission?" is less useful than "what kind of thing is the doctor doing — and is that kind the kind the distinction was drawn for?"

### Failure modes

| Failure | Symptom | Repair |
|---|---|---|
| **Distinction-mongering** | A new distinction is introduced for every objection, and none is defended | Ask test 6 of each: what does it explain? |
| **False dichotomy** | A distinction is presented as exhaustive when a third option exists | List the third option explicitly (E.1, move 2) |
| **Distinction-as-answer** | The objection is answered by distinguishing rather than by addressing | A distinction answers an objection only if one side of it is independently supported |
| **The normative smuggled as descriptive** | A descriptive distinction is used to license a normative verdict | Test 4; state the normative premise separately, or the argument is incomplete |
| **The undefended borderline** | The distinction's borderline cases are exactly the cases in dispute, and the analysis waves them away | The borderline case is the argument; go there |

**Exercise.** Take the treatment/enhancement distinction in medicine (case 16). Run all six tests. Then take the distinction between *killing* and *letting die* and run test 4 on a case of withdrawing futile treatment. Compare: is one distinction doing more work than the other, and why?

---

## E.4 — Template 4: Thought-Experiment Design

**The principle.** A thought experiment is not a story. It is an instrument for isolating a variable, and like any instrument it can be badly calibrated. The design question is always: *what is this case supposed to show, and does it in fact isolate the feature it varies?*

### The six specifications

| # | Specification | The question it answers |
|---|---|---|
| 1 | **Target judgment** | What intuition is the case supposed to elicit, and what theory does that intuition support or refute? |
| 2 | **Variable** | Which feature is manipulated? Exactly one, or the inference is confounded. |
| 3 | **Foil** | What is the controlled comparison case, identical except for the variable? |
| 4 | **Neutral description** | Is the case described without presupposing the conclusion? (The usual failure: the case is rigged by its adjectives.) |
| 5 | **Robustness** | Does the verdict survive changes to irrelevant features, and is it stable across subjects and framings? |
| 6 | **Debunking check** | Is there a psychological or cultural explanation of the intuition that does not support the theory? |

### The template

```plaintext
CASE NAME: ______________          (after the pattern of Ch. 3, 9)

1. TARGET. The intuition to be elicited is: "__________________"
   It bears on the theory T: ______________________
   If the intuition goes the other way, T is [refuted / weakened].

2. VARIABLE. The feature manipulated is: ______________
   Everything else is held fixed, including: ______________

3. FOIL. The comparison case is: ______________
   The two cases differ ONLY in: ______________
   [If you cannot state the difference in one clause, the design is confounded.]

4. DESCRIPTION CHECK. Re-read the case. Does any adjective or detail
   presuppose the verdict?  [Y/N]  Which? ______________
   Rewrite the description neutrally: ______________________

5. ROBUSTNESS. Change an irrelevant feature: does the intuition survive?
   Change the framing (gain vs. loss; first vs. third person)?
   Is the intuition likely to be shared by people outside your culture
   and your philosophical training?  [Note: this is empirical — Ch. 9.]

6. DEBUNK. The intuition might be explained by: status quo bias /
   loss aversion / just-world belief / moralizing / unfamiliarity.
   Does the explanation undermine the evidential force?  [Y/N]
   Does the theory have independent support?  ______________
```

### Worked example: designing a case to test the experience-machine verdict

**The target.** Nozick's intuition is that we would refuse the machine and that this shows hedonism is false. The standard objection (Appendix C, §12) is that the refusal might reflect *status quo bias* or *false beliefs about reality* rather than a judgment about welfare. Design a case that separates these.

**Variable.** *Agency versus reality.* In the original, the machine offers a passive stream of experiences. The refusal might be about *doing* rather than about *contact with reality* (Nozick's first reason rather than his third).

**Foil.** Construct two machines:

- **M1 (passive).** You are fed experiences of achievement; you do nothing.
- **M2 (active).** You genuinely deliberate, choose, and act inside a simulated world — the simulation is causally responsive to your agency — but the world is simulated.

If the intuition to refuse survives M2, the refusal is about reality. If it disappears at M2, the refusal was about agency, and the argument against hedonism has changed shape: it supports an *achievement* condition, not a *reality* condition. If it survives both, there is a third factor (perhaps that the achievements are not *yours* in the relevant sense).

**Description check.** M2 must not be described as "a simulation of agency" — that phrase presupposes the verdict. It must be described functionally: "your choices have consequences in the world you experience, and the world responds." The loaded adjective is the commonest way a thought experiment is ruined.

**Robustness.** The case should be run in both directions (offered the machine / already inside it and offered exit), because loss framing changes the verdict. The empirical literature on the "experience machine" is thin and mostly WEIRD undergraduates — a caution, not a refutation.

**Debunking check.** If the refusal of M1 is fully explained by loss aversion and the refusal of M2 is not, the case has isolated something: *reality* matters to people independently of agency. That is a real finding, and it supports objective-list accounts, which is the standard conclusion drawn from the case in Ch. 48.

### Failure modes

| Failure | Symptom | Repair |
|---|---|---|
| **Intuition-mining** | The case is constructed to produce the verdict the author wants, then cited as evidence | Construct the case *and* its mirror image; if only one produces the verdict, the design is suspect |
| **The remote-case problem** | The case is so far from any actual situation that intuitions are unreliable about it | Prefer cases that are close to real decisions; if you must go remote, explain why the distance is irrelevant |
| **Loaded description** | Words in the vignette carry the verdict ("a *mere* simulation") | Rewrite in functional, neutral terms |
| **Non-isolated variable** | Two features change at once | State the difference in one clause (specification 3) |
| **Confusing intuition with theory** | The intuition is treated as data when it is a *theory-laden* judgment (Ch. 9) | State what would debunk it |

**Exercise.** Design a case that tests whether the Gettier intuition depends on the "luck" framing or on the "false lemma" structure. (Ch. 7 gives the material; the design brief is specifications 1–6.) Then state what result would refute your own preferred account of the Gettier lesson.

---

## E.5 — Template 5: Objection-and-Reply

**The principle.** An objection is not a disagreement; it is a structured challenge with a target. The discipline is to say *which* premise the objection attacks, *how much* the reply costs, and *what remains* after the exchange.

### Three kinds of objection

| Kind | What it does | The reply must show |
|---|---|---|
| **Internal** | Shows the view is inconsistent with itself | That the inconsistency is only apparent, or concede and revise |
| **External** | Shows the view conflicts with something else we have strong reason to believe | That the conflicting belief is less secure than the view, or that the conflict is not real |
| **Methodological** | Shows the view cannot do the work it was introduced to do | That it can, or that it need not |

Most bad essays give external objections to views that have not been stated with enough precision to be internally assessed. Most good essays begin internally: *does the view, on its own terms, work?*

### The template

```plaintext
VIEW UNDER ATTACK: ______________
The view's central claim: ______________
The work it is supposed to do: ______________

OBJECTION (strongest form):
  O1. ______________________
  O2. ______________________
  ⇒ C. The view is [false / unmotivated / unable to do its work]

TARGET OF THE OBJECTION: premise P__ of the view, namely ______

REPLIES (give three; the third is usually the honest one):
  R1 (strong / denying): ______________________
     Cost: ______________________
     Residual: ______________________
  R2 (middling / distinguishing): ______________________
     Cost: ______________________
     Residual: ______________________
  R3 (concessive / revising): ______________________
     Cost: ______________________
     Residual: ______________________

AFTER THE EXCHANGE: the view is [refuted / weakened to __ / intact],
because the objection's force depended on ____, and that is ____.
```

### Worked example: objections to the experience-machine verdict

**View.** Nozick's judgment that we would refuse the machine shows hedonism is false.

**Objection (strongest form).**

- O1. Our refusal is explained by status quo bias and loss aversion.
- O2. If a judgment is fully explained by a bias, it is not evidence about the thing judged.
- ∴ The refusal is not evidence against hedonism.

**Target.** The objection attacks the *evidential* premise — that the intuition tracks welfare — not Nozick's descriptions of the case. This is important: the case itself is fine; the inference from case to conclusion is what is attacked.

**Replies.**

- **R1 (deny O1).** The refusal is not merely inertial: people also refuse the machine when it is offered to them as a *gain* from a neutral baseline, and they refuse it for others, and they report the refusal as a considered judgment. *Cost:* the empirical evidence is thin and culturally parochial. *Residual:* the bias explanation is incomplete.
- **R2 (distinguish).** Even if the *refusal* is biased, the *judgment* it expresses may be correct; biases can accompany correct judgments. The case is a *probe*, not a proof (Appendix C, §12), so the objection weakens but does not destroy its force. *Cost:* the case now carries less weight than Nozick claimed. *Residual:* the case is still a *prima facie* counterexample requiring explanation.
- **R3 (concede).** The machine case does not refute hedonism; it forces hedonism to explain the intuition away, and that explanatory burden is itself a cost. The correct conclusion is that hedonism is *disfavored*, not refuted — and the case has value as a *diagnostic*, because any theory that must call all our reflective judgments about welfare systematically mistaken is in trouble.

**After the exchange.** The view is *weakened to a presumption*. The objection's force depends on the empirical claim about bias, which is contestable; the case survives as a probe with defeasible evidential weight. This is the honest verdict, and it is more useful than either "Nozick refutes hedonism" or "the case is worthless."

### The three-reply rule, and the motte-and-bailey test

Always give three replies, ordered by how much they concede. The strong reply is the one a defender would actually give; the concessive reply is the one that is usually true. An essay that gives only the strong reply is a brief for a client; an essay that gives only the concessive reply has no thesis.

**Motte-and-bailey test.** If a defender, when pressed, retreats to a modest claim while the original argument advanced a bold one, ask: *is the modest claim sufficient to do the work the bold one was introduced to do?* If not, the retreat is a change of subject, not a defense (Ch. 4).

### Failure modes

| Failure | Symptom | Repair |
|---|---|---|
| **Straw-man objection** | The objection attacks a crude version | State the view in its strongest form first (E.2) |
| **Reply by distinction** | The objection is answered by introducing a new distinction that is not independently defended | Test the distinction (E.3) |
| **Winning the argument, losing the phenomenon** | The reply saves the thesis by denying the datum that motivated it | Ask what the theory was introduced to explain |
| **Uncosted reply** | A reply is offered with no statement of what it gives up | Every reply has a cost; name it |
| **The infinite exchange** | Objection, reply, counter-reply, ad infinitum | Stop when the residual is identified; state the verdict |

**Exercise.** Take the "no miracles" argument (Appendix C, §7) and write the objection in its strongest form, targeting the load-bearing premise you identified in E.2. Then give three replies with costs. Then decide which reply a scientific realist should actually give.

---

## E.6 — Template 6: The Philosophical Analysis

**The principle.** A philosophical analysis is an argument with a shape: a question, a map of the options, a position, a defense, and an honest statement of what remains. The shape is not decoration; it is what makes the piece assessable.

### The architecture (1,500–2,500 words)

| Section | Proportion | Function | Sentence stem |
|---|---|---|---|
| **1. The question** | 10% | Fix the target, state the stakes, say what the piece will show | "The question is not X but Y. The answer matters because Z. I shall argue that..." |
| **2. The map** | 20% | The rival answers, and why the live ones are live | "There are three positions: A, B, and C. A is ruled out by..., so the real dispute is between B and C." |
| **3. The argument** | 35% | The positive case, with the load-bearing premise flagged | "The central premise is P. P is supported by..." |
| **4. The objection** | 15% | The strongest objection, stated fairly | "The best objection is that... If sound, it shows..." |
| **5. The reply** | 15% | The defense, with its cost | "The reply is that... The cost of this reply is..." |
| **6. The verdict and the residual** | 5% | What has been established, and what has not | "I conclude that... What remains open is..." |

### Paragraph rules

1. **One claim per paragraph.** The topic sentence states it.
2. **The last sentence says what follows** — from the claim, for the argument.
3. **The dialectic is signposted.** "This objection fails" and "This reply costs" are arguments, not transitions.
4. **Terms are defined at first use**, not in a glossary at the end.
5. **Never "clearly."** If it were clear, it would not need saying.
6. **Your confidence is calibrated.** "This shows" vs. "this suggests" vs. "this is consistent with."

### The self-assessment rubric

| Criterion | 1 (fails) | 2 (weak) | 3 (competent) | 4 (strong) |
|---|---|---|---|---|
| **Question** | Unclear or shifts | Clear but trivial | Clear and stable | Clear, stable, and well-motivated |
| **Map** | One view, no rivals | Rivals listed, not weighed | Rivals weighed | Rivals weighed, live options identified |
| **Argument** | Assertion | Assertion plus support | Valid argument, premises supported | Valid, supported, load-bearing premise identified |
| **Objection** | None, or straw man | Present but weak | Strong and fairly stated | Strongest form, targeting the right premise |
| **Reply** | Dismissal | Reply without cost | Reply with cost | Reply, cost, and residual honestly stated |
| **Prose** | Unclear | Correct but shapeless | Clear and structured | Precise, economical, signposted |

**Scoring note.** The rubric is diagnostic, not punitive. Most first drafts are 2s. The fastest route from 2 to 3 is not more reading; it is E.2 (mapping) and E.5 (objection-and-reply). The fastest route from 3 to 4 is E.1 (question isolation) and E.3 (distinction testing).

### Worked outline: "Is it permissible to use a deceptive AI system to improve patient adherence?"

**1. Question (150 words).** Not "is deception wrong?" (settled) and not "does the system work?" (empirical), but: *is a system whose success depends on the patient's false beliefs about it a permissible form of clinical communication?* The stakes: autonomy is a constraint, not a preference. Thesis: permissible only if the deception is *disclosed in principle* and *withdrawn on request* — a "transparency-in-principle" condition.

**2. Map.** (a) Consequentialist: permissible if net benefit (the "nudge" view). (b) Kantian: impermissible, because it uses the patient as means (the "respect" view). (c) Fiduciary/relational: permissible if it is the kind of thing a good clinician could disclose without destroying the relationship (the "transparency" view). A and B are both too coarse; C is the live option.

**3. Argument.** Premise 1: the wrong in deception is the usurpation of the other's agency, not the false belief as such (Frankfurt on bullshit). Premise 2: a practice that is *disclosable* does not usurp agency in the relevant way. Premise 3: a disclosable nudge retains the patient's standing as a reasoner. Conclusion: disclosable nudges are permissible; non-disclosable ones are not. **Load-bearing premise: 1.**

**4. Objection.** The transparency condition is a fiction: patients will not read the disclosure, and the disclosure will not reach the moment of decision, so the *effective* deception is total. (Targets premise 2.)

**5. Reply.** The condition is not about actual comprehension but about *standing*: the point is whether the patient *could* find out and object, not whether they will. Cost: this is a thinner notion of autonomy than the Kantian one. Residual: the thinner notion may be enough for clinical contexts but not for research contexts.

**6. Verdict.** Disclosable deception is permissible; the interesting boundary is between disclosable and undisclosable, which is a question about institutions, not individual acts. (Ch. 47, 51; Appendix B: autonomy, paternalism, testimonial injustice.)

---

## E.7 — The Chain, Run Once

One problem, all six templates, in sequence. The purpose is to show what the outputs look like and how each constrains the next.

**The problem.** A city proposes to deploy a predictive-policing algorithm. It is demonstrably biased — it flags members of one demographic at a higher rate than base rates warrant — but it also reduces total crime relative to current practice. *Is deploying it permissible?*

**E.1, Question isolation.** Classify: normative, with an empirical component. Contrast: (a) permissible if net crime reduction; (b) impermissible because it violates equality; (c) permissible only with structural remedies (the "remedial" view); (d) the question is really about *who decides*, not about the algorithm. Presuppositions: that "reduces total crime" is well-defined and measured correctly; that bias is a property of the algorithm rather than of the data or the policing environment; that the base rate is the right comparison. Answer-form: the question is settled by a principle about *fairness under risk*, not by the empirical facts alone. Working version: *"Given that the algorithm's bias is a property of its training data, is its deployment permissible under a principle that permits unequal treatment when the inequality tracks an antecedent injustice?"*

**E.2, Argument map.** Conclusion: permissible only with remedies. P1: the algorithm's disparate impact is caused by biased historical data. P2: a practice that reproduces an antecedent injustice is impermissible unless it also remedies it. P3: the algorithm *can* be paired with remedies (audits, review, compensation). C. **Load-bearing premise: P2** — the principle of remedial fairness.

**E.3, Distinction testing.** The distinction "discriminatory vs. merely disparate-impact" — does it mark a difference in truth-value? Yes (intentional discrimination is a different wrong). Is it exhaustive? No: there is a third category, *reproduced* injustice without intent, which is the interesting one. Is it descriptive or normative? Normative. Does it survive the cases that matter? Only when combined with a doctrine of remedial responsibility.

**E.4, Thought-experiment design.** Design a case that isolates *who bears the cost*: the algorithm is biased against group A but reduces crime in group B, and vice versa. If the intuition flips with the direction of the bias, the principle is about distribution; if it does not, the principle is about the *fact* of bias. Design check: the cases must differ only in the demographic, not in the magnitude of harm.

**E.5, Objection and reply.** Objection: the "remedial" view licenses any biased practice that happens to include a remedy — the remedy is a fig leaf. Target: P2. Reply: the remedy must be *structurally integrated*, not bolted on; it must change the practice's decision procedure. Cost: this is a high bar, and it may make almost all deployments impermissible. Residual: the view is close to impermissibility in practice, which may be the right answer but weakens its claim to be a *permissive* position.

**E.6, The analysis.** The essay that results is not "pro or con" but a thesis about *conditions*: deployment is permissible only if the remedy is structural, and the burden is on the deployer to show it. That is a conclusion with a target, a map, a load-bearing premise, a tested distinction, an isolating case, a costed reply, and a stated residual. It is what the book means by *systematic analysis*.

---

## E.8 — Fifty Case Studies

Each entry gives the case, the question worth asking, the concepts and chapters to bring to it, and **the trap** — the most tempting wrong move. The cases are drawn from law, medicine, technology, science, and ordinary life. They are graded in difficulty within each domain, roughly in the order given.

### Law

| # | Case | The question | Concepts / chapters | The trap |
|---|---|---|---|---|
| 1 | A suspect is detained under a "ticking bomb" statute that permits coercive interrogation | Is the statute permissible if it is used only when officials certify an emergency? | Torture; dirty hands; rule vs. act; Ch. 45, 51 | Arguing from the imagined case to the statute — the statute must also govern the false certification |
| 2 | A defendant is clearly guilty but cannot receive a fair trial (evidence destroyed by police negligence) | Should the court acquit? | Rights; integrity of the system; consequentialism; Ch. 45, 47 | Treating the question as "does the acquittal have bad consequences?"; it is about the *system's* justification |
| 3 | A corporation is prosecuted for manslaughter; the culpability is diffuse across the hierarchy | Can a corporation be blameworthy? | Group agency; moral responsibility; Ch. 11, 27 | Assuming group blame reduces to individual blame, or denies it entirely |
| 4 | A jury hears statistical evidence that a suspect was one of 1,000 ticket-holders, 999 of whom paid | Is a conviction on statistical evidence alone legitimate? | Evidentialism; proof; generalization; Ch. 10, 11 | Treating the question as mathematical; it is about what a *jury* is for |
| 5 | A negligence standard asks what "the reasonable person" would do | Whose reasonableness? | Idealization; standpoint epistemology; Ch. 46, 47 | Assuming "reasonable person" is a descriptive claim; it is a normative stipulation |
| 6 | A wrongfully imprisoned man is compensated for lost years; his counterfactual future is unknowable | Is the compensation just if it cannot be measured? | Counterfactuals; compensation; Ch. 18, 47 | Treating compensation as a demand for *equivalence* rather than for *acknowledgment* |
| 7 | A sentencing algorithm predicts recidivism with 70% accuracy | Should it be used? | Prediction; desert; responsibility; Ch. 27, 51 | Ignoring that *judges* also predict at ~65%; the comparison class matters |
| 8 | A man asks a search engine to remove a 20-year-old article about his conviction | Does the right to be forgotten override the public record? | Publicity; testimony; archives; Ch. 11, 51 | Framing it as privacy vs. speech, when it is also about the *epistemics of the archive* |
| 9 | A defendant invokes a cultural defense against a charge of assault | Does the defense express respect or condescension? | Relativism; autonomy; equality; Ch. 13, 44 | Using "culture" as an explanatory category in place of evidence |
| 10 | A constitutional court strikes down a law passed by a large majority | Is judicial review compatible with democracy? | Authority; legitimacy; public reason; Ch. 47 | Assuming the majority's preference *is* the democratic standard; that is the disputed premise |

### Medicine

| # | Case | The question | Concepts / chapters | The trap |
|---|---|---|---|---|
| 11 | A patient in a trial believes the trial is designed for their benefit | Does the therapeutic misconception vitiate consent? | Consent; information; trust; Ch. 51 | Treating the misconception as a flaw in the *patient* rather than in the *institution* |
| 12 | A doctor considers disclosing a 1-in-10,000 risk of a serious side-effect, knowing the disclosure will probably cause the patient to refuse life-saving treatment | Is disclosure required? | Autonomy; risk; paternalism; Ch. 47, 51 | Treating the disclosure as an event rather than as a *practice* with epistemic effects |
| 13 | A market in kidneys is proposed | Is commodification of the body a distinctive wrong? | Commodification; autonomy; exploitation; Ch. 45, 51 | Reducing the objection to "bad consequences" and missing the *dignity* argument entirely |
| 14 | A patient with capacity refuses treatment that is clearly in their interest | Must the clinician defer? | Autonomy; capacity; well-being; Ch. 47 | Assuming autonomy *always* wins; it is a weight, not an axiom |
| 15 | A clinician considers prescribing a placebo for a condition with a good placebo response | Is deception permissible for benefit? | Deception; speech acts; Ch. 34, 51 | Forgetting that placebos can work *without* deception (open-label placebo) — check the empirical premise |
| 16 | A student asks for cognitive enhancement drugs before an exam | Does the treatment/enhancement distinction do any work? | Distinction testing (E.3); Ch. 51 | Assuming the distinction is either sharp or useless; it may be gradual |
| 17 | A patient's advance directive refuses treatment that the demented patient now seems to want | Which self governs? | Personal identity; precedent autonomy; Ch. 26 | Assuming the later self is "not the same person" in the legal-metaphysical sense |
| 18 | A genetic test reveals a risk that a patient has not asked about | Is there a "right not to know"? | Autonomy; information; Ch. 11, 51 | Treating the right as absolute rather than as a defeasible claim against disclosure |
| 19 | A pandemic triage protocol uses quality-adjusted life years | Is QALY-based triage just? | Aggregation; disability; value of life; Ch. 45, 48 | Assuming QALYs are neutral measures rather than evaluative rankings |
| 20 | A pharmacist refuses to dispense a prescription on moral grounds | Is conscientious objection compatible with professional duty? | Complicity; role morality; Ch. 45, 47 | Framing it as a clash of rights; it is also about *institutional design* |

### Technology

| # | Case | The question | Concepts / chapters | The trap |
|---|---|---|---|---|
| 21 | A biased predictive-policing algorithm reduces total crime | Is deployment permissible? | Fairness; remedies; Ch. 45, 47 (worked in §E.7) | Ignoring that the bias is in the data, not the code |
| 22 | An autonomous weapon misidentifies a target; no human chose that specific strike | Who is responsible? | Responsibility gap; agency; Ch. 27, 51 | Answering "the commander" without saying what the commander *did* |
| 23 | A language model produces confident falsehoods | Should we treat it as a testimonial source? | Testimony; authority; Ch. 11 | Treating the model as an *unreliable speaker* rather than as a *tool that mimics speakers* |
| 24 | A powerful AI system's values must be specified by its designers | Whose values? | Value specification; constructivism; Ch. 44 | Assuming there is a fact of the matter about "the right values" independent of procedure |
| 25 | A deepfake of a politician appears days before an election | Is the harm to truth or to trust? | Testimony; epistemology of doubt; Ch. 11, 34 | The "liar's dividend": claiming real footage is fake — the mirror problem |
| 26 | A platform optimises for engagement and produces addiction | Is the design autonomous or coercive? | Autonomy; manipulation; Ch. 30, 47 | Treating addiction as a failure of will rather than as a design outcome |
| 27 | A firm sells personal data it collected without explicit consent | Is data property? | Property; personhood; Ch. 47 | Assuming the property answer settles the question; ownership of data is neither obviously apt nor obviously inapt |
| 28 | A system reports distress signals that may or may not indicate sentience | What is owed to digital minds under uncertainty? | Moral status; precaution; Ch. 29 | Using uncertainty as a license for either indifference or paralysis |
| 29 | An algorithm schedules workers, ratings them, and fires them | Is algorithmic management a freedom problem? | Republican freedom; Ch. 47 | Reducing it to "consent in the contract" |
| 30 | A manufacturer locks repairs behind proprietary software | Does ownership include the right to repair? | Ownership; design; Ch. 47 | Treating property as a single thing rather than a bundle of incidents |

### Science

| # | Case | The question | Concepts / chapters | The trap |
|---|---|---|---|---|
| 31 | A field discovers that half its published findings fail to replicate | Does this undermine the claim that science produces knowledge? | Reliability; social epistemology; Ch. 40, 11 | Concluding "science is unreliable" rather than "the *publication system* is" — distinguish the method from the institution |
| 32 | A regulator must decide whether a chemical is safe, with a threshold that determines how many false negatives are tolerated | Is the choice of threshold a scientific or a value question? | Inductive risk; Ch. 39 | Treating "safety" as a purely scientific predicate |
| 33 | A conservation program protects a "species" whose boundaries are contested | What is being protected? | Natural kinds; species problem; Ch. 42 | Assuming "species" is a natural kind; it may be a practical kind |
| 34 | Physicists propose a multiverse to explain fine-tuning | Is this science? | Demarcation; testability; Ch. 40, 50 | Applying Popper mechanically; the criterion is a cluster, not a test |
| 35 | A "wellness" protocol makes unfalsifiable claims about energy | Is it pseudoscience? | Demarcation; evidence; Ch. 40 | Using "pseudoscience" as a term of abuse instead of a diagnostic |
| 36 | An economic model assumes perfectly rational agents and predicts badly | Is the model false, or is it an idealization? | Models; idealization; Ch. 39 | Treating falsehood as automatically a defect; idealized models can be *explanatory* |
| 37 | A quantum measurement yields a definite outcome; the theory predicts superposition | What does the theory say about observation? | Measurement problem; Ch. 41 | Importing "consciousness causes collapse" without the argument |
| 38 | Animal studies predict human responses imperfectly | When is extrapolation warranted? | Models; analogy; Ch. 29, 42 | Assuming the question is statistical when it is also *analogical* |
| 39 | A junior researcher's finding is dismissed by senior figures in the field | Is this epistemic injustice? | Testimony; credibility; Ch. 11 | Treating every dismissal as injustice; credibility has *evidence* behind it |
| 40 | A machine-learning model predicts accurately but its reasoning is inscrutable | Does explanation require understanding? | Explanation; opacity; Ch. 38 | Assuming that because *we* cannot read it, it is not a reason |

### Ordinary life

| # | Case | The question | Concepts / chapters | The trap |
|---|---|---|---|---|
| 41 | A family decides not to tell a dying relative the diagnosis | Is the deception permissible? | Autonomy; paternalism; Ch. 45, 51 | Applying a clinical framework to a *familial* one without noticing the shift |
| 42 | A partner reads the other's messages "for reassurance" | Is the privacy violation distinct from the distrust? | Privacy; trust; Ch. 47 | Treating privacy as secrecy; it is also about *standing* |
| 43 | One vote will not change an election outcome | Is voting rational? | Rationality; collective action; Ch. 10, 45 | Conflating *causal* efficacy with *expressive* or *participatory* reasons |
| 44 | A friend asks you to help them move; you have a prior commitment to a stranger | Should friendship have priority? | Partiality; impartiality; Ch. 45 | Assuming impartialism requires treating strangers as friends, which nobody believes |
| 45 | A VR system offers a life more vivid, more meaningful, and more pleasant than your own | Would you be irrational to prefer it? | Well-being; reality; Ch. 48 | Re-running Nozick without asking what the new case isolates |
| 46 | You promised your late friend you would finish their book; you now have no interest | Does a promise to the dead bind? | Promising; posthumous interests; Ch. 26, 45 | Assuming the dead cannot be wronged, which is the question |
| 47 | You deliberately seek out views you expect to disagree with | Is this epistemically required? | Disagreement; open-mindedness; Ch. 11 | Assuming exposure to disagreement always improves calibration; it can entrench |
| 48 | A couple considers having a child in a climate crisis | Is having a child a harm to the child? | Non-identity; future persons; Ch. 51 | Applying person-affecting principles without noticing they cannot handle creation |
| 49 | You buy a counterfeit designer bag knowingly | Is the wrong to the brand, to the buyer, or to no one? | Authenticity; aesthetic value; Ch. 45, 49 | Treating "authenticity" as obviously valuable; it needs an argument |
| 50 | A distant event is reported only by sources that confirm each other's bias | Should you believe it? | Testimony; independence; Ch. 10, 11 | Treating agreement as corroboration without checking *independence* |

---

### Model sketches for selected cases

Eight of the fifty, showing the expected skeleton rather than the full essay.

**Case 4 (statistical evidence).** The map: (a) purely probabilistic evidence is sufficient (b) it is never sufficient (c) it is sufficient only when the evidence is *causal* in the right way (the "individualization" view). The live option is (c). Load-bearing premise: that a verdict requires an answer to "why this defendant?" and not merely "how likely?" The trap is to run a Bayesian calculation: the likelihood ratio can be enormous and the intuition that a conviction is illegitimate can survive — which shows the objection is to the *form* of the evidence, not its weight. Verdict: the individualization view, with the cost that it makes some statistical evidence unusable.

**Case 11 (therapeutic misconception).** The map: (a) the misconception is the patient's error (b) it is a failure of the consent process (c) it is a structural feature of trial participation that no consent form can remedy (the live option). Load-bearing premise: that consent is about *understanding*, not about *signature*. Verdict: (c), with the consequence that the remedy is institutional (independent advising), not documentary.

**Case 17 (advance directives and dementia).** The map: (a) precedent autonomy governs (b) the present self governs (c) a *narrative* self governs, and the directive is evidence in a story rather than a command (the live option). Load-bearing premise: that identity is not all-or-nothing, so neither is the authority of a past self. The trap is to ask "which one is the same person?" as though identity were the criterion; the interesting question is what *respect for a person* requires when the person is fragmented.

**Case 21 (predictive policing).** See §E.7 in full. The short skeleton: load-bearing principle is *remedial fairness*; the objection is that the remedy is a fig leaf; the reply requires structural integration; the residual is that the view is nearly impermissibility in practice.

**Case 31 (replication crisis).** The map: (a) the crisis refutes the claim that science produces knowledge (b) it refutes nothing; replication is not the essence of science (c) it refutes a *specific* claim about the reliability of a *specific institution* (the live option). Load-bearing premise: the distinction between the method and the institution (E.3, test 1). Verdict: (c), with consequences for how we should cite published findings.

**Case 36 (economic models).** The map: (a) false assumptions make a model false and worthless (b) models are instruments, and false assumptions can be explanatory (the live option) (c) models are true of "the world" in a different sense (internal realism). Load-bearing premise: that explanation does not require truth of the assumptions, only of the mechanism. The trap is to attack the realism of the assumptions without asking what the model is *for*.

**Case 44 (partiality).** The map: (a) impartialism is correct and friendship must be justified as a general practice (b) partiality is a basic requirement of the ethical life (c) partiality is permitted but not required — a *permission* grounded in the value of particular relationships (the live option). Load-bearing premise: that the question is about the *structure* of moral reasons, not their strength. Verdict: (c), with the cost that it leaves the boundary of permissible partiality vague.

**Case 50 (correlated testimony).** The map: (a) agreeing sources corroborate (b) agreement corroborates only if independent (c) agreement can corroborate even if correlated, when the *correlation* is itself explicable (the live option). Load-bearing premise: that corroboration is a matter of *conditional independence given the hypothesis*, not of the number of sources. This is where the Bayesian toolkit (Appendix A) does real philosophical work: the likelihood ratio is close to 1 when the sources are correlated.

---

## E.9 — The Self-Directed Curriculum

Two routes, both of which assume Part I has been read first. The short one is for a term; the long one is for a year.

### The twelve-week route

| Week | Read | Do | Output |
|---|---|---|---|
| 1 | Ch. 1–2 | E.1 on three questions | Three isolated questions, one page |
| 2 | Ch. 3–4 | E.2 on one argument from Appendix C | One argument map |
| 3 | Ch. 5–6 | E.3 on one distinction | One distinction test |
| 4 | Ch. 7–8 | E.4 on a Gettier variant | One thought-experiment spec |
| 5 | Ch. 9–10 | E.5 on one objection | One objection/reply table |
| 6 | Ch. 11–12 | Case 4, 50 | One full analysis (1,500 words) |
| 7 | Ch. 13–16 | E.1–E.3 on Case 31 | One map plus distinction test |
| 8 | Ch. 17–20 | E.4 on a time or identity case | One design brief |
| 9 | Ch. 23–26 | Case 17, 28 | One full analysis |
| 10 | Ch. 31–34 | Case 23, 25 | One map plus objection table |
| 11 | Ch. 38–41 | Case 31, 34, 37 | One full analysis |
| 12 | Ch. 44–48 | Case 12, 13, 44 | One full analysis, plus a revision of week 6 |

### The one-year route

A year of work, in four quarters, with a daily practice running underneath it.

**Q1 — Method and epistemology.** Ch. 1–13. Deliverables: three full analyses, one per month. Weekly: one argument map from Appendix C; one distinction test; one page of the philosophical diary (Ch. 4, §5).

**Q2 — Metaphysics and mind.** Ch. 14–30. Deliverables: two full analyses on mind, one on substance or modality. Weekly: one thought-experiment *design* (not just an evaluation); one "steel-man" exercise on a view you reject.

**Q3 — Language, logic, science, mathematics.** Ch. 31–43. Deliverables: one analysis on truth or meaning; one on scientific realism; one on a mathematical problem. Weekly: one formalization exercise (Appendix A); one case from the science list.

**Q4 — Value and metaphilosophy.** Ch. 44–54. Deliverables: two analyses on normative ethics; one on political philosophy; a final essay that traces one concept through the whole book (Ch. 53, §7).

**The daily practice.** Twenty minutes: reconstruct one argument from memory, then check it against its source. This is the single highest-yield exercise in the book, and it is also the one most often skipped, because it feels like recitation. It is not: reconstruction from memory reveals the suppressed premises you have been supplying silently, and those are your own philosophical commitments, which is what you most need to see.

### When you are stuck

Four diagnostic questions, in order. They resolve most stalls.

1. **Is the question clear?** Go back to E.1. If you cannot state the working version in one sentence, the problem is upstream of any argument.
2. **Is the key term doing one job?** Check it in Appendix B. Most stalls are caused by a term that is being used in two senses, one of which is doing the work.
3. **Have you found the load-bearing premise?** If the argument feels unanswerable, you have probably not yet located the premise that carries it — and it is usually not the one being discussed.
4. **Are you answering the objection, or a neighbor of it?** Restate the objection in its strongest form (E.5). If your reply now looks irrelevant, it was addressed to the neighbor.

---

## E.10 — Closing Note on the Workbook's Limits

Three honest caveats.

**First, the templates cannot supply judgment.** The counterexample battery tells you to look for a case where the conditions hold but the concept does not apply. It cannot tell you whether the case you have imagined is a genuine counterexample or a neighboring phenomenon with a different structure. That is the skill the book is trying to teach, and it is learned by doing, badly, for a long time.

**Second, the case studies are not neutral.** Their vignettes encode choices about what matters (the bias in the algorithm, the autonomy of the patient, the independence of the sources). A reader who works through all fifty will absorb a set of concerns as well as a method. That is unavoidable, and it is why §D.13's warning about the canon applies here too: the workbook's selection is one selection, and the optional threads in each part name what it leaves out.

**Third, and most important: the workbook is for the analysis, not the career.** The temptation, once the templates are learned, is to produce work that exhibits method and evades substance — the essay that maps everything and concludes nothing, or the essay whose objection is so symmetrically answered that no position is ever risked. The templates are meant to make the argument *sharper*, not to replace it. A philosophical analysis that does not take a stand is a diagram of an argument, and the difference between a diagram and an argument is the difference between knowing how philosophy is done and doing it.

---

*Cross-references: the vocabulary used throughout is defined in Appendix B; the fifteen arguments that supply most of the practice material are reconstructed in Appendix C; the figures named in the cases are located in Appendix D; the formal notation for the Bayesian and decision-theoretic exercises is in Appendix A. Chapter references in each case point to the fuller treatment of the concepts involved.*

*A final exercise, from which the others follow.* Take one case from this appendix that you find genuinely difficult — not the one you already know how to answer. Run it through all six templates. Then ask whether your conclusion is the one you started with. If it is, you have either been very lucky or have not done the work.*
