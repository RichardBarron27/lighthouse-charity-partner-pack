# Browser Permissions Explained

Lighthouse requests the minimum permissions needed to work. This document explains every single permission and exactly why it is needed.

---

## Permission: Storage

**What it means:** The extension can save a small amount of data on your device using the browser's built-in storage.

**Why Lighthouse needs it:** When you click "Remind me later" to snooze the helpline panel, Lighthouse saves a single timestamp so it knows when the snooze period ends. This is the only thing stored. No messages, no conversations, no personal information.

**What it does NOT allow:** This permission does not give access to your files, your browsing history, your passwords, or anything else on your computer.

---

## Host Permissions (Website Access)

Lighthouse requests permission to run on the following websites only:

| Website | Why |
|---|---|
| chat.openai.com | ChatGPT conversations |
| chatgpt.com | ChatGPT conversations |
| claude.ai | Claude conversations |
| gemini.google.com | Google Gemini conversations |
| copilot.microsoft.com | Microsoft Copilot conversations |
| character.ai | Character.ai conversations |
| chat.deepseek.com | DeepSeek conversations |
| grok.com | Grok conversations |
| pi.ai | Pi conversations |
| poe.com | Poe conversations |
| perplexity.ai | Perplexity conversations |
| huggingface.co/chat | HuggingChat conversations |
| chat.mistral.ai | Le Chat (Mistral) conversations |

**Why Lighthouse needs these:** To read the conversation text on these pages so it can check for signs of distress. This is how the extension does its job — it needs to see the words on the page.

**What it does NOT allow:** These permissions only let Lighthouse read the page content on these specific websites. It cannot see other websites, cannot see other tabs, cannot access your email, cannot access your files, and cannot access any website not listed above.

---

## What Lighthouse Does NOT Request

The following permissions are **not** requested because Lighthouse does not need them:

| Permission | Status | Why Not Needed |
|---|---|---|
| Browsing history | **Not requested** | Lighthouse does not track where you go |
| Bookmarks | **Not requested** | Not relevant to what Lighthouse does |
| Downloads | **Not requested** | Lighthouse does not download anything |
| Notifications | **Not requested** | Lighthouse shows helplines on the page, not as popup notifications |
| Geolocation | **Not requested** | Lighthouse does not need to know where you are |
| Camera or microphone | **Not requested** | Lighthouse only reads text, not audio or video |
| Clipboard | **Not requested** | Lighthouse does not read or write your clipboard |
| All websites | **Not requested** | Lighthouse only runs on the 12 chatbot platforms listed above |
| Network requests | **Not requested** | Lighthouse never contacts any server |

---

## Summary

Lighthouse uses **1 permission** (storage, for snooze only) and access to **12 specific AI chatbot websites** (to read conversation text). Nothing more.

If you have questions about permissions, contact us at **richard@red-specter.co.uk**.
