# MUNSHEE.PK
## Master Product Context, Business Vision, Feature Specification and Engineering Operating Instructions

**Document purpose:** Establish a shared understanding of the Munshee product, its business purpose, user experience, features, architecture, business rules, brand identity, development constraints, and long-term direction.

**Primary audience:** Kilo Code and any AI agent, developer, designer, or technical collaborator working on Munshee.

**Product:** Munshee.pk  
**Category:** AI Business Operating System (BOS)  
**Initial market:** Pakistan  
**Long-term ambition:** A globally competitive business operating platform.

---

# PART 1 — WHAT MUNSHEE IS

## 1.1 Product definition

Munshee.pk is a Pakistan-first AI Business Operating System designed to help online sellers and small businesses organize their business knowledge, understand their operations, and use AI to perform useful business work.

Munshee is not intended to be just another chatbot, dashboard, ecommerce storefront, or collection of disconnected AI tools.

It is intended to become a coherent business workspace in which a merchant can bring together information about their business, confirm what is accurate, ask questions about it, use AI-assisted capabilities, review proposed actions, and understand what is happening.

The central product idea is:

**Turn scattered business information into organized, usable business knowledge—and make that knowledge useful for everyday business operations.**

The product should make business management easier without removing the merchant's understanding or control.

Munshee should progressively help merchants move from fragmented information and repetitive manual work toward a more organized, intelligent, measurable way of operating.

## 1.2 The problem Munshee is designed to address

Many small businesses manage their operations through a mixture of disconnected tools and informal processes.

Depending on the business, information may be spread across:

- WhatsApp conversations
- Instagram messages
- Facebook interactions
- TikTok activity
- Websites and online stores
- Product photographs
- Receipts and business documents
- Orders and customer enquiries
- Spreadsheets
- Paper ledgers
- Personal notes
- Individual employees' knowledge

This creates several potential problems:

1. Business information is scattered.
2. The merchant must repeatedly search for information.
3. Important details may be forgotten or recorded inconsistently.
4. Repetitive work consumes time.
5. It can be difficult to understand what is happening across different business activities.
6. Business knowledge may remain trapped in individual conversations or documents.
7. Decisions may be made without a clear, organized view of the available information.
8. Business owners may struggle to introduce automation without losing control.

These are the problems Munshee's product strategy should address.

Do not assume every merchant experiences every problem. The product must accommodate different business sizes, workflows, levels of technical knowledge, and operational needs.

## 1.3 The Munshee promise

Munshee should help a business owner answer questions such as:

- What information does my business already know?
- Where did that information come from?
- Which information has been confirmed?
- What do I need to review?
- Can I ask questions about my business?
- What work can AI help me perform?
- What action is being proposed?
- What has actually happened?
- What needs my attention?
- What can I learn from my available business information?

The experience should progressively make these questions easier to answer.

Do not promise perfect automation, guaranteed growth, or capabilities that have not been implemented and verified.

## 1.4 The core operating loop

Munshee's defining product model is:

# EXTRACT → CONFIRM → LEARN → MEASURE

This model must influence the architecture, interface, content, and future product decisions.

### Stage 1: EXTRACT

Collect or receive available business information from supported sources.

Depending on implemented integrations, this may include text, structured records, documents, images, and other business inputs.

The system attempts to turn useful information into structured business facts.

Examples of possible facts include:

- Business name
- Product information
- Product prices
- Business hours
- Delivery policies
- Return policies
- Frequently asked questions
- Business contact information
- Operational preferences

These are examples, not an assumption that every fact type or input source is already implemented.

The system should retain appropriate source information and communicate uncertainty where possible.

### Stage 2: CONFIRM

Allow the merchant to review extracted information before it is treated as trusted business knowledge.

The merchant should be able to inspect, correct, approve, reject, or otherwise resolve information according to the implemented workflow.

Important principles:

- Extracted information is not automatically equivalent to verified information.
- Conflicting facts must not be silently merged into a false certainty.
- Uncertain information should not be presented as confirmed.
- The user should understand what requires attention.
- Confirmation should be straightforward and understandable.
- The system should preserve provenance and relevant timestamps where supported.

### Stage 3: LEARN

Make confirmed business information useful.

Potential applications include:

- Asking questions about the business
- Finding relevant business facts
- Receiving answers grounded in available information
- Understanding business policies
- Getting help with supported business tasks
- Using confirmed information as context for supported AI operations

