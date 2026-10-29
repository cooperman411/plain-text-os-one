# PT/OS One — AI Compatibility Guide

**One portable document. Different AI assistants. No special setup required.**

*Reviewed: October 28, 2026*

## The short version

PT/OS One does not require an AI that can manage folders, edit files in place, connect to outside services, or run automations. An ordinary chat assistant can be enough.

The essential question is: **Can this assistant read your document, use its instructions, and give you a complete updated version when you ask?**

More capable assistants may also create downloadable files, use connected apps, or perform authorized tasks. Those extras are useful, not required.

This guide describes likely ways to use PT/OS One, not guarantees about every plan, model, device, or account. Features change, and none of the configurations below was tested end-to-end for this guide.

## Three levels of use

| Level | What the AI can do | What PT/OS One needs |
|---|---|---|
| **Chat** | Read pasted text, use your preferences and project information, help you plan, and return revised text. | Enough room in the conversation for your document and its updated version. |
| **Documents** | Read an uploaded document and/or create a downloadable replacement. | Supported formats and file-generation features. The person still keeps the master copy. |
| **Connected actions** | Work with authorized email, calendars, files, apps, or automations where tools permit. | A real connection, appropriate permissions, and confirmation that the action occurred. |

These are capabilities, not subscription tiers. One assistant might support all three; another might support only the first. **The same PT/OS One document works in either case.**

## Platform guide

The **Chat** route means pasting the document into a conversation. File uploads and external actions are separate features; do not assume they exist just because the assistant can chat.

| AI assistant / environment | Practical PT/OS One route | Additional capabilities or caveats |
|---|---|---|
| **ChatGPT** | Paste or upload the document. | File creation, connected apps, and scheduled tasks depend on the available tools, plan, and permissions. |
| **Claude** | Paste or upload the document. | Can create downloadable documents when file creation is enabled. Cowork and Claude Code offer different, more advanced file workflows. |
| **Google Gemini** | Paste or upload the document. | Some configurations can generate files or work with Google documents. Check the specific app and permissions. |
| **Grok** | Paste or upload the document. | Connected services may be available. Connection to a service does not automatically authorize every action. |
| **Microsoft Copilot** | Use the document in chat or a supported Microsoft document workflow. | Office/OneDrive actions depend heavily on which Copilot product and license are being used. |
| **Mistral Le Chat** | Paste the document; use file input if supported in the current interface. | Mistral Vibe is a separate, more technical agent environment. |
| **Brave Leo** | Paste the document. | PDF attachments are supported on certain desktop and Android versions; do not assume source-file editing. |
| **Duck.ai** | Paste the document. | Some models support PDF uploads, but not general document uploads. Duck.ai lists PDF page limits by plan. No external actions should be assumed. |
| **Perplexity** | Paste or upload the document where supported. | Research and file access vary by configuration. Access to a connected file does not imply permission to edit it. |
| **Hermes Agent** | Provide the document in chat or its authorized workspace. | Agent installations may maintain files and run tools, but those capabilities depend on how the agent is deployed. |
| **OpenClaw** | Give the agent access to the document in an approved workspace. | Can support advanced workflows, but installing an agent is unnecessary for PT/OS One. |
| **Muse** | Use the document in conversation or an accessible file, if supported by the configured environment. | File tools and integrations require checking in the actual installation; not verified here. |
| **DeepSeek** | Paste the document; use uploads if supported. | Treat external actions and persistent editing as unavailable unless the actual interface provides them. |
| **Lumo (Proton)** | Paste or upload the document; Proton Drive files can be supplied as context. | Lumo Creations is available to Free and paid users who sign in to a Proton account. It can generate downloadable Word, PDF, or HTML documents. A generated copy is not automatic updating of your master document. |
| **Qwen** | Paste the document; use uploads if supported. | Available tools vary by service and configuration; verify before relying on them. |

