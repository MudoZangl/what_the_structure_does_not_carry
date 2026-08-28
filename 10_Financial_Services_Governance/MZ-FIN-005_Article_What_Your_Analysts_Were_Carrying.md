**Article · financial services**

# What Your Analysts Were Carrying

*Risk data aggregation, agentic AI, and the obligations that have quietly become unowned*

Georg Zangl · drawn from What the Structure Does Not Carry (2026)

**MZ-FIN-005 v1.0 · 17 August 2026 · approx. 3,000 words**

## A failure nobody disputes

In January 2013 the Basel Committee on Banking Supervision issued fourteen principles for effective risk data aggregation and risk reporting. They asked for things no one could reasonably object to. Data should be accurate and have integrity. It should be complete. It should arrive in time to be useful. It should be adaptable to questions nobody had thought of yet. And its lineage should be traceable — an institution should be able to say where a number came from.

More than a decade later, successive supervisory progress reviews have found adoption incomplete. Not at marginal institutions with no money, but across large, well-capitalised banks with senior sponsorship, multi-year programmes, dedicated data offices, and real budgets. The principles were not contested, the deadlines were not secret, and the effort was not withheld.

The usual explanations are all true and all insufficient. Legacy systems, yes. Data silos, yes. Merger archaeology, cost pressure, competing regulatory priorities, the sheer size of the estate — every one of these is a genuine obstacle. None of them explains why so much sustained effort produced so little closure. Institutions have delivered harder things than this in thirteen years.

There is a better explanation, and it is uncomfortable because it implies the programmes were solving the wrong problem. The principles were already being satisfied. They were simply not being satisfied by the architecture.

## Who was actually holding the line

Consider what lineage meant in practice before any programme addressed it. A controller received two figures for the same exposure from two systems and knew which one to trust, because she knew that one of them was fed by a feed that ran before the overnight adjustment and the other after. That knowledge was not documented. It did not need to be, because she was there.

Consider completeness. An analyst noticed that a position was missing from a report because he had seen it the previous week and remembered it. Consider timeliness. A risk officer knew that Tuesday’s number was provisional and Thursday’s was final, and paced her escalation accordingly. Consider accuracy. Someone reconciled, by hand, at the end of every month, and the reconciliation was called data quality work rather than what it was: a human being standing at the boundary between two systems, holding a property that neither system carried.

This work was continuous, skilled, and almost entirely invisible. It never appeared in a project plan because it was already paid for. It generated no procurement, no business case, no capitalised cost. It was salaried, which is the most effective form of camouflage an activity can have. And because it was invisible, the architecture was never asked to do it.

This is the argument in one sentence: the risk data aggregation principles asked for properties the architecture did not hold, and people held them instead. Thirteen years of programmes tried to build into the systems something that was being delivered every day by staff whose contribution nobody had counted — which is why the gap stayed open while the effort was real.

## The subsidy, and what happens when it is withdrawn

The best-documented case of this layer being removed on purpose is not from banking. In 2016 the Canadian federal government consolidated pay administration and introduced a new payroll system. Pay advisers, who held the interpretive knowledge of collective agreements, acting arrangements, retroactive adjustments and the long tail of entitlement edge cases, were removed from the process. The system was to handle it.

Hundreds of thousands of pay errors followed. Remediation ran for years and cost far more than the savings the programme was designed to produce. Official audits and parliamentary reporting document all of it. And the striking thing about the record is what is absent from it: no significant technical failure of the kind that would explain the outcome. The tasks moved. The people who carried the meaning did not move with them, and no system had ever been asked to hold what they held, because nobody had noticed they were holding it.

A payroll process is a ledger process with rules, exceptions and judgement. So is accrual accounting. So is intercompany elimination, collateral eligibility, exposure aggregation, suitability assessment, and every reconciliation in a bank. The mechanism transfers, and the transfer is the point.

## What the failure looks like from the inside