The assistant must distinguish known facts from assumptions and unavailable information.

It must not invent a business policy or claim that a task was completed when it was not.

### Stage 4: MEASURE

Help the merchant understand product usage and business operations through accurate, available information.

Potential areas include:

- AI usage and credit consumption
- Activity history
- Pending reviews
- Completed actions
- Operational summaries
- Available business analytics
- Trends and performance indicators where reliable data exists

Never fabricate statistics to make a dashboard look complete.

If there is insufficient data, provide a meaningful empty state explaining what is needed to produce useful insights.

## 1.5 Product philosophy

Munshee should be:

- Intelligent without pretending to know everything
- Automated without removing human control
- Powerful without overwhelming beginners
- Premium without becoming visually complicated
- Data-driven without inventing data
- Helpful without constantly interrupting the user
- Secure by design
- Understandable to nontechnical business owners
- Flexible enough to support different kinds of merchants

The product should feel like a reliable operational partner, not an unpredictable black box.

---

# PART 2 — TARGET USERS AND MARKET

## 2.1 Initial target audience

The initial audience is Pakistani merchants and small-business owners, especially people who already conduct business through digital channels.

Priority audiences include:

### A. Social commerce sellers

Businesses that receive enquiries and orders through social media and messaging platforms.

Their needs may include organizing product information, responding to repeated questions, understanding customer enquiries, and managing business knowledge.

### B. Small ecommerce businesses

Businesses operating websites, online stores, or a combination of digital channels.

Their needs may include consistent product information, organized policies, better operational visibility, and supported AI-assisted workflows.

### C. Traditional businesses moving toward digital operations

Shopkeepers, retailers, wholesalers, and family-run businesses that may still rely on paper records and informal processes.

They need a straightforward interface that does not assume advanced technical knowledge.

### D. Growing merchants

Businesses that have outgrown informal record-keeping and need better visibility, repeatable processes, and potentially more sophisticated automation.

### E. Businesses working with external professionals

Merchants may eventually need help from specialists who can assist with business operations, technology, marketing, or other supported services.

Munshee's intended scope includes a professional marketplace or expert ecosystem, but the exact operational capabilities and current implementation must be verified before being advertised.

## 2.2 Initial geographic and linguistic focus

Pakistan is the initial market.

The product should support the language and operational realities of Pakistani businesses.

The intended languages are:

- English
- Urdu
- Roman Urdu

Language support must be genuine.

Do not merely translate the homepage while leaving the application, error messages, forms, or navigation untranslated.

The application must handle right-to-left layouts correctly wherever Urdu is supported.

## 2.3 Long-term audience

The ambition is international expansion.

Do not build the initial product around assumptions that prevent future localization, additional integrations, new merchant categories, or scalable operational architecture.

However, do not prematurely implement every future requirement.

Build a sound foundation and prioritize real user needs.

---

# PART 3 — PRODUCT SCOPE AND FEATURE MAP

## 3.1 Important feature-status rule

Kilo must distinguish four categories:

1. **Established product requirement:** A capability or business rule that belongs to the intended product.
2. **Existing implementation:** A capability that is demonstrably present in the current codebase.
3. **Planned capability:** A desired future feature that may not be implemented yet.
4. **Unverified capability:** Something whose status is unknown until inspected and tested.

Never treat these categories as interchangeable.

Before changing a feature, inspect its route, component, data model, service calls, authorization rules, and tests.

Do not describe a feature as working simply because its page exists.

## 3.2 Public website

The public website must explain Munshee clearly and help prospective merchants understand whether it is useful for them.

The established public-facing scope includes the following areas.

### Homepage

Purpose:

- Explain what Munshee is.
- Establish trust and credibility.
- Identify the problem it solves.
- Introduce the core workflow.
- Help visitors understand its relevance to their business.
- Guide users toward appropriate next steps.

Potential content areas, subject to the approved design:

- Hero section
- Product explanation
- Feature overview
- How it works
- Relevant merchant use cases
- Product visuals
- Pricing
- Trust and credibility information
- Frequently asked questions
- Calls to action

Do not add every section automatically.

Use the approved reference design and the actual product story to determine the appropriate composition.

### Features page

Explain the real product capabilities in understandable language.

Feature descriptions must correspond to implemented capabilities or be explicitly labelled as planned.