**A note on Duck.ai:** Its current help page describes image and PDF uploads for some models, not general `.md` or `.txt` uploads. Pasting text is the straightforward approach; a PDF can be useful if the chosen model accepts it. Do not promise that a file accepted elsewhere will upload to Duck.ai.

## How to start

The main [PT/OS One README](README.md) provides a single copyable prompt pointing to the [PT/OS One repository](https://github.com/cooperman411/plain-text-os-one). An AI that can open the repository can follow its instructions.

If the assistant cannot read the GitHub URL, open [AGENT.md](AGENT.md), copy its contents into the conversation, and ask the assistant to help you get started.

**You only need `AGENT.md` for setup.** Once your personal document is created, it contains its own operating instructions. Bring that document to whichever compatible AI you use next.

## Updating the document

1. Give the assistant your current PT/OS One document, unless it already has verified access to that exact copy.
2. Explain what changed and ask for the document to be updated.
3. Have the assistant return the **complete revised document**, either as text you can save or as a downloadable file.
4. Keep the updated version as your master copy. Check that important sections were not lost.

An assistant with suitable file tools can sometimes edit the master directly. It must verify that the save succeeded. **A new chat, a Project, an uploaded file, or an AI's own memory is not automatic synchronization across providers.**

## What it does *not* promise

- **No universal GitHub access.** The one-prompt setup is the simplest option, but some assistants cannot follow a repository link. That is why `AGENT.md` is available as a fallback.
- **No universal upload format or size.** Plain text is the most portable content; `.txt` and `.md` are convenient where supported. PDFs can help with limited upload interfaces, but should not become the only editable master copy. Keep the document reasonably short.
- **No automatic cross-service memory.** An assistant knows only the information you give it or that its authorized tools can retrieve.
- **No imaginary automations.** A described workflow is not a running scheduled task. Confirm which service is responsible, whether it is active, and when that status was checked.
- **No tedious substitutes for missing tools.** If an assistant cannot access email, it should say so—not ask you to paste an entire inbox into chat. Manual alternatives should be genuinely practical.
- **No implied permission.** Reading a document does not authorize sending email, changing calendar entries, publishing content, or spending money.

## A quick compatibility check

Before relying on a new AI, give it your current document and ask it to summarize one or two priorities from it. Then ask for a small change and request the complete revised document. If it cannot reliably read or return the full document, use a smaller version or a different assistant for maintenance.

For advanced features, test the specific action and verify the result. Never assume a tool exists because another version of that AI offers it.

## Sources and updates

This guide is adapted from the original [PT/OS Workspace capability matrix](https://github.com/cooperman411/plain-text-os/blob/main/CAPABILITY-MATRIX.md). That matrix tests persistent multi-file read/write access; **PT/OS One deliberately does not require it**.

Selected vendor documentation:

- [ChatGPT Library and uploaded files](https://help.openai.com/en/articles/20001052-using-library-to-manage-files-in-chatgpt)
- [ChatGPT connected apps](https://help.openai.com/en/articles/11487775-connected-apps-in-chatgpt)
- [Claude file uploads](https://support.claude.com/en/articles/8241126-upload-files-to-claude)
- [Claude file creation](https://support.claude.com/en/articles/12111783-create-and-edit-files-with-claude)
- [Gemini file uploads](https://support.google.com/gemini/answer/14903178)
- [Grok file uploads](https://docs.x.ai/grok/faq)
- [Brave Leo PDF attachments](https://brave.com/whats-new/leo-pdf-attachments/)
- [Duck.ai file uploads](https://duckduckgo.com/duckduckgo-help-pages/privacy-pro/duck-ai/does-duckai-support-file-uploads)
- [Lumo and Proton Drive](https://proton.me/support/lumo-drive)
- [Lumo Creations](https://proton.me/support/lumo-creations)

Update individual platform entries when verified behavior changes. Avoid turning this guide into a pricing or feature checklist that will be obsolete next month.