# Acadia (acadia)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Acadia is a Connected Worker Platform designed for employee productivity, acquired by Epicor. It delivers digital work instructions, knowledge management, skills matrices, quizzing, process evaluations, and team communications to frontline workers across manufacturing, transportation, healthcare, and retail banking. Acadia integrates with SSO, ERP, HRIS, LMS, IoT, and credentialing systems to enable enterprise-grade workforce development at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Connected Worker, Knowledge Management, Manufacturing, Skills Management, Training, Workforce Development

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Acadia Platform API
Acadia Platform API provides programmatic access to digital work instructions, employee skills matrices, quizzes, evaluations, and knowledge management features for workforce development integrations.

**Human URL:** [https://www.acadia-software.com/](https://www.acadia-software.com/)

#### Tags:

 - Connected Worker, Knowledge Management, Training, Workforce Development

#### Properties

- [Documentation](https://www.acadia-software.com/)
- [OpenAPI](openapi/acadia-platform.yaml)
- [JSONSchema](json-schema/acadia-work-instruction-schema.json)
- [Example](examples/acadia-work-instruction-example.json)

## Common Properties

- [Website](https://www.acadia-software.com/)
- [Portal](https://www.acadia-software.com/)
- [SignUp](https://www.acadia-software.com/)
- [Blog](https://www.acadia-software.com/blog/)
- [Documentation](https://www.acadia-software.com/features/)
- [SpectralRules](rules/acadia-spectral-rules.yml)
- [NaftikoCapability](capabilities/workforce-development.yaml)
- [Vocabulary](vocabulary/acadia-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Digital Work Instructions | Convert procedures to interactive task lists with videos, images, and dynamic content; assign via QR code, ERP integration, or manager distribution |
| Knowledge Management | Centralized document creation with automated translation, algorithmic search, and custom metadata filters |
| Skills Matrix | Track training and skill attainment, quantify individual and team performance, and identify capability gaps |
| Quizzing and Evaluations | Assess employee skill proficiency, measure comprehension, and perform objective skill evaluations during task execution |
| Team Communications | Auditable acknowledgements for process changes, group communications, and document change tracking |
| SSO Integration | Secure single sign-on via Active Directory and LDAP with role-based access control |
| ERP and HRIS Integration | Integration with ERP, HRIS, LMS, IoT, and credentialing systems for enterprise workforce management |
| SOC 2 Type II Certified | Enterprise-grade security with multi-layer encryption, intrusion prevention, and GDPR compliance |
| Career Path Visibility | Display advancement requirements and skill gap identification for employee career development |

## Use Cases

| Name | Description |
|------|-------------|
| Manufacturing Workforce Onboarding | Use digital work instructions to onboard new manufacturing employees quickly and ensure procedure compliance |
| Compliance Training | Assign and track completion of compliance-critical training and policy acknowledgements with full auditability |
| Frontline Skill Gap Analysis | Use the skills matrix to identify capability gaps in frontline teams and prioritize training investments |
| Process Improvement Feedback | Capture structured employee feedback on task-specific procedures to improve standard work over time |
| ERP-Triggered Work Instructions | Automatically assign work instructions based on ERP work orders for synchronized production operations |
| Multi-Language Training Deployment | Deploy synchronized multi-language training content to global workforces without manual translation delays |

## Integrations

| Name | Description |
|------|-------------|
| SAP | Integration with SAP ERP for work order-triggered digital work instruction assignment |
| Active Directory | Single sign-on via Microsoft Active Directory for enterprise identity management |
| LDAP | LDAP-based SSO for enterprise authentication systems |
| Learning Management Systems | Integration with third-party LMS platforms for training record synchronization |
| HRIS Systems | Integration with HR information systems for employee data synchronization |
| IoT Platforms | Integration with IoT systems for operational data correlation with training and task execution |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Acadia Platform](openapi/acadia-platform.yaml)

### JSON Schema

- [Acadia Employee List Schema](json-schema/acadia-employee-list-schema.json)
- [Acadia Employee Schema](json-schema/acadia-employee-schema.json)
- [Acadia Employee Skills Matrix Schema](json-schema/acadia-employee-skills-matrix-schema.json)
- [Acadia Quiz List Schema](json-schema/acadia-quiz-list-schema.json)
- [Acadia Quiz Schema](json-schema/acadia-quiz-schema.json)
- [Acadia Role List Schema](json-schema/acadia-role-list-schema.json)
- [Acadia Role Schema](json-schema/acadia-role-schema.json)
- [Acadia Skill Record Schema](json-schema/acadia-skill-record-schema.json)
- [Acadia Work Instruction List Schema](json-schema/acadia-work-instruction-list-schema.json)
- [Acadia Work Instruction Schema](json-schema/acadia-work-instruction-schema.json)
- [Acadia Work Instruction Step Schema](json-schema/acadia-work-instruction-step-schema.json)

### JSON Structure

- [Acadia Employee List Structure](json-structure/acadia-employee-list-structure.json)
- [Acadia Employee Skills Matrix Structure](json-structure/acadia-employee-skills-matrix-structure.json)
- [Acadia Employee Structure](json-structure/acadia-employee-structure.json)
- [Acadia Quiz List Structure](json-structure/acadia-quiz-list-structure.json)
- [Acadia Quiz Structure](json-structure/acadia-quiz-structure.json)
- [Acadia Role List Structure](json-structure/acadia-role-list-structure.json)
- [Acadia Role Structure](json-structure/acadia-role-structure.json)
- [Acadia Skill Record Structure](json-structure/acadia-skill-record-structure.json)
- [Acadia Work Instruction List Structure](json-structure/acadia-work-instruction-list-structure.json)
- [Acadia Work Instruction Step Structure](json-structure/acadia-work-instruction-step-structure.json)
- [Acadia Work Instruction Structure](json-structure/acadia-work-instruction-structure.json)

### JSON-LD

- [Acadia Platform Context](json-ld/acadia-platform-context.jsonld)

### Examples

- [Acadia Employee Example](examples/acadia-employee-example.json)
- [Acadia Employee List Example](examples/acadia-employee-list-example.json)
- [Acadia Employee Skills Matrix Example](examples/acadia-employee-skills-matrix-example.json)
- [Acadia Quiz Example](examples/acadia-quiz-example.json)
- [Acadia Quiz List Example](examples/acadia-quiz-list-example.json)
- [Acadia Role Example](examples/acadia-role-example.json)
- [Acadia Role List Example](examples/acadia-role-list-example.json)
- [Acadia Skill Record Example](examples/acadia-skill-record-example.json)
- [Acadia Work Instruction Example](examples/acadia-work-instruction-example.json)
- [Acadia Work Instruction List Example](examples/acadia-work-instruction-list-example.json)
- [Acadia Work Instruction Step Example](examples/acadia-work-instruction-step-example.json)

## Capabilities

Naftiko capabilities for Acadia Connected Worker Platform.

### Shared Per-API Definitions

- [Acadia Platform](capabilities/shared/acadia-platform.yaml)

### Workflow Capabilities

- [Workforce Development](capabilities/workforce-development.yaml)

## Vocabulary

- [Acadia Vocabulary](vocabulary/acadia-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 3 actions, 1 workflow, and 3 personas

## Rules

- [Acadia Spectral Rules](rules/acadia-spectral-rules.yml) — 25 rules enforcing Acadia API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