### Pricing page

Show the established pricing plans accurately.

Do not change prices, credit allowances, plan names, or billing assumptions without explicit approval.

### About page

Explain Munshee's purpose, audience, and approach.

Do not invent a company history, team size, funding, customer numbers, or achievements.

### Authentication entry points

Public pages may provide sign-in and registration entry points.

Verify that they connect to the real authentication flow.

Do not use fake authentication interactions or simulate successful registration.

## 3.3 Merchant application

The merchant application is the operational workspace where the product's value must become real.

Its existing route and component structure must be inspected before making changes.

The established merchant scope includes the following areas.

### A. Merchant dashboard

Purpose:

Provide an understandable overview of the merchant's business workspace and what requires attention.

Depending on available real data, this may include:

- Business overview
- Pending reviews
- Recent activity
- AI usage
- Relevant business summaries
- Important actions
- Entry points into major workflows

Requirements:

- Prioritize actionable information.
- Avoid unnecessary charts.
- Show accurate values.
- Distinguish zero values from missing data.
- Explain empty states.
- Make important next steps obvious.
- Do not fabricate activity or business performance.

### B. Business Sources

Purpose:

Help merchants manage the sources of their business information.

Potential sources include supported website information, documents, text, images, and authorized external business channels.

The actual supported source types must be verified against the codebase.

The interface should explain:

- Which sources are connected or available
- Which sources require configuration
- What information has been received
- Whether a source needs attention
- Whether an operation is still processing
- Whether a connection has failed

Never show a source as connected if the integration has not actually succeeded.

Never invent external account data.

### C. Business Brain / Facts

Purpose:

Represent the organized business knowledge used by Munshee.

This is a core product concept.

Business facts should be structured and understandable rather than buried in unorganized conversation history.

Where supported by the implementation, a fact may have:

- A type or category
- A value
- A source
- A verification state
- A timestamp
- A confidence indicator
- A business association
- A relevant review or correction history

Inspect the real schema before assuming every field exists.

The interface should help merchants:

- Find facts
- Understand what they mean
- Review uncertain information
- Correct incorrect information
- Confirm information
- Identify conflicts
- Understand where information originated

Do not silently convert an unverified fact into a verified one.

Do not confuse source confidence with merchant confirmation.

### D. Review workflow

Purpose:

Give the merchant control over information that requires review.

A good review experience should answer:

- What is being reviewed?
- Where did it come from?
- Why does it need attention?
- What happens if I approve it?
- Can I correct it?
- What happens if I reject it?

Keep the review process focused.

Avoid forcing users through unnecessary steps.

Do not claim a review has been saved unless the actual operation succeeds.

### E. AI conversations / Ask Munshee

Purpose:

Let merchants ask questions and receive useful assistance grounded in available business context.

The intended experience should support natural interaction while making the source and limits of answers understandable.

The assistant should:

- Understand the merchant's question.
- Use appropriate available context.
- Answer in the user's language where supported.
- Avoid inventing business facts.
- Communicate uncertainty.
- Distinguish verified information from assumptions.
- Provide helpful next steps when appropriate.

The conversation interface should be easy to read and operate.

Do not assume every conversation can trigger external actions.

Do not expose confidential business data to an unauthorized user or tenant.

### F. AI actions, review, and autonomy

Munshee's intended direction includes AI-assisted work and a controlled autonomy model.

This must be implemented with explicit boundaries.

Different actions may require different permission levels:

- Informational responses
- Suggested actions
- Actions requiring merchant approval
- Pre-authorized actions with appropriate safeguards
- Actions that are not permitted

The actual authorization model must be derived from existing product rules and backend enforcement.

The interface should clearly communicate:

- What the AI proposes to do
- What information it will use
- What the consequences may be
- Whether user approval is required
- Whether the action is pending
- Whether it succeeded or failed
- What can be undone, if anything

Do not invent an autonomy setting or imply that a capability exists without verification.

Never let a visual toggle serve as the only authorization mechanism for a sensitive operation.

Backend enforcement is required for real permissions.

### G. Activity and usage

Purpose:

Help merchants understand what has happened in their workspace and how they are using the product.

Potential information includes:

- Recent activities
- AI operations
- Action outcomes
- Credit consumption
- Pending work
- Errors requiring attention

Only display information supported by real data.

