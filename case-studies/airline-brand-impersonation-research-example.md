# Airline Brand Impersonation Research – Practical Example

> **Project type:** Research, claim verification and risk assessment  
> **Topic:** Suspicious airline promotion and brand impersonation  
> **Brand used in the scenario:** LOT Polish Airlines  
> **Research cut-off date:** 29 July 2026  
> **Status:** Portfolio case study  
> **Note:** The suspicious promotion described below is fictional. It was created solely to demonstrate a research and fact-checking workflow. No real malicious domain or active campaign is reproduced.

## Project overview

This case study demonstrates how a suspicious airline promotion can be assessed using:

- official brand information,
- source hierarchy,
- claim-by-claim verification,
- domain and communication-channel checks,
- evidence-status classification,
- risk indicators,
- human editorial judgment.

The purpose is not to make a legal determination or identify a criminal.

The objective is to establish whether the promotion is supported by reliable evidence and whether a user should interact with it.

## Fictional scenario

A social media user sees a sponsored advertisement containing the LOT Polish Airlines name, logo and aircraft imagery.

The advertisement states:

> LOT is celebrating its anniversary. Complete a short survey and receive a flight ticket with a 90% discount. The offer is available today only.

The button leads to:

```text
lot-anniversary-tickets.example
```

The page asks the user to:

- answer five survey questions,
- provide their full name and email address,
- enter a booking number,
- log in to an airline account,
- enter card details,
- pay a PLN 9 processing fee,
- share the promotion with three friends.

After completing the form, the user is told that a LOT representative will contact them through Messenger.

The domain uses `.example`, a reserved placeholder used here to avoid reproducing an active or potentially dangerous address.

## Research objective

The objective is to assess whether the promotion can be treated as an authentic LOT campaign.

The research should answer:

1. Is the promotion hosted on an official LOT channel?
2. Does the described contact process match LOT’s published communication practices?
3. Are the promotion, discount and processing fee supported by official information?
4. Does the page request information that creates a security risk?
5. Which elements are verified facts, interpretations or unresolved claims?
6. What should the user do next?
7. Which evidence should be preserved and where should the incident be reported?

## Intended audience

This case study is relevant to:

- marketing and communication specialists,
- social media teams,
- content moderators,
- customer-service teams,
- brand-protection specialists,
- digital-security teams,
- Polish-language content evaluators,
- consumers assessing suspicious promotions.

## Scope

### Included

- public information published by LOT,
- official cybersecurity guidance,
- verification of domains and communication channels,
- analysis of promotional claims,
- identification of social-engineering indicators,
- incident-reporting guidance,
- editorial assessment of the evidence.

### Excluded

- technical malware analysis,
- access to private company systems,
- payment-provider investigation,
- law-enforcement attribution,
- identification of the person operating the page,
- legal classification of the incident,
- automated domain takedown.

## Source strategy

The research prioritizes:

### Tier 1 — Official and primary sources

- LOT cybersecurity information for passengers,
- LOT warnings about impersonation,
- official LOT website and communication channels,
- official government incident-reporting guidance,
- CERT Polska reporting procedures,
- ENISA threat-landscape publications.

### Tier 2 — Independent context

Reputable cybersecurity reporting may be used to explain patterns or broader context, but not to verify whether this specific promotion is authentic.

### Tier 3 — Discovery sources

The following may provide leads but are not sufficient evidence:

- social media comments,
- screenshots shared by users,
- search-result snippets,
- discussion forums,
- reposted warnings,
- AI-generated summaries,
- unsourced statements from influencers.

## Source set

| Source | Type | Purpose in the assessment | Evidence strength |
|---|---|---|---|
| LOT cybersecurity guidance for passengers | Official primary source | Confirm official website, contact channels and user-safety guidance | High |
| LOT warning about people impersonating the airline | Official primary source | Verify published warnings about false profiles, suspicious links and social-media contact | High |
| ENISA Threat Landscape 2025 | Official EU report | Provide broader context about phishing and social engineering | High for general context |
| Gov.pl incident-reporting guidance | Official government source | Confirm the appropriate reporting route in Poland | High |
| The fictional advertisement and landing page | Evidence under review | Identify the claims, requested data and visible risk signals | Unknown until verified |