It is worth being precise about the mechanism, because it is not the failure mode most AI governance discussion prepares an institution for.

Take an approval limit: four hundred, a hard ceiling, above which a second signature is required. In one system this is a validation rule. It is testable, documentable, and enforced in one place, and it works.

Now distribute the work. One process originates a request in a planning system. A second evaluates it against a policy retrieved from a document store. A third submits it to procurement through an integration written years ago by someone who has left. The figure four hundred arrives at procurement as a number. The condition that made it a ceiling rather than a budget was never part of the payload, because no interface between those systems was ever specified to carry it. An order is placed above the cap.

Nothing malfunctioned. No model was wrong, no data was corrupt, no system deviated from its specification. Every value was accurate. The obligation — that the limit be enforced — was satisfied nowhere, because it had been assigned to nothing.

This is a meaning error, and it is invisible to every data quality control an institution owns, for the simple reason that the data is not faulty. It is also invisible to conformity assessment conducted system by system, because no system is at fault. It shows up much later, as an outcome that is individually explicable and collectively wrong, and it is usually reported as a process issue.

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **The mechanism predates AI, and the sector’s own enforcement record proves it.** In August 2012 a deployment at a US market maker left obsolete code active on one of eight servers. Order routing behaved exactly as written and the firm lost roughly 460 million dollars in forty-five minutes. The regulatory proceeding that followed addressed the absence of adequate controls and supervisory procedures, not any analytical defect. In Australia, a software change in a deposit machine channel meant threshold transaction reports were not generated for a large volume of transactions over several years, concluding in Federal Court proceedings and a substantial civil penalty in 2018. In neither case was a model wrong. In both, something crossed a boundary without a property that should have travelled with it. |

## Why agentic AI changes the arithmetic

The instinctive worry about agentic systems is that they are unreliable — that they will hallucinate, misjudge, or act erratically. That worry is legitimate and it is not the argument here. The argument is close to the opposite.

The risk is that agents are fast, tireless, and reliable enough to be trusted with the task, and that automating a task also removes the person who was standing at the boundary. Nobody decides to withdraw the subsidy. It is withdrawn as a by-product of every successful automation, one process at a time, and each individual case looks like a straightforward efficiency.

The sector is not approaching this slowly. In the 2026 global survey of AI in financial services conducted by the Cambridge Centre for Alternative Finance — 628 organisations across 151 jurisdictions, including 149 traditional financial institutions and 130 central banks and regulators — agentic AI was in active adoption among 52% of industry respondents, with 23% already at a scaling or transforming stage. Eighty-one per cent expected it to be meaningfully achieved by 2030.

The same survey suggests the sector already senses the problem, without quite having named its cause. It defines collective forgetting as a systemic risk in which organisations lose the institutional memory and the capability to execute processes manually if required, and ranks loss of human oversight and collective forgetting the third highest AI risk overall: 51% of all respondents, 55% of industry, and 60% of traditional financial institutions. Regulators rated it lowest of the three groups, at 42%.

That distribution is worth pausing on. Incumbent institutions — the ones with the deepest process history and the most accumulated undocumented judgement — are the most worried. Their supervisors are the least. The institutions with the most to lose can feel it, and the people who will examine them have not yet made it a question.

## Six properties, five of which the sector already requires

If the problem is that properties fail to survive boundaries, the useful move is to name the properties. Six of them must survive every boundary a piece of work crosses, and the reason to state them explicitly is that each one is already the subject of an obligation somewhere in a bank’s existing framework.

Context is the condition that makes a value mean what it means — provisional or final, gross or net, a ceiling or a target. Risk data aggregation principles already require accuracy, completeness and lineage, which is context custody in other words. Accountability is attribution generated as a by-product of execution rather than assembled afterwards; audit trail and record-keeping obligations already require it. Coordination is a single statement of an invariant binding every participant, which is what group-wide aggregation and consistent risk appetite were always for. Execution coherence is one enforcement point per rule that admits no exception, with no participant able to bypass it — which is precisely why algorithmic trading rules require pre-trade controls and kill functionality, and why those rules work. Institutional memory is a durable record with provenance, plus the retained ability to run the process without the system; retention rules cover the first half.

