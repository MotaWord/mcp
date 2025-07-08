# 🧠 Connecting MotaWord MCP to ChatGPT (via Connectors)

This guide walks you through how to connect the **MotaWord MCP (Model Context Protocol)** to ChatGPT using the native **Connectors** interface, enabling real-time access to translation project data directly from within your chat.

Once connected, you can ask ChatGPT questions like:

> "Show me the progress of our legal contract translation."  
> "Which projects are still under review?"  
> "Is the localization for our website completed?"

---

## ⚙️ What You’ll Need

- A MotaWord MCP-enabled account with OAuth support  
- Access to ChatGPT’s **Connectors** (available to pro users on ChatGPT 4o)  
- MCP Server URL: `https://api.motaword.com/mcp`  
- Developer permissions to create new connectors (if needed)

---

## 🔌 Step-by-Step Setup

### 1. Open ChatGPT’s Connector Menu  
Go to **Settings → Connectors** in ChatGPT.  
You'll see existing integrations like Gmail, Google Drive, GitHub, etc.

![Step 1 – Open Connectors](https://a.storyblok.com/f/84976/2346x1855/9cc8be209d/gpt1.png)

---

### 2. Click "Create" to Add a New Connector  
Choose **Create** (top right) to begin setting up a new integration.

![Step 2 – Click Create](https://a.storyblok.com/f/84976/2650x1919/2feffbb2ac/gpt2.png)

---

### 3. Fill in Connector Details  
Set up the connector as follows:

- **Name**: `MotaWord Translations`  
- **MCP Server URL**: `https://api.motaword.com/mcp`  
- **Authentication**: `OAuth`  
- ✅ Check: “I trust this application”

Then click **Create**.

![Step 3 – Connector Form](https://a.storyblok.com/f/84976/2903x1536/de78decd4e/gpt3.png)

---

### 4. Authorize ChatGPT with Your MotaWord Account  
You’ll be redirected to authenticate.  
Log in with your MotaWord credentials and **Allow Access**.

This grants ChatGPT permission to:

- View your projects and translations  
- Create or modify translations  
- Manage integrations on your behalf  

![Step 4 – OAuth Access](https://a.storyblok.com/f/84976/2654x1892/b073065dad/gpt4.png)

---

### 5. Verify the Connector is Active  
Back in ChatGPT, MotaWord will now appear under your **Enabled connectors** list.

![Step 5 – Connector Active](https://a.storyblok.com/f/84976/2648x1838/7793724e7b/gpt5.png)

---

### 6. Use It in Conversation  
In any chat, click the ⚙️ **Tools** or 🌐 **Sources** dropdown. Enable “MotaWord Translations” as a source.

Now you can ask things like:

> "What is the current status of project 387JXA?"  
> "List all French projects in the review stage."  
> "Get progress updates for marketing campaigns."

![Step 6 – Using the Connector](https://a.storyblok.com/f/84976/2651x1835/b81c37cfec/gpt6.png)

---

## ✅ Supported Capabilities

With MotaWord MCP connected, ChatGPT can:

- Retrieve project metadata  
- Show current workflow phase (Translation, Review, Delivery)  
- Fetch progress stats or assignment breakdowns  
- Trigger contextual project queries during conversations  

---

## 🔐 Security & Permissions

Your MotaWord data is accessed securely using OAuth and is **only visible to you**. You can revoke access at any time via:

> ChatGPT Settings → Connectors → MotaWord Translations → Revoke Access

---

## 💬 Example Prompts

```plaintext
"Show me all projects due this week"
"Get progress for French → Arabic translation jobs"
"Is the HR handbook project completed?"
"How many words are left in project ID 1254cf?"
