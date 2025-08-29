# DevSync 
**AI-Powered Team Chat Inside Your IDE**

DevSync is a secure, collaborative chat extension for VS Code and developer IDEs — built to keep your team’s discussions, decisions, and code reviews directly in your coding environment.  
No more context-switching between Slack, Discord, and Jira. DevSync brings **AI-enhanced collaboration** where it matters most: inside your code.

---

##  Features
-  **Chat Inside Your IDE**  
  - Real-time messaging inside VS Code (extension)  
  - Private chats + team chat rooms (up to 30 people)  
  - Local Area Network (LAN) mode for secure offline communication  

-  **Collaborative AI Code Review**  
  - Share code snippets from your editor  
  - AI-assisted reviews highlight issues, suggest improvements, and summarize team feedback  

-  **AI Conversation Summaries**  
  - Automatic summaries of chat threads  
  - Capture key outcomes, decisions, and next steps  
  - Export summaries into project docs (Markdown/Confluence/Jira-ready)  

-  **Enterprise-Ready Security**  
  - Self-host option or LAN-only deployment  
  - Local database (cleared on uninstall or reinstall)  
  - AI moderation layer to keep chats safe & compliant  

-  **Lightweight by Design**  
  - Built on Python MCP server for simplicity  
  - Runs alongside existing IDE AI integrations (Claude, Copilot, Trae, etc.)  
  - Cloud-hosted option (Render) for fast startup, with future LAN/offline mode  

---

##  Getting Started

### 1. Install Extension
- [Download from VS Code Marketplace](#) *(coming soon)*  
- Or clone this repo and sideload manually.

### 2. Run the MCP Server
```bash
git clone https://github.com/your-org/devsync.git
cd devsync
pip install -r requirements.txt
python server.py
```