Then there is authority: the decision right under which an action is taken, held as data outside the components that exercise it, and consulted at every boundary the work crosses. This is the one property in the set with no existing home.

An institution records mandates, delegated signing authority, limits and four-eyes requirements — for people. It has senior manager regimes and delegation frameworks of real sophistication. None of it covers a decision right that a machine must consult at a boundary, at machine speed, without a human in the transaction. In practice an agent acts under an integration account whose entitlements were configured years ago by someone who has since left, for a purpose unrelated to what the agent now does. Segregation of duties is defeated without any individual breaching anything.

That is the shape of the whole problem. Five obligations the institution already carries have quietly become unowned, and a sixth was never written because until recently it did not need to be.

## The oversight control that cannot function

Two consequences arrive before the others, and the first concerns human oversight, which is where governance functions instinctively place the weight.

The control reads well. Every exception is reviewed by a qualified person before action is taken, and the reviewer may refuse. At low volume it is a real control and it works. At agentic volume it stops working, and the mechanism of its failure has nothing to do with the competence or diligence of the reviewer.

A person facing four thousand items a month cannot evaluate each one. Refusing carries a cost — a conversation, a delay, a colleague’s irritation, possibly a challenge to be defended. Approving carries none. Review becomes approval, approval becomes a pattern, and the pattern becomes a click. Throughout, the audit trail records that human oversight occurred, entirely accurately.

The consequence is not operational but evidential. The institution has represented, in its control library and to its supervisor, that it has a control which cannot function as described. That is a materially different exposure from having no control at all, because it is discoverable, documented, and dated.

There are three honest responses. Reduce the volume so review is genuinely possible, and describe sample-based review as the different control that it is. Or move enforcement into the structure and let the human supervise the structure — reviewing the gate, its rule set and its exception log rather than each transaction, which is the only response that scales. Or accept the residual risk explicitly, with the reasoning recorded, which is the least attractive option and entirely defensible.

The fourth option is to leave the fiction in the control library. It is not a response, and it is the one an examiner or an incident will eventually find.

## The record, and the account of the record

The second consequence concerns evidence, and it turns on a distinction that is easy to state and easy to miss in practice: a record is generated at the moment of action, or it does not exist.

When something goes wrong in a distributed process, what an institution can usually produce is a reconstruction — an explanation assembled after the fact from several systems, by capable people acting in good faith. It looks like evidence. It may even be accurate. But it was authored after the event by parties with an interest in the outcome, and that is a different thing from a record.

Three questions separate them, and they can be asked by anyone. What was captured at execution, and what was derived later — which requires the schema rather than the report. Does the record contain the version of the rule in force at the time, since a record that cannot establish which policy applied cannot establish whether it was followed. And can it be verified by a party who does not operate the system, because if verification requires the keeper of the record, what exists is the keeper’s account.

The most serious documented consequence of not asking those questions is the Post Office Horizon case in the United Kingdom, where accounting system output was treated as independently reliable in disputes with, and prosecutions of, sub-postmasters over two decades. More than nine hundred prosecutions followed and 236 people were imprisoned. Litigation and a statutory inquiry established that the system’s reliability had been asserted rather than demonstrated. The narrow lesson, and the transferable one, is that nobody had asked whether the record could be verified by a party who did not operate the system.

There is a related finding in the Cambridge survey that deserves more attention than it has received. Fifty-five per cent of industry respondents, rising to 76% among large financial institutions, reported difficulty measuring the value of their AI deployment. The survey’s own conclusion is the sentence to take to a risk committee: the measurement deficits that make AI value hard to capture may make AI risk equally hard to observe. An institution that cannot attribute cost per action cannot attribute exposure per action either, because both come from the same absent record.

