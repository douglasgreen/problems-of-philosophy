# Appendix C — The Argument Hall of Fame

**What this appendix is.** Fifteen arguments that have shaped the discipline, each reproduced, formally reconstructed, and assessed. The selection is not a list of the *best* arguments (there is no such list) but of the arguments that have done the most *work*: the ones that generated traditions, forced distinctions, or set the terms of a debate that is still running.

**How each entry is organized.** Every entry has the same six parts:

1. **Source** — where the argument is stated, and in what form.
2. **The argument** — as its author gave it, in the author's own idiom as far as possible.
3. **Reconstruction** — a numbered, citable form. These are *one* reasonable reconstruction, not the only one; where rivals matter, a variant is given.
4. **The load-bearing premise** — the one premise that does the work. Every landmark argument has exactly one, and the history of its reception is usually the history of attacks on that premise.
5. **The strongest objection, and the replies** — the dialectic, not a verdict from nowhere.
6. **Verdict** — a status label from the following taxonomy.
   - **Refuted** — the argument fails on a premise that cannot be repaired without changing the argument.
   - **Refuted in strong form; survives in weak form** — the ambitious conclusion fails, a modest one survives.
   - **Constrains but does not establish** — the argument does not prove its conclusion but rules out certain positions and shifts the burden.
   - **Live** — no consensus; the argument remains a serious option.
   - **Decisive constraint** — the argument establishes a boundary that any subsequent theory must respect, even if its own positive conclusion is disputed.
   - **Paradox** — the argument is valid from apparently true premises to an unacceptable conclusion; every resolution pays a price, and the argument remains a standing test of a conceptual scheme.

**Summary table.**

| # | Argument | Type | Load-bearing premise | Verdict |
|---|---|---|---|---|
| 1 | Ontological | Deductive (modal) | A maximally great being is possible | Live; unrefuted, unproven |
| 2 | *Cogito* | Self-verifying performance | Doubting presupposes a doubter | Refuted in strong form; limited certainty survives |
| 3 | Master argument | *Reductio* | Conceiving entails conceived | Refuted in strong form; semantic residue |
| 4 | From illusion | Generalization from indistinguishability | Indistinguishability entails sameness of object | Rejected; premise not dead |
| 5 | Gettier case | Counterexample | JTB is sufficient for knowledge | Decisive constraint |
| 6 | Zombie | *Modus tollens* from conceivability | Conceivability entails metaphysical possibility | Live; forces a choice |
| 7 | No miracles | Abduction | Predictive success needs a truth-conducive explanation | Live; modest form strong |
| 8 | Problem of evil | Deductive + evidential | No morally sufficient reason for evil | Logical form refuted; evidential form live |
| 9 | Open question | *Reductio* on definitional naturalism | Meaning-identity would render the question trivial | Partial; defeats only analytic naturalism |
| 10 | Companions in guilt | Parity | Moral and epistemic normativity are of a kind | Live; cuts both ways |
| 11 | Original position | Constructive/contractual | Maximin behind the veil of ignorance | Fails as deduction; succeeds as device |
| 12 | Experience machine | Counterexample to hedonism | We would not choose the machine | Powerful probe, not a proof |
| 13 | Liar | Paradox | Bivalence + T-schema + self-reference | Paradox; unsolved |
| 14 | Rule-following | Skeptical paradox | Past facts fix what a rule requires | Deep; conclusion widely resisted |
| 15 | Moore's hands | Parity (Moore's *modus ponens*) | The premises are more certain than the skeptical conclusion | Diagnostic; live |

---

## 1. The Ontological Argument

**Source.** Anselm, *Proslogion* 2 (1078); the modal descendant in Plantinga, *The Nature of Necessity* (1974), ch. 10; the second (necessity) form in Malcolm (1960) and Hartshorne (1961).

**The argument.** Anselm's chapter 2:

> And certainly that than which a greater cannot be thought cannot exist in the understanding alone. For if it is in the understanding alone, it can be thought to exist in reality also, which is greater.

The fool of Psalm 14 "has said in his heart, There is no God"; Anselm's claim is that the fool has thereby *understood* the phrase, and that the phrase, once understood, cannot consistently be thought to lack a referent.

**Reconstruction (Anselm).**

1. God is "that than which no greater can be conceived" (by stipulation). — definition
2. God exists in the understanding — at least the concept is grasped. — premise (the fool understands)
3. Suppose God exists *only* in the understanding. — assumption for *reductio*
4. Then a being greater than God can be conceived: namely, one that exists in reality as well. — premise
5. But nothing greater than God can be conceived, by (1). — from (1)
6. Therefore God exists in reality. — *reductio* on (3)