## Claims extracted from the promotion

The promotion presents the following statements as facts:

1. The campaign is organized by LOT Polish Airlines.
2. The campaign celebrates a LOT anniversary.
3. Participants can receive a 90% discount on a flight ticket.
4. The offer is available for one day only.
5. Paying PLN 9 is required to receive the discount.
6. Providing booking, login and payment information is part of the official process.
7. A LOT representative will contact the participant through Messenger.
8. The use of the logo and aircraft imagery confirms that the advertisement is authentic.

Each claim must be assessed separately.

## Claim-evidence register

| ID | Claim | Evidence status | Source or evidence | Source type | Evidence strength | Assessment |
|---|---|---|---|---|---|---|
| C1 | The promotion is an official LOT campaign | Contradicted | The page is hosted outside the official `lot.com` domain | Official brand guidance and inspected scenario | High | The promotion cannot be treated as official based on the supplied link |
| C2 | The promotion celebrates a real LOT anniversary | Unverified | No approved campaign announcement or rules were supplied | No supporting source | Low | The anniversary statement may be used only as an emotional hook |
| C3 | Participants receive a 90% ticket discount | Unverified | No official terms, fare rules or LOT campaign page were provided | No supporting source | Low | The numerical discount requires direct confirmation |
| C4 | The offer ends today | Unverified | The claim appears only in the advertisement | Advertisement | Low | The deadline creates urgency but does not provide evidence |
| C5 | A PLN 9 processing fee is required | Unverified and high risk | No official payment rules or campaign terms were provided | Landing page under review | Low | Payment should not be made until the campaign is confirmed through LOT |
| C6 | Users must provide login and booking information | Contradicted by safety guidance | LOT advises users not to disclose login details and to protect booking information when identity is uncertain | Official brand guidance | High | The request is inconsistent with published safety advice |
| C7 | A LOT representative will contact the user through Messenger | Contradicted | LOT warns users about impersonation and states that it does not initiate passenger correspondence through social media channels | Official brand warning | High | The proposed contact method is a significant warning signal |
| C8 | Brand visuals prove authenticity | Unsupported | Scammers may reproduce logos, layouts, photos and profile names | Official warnings about lookalike pages and false profiles | High | Visual similarity is not evidence of ownership |
| C9 | High numbers of likes or comments prove that the offer is real | Unsupported | Engagement can be manipulated, automated or unrelated to authenticity | No reliable supporting evidence | Low | Social engagement should not be used as verification |
| C10 | The incident can be reported to CERT Polska | Supported | Official Polish guidance directs suspicious domains and phishing reports to CERT Polska | Government source | High | The user should preserve evidence and submit a report |

## Key verification findings

### 1. Domain verification

The landing page is not hosted on the official `lot.com` domain.

This is the strongest direct indicator in the assessment.

A page using a similar name, logo or visual identity should not be treated as official when its domain does not match the brand’s confirmed website.

### 2. Contact-channel verification

The promotion states that the participant will be contacted through Messenger.

This conflicts with LOT’s published warning about people impersonating the airline and its guidance concerning social-media correspondence.

A profile name or logo is not sufficient proof that the sender represents the airline.

### 3. Promotion verification

No official campaign page, rules, eligibility requirements or promotional terms were provided.

The following elements therefore remain unverified:

- the anniversary campaign,
- the 90% discount,
- the one-day deadline,
- the PLN 9 fee,
- the ticket-award process.

The absence of supporting evidence should not automatically be described as proof of fraud.

It does mean that the promotion must not be presented as authentic.

### 4. Data-request verification

The page asks for:

- personal data,
- booking information,
- account login details,
- card information,
- payment.

These requests significantly increase the potential impact of interacting with the page.

The user should not enter or submit the information before independently confirming the campaign through LOT’s official channels.

### 5. Visual-identity verification

The advertisement uses:

- the airline’s name,
- a logo,
- aircraft imagery,
- brand-style colours,
- a professional-looking landing page.

These elements may make the offer appear credible, but they do not establish ownership.

Visual identity can be copied without authorization.

## Warning-signal register

