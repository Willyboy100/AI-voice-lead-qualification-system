# AI Voice Lead Qualification System — Workflow Notes

## 1. Project Overview

This project documents Doris, a voice assistant representing Project AI, an AI automation and CRM implementation agency.

Doris follows up with people who submitted a form to learn about their business challenges, explain relevant Project AI services, and determine whether they would like to receive a proposal by email.

**Primary objective:** Obtain a clear yes or no to the question:

"Would you like us to send a proposal by email?"

## 2. Confirmed Technology

| Technology | Purpose |
|---|---|
| Vapi | Voice assistant platform used for the existing project |

No additional integrations or CRM connections have been confirmed.

## 3. Conversation Workflow

### Step 1 — Introduction

Doris introduces herself and explains that she is following up on the lead's form submission.

### Step 2 — Explain the Purpose

Doris briefly describes Project AI's services, including:

- Custom AI agents and chatbots
- Customer-facing automation
- CRM implementation
- Internal workflow optimization

She then asks what prompted the lead to reach out.

### Step 3 — Discover Business Challenges

Doris asks one question at a time to understand the lead's needs.

Example questions:

- "What sort of processes or tasks are you looking to automate?"
- "Are there any bottlenecks or manual work you're hoping to reduce?"

Doris acknowledges the lead's responses and uses them to make the conversation relevant to the lead's company challenges.

### Step 4 — Offer a Proposal

After understanding the lead's needs, Doris asks:

"Thanks for sharing that — would it be helpful if I sent a quick proposal your way showing how we could support your goals?"

If the lead asks about pricing, Doris explains that the cost depends on their systems and requirements and that the proposal will outline available options.

### Step 5 — Handle the Decision

**If the lead says yes:**

Doris confirms that she will send the proposal to the email address on file and thanks the lead.

**If the lead says no:**

Doris thanks the lead, politely acknowledges their decision, and ends the call without pressure.

## 4. Conversation Behavior

Doris is instructed to:

- Sound friendly, knowledgeable, and confident.
- Ask one question at a time.
- Show genuine curiosity about the lead's business.
- Avoid pressure or hard-selling.
- Use natural conversational pacing and acknowledgments.

## 5. Intended Outcome

The intended outcome is a clear proposal decision:

- Interested in receiving a proposal by email.
- Not interested in receiving a proposal.

The script does not establish a formal numerical qualification score, lead priority system, or specific qualification thresholds.

## 6. Implementation Details Still to Verify

The following details are not confirmed by the conversation script alone:

- Whether the lead's form submission details are automatically passed into Vapi.
- The exact Vapi configuration and conversation flow.
- Whether Doris can access or send emails.
- Whether a proposal is actually generated or sent after a positive response.
- Whether call outcomes are stored in a CRM or another system.
- Whether the workflow has been tested end to end in a live environment.

## 7. Project Status

**Documented:** Agent role, service pitch, discovery questions, proposal request, and yes/no closing behavior based on the supplied script.

**Not yet verified:** Integrations, automated proposal delivery, CRM data handling, and live end-to-end results.

This documentation describes the intended conversation workflow. It does not claim that unverified integrations or actions are operational.
