# INTEGRATION DRIFT: INSTITUTIONAL CONSTRAINTS AND HR TECHNOLOGY SYSTEM INTEGRATION IN THE PUBLIC SECTOR

**Peter Demerjian, Bryan Gibson, Brandon Hall**
Working Paper - December 2025

---

## ABSTRACT

This study examines why public sector organizations systematically fail to achieve planned legacy system retirement following HR technology acquisitions. We introduce Integration Drift—the divergence between planned and actual system integration outcomes caused by institutional constraints—and develop the Institutional-Technical-Organizational (ITO) Attribution Framework to decompose delay into addressable components. Using comparative case analysis of the U.S. Army's Integrated Personnel and Pay System-Army (IPPS-A), OPM's forthcoming government-wide HCM initiative, and Walmart's Workday implementation, we examine institutional amplification: whether and how constraints function not merely as additive delays but as multipliers on technical and organizational challenges.

IPPS-A demonstrates measurable Integration Drift: the project planned Release 3 deployment by December 2021 but achieved it in January 2023 (13-month delay), with payroll integration deferred from 2023 to calendar year 2026 (36-month deferral). These documented delays correlate temporally with institutional milestones: Federal Acquisition Regulation (FAR) testing requirements (announced October 2021), appropriations constraints, and civil service change management. In contrast, Walmart's Workday implementation across 2.1 million employees achieved full legacy system retirement within planned timelines, despite comparable technical and operational complexity.

Using comparative case analysis with ITO attribution coding, we find evidence that institutional constraints do not merely add to project timelines but amplify technical and organizational delays through sequential requirements, constraint cascades, and risk-averse responses. We ground this amplification mechanism in a unified framework (Quigley, Tsebelis, Fukuyama, Kornai) explaining why constraints persist and why public organizations lack survival pressure to overcome them. The paper offers testable predictions for OPM's forthcoming implementation.

**Keywords:** Integration drift, institutional theory, veto players, vetocracy, soft budget constraints, HRIS, public sector IT, M&A integration

---

## 1. INTRODUCTION

### 1.1 The Empirical Puzzle

In fiscal year 2024, the U.S. federal government requested approximately $74 billion for civilian agency information technology, with additional billions allocated to defense IT systems (OMB, 2024). HR and personnel systems modernization represents a substantial portion of this investment. Despite this investment, federal IT projects consistently exceed planned timelines and fail to achieve targeted legacy system retirement rates. The Government Accountability Office has designated federal IT acquisition and management as "high risk" since 2015, documenting persistent patterns of schedule slippage, cost overruns, and incomplete system consolidation (GAO, 2024).

**The financial stakes are substantial.** Federal agencies spend more than $100 billion annually on IT investments, with approximately 80 percent—roughly $80 billion—allocated to operations and maintenance of existing systems, including legacy infrastructure (GAO, 2023). GAO analysis of just ten critical federal legacy systems found annual maintenance costs of $337 million (GAO, 2019). From fiscal years 2010 to 2017, operations and maintenance spending increases produced a $7.3 billion decline in funds available for development, modernization, and enhancement activities (GAO, 2016). Each month of Integration Drift extends legacy maintenance burdens while deferring modernization benefits—a compounding cost that accounting analysis could quantify as net present value of deferred integration.

The standard explanation attributes these outcomes to poor management, inadequate planning, or insufficient technical expertise. This explanation is unsatisfying for three reasons. First, it fails to explain why the pattern persists across agencies with different leadership, different contractors, and different technical requirements. If poor management were the cause, variation would be the expectation. Instead, we observe convergence toward similar (unfavorable) outcomes. Second, it implies that private sector organizations implementing equivalent systems are simply better managed—an assumption that ignores the fundamentally different institutional environments in which public and private organizations operate. Third, it suggests no actionable remedy beyond exhortation to "do better."

This paper examines post-acquisition integration of large-scale HR technology platforms in public versus private settings, advancing an alternative explanation grounded in institutional theory. We argue that public sector IT projects are not poorly managed but differently constrained. The rules governing federal acquisitions—Federal Acquisition Regulation (FAR) protest periods, congressional appropriations cycles, civil service protections, collective bargaining agreements—exist to ensure democratic accountability, fair competition, and worker protection. These are better understood as intentional features of public governance rather than as bureaucratic pathologies. However, these features impose costs that compound in ways existing literature has not adequately theorized.

### 1.2 Integration Drift: Concept and Definition

We introduce Integration Drift as a theoretical construct capturing involuntary divergence between planned and actual system integration outcomes:

> **DEFINITION:** Integration Drift is the gap between an organization's stated integration intent at acquisition announcement (T₀) and actual system preservation at post-implementation assessment (T₀ + 24 months), where the gap emerges from institutional constraints the organization cannot unilaterally change.