**Reconstruction (Plantinga's modal form).** This is the form that has dominated discussion, because it avoids the "great-making property" dispute:

1. It is possible that there exists a maximally great being — one that exists in every possible world and is maximally excellent in each.
2. Necessarily, if a maximally great being is possible, then it exists in every possible world.
3. The actual world is a possible world.
4. Therefore a maximally great being exists.

Formally, with $M$ = "a maximally great being exists" and $\Box$/${\Diamond}$ modal operators:

$$\Diamond\Box M \;\wedge\; \Box(\Diamond\Box M \to \Box M) \vdash \Box M$$

The step is an instance of the $S5$ schema $\Diamond\Box p \to \Box p$.

**The load-bearing premise.** In Anselm's version it is (4): that a being's existing in reality is *greater* than its existing only in the understanding. In Plantinga's it is (1): the possibility premise. Note the structure: the modal argument is valid in $S5$, and its validity is not in dispute. All the action is in whether the possibility of a maximally great being can be affirmed without already affirming its actuality.

**Strongest objection (Anselm's).** Kant: existence is not a *predicate* that adds to a concept, so (4) is false. To say that a hundred real thalers contain more than a hundred possible thalers is to say something about my financial situation, not about the concept. In post-Fregean terms, existence is a second-order property, expressed by the quantifier, not a first-order property that an object might have or lack. Hence "a being with all perfections plus existence" is not a greater concept than "a being with all perfections" — there is no additional property to add.

**Strongest objection (Plantinga's).** The possibility premise (1) is not free. If $S5$ is the logic of metaphysical modality, then $\Diamond\Box M$ and $\neg\Diamond\Box M$ are the only options, and the argument has established a *disjunction*: either God's existence is impossible or it is necessary. The atheist can accept the disjunction and affirm the first horn. The argument therefore shifts the burden rather than discharging it — unless there is independent warrant for the possibility premise, and the standard candidates (conceivability, intuition) are exactly what is disputed.

**Replies.**

- **To Kant:** Kant's objection, if sound, refutes the version of the argument that treats existence as a great-making *property*, but the modal version can be run without that premise: maximal greatness is defined by the *necessity* of maximal excellence, and necessity is not existence. Plantinga's argument does not say "existence is a perfection"; it says that the possibility of a certain modal profile entails its actuality.
- **To the possibility objection:** Perhaps the possibility premise is *properly basic* or warranted by the general reliability of modal intuition, so it does not require independent proof. This is the line taken by Plantinga and, differently, by Pruss.
- **Gaunilo's parody** (the perfect island) is generally thought to fail, but for a subtle reason: "greatest island" is constrained by the sort of thing an island is, and greatness for islands does not plausibly include necessary existence. The parody shows that the argument's form cannot be applied to *arbitrary* great-making descriptions; it does not show that it fails for the *maximal* case.

**Verdict: Live.** The argument is not refuted — the modal version is valid, and Kant's objection does not touch it. Nor is it established: the possibility premise is doing all the work, and it is precisely what a well-informed atheist will deny. Its enduring value is not as a proof but as a *model* of how modal reasoning can carry substantive metaphysical weight, and as a permanent test of any account of the relation between conceivability, possibility, and existence. (*Ch. 16, 50*)

---

## 2. The *Cogito*

**Source.** Descartes, *Meditation II* (1641); the *Discourse on Method* IV (1637). The most-discussed reconstructions: Hintikka (1962), Williams (1978), Frankfurt (1970).

**The argument.** After the hyperbolic doubt of *Meditation I*, Descartes writes:

> Let him deceive me as much as he can, he will never bring it about that I am nothing so long as I think that I am something.

And in the *Discourse*: *je pense, donc je suis* — "I think, therefore I am."

**Reconstruction (the syllogistic reading).**

1. I am thinking. — premise
2. Whatever thinks, exists. — premise
3. Therefore I exist. — from (1), (2)

*Immediate problem:* this is valid but dialectically useless. Premise (2) is a general principle that itself stands in need of justification, and premise (1) already deploys the first-person pronoun whose existence it is supposed to establish. The *cogito* was meant to be *prior* to all general principles, not derived from them. Descartes himself denies that it is a syllogism.

**Reconstruction (the performative/self-verifying reading).** The thought is not an inference but an act whose performance guarantees its content:

1. The act of doubting that I exist is itself a case of thinking.
2. To doubt is to exist as a doubter: the occurrence of the doubt entails the existence of a subject of the doubt.
3. Therefore the proposition "I do not exist" cannot be coherently doubted, because the doubting refutes it.

More precisely, following Hintikka: the sentence "I exist" has the property that its *utterance as a judgment* cannot fail to be true, because the act of judging is itself the existence of the judge. It is not that the *proposition* is a tautology; it is that the *performance* is self-verifying.

**The load-bearing premise.** The move from "there is a thinking" to "I think." Descartes needs the subject of thought to be a *substantial self* — a *res cogitans* — and the argument at best delivers an occurrence of thinking with an indexical subject-position attached. Lichtenberg's objection is the classic statement of the gap: strictly, all we are entitled to is "it thinks" or "there is thinking," not "I think." The "I" is an inference, not a datum.

**Strongest objection.** The *cogito* establishes at most an *indexical* certainty: that *this* thinking is occurring, here, now. It does not establish (i) that there is a persisting self, (ii) that the self is immaterial, or (iii) that the self is the same across time. The move from the punctual certainty to a substantial soul is made in the *Meditations* by further arguments — the piece of wax, the simplicity argument — and those arguments are far weaker than the *cogito* itself. Hume's bundle theory and the Buddhist *anattā* analysis both accept the occurrence of thought while denying the substantial self. Sartre's version is instructive: the *cogito* yields a *pre-reflective* consciousness, which is not yet an ego; the ego is constructed at the reflective level.

**Replies.**

- **Frankfurt:** the *cogito* is not an inference but an *intuition* of a necessary connection; the certainty is not evidential but constitutive. Doubting is a mode of thinking, and thinking is a mode of being.
- **The essential indexical (Perry):** the content "I exist" cannot be reduced to any impersonal proposition, and that irreducibility is itself an argument for the reality of the subject-position. This does not give Descartes a substance, but it gives him more than Lichtenberg allows.
- **Williams's diagnosis:** Descartes needs the *cogito* to be immune to doubt *and* to be the foundation of a system; no single proposition can do both, because the certainty of the *cogito* is a certainty about an act, not about the world.

**Verdict: Refuted in strong form; a limited certainty survives.** As a refutation of skepticism, the *cogito* fails: it establishes the occurrence of thought, not the existence of a substantial, persisting, immaterial soul, and it leaves the problem of the external world and of other minds exactly where it was. But it survives as one of the very few things that cannot be coherently doubted, and its methodological lesson — that the doubter is implicated in the doubt — is permanent. The *cogito* is the paradigm of an argument that is *certain* without being *foundational*. (*Ch. 6, 26*)

---

## 3. Berkeley's Master Argument

**Source.** Berkeley, *A Treatise Concerning the Principles of Human Knowledge* (1710), §§22–23; *Three Dialogues between Hylas and Philonous* (1713), First Dialogue.

**The argument.** Berkeley's target is the "opinion strangely prevailing amongst men, that houses, mountains, rivers, and in a word all sensible objects, have an existence, natural or real, distinct from their being perceived by the understanding." His argument is a challenge: try to conceive it.

> It is indeed an opinion strangely prevailing amongst men... But, say you, surely there is nothing easier than to imagine trees, for instance, in a park, or books existing in a closet, and nobody by to perceive them. I answer, you may so, there is no difficulty in it; but what is all this, I beseech you, more than framing in your mind certain ideas...? But do not you yourself perceive or think of them all the while? This therefore is nothing to the purpose; it only shows you have the power of imagining or forming ideas in your mind; but it does not show that you can conceive it possible that the objects of your thought may exist without the mind.

**Reconstruction.**

1. To conceive of an object is to have it before the mind — that is, to perceive it, in the broad sense of "perceive" that includes imagining.
2. Whatever is conceived is, in the conceiving, perceived (by the conceiver).
3. The inconceivable cannot be a genuine possibility.
4. Therefore it is impossible that an object should exist unperceived.

**The load-bearing premise.** The slide from (2) to (4). Berkeley needs:

$$(\forall x)(\text{conceiving } x \to x \text{ is conceived})$$

but the conclusion requires:

$$(\forall x)(\text{conceiving } x \to x \text{ is perceived})$$

and these are different. The first is a tautology about the act of conceiving; the second says something about the *object* conceived — that it has the property of being perceived. The inference from the one to the other is the fallacy diagnosed by the early commentators as the confusion between *the idea in the mind* and *the object of the idea*. When I imagine a tree in an empty park, the *imagining* is mental; the *tree imagined* need not be.

**Strongest objection.** The argument conflates the *act* of conceiving with the *object* conceived (the "conceiving–conceived" confusion). A second, independent objection: from "I cannot conceive of $x$ without $\phi$-ing" it does not follow that "$x$ cannot exist without being $\phi$-ed," since my conceptual limitations are not constraints on reality. The history of science is a catalog of things once inconceivable and now actual (action at a distance, non-Euclidean geometry, quantum superposition).

**Replies.**

- **The semantic reading.** Berkeley's conclusion can be recast as a claim about *content* rather than possibility: the notion of a mind-independent object is not a coherent notion, because any attempt to spell out what it would be to verify a claim about such objects reduces to a claim about possible experiences. On this reading the master argument is not a *reductio* but an invitation to analyze the concept — and the analysis produces phenomenalism rather than the crude conclusion that Berkeley is usually saddled with.
- **The idealist's response to the fallacy charge:** if one grants the representationalist picture according to which what is before the mind is always an *idea*, then the object of thought just *is* the idea, and the distinction between act and object collapses. But this is the conclusion, not a premise; the argument cannot assume it.
- **Berkeley's own best defense:** the master argument is not meant to *prove* idealism but to *silence* the realist's claim to have a coherent alternative. It is an argument from the unavailability of a competing conception, not a proof from premises.

**Verdict: Refuted in strong form; a semantic residue survives.** As a refutation of realism it fails, and the fallacy is elementary once stated. But it is a permanent contribution: it forces the realist to explain how thought "reaches beyond" the given, and it is the ancestor of the whole family of arguments — verificationism, phenomenalism, internal realism — that locate the difficulty in the *content* of the realist's claim rather than in its truth. (*Ch. 5, 20, 31*)

---

## 4. The Argument from Illusion

**Source.** The classical statements: Hume, *Treatise* I.iv.2; Russell, *The Problems of Philosophy* (1912), ch. 1; Ayer, *The Foundations of Empirical Knowledge* (1940). The critique: Austin, *Sense and Sensibilia* (1962). The revival: disjunctivism (Hinton 1973; McDowell 1982; Martin 2004).

**The argument.** Russell's table: it looks different from different angles, changes color in different lights, and its apparent shape varies with the observer. Yet "the real table, if there is one, is not the same as what we immediately experience by sight or touch or hearing." The inference is that what we are immediately aware of is not the table but a *sense-datum*.

**Reconstruction.**

1. In cases of illusion and hallucination, one is directly aware of something that is not a public material object (a bent-looking stick, a pink rat). — premise
2. The experience in such a case is subjectively indistinguishable from a veridical experience of the "same" kind. — premise
3. If two experiences are subjectively indistinguishable, they must have the same immediate object (or at least the same intrinsic experiential nature). — premise (the "common factor" thesis)
4. Therefore in the veridical case one is directly aware of something of the same kind as in the illusory case. — from (2), (3)
5. Therefore what one is directly aware of in perception is never a material object, but a sense-datum. — from (4)

**The load-bearing premise.** (3), the common-factor thesis. Everything else is comparatively uncontroversial: illusion and hallucination occur (1), and the experiences are often indistinguishable from the subject's point of view (2). The question is whether indistinguishability *from the inside* entails sameness of *object* or sameness of *intrinsic nature*.

**Strongest objection.** Disjunctivism denies (3): veridical perception and hallucination are not two species of a common experiential kind. In the veridical case, the subject stands in a direct relation to a mind-independent object; in the hallucinatory case, no such relation obtains. The two may be *subjectively indistinguishable* — the subject cannot tell, from the inside, which is which — without sharing a common experiential *constituent*. Compare: a genuine coin and a perfect counterfeit are indistinguishable to the naked eye without being the same kind of thing. Austin adds a second objection: the argument treats "material objects" and "sense-data" as exhaustive categories and treats all cases of perceptual error as homogeneous, when in fact "illusion," "delusion," "hallucination," and "misperception" are a mixed bag with different structures.

**Replies.**

- **The disjunctivist must explain the indistinguishability.** If the two cases share no experiential factor, why can't the subject tell them apart? The reply is that indistinguishability is a fact about *epistemic access*, not about *phenomenal constitution* — but this is exactly what is disputed, and the burden is real.
- **The sense-datum theorist can retreat** to the claim that we are aware of *appearances*, where "appearance" is neutral between realist and idealist readings. This is the "adverbial" or "intentionalist" move: the experience is a *way of representing*, not a relation to a private object.
- **Naive realism** (Martin, Campbell) holds that in veridical perception the object itself is a constituent of the experience. It must then say what the hallucinating subject's experience is *of* — and the answer, "nothing," is the price of the position.

**Verdict: Rejected in its classical form; the premise is not dead.** The argument from illusion is no longer accepted as a proof of sense-data, because (3) is recognized as a substantive thesis rather than a datum. But the *phenomenological* observation behind it — that experience is not transparent to its object — remains the central difficulty for naive realism, and the disjunctivist response is itself a substantial and contested research program. The argument's historical importance is enormous: it generated the sense-datum theory, phenomenalism, and the whole problematic of the "veil of perception." (*Ch. 5, 6, 20*)

---

## 5. The Gettier Case

**Source.** Edmund Gettier, "Is Justified True Belief Knowledge?", *Analysis* 23 (1963), 121–123. The counterexample form, not an argument: Gettier gives two cases and draws a conclusion about the analysis.

**The case (Gettier's first).** Smith and Jones are applicants for a job. Smith has strong evidence for the conjunctive proposition:

> (a) Jones will get the job, and Jones has ten coins in his pocket.

From (a) Smith infers:

> (b) The man who will get the job has ten coins in his pocket.

Smith's evidence for (a) is excellent (the employer told him; he counted the coins himself), and he is justified in believing (b). In fact, Smith will get the job, and Smith — not Jones — has ten coins in his pocket. So (b) is true, Smith believes it, and Smith is justified in believing it. But Smith does not know (b): his belief is true only because of the coins in his own pocket, which he knows nothing about.

**Reconstruction (as a refutation of the JTB analysis).**

1. (JTB) $S$ knows that $p$ iff (i) $p$ is true, (ii) $S$ believes that $p$, and (iii) $S$ is justified in believing that $p$. — the target analysis
2. In the Gettier case, conditions (i), (ii), and (iii) are all satisfied. — premise (the case)
3. In the Gettier case, $S$ does not know that $p$. — premise (the intuition about the case)
4. Therefore (JTB) is false. — from (2), (3)

**The load-bearing premise.** The JTB analysis itself, in its *sufficiency* direction. The case does not threaten the necessity of justification or truth; it threatens the claim that justification plus truth is *enough*. The lesson is usually put as a slogan: **knowledge is not merely justified true belief, because justification and truth can come apart in a way that leaves the belief true only by luck.**

**Strongest objection (to the counterexample, not the conclusion).** Some externalists (and some virtue epistemologists) deny premise (3) or premise (2). If Smith's belief is *not* justified — because the process producing it is unreliable in the relevant respect, or because the justification is defeated by the fact that the evidence, though good, is misleading — then the case does not satisfy the JTB conditions at all. Alternatively, if one adopts a safety condition, Smith's belief is unsafe (in nearby worlds he believes (b) and it is false), so it is not knowledge, and the case is explained without abandoning the analysis. The force of the case therefore depends on a *fallibilist internalist* conception of justification, on which Smith's evidence genuinely justifies.

**Replies and the industry.** The literature divides into four families of fourth conditions:

- **No-defeater conditions:** knowledge requires that there be no true proposition which, if added to $S$'s evidence, would defeat the justification (Lehrer, Paxson).
- **Causal conditions:** the belief must be causally connected, in the right way, to the fact that makes it true (Goldman 1967).
- **Sensitivity/tracking:** if $p$ were false, $S$ would not believe it (Nozick).
- **Safety:** $S$'s belief could not easily have been false (Sosa, Williamson).

Each faces its own counterexamples; the industry is a demonstration of how hard it is to state a condition that is neither too strong (excluding ordinary knowledge) nor too weak (admitting Gettier cases).

**Verdict: Decisive constraint.** The Gettier case is not an argument in the traditional sense but a counterexample of singular efficiency, and it established a boundary: *any* analysis of knowledge must explain why justified true belief can be true only by accident. Its deeper lesson, drawn by Williamson and by the knowledge-first tradition, is that the project of analyzing knowledge into belief plus independent conditions may be misguided — that knowledge may be the primitive. (*Ch. 7, 8*)

---

## 6. The Zombie Argument

**Source.** David Chalmers, *The Conscious Mind* (1996), ch. 3; the antecedents in Kirk (1974) and in the Leibnizian "mill" argument. The replies: the type-A/type-B/type-C physicalist taxonomy of Chalmers (2003) and Stoljar (2006).

**The argument.** A *philosophical zombie* is a being physically and functionally identical to a normal human, in an identical environment, but with no phenomenal experience: "all is dark inside." Chalmers:

> Zombies are conceivable. ... If zombies are conceivable, they are metaphysically possible. ... If zombies are possible, then physicalism is false.

**Reconstruction.**

1. It is conceivable that there should be a being physically identical to me, in an identical environment, with no phenomenal experience. — premise (conceivability)
2. If a situation is ideally conceivable, it is metaphysically possible. — premise (CP thesis)
3. Therefore zombies are metaphysically possible. — from (1), (2)
4. If zombies are metaphysically possible, then the physical facts do not necessitate the phenomenal facts. — premise
5. Physicalism entails that the physical facts necessitate the phenomenal facts (the physical facts fix all the facts). — premise
6. Therefore physicalism is false. — from (3), (4), (5)

The argument is a *modus tollens* on the physicalist's own supervenience thesis: if the physical facts fix the phenomenal facts, a physically identical world must be phenomenally identical; but a zombie world is physically identical and phenomenally different; so the fixing relation fails.

**The load-bearing premise.** (2), the conceivability–possibility thesis — or, if one accepts (2), premise (1). The argument is valid if (2) holds; the entire dispute is about whether ideal conceivability is a reliable guide to metaphysical possibility in the phenomenal case.

**Strongest objection (the type-B physicalist reply).** There can be *a posteriori necessary identities* between physical and phenomenal properties, exactly as there are between water and H₂O. "Water is not H₂O" was once conceivable, but it is not possible, because the identity is necessary though discovered empirically. By parity, "zombies exist" may be conceivable in our present state of ignorance, and yet impossible: once we understand the physical nature of experience, the zombie scenario will be seen to be like the scenario of water without H₂O. The apparent conceivability is an artifact of our incomplete concepts. (Loar, Papineau, Tye, Carruthers.)

**Reply to the objection.** The water case works because there is an *independent* handle on the essence — we can identify H₂O by its causal role and then discover that it is the stuff we called water. In the phenomenal case, there is no such independent handle: the phenomenal property is *given* in experience, and no empirical discovery could reveal that it "really was" something else. The conceivability of zombies is therefore not the same kind of ignorance-generated illusion; it is the expression of the fact that we have *no conception at all* of how physical facts could necessitate phenomenal ones. This is the epistemic gap, and the type-B reply simply relabels it. (Chalmers's "meta-problem" is the further move: even if we cannot close the gap, we can explain why it *seems* unclosable.)

**Objection (the type-A reply).** Phenomenal consciousness, as Chalmers conceives it, is illusory or at least not a further fact over the functional facts (Dennett, Frankish). If so, the zombie is either impossible or is simply a normal human described oddly: there is nothing further for the zombie to lack. This is *illusionism*, and it denies (1) or, more subtly, denies that (1) has the significance claimed.

**Verdict: Live; it forces a choice.** The zombie argument has not refuted physicalism — the type-B reply is a serious option, and illusionism is a serious option. But it has imposed a structure on the debate: every physicalist must now say which of the premises they reject, and each rejection has a cost. The argument is best understood not as a proof but as a *dilemma generator*, and its lasting contribution is to have made the epistemic gap between the physical and the phenomenal the central datum that any theory of mind must accommodate. (*Ch. 24, 25*)

---

## 7. The No-Miracles Argument

**Source.** Hilary Putnam, *Mathematics, Matter and Method* (1975); Richard Boyd (1984); the canonical formulation and critique in van Fraassen, *The Scientific Image* (1980). The pessimistic counter: Laudan (1981); the structuralist reply: Worrall (1989).

**The argument.** The success of science — especially its *novel* predictive success, where a theory predicts a phenomenon no one was looking for — would be a miracle if the theory were not at least approximately true. We should not accept miracles. So our best theories are approximately true.

**Reconstruction.**

1. Our best mature scientific theories enjoy extraordinary predictive and manipulative success, often in novel domains. — premise
2. This success stands in need of explanation. — premise (explanatory demand)
3. The only available explanation is that the theories are at least approximately true, and that their central theoretical terms refer. — premise
4. If a theory were not approximately true, its success would be an inexplicable coincidence — a miracle. — from (2), (3)
5. We should not accept miracles as explanations. — premise
6. Therefore our best theories are approximately true. — from (4), (5)

In abductive form: realism is the hypothesis that best explains the success of science, and we should believe the best explanation.

**The load-bearing premise.** (3): that truth (or approximate truth) is the *only* adequate explanation of success. Everything turns on whether there are non-truth-conducive explanations of predictive success — selection effects, the pragmatic construction of theories around the phenomena, or the possibility that a false theory can be empirically adequate.

**Strongest objection (the pessimistic meta-induction).** Laudan: the history of science is a graveyard of theories that were empirically successful and are now taken to be false — Ptolemaic astronomy, phlogiston chemistry, caloric theory, the ether, Newtonian mechanics at high velocity. If the history of science shows successful-and-false theories in the past, we have inductive reason to expect that our present theories are also successful-and-false. The no-miracles argument then proves too much: it would have licensed realism about phlogiston.

**Replies.**

- **Structural realism (Worrall):** what survives theory change is the *structure* — the mathematical relations — even when the entities are discarded (the ether's structure survived in relativity; Fresnel's equations survived Maxwell). So the realist should be a realist about structure, not about the intrinsic natures of theoretical entities. This blunts the meta-induction, at the cost of a thinner realism.
- **Selective realism (Psillos, Kitcher):** the theories that were successful-but-false were not successful *in the same way*; the parts of them that did the predictive work are the parts that were retained. The meta-induction relies on a coarse-grained notion of "theory" that ignores which components were actually responsible for success.
- **The base-rate problem (Magnus & Callender):** even if truth raises the probability of success, the prior probability of any given theory's being true may be so low that a successful theory is still probably false. The no-miracles argument is an informal likelihood argument that ignores the base rate; when made precise, it may not support the conclusion. This is the strongest statistical objection.
- **Van Fraassen's diagnosis:** the argument is an inference to the best explanation, and inference to the best explanation is only legitimate *if* one already takes explanatory considerations as truth-conducive — which is exactly what the constructive empiricist denies. The argument therefore begs the question against the anti-realist, or at least it is a piece of *realist* methodology applied to a dispute about realism.

**Verdict: Live; strong in modest form, weak in the ambitious form.** As an argument for full-blown realism — the literal truth of our best theories and the existence of all their central posits — it is vulnerable to the meta-induction and to the base-rate objection. As an argument for *some* form of realism (structural, or selective, or "the theories latch onto the world in some way") it is considerably stronger. Its true function is diagnostic: it makes explicit that realism is an explanatory hypothesis, and it forces the anti-realist to explain success without invoking truth. (*Ch. 40, 41*)

---

## 8. The Problem of Evil

**Source.** The logical problem: J. L. Mackie, "Evil and Omnipotence," *Mind* (1955). The Free Will Defense: Plantinga, *The Nature of Necessity* (1974), ch. 9. The evidential problem: William Rowe, "The Problem of Evil and Some Varieties of Atheism" (1979). Skeptical theism: Wykstra (1984); the "cornerstone" critique: Almeida & Oppy, and others.

**The logical argument.** The classical form (Mackie):

1. God is omnipotent, omniscient, and wholly good. — definition of theism
2. An omnipotent being could prevent all evil. — from omnipotence
3. An omniscient being would know of all evil. — from omniscience
4. A wholly good being would want to prevent all evil it knew of and could prevent. — from perfect goodness
5. Therefore, if God exists, there is no evil. — from (2)–(4)
6. There is evil. — premise (empirical)
7. Therefore God does not exist. — from (5), (6)

**The logical argument's load-bearing premise.** The inference from (4) to (5): that a wholly good being would prevent *any* evil it could, without exception. This requires the further premise that there is no *morally sufficient reason* for permitting evil — and that premise is a modal claim about what reasons God could have, which is precisely what the theist denies.

**The Free Will Defense.** Plantinga's response is not a theodicy (an account of what God's actual reason is) but a *defense*: it suffices to show that the conjunction of God's existence and evil is *possibly* explained by a morally sufficient reason. The defense: it is possible that God permits evil because a world containing significantly free creatures who sometimes do evil is more valuable than a world of automata, and because the existence of free creatures is a necessary condition of certain great goods (love, moral goodness, the possibility of heroism and compassion). Since the logical argument requires a *necessary* connection between God and the absence of evil, a possible sufficient reason defeats it. Mackie's argument is generally conceded to have failed as a deductive proof; even Mackie later allowed that the Free Will Defense is a successful defense, though not a theodicy.

**The evidential argument (Rowe).**

1. There exist instances of intense suffering which an omnipotent, omniscient being could have prevented without thereby losing some greater good or permitting some evil equally bad or worse. — premise (the "noseeum" inference, or rather its denial)
2. An omnipotent, omniscient, wholly good being would prevent any such suffering. — premise
3. Therefore there is no omnipotent, omniscient, wholly good being. — from (1), (2)

The evidential form does not claim that evil is logically incompatible with God; it claims that the *amount and distribution* of suffering makes theism improbable. The argument is probabilistic: the data of evil are more likely on the hypothesis of atheism than on the hypothesis of theism.

**Skeptical theism.** The reply targets premise (1): given our cognitive limitations, we are in no position to judge that a given instance of suffering has no unknown greater good. Wykstra's "COR(NEA)": we should not expect to see the goods that justify God's permission, any more than a child can see the reasons for a parent's restrictions. If the skeptical premise is accepted, the evidential argument loses its evidential force, because we cannot know that an instance of suffering is *gratuitous*.

**Objections to skeptical theism.** (i) It proves too much: if we cannot judge that a given evil is gratuitous, can we judge that a given good is genuinely good? The skepticism threatens to undercut moral knowledge altogether (the "abducting skeptical theism" objection). (ii) It makes God's goodness unknowable in principle, which strains the concept of a *morally* perfect being. (iii) The appeal to unknown goods, if unrestricted, renders any amount of suffering compatible with theism, which many take to be a reductio of the position.

**Verdict: The logical form is refuted; the evidential form is live.** The deductive problem of evil is now widely regarded as defeated by the Free Will Defense (or by the more general point that the argument needs an unjustified modal premise). The evidential problem remains one of the strongest considerations against theism, and its force is essentially a matter of how much weight one gives to the skeptical-theist move. The debate is a model of how an argument can migrate from the deductive to the probabilistic register, and of how the burden of proof shifts with it. (*Ch. 50*)

---

## 9. The Open Question Argument

**Source.** G. E. Moore, *Principia Ethica* (1903), §13. The critique: Frankena (1939), and the synthetic-naturalist revival (Cornell realism: Boyd, Sturgeon, Railton).

**The argument.** Moore's target is "naturalism" in ethics: the identification of "good" with some natural property $N$ — pleasure, desire-satisfaction, evolutionary fitness, or what have you.

**Reconstruction.**

1. Suppose "good" means the same as $N$ (a natural property). — assumption for *reductio*
2. Then the question "I know that $x$ is $N$; but is $x$ good?" would be equivalent to "I know that $x$ is $N$; but is $x$ $N$?" — by substitution of synonyms.
3. The latter question is trivial: it is closed, its answer is guaranteed by the meaning of the terms.
4. The former question is *open*: it is intelligible, it is not trivial, and a competent speaker can seriously entertain it. — premise (the intuition)
5. Therefore "good" does not mean $N$, for any natural $N$. — from (1)–(4)
6. Therefore the good is not a natural property — it is a simple, non-natural, indefinable property. — Moore's conclusion

**The load-bearing premise.** (2)/(4): that *meaning identity* would render the question trivial and that the question is, in fact, not trivial. The argument is a test of alleged analytic identities by a speaker's competence: if the identity held analytically, the question would be closed to anyone who understood the terms.

**Strongest objection (Frankena).** The argument conflates *openness to a speaker* with *semantic non-identity*. A question can be open — genuinely informative, not trivial — even when the identity holds, if the identity is *a posteriori*. "I know this is water; but is it H₂O?" was an open question before chemistry, and it remains informative for anyone ignorant of the identity. If that is allowed, Moore's argument proves only that "good" is not *analytically* equivalent to $N$ — it does not show that it is not *synthetically* identical to some natural property. The naturalist can accept the premise and deny the conclusion.

**Replies.**

- **Moore's own reply:** "good" is a simple notion, so there is no room for a synthetic identity of the water/H₂O kind; the identity would have to be graspable by analysis, and analysis of a simple notion is impossible. But this is an additional, contestable premise, not a consequence of the argument.
- **The synthetic naturalist's reply (Cornell realism):** moral properties are natural properties, but the identity is a posteriori and discovered by empirical and moral inquiry, not by conceptual analysis. The open question is the mark of an a posteriori identity, not of a non-natural property. This is the position the open-question argument was designed to refute, and it survives the argment.
- **The expressivist's reply:** the "openness" reflects the *practical*, action-guiding character of moral judgment, not a semantic gap. The question is open because answering it requires a practical stance, not because the property is non-natural.

**Verdict: Partial success; it defeats analytic naturalism only.** The argument is a decisive refutation of the thesis that "good" is *synonymous* with a natural predicate. It does not refute naturalism *tout court*, because the synthetic naturalist can accept every premise. Its lasting contribution is the demonstration that moral concepts are not trivially reducible to descriptive ones — and, more broadly, the invention of the "open question" technique as a test of conceptual identity, which is now used far beyond ethics. (*Ch. 44, 36*)

---

## 10. The Companions in Guilt Argument

**Source.** Mackie, *Ethics: Inventing Right and Wrong* (1977), ch. 1 (the argument from queerness); the "companions in guilt" strategy as a realist counter to error theory: Cuneo, *The Normative Web* (2007); Shafer-Landau, *Moral Realism* (2003); the error-theoretic reply: Streumer, *Unbelievable Errors* (2017).

**The structure.** Mackie argues that moral facts would be "queer": they would be intrinsically prescriptive, motivating by their nature, and accessible only by a special faculty of moral intuition. Since we have no reason to believe in such entities, moral discourse is systematically false. The companions-in-guilt reply turns the argument against the error theorist:

**Reconstruction (realist direction).**

1. There are normative facts of other kinds that we cannot reasonably deny: epistemic facts (there are correct and incorrect inferences, reasons to believe, justified and unjustified beliefs), logical facts, and mathematical facts. — premise
2. These facts are non-natural, irreducible, and known by something like rational insight. — premise
3. Whatever makes moral facts "queer" — their prescriptive character, their non-naturalness, their requiring a special faculty — applies equally to these other normative facts. — premise
4. Since we accept the latter, we should accept the former; the error theorist's argument, if sound, would commit us to a general normative skepticism that no one can live with. — from (1)–(3)
5. Therefore moral realism is no worse off than the realism we already accept about epistemic and logical norms. — conclusion

**The load-bearing premise.** (3): that moral and epistemic normativity are of the same kind, so that whatever makes moral facts objectionable makes epistemic facts objectionable too. *This is where the argument lives or dies.*

**Strongest objection.** The disanalogy: moral facts are supposed to be *practically authoritative* — they give reasons for action, and their violation merits blame — while epistemic facts are *theoretical*: they give reasons for belief, but their violation is a cognitive failing, not a moral one. Mackie's "objective prescriptivity" is a claim about the *action-guiding* force of moral facts, and the companion facts do not obviously share it. If so, the queerness is specific to morality, and the parity fails. (This is Brink's and, differently, Parfit's line of reply from the realist side; and it is Streumer's line from the error-theoretic side: epistemic facts are *also* queer, and the correct conclusion is a *global* normative error theory, which is unbelievable but true.)

**Replies.**

- **Cuneo's reply:** epistemic facts *are* practically authoritative — they generate genuine requirements ("you ought not believe against the evidence"), and violations are criticizable in a way that is not merely instrumental. The distinction between theoretical and practical normativity is real but does not mark a difference in *kind* of queerness.
- **The "unbelievable" reply (Streumer):** the fact that a global normative error theory is unbelievable does not make it false; it only explains why we cannot bring ourselves to believe it. The companions-in-guilt argument then becomes an argument for a *general* anti-realism, not for moral realism specifically — the guilt spreads rather than being discharged.
- **The deflationary reply:** both moral and epistemic "facts" are expressive or institutional; neither is queer because neither is a sui generis entity. The argument presupposes a realist reading of the companion facts.

**Verdict: Live; it cuts both ways.** The argument is structurally elegant and has shifted the burden onto the moral error theorist to explain why the queerness does not generalize. But its conclusion depends entirely on whether the kind-identity in premise (3) holds, and the two available resolutions — accept moral facts, or reject all normative facts — are both costly. It is the best current example of a *parity argument*, and of how an argument can be turned against its author. (*Ch. 44*)

---

## 11. The Original Position

**Source.** John Rawls, *A Theory of Justice* (1971), §§3–4, 20–30, 40–46; restated in *Political Liberalism* (1993), Lecture I and II.

**The argument.** Rawls's contractualism is not a historical hypothesis but a *device of representation*: the principles of justice are those that would be chosen by free, equal, rational, and mutually disinterested parties in a hypothetical situation of fair choice — the original position — behind a *veil of ignorance* that deprives them of knowledge of their own social position, natural talents, conception of the good, and generation.

**Reconstruction (the argument from the original position).**

1. The principles of justice are the principles that would be agreed to by free, equal, rational, mutually disinterested parties in a fair choice situation. — premise (the constructivist method)
2. The original position, with its veil of ignorance, is the fair choice situation: it models the conditions under which any agreement is fair. — premise
3. In that situation, the parties do not know their place in society, their talents, or their conception of the good; they must choose principles that will protect their interests whatever their eventual position. — from the description of the veil
4. Under those conditions, the parties will use *maximin* reasoning: they will choose the alternative whose worst outcome is better than the worst outcome of any other alternative. — premise (the decision-theoretic claim)
5. Maximin selects the two principles: (a) equal basic liberties, and (b) inequalities are permitted only if they satisfy fair equality of opportunity and the difference principle (they maximize the position of the least advantaged). — premise (the derivation)
6. Therefore the two principles are the principles of justice. — from (1)–(5)

**The load-bearing premise.** (4), the maximin claim — or, more precisely, the conjunction of (2) and (4): that the veil of ignorance is the right model of fairness *and* that rational choice under that veil yields the two principles. Note that the argument is not a deductive proof from definitions; it is a *construction*, whose adequacy is judged by reflective equilibrium with our considered convictions.

**Strongest objection (Harsanyi).** Behind a veil of ignorance that makes one's position equiprobable, the rational choice is *expected-utility maximization*, not maximin. Maximin is a rule for radical uncertainty or for catastrophic outcomes, not for a decision under risk. And expected-utility maximization behind the veil yields *utilitarianism*, not the difference principle. The original position, properly specified, is an argument for utilitarianism — the opposite of Rawls's conclusion.

**Further objections.**

- **Nozick:** nothing follows from a hypothetical agreement; actual consent is what binds, and the original position is a "miracle" that generates entitlements from nowhere.
- **The thin theory of the good:** the parties are supposed to choose principles without knowing their conception of the good, but they need *some* theory of primary goods to rank outcomes. The thin theory may smuggle in substantive liberal commitments.
- **The arbitrariness of the veil:** why should the parties not know their talents? If they did, the choice would be different; the veil's thickness is a substantive moral assumption, not a neutral modeling choice.

**Replies.**

- **Rawls's own restatement:** the original position is not a decision-theoretic derivation but a *device of representation* whose output is judged by reflective equilibrium. The maximin argument is a heuristic; the deeper justification is that the two principles match our considered convictions in wide reflective equilibrium, and that they provide a *public* basis of justification in a pluralistic society.
- **The Harsanyi reply:** Rawls can argue that the parties are choosing *principles for a basic structure they will live under*, not gambles on a single life; the "strains of commitment" argument is supposed to show that the parties cannot risk the worst outcome, which rules out the utilitarian lottery.
- **The constructivist reply:** the point of the original position is not to model a decision but to make vivid the *moral point of view* — impartiality, reciprocity, and the rejection of arbitrary advantage. Its justification is practical, not theoretical.

**Verdict: Fails as deduction; succeeds as a device.** The original position does not prove the two principles from the description of the parties; the derivation depends on the maximin premise, which is contestable, and on the specification of the veil, which is a moral choice. But as a *device of representation* — a way of making the demands of impartiality vivid and public — it is one of the most productive constructions in the history of political philosophy, and its method (construct a fair choice situation, derive principles, test against convictions) is now standard. The lesson is that a formal model can be philosophically illuminating even when it is not probative. (*Ch. 47, 3*)

---

## 12. The Experience Machine

**Source.** Robert Nozick, *Anarchy, State, and Utopia* (1974), pp. 42–45.

**The argument (against hedonism).**

1. Hedonism: a person's well-being consists entirely in the balance of pleasurable and painful experience. — target thesis
2. We would not choose to plug into an experience machine that would give us maximally pleasant experiences for the rest of our lives, at the cost of contact with reality. — premise (the intuition)
3. If hedonism were true, we *would* choose the machine, since it maximizes the only thing hedonism says is good. — premise
4. Therefore hedonism is false: we value reality, activity, and achievement in addition to, or instead of, experience. — from (2), (3)

Nozick's three reasons for refusing: (i) we want to *do* things, not merely seem to do them; (ii) we want to *be* a certain kind of person, not merely seem to be; (iii) the machine limits us to a manufactured reality, and we value contact with a deeper reality.

**The load-bearing premise.** (2), the intuition about what we would choose — and, behind it, the assumption that our choices are a guide to what is good for us.

**Strongest objection.** The argument tests *preferences*, not *welfare*. The hedonist can respond:

- **The status quo bias:** we are attached to our actual lives and averse to radical change; the refusal may reflect loss aversion, not a judgment about value.
- **The false belief reply:** we refuse because we believe the machine's experiences are not "real," and that belief would be *false* inside the machine (or irrelevant to the welfare it delivers). The hedonist can say the refusal is based on a confusion, so it is not evidence against hedonism.
- **The paternalism reply:** our considered preferences may not track our good; the hedonist's claim is about what *is* good for us, not about what we *think* is good.
- **The adaptation reply:** people who have been on the machine (in the actual world, e.g., long-term immersive VR) may report high well-being; the intuition may be culturally parochial.

**Replies.**

- **The "experience requirement" is not merely a preference:** the intuition survives reflection, and it is not obviously a bias. It is a judgment about what makes a life go well, and it is widely shared. If a theory of welfare implies that all our reflective judgments about welfare are systematically mistaken, that is a cost for the theory.
- **The argument also refutes desire-satisfaction in its actual-desire form:** if what we want is to *do* things, and the machine delivers only the experience of doing them, then actual-desire satisfaction is not sufficient for welfare either. The machine is thus a probe for any theory, not just hedonism.
- **The objective-list reply:** the intuition supports an objective-list view on which achievement, knowledge, and reality-contact are goods independent of experience. This is the most common contemporary response.

**Verdict: A powerful probe, not a proof.** The experience machine does not refute hedonism, because the hedonist can explain the intuition away. But it is the single most efficient thought experiment in value theory: it forces any theory of well-being to say what it is about a life that makes it go well, and it has been decisive in the shift from pure hedonism to hybrid and objective-list accounts. Its lesson is methodological as much as substantive: a thought experiment can be probative without being conclusive, if it isolates the right variable. (*Ch. 48*)

---

## 13. The Liar Paradox

**Source.** Eubulides of Miletus (4th c. BCE); the modern discussion: Tarski (1933), Kripke (1975), Burge (1979), Priest (1987), Field (2008).

**The paradox.** Consider:

> $L$: This sentence is false.

**Derivation.**

1. $L$ is either true or false. — bivalence
2. Suppose $L$ is true. Then what it says is the case: it says that $L$ is false. So $L$ is false. Contradiction.
3. Suppose $L$ is false. Then things are as it says, so $L$ is true. Contradiction.
4. Therefore, from bivalence, a contradiction follows. — from (1)–(3)

Formally, with $T(\ulcorner L \urcorner)$ for "the sentence $L$ is true" and the T-schema $T(\ulcorner L \urcorner) \leftrightarrow L$:

$$L \leftrightarrow \neg T(\ulcorner L \urcorner) \quad\text{and}\quad T(\ulcorner L \urcorner) \leftrightarrow L \;\vdash\; L \leftrightarrow \neg L$$

The argument shows that a language satisfying (i) classical bivalence, (ii) a truth predicate applicable to all of its own sentences, (iii) the T-schema, and (iv) elementary classical reasoning is inconsistent. At least one of these must go, and each choice has a cost.

**The load-bearing premise.** There is no single premise to attack; the paradox is a *joint* inconsistency, and the philosophical work is in deciding which conjunct to give up. The history of the problem is the history of those choices.

**The solutions and their costs.**

- **Tarski's hierarchy.** No language can contain a truth predicate for its own sentences; truth must be stratified into meta-languages. *Cost:* no single truth predicate for natural language, and the hierarchy seems to falsify the obvious fact that we do talk about the truth of sentences in our own language; moreover, the hierarchy must be expressible, which generates a revenge problem.
- **Kripke's fixed-point theory.** Truth is defined by a groundedness process; some sentences are neither true nor false (ungrounded). *Cost:* the strengthened Liar ("this sentence is not true") forces a truth-value gap, and the gap is itself expressible; revenge again.
- **Contextualism (Burge, Simmons).** The truth predicate is context-sensitive; the Liar shifts the context in which it is evaluated. *Cost:* the context-sensitivity must be specified without circularity, and the account must explain why the sentence seems to have a stable content.
- **Paraconsistency / dialetheism (Priest).** Some sentences are both true and false; the Liar is one of them. *Cost:* a non-classical logic, a revision of the meaning of negation, and the burden of showing that the resulting theory is not merely ad hoc.
- **Deflationism plus a robust account of the truth predicate's function (Field, Horsten).** The T-schema is not the whole story; the truth predicate serves expressive and generalizing functions that constrain its logic. *Cost:* the account is technically demanding and still developing.

**Verdict: Paradox; unsolved.** The Liar is not a puzzle to be dissolved by a clever distinction; it is a structural limit of any language rich enough to talk about its own truth. Every solution pays a price in expressiveness, in classical logic, or in the naivety of the T-schema. Its value is that it forces precision about the concepts of truth, meaning, and validity — and it is the paradigm of a *deep* paradox, one that marks a genuine tension in a conceptual scheme rather than a mere confusion. (*Ch. 32, 33, 35*)

---

## 14. The Rule-Following Paradox

**Source.** Wittgenstein, *Philosophical Investigations* (1953), §§138–242; the skeptical reading and the "quus" example: Kripke, *Wittgenstein on Rules and Private Language* (1982). The exegetical dispute: Wright (1984), Boghossian (1989), and the Wittgenstein literature generally.

**The paradox.** Any rule has only finitely many applications. For any finite segment of behavior, there is always a deviant rule compatible with it. Kripke's example: the function **quus**, defined by

$$x \oplus y = \begin{cases} x + y & \text{if } x, y < 57 \\ 5 & \text{otherwise} \end{cases}$$

I have never computed a sum larger than 56, so my entire past behavior, dispositions, and mental history are compatible with my having meant *quus* all along, not *plus*. What fact about me makes it the case that I meant plus?

**Reconstruction (Kripke's skeptical argument).**

1. A rule must determine what is correct in each new case: if I mean plus, then "68 + 57 = 125" is correct and "= 5" is incorrect. — premise (normativity of rules)
2. The whole of my past behavior, dispositions, and mental states is compatible with my having meant quus all along. — premise (finiteness)
3. There is no fact of the matter about what I meant, over and above the dispositions. — from (1), (2) (the skeptical conclusion)
4. If there is no fact of the matter, then there is no such thing as following a rule; meaning is an illusion. — premise
5. Therefore meaning is not a fact about the individual; it is grounded in communal practice — the "skeptical solution": assertibility conditions, not truth conditions. — Kripke's conclusion

**The load-bearing premise.** (3): that no fact about the individual — dispositional, phenomenal, or intentional — can distinguish meaning plus from meaning quus. The argument is a *reductio* on the idea that meaning is a fact about an individual considered in isolation.

**Strongest objections.**

- **The dispositionalist reply (Blackburn, Fodor):** meaning plus is a disposition to respond in certain ways. But dispositions are finite, and any finite disposition can be characterized in quus-compatible terms; moreover, dispositions explain what I *would* do, not what I *ought* to do — so they cannot capture the normativity in premise (1).
- **The "primitive fact" reply (Wright, Boghossian):** there is a primitive fact of meaning, not reducible to dispositions; Kripke's argument presupposes a verificationist constraint on facts. But then the argument begs the question against the realist about meaning.
- **The normativity objection:** the argument equivocates between *what I would do* and *what I ought to do*. Dispositions do not determine norms; norms are normative all the way down. If so, the skeptical conclusion is a *truism* — meaning is not a dispositional fact — rather than a paradox. The real work is then to give a positive account of the normative fact.
- **The exegetical objection:** Kripke's reading may not be Wittgenstein's. Wittgenstein's target may be the *mental act* of meaning (the picture of a rule as a mental state that contains all its applications), not meaning simpliciter. On the standard reading, Wittgenstein's point is that following a rule is a *practice*, and the "paradox" is dissolved by attending to the form of life in which the practice is embedded.

**Verdict: Deep; the skeptical conclusion is widely resisted.** The argument has not been refuted — the dispositionalist and primitive-fact replies each have costs — but few philosophers accept the skeptical conclusion that there is no fact of the matter about meaning. What is widely accepted is the *constraint*: meaning cannot be located in a mere fact about an individual's past; it must be located in a normative practice, whether communal or otherwise. The paradox is a permanent test of any naturalistic theory of meaning. (*Ch. 31*) *Note:* a caution about the exegesis is in order. Kripke presents the argument as Wittgenstein's; whether it is, and whether the "skeptical solution" is Wittgenstein's or Kripke's invention, are separate questions. The argument is philosophically important either way, but do not attribute it to Wittgenstein without the qualification.

---

## 15. Moore's Hands

**Source.** G. E. Moore, "Proof of an External World" (1939), *Philosophical Papers* (1959); the response: Wittgenstein, *On Certainty* (1969); the modern descendants: Pryor's dogmatism (2000), Wright (1985), Pritchard's hinge epistemology (2012).

**The argument.** Moore holds up his hands and says: "Here is one hand, and here is another." He claims thereby to have proved the existence of an external world.

**Reconstruction.**

1. Here is one hand. — premise (Moore's demonstration)
2. Here is another. — premise
3. Therefore at least two hands exist. — from (1), (2)
4. If at least two hands exist, then there are external objects — things whose existence does not depend on being perceived. — premise (a hand is an external object)
5. Therefore an external world exists. — from (3), (4)

Moore adds a meta-claim: the premises are *more certain* than any premise of the skeptic's argument, and the conclusion follows deductively; so the proof meets the standards of a proof.

**The load-bearing premise.** Not the demonstration (1)–(2) — those are as certain as anything — but the *epistemic* claim that the premises are more certain than the skeptic's premises. The argument is not a derivation from more basic premises; it is a claim of *parity*, or rather of priority: ordinary perceptual knowledge has a default standing that the skeptic's premises lack.

**Strongest objection.** The skeptic's charge: the argument assumes what it is supposed to prove. The premise "here is a hand" is exactly the kind of claim the skeptic doubts; a proof that begins from a premise the interlocutor rejects is not a proof *for that interlocutor*. Moore's argument may be valid, but it is question-begging in the dialectical sense: it does not move the skeptic.

**Replies.**

- **Moore's meta-claim:** the charge of question-begging assumes that the skeptic's doubt has a default priority over ordinary knowledge. But why should it? Moore's claim is that ordinary perceptual beliefs are more certain than the philosophical premises used to undermine them. If so, the burden is on the skeptic to show that the doubt is more reasonable than the belief. This is the "Moorean" strategy: *modus ponens* against the skeptic's *modus tollens*.
- **Wittgenstein's response:** Moore is right to hold up his hands, but wrong to claim *knowledge*. The propositions "here is a hand" are *hinges* — they are exempt from doubt and are not the sort of thing that can be known in the ordinary way, because they are the background against which knowing and doubting take place. The proper description is "this is how I go on," not "I know." This concedes the skeptic's point about knowledge while denying its significance: the skeptic demands a justification for something that does not need one.
- **Dogmatism (Pryor):** perceptual experience itself can justify perceptual belief without the subject's needing independent evidence for the reliability of perception. If so, Moore's premises can be justified by the experiences that accompany them, and the skeptic's demand for a non-circular justification is too strong.
- **Hinge epistemology (Pritchard):** there are hinge commitments that are not beliefs and are not in the market for knowledge; the skeptic's error is to treat them as propositions to be assessed.

**Verdict: Diagnostic; live.** Moore's argument is not a proof in the classical sense — it does not derive its conclusion from premises the skeptic accepts — but it is a *diagnostic* argument of the first importance: it forces a choice between accepting an epistemically privileged starting point (Moore, dogmatism) and explaining why the skeptic's demand is illegitimate (Wittgenstein, hinge epistemology, contextualism). Its value is that it makes explicit the structure of the epistemological problem, and it is the cleanest test case for any theory of the architecture of knowledge. (*Ch. 6, 13*)

---

## C.16 — Five Patterns Across the Hall

Reading the fifteen together reveals recurring structural features. They are worth learning as diagnostic habits.

**1. Every landmark argument has exactly one load-bearing premise, and the history of the argument is the history of attacks on it.** The ontological argument's possibility premise; the *cogito*'s "I think"; the master argument's "conceiving entails conceived"; the illusion argument's "indistinguishability entails sameness"; the no-miracles argument's "truth is the only explanation of success"; the open question's "meaning-identity would render the question trivial." When you meet a new argument, find the premise that, if false, collapses everything. That is where to work.

**2. Most of the great arguments are parity or dilemma arguments, not deductions.** The companions-in-guilt argument, Moore's hands, the *cogito*, the zombie argument, and the rule-following paradox all work by putting the opponent in a position where they must accept a conclusion they did not want or reject a premise they cannot give up. The most efficient philosophical arguments do not prove; they *force a choice*.

**3. Thought experiments are probes, not proofs.** The Gettier case, the experience machine, the zombie, the trolley. A thought experiment earns its status by isolating a variable; it loses it when the intuition it elicits is an artifact of the scenario's construction. The test is always: what is this case a case *of*, and does the intuition survive reflection and variation?

**4. The verdict is rarely "won" or "lost"; it is "shifted the burden" or "constrained the space."** Of the fifteen, only the logical problem of evil and the master argument are widely regarded as *refuted* in their strong forms. The rest are live, or have migrated to a more modest form, or have established a constraint that later theories must respect. Philosophical progress is mostly the accumulation of constraints, not the accumulation of proofs.

**5. Reconstruction is where the philosophy happens.** Every entry above required choices about how to number premises, what to treat as a premise rather than a definition, and which variant to present. Those choices are not neutral: they determine which objection is visible. The most common philosophical error is not a false premise but a *bad reconstruction* — one that makes an argument look better or worse than it is. Learn to reconstruct an argument three ways before deciding what it says.

---

## C.17 — Exercises

1. **Reconstruct the ontological argument without the "existence is a perfection" premise.** Does the modal version survive? What does it need that the Anselmian version does not?
2. **Run the *cogito* as a syllogism and as a performance.** Which is stronger, and why does Descartes deny it is a syllogism?
3. **State the master argument's fallacy in one sentence.** Then give Berkeley the best reply you can, using the semantic reading.
4. **Take the argument from illusion and vary premise (3).** What follows for the sense-datum theory if indistinguishability does *not* entail sameness of object? Is disjunctivism the only alternative?
5. **Construct a Gettier case of your own** that defeats a safety condition. Then construct one that defeats a sensitivity condition.
6. **State the zombie argument in $S5$ notation.** Then identify exactly which premise each of type-A, type-B, and type-C physicalism rejects.
7. **Make the no-miracles argument statistically precise.** Does the base-rate objection defeat it, or can the realist reply by adjusting the prior?
8. **Distinguish the logical from the evidential problem of evil** in terms of the modal status of the key premise. Why does the Free Will Defense defeat the first but not the second?
9. **Run the open-question argument against a synthetic naturalist.** What premise must they reject, and at what cost?
10. **Turn the companions-in-guilt argument around.** What does the error theorist say, and is the resulting global error theory believable? (See Streumer.)
11. **Separate Rawls's maximin argument from his constructivism.** Does the failure of the first undermine the second?
12. **Give the hedonist's best reply to the experience machine**, then give the objective-list theorist's reply to that reply.
13. **State the Liar in T-schema form.** Then show what each of the five solutions gives up.
14. **Distinguish Kripke's skeptical argument from Wittgenstein's own text.** Which conclusion does each support?
15. **Reconstruct Moore's argument as a *modus ponens* and the skeptic's as a *modus tollens*.** What would settle which is the better form?

---

*Cross-references: every argument above is treated at greater length in the chapter indicated, and the terms in bold are defined in Appendix B. The formal notation is set out in Appendix A; the thinkers named are located in Appendix D; the templates for reconstruction are in Appendix E.*

*One closing warning. These fifteen arguments are the most discussed in the discipline, and that is a reason for caution as well as attention. Familiarity breeds the illusion of understanding: a reader can recite the Gettier case without being able to say what it shows, or state the zombie argument without being able to name the premise they would reject. The test of mastery is not reproduction but reconstruction under variation: change a premise, and see whether you can still say what follows. That is the skill this appendix is meant to train.*
