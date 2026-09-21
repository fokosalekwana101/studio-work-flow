# AI Workplace Studio

BUILD THE WEBSITE NOW. Do not spend credits asking unnecessary clarification questions. Use the specification below as the source of truth. Prioritize a working, polished prototype over extra features.

WORKFLOW STUDIO

AI Workplace Productivity Assistant

Build a high-end, presentation-ready workplace productivity web application called WorkFlow Studio.

The application should demonstrate how AI can automate common workplace tasks such as email writing, meeting summarization, task scheduling, research and workplace questions.

1. DESIGN SYSTEM

Create an ultra-modern premium SaaS interface inspired by Linear and Vercel.

Visual style

Strict monochrome palette only.

Pure white, deep charcoal, black and zinc/grey tones.

NO bright accent colours.

High-contrast typography.

Crisp 1px borders.

Subtle shadows only where necessary.

Generous spacing.

Minimal, professional and sophisticated.

Avoid generic dashboard templates.

Make the product visually distinctive.

Theme

Implement a fully functional Light/Dark mode toggle in the top header.

Both themes must look intentionally designed, not simply inverted.

Layout

Use:

Collapsible floating icon sidebar.

Top header.

Global ⌘K / Ctrl+K command/search bar.

Main workspace.

Dual-pane layouts for AI tools where appropriate.

Input panel on the left.

Live document-style AI output panel on the right.

The interface must be responsive on desktop, tablet and mobile.

2. APPLICATION NAVIGATION

Sidebar:

Dashboard

Email Generator

Meeting Summarizer

Task Planner

Research Assistant

AI Chat

Settings

The sidebar should collapse into icons and expand when needed.

Add tooltips for sidebar icons.

3. DASHBOARD

Create a clean overview dashboard.

Show:

Welcome/header section.

Short description of WorkFlow Studio.

Quick-access cards for the five AI tools.

Emails Generated

Meetings Summarized

Tasks Planned

Research Briefings

Estimated Time Saved

Use realistic demo statistics only where necessary and clearly treat them as demo/estimated data.

Include a small "Recent Activity" section.

Do not build complex analytics.

4. SMART EMAIL GENERATOR

Create a fully functional AI email-generation workflow.

Inputs

Recipient

Audience selector:

Client

Manager

Team

Other

Core Message

Tone:

Formal

Direct

Persuasive

Tone Intensity slider

AI output

Display the result as a professional document preview containing:

Subject line

Email body

Copy button

Regenerate button

Executive Polish toggle

Executive Polish should rewrite the generated email to make it clearer, more concise and executive-level while preserving the original meaning.

AI rules

The AI must:

Use only information provided by the user.

Never invent facts, names, deadlines or commitments.

Adapt wording to the selected audience.

Follow the selected tone and intensity.

Produce professional workplace communication.

5. MEETING NOTES SUMMARIZER

Create a fully functional meeting summarization workflow.

Input

Large transcript/raw notes text area.

AI output

Display:

Executive Summary

Concise overview of the meeting.

Key Decisions

Important decisions extracted from the notes.

Action Items

Create clean copyable Markdown task cards.

Each task should contain where available:

Task

Owner

Deadline

Priority

If an owner or deadline is not present in the source material, display "Not specified" rather than inventing one.

Additional controls

Copy summary

Copy action items

Regenerate

6. AI TASK PLANNER & SCHEDULER

Create an AI scheduling workflow.

Inputs

Unstructured task list

Available working hours

Optional task priorities

AI output

Generate a clean timeline/table containing:

Time

Task

Duration

Priority

Reason/notes

Priority tiers:

P1 — Critical

P2 — High

P3 — Normal

P4 — Low

The AI should prioritize tasks using urgency and importance.

Also provide:

Time Optimization Suggestions

Examples:

Batch similar tasks.

Protect focus periods.

Move low-priority work.

Identify scheduling conflicts.

Add reasonable buffers where appropriate.

Do not claim that a schedule is objectively optimal. Present it as an AI-generated recommendation.

7. AI RESEARCH ASSISTANT

Create a research/briefing workflow.

Inputs

Topic/query

Optional pasted article, report or text.

Output

Create a professional briefing card containing:

Plain-English Summary

Explain the topic simply for a busy workplace user.

Key Takeaways

Important information extracted from the input.

Potential Risks

Relevant risks, limitations or uncertainties.

Actionable Recommendations

Practical recommendations clearly labelled as AI-generated recommendations.

The AI must:

Avoid fabricating facts.

Avoid fabricating sources.

Clearly distinguish information from recommendations.

