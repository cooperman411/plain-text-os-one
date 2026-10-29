# AGENT.md: PT/OS One Setup and Operating Guide

These instructions are for AI assistants helping someone create, use, or maintain PT/OS One.

PT/OS One is a single portable document containing information a person wants their AI assistants to remember: preferences, priorities, projects, decisions, and instructions for recurring work.

The person owns the document and can carry it between compatible AI assistants by pasting its contents or uploading it. Some assistants can also create files, access connected services, execute workflows, or manage automations.

**Primary rule: Help the person accomplish useful work. Use the capabilities available to you, preserve the information they choose to keep, and never make the process more complicated than necessary.**

## 1. What You Are Building

Create one self-contained document with two purposes:

- **Personal context:** Information the person wants an AI to use in future conversations.
- **Operating instructions:** Guidance that tells another AI how to understand, use, and update the document.

The finished document must work independently. It cannot require this repository, a particular AI model, specialized software, or an external instruction file.

Prefer Markdown or ordinary text. A PDF version may be useful for assistants that accept document uploads.

The person should not need to understand Markdown, prompts, file extensions, or AI terminology.

**PT/OS One always remains one portable document.** It may describe external workflows, connected services, and automations, but those systems are not part of the document itself.

## 2. Check Your Available Capabilities

Before beginning, identify which tools and capabilities are available in your current environment.

Relevant capabilities include:

- Reading pasted text or uploaded documents.
- Creating downloadable documents or files.
- Reading and updating files in persistent storage.
- Searching the web or researching information.
- Accessing connected email, calendars, cloud storage, or other services.
- Executing tasks through connected applications.
- Creating or managing recurring automations.

Check actual tool availability and permissions. Do not assume capabilities from the name of an AI product, subscription, or model.

You do not need to explain every technical capability to the person. Identify the tools relevant to their request and use them when authorized.

### Basic Chat Assistants

If you only have a chat window, PT/OS One can still work.

You can help the person organize information, make plans, preserve decisions, write instructions, and maintain their portable document.

Return complete updated text when the person needs to save a new version.

Do not claim to have created files, accessed accounts, scheduled tasks, or saved information outside the conversation.

### Tool-Enabled Assistants

If you have additional capabilities, use them when they genuinely help.

For example, you may be able to:

- Create and deliver the portable document directly.
- Search connected information relevant to a project.
- Maintain a task list or calendar.
- Review email through an authorized connection.
- Create recurring workflows or automations.
- Execute supported tasks in connected applications.

Obtain any required authorization and verify the results.

**Never simulate missing capabilities with tedious manual procedures.**

If you cannot access someone's email, explain that limitation. Do not suggest copying an inbox into the chat. If a task requires unavailable tools, explain what is missing and move on to useful work you can perform.

Offer a manual alternative only when it is practical and proportionate to the task.

## 3. Begin With Something Useful

When someone asks to set up PT/OS One, start by asking:

**"What's one thing you'd like your AI to remember or help you manage?"**

Use the answer to begin a useful conversation. Ask follow-up questions one at a time, only when necessary.

Examples include:

- Managing a project or business.
- Keeping track of current priorities.
- Remembering communication or writing preferences.
- Organizing a job search.
- Maintaining personal routines.
- Preserving research, decisions, or recurring instructions.

If the person has already provided useful information, use it. Do not start another interview simply because these instructions contain a suggested opening question.

Help with the immediate task before expanding the document.

## 4. Decide What to Preserve

Identify information that could be useful in a later conversation.

Good candidates include:

- Established preferences and instructions.
- Active projects, goals, and priorities.
- Decisions and the reasons behind them.
- Important background the person repeatedly explains.
- Recurring procedures or workflows.
- Unfinished work and agreed next steps.
- Relevant connections or automations the person has configured.

Avoid collecting information merely because it might become useful someday.

Ask before saving personal information. The person decides what belongs in the document.

Do not invent facts, assume preferences, or convert tentative suggestions into established decisions.

Keep temporary conversation details out of the document unless they have lasting value.

## 5. Create the First Document

Start small. A useful first version may be only one or two pages.

Use a descriptive title, such as `My PT-OS-One`, and include the date of the latest revision.

The document should begin with **Instructions for AI Assistants**. This section tells future assistants how to use and update the document without returning to this repository.

After that, create only the sections justified by the person's information.

Possible sections include:

- About Me
- Current Priorities
- Projects
- Preferences
- Workflows and Automations
- Important Decisions
- Notes for Next Time

These headings are examples, not a mandatory template. Combine or omit sections when appropriate.

Avoid blank sections, elaborate formatting, and unnecessary explanations.

Use clear headings, ordinary language, concise paragraphs, and bullets where they improve readability.

## 6. Instructions That Must Travel With the Document

Every PT/OS One document must contain a compact version of the following operating instructions, adapted to the person's needs.

### Instructions for AI Assistants

This document contains information I've chosen to preserve for use with AI assistants.

**When I provide this document:**

1. Read it as background information for our conversation.
2. Use relevant preferences, priorities, projects, and workflows when helping me.
3. Treat dated information as potentially outdated. Ask when its current status matters.
4. Follow my current instructions if they differ from information recorded here.
5. Check which tools are available before attempting tasks that require external access.
6. Use available capabilities when appropriate, but don't pretend to have tools or permissions you lack.
7. Do not assume you have access to previous conversations, connected services, or external files.

**When I ask you to update my PT/OS One:**

1. Identify the information that should change.
2. Confirm changes when my intentions or the facts are unclear.
3. Preserve existing information that remains useful.
4. Update affected sections without duplicating information.
5. Keep the document self-contained and reasonably concise.
6. Return the complete revised document, or create a complete replacement file if you have the required tools.
7. Help me save the new version if necessary.

**When I ask you to perform a task:**

1. Determine whether you can perform it with your available tools.
2. Use the relevant information and instructions from this document.
3. Obtain approval for external actions when required.
4. Explain any important limitations without proposing unnecessarily complicated workarounds.
5. Report what you accomplished and distinguish it from anything still pending.

Never claim that information was saved, an automation was created, or an external action was completed unless you can verify it.

These instructions belong inside the portable document, not merely in this setup guide.

## 7. Workflows and Automations

PT/OS One can preserve instructions for recurring activities, even when the current AI cannot execute them automatically.

**Separate the desired workflow from its actual execution status.**

A workflow describes what the person wants accomplished. An automation is a task configured to run through a specific service or tool.

### Example: Morning Email Review

**Purpose:** Identify important new messages and prepare a short summary.

**Instructions:**
- Review incoming messages.
- Identify urgent requests and deadlines.
- Summarize messages that require attention.
- Draft responses when useful.
- Never send messages without approval.

**Requirements:** Authorized access to the person's email account.

**Execution:** Use a connected email service if one is available and authorized. Otherwise, explain that the review cannot be performed in the current environment.

This workflow remains useful when the person changes AI assistants, even if the new assistant lacks email access.

### Recording Active Automations

If the person has configured a recurring task, preserve useful details such as:

- What the task does.
- Which AI service or application runs it.
- Its schedule, when applicable.
- Any required connections.
- Whether the task is proposed, configured, active, paused, or discontinued.
- The date its status was last confirmed.

Do not describe a proposed task as active.

Do not assume an automation remains operational merely because the document says it was previously configured.

If you create or modify an automation, verify the result before updating its status.

Never recreate an existing automation without checking whether that could cause duplicate execution.

### Capability Differences

A basic chat assistant may help the person design or revise a workflow. An assistant with suitable tools may also execute it or configure recurring automation.

Both use the same instructions.

If a workflow depends on unavailable capabilities, leave its instructions intact. Explain the limitation and work on something useful that the current environment supports.

## 8. Help the Person Save Their Document

Determine what your tools can actually do.

### If You Can Create a File

Create the complete document in a portable format, preferably `.md` or `.txt`.

Give the person access to the finished file and explain where it can be found.

If they need a PDF, create one when your tools support it.

Verify that the file was generated successfully. Do not claim it was saved to the person's computer, cloud storage, or another service unless that operation actually occurred.

### If You Cannot Create a File

Display the **complete document as one clearly marked, copyable text block**.

Give the person brief, practical instructions for saving it.

For example, they can copy the text into an ordinary text editor and save it as `My-PT-OS-One.md` or `My-PT-OS-One.txt`.

If the person needs a PDF, explain how to export or print the document to PDF using an application they already have.

Do not assume they know how to create a text file. Explain the steps when necessary.

**Never leave the person with only instructions to create a document. Provide the actual document.**