Ensure activity descriptions are understandable to nontechnical users.

### H. Billing and subscriptions

Purpose:

Help merchants understand their plan, credits, and subscription-related information.

The existing implementation must be inspected to determine which operations are supported.

The interface must not fabricate payment success, subscription activation, or credit balances.

### I. Settings

Purpose:

Allow merchants to manage supported account and workspace preferences.

Potential areas include:

- Profile
- Business details
- Language
- Preferences
- Supported integrations
- Other existing settings

Implement only settings supported by the product.

Changes must persist correctly and communicate success or failure.

### J. Merchant onboarding

Purpose:

Help a new merchant understand the product and establish the information needed to begin using it.

The intended onboarding experience should be clear and progressive.

Possible steps include:

1. Explain what Munshee does.
2. Collect necessary business information.
3. Configure supported sources.
4. Establish initial business facts.
5. Review and confirm information.
6. Guide the merchant toward their first useful result.

This is a desired workflow model, not a claim that every step currently exists.

Inspect the current onboarding flow before redesigning it.

Avoid long, unnecessary questionnaires.

Ask for information when it is needed, explain why it matters, and preserve progress where supported.

## 3.4 Professional marketplace and expert ecosystem

Munshee's broader scope includes professionals whom merchants can discover, hire, or work with through the platform.

These professionals are external experts serving merchants. They are not automatically Munshee employees.

Potential future categories may include specialists who help merchants improve their business operations, technology, marketing, or other relevant activities.

Before implementing or advertising marketplace functionality, establish:

- Whether professional profiles exist
- Whether discovery and search work
- Whether hiring or engagement workflows exist
- Whether communication is supported
- Whether payments or commissions exist
- Whether verification or reviews exist
- What protections are provided to merchants

Do not fabricate verified professionals, ratings, testimonials, completed jobs, or payment features.

The marketplace should be developed according to a separately validated feature specification.

## 3.5 Owner and administrative oversight

The product direction includes a separate administrative environment for platform oversight.

The owner should ultimately be able to understand relevant operational information, including usage and AI-related activity, through authorized administrative tooling.

The administrative application is a separate workstream.

For ordinary merchant UI/UX tasks:

- Do not redesign or modify the admin application.
- Do not merge admin routes into the merchant application.
- Do not expose administrative data in merchant-facing interfaces.
- Do not treat hidden frontend routes as access control.
- Do not change administrative permissions without explicit authorization.

Administrative monitoring must respect tenant boundaries, access permissions, privacy, and data minimization.

---

# PART 4 — BUSINESS MODEL AND LOCKED PRICING

## 4.1 Canonical pricing

The established plan structure is:

| Plan | Monthly price | Monthly credits |
|---|---:|---:|
| Free | ₨0 | 150 |
| Starter | ₨10,000 | 5,000 |
| Business | ₨25,000 | 15,000 |
| Pro | ₨50,000 | 40,000 |
| Business OS | ₨100,000+ | 100,000+ |

These values are locked product decisions.

Do not change them during redesigns, copy editing, component refactoring, or pricing-page work.

Do not introduce old or inconsistent prices.

Do not invent discounts, trial periods, extra allowances, renewal conditions, or payment terms.

If the implementation contains conflicting plan information, identify the source of truth and report the discrepancy rather than silently changing business policy.

## 4.2 Credit system

Credits represent an established element of the product's commercial model.

Inspect the existing implementation to determine:

- How credits are consumed
- Which operations consume credits
- How balances are calculated
- How plan allowances are applied
- How usage is recorded
- How failures and refunds are handled
- What users see when credits are insufficient

Do not invent credit-consumption rules.

Never modify credit accounting or billing logic as part of a visual-only task.

The UI must reflect the authoritative backend balance rather than a fabricated local value.

## 4.3 Business goals

The product's stated ambitions include reaching approximately 100 users and 20 professionals hired by merchants.

Treat these as goals, not achieved results.

Do not display them as actual traction, testimonials, or statistics.

---

# PART 5 — BRAND IDENTITY AND DESIGN DIRECTION

## 5.1 Brand spelling

Use the brand name:

**Munshee**

Use `Munshee.pk` where the domain or complete product identity is appropriate.

Do not randomly alternate between Munshee, Munshe, Munshi, or other spellings.

## 5.2 Visual identity

The established design direction is premium, minimal, warm, accessible, and business-focused.