Three elements distinguish Integration Drift from general project delay. First, it is measured as outcome divergence (system preservation rate) rather than timeline extension. Second, it is involuntary—organizations experiencing drift intended full integration but were prevented from achieving it. Third, it is institutional—the constraints causing drift are embedded in law, regulation, or collective agreement, not organizational choice or technical limitation alone.

The term "drift" is used to emphasize continuous, cumulative divergence from intended trajectory—unlike "failure" (which implies culpable inadequacy) or "delay" (which implies eventual achievement).

### 1.3 Research Questions

This study addresses three interrelated questions:

**RQ1:** Do public sector organizations exhibit systematically higher Integration Drift than private sector organizations implementing equivalent HR technology?

**RQ2:** What is the relative contribution of institutional, technical, and organizational factors to observed Integration Drift?

**RQ3:** Do institutional constraints operate as additive delays or as amplifiers of technical and organizational challenges?

### 1.4 Preview of Findings

Comparative analysis of Army IPPS-A and Walmart Workday implementations reveals substantial sector differences. IPPS-A, targeting consolidation of approximately 50 legacy systems serving 1.1 million soldiers, has demonstrated Integration Drift: the project planned Release 3 deployment by December 2021 but achieved it in January 2023 (13-month delay), with payroll integration deferred from 2023 to calendar year 2026 (36-month deferral).

In contrast, Walmart implemented Workday across 2.1 million employees globally, achieving complete legacy system retirement within planned timelines. As we establish in Section 5, technical and operational complexity in both migrations is comparable when systematically assessed; the divergence in outcomes is most consistent with differences in institutional context rather than technical factors alone.

### 1.5 Contributions

This study makes three contributions. Theoretically, we extend M&A integration research by grounding Integration Drift in a unified framework spanning Quigley, Tsebelis, Fukuyama, and Kornai—explaining how institutional constraints accumulate, resist reform, and why organizations lack pressure to overcome them. Methodologically, we develop the ITO Attribution Framework, a replicable approach for decomposing project delay into addressable components. Practically, we distinguish delays amenable to management improvement from those requiring institutional reform.

---

## 2. THEORETICAL FRAMEWORK

### 2.1 M&A Integration Theory and Its Limits

The M&A literature conceptualizes post-acquisition integration as strategic choice. Haspeslagh and Jemison (1991) identify four integration approaches—absorption, preservation, symbiosis, and holding—distinguished by strategic interdependence needs and organizational autonomy requirements. The implicit assumption: integration mode is chosen through deliberate decision-making.

We challenge this assumption in institutionally constrained environments. Organizations may intend absorption but achieve preservation—not through choice but through institutional prevention. Integration Drift captures this involuntary divergence between strategy and outcome.

This matters because incomplete integration is a primary driver of M&A value destruction. King et al. (2004) find in their meta-analysis that post-acquisition performance depends significantly on integration effectiveness. When HRIS integration stalls, organizations bear perpetual dual-system maintenance costs and fail to realize anticipated synergies. Integration Drift thus represents a specific channel through which institutional constraints translate into unrealized value—not merely delay, but ongoing value leakage for as long as legacy systems persist.

### 2.2 Public Sector IT: Institutional Differences

Research documents systematic differences between public and private sector IT implementation. Moon and Bretschneider (2002) find that perceived red tape significantly constrains IT innovativeness in public organizations. Fountain (2001) argues that identical technologies produce different outcomes when enacted through different institutional arrangements. Troshani, Jerram, and Hill (2011) find that public sector HRIS adoption follows different patterns than private sector adoption, with longer timelines and more stakeholder involvement.

What this literature does not fully theorize is the mechanism by which institutional constraints produce specific outcomes. We turn to a novel theoretical synthesis.

### 2.3 From Quigley to Kornai: A Unified Framework

We propose a unified framework explaining why institutional constraints persist, accumulate, amplify project timelines—and why organizations lack survival pressure to overcome them. This framework spans four theoretical contributions: Quigley's instrument/institution distinction, Tsebelis's veto player theory, Fukuyama's concept of vetocracy, and Kornai's soft budget constraint theory.

#### 2.3.1 Instruments and Institutions (Quigley, 1961)

Carroll Quigley's foundational insight distinguishes between instruments and institutions. An instrument is an organization that does what it was designed to do—it serves a genuine social need and little else. Over time, however, instruments transform into institutions: they "take on a life of their own, protect themselves and serve their own interests more than they advance the cultural need they were designed to solve" (Quigley, 1961: 101).

This transformation is not conspiracy or corruption. The procurement officer who masters FAR complexity has invested years in that expertise; simplifying FAR threatens that investment. The contractor who has learned to navigate federal acquisition has built competitive advantage on that knowledge. None of these actors are villains; each can be viewed as rationally protecting accumulated expertise and interests. Arthur (1994) and Pierson (2000) formalize this mechanism as increasing returns: once actors invest in mastering a complex system, switching costs rise over time, creating path dependence that makes reform progressively more difficult. For M&A integration, this implies that acquirers inherit not just legacy systems but the accumulated institutional investments protecting those systems—a burden private acquirers can override but public sector organizations often cannot.

