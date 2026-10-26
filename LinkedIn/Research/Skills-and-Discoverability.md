# LinkedIn Skills and Discoverability Research Guide

Public-safe guidance for selecting, ordering, and supporting LinkedIn skills. Candidate skills in this guide are examples, not claims of proficiency.

## Evidence labels

- **Official fact:** Current LinkedIn Help or product documentation.
- **Dated official evidence:** An older LinkedIn article or Recruiter document that may no longer describe the current UI.
- **Synthesis:** Practical guidance inferred from the evidence; not a documented ranking rule.

Sources were accessed on **2026-10-27**.

## Current official facts

- A profile can contain up to 100 skills: [Add and remove skills](https://www.linkedin.com/help/linkedin/answer/a549047).
- LinkedIn asks members to select where each skill was used. Skills associated with Experience roles do not count toward the 100-skill limit: [Skill endorsements](https://www.linkedin.com/help/linkedin/answer/a565106).
- Skills can be reordered. Removing and re-adding a skill permanently removes its endorsements: [Skill endorsements](https://www.linkedin.com/help/linkedin/answer/a565106).
- First-degree connections can endorse skills. LinkedIn says endorsements reinforce weighting and may improve discovery, but it publishes no formula or magnitude.
- Skill Assessments are retired: [LinkedIn Skill Assessments](https://www.linkedin.com/help/linkedin/answer/a507663).
- LinkedIn hiring AI can use experience, skills, summary, education, certifications, publications, and other profile data to compare a member with job qualifications. Recruiters remain responsible for verification: [How LinkedIn uses AI Agents](https://www.linkedin.com/help/linkedin/answer/a7437598).

## Dated official evidence

- A 2023 LinkedIn product post says members can tag up to five Top Skills in About and associate skills with jobs, projects, education, and credentials: [New Profile tools](https://www.linkedin.com/pulse/new-profile-tools-spotlight-your-top-skills-projects-rohan-rajiv-2e).
- LinkedIn's Skills Graph maps aliases and related skills and can infer skills from profile text: [Building LinkedIn's Skills Graph](https://www.linkedin.com/blog/engineering/skills-graph/building-linkedin-s-skills-graph-to-power-a-skills-first-world).
- A 2019 Recruiter guide says the Skills filter considers explicit skills and relevant profile keywords, while the Keywords filter searches the full profile: [How Search Filters Work in Recruiter](https://delivery-p143253-e1476319.adobeaemcloud.com/adobe/assets/urn:aaid:aem:a32d752a-1fa9-4861-a56c-1a722c1793c9/original/as/original.pdf).

These older sources explain concepts, not guaranteed current behavior.

## UI limits and freshness

| Item | Baseline on 2026-10-27 | Confidence |
|---|---|---|
| Skills section | Up to 100 skills | High |
| Experience-associated skills | Excluded from the 100-skill limit | High |
| Skills ordering | Reordering supported | High |
| About Top Skills | Up to 5 | Medium; based on a 2023 product post |
| Skill Assessments | Retired | High |
| Per-position skill cap | Not documented | Unknown |
| Free-text skills | Not documented | Unknown |

**Recheck counter: 0.** This is the baseline captured on 2026-10-27. Increment the counter and replace the date after checking the live editor and current Help pages.

Recheck the exact typeahead labels before publication, especially for newer concepts such as Model Context Protocol, agentic AI, RAG, and agent evaluation.

## Evidence-first selection

Include a skill only when all of these are true:

1. It was used hands-on in production or a substantial project.
2. Its trade-offs and failure modes can be defended in an interview.
3. It can be linked to a real role, project, education entry, or credential.
4. The linked entry contains a public-safe example of the skill in use.
5. It is relevant to target roles.

Promote a skill to the top group only when it also represents recent, sustained work and strong evidence.

**Synthesis:** A focused list is more useful than filling all 100 slots. LinkedIn documents a maximum, not an optimal count.

## Organizing an engineering skill set

Use only skills supported by evidence.

### Backend and distributed systems

- Distributed Systems
- C# or another primary production language
- .NET, when it adds information beyond the language
- Python, when used for shipped services or tooling
- API Design or RESTful APIs
- System Design
- Back-End Development or Microservices

### Cloud, reliability, and security

- Microsoft Azure
- Kubernetes or Azure Kubernetes Service
- Observability
- Site Reliability Engineering or Incident Management
- Authentication and Authorization
- OAuth, OpenID Connect, or Microsoft Entra ID

### Agentic AI platform engineering

- AI Agents or agent orchestration
- LLM application engineering
- Model Context Protocol
- Agent or LLM evaluation
- Retrieval-augmented generation
- Agent security and guardrails

Do not treat these lists as recommendations to claim every term. Select the standardized LinkedIn label that best matches real work, and avoid synonyms that describe the same capability.

## Example Top Skills orientations

These are templates, not personal recommendations.

| Orientation | Example order |
|---|---|
| Backend and cloud | Primary language; Distributed Systems; API Design; Microsoft Azure; Kubernetes |
| Reliability | Distributed Systems; Primary language/framework; Site Reliability Engineering; Observability; Microsoft Azure |
| Hybrid platform | Distributed Systems; AI Agents; Primary language; API Design; Microsoft Azure |
| Agent tool integration | AI Agents; Model Context Protocol or API Design; Distributed Systems; Primary language; Authentication and Authorization |
| Agent quality | AI Agents; Agent Evaluation; Observability; Distributed Systems; Retrieval |

**Synthesis:** Keep durable engineering foundations visible even in an agent-focused profile. Platform-oriented agent roles still depend on APIs, distributed systems, reliability, security, and observability.

## Linking skills to evidence

- Use the "where you used this skill" checkboxes for every accurate role or project.
- Add one public-safe Experience or Project sentence that demonstrates each top skill.
- Use Projects for substantial independent or open-source work, without implying production use.
- Keep the same core terminology across Skills, About, and Experience, but do not repeat phrases mechanically.
- Preserve endorsed skills by reordering rather than deleting and re-adding them.
- Use certifications only when earned and relevant.

## What to leave out

- Skills learned only through tutorials.
- Internal codenames or confidential technologies.
- Legacy skills that no longer represent the work sought.
- Near-duplicate labels such as multiple versions of "REST API."
- Generic traits as top technical skills.
- Machine-learning training frameworks or data-science labels without real evidence.
- Skill Assessment badges, because the feature is retired.
- Any skill that cannot be defended in an interview.

## Discoverability: what is known

LinkedIn confirms that:

- Explicit skills and profile context are used in matching and recruiter workflows.
- The Skills Graph recognizes aliases and relationships between concepts.
- Hiring AI can examine multiple profile sections, not only the Skills list.
- Endorsements have some stated weighting, but the effect is not quantified.

Therefore, a skill should be both selected in Skills and demonstrated in Experience or Projects.

## Discoverability: what is not known

LinkedIn does not publish:

- Search or recommendation ranking formulas.
- Weights for skills, endorsements, headline, About, or recency.
- An optimal number of skills.
- A guaranteed benefit from frequent edits.
- A guarantee that an exact keyword produces a ranking position.
- A current public rule for per-position skill limits.

Do not publish "ATS score," guaranteed ranking, or endorsement-count claims.

## Privacy and accuracy

- Only connect a skill to public-safe evidence.
- Do not reveal internal architecture, incidents, security controls, customer names, unreleased products, or private metrics.
- Do not imply production depth for experiments or coursework.
- Distinguish application/platform engineering from model research or training.
- Treat generated suggestions and job-match summaries as aids, not proof of qualification.
- The recruiter is responsible for verification, but the member remains responsible for a truthful profile: [User Agreement](https://www.linkedin.com/legal/user-agreement).

## Maintenance checklist

- Confirm the 100-skill limit in current Help or the live editor.
- Confirm whether About still permits five Top Skills.
- Check the exact available labels for newer technologies.
- Confirm where-used associations for every top skill.
- Verify that each top skill has public-safe supporting evidence.
- Reorder instead of deleting endorsed skills.
- Review Search Appearances and job-match feedback without assuming causation.

## Supporting technical references

- [What is the Model Context Protocol?](https://modelcontextprotocol.io/docs/getting-started/intro)
- [MCP Authorization](https://modelcontextprotocol.io/specification/latest/basic/authorization)

Protocol documentation establishes what a technology is. It does not establish that a member has the skill or that LinkedIn recognizes the exact label.