Preferred visual elements include:

- Warm cream backgrounds
- Espresso-brown typography
- Restrained caramel or muted-gold accents
- Strong, readable typography
- Deliberate whitespace
- High-quality imagery
- Consistent component design
- Subtle, meaningful interaction feedback

The approved Readdy reference should guide the specific composition and visual details.

Do not replace the reference with a generic SaaS layout.

## 5.3 Typography

Use typography to create a clear hierarchy.

The design may combine a distinctive serif for major editorial headings with a highly readable sans-serif for body text and controls, where that matches the approved reference.

Prioritize:

- Readability
- Appropriate line length
- Consistent weights
- Balanced line height
- Clear heading hierarchy
- Strong contrast
- Appropriate mobile scaling

Avoid oversized headings that break layouts or consume excessive space.

Check Urdu typography and rendering separately.

## 5.4 Photography

Munshee's photography should feel authentic and relevant to Pakistani business owners.

Preferred direction:

- Documentary-style commercial photography
- Natural light
- Realistic environments
- Natural human expressions
- Realistic skin texture
- Believable proportions
- Restrained warm color grading
- Genuine small-business contexts

Avoid generic stock-photo gloss, exaggerated expressions, artificial-looking people, and repetitive imagery.

Generated people must not be represented as actual employees or customers.

## 5.5 Logo

Use the actual approved logo asset.

Check:

- Transparent padding
- Aspect ratio
- Display dimensions
- Wordmark proportions
- Icon-to-wordmark alignment
- Background compatibility
- Header and footer consistency
- Mobile behavior

Do not distort the logo or substitute an unrelated icon.

Do not enlarge an image blindly without inspecting its actual contents.

## 5.6 Motion and interaction

Use motion to make the product feel responsive and polished.

Appropriate examples include:

- Subtle entrance transitions
- Selected scroll reveals
- Button hover and press feedback
- Smooth menu transitions
- Clear loading states
- Gentle transitions between interface states
- Carefully designed workflow explanations

Avoid:

- Excessive motion
- Long entrance sequences
- Repetitive bouncing
- Unnecessary parallax
- Decorative glowing orbs
- Random floating objects
- Excessive gradients
- Glassmorphism for its own sake
- Animations that delay essential interaction

Respect reduced-motion preferences.

The experience should feel premium and alive without becoming distracting.

---

# PART 6 — IMAGE AND FEATURE-VISUAL STRATEGY

## 6.1 Three categories of visuals

Keep these categories distinct.

### Category A: Realistic business photography

Purpose: establish relevance, communicate context, and help merchants recognize their own world.

Examples include Pakistani shopkeepers, entrepreneurs, business records, and fulfilment environments.

### Category B: Explanatory illustrations

Purpose: explain how a product capability or workflow works.

Examples include information extraction, fact confirmation, AI assistance, and business insights.

### Category C: Actual product screenshots

Purpose: demonstrate the real Munshee interface.

Use screenshots from the actual application.

Never present a generated dashboard as the real product.

## 6.2 Existing image inventory

The user has shown a folder containing these assets:

- `Abdur-Rehman.jpg`
- `landing-ur.png`
- `munshee-image1.jpg`
- `munshee-image2.jpg`
- `munshee-image3.jpg`
- `munshee-image4.jpg`
- `munshee-image5.jpg`
- `munshee-image6.jpg`
- `munshee-image7.jpg`
- `munshee-image8.jpg`
- `munshee-image9.jpg`
- `munshee-image10.jpg`
- `munshee-image11.jpg`
- `munshee-image12.jpg`
- `munshee-image13.jpg`
- `munshee-logo.png`

Verify the files and their contents before using them.

Do not assume their actual content based on filenames.

Do not use `Abdur-Rehman.jpg` publicly until its intended purpose and permission are clear.

Do not place `landing-ur.png` in an unrelated section merely because it exists.

## 6.3 Asset-to-section mapping

For each image, record:

- What it depicts
- Its intended purpose
- Which page and section should use it
- Whether its composition suits the layout
- Its aspect ratio
- Its focal point
- Whether it needs replacement
- Whether it is a real screenshot or an illustrative asset

Use appropriate image positioning and responsive behavior.

Do not reuse the same image in unrelated sections simply to fill empty space.

## 6.4 Feature storytelling

The four-step workflow should be visually understandable.

