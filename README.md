# MotaWord MCP (Model Context Protocol)

The **MotaWord MCP (Model Context Protocol)** is a private interface that provides structured, real-time access to translation project data. It’s designed to offer external systems (like LLMs, automation tools, or admin dashboards) context-aware visibility into the status, structure, and progress of ongoing translation jobs on the MotaWord platform.

This protocol enables seamless monitoring of translation workflows, allowing authorized systems or users to retrieve current project states—translation, review, or completion—without relying on manual updates or emails.

> ⚠️ **Note:** This is a private, closed-source repository used for documentation and reference only.

---

## 🔗 API Access

**Base URL:**

https://api.motaword.com/mcp

Authentication is required for access. Please refer to internal documentation or your API key provisioning contact for credentials.

---

## 🔐 Authentication

MCP uses token-based authentication. Tokens must be included in the request header:

Authorization: Bearer YOUR_TOKEN_HERE

To obtain credentials, contact your MotaWord integration manager or support team.

---

## 🎯 Use Cases

- Provide LLMs or middleware with real-time translation project context
- Monitor the lifecycle of a project: from creation → translation → review → delivery
- Enable dashboard visualizations or notification triggers based on live project data
- Power internal tools that need to surface project status programmatically

---

## 📦 Example Endpoints

> Full API specs are internal. Below are sample purposes for endpoints under MCP.

| Endpoint                     | Description                                                 |
|-----------------------------|-------------------------------------------------------------|
| `/mcp/projects`             | List all accessible projects with their statuses            |
| `/mcp/project/{id}`         | Get full context (status, language pairs, deadlines, etc.)  |
| `/mcp/project/{id}/timeline`| View timestamps of each workflow stage                      |

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