Applied to federal IT acquisition: FAR began as an instrument to prevent procurement corruption. It worked. But FAR has become an institution—over 2,000 pages of accumulated complexity serving an ecosystem of lawyers, consultants, and procurement officials whose livelihoods depend on that complexity. Therefore we expect many institutional constraints to persist even when they are widely recognized as imposing costs.

#### 2.3.2 Veto Players and Institutional Gridlock (Tsebelis, 2002)

George Tsebelis's veto players theory explains why institutions resist reform. A veto player is any actor whose agreement is required for policy change. Tsebelis demonstrates formally that "having more veto players necessarily makes a polity less able to change its policies" (Tsebelis, 2002: 2).

The American constitutional system was deliberately designed with multiple veto players to prevent tyranny. But veto players have proliferated far beyond the constitutional structure:

**Veto Players in Federal IT Acquisition:**

| Category | Players |
|----------|---------|
| Constitutional | President, House, Senate |
| Statutory | GAO, Inspectors General, Courts, Agency CIO |
| Regulatory | OMB, OPM, GSA |
| Contractual | Unions (AFGE, NTEU), incumbent contractors |
| Informal | Congressional committees, media, interest groups |

**Result:** Numerous actors with effective veto power over change, and no single actor with authority to compel completion.

Tsebelis's theory predicts the consequence: with this many veto players, "significant departures from the status quo are impossible" (Tsebelis, 2002: 19). Any major IT initiative must either satisfy all veto players (which takes years) or circumvent them (which creates legal and political risk). Therefore we expect project delay to correlate positively with the number of veto players whose approval is required.

#### 2.3.3 Vetocracy and Its Costs (Fukuyama, 2014)

Francis Fukuyama synthesizes these dynamics in his concept of vetocracy—"a system of governance whereby no single entity can acquire enough power to make decisions and take effective charge." The American system, Fukuyama argues, has evolved from healthy checks and balances into pathological vetocracy:

> "The American system was designed to prevent tyranny by making action difficult. It succeeded. But it provided no corresponding mechanism to force action when action is needed. The result: everyone can say no, and nobody can say yes."

Applied to federal IT acquisition: Federal agencies do not choose preservation over absorption; they are pushed toward preservation by a system in which numerous actors can block integration and no single actor can compel it. Therefore we expect federal IT projects to converge toward similar outcomes across a range of management quality and stated intent.

#### 2.3.4 Absence of Competitive Pressure and Asymmetric Risk (Building on Kornai, 1986)

The preceding analysis explains how institutional constraints accumulate and resist reform. A complementary question remains: why don't organizations simply push harder to overcome these constraints? We extend Janos Kornai's theory of soft budget constraints to address this question.

Kornai, analyzing socialist economies, observed that state enterprises behaved differently than market firms because they faced fundamentally different survival conditions. Market firms operate under hard budget constraints: if revenues persistently fall short of costs, the firm fails. This creates intense pressure to eliminate inefficiencies—including the costly maintenance of redundant systems. State enterprises, by contrast, operate under soft budget constraints: if revenues fall short, the state provides subsidies. The enterprise survives regardless of efficiency.

We adapt this framework to federal agencies, recognizing that the mechanism differs from Kornai's original formulation. Federal agencies do not receive explicit subsidies when projects fail; they operate within fixed appropriations. However, two features produce analogous behavioral effects:

**Absence of competitive pressure:** Unlike private firms, federal agencies face no competitors who might capture market share by integrating faster. Walmart's delayed integration would create competitive disadvantage; the Army's delayed integration creates no equivalent organizational threat.

**Asymmetric risk structure:** Legacy maintenance costs are diffuse, distributed across appropriations, and invisible to political principals. Transition failures—a soldier not paid, a benefit miscalculated, a congressional hearing convened—are concentrated, attributable, and career-ending. Rational managers therefore preserve legacy systems indefinitely: the financial cost of redundancy threatens no one's career, while the political cost of transition failure is immediate and personal.

This framework completes the theoretical synthesis. Quigley explains how instruments transform into self-perpetuating institutions. Tsebelis demonstrates how veto player accumulation produces gridlock. Fukuyama shows how this gridlock becomes vetocracy. The Kornai-derived framework addresses the prior question: why don't organizations simply push through these barriers? The answer is that public organizations face no survival pressure to do so—and face asymmetric career risk if they try. Therefore we expect public organizations to exhibit greater tolerance for persistent inefficiencies than private organizations facing hard budget constraints and competitive pressure.

### 2.4 Institutional Amplification: How Constraints Multiply

Quigley's (1961) distinction between instruments and institutions finds a modern, rigorous parallel in Lo's (2017; Levin & Lo, 2015) analysis of regulatory evolution. Lo documents how financial regulation, initially adaptive responses to crises, accretes into increasingly complex systems whose compliance costs grow more than proportionally with the number of rules. Applied here, each new procurement statute or FAR subpart began as a targeted solution (prevent fraud, ensure competition, protect workers) but cumulatively produces compliance burdens that amplify technical and organizational delays far beyond additive expectation—precisely the mechanism we term institutional amplification.