### Extract

Show information coming from supported business inputs and becoming organized facts.

### Confirm

Show the merchant reviewing information and retaining control.

### Learn

Show the assistant using available business context to help answer a question.

### Measure

Show meaningful, accurate summaries of available information.

Do not imply that unsupported integrations or capabilities already exist.

---

# PART 7 — TECHNICAL ARCHITECTURE

## 7.1 Known architecture

The previously documented architecture includes:

### Frontend

- React 19
- TypeScript
- Vite
- React Router 7
- Tailwind CSS 4
- TanStack Query

### Backend and data

- Supabase Postgres
- Supabase Auth
- Supabase Storage
- Supabase Edge Functions using Deno

### AI

Previously documented model configuration:

- OpenRouter with Llama 3.3 70B for text
- Qwen 2.5-VL 72B for vision

Verify the current implementation, model identifiers, routing, and configuration before relying on these details.

Do not expose API keys or other secrets.

### Hosting

Previously documented hosting direction:

- Cloudflare Pages

Verify current deployment configuration before making changes.

### Localization

The project has previously been reported to contain numerous localization namespaces and locale files.

Inspect the current files rather than relying on historical counts.

Check English, Urdu, and Roman Urdu coverage.

## 7.2 Architecture principles

- Preserve existing architecture unless a change is justified.
- Reuse existing components when appropriate.
- Avoid duplicate data-fetching logic.
- Keep business logic out of purely presentational components where practical.
- Use established design tokens.
- Maintain proper tenant isolation.
- Respect server-side authorization.
- Keep secrets out of client bundles and logs.
- Preserve reliable loading, error, and empty states.
- Maintain compatibility with existing routes and tests.

Do not add a dependency when the existing stack already provides a suitable solution.

## 7.3 Database and tenant integrity

Munshee is a multi-tenant product.

Data belonging to one merchant must not become accessible to another merchant without explicit authorization.

Every relevant data operation must respect the established ownership model and backend policies.

Never rely solely on client-provided tenant identifiers or frontend route guards.

Inspect the real authorization model before modifying data access.

Database migrations are sensitive operations and are outside the scope of an ordinary visual redesign.

---

# PART 8 — SECURITY, PRIVACY, AND TRUST

## 8.1 Trust is a product feature

Business owners may provide commercially sensitive information.

The application must treat that information responsibly.

Do not expose:

- Customer information to unauthorized users
- Business records across tenant boundaries
- Access tokens
- API credentials
- Private documents
- Administrative data
- Internal secrets in logs or browser-visible code

## 8.2 AI accuracy

The assistant should distinguish:

- Confirmed facts
- Unconfirmed extracted information
- Inferences
- Unknown information
- Failed or incomplete operations

Do not present a guess as a verified business fact.

Do not publish uncertain information as confirmed merely because an AI model produced it.

## 8.3 External integrations

An integration should be shown as active only when its actual connection state supports that claim.

Do not fabricate:

- Successful connections
- Synchronized records
- Completed tasks
- Payment success
- Subscription activation
- Verified external accounts

## 8.4 Public credibility

Never invent:

- Testimonials
- Customer logos
- User counts
- Revenue results
- Security certifications
- Partnerships
- Awards
- Completed marketplace engagements

Use real evidence or omit the claim.

---

# PART 9 — USER EXPERIENCE PRINCIPLES

## 9.1 Design for nontechnical business owners

The user should not need to understand the underlying software architecture to use Munshee.

Use straightforward language.

Explain unfamiliar terms.

Keep important actions visible.

Avoid presenting technical logs as the primary interface for ordinary users.

## 9.2 Clear next steps

Each major page should answer:

1. Where am I?
2. What am I looking at?
3. What can I do here?
4. What should I do next?

Use meaningful page headings and action labels.

Avoid vague labels such as "Proceed" when a more specific description is possible.

## 9.3 Empty states

Empty states should explain what is missing and how to get started.

For example, an empty business-knowledge section might explain how to add a supported source or enter initial information.

Do not fabricate records just to avoid an empty screen.

## 9.4 Loading states

Use loading feedback when an operation genuinely takes time.

Avoid unnecessary spinners for instant interactions.

Where appropriate, preserve layout stability while data loads.

## 9.5 Error states

Errors should explain:

- What failed
- Whether the user's information was saved
- Whether retrying is appropriate
- What action can resolve the problem

