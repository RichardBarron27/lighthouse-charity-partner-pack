# How to Install Lighthouse — "Still Here"

Lighthouse is a free browser extension that shows helpline numbers when an AI chatbot conversation becomes concerning. It works silently in the background and everything stays on your device.

This guide walks you through installing it on **Chrome** or **Firefox**.

---

## What You Need

- A computer running **Google Chrome** or **Mozilla Firefox**
- The `lighthouse-still-here.zip` file (included in this pack)
- About 2 minutes

---

## Installing on Google Chrome

### Step 1: Unzip the extension

Find the `lighthouse-still-here.zip` file and extract it to a folder on your computer. You can right-click the file and choose **Extract All** (Windows) or double-click it (Mac).

Remember where you saved the extracted folder — you will need it in Step 4.

### Step 2: Open the Extensions page

Open Chrome and type this into the address bar:

```
chrome://extensions/
```

Press **Enter**. You will see Chrome's extension management page.

### Step 3: Turn on Developer Mode

Look for the **Developer mode** toggle in the **top-right corner** of the page.

Click it so it turns **blue** (on).

You will see three new buttons appear: "Load unpacked", "Pack extension", and "Update".

### Step 4: Load the extension

Click the **Load unpacked** button.

A file picker will open. Navigate to the folder where you extracted the zip file. Select the folder that contains `manifest.json` (this is the main folder, not a subfolder inside it).

Click **Select Folder**.

### Step 5: Confirm it is working

You should now see **"Lighthouse — Still Here"** in your list of extensions with a lighthouse icon.

The extension is now active. You can click the lighthouse icon in your toolbar to see its status.

**That's it — Lighthouse is now running.**

---

## Installing on Mozilla Firefox

### Step 1: Unzip the extension

Find the `lighthouse-still-here.zip` file and extract it to a folder on your computer.

### Step 2: Open the debugging page

Open Firefox and type this into the address bar:

```
about:debugging#/runtime/this-firefox
```

Press **Enter**.

### Step 3: Load the extension

Click the **Load Temporary Add-on** button.

A file picker will open. Navigate to the folder where you extracted the zip. Open the folder and select the file called **`manifest.json`**.

Click **Open**.

### Step 4: Confirm it is working

You should see **"Lighthouse — Still Here"** appear in the list of temporary extensions.

The lighthouse icon will appear in your toolbar. Click it to check the status.

**Note:** In Firefox, temporary add-ons are removed when you close the browser. You will need to repeat Steps 2-3 each time you restart Firefox. This is a Firefox limitation, not a problem with Lighthouse.

---

## How to Tell It Is Working

1. Visit any supported AI chatbot (such as ChatGPT, Claude, Gemini, or any of the 12 platforms listed below)
2. Click the **lighthouse icon** in your browser toolbar
3. If you see a green dot and the word **"Active"**, everything is working

### Supported Platforms

| Platform | Website |
|---|---|
| ChatGPT | chat.openai.com |
| Claude | claude.ai |
| Google Gemini | gemini.google.com |
| Microsoft Copilot | copilot.microsoft.com |
| Character.ai | character.ai |
| DeepSeek | chat.deepseek.com |
| Grok | grok.com |
| Pi | pi.ai |
| Poe | poe.com |
| Perplexity | perplexity.ai |
| HuggingChat | huggingface.co/chat |
| Le Chat (Mistral) | chat.mistral.ai |

---

## Snooze

If the helpline overlay appears and you want to pause it temporarily, click **"Remind me later"**. This snoozes Lighthouse for 1 hour. You can also snooze from the popup by clicking the lighthouse icon in your toolbar.

---

## Uninstalling

### Chrome
Go to `chrome://extensions/`, find Lighthouse, and click **Remove**.

### Firefox
Go to `about:debugging#/runtime/this-firefox` and click **Remove** next to Lighthouse.

---

## Questions?

Contact us at **richard@red-specter.co.uk** and we will be happy to help.