Three specific mechanisms operate through the unified framework:

**1. Sequential Requirements (Veto-Driven Serialization)**
FAR often requires sequential rather than parallel processes. Veto players at each stage can halt progress, forcing sequential approval. A private organization can conduct system testing while finalizing contracts; a public organization typically cannot.

**2. Constraint Cascades (Institutional Density)**
Institutional constraints interact. Union agreements negotiated for one change apply to subsequent changes. Appropriations secured for one fiscal year constrain spending patterns in subsequent years. Each constraint creates additional constraints—path dependence at the institutional level.

**3. Risk-Averse Responses (Kelman's Fear of Discretion)**
Kelman (1990) identifies "fear of discretion" as pervasive in federal procurement: officials avoid exercising judgment even when regulations permit flexibility, because discretion creates audit risk while conformity provides protection. This amplifies technical challenges into extended timelines.

### 2.5 Alternative Explanations

A complete account must address competing explanations for observed delays:

**Contractor Incentives:** Cost-plus contracts may incentivize contractors to extend rather than accelerate timelines. CACI International, IPPS-A's prime contractor, benefits financially from extended development. We acknowledge this principal-agent dynamic as a contributing factor, though we note it operates within the institutional framework: cost-plus contracting is itself an institutional choice driven by the difficulty of specifying complete contracts under uncertainty—a challenge amplified by institutional constraints.

**Technical Complexity Differences:** Section 5 addresses this directly. We establish that Walmart and Army implementations involve comparable technical complexity along measurable dimensions, though complexity manifests differently across domains.

**COVID-19 Disruption:** IPPS-A's Release 3 delay (December 2021 to January 2023) coincided with the COVID-19 pandemic. We address this confound in Section 4.4, noting that (a) institutional delays preceded COVID-19, (b) the pandemic affected all large IT implementations yet private sector outcomes diverged from public sector outcomes, and (c) the 36-month payroll deferral extends well beyond pandemic disruption timelines.

**Management Quality:** We cannot rule out that Army project management was inferior to Walmart's. However, the persistence of similar outcomes across agencies with different management suggests institutional rather than managerial causation. Poor management would predict variance; institutional constraints predict convergence.

### 2.6 Why Reform Fails

Understanding this framework explains why decades of federal IT reform have produced limited results:

**Pressure fails** because it treats symptoms (slow projects) rather than causes (veto player accumulation). Pressure cannot overcome structural gridlock.

**Simplification fails** because institutions resist it. Every rule exists because someone wanted it; removing rules mobilizes constituencies. FAR "simplification" efforts have consistently added pages, not removed them.

**Bypass fails systemically** because circumventing constraints creates precedents that erode legitimate purposes constraints originally served.

These constraints were not mistakes. They were solutions to real problems: the spoils system really did produce incompetent government; corrupt procurement really did waste public funds. The instruments created to solve these problems worked. The problem is their transformation into institutions that resist reform—compounded by the absence of survival pressure that might otherwise force organizations through the barriers.

---

## 3. INSTITUTIONAL CONTEXT OF FEDERAL HR ACQUISITION

### 3.1 Federal Acquisition Regulation

The Federal Acquisition Regulation (FAR) governs procurement for all executive branch agencies. Over 2,000 pages of accumulated regulations implement approximately 40 public laws related to government procurement.

For IT acquisition specifically, FAR imposes procedural requirements that extend timelines relative to private procurement:

**Competition Requirements (FAR Part 6):** Public solicitation, adequate response time, objective evaluation criteria—extending procurement timelines by several months relative to direct negotiation.

**Protest Procedures (FAR Part 33):** GAO protest resolution requires 100 days; agencies typically suspend performance during this period. In FY2023, GAO received 2,025 protest filings (GAO, 2024).

**Sequential Testing:** FAR requires completion of System Acceptance Testing (SAT), System Integration Testing (SIT), and Limited User Testing (LUT) phases—each a gatekeeping veto point.

### 3.2 Appropriations Constraints

Congressional appropriations occur annually, misaligned with IT project cycles. Agencies cannot commit to multi-year funding without specific authority. Budget constraints emerge unpredictably when Congress revises appropriations or reallocates funds. The Anti-Deficiency Act (31 U.S.C. Section 1341) prohibits obligating funds in excess of appropriations, creating extreme risk aversion around spending acceleration.

### 3.3 Civil Service and Union Constraints

Federal employees are protected through civil service rules and collective bargaining agreements. Technology changes affecting compensation, work location, or job classification require notification periods, union consultation, grievance procedures, and potentially binding arbitration. Each adds time—protecting workers while extending implementation timelines.

---

## 4. RESEARCH DESIGN

### 4.1 Comparative Case Study Approach

We employ comparative case study methodology to examine the Institutional Amplification Hypothesis:

| Case | Institutional Intensity | Predicted Drift |
|------|------------------------|-----------------|
| Army IPPS-A | High | High |
| Walmart Workday | Low | Minimal |
| OPM HCM | Moderate | Moderate |

The empirical logic is straightforward: if institutional constraints drive Integration Drift, organizations with similar technical complexity but different institutional contexts should exhibit different outcomes.

### 4.2 Case Selection Rationale

**IPPS-A:** Largest federal HR system consolidation, well-documented public delays, known institutional constraints, comparable technical scope to Walmart.

**Walmart:** Comparable employee population (2.1M vs. 1.1M), comparable legacy system complexity, achieved full retirement within planned timelines, operates under minimal institutional constraints.

**OPM:** Forthcoming implementation provides prospective test of predictions.

### 4.3 ITO Decomposition Framework

We analyze delays using the ITO Attribution Framework:

```
D_total = D_I + D_T + D_O + (D_I × D_T) + (D_I × D_O)
```

Where:
- D_I = Institutional delay (constraints documented in statute, regulation, or contract)
- D_T = Technical delay (complexity-driven, observable in comparable private implementations)
- D_O = Organizational delay (execution-driven, within management control)
- Interaction terms capture amplification effects

We treat these components as analytically separable while explicitly modeling interaction effects. The key test: if institutional constraints merely add to delay, interaction terms should be negligible. If they amplify other delays, interaction terms should be substantial.

**Attribution Protocol:**
1. Identify delay episode from documentary source (GAO reports, program announcements, budget documents)
2. Determine primary cause category using decision tree (Appendix A)
3. Validate classification using secondary evidence
4. Estimate amplification by comparing duration to private-sector baseline for equivalent technical challenge
5. Code interaction effects where institutional constraints extended technically-driven delays

### 4.4 Addressing Confounds

**COVID-19:** IPPS-A's Release 3 delay (December 2021 → January 2023) overlapped with pandemic disruption. Three observations mitigate this confound:

1. **Pre-pandemic delays:** IPPS-A experienced schedule slippage before March 2020, establishing a pattern preceding COVID-19
2. **Differential outcomes:** If COVID-19 were the primary cause, we would expect comparable delays across public and private implementations; instead, outcomes diverge by sector
3. **Extended deferrals:** The 36-month payroll integration deferral extends to 2026, well beyond reasonable pandemic attribution

**Selection bias:** Cases were selected because outcomes were known. We acknowledge this limitation and note that within-sector variance exists—some federal IT projects succeed more quickly, some private implementations encounter significant delays. Our claim is not that all federal projects drift and all private projects succeed, but that institutional constraints systematically shift the distribution of outcomes.

---

## 5. CASE ANALYSIS

### 5.1 Case 1: Army IPPS-A

#### 5.1.1 Project Overview

IPPS-A is the Army's effort to consolidate more than 50 legacy HR systems into a single integrated platform serving 1.1 million personnel across Active, Guard, and Reserve components. CACI International was awarded the contract in 2015. Full deployment to all Army components was reported in January 2023, following more than $1 billion in investment over approximately eight years (Federal News Network, 2023).

#### 5.1.2 Documented Timeline and Delays

| Milestone | Planned | Actual | Delay |
|-----------|---------|--------|-------|
| Release 3 deployment | December 2021 | January 2023 | 13 months |
| Payroll integration | 2023 | 2026 | 36 months |
| Full legacy retirement | TBD | Ongoing | TBD |

The October 2021 announcement specifically cited System Acceptance Testing (SAT) issues. Federal acquisition regulations require sequential completion of SAT, SIT, and LUT phases—each a gatekeeping veto point.

#### 5.1.3 ITO Attribution

**INSTITUTIONAL FACTORS (documented):**
- FAR sequential testing: 9-month delay attributed to testing requirements following October 2021 announcement
- Appropriations constraints: Payroll integration deferred 36 months pending funding alignment
- Civil service change management: October 2022 pay standardization added notification and consultation periods

**TECHNICAL FACTORS (documented):**
- Legacy data quality: 95.2% of test participants found data errors (DOT&E testing documentation)
- Interface complexity: 15+ Army/DOD systems feeding IPPS-A

**ATTRIBUTION ESTIMATE:** Based on documentary evidence, we estimate institutional factors account for 50-60% of observed delay, technical factors 25-30%, and organizational factors 10-20%. The interaction between institutional and technical factors—where FAR testing requirements extended technical remediation timelines—accounts for substantial additional delay beyond additive expectation.

#### 5.1.4 Amplification Evidence

What is typically a months-long data cleanup effort in private implementations became multi-year remediation in this institutional context. The ~8-year timeline (2015 contract to 2023 deployment) substantially exceeds private sector implementations of similar scale. We estimate that institutional amplification—not merely institutional addition—accounts for this divergence.

### 5.2 Case 2: Walmart Workday

Walmart selected Workday as its global HR platform, replacing legacy PeopleSoft systems. Implementation scope: 2.1 million employees globally. Outcome: full legacy system retirement achieved within planned timelines.

#### 5.2.1 Establishing Complexity Equivalence

A rigorous comparison requires establishing that Walmart's implementation involved comparable complexity to IPPS-A. We assess complexity across multiple dimensions:

| Dimension | Army IPPS-A | Walmart Workday | Assessment |
|-----------|-------------|-----------------|------------|
| **Scale** | 1.1M personnel | 2.1M employees | Walmart larger |
| **Geographic scope** | Primarily domestic + deployed | 28 countries, multiple currencies | Walmart more complex |
| **Workforce diversity** | Active, Reserve, Guard, civilian | Hourly, salaried, distribution, corporate, international | Comparable |
| **Pay structures** | Base pay, combat pay, BAH, BAS, hazard duty, special duty | Hourly rates, salaries, bonuses, international variations, multiple currencies | Different but comparable complexity |
| **Regulatory compliance** | Military regulations, federal personnel rules | 50 state labor laws, 28 national labor regimes, varying tax codes | Walmart arguably more complex |
| **Turnover/transaction volume** | Lower turnover, complex status changes | High turnover (100%+ annually in some roles), massive hire/term volume | Walmart higher volume |
| **Operational stakes** | Mission-critical; errors affect readiness | Business-critical; errors affect 2.1M livelihoods; trucking fleet has fatality exposure | Both high-stakes |
| **Legacy system age** | Some systems decades old | PeopleSoft implementation mature | Comparable |
| **Data sensitivity** | Some classified personnel data | PII for 2.1M employees and dependents | Both sensitive |

**Assessment:** Complexity is comparable but differently distributed. Military HR involves distinctive pay structures (combat pay, housing allowances, deployment adjustments); retail HR involves higher transaction volumes, global regulatory fragmentation, and currency complexity. Neither domain is clearly "more complex"—they are differently complex.

This equivalence is important: it establishes that divergent outcomes cannot be attributed to Walmart facing an "easier" technical challenge. Both implementations involved substantial, enterprise-scale complexity.

#### 5.2.2 Institutional Context Comparison

| Constraint Type | Walmart | Federal Agency |
|-----------------|---------|----------------|
| Procurement | Corporate policy | FAR (2,000+ pages) |
| Competition req. | None (negotiated) | Full & open |
| Protest mechanism | None | GAO/COFC (100 days) |
| Budget cycle | Continuous | Annual appropriations |
| Union constraints | Limited | AFGE/NTEU |
| Competitive pressure | Intense (rivals) | None |
| Budget constraint | Hard (margin pressure) | Soft (appropriations) |

#### 5.2.3 Why the Divergence?

Walmart faces hard budget constraints and competitive pressure. Every dollar maintaining legacy systems reduces margin. Every month of delayed integration creates competitive disadvantage relative to rivals who modernize faster. This creates sustained pressure to retire legacy systems even when doing so entails transition risk.

The Army faces soft budget constraints and no competitive pressure. Legacy costs are absorbed by appropriations; they do not threaten organizational survival. No competitor can capture "market share" by integrating faster. But a failed cutover—a soldier not paid, a benefit miscalculated, a congressional hearing convened—represents immediate, attributable political cost.

Both organizations respond rationally to their incentive structures. The primary difference is structural rather than managerial.

### 5.3 Case 3: OPM Government-Wide HCM

OPM is launching a government-wide HR system consolidation initiative targeting October 2025. This case provides prospective test of predictions.

#### 5.3.1 Predictions

We register the following predictions as of December 2025, prior to OPM HCM contract award. Predictions are designed with explicit falsification criteria:

| Prediction | Expected Outcome | Falsification Criterion | Confidence |
|------------|------------------|------------------------|------------|
| **P1: Award delay** | 6-12 months beyond RFP schedule | Award within 3 months of RFP schedule | High |
| **P2: Adoption rate** | <60% agency participation at T+24 months | >75% participation at T+24 months | Moderate |
| **P3: Union impact** | 4-8 months delay attributable to union consultation | <2 months union-attributable delay | High |
| **P4: Legacy retirement** | <50% legacy retirement at T+48 months despite plan | >70% retirement at T+48 months | Moderate |

**Interpretation guidance:** Outcomes within predicted ranges support the Institutional Amplification Hypothesis. Outcomes meeting falsification criteria would require theoretical revision. Outcomes between predicted ranges and falsification criteria would be inconclusive.

---

## 6. DISCUSSION

### 6.1 Theoretical Implications

We extend M&A integration research by identifying Integration Drift as an institutional contingency on classic M&A integration theory—conditions under which integration strategy diverges from integration outcome:

```
Realized Integration Mode = f(Intended Mode, Institutional Constraints, Competitive Pressure)
```

Federal agencies do not choose preservation; they are pushed toward it by veto player gridlock and face no survival pressure (under soft budget constraints and absent competition) to push back.

### 6.2 The Counterfactual

Would the Army achieve Walmart-like outcomes with Walmart-like institutional freedom? We must be careful here: the Army cannot and should not operate without democratic oversight. The question is not whether to remove constraints, but whether the current constraint configuration produces unnecessary amplification beyond what democratic accountability requires.

Available evidence is consistent with the view that equivalent technical capability exists (federal contractors succeed in private implementations), adequate resources were allocated ($1B+ investment), and technical complexity was comparable. The documented institutional constraints—FAR testing serialization, appropriations cycles, union consultation—are features that distinguish public from private implementation contexts.

### 6.3 Policy Implications

The unified framework enables diagnostic clarity. We emphasize: this analysis does not argue for eliminating democratic safeguards; it argues for distinguishing necessary constraints from unnecessary amplification.

**CONSTRAINTS SERVING DEMOCRATIC VALUES (Retain):**
- Transparency in procurement: Prevents corruption
- Union consultation: Protects workers
- Appropriations oversight: Ensures accountability
- Protest mechanisms: Ensures fair competition

**CONSTRAINTS THAT MAY BE ARTIFACTS (Examine):**
- Sequential testing requirements: Mandated by statute or agency habit?
- Fiscal year boundary effects: Can multi-year IT appropriations reduce friction?

**CONSTRAINTS ASSOCIATED WITH UNNECESSARY AMPLIFICATION (Reform Candidates):**
- Procurement culture risk-aversion: Kelman's "fear of discretion"
- Cascading approval gates: Consolidated procedures could preserve legitimacy while reducing serial delay

### 6.4 Implications for OPM Implementation

If our framework is correct, OPM's forthcoming implementation will encounter predictable challenges regardless of management quality. Policy-makers might consider:

1. Securing multi-year appropriations authority to reduce fiscal year boundary effects
2. Consolidating testing gates where sequential requirements are customary rather than statutory
3. Front-loading union consultation to parallelize rather than serialize constraints
4. Establishing clear authority for someone to say "yes" rather than only mechanisms for saying "no"

### 6.5 Limitations

**Case count:** Three cases cannot support population-level claims. We offer existence proof, not prevalence estimates.

**Data access:** Precise ITO quantification requires internal program documentation not publicly available. Our attribution estimates should be treated as indicative rather than definitive.

**Selection:** Cases were selected on known outcomes. Within-sector variance exists.

**Falsifiability:** OPM predictions are prospective but may be affected by factors we cannot anticipate. Prediction failure would require theoretical revision.

---

## 7. CONCLUSION

Public sector IT projects take longer than private sector equivalents. This is an empirical regularity. The question is why—and what follows from the answer.

The unified framework provides a structured explanation: institutional constraints that were once instruments solving real problems have become institutions serving their own perpetuation. These constraints accumulate, resist reform, and amplify project timelines. And because public organizations operate under soft budget constraints and face no competitive pressure, they face no survival pressure to overcome these barriers.

This does not excuse outcomes. It enables intelligent response. Understanding that Integration Drift is a predictable institutional outcome—not management failure—enables policymakers to distinguish which delays are necessary costs of democratic governance and which represent unnecessary amplification.

IPPS-A is better understood as the outcome of an organization navigating institutional constraints it cannot unilaterally change—and lacking the survival pressure to force its way through. OPM is about to attempt the same thing. Making predictions public creates accountability: if OPM follows IPPS-A patterns, policymakers should ask not "why did this project fail?" but "what institutional reforms would enable different outcomes?"

---

## REFERENCES

Arthur, W. B. (1994). *Increasing returns and path dependence in the economy.* University of Michigan Press.

Fountain, J. E. (2001). *Building the virtual state: Information technology and institutional change.* Brookings Institution Press.

Fukuyama, F. (2014). *Political order and political decay: From the industrial revolution to the globalization of democracy.* Farrar, Straus and Giroux.

Government Accountability Office. (2016). *Information Technology: Federal agencies need to address aging legacy systems* (GAO-16-468).

Government Accountability Office. (2019). *Information Technology: Agencies need to develop and implement modernization plans for critical legacy systems* (GAO-19-471).

Government Accountability Office. (2023). *Information Technology: Agencies need to continue addressing critical legacy systems* (GAO-23-106821).

Government Accountability Office. (2024). *High-risk series: Efforts made to achieve progress need to be maintained and expanded to fully address all areas* (GAO-24-106203).

Government Accountability Office. (2024). *Bid protest annual report to Congress for fiscal year 2023* (GAO-24-900538).

Haspeslagh, P. C., & Jemison, D. B. (1991). *Managing acquisitions: Creating value through corporate renewal.* Free Press.

Kelman, S. (1990). *Procurement and public management: The fear of discretion and the quality of government performance.* AEI Press.

King, D. R., Dalton, D. R., Daily, C. M., & Covin, J. G. (2004). Meta-analyses of post-acquisition performance: Indications of unidentified moderators. *Strategic Management Journal, 25*(2), 187-200.

Kornai, J. (1986). The soft budget constraint. *Kyklos, 39*(1), 3-30.

Levin, S., & Lo, A. W. (2015). Opinion: A new approach to financial regulation. *Proceedings of the National Academy of Sciences, 112*(41), 12543-12544.

Lo, A. W. (2017). *Adaptive markets: Financial evolution at the speed of thought.* Princeton University Press.

Moon, M. J., & Bretschneider, S. (2002). Does the perception of red tape constrain IT innovativeness in organizations? *Journal of Public Administration Research and Theory, 12*(2), 273-291.

Office of Management and Budget. (2024). Federal information technology spending FY 2024. IT Dashboard, itdashboard.gov.

Pierson, P. (2000). Increasing returns, path dependence, and the study of politics. *American Political Science Review, 94*(2), 251-267.

Quigley, C. (1961). *The evolution of civilizations: An introduction to historical analysis.* Macmillan.

Tsebelis, G. (2002). *Veto players: How political institutions work.* Princeton University Press.

Troshani, I., Jerram, C., & Hill, S. R. (2011). Exploring the public sector adoption of HRIS. *Industrial Management & Data Systems, 111*(3), 470-488.

---

## APPENDIX A: ITO ATTRIBUTION CODING PROTOCOL

**STEP 1:** Identify delay episode from documentary source

**STEP 2:** Determine primary cause category using decision tree

**STEP 3:** Validate classification using secondary evidence

**STEP 4:** Estimate baseline duration from comparable private implementation

**STEP 5:** Code interaction effects where applicable

### Decision Tree:

```
Is delay caused by statute, regulation, contract, or constitutional
requirement that organization cannot change?
    → YES: Code as INSTITUTIONAL (I)
    → NO: Continue

Is delay caused by system characteristics (legacy architecture, data
quality, interface complexity) independent of institutional context?
    → YES: Code as TECHNICAL (T)
    → NO: Continue

Is delay caused by planning decisions, resource allocation, or execution
choices within organizational control?
    → YES: Code as ORGANIZATIONAL (O)
    → NO: Review and reclassify
```

### Amplification Assessment:

```
Did institutional constraints extend the duration of technical remediation
beyond private-sector baseline?
    → YES: Code interaction effect (I × T)
    → Estimate amplification factor: (Actual duration) / (Baseline duration)
```

---

## APPENDIX B: COMPLEXITY EQUIVALENCE ASSESSMENT

### Systematic Comparison of IPPS-A and Walmart Workday

| Factor | IPPS-A Measure | Walmart Measure | Complexity Assessment |
|--------|---------------|-----------------|----------------------|
| Employee count | 1.1M | 2.1M | Walmart 1.9x scale |
| Countries | 1 (+ deployments) | 28 | Walmart more complex |
| Currencies | 1 | 15+ | Walmart more complex |
| Pay types | ~20 (base, BAH, BAS, combat, hazard, etc.) | ~10 (hourly, salary, bonus variants) | IPPS-A more complex |
| Regulatory regimes | 1 federal + military | 50 state + 28 national | Walmart more complex |
| Annual transactions | Moderate (lower turnover) | Very high (100%+ turnover in some roles) | Walmart higher volume |
| Legacy systems replaced | 50+ | Multiple (PeopleSoft modules) | Comparable |
| Data sensitivity | High (some classified) | High (PII for 2.1M) | Comparable |
| Operational stakes | Mission-critical | Business-critical + safety-critical (trucking) | Comparable |

**Conclusion:** Neither implementation is clearly "simpler." Complexity is distributed differently but comparable in aggregate. Divergent outcomes cannot be attributed to complexity differences.

---

## APPENDIX C: SEALED PREDICTIONS FOR OPM IMPLEMENTATION

The following predictions are registered as of December 2025, prior to OPM HCM contract award:

**PREDICTION 1: Award timeline exceeds RFP schedule by 6-12 months**
- Registration date: December 2025
- Evaluation date: Q2 2027 (18 months post-RFP)
- Falsification criterion: Award within 3 months of RFP schedule

**PREDICTION 2: <60% agency participation at T+24**
- Registration date: December 2025
- Evaluation date: Q2 2028 (24 months post-award)
- Falsification criterion: >75% agency participation

**PREDICTION 3: Union negotiations extend deployment 4-8 months**
- Registration date: December 2025
- Evaluation date: Per agency deployment schedule
- Falsification criterion: <2 months union-attributable delay

**PREDICTION 4: <50% legacy retirement at T+48 months despite plan**
- Registration date: December 2025
- Evaluation date: Ongoing tracking
- Falsification criterion: >70% retirement at T+48 months

---

*This working paper is prepared for advisor review. Comments welcome.*