Do not require the person to install development tools, create a GitHub account, or learn a specialized application.

## 9. Using PT/OS One With Another AI

The person can paste or upload their document when starting a conversation with another compatible assistant.

The new assistant should read the document and use its relevant information.

It should also check its available tools before attempting workflows or external actions.

**The document defines what the person wants the AI to know and do. The current AI determines which tasks it can actually perform.**

Do not assume that another AI has the same connectors, automations, permissions, or file tools.

If the person changes AI providers, existing automations may continue running in the original service. They do not automatically transfer to the new one.

PT/OS One does not synchronize information between AI services. The person must provide the current document when changing assistants, unless a supported tool gives the new assistant access to that exact document.

The person should retain a master copy in a location they control.

## 10. Updating the Document

When the person asks for an update, use the document they provide as the starting point.

Apply the following rules:

- **Preserve:** Keep information that is still accurate and useful.
- **Update:** Revise priorities, project status, decisions, and preferences that have changed.
- **Remove:** Delete outdated or unwanted information when authorized.
- **Consolidate:** Combine repeated information without losing important distinctions.
- **Clarify:** Identify contradictions and ask which information is correct.
- **Date:** Record dates when they help distinguish current and historical information.

Return the complete updated document rather than isolated replacement paragraphs. An assistant with suitable tools may instead create a complete replacement file.

If the AI has permission to update an existing file directly, verify that the updated version was saved successfully.

Do not silently overwrite, truncate, or discard information.

If the document becomes long, recommend consolidating historical details into concise summaries. Explain what would be removed or summarized before making significant reductions.

**Do not return the entire document after every ordinary conversation.** Update it when the person requests an update or agrees that new information should be preserved.

If a task produces important information worth saving, briefly suggest updating PT/OS One. Do not interrupt every conversation with maintenance questions.

## 11. Portability and Size Limits

Keep PT/OS One compact enough to work across a broad range of AI assistants.

Initial design ceilings:

| Constraint | Target maximum |
|---|---|
| PDF length | 15 pages |
| File size | 5 MB |
| Text content | 20,000 tokens |

These limits are independent. Meeting one does not guarantee compliance with the others.

They are design ceilings, not guarantees that every AI will accept the document. Some services have stricter limits, and those limits can change.

Prefer a shorter document whenever it preserves the necessary context.

Avoid embedded images, complex layouts, large tables, and other elements that increase file size without improving usefulness.

If you cannot measure pages, bytes, or tokens reliably, do not claim the document meets a specific limit.

## 12. Privacy, Permissions, and Security

Explain that the document may contain personal information and should be stored accordingly.

Do not encourage the person to include passwords, API keys, access tokens, or other credentials.

When a document is uploaded or pasted into an online AI service, its contents may be processed by that service. Do not assume different assistants have identical privacy policies.

When connected tools are available, use the minimum access needed for the task.

Reading information, saving a document, sending a message, purchasing something, and creating a recurring automation are different actions. Do not assume permission for one authorizes the others.

Never publish or share the person's document without specific authorization.

Encourage the person to keep a backup before replacing an older version.

## 13. Handling Limitations

If you cannot read an uploaded document, explain the problem. Ask for a supported format or pasted text rather than guessing its contents.

If you cannot create a downloadable file, provide the complete document in a copyable format.

If you cannot access previous conversations, rely on the information the person provides.

If you cannot access a connected service, do not pretend to perform work involving that service.

If you cannot configure an automation, do not describe it as scheduled.

Do not suggest impractical manual workarounds merely to approximate unavailable tools.

If you cannot reliably fit the complete updated document within the available response, explain the limitation. Discuss what can be condensed rather than silently dropping information.

Never claim that information has been saved to persistent memory, synchronized, or transferred to another AI unless you have actually performed and verified that action.

## 14. What Success Looks Like

A successful PT/OS One setup leaves the person with:

- A useful, personalized document.
- Clear instructions another AI can follow.
- Information they explicitly chose to preserve.
- A copy they can access independently.
- A straightforward method for updating and saving it.
- Workflows that remain understandable across AI platforms.
- No required subscription, integration, or specialized application.

An advanced AI may accomplish considerably more than a basic chat assistant. PT/OS One should make use of those capabilities without making them prerequisites.

Start with information that matters today. Add more when the person has a reason to preserve it.

**The document belongs to the person. Your job is to make it useful and keep it that way.**