| Warning signal | Why it matters | Risk level |
|---|---|---|
| Domain does not match the official brand domain | The page cannot be linked directly to the verified organization | High |
| Large discount without official rules | The financial benefit is not supported by transparent terms | High |
| Immediate payment request | The page attempts to collect money before authenticity is confirmed | High |
| Login and card details requested | Compromise could affect accounts and financial information | High |
| Messenger contact promised | Conflicts with published brand communication guidance | High |
| “Today only” deadline | Creates pressure and reduces time for verification | Medium–high |
| Request to share with friends | May be used to expand distribution through trusted contacts | Medium |
| Logo and professional design | May create false authority without proving ownership | Medium |
| No named organizer or legal details | Makes accountability and verification difficult | High |
| No official campaign terms | Prevents the user from checking eligibility, payment and complaint rules | High |

## Risk assessment

### Overall classification

**High risk — likely brand impersonation or phishing attempt**

### Basis for the classification

The assessment is based on the combination of:

- a non-official domain,
- unsupported promotional claims,
- requests for sensitive information,
- a payment request,
- high-pressure language,
- social sharing,
- contact through a channel inconsistent with the airline’s published guidance.

No single visual indicator is used as proof.

The classification results from several independent warning signals combined with contradictions found in official brand guidance.

## Recommended user response

The user should:

1. Stop interacting with the advertisement and landing page.
2. Do not pay the PLN 9 fee.
3. Do not provide passwords, booking details or card information.
4. Do not download files, applications or certificates.
5. Do not contact the profile through Messenger.
6. Open the official LOT website independently rather than using the advertisement link.
7. Check current offers through verified LOT channels.
8. Contact LOT directly if the promotion remains unclear.
9. Preserve the advertisement, domain and relevant screenshots.
10. Report the suspicious page to CERT Polska.
11. Report the advertisement through the social media platform.
12. Contact the bank immediately if payment information was submitted.

## Evidence-preservation checklist

Before reporting the incident, preserve:

- a screenshot of the full advertisement,
- the profile or advertiser name,
- the date and time,
- the complete displayed domain,
- the landing-page screenshot,
- the wording of the promotional claim,
- the requested payment amount,
- the requested data fields,
- confirmation messages,
- email or Messenger messages,
- payment confirmation, when applicable,
- browser and device information, when relevant.

Sensitive information should be redacted before publishing screenshots in a public portfolio or social media post.

## Reporting path

### Report to the brand

Contact LOT through the cybersecurity or contact details published on its official website.

Do not use contact information displayed on the suspicious advertisement.

### Report to CERT Polska

Potential phishing, suspicious domains and impersonation attempts can be reported through the official CERT Polska incident-reporting service.

### Report to the platform

Use the platform’s reporting function to flag:

- impersonation,
- fraud,
- phishing,
- misleading advertising,
- unauthorized use of brand identity.

### Contact the bank or payment provider

When payment or card information has already been submitted, contact the financial institution as quickly as possible.

### Contact law enforcement

When money, personal data or account access has been lost, preserve the evidence and consider reporting the matter to the Police or prosecutor.

## Example customer-facing response

> This promotion cannot currently be verified as an official LOT campaign. The advertisement directs users to a domain outside `lot.com`, requests payment and sensitive information, and proposes contact through Messenger.
>
> Do not complete the form or submit payment. Verify the offer independently through LOT’s official website or contact centre. Preserve screenshots and report the suspicious page to the platform and CERT Polska.

## Editorial wording guidance

### Appropriate wording

- “The promotion could not be verified through official sources.”
- “The page contains several indicators associated with impersonation and phishing.”
- “Do not interact with the page until the offer is independently confirmed.”
- “The available evidence supports a high-risk classification.”
- “The domain does not match the official brand website.”

### Wording to avoid

- “This person is definitely a criminal.”
- “The company has confirmed that every similar advertisement is fraudulent.”
- “No official promotion ever requests payment.”
- “The page has stolen customer data.”
- “Everyone who clicked the page has lost money.”

These statements go beyond the available evidence.

## Facts, interpretations and unknowns

### Verified facts

- LOT publishes an official website and cybersecurity guidance.
- The fictional landing page does not use the official LOT domain.
- The promotion asks for personal, login, booking and payment information.
- The promotion proposes contact through Messenger.
- Official Polish guidance provides a reporting route through CERT Polska.

