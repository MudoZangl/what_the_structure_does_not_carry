# 11_Financial_Services_Governance — how the book applies in a regulated financial institution

NOT teaching material. Four sector guidance documents (3–4 pp each) for people who already run governance
in a bank, insurer, or asset manager: second-line risk and model risk functions, internal audit, operational
resilience teams, and the finance function itself.

The sector argument in one paragraph: financial services has the most developed governance apparatus of any
commercial sector AND the deepest agentic adoption — 52% of industry respondents in active adoption, 23%
already scaling or transforming. It will therefore find the gap between mature controls and distributed
execution before anyone else does. The apparatus already asks for five of the six properties; it asks for
them of systems with a locus, and agentic deployments have none.

## The four documents

- **MZ-FIN-001 — Why this sector reaches the problem first.** START HERE. Maps each of the six properties to
  the instrument that already requires it (risk data aggregation principles, delegated authority and mandate
  frameworks, audit trail and record-keeping rules, algorithmic trading pre-trade controls and kill
  functionality, retention expectations) and states what agentic deployment breaks in each. Identifies the
  one property with no existing home: authority as machine-consultable data. Includes the three-lines
  mapping and four starting actions.
- **MZ-FIN-002 — When the risk is not in the model.** For model risk management and the second line. Model
  risk management governs components; agentic failures occur at crossings between them, so a fully validated
  model inside an unvalidated crossing is a component certificate for an unassessed system. Extends the
  discipline's own concepts — inventory, tiering, conceptual soundness, validation, effective challenge,
  ongoing monitoring, outcomes analysis, change control — from the component to the crossing. Uses Knight
  Capital and Commonwealth Bank/AUSTRAC rather than any AI incident, because both are court and regulator
  documented and neither involved a model being wrong.
- **MZ-FIN-003 — Dependency, concentration, and the cost of saying no.** The one area where the sector is
  ahead of the book: operational resilience regulation already requires registers, exit strategies, and
  critical-provider identification. So this asks three questions about existing compliance instead — does the
  register reach the model and inference layer, was the exit tested or only written, and who holds the
  transitive list. Six-layer census covering the dependencies a contract-based register misses, including
  orchestration frameworks with no counterparty and policy dependency, where a provider changes what the
  institution may do with no outage at all.
- **MZ-FIN-004 — The close, the controls, and the record.** The finance function as the sharpest case in any
  sector: the output is personally attested, the controls are already boundary controls (segregation of
  duties, four eyes, three-way match, thresholds, reconciliation), and the failure arrives as a number. The
  Canadian federal payroll consolidation is the consequence record. Includes what to tell the external
  auditor and when — a control resting on model instructions is neither automated nor manual in any sense
  the audit framework recognises.

- **MZ-FIN-005 — What Your Analysts Were Carrying** (article, 6 pp / ~3,300 words). NOT guidance and NOT
  structured like the four above: continuous prose, one argument, readable start to finish, no tables or
  rubrics. For circulating to a governance group, a risk committee, or a publication. Opens on the risk data
  aggregation failure the sector lived through — thirteen years, real budgets, gap still open — and supplies
  the explanation: the principles were already being satisfied, by people standing at boundaries, and the
  effort was invisible because it was salaried. Then Phoenix as the documented case of that layer being
  removed on purpose, the four-hundred-as-ceiling mechanism, the six properties with authority as the one
  with no home, oversight at volume, record versus reconstruction, and four things doable this quarter with
  no budget. Supplied as .docx (house style) and .md (for pasting into a publishing platform).

## Discipline for this folder

- The argument is that the obligations already exist. Nothing here proposes a new framework, and framing it
  as one will lose the room — particularly with model risk functions, who are right to defend a discipline
  that predates this wave by fifteen years.
- Risk data aggregation is the honest precedent, not a rhetorical one: principles issued in 2013 requiring
  accuracy, completeness, timeliness and lineage, still incompletely adopted after more than a decade at
  institutions with real budgets and real intent — because people carried those properties at every boundary
  and the effort was invisible because it was salaried. Agentic deployment removes them.
- Regulatory instruments are described in general terms only and always flagged for verification. Supervisory
  guidance on model risk and operational resilience differs materially by jurisdiction, and several
  instruments are moving during 2026.
- Survey figures come from folder 8 and must be cited with the respondent group. Never cite the largest cut
  as though it were industry-wide.
- Consequence records trace to courts, regulators, official audits, or company admission. Knight Capital
  (SEC proceeding), Commonwealth Bank (Federal Court of Australia, 2018), and the Canadian payroll programme
  (official audits and parliamentary reporting) all qualify. No AI-incident anecdotes.
- Style matches the bundle: Stone palette, Georgia, no colour.

## Scope note

"Finance governance" was read as AI governance in financial services. MZ-FIN-004 covers the narrower
finance-function reading (financial reporting, close, controls, payments), so both senses are served. If the
finance function alone is the intended audience, MZ-FIN-004 is the document and the other three are context.