Identify uncertainty where relevant.

8. AI CHATBOT

Create a clean workplace assistant chat interface.

Features:

Stream-style conversation.

User/AI message distinction.

Markdown support.

Suggested prompt chips.

Copy response button.

Clear conversation button.

Auto-scroll.

Loading state.

Error state.

Suggested prompts:

"Summarize this document"

"Help me write a professional email"

"Turn these tasks into a schedule"

"Explain this topic simply"

"Prepare talking points for my meeting"

Keep the chatbot focused on workplace productivity.

9. RESPONSIBLE AI

This is an important assessment requirement.

Place a visible but unobtrusive banner in the application:

Responsible AI Notice: Model outputs may contain inaccuracies. Always review, edit, and verify content before workplace execution. Do not submit proprietary corporate data.

Under EVERY AI-generated output, include an interactive:

Verification Checklist

Checkboxes should be relevant to the feature.

Examples:

Email:

Facts verified

Tone verified

Recipient/audience verified

Confidential information checked

Meeting:

Decisions verified

Action items verified

Owners verified

Deadlines verified

Research:

Facts verified

Sources checked

Risks reviewed

Recommendations reviewed

Task Planner:

Priorities verified

Time estimates reviewed

Schedule conflicts checked

Chat:

Response reviewed

Facts verified

Sensitive information checked

Make the checklist interactive.

10. AI AND PROMPT ENGINEERING

The AI functionality must use structured prompts rather than generic one-line prompts.

Use this structure internally for each AI workflow:

ROLE → CONTEXT → TASK → CONSTRAINTS → OUTPUT FORMAT → VERIFICATION RULES

Prompts should be optimized for:

Accuracy

Professional workplace language

Clear structured outputs

Conciseness

Avoiding hallucinations

Avoiding invented information

Do not expose API keys in frontend code.

Use environment variables/secrets where required.

If an AI provider/API connection is required, structure the application so it can be connected securely.

Do not use fake AI responses as the final implementation if a real AI integration is available.

If AI credentials are unavailable during initial development, build the complete UI and integration structure with clearly isolated mock fallback data so the real provider can be connected without redesigning the application.

11. UX STATES

Every AI workflow must have:

Empty state

Input validation

Generate button

Loading state

Generated result

Copy action

Regenerate action

Error state

Clear/reset action

Disable the Generate button when required input is missing.

Use subtle animations only where they improve usability.

12. PRODUCTIVITY VALUE

The application should visibly demonstrate productivity improvement.

Track simple application-level metrics:

Emails generated

Meetings summarized

Tasks planned

Research briefings generated

Estimated time saved

For estimated time saved, clearly label it as an estimate and do not make unsupported productivity claims.

13. SETTINGS

Keep Settings lightweight.

Include:

Light/Dark mode

AI response preference: Concise / Detailed

Default email tone

Responsible AI notice

Clear local/demo activity data

Do NOT build unnecessary account management, billing, team administration or enterprise features.

14. IMPORTANT BUILD RULES

Follow these rules strictly:

Build the complete website, not just a landing page.

Prioritize the five core AI workflows.

Make every workflow visually polished and interactive.

Keep the architecture simple.

Avoid unnecessary dependencies.

Do not add features that are not required.

Do not create complex authentication unless technically required.

Do not create payment/billing functionality.

Do not create social features.

Do not create unnecessary admin panels.

Do not waste credits on decorative features that don't improve the assessment.

Reuse components where possible.

Keep the design system consistent across every page.

Ensure the application works on desktop and mobile.

Use realistic empty/demo states where required.

Make all buttons and controls functional.

Do not leave obvious placeholder text such as "Lorem ipsum".

Do not stop after creating the dashboard — build all five workflows.

Do not ask me to repeatedly approve small design decisions. Make sensible decisions based on this specification and continue building.

If a technical implementation choice is required, choose the simplest reliable solution that satisfies the requirements.

15. FINAL QUALITY CHECK

Before considering the build complete, verify that:

Dashboard works.

Navigation works.

Light/Dark mode works.

Email Generator works.

Meeting Summarizer works.

Task Planner works.

Research Assistant works.

AI Chat works.

Copy buttons work.

Verification checklists work.

Loading/error states exist.

Responsive layouts work.

Responsible AI notice is visible.

No bright accent colours are used.

UI remains monochrome.

No unnecessary features have been added.

The application looks presentation-ready.

Build the website now and prioritize functionality, polish and assessment requirements over unnecessary complexity.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://studio-work-flow.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/8b6b649d-e32d-410a-890c-ec04e77f3104).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
