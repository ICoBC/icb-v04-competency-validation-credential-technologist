<!--
author:   ICoBC - International Council on Badges and Credentials
email:    info@icobc.net
version:  1.0.0
language: en
narrator: UK English Female
comment:  Candidate guide for the work-based validation of competency at ICSF skill STND, level L3 Enable: how to collect, structure and defend evidence that the credential systems you run are standard-conformant, well operated and sensibly integrated.
@style
:root { --icobc-navy:#02375B; --icobc-orange:#F78222; --icobc-cyan:#5DCAE7; --icobc-lime:#B1CF37; --icobc-mist:#F1F5F8; --icobc-line:#D8E2E9; --icobc-muted:#4F6576; }
body { font-family: "Open Sans", Arial, sans-serif; }
h1, h2, h3, h4 { color: var(--icobc-navy); }
a { color: var(--icobc-navy); }
table th { background: var(--icobc-mist); color: var(--icobc-navy); }
blockquote { border-left: 4px solid var(--icobc-orange); background: var(--icobc-mist); padding: 8px 16px; }
@end
-->

# Competency Validation: Credential Technologist

**Proof that you run standard-conformant credential technology in live work.**

Course ID: ICB-V04 | Badge: Competency Validation: Credential Technologist (Competency, L3), alignment code ICSF-STND-L3-C

## About this course

This is a candidate guide for a work-based validation. It is not a course that teaches the topic from the start. It tells you what evidence from live work to collect, how to structure your portfolio, how the manager attestation works and how to prepare for the 45-minute technical discussion.

**Who it is for**

- HR and learning technology owners (audience C3) who run credential tooling in a corporate academy, an HR department or a learning organisation.
- Education IT and credential operations staff (audience E4) in universities, colleges and training providers.

**Framework alignment**

The validation sits in the ICoBC Credentialing Skills Framework (ICSF), skill STND "Standards and interoperability", under the VRITE pillar Trustworthiness. The level is L3 "Enable" and the stage is C "Competency".

- Skill at this level: you select standards and profiles for a programme, map data models and resolve interoperability issues.
- Stage definition: you apply the capability in a real context, usually work, with the responsibility of the stated level, over time and with observable effect.

**Learning outcomes**

1. Show that systems you run issue and verify standard-conformant credentials.
2. Show how you handle status, revocation and incidents.
3. Show integration and data portability decisions you made.

**Workload**

About 15 hours of candidate preparation and assessment. Most of this time goes into selecting, checking and describing evidence that already exists in your work. You should not need to create new systems for the validation.

**Prerequisites**

- ICB-P07 Open Badges 3.0 and Verifiable Credentials: Hands-on Lab
- ICB-P09 Choosing a Credential Platform Without Lock-in
- ICB-P11 Running Credential Operations

**How it is assessed**

- A technical portfolio with conformance results and operations records.
- A manager attestation.
- A 45-minute technical discussion.

**Badge**

"Competency Validation: Credential Technologist (Competency, L3)". Badge evidence is the portfolio, the attestation and the discussion record. The badge is valid for 3 years.

**Focus of this guide**

The quality focus is VRITE Trustworthiness. The AI focus is the disclosure of AI use in technical artefacts: if AI tools helped you write a mapping, a script, a policy or a report in your portfolio, you say so.

| Outcome | Module | How it is assessed |
|---|---|---|
| 1. Show that systems you run issue and verify standard-conformant credentials. | Portfolio guidance; Selecting evidence | Conformance results and sample credentials in the portfolio; questions in the technical discussion |
| 2. Show how you handle status, revocation and incidents. | Selecting evidence; Preparing for the technical discussion | Operations records in the portfolio; manager attestation; incident walk-through in the technical discussion |
| 3. Show integration and data portability decisions you made. | Portfolio guidance; Preparing for the technical discussion | Decision records and mappings in the portfolio; reasoning explored in the technical discussion |

> Completing this guide or passing the validation does not by itself prove competency in a job. The badge records that a panel reviewed your evidence from live work against stated criteria at a point in time.

**How the guide is built**

Each of the three modules has three parts: guidance, a worked example of good evidence, and a practice activity with a self-check. Two settings recur: a corporate academy (an HR department running credentials for employees and partners) and a university or training provider.

**Status of topics**

Status as of November 2026; check before publishing.

| Topic | Status | What to remember |
|---|---|---|
| Open Badges 3.0 and CLR 2.0 | Established | Current specifications. Platform support is still uneven, so check the conformance certification of your tools. |
| W3C Verifiable Credentials Data Model 2.0 | Established | A W3C Recommendation since 2025. Related specifications for status lists and securing mechanisms continue to evolve. |
| EUDI Wallet (eIDAS 2.0) | Emerging | Member States must offer at least one wallet by 24 December 2026. Germany plans its state wallet ("d-you") for 2 January 2027 with basic functions first. Regulated private sectors must accept the wallet about one year after issuance starts. Readiness varies widely between Member States. |

<!-- VERIFY: Confirm all EUDI Wallet dates and the German wallet plans against official sources before publication. -->

## Portfolio guidance

This module explains what the portfolio is, how to structure it and what the panel expects to see. It prepares you mainly for outcomes 1 and 3.

### What the portfolio must show

The portfolio is a technical dossier built from live work. It shows that you, personally, carry out the work described in ICSF skill STND at level L3: you select standards and profiles, map data models and resolve interoperability issues.

The panel looks for three qualities in everything you submit:

- **Real:** the artefact comes from a system that serves real earners, learners or employees, not from a sandbox built for the validation.
- **Yours:** your role is clear. A team result is fine, as long as you say what you decided and what you did.
- **Over time:** the evidence covers weeks or months, not a single afternoon. Stage C asks for application over time with observable effect.

A good portfolio is short and well indexed. Aim for 12 to 20 artefacts, each with a one-paragraph cover note. Quality of selection counts more than volume.

Keep the portfolio in a format the panel can open without special tools: PDF for documents, plain JSON files for sample credentials, and text or CSV exports for logs and conformance results.

### The evidence map

The technical evidence map links each outcome to the artefacts that support it. Build your own version of this map before you collect anything. It stops you from collecting 30 documents for outcome 1 and none for outcome 3.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Technical evidence map</title>
  <desc>Three outcome boxes on the left connect to three groups of portfolio artefacts on the right: conformance results and sample credentials for outcome 1, operations records for outcome 2, and decision records and mappings for outcome 3. A navy box in the centre labelled Candidate with a role statement joins them.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#F1F5F8"/>
  <rect x="30" y="40" width="220" height="90" rx="6" ry="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="140" y="75" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Outcome 1</text>
  <text x="140" y="97" font-size="14" fill="#02375B" text-anchor="middle">Issue and verify</text>
  <text x="140" y="115" font-size="14" fill="#02375B" text-anchor="middle">to the standards</text>
  <rect x="30" y="180" width="220" height="90" rx="6" ry="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="140" y="215" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Outcome 2</text>
  <text x="140" y="237" font-size="14" fill="#02375B" text-anchor="middle">Status, revocation</text>
  <text x="140" y="255" font-size="14" fill="#02375B" text-anchor="middle">and incidents</text>
  <rect x="30" y="320" width="220" height="90" rx="6" ry="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="140" y="355" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Outcome 3</text>
  <text x="140" y="377" font-size="14" fill="#02375B" text-anchor="middle">Integration and</text>
  <text x="140" y="395" font-size="14" fill="#02375B" text-anchor="middle">data portability</text>
  <rect x="540" y="40" width="230" height="90" rx="6" ry="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="655" y="75" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Conformance results</text>
  <text x="655" y="97" font-size="14" fill="#02375B" text-anchor="middle">Sample credentials</text>
  <text x="655" y="115" font-size="14" fill="#02375B" text-anchor="middle">Verification logs</text>
  <rect x="540" y="180" width="230" height="90" rx="6" ry="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="655" y="215" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Operations records</text>
  <text x="655" y="237" font-size="14" fill="#02375B" text-anchor="middle">Revocation log</text>
  <text x="655" y="255" font-size="14" fill="#02375B" text-anchor="middle">Incident reports</text>
  <rect x="540" y="320" width="230" height="90" rx="6" ry="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="655" y="355" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Decision records</text>
  <text x="655" y="377" font-size="14" fill="#02375B" text-anchor="middle">Data mappings</text>
  <text x="655" y="395" font-size="14" fill="#02375B" text-anchor="middle">Export and exit tests</text>
  <circle cx="395" cy="225" r="62" fill="#02375B"/>
  <text x="395" y="220" font-size="14" fill="#FFFFFF" text-anchor="middle" font-weight="bold">Candidate</text>
  <text x="395" y="240" font-size="14" fill="#FFFFFF" text-anchor="middle">role statement</text>
  <line x1="250" y1="85" x2="340" y2="190" stroke="#02375B" stroke-width="2"/>
  <line x1="250" y1="225" x2="333" y2="225" stroke="#02375B" stroke-width="2"/>
  <line x1="250" y1="365" x2="340" y2="260" stroke="#02375B" stroke-width="2"/>
  <line x1="457" y1="200" x2="540" y2="95" stroke="#02375B" stroke-width="2"/>
  <line x1="457" y1="225" x2="540" y2="225" stroke="#02375B" stroke-width="2"/>
  <line x1="457" y1="250" x2="540" y2="355" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="440" font-size="14" fill="#4F6576" text-anchor="middle">Cyan: education and provider artefacts. Lime: operations artefacts. Orange: employer-side decisions.</text>
</svg>

The colours in the graphic are labels for the kind of artefact. Your own artefacts may come from either an employer or an education setting, and many will come from both.

### Structure of the portfolio

Use this structure. It is the same for every candidate, which helps the panel to read your work quickly.

1. **Cover sheet** (one page): name, organisation, role, systems in scope, period covered, and the AI disclosure statement.
2. **Role statement** (half a page): what you are responsible for, and what others decide.
3. **Evidence index** (one page): a table listing every artefact with its ID, title, date, outcome supported and the criteria it addresses.
4. **Section A, Issue and verify** (outcome 1): conformance results, sample credentials, verification evidence.
5. **Section B, Status, revocation and incidents** (outcome 2): operations records and incident records.
6. **Section C, Integration and portability** (outcome 3): decision records, data mappings, export tests.
7. **Reflection** (one page): what you would change in your set-up after this review.
8. **Attestation** (sent separately by your manager, see below).

### The AI disclosure statement

The AI focus of this validation is the disclosure of AI use in technical artefacts. On your cover sheet, state whether AI tools were used in preparing any artefact. For each artefact where they were, say:

- what the tool was used for, for example drafting a field mapping table or summarising a log;
- what you checked or changed yourself;
- who is accountable for the final content, which is you.

If you used no AI tools, write that in one line. A missing statement is treated as an incomplete portfolio, because the panel cannot judge trustworthiness without it.

### Confidentiality and data protection

Your artefacts will contain real data. Before submitting, remove or pseudonymise personal data of earners and colleagues. Replace names, email addresses and identifiers with consistent placeholders such as "Earner A". Black out internal URLs and credentials. Tell the panel in the cover note what you changed. Check your organisation's rules before you share anything, and ask for written permission where needed.

<!-- VERIFY: Confirm that ICoBC panel confidentiality terms and data handling for submitted portfolios are stated in the current candidate agreement. -->

**Worked example: A portfolio index from a corporate academy**

Maria Keller is the learning technology owner in the HR department of a mid-sized company. The numbers below are illustrative. She runs a credential service for internal training and for partner suppliers. Her evidence index begins like this:

| ID | Artefact | Date | Outcome | Criteria |
|---|---|---|---|---|
| A1 | Conformance test results for the issuing service, export from the test suite | 12 March | 1 | C1 |
| A2 | Three redacted sample credentials, JSON, for three course types | 12 March | 1 | C1 |
| A3 | Verification log extract, 30 days, with three failed verifications explained | 30 April | 1 | C1, C2 |
| B1 | Revocation log extract, 6 months, with reasons and timings | 30 Sept | 2 | C3 |
| B2 | Incident report: expired signing key, with timeline and follow-up actions | 17 June | 2 | C3, C4 |
| C1 | Decision record: choice of profile for supplier training badges | 5 Feb | 3 | C5 |
| C2 | Mapping table: HR system fields to credential fields | 5 Feb | 3 | C5 |
| C3 | Export test: full issued-credential export and re-import into a test system | 22 Aug | 3 | C6 |

Why this is good evidence: every item has a date, belongs to live work, names the outcome it supports and can be checked by the panel. The index shows a spread over seven months, so the panel sees application over time. Maria's cover sheet adds that AI tools helped her draft the layout of mapping table C2, and that she checked every row against the source system.

**Practice activity: Draft your evidence index**

Time: about 90 minutes.

1. List every system you run or help run that issues or verifies credentials. Note your role for each.
2. For each learning outcome, list up to six possible artefacts from the last 12 months. Do not worry about quality yet.
3. Build a table with the columns ID, Artefact, Date, Outcome, Criteria. Use the criteria table in "Assessment and badge" to fill the last column.
4. Mark any outcome that has fewer than three artefacts. Plan what you will collect to fill the gap.
5. Draft your AI disclosure statement, even if it only says that you used no AI tools.

<details>
<summary>Facilitator notes</summary>

Use this activity in a 90-minute online session or as home preparation. Candidates often start with the artefacts they are proud of rather than with the outcomes. Ask them to show their outcome-to-artefact grid, not the documents. Look for gaps in outcome 3, which is the one most often neglected. Remind candidates that the evidence must come from live work, and that a sandbox built for the validation does not meet the stage definition.

</details>

**Self-check: Portfolio guidance**

**Question 1.** Which description best fits the portfolio the panel expects?

[( )] A long collection of all documents produced in the last five years, so the panel can choose.
[(X)] A short, indexed set of real, dated artefacts from live work, each linked to an outcome, with your own role clear.
[( )] A demonstration environment built for the validation, so that no real data is involved.
[( )] A slide presentation that summarises your system architecture without original artefacts.
[[?]] Think about the stage definition: real context, over time, observable effect.
****
The stage C definition asks for application in a real context, over time, with observable effect. A short, indexed set of dated artefacts with a clear role statement meets this. A demonstration environment does not come from live work, and an archive of everything makes it hard for the panel to judge.
****

**Question 2.** You used an AI tool to draft a field mapping table, then corrected several rows yourself. What do you do?

[( )] Nothing, because you corrected the table and it is now your work.
[( )] Remove the table from the portfolio so that AI use is not an issue.
[(X)] Disclose on the cover sheet what the tool was used for, what you checked or changed, and that you are accountable for the final content.
[( )] Ask the tool to add a statement to the table that it was created by AI.
[[?]] The AI focus is disclosure of AI use in technical artefacts.
****
Disclosure is the rule. Say what the tool did, what you verified and that you are accountable. Hiding or removing the artefact does not help the panel judge trustworthiness, and a statement written by the tool is not your accountability statement.
****

**Question 3.** Before you submit redacted sample credentials, what must you do about earner data?

[( )] Submit them unchanged, because the panel is bound by confidentiality.
[( )] Delete the identifier fields so the credentials no longer validate against the data model.
[(X)] Remove or pseudonymise personal data consistently, note what you changed, and check your organisation's rules and permissions first.
[( )] Replace the real credentials with invented ones so that no real data is involved.
[[?]] Consistent placeholders keep the structure readable.
****
Pseudonymise with consistent placeholders so the structure remains readable, and tell the panel what you changed. Check permissions first. Invented credentials would not be evidence from live work, and deleting identifier fields would break the structure the panel wants to see.
****

## Selecting evidence

This module explains which artefacts best show each outcome, how to judge their quality and how the manager attestation works. It prepares you for outcomes 1 and 2 above all, and it supports outcome 3.

### Evidence for outcome 1: issue and verify to the standards

The panel wants to see that the systems you run produce credentials that meet the current standards, and that they are checked in practice. Strong evidence for this outcome includes:

- **Conformance results.** Output from a conformance or validation test for your issuing service, with the date, the tool or test suite named in neutral terms, the version of the specification tested and the result. Include failed tests and what you did about them.
- **Sample credentials.** Two or three redacted credentials, in their native data format, that represent different credential types. Open Badges 3.0 credentials and CLR 2.0 records are the current specifications for badges and learner records. W3C Verifiable Credentials Data Model 2.0 has been a W3C Recommendation since 2025.
- **Verification evidence.** Logs or records showing that credentials were verified by someone other than the issuing system, for example an employer or a partner institution, with outcomes.
- **Tool conformance information.** Platform support for the standards is still uneven. Show that you checked the conformance certification of the tools you use, and note what is certified and what is not.

Related specifications for status lists and securing mechanisms continue to evolve. Where your set-up depends on them, record the exact version or draft you used and the date you checked it. Do not claim conformance to a specification version you did not test.

<!-- VERIFY: Confirm current names, versions and publication status of the status list and securing mechanism specifications referenced in candidate evidence. -->

### Evidence for outcome 2: status, revocation and incidents

This outcome is about what happens after issuing. Good evidence shows that you run the lifecycle of a credential, not only its first day.

- **Status and revocation records.** An extract from your revocation or suspension log covering several months: the credential, the reason category, the date of the request, the date of the action and who approved it.
- **Policy or procedure.** The rule your organisation follows for revocation, with your role in it. A short, current document is enough.
- **Incident record.** One or two real incidents, for example an expired signing key, a verification failure after a platform update or an issuing error that affected many earners. For each: timeline, impact, how earners and verifiers were informed, the fix and the follow-up.
- **Monitoring.** A sample of the checks you run, for example key expiry reminders or verification failure reports.

The panel values honest incident records. An incident with a clear cause, a clear fix and a lesson learned is stronger evidence than a claim that nothing ever went wrong.

### Evidence for outcome 3: integration and portability

This outcome asks for decisions you made, not only systems you operate. The panel wants to know why.

- **Decision records.** A short record of a real choice, for example which profile to use for a programme, or whether to integrate the credential service with the HR or student record system. Include the options you considered, the criteria, the decision and the date.
- **Data mappings.** A table showing how fields in a source system map to fields in the credential data model, with notes on gaps and workarounds.
- **Portability tests.** Evidence that earners and your organisation can take data out: an export of issued credentials, a re-import or verification in another system, or a documented exit plan.
- **Interoperability issues you resolved.** One case in which two systems did not work together, with diagnosis and resolution.

Wallets are an emerging topic. Member States must offer at least one EUDI Wallet by 24 December 2026, Germany plans its state wallet for 2 January 2027 with basic functions first, and regulated private sectors must accept the wallet about one year after issuance starts. Readiness varies widely between Member States. If you made a decision with wallets in mind, record what you assumed and what you will recheck. If you have made no wallet decision yet, do not invent one: say so, and explain how your portability evidence prepares you.

Status as of November 2026; check before publishing.

<!-- VERIFY: Confirm EUDI Wallet milestone dates, the planned German wallet name and date, and the acceptance timeline for regulated private sectors. -->

### Judging the quality of an artefact

Before you add an artefact, ask five questions:

1. **Authentic:** does it come from live work?
2. **Dated:** can the panel see when it was created?
3. **Attributable:** is your role clear?
4. **Relevant:** does it show something specific in the criteria table?
5. **Checkable:** could the panel ask you about it and expect a detailed answer?

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Operations record excerpt</title>
  <desc>A sample table excerpt of a revocation and incident log with four columns: date, event, action and owner. Three rows are shown and a callout lists what makes the excerpt good evidence: dated, reason given, timing visible, owner named, redacted.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <text x="40" y="40" font-size="16" fill="#02375B" font-weight="bold">Operations record excerpt (illustrative, redacted)</text>
  <rect x="40" y="60" width="720" height="40" rx="6" ry="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="55" y="86" font-size="14" fill="#02375B" font-weight="bold">Date</text>
  <text x="165" y="86" font-size="14" fill="#02375B" font-weight="bold">Event</text>
  <text x="400" y="86" font-size="14" fill="#02375B" font-weight="bold">Action</text>
  <text x="640" y="86" font-size="14" fill="#02375B" font-weight="bold">Owner</text>
  <rect x="40" y="100" width="720" height="44" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="55" y="127" font-size="14" fill="#02375B">3 Mar</text>
  <text x="165" y="127" font-size="14" fill="#02375B">Issuing error, Earner A</text>
  <text x="400" y="127" font-size="14" fill="#02375B">Revoked, reissued</text>
  <text x="640" y="127" font-size="14" fill="#02375B">Candidate</text>
  <rect x="40" y="144" width="720" height="44" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="55" y="171" font-size="14" fill="#02375B">17 Jun</text>
  <text x="165" y="171" font-size="14" fill="#02375B">Signing key expired</text>
  <text x="400" y="171" font-size="14" fill="#02375B">Key renewed, notice sent</text>
  <text x="640" y="171" font-size="14" fill="#02375B">Candidate, IT</text>
  <rect x="40" y="188" width="720" height="44" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="55" y="215" font-size="14" fill="#02375B">9 Sep</text>
  <text x="165" y="215" font-size="14" fill="#02375B">Withdrawal request, Earner B</text>
  <text x="400" y="215" font-size="14" fill="#02375B">Status set to revoked</text>
  <text x="640" y="215" font-size="14" fill="#02375B">HR lead</text>
  <rect x="40" y="260" width="720" height="150" rx="6" ry="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="60" y="290" font-size="14" fill="#02375B" font-weight="bold">Why this is good evidence</text>
  <text x="60" y="318" font-size="14" fill="#02375B">1. Dated entries over several months</text>
  <text x="60" y="342" font-size="14" fill="#02375B">2. Reason and action recorded for each event</text>
  <text x="60" y="366" font-size="14" fill="#02375B">3. Owner named, so your role is visible</text>
  <text x="60" y="390" font-size="14" fill="#02375B">4. Earners pseudonymised, structure kept</text>
</svg>

### The manager attestation

The manager attestation is a short statement from a person who supervises or sponsors your work and can confirm that the portfolio reflects live work. It is not a reference letter and it does not replace the evidence.

How it works:

1. **You choose the attester.** This is usually your line manager, programme owner or head of department. If no suitable manager exists, ask a senior colleague who has seen your work over time and tell the panel why.
2. **You brief them.** Share the outcomes, the criteria table and your evidence index. Ask them to read the artefacts they are asked to confirm.
3. **They write and send it themselves.** The attester sends the attestation directly to the panel, not through you. This protects its independence.
4. **It covers four points.** The relationship and the period they have known your work, the systems and responsibilities you hold, confirmation that the artefacts are from live work and that you did what you describe, and any limits, for example decisions made by others.
5. **It states no more than they know.** A good attester says what they have seen and what they have not.

<!-- VERIFY: Confirm the current attestation form, submission route and deadlines in the ICoBC candidate agreement. -->

**Worked example: An incident record from a university**

Dr Samira Haddad leads credential operations at a university. The numbers below are illustrative. Her incident record covers a failure that affected graduates during a busy summer:

- **Summary:** after a platform update, 410 degree-related credentials failed verification at two partner employers.
- **Detection:** a verifier reported the problem on day 1; Samira confirmed it with a test verification the same morning.
- **Cause:** the update changed how the signing key reference was published. Samira compared the credential against the data model and located the changed reference.
- **Resolution:** the provider corrected the reference within two days. Samira re-verified a sample of 30 credentials from each batch and recorded the results.
- **Communication:** a message to graduates and verifiers on day 2 and a closing note on day 4.
- **Follow-up:** a post-update verification test was added to the change procedure, and the supplier agreement was amended to require advance notice of changes to key references.
- **AI disclosure:** Samira used an AI tool to tidy the timeline wording and confirmed every date from the system logs.

Why this is good evidence: it shows detection, diagnosis against the standard, communication, resolution and a lasting change in the procedure. It also shows Samira's own part and an honest account of the supplier's role.

**Practice activity: Choose and assess three artefacts**

Time: about 2 hours.

1. For each outcome, pick the single strongest artefact from your list.
2. Apply the five quality questions (authentic, dated, attributable, relevant, checkable). Write one sentence for each answer.
3. Replace any artefact that fails two or more questions.
4. Draft the cover note for each artefact in five lines: what it is, when, your role, which outcome and criteria, what you changed for confidentiality.
5. Write the briefing email to your attester. List what you want them to confirm and attach the evidence index.

<details>
<summary>Facilitator notes</summary>

Ask candidates to swap one cover note with a peer and to answer the five quality questions as reviewers. Common weaknesses: artefacts without dates, role statements that say "we" throughout, and incident records that skip the cause. If a candidate has no incident, do not invent one. Look for smaller operational events, for example a revocation request, a failed verification or a key renewal, and help the candidate to document them honestly. For outcome 3, watch for decision records written after the fact. A decision record should come from the time of the decision, or say clearly that it was reconstructed.

</details>

**Self-check: Selecting evidence**

**Question 4.** Which artefact best supports outcome 2, status, revocation and incidents?

[( )] A product brochure that describes the revocation features of your platform.
[( )] A diagram of the intended revocation process that has never been used.
[(X)] A dated extract of your revocation log over several months, with reasons, timings and owners, plus one incident record with timeline and follow-up.
[( )] A statement that no revocations or incidents have occurred.
[[?]] Outcome 2 asks how you handle these events in live work.
****
The panel wants records of real handling over time. A log extract with reasons, timings and owners, together with an incident record, shows that you run the lifecycle. A brochure or an unused diagram does not show your own handling, and an empty claim cannot be checked.
****

**Question 5.** What is the main difference between a decision record and a data mapping in outcome 3?

[( )] A decision record is for earners and a data mapping is for verifiers.
[(X)] A decision record explains a choice with options, criteria and a date, while a data mapping shows how source fields correspond to credential fields.
[( )] A decision record is only needed for new systems and a data mapping only for old systems.
[( )] They are the same document written for different audiences.
[[?]] One shows reasoning, the other shows structure.
****
A decision record captures the reasoning: options, criteria, the choice and its date. A data mapping captures the structure: which source field feeds which credential field, with gaps and workarounds. Outcome 3 asks for both kinds of evidence because decisions and mappings show different parts of your competence.
****

**Question 6.** How does the manager attestation reach the panel?

[( )] You collect it and place it in your portfolio so the panel finds everything in one place.
[( )] Your manager signs a template that you wrote, and you submit it.
[( )] It is not needed if your portfolio is complete.
[(X)] Your manager writes it and sends it directly to the panel, covering the period and responsibilities they know and confirming the work is live.
[[?]] Independence is the purpose.
****
The attestation is independent evidence. Your manager writes it, sends it directly and states only what they know. A template you wrote yourself or a document you forward weakens that independence, and the attestation is part of the badge evidence, so it cannot be skipped.
****

## Preparing for the technical discussion

This module explains the 45-minute technical discussion and how to prepare for it. It brings together all three outcomes, with a particular focus on outcomes 2 and 3.

### What the discussion is

The technical discussion is a conversation between you and one or two panel members who have read your portfolio. It takes 45 minutes. It is not an exam on definitions. The panel wants to understand what you did, why you did it and how you think about problems.

The discussion checks three things:

- **Authenticity:** you can talk about your evidence in detail, because you did the work.
- **Judgement:** you explain choices and trade-offs, and you know the limits of your solution.
- **Trustworthiness:** you are honest about what went wrong, what you do not know and how you used AI tools.

### A suggested shape for the 45 minutes

The exact running order is set by the panel. This shape is typical.

| Minutes | Part | What happens |
|---|---|---|
| 0 to 5 | Opening | Introductions, your role, the systems in scope, the AI disclosure statement |
| 5 to 20 | Outcome 1 and 2 | Walk-through of conformance results, a sample credential, an operations record and an incident |
| 20 to 35 | Outcome 3 | Decision records, mappings, portability tests, interoperability issues |
| 35 to 43 | Scenarios | The panel gives one or two short "what would you do" cases |
| 43 to 45 | Close | Your questions, next steps |

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Shape of the 45-minute technical discussion</title>
  <desc>A horizontal timeline in five segments: opening from 0 to 5 minutes, outcomes 1 and 2 from 5 to 20, outcome 3 from 20 to 35, scenarios from 35 to 43 and close from 43 to 45. Below the timeline, three preparation habits are listed: know your artefacts, prepare a failure story, be ready to explain trade-offs.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#F1F5F8"/>
  <text x="40" y="45" font-size="16" fill="#02375B" font-weight="bold">The 45-minute technical discussion</text>
  <rect x="40" y="80" width="80" height="70" rx="6" ry="6" fill="#02375B"/>
  <text x="80" y="110" font-size="14" fill="#FFFFFF" text-anchor="middle" font-weight="bold">Opening</text>
  <text x="80" y="132" font-size="14" fill="#FFFFFF" text-anchor="middle">0 to 5</text>
  <rect x="124" y="80" width="230" height="70" rx="6" ry="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="239" y="110" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Outcomes 1 and 2</text>
  <text x="239" y="132" font-size="14" fill="#02375B" text-anchor="middle">5 to 20</text>
  <rect x="358" y="80" width="230" height="70" rx="6" ry="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="473" y="110" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Outcome 3</text>
  <text x="473" y="132" font-size="14" fill="#02375B" text-anchor="middle">20 to 35</text>
  <rect x="592" y="80" width="120" height="70" rx="6" ry="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="652" y="110" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Scenarios</text>
  <text x="652" y="132" font-size="14" fill="#02375B" text-anchor="middle">35 to 43</text>
  <rect x="716" y="80" width="44" height="70" rx="6" ry="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="738" y="110" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">End</text>
  <text x="738" y="132" font-size="14" fill="#02375B" text-anchor="middle">43</text>
  <rect x="40" y="200" width="220" height="190" rx="6" ry="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="150" y="232" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Know your artefacts</text>
  <text x="150" y="262" font-size="14" fill="#4F6576" text-anchor="middle">Re-read every item</text>
  <text x="150" y="284" font-size="14" fill="#4F6576" text-anchor="middle">Know the dates, the</text>
  <text x="150" y="306" font-size="14" fill="#4F6576" text-anchor="middle">tools and your part</text>
  <rect x="290" y="200" width="220" height="190" rx="6" ry="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="232" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Prepare a failure story</text>
  <text x="400" y="262" font-size="14" fill="#4F6576" text-anchor="middle">Cause, impact, fix,</text>
  <text x="400" y="284" font-size="14" fill="#4F6576" text-anchor="middle">lesson, change made</text>
  <rect x="540" y="200" width="220" height="190" rx="6" ry="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="650" y="232" font-size="14" fill="#02375B" text-anchor="middle" font-weight="bold">Explain trade-offs</text>
  <text x="650" y="262" font-size="14" fill="#4F6576" text-anchor="middle">Options, criteria,</text>
  <text x="650" y="284" font-size="14" fill="#4F6576" text-anchor="middle">risks, what you</text>
  <text x="650" y="306" font-size="14" fill="#4F6576" text-anchor="middle">would revisit</text>
</svg>

### Questions to expect

You cannot predict every question, but you can prepare for the kinds of question the panel will ask.

**On issuing and verification (outcome 1)**

- Which specification versions do your systems support, and how do you know?
- Show me a credential from your portfolio. Which fields are required, and which did you add?
- How did you check conformance? What did the tool not cover?
- How can someone outside your organisation verify this credential?

**On status, revocation and incidents (outcome 2)**

- When do you revoke and when do you suspend or reissue? Who decides?
- Walk me through your incident. When did you know? What did you tell earners?
- What would you do if a signing key were compromised?
- How do you test that status information is still reachable?

**On integration and portability (outcome 3)**

- Why did you choose this profile? What else did you consider?
- Where do your mappings lose information, and how do you handle that?
- If you changed platform tomorrow, what would an earner keep?
- How do wallets affect your plans, and what would you recheck before acting?

**On AI use and trustworthiness**

- Which artefacts did you prepare with AI support? What did you verify yourself?
- Where would you not use AI for a technical artefact, and why?

### How to answer well

- **Start with your role.** Say "I decided" or "I ran" when you did, and "the team decided" when you did not.
- **Use the artefact.** Point to the log line, the field or the table row. Panels like specifics.
- **Name the limit.** Say what your solution does not cover. This shows judgement.
- **Be honest about the emerging.** For topics marked Emerging, such as the EUDI Wallet, say what is known, what is planned and what you will recheck. Do not present plans as facts.
- **Ask for clarification.** If a question is unclear, restate it before answering.
- **Do not guess.** "I do not know, and this is how I would find out" is an acceptable answer. An invented answer is not.

### Practical preparation

- Re-read your portfolio the day before, with the criteria table next to it.
- Prepare a one-page note of the main facts: systems, versions, dates, numbers. You may use it if the panel allows notes.
- Test your video link, audio and screen sharing. Have the artefacts open in a folder.
- Prepare a 3-minute overview of your role and systems for the opening.
- Plan a quiet place and a short break before the discussion.

<!-- VERIFY: Confirm the discussion format, permitted notes and online platform rules in the current ICoBC candidate agreement. -->

**Worked example: A strong answer on a portability decision**

Panel question to Jonas Reiter, a head of training operations at a vocational training provider: "If you changed platform tomorrow, what would an earner keep?"

Jonas answers, using his portability test (artefact C3 in his index):

"Earners keep every credential they have already collected, because each one is signed and verifiable on its own. In March, I ran a full export of 1,200 issued credentials (an illustrative figure from our test) and verified a sample of 50 in a second environment. 47 verified without change. Three failed because the issuer identifier pointed to a path that only exists on our current platform. I recorded that as a risk and agreed with our IT team to host the issuer identifier on a domain we control. Earners would lose two things: the badge gallery pages on the current platform, and the analytics on how often employers view them. I put both in the exit plan. I have not yet tested wallet import. Wallet readiness varies between Member States and I will recheck the position when the national wallet is available."

Why this is a strong answer: Jonas refers to a real test, gives numbers, names the three failures and their cause, states what was lost and what he did about it, and is honest about what he has not tested. He does not claim more about wallets than he knows.

**Practice activity: Rehearse the discussion**

Time: about 3 hours including a peer session.

1. Write answers of no more than 90 seconds to one question from each group above, using your own artefacts.
2. Prepare your failure story in five parts: cause, impact, fix, lesson, change made.
3. Arrange a 45-minute mock discussion with a peer or mentor who has read your evidence index. Ask them to play the panel, using the questions above and two scenarios of their own.
4. After the mock, note three answers that were vague and rewrite them with a specific artefact reference.
5. Check your AI disclosure statement again and prepare a clear answer on what you verified yourself.

<details>
<summary>Facilitator notes</summary>

Offer mock discussions in pairs or small groups. The facilitator should follow the same time boxes as the real discussion and should avoid coaching during the conversation. Give feedback afterwards on four points: use of specifics, clarity of role, honesty about limits, and handling of emerging topics. If candidates tend to over-claim on wallets, remind them that wallet readiness varies widely and that the correct answer includes what they will recheck. Do not share live panel questions. The practice questions in this guide are examples, not a question bank.

</details>

**Self-check: Preparing for the technical discussion**

**Question 7.** The panel asks about EUDI Wallet readiness for your programme, and you have not yet made any wallet decision. What is the best answer?

[( )] Say that your platform is fully ready for all wallets, to show confidence.
[( )] Say that wallets are irrelevant to credential technology.
[(X)] Say what you know and what is planned, state that you have made no decision yet, explain how your portability evidence prepares you and name what you will recheck.
[( )] Refuse to answer, because the topic is not in your portfolio.
[[?]] The topic is marked Emerging and readiness varies widely.
****
For an emerging topic, accurate and honest is the right approach. State what is known and planned, that you have not decided, how your existing work prepares you and what you will recheck. Over-claiming is a trustworthiness problem, and refusing to engage misses the chance to show judgement.
****

**Question 8.** Which is the strongest way to answer "Walk me through your incident"?

[( )] Give a general description of how incidents are usually handled in credential systems.
[(X)] Use your incident record: timeline, your own actions, cause, communication to earners and verifiers, fix and the change you made afterwards.
[( )] Explain that the incident was the supplier's fault and that nothing could have been done.
[( )] Describe an incident from a colleague's system that had a better outcome.
[[?]] The panel wants authentic detail and your own part.
****
The panel tests authenticity and judgement. A walk-through of your own record with the timeline, cause, communication, fix and follow-up shows both. General descriptions do not prove your part, blaming a supplier avoids the question, and using a colleague's incident is not your evidence.
****

**Question 9.** You used an AI tool to draft a verification script that appears in your portfolio. The panel asks how you know it works. What do you say?

[( )] The tool is accurate, so the script does not need separate checking.
[( )] You do not remember how the script was written.
[( )] You ask the panel to treat the script as a team product.
[(X)] You describe the tests you ran on it, the cases where you corrected it, and confirm that you are accountable for the result as stated in your disclosure.
[[?]] Disclosure and accountability go together.
****
Your disclosure statement promised that you verified the artefact. In the discussion, you show how: tests, corrections and accountability. Relying on the tool's accuracy, forgetting the origin or hiding behind the team would weaken trust in the whole portfolio.
****

## Assessment and badge

### The task

The validation has three parts. All three must be completed within your validation window, which the panel confirms in your candidate agreement.

<!-- VERIFY: Confirm the validation window, resubmission rules and panel composition in the current candidate agreement. -->

1. **Technical portfolio.** Submit the portfolio described in "Portfolio guidance", with conformance results, sample credentials, operations records, decision records and the AI disclosure statement.
2. **Manager attestation.** Your attester sends the attestation directly to the panel.
3. **Technical discussion.** A 45-minute conversation with the panel, based on your portfolio.

In addition, complete the final knowledge check below. It helps you confirm that you can state the core points before the discussion. It does not replace any of the three parts above.

### Assessment criteria

Each criterion is rated as Not yet met, Met or Strongly met. The panel rates the combined evidence from the portfolio, the attestation and the discussion.

| ID | Criterion | Outcome | Met when | Strongly met when |
|---|---|---|---|---|
| C1 | Standard-conformant issuing and verification | 1 | Conformance results and at least two sample credentials show that systems you run issue credentials to a stated current specification version, and verification evidence shows they were checked | Results include failed tests with documented fixes, tool conformance certification was checked, and external verification is shown |
| C2 | Accuracy about standards and their status | 1 | You state the versions you support, distinguish established from emerging topics and do not over-claim | You also explain how evolving specifications for status lists and securing mechanisms affect your set-up and what you will recheck |
| C3 | Status and revocation handling | 2 | Records over several months show reasons, timings and owners, and a procedure exists with your role stated | Records show tested status reachability, monitoring and a clear policy for revocation, suspension and reissue |
| C4 | Incident handling | 2 | At least one real incident shows timeline, cause, communication, fix and follow-up, with your part clear | The incident led to a lasting change in procedure or supplier agreement, and you can explain what remains uncertain |
| C5 | Integration and mapping decisions | 3 | At least one dated decision record shows options, criteria and choice, and a mapping shows gaps and workarounds | Decisions show trade-offs, a resolved interoperability issue and a review of earlier decisions |
| C6 | Data portability | 3 | An export or exit test shows what earners and the organisation can take with them | The test includes verification in a second environment, documented losses and a maintained exit plan |
| C7 | Authenticity and sustained practice | 1, 2, 3 | Evidence comes from live work over time, your role is clear and the attestation confirms it | Evidence spans a year or more with visible improvement and the discussion confirms deep personal involvement |
| C8 | Trustworthiness and AI disclosure | 1, 2, 3 | Confidentiality is handled, the AI statement is complete and you are honest about limits in the discussion | You show checks you made on AI-assisted artefacts and a clear view of where AI use is not suitable |

### Pass rule

- You pass when every criterion C1 to C8 is rated at least Met.
- At least two of the criteria C1 to C6 must be rated Strongly met.
- The attestation must be received and must confirm that the evidence is from live work.
- The AI disclosure statement must be complete.
- If a criterion is rated Not yet met, the panel states which evidence is missing. You may resubmit within the period set in the candidate agreement.

<!-- VERIFY: Confirm the pass rule, rating scale and resubmission period with the current ICoBC validation rules before publication. -->

### Self-check against the criteria

Before you submit, answer each question with yes or no. Any "no" shows work to do.

- [ ] My evidence index lists every artefact with date, outcome and criteria.
- [ ] Every artefact comes from live work and names my role.
- [ ] I have conformance results and at least two sample credentials with the specification version stated.
- [ ] I have verification evidence from beyond my own system.
- [ ] I have a revocation log extract over several months and a procedure.
- [ ] I have at least one real incident record with a lasting follow-up.
- [ ] I have at least one decision record and one data mapping with gaps noted.
- [ ] I have an export or exit test and I can state what is lost.
- [ ] I have briefed my attester, and the attester will send the attestation directly.
- [ ] My AI disclosure statement is on the cover sheet.
- [ ] I removed or pseudonymised personal data and have permission to share.
- [ ] I can answer questions on EUDI Wallet plans without over-claiming.

### Final knowledge check

**Question 10.** A university credential team tests its issuing service with a conformance tool, finds that three tests fail and fixes two of them. How should the candidate present this in the portfolio?

[( )] Include only the passing results, because failures could count against the candidate.
[(X)] Include the full results, show the fixes for the two failures and explain the third open failure with a plan.
[( )] Replace the results with a statement that the service is conformant.
[( )] Repeat the test until all tests pass and submit only the final run.
[[?]] Outcome 1 asks you to show conformance, and trustworthiness asks for honesty.
****
Full results with documented fixes and an explained open item show both conformance work and honesty. Selecting only passing results or replacing results with a claim weakens trustworthiness. Submitting only a final clean run hides the learning that the panel wants to see.
****

**Question 11.** Why does the panel ask you to state which specification version you tested?

[( )] Because older versions are not allowed in any programme.
[( )] Because the panel only accepts the newest draft of any specification.
[(X)] Because a conformance claim is only meaningful for a stated version, and related specifications for status lists and securing mechanisms continue to evolve.
[( )] Because version numbers are required on every badge image.
[[?]] A claim without a version cannot be checked.
****
A conformance claim relates to a particular version. Because related specifications continue to evolve, the version and the date you checked make your claim verifiable. The panel does not require the newest draft, and it does not prohibit older versions as such.
****

**Question 12.** Which record best shows that you handle revocation in live work?

[( )] A policy document that you have written but never applied.
[( )] A screenshot of a settings page showing that revocation is possible.
[(X)] A dated log extract over several months showing reasons, request and action dates and owners, with personal data pseudonymised.
[( )] A message from a supplier saying that revocation is supported.
[[?]] The panel looks for use over time.
****
A log extract shows the actual use of revocation over time, with reasons, timings and owners. A policy never applied, a settings screenshot or a supplier statement show capability or intent, not your handling in live work.
****

**Question 13.** During a discussion, you are asked what you did after a signing key expired unexpectedly. Which answer best meets criterion C4?

[( )] The key was renewed by IT and you were not involved.
[( )] The incident was minor and needs no explanation.
[(X)] You give the timeline, how you confirmed the cause, how earners and verifiers were informed, the fix and the procedure change you made afterwards.
[( )] You describe how another organisation could handle a key expiry.
[[?]] C4 asks for timeline, cause, communication, fix and follow-up.
****
Criterion C4 requires a real incident with a clear timeline, cause, communication, fix and follow-up, and your part must be visible. Stating that IT did everything or describing another organisation does not show your own handling.
****

**Question 14.** A corporate academy maps fields from its HR system to credential fields and finds that the HR system holds only a job family code, while the credential should show a role title. What best shows good practice in the portfolio?

[( )] Fill the role title with the job family code and say nothing about it.
[( )] Leave out the field and not mention the gap.
[(X)] Record the gap in the mapping table, describe the workaround and the reason, and note who agreed to it and when.
[( )] Remove the credential type from the programme.
[[?]] Outcome 3 includes the decisions you made and how you documented gaps.
****
Documenting gaps and workarounds, with the decision and its owner, shows the integration judgement that outcome 3 asks for. Silently substituting data or omitting a field hides a mapping decision.
****

**Question 15.** What does a convincing portability test include?

[( )] A statement from the platform supplier that exports are possible.
[(X)] A full export of issued credentials, verification of a sample in a second environment, and a record of what was lost.
[( )] A list of file formats the platform lists in its documentation.
[( )] A plan to test portability after the next platform change.
[[?]] Show what earners and the organisation can actually take with them.
****
A test with an actual export, verification in a second environment and a record of losses is evidence of portability. Supplier statements, documentation and future plans are not tests, and they cannot show what earners would really keep.
****

**Question 16.** A candidate used an AI tool to summarise an operations log for the portfolio. Which action meets the disclosure expectation?

[( )] Mention the AI use only if the panel asks about it in the discussion.
[( )] Remove the summary and submit the raw log without explanation.
[( )] Credit the AI tool as the author of the summary.
[(X)] State on the cover sheet what the tool was used for, what you checked against the raw log, and that you are accountable for the summary.
[[?]] Disclose in the portfolio, not only when asked.
****
Disclosure belongs in the portfolio, on the cover sheet, with the purpose, your checks and your accountability. Waiting to be asked, deleting the summary without explanation or naming the tool as author does not meet the expectation.
****

**Question 17.** A panel member asks how wallets affect your programme. Your organisation has not decided anything. Which answer is best?

[( )] Wallets will replace all other credential formats within a year.
[( )] Your organisation is exempt from any wallet rules.
[(X)] Member States must offer a wallet by 24 December 2026, readiness varies, you have made no decision yet, your export tests prepare you and you will recheck the position when national wallets are available.
[( )] No answer is possible, because the topic is not in the portfolio.
[[?]] State what is known, what is planned and what you will recheck.
****
The best answer separates the known obligation from the uncertain readiness, is honest that no decision exists, links to the portability evidence and names what will be rechecked. The other answers over-claim, assume exemption without evidence or avoid the question.
****

### Evidence submitted for the badge

The badge "Competency Validation: Credential Technologist (Competency, L3)", alignment code ICSF-STND-L3-C, is awarded on the basis of three pieces of evidence:

1. **Portfolio:** your technical portfolio, including conformance results, operations records, decision records and the AI disclosure statement.
2. **Attestation:** the manager attestation received by the panel.
3. **Discussion record:** the panel's record of the 45-minute technical discussion and its ratings against criteria C1 to C8.

The badge is valid for 3 years. It records that a panel reviewed evidence from live work against stated criteria. It does not state that the holder is competent in any particular job. After three years, you can renew by submitting new evidence from your current work.

<!-- VERIFY: Confirm the renewal process and the badge metadata fields in the current ICoBC badge specification. -->

## Sources and further reading

Status as of November 2026; check before publishing.

Only official texts and framework owners are listed. Check the current version and publication status of each before you rely on it.

- 1EdTech Consortium: Open Badges 3.0 specification and Comprehensive Learner Record (CLR) 2.0 specification, with their conformance and certification information. Search the 1EdTech Consortium website for the current documents.
- World Wide Web Consortium (W3C): Verifiable Credentials Data Model 2.0, W3C Recommendation. Search the W3C website, technical reports section, for the current text and for related work on status lists and securing mechanisms.
- European Union: Regulation (EU) No 910/2014 as amended by Regulation (EU) 2024/1183 (eIDAS 2.0), establishing the European Digital Identity Framework. Search EUR-Lex for the consolidated text.
- European Commission: information on the European Digital Identity Wallet and its implementing acts and the architecture and reference framework. Search the European Commission website for current information.
- German federal government: official information on the planned German state wallet. Search the websites of the responsible federal ministries for current statements.
- ICoBC: ICoBC Credentialing Skills Framework (ICSF), skill STND "Standards and interoperability", and the ICoBC validation rules and candidate agreement. Available from ICoBC, info@icobc.net.

<!-- VERIFY: Confirm exact titles, versions, publication dates and access routes of every source above, and the current status of the German wallet plans, before publication. -->