Do not display raw internal errors to ordinary users unless the context genuinely calls for technical diagnostics.

## 9.6 Destructive actions

Provide appropriate confirmation for destructive or irreversible actions.

Do not make important operations easy to trigger accidentally.

---

# PART 10 — PRODUCT DEVELOPMENT PRIORITIES

## 10.1 Priority order

Kilo should classify work into these categories.

### P0 — Correctness, security, and critical usability

Examples:

- Incorrect or misleading product information
- Broken core workflows
- Data integrity problems
- Tenant isolation problems
- Unauthorized access
- False success messages
- Broken authentication
- Critical accessibility problems

Security fixes require appropriate scope and approval when they affect protected architecture.

### P1 — Core product usability

Examples:

- Merchant onboarding
- Business source management
- Fact review
- AI interaction
- Action review
- Accurate credit display
- Reliable navigation
- Clear errors and loading states

### P2 — Product quality and visual polish

Examples:

- Image relevance
- Typography
- Spacing
- Responsive layouts
- Logo alignment
- Interaction feedback
- Meaningful animation
- Better empty states

### P3 — Future capabilities

Examples:

- Expanded automation
- Additional integrations
- Advanced analytics
- Broader professional marketplace functionality
- Additional supported business workflows

These examples must be validated against the roadmap before implementation.

## 10.2 Avoid premature implementation

Do not build future features just because they appear in the product vision.

First establish:

- The user problem
- The expected behavior
- The required data
- The permission model
- The success criteria
- The operational dependencies
- The testing requirements

Then implement the smallest complete solution that fits the architecture.

---

# PART 11 — KILO CODE OPERATING PROCEDURE

## 11.1 Before every task

1. Read this document.
2. Read relevant project instructions.
3. Inspect the current repository state.
4. Check for user changes.
5. Identify the actual files and components involved.
6. Read the relevant implementation.
7. Determine whether the task is visual, functional, architectural, or security-sensitive.
8. Establish a baseline.
9. Identify uncertainties.
10. Produce a focused plan.

Do not edit files based solely on assumptions.

## 11.2 Audit before implementation

For substantial changes, begin with a read-only audit.

Report:

- What currently exists
- What is working
- What is broken
- What needs improvement
- What should remain unchanged
- What requires clarification
- What can safely be implemented now

Resolve uncertainties using repository evidence and available tests wherever possible.

Ask the owner only when a meaningful decision cannot be established from existing requirements.

## 11.3 Controlled execution

Implement in small, verifiable phases.

After each meaningful phase:

- Inspect the changes.
- Run relevant checks.
- Review visual output when applicable.
- Check for regressions.
- Preserve existing behavior.
- Update documentation when appropriate.

Do not replace large parts of the application in one uncontrolled rewrite.

## 11.4 Final report

Every substantial task should end with:

- Summary of changes
- Files or components affected
- Reasons for important decisions
- Tests actually performed
- Test results
- Known limitations
- Remaining issues
- Any action requiring approval

Do not claim success when only code has been written but the feature has not been verified.

---

# PART 12 — ABSOLUTE CHANGE-CONTROL RULES

Unless the owner explicitly approves otherwise:

- Do not discard user changes.
- Do not reset the repository.
- Do not delete existing work without justification.
- Do not commit.
- Do not push.
- Do not deploy.
- Do not publish.
- Do not run production migrations.
- Do not alter production data.
- Do not make purchases.
- Do not use paid services or APIs.
- Do not expose secrets.
- Do not modify unrelated systems.
- Do not alter locked pricing.
- Do not invent features.
- Do not fabricate test results.
- Do not change the separate admin application during merchant UI/UX work.

If a proposed action could be destructive, expensive, production-affecting, or difficult to reverse, stop and ask for approval.

---

# PART 13 — THE CURRENT UI/UX WORKSTREAM

The current task is to improve the existing Munshee website and application while following the approved Readdy reference.

Reference:

https://readdy.ai/project/b398cc85-2653-4994-b66b-83a00cc44792

The reference must be inspected directly or through supplied screenshots.

Do not claim exact fidelity without visual comparison.

## 13.1 Immediate objectives

