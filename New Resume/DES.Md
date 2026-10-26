# Microsoft — Conversational AI Internship

## Accomplishment inventory, May–July 2021

**Role:** Software Engineer Intern.

Refreshed October 27, 2026 from the existing inventory of internship reviews and earlier career artifacts. The documented review span runs from May into July; month-level tenure is retained. This refresh did not independently re-read the underlying reviews.

The exact historical team-name expansion varies across sources. The generic company/role description above avoids asserting an unverified internal name.

## Knowledge-base onboarding and refresh

### Individual implementation

- Designed bot-based onboarding so administrators could add a question-answering knowledge base without writing application code.
- Implemented dialogs and integration with Cognitive Services APIs, QnA Maker and existing Cosmos DB storage.
- Built update/refresh flows to keep stored knowledge and service applications consistent.
- Investigated and corrected deserialization issues after dependency upgrades.

**Outcome:** administrator-driven onboarding and refresh through a conversational interface. This does not establish a universal ingestion-performance guarantee.

## Language understanding and intent routing

| Work | Supported status / outcome |
|---|---|
| Evaluated and implemented an offline language-recognizer path | Compared available recognizer behavior with legacy dispatch handling |
| Retained the compatible dispatch path for dynamic onboarding | Recognized that runtime utterance updates were required and not supported by the alternative in the needed way |
| Separated static and dynamic intent-label handling | Clarified intent routing between fixed handlers and changing knowledge bases |
| Proposed a split-dialog architecture | Proposal only; subsequent implementation is not established |

Do not claim that the newer recognizer replaced the existing dispatcher. No measured accuracy delta is established. A suggested custom algorithm is not proof that it was implemented.

## Enterprise workflow prototype

- Built conversational access-request and onboarding flows.
- Integrated enterprise APIs with Logic Apps, Power Automate, Teams, Outlook and SharePoint.
- Evaluated storage options for approval requests, including SharePoint lists and Cosmos DB.
- Demonstrated an end-to-end approval prototype.

**Status:** working prototype. It is not evidence of a completed production launch, achieved availability target or measured reduction in approval time.

## Modernization and engineering practice

- Upgraded bot dependencies and addressed follow-up integration issues.
- Evaluated Adaptive Dialogs, Composer and alternative intent-recognition components.
- Applied modular design, error handling and structured design-review feedback.
- Captured lessons in automated testing, API-authentication preparation, technical documentation and concise presentations.

Historical review praise for code quality does not establish complete testing or production readiness.

## Skills

C#, .NET Core, Microsoft Bot Framework, conversational AI, Cognitive Services, LUIS, QnA Maker, offline intent recognition, Cosmos DB, API integration, authentication/authorization concepts, Logic Apps, Power Automate, Teams, Outlook, SharePoint, dependency modernization and software design.

## Reuse boundaries

- Beginning-of-internship goals are not delivered accomplishments; do not claim target coverage or availability.
- Knowledge-base source records refer to utterances, not automatically to question-answer pairs.
- Keep the dispatcher compatibility decision and prototype status intact.
- Formal team naming and any quantitative performance claims require source verification.
- Prefer the grounded conversational-AI and integration responsibilities over unverified numerical impact.