## What it costs to find out

Almost nothing, which is the most useful feature of this diagnosis. Four things can be done this quarter without a budget, a programme, or anybody’s permission, and none of them requires access to source code, model weights or training data — which also means they work against a vendor-hosted system.

First, take five rules that admit no exception — a jurisdictional transfer prohibition, a sanctions screen, an approval ceiling, a segregation requirement, a prohibited-instrument rule — and ask, for each, where it is physically enforced in any path an agent can reach. The answer must be a single place through which all subject work passes and which no component can bypass. If the answer is that a model has been instructed not to breach the rule, the rule is unenforced, and it should be recorded that way. Modality admits no rate: a model instructed not to do something does it less often, and less often is not never.

Second, select one transaction from at least a month ago in a live deployment and require full attribution by query — acting identity, authority relied upon, and the version of the rule then in force. Not a sample log, not a report: one transaction, chosen by the asker, produced in the room. This single exercise predicts the institution’s position in an examination or an incident better than any control self-assessment.

Third, add six columns to the AI inventory the institution already maintains, one per property. Not a new register — six columns on the existing one, so that gaps become visible across the portfolio rather than case by case.

Fourth, build a dependency census and compare it against the third-party register. The register lists arrangements; the census lists reliance, which is a different question. Its distinctive entries are the orchestration framework with no contractual counterparty, and policy dependency — a provider that can change what the institution is permitted to do with no outage, no price change, and no notice period the institution controls.

## The uncomfortable version

Financial services has been doing boundary control for a century. Segregation of duties, four eyes, three-way match, approval thresholds, maker-checker, reconciliation: every one of these is a rule about what must be true when work passes from one party to another. No sector understands the discipline better, and none has practised it longer.

What the sector never had to do was specify the boundary. A person stood there. She knew which figure was provisional, which limit was a ceiling, which approval had actually been given and by whom, and what to do when the answer was not in the procedure. She was not the fallback for the process. In the parts that mattered most, she was the process.

The institution is now removing her, one automation at a time, from a position it never documented, to close a gap its own supervisors have been recording as open for thirteen years. That is not a reason to stop automating. It is a reason to specify the boundary before she leaves it — and the specification is cheap, while the reconstruction is not.

## Sources and limits

Survey figures are from The 2026 Global AI in Financial Services Report (Cambridge Centre for Alternative Finance, University of Cambridge, April 2026), a self-reported survey of 628 organisations across 151 jurisdictions, dated April 2026 and specific to financial services; respondent groups are stated wherever a figure is given, because the cuts differ materially. The risk data aggregation principles are the Basel Committee’s Principles for effective risk data aggregation and risk reporting (2013), and the adoption position is drawn from subsequent supervisory progress reviews. Case descriptions are drawn from court judgments, regulatory proceedings, and official audits, and are given as records rather than as authority for any proposition of law; figures reported in open or subsequent proceedings may have moved and should be verified against the primary source.

This article addresses what structures carry across boundaries. It says nothing about model accuracy, discriminatory outcomes, capital treatment, or conduct risk in substance, all of which require different methods and different expertise. Custody of the six properties is necessary and not sufficient. Nothing here is legal, regulatory, audit, or accounting advice, and it does not state the law or supervisory expectation of any jurisdiction.

Declaration of interest: the author builds infrastructure of the kind this article argues for, and has a commercial interest in its conclusion. The tests described above are derived from stated requirements rather than calibrated to any product, and should be run hardest against whichever supplier’s vocabulary most closely resembles this article — including the author’s. If they do not bite there, the argument has failed.

**Author’s note**

The content of this document is the author’s. The framework, the six properties, the four axioms, the nine tests and the consequence records are drawn from *What the Structure Does Not Carry* (Georg Zangl, 2026). The document was drafted with the assistance of Claude, an AI assistant made by Anthropic. The author has reviewed it and holds editorial responsibility for it.