1. Inspect the reference.
2. Audit the current website.
3. Inspect all existing images.
4. Map images to the correct sections.
5. Correct logo dimensions and alignment.
6. Preserve the intended brand identity.
7. Improve visual hierarchy and responsive behavior.
8. Add meaningful motion and microinteractions.
9. Verify existing functionality.
10. Capture before-and-after screenshots.
11. Report remaining differences.

## 13.2 Image requirements

Every image must support the section's message.

Do not use images merely to fill space.

Use actual application screenshots for genuine product demonstrations.

Do not present generated illustrations as working application screens.

Keep photographs, explanatory illustrations, and real product screenshots conceptually distinct.

## 13.3 Animation requirements

Add restrained, intentional motion.

Potential examples:

- Subtle hero entrance
- Selected scroll reveals
- Button hover and press feedback
- Smooth mobile navigation
- Clear loading transitions
- Workflow explanations

Avoid generic animation effects and decorative clutter.

Respect reduced-motion preferences.

## 13.4 Visual acceptance criteria

The result must:

- Follow the supplied reference closely.
- Preserve the established Munshee identity.
- Use contextually appropriate images.
- Have correct logo proportions.
- Be responsive.
- Be accessible.
- Avoid generic AI-generated design patterns.
- Provide meaningful interaction feedback.
- Preserve real application behavior.

---

# PART 14 — HOW TO MAKE PRODUCT DECISIONS

When several solutions are possible, evaluate them in this order:

1. Does the solution satisfy the actual user need?
2. Does it preserve data correctness and security?
3. Does it match the approved product and brand direction?
4. Does it work with the existing architecture?
5. Is it understandable to the intended user?
6. Is it maintainable?
7. Can it be tested?
8. Does it avoid unnecessary complexity and cost?

Prefer one coherent solution over several overlapping features.

Do not implement something simply because another SaaS product does it.

Do not sacrifice functionality for appearance.

Do not sacrifice usability for visual novelty.

Do not sacrifice security for convenience.

Do not sacrifice the approved design for generic trends.

---

# PART 15 — DEFINITION OF A SUCCESSFUL MUNSHEE EXPERIENCE

A successful Munshee experience should allow a merchant to:

1. Understand what the product does.
2. Get started without unnecessary confusion.
3. Bring in information through supported workflows.
4. Understand what information has been extracted.
5. Review and confirm relevant facts.
6. Use available business knowledge in supported AI interactions.
7. Understand what an AI action proposes to do.
8. Retain appropriate control over actions.
9. Understand available usage and operational information.
10. Recover from errors without needing technical assistance for ordinary problems.

The product should provide these experiences through a coherent, accessible interface.

The long-term direction is a system that can do more useful work while remaining understandable, controllable, and trustworthy.

Do not mistake this ambition for permission to claim every capability exists today.

---

# FINAL DIRECTIVE TO KILO CODE

Treat this document as the shared product context for Munshee.

Before each task, understand the product problem and the relevant requirements.

Inspect the actual implementation. Distinguish established decisions from assumptions and future plans. Preserve existing work. Make focused changes. Verify the results.

Your job is not to maximize the amount of code you write.

Your job is to help build Munshee into a coherent, trustworthy, useful, premium-quality AI Business Operating System.

**Understand the business. Respect the product. Preserve what works. Fix what is wrong. Build only what is justified. Verify what you deliver.**

---

## What I recommend you do next

Don't ask Kilo to redesign the entire product immediately after reading this document. Give it a staged assignment.

### Stage 1 — Understand the existing product

Ask Kilo to read the master context, inspect the repository, and produce a factual report of the current implementation.

It should identify which features are working, partially implemented, broken, or only planned.

### Stage 2 — Build a product-to-code map

Ask Kilo to map each product area to its actual routes, components, services, database structures, and tests.

This will reveal whether the interface represents real functionality or merely looks complete.

### Stage 3 — Finish the UI/UX work

Once the product map is available, use the image and logo refinement prompt we developed earlier. Have Kilo inspect the reference, correct the image mapping, improve the logo, and introduce purposeful motion.

### Stage 4 — Validate the experience

Test the important merchant journeys end to end. Verify that buttons, forms, navigation, data operations, and AI interactions behave correctly.

**The most important distinction:** Munshee's vision is much larger than its current implementation. Kilo must understand both, but it must never confuse what you want Munshee to become with what the software can demonstrably do today. That distinction will help it make better engineering decisions and avoid creating a beautiful interface that promises functionality the product cannot deliver.
