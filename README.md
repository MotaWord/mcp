# MotaWord MCP (Model Context Protocol)

The **MotaWord MCP (Model Context Protocol)** is a private interface that provides structured, real-time access to translation project data. It’s designed to offer external systems (like LLMs, automation tools, or admin dashboards) context-aware visibility into the status, structure, and progress of ongoing translation jobs on the MotaWord platform.

This protocol enables seamless monitoring of translation workflows, allowing authorized systems or users to retrieve current project states—translation, review, or completion—without relying on manual updates or emails.

> ⚠️ **Note:** This is a private, closed-source repository used for documentation and reference only.

---

## 🔗 API Access

**Base URL:**

https://api.motaword.com/mcp

yaml
Copy
Edit

Authentication is required for access. Please refer to internal documentation or your API key provisioning contact for credentials.

---

## 🔐 Authentication

MCP uses token-based authentication. Tokens must be included in the request header:

Authorization: Bearer YOUR_TOKEN_HERE

yaml
Copy
Edit

To obtain credentials, contact your MotaWord integration manager or support team.

---

## 🎯 Use Cases

- Provide LLMs or middleware with real-time translation project context  
- Monitor the lifecycle of a project: from creation → translation → review → delivery  
- Enable dashboard visualizations or notification triggers based on live project data  
- Power internal tools that need to surface project status programmatically  

---

## 🖼️ Usage Showcase (Claude AI)

Below is an example of how Claude AI interacts with the MotaWord MCP to surface project details in a contextual, conversational interface:

**1. Input Prompt**  
![Claude MCP Screenshot - Input](https://a.storyblok.com/f/84976/2800x2020/0ed4a39873/mcp-claude-1.png)

**2. Claude Processing View**  
![Claude MCP Screenshot - Progress](https://a.storyblok.com/f/84976/2598x1946/85ebab6b39/claude2.png)

**3. Claude Review Phase Example**  
![Claude MCP Screenshot - Review Phase](https://a.storyblok.com/f/84976/2593x1936/8d105337eb/claude3.png)

**4. Final Response with Project Details**  
![Claude MCP Screenshot - Final Output](https://a.storyblok.com/f/84976/2716x2020/7527b8374e/mcp-claude-2.png)

---

## 🏢 About MotaWord

[MotaWord](https://www.motaword.com) is a cloud-based professional translation platform that combines collaborative human translation with scalable API-driven workflows. We support over 110 languages and serve clients across legal, financial, tech, and academic sectors.

---

## 📝 License

This repository and protocol are proprietary to MotaWord. All rights reserved. Not intended for public use or distribution.

---

## 📬 Contact

- **Website:** [www.motaword.com](https://www.motaword.com)  
- **Support:** [info@motaword.com](mailto:info@motaword.com)