### Interpretations

- The deadline appears designed to create pressure.
- The request to share the campaign may support rapid distribution.
- The low processing fee may be intended to reduce the user’s hesitation.
- The copied visual identity may be intended to borrow trust from the airline.

These are plausible interpretations, not confirmed statements about the operator’s intentions.

### Unknowns

- who created the page,
- where the operator is located,
- whether submitted data is stored,
- how many users interacted with it,
- whether any payment was processed,
- whether malware is present,
- whether the advertiser controls other domains,
- whether law enforcement is already investigating.

## Source-quality assessment

| Source | Authority | Recency | Proximity to evidence | Independence | Relevance |
|---|---|---|---|---|---|
| LOT cybersecurity guidance | High | Current at research cut-off | Direct brand source | Brand-owned | Directly relevant |
| LOT impersonation warning | High | Current at research cut-off | Direct brand source | Brand-owned | Directly relevant |
| ENISA Threat Landscape 2025 | High | Recent | Official threat analysis | Independent EU agency | Relevant as general context |
| Gov.pl incident guidance | High | Current at research cut-off | Official reporting instructions | Government source | Directly relevant to reporting |
| Advertisement engagement and comments | Low | Current but unstable | Indirect | Unknown | Insufficient for authenticity |
| AI-generated assessment | Not evidence | Generated during analysis | Indirect | Model-dependent | Useful only as editorial support |

## Human editorial contribution

Human judgment was required to:

- divide the advertisement into verifiable claims,
- select official sources,
- distinguish contradiction from absence of evidence,
- avoid treating visual similarity as proof,
- avoid accusing an unidentified party of a crime,
- evaluate the combined warning signals,
- communicate uncertainty,
- formulate a proportionate user warning,
- identify appropriate reporting routes,
- remove unsafe or overly confident wording.

## How AI supported the process

AI can assist with:

- extracting claims from the advertisement,
- organizing a claim-evidence register,
- proposing source categories,
- summarizing long official documents,
- identifying missing information,
- comparing versions of statements,
- preparing a first draft of the user warning.

AI should not independently:

- decide that a person committed a crime,
- confirm the ownership of a domain without evidence,
- invent campaign terms,
- create unverified quotations,
- assume that a missing promotion page proves fraud,
- open or interact with a dangerous page on behalf of the user,
- replace brand, security-team or law-enforcement verification.

## Limitations

This case study is based on a fictional promotion.

It does not include:

- a live suspicious domain,
- domain-registration records,
- DNS analysis,
- hosting-provider information,
- advertising-account metadata,
- malware analysis,
- transaction records,
- private brand-security data,
- platform investigation results,
- law-enforcement findings.

The assessment demonstrates an editorial and research workflow rather than a forensic cybersecurity investigation.

## Key lessons

1. A copied logo does not prove that a page is official.
2. The domain is one of the first elements that should be verified.
3. Every promotional statement should be separated into an individual claim.
4. Absence of evidence is not always proof of fraud, but it prevents confirmation.
5. Requests for payment and sensitive data increase the potential impact.
6. Urgency and social sharing may reduce the time available for careful verification.
7. Official brand guidance should be checked before relying on social media comments.
8. AI can organize the evidence but cannot serve as the source of truth.
9. A public warning should remain accurate, proportionate and legally cautious.
10. Human review is required before publication or escalation.

## Conclusion

The fictional promotion should not be treated as an authentic LOT campaign.

The strongest evidence is:

- the non-official domain,
- the contradiction with published communication guidance,
- the unsupported discount and fee,
- the request for login, booking and payment information,
- the combination of urgency, payment and brand impersonation indicators.

The recommended workflow is:

**Capture evidence → Extract claims → Verify official channels → Assess sources → Register evidence → Classify risk → Warn the user → Report the incident → Preserve human oversight**

## Status

Version 1.0 of the airline brand impersonation research case study is complete.

Recommended next steps:

- add the case study to the repository README,
- test the research prompt on a second fictional promotion,
- compare how ChatGPT and Claude classify the evidence,
- document model errors and unsupported assumptions,
- create a simplified consumer-facing checklist.
