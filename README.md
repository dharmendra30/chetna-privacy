# Privacy Policy for Chetna Privacy Agent

**Last Updated: October 2, 2026**

Chetna ("the Application") is built as a completely local-first, privacy-preserving local knowledge base and offline AI agent client. This software is designed from the ground up to respect user data sovereignty. 

---

### 1. Data Philosophy & Zero Cloud Transmission
The core architecture of Chetna is built on a strict **Zero-Network, Local-First** pipeline:
* **No Remote Analytics:** We do not include telemetry trackers, event tracking tools, or remote crashes frameworks.
* **No Third-Party Infrastructure:** Your textual inputs, local Markdown files, and conversational data are never transmitted to external cloud systems, remote databases, or commercial entities by this application.

### 2. Local File Scanning & Permissions
Chetna requests access to local directories strictly to read plain-text Markdown (`.md`) notes based entirely on explicit user choice. 
* **Scope of Access:** The application parses directories chosen exclusively by the user via native OS folder dialogs.
* **On-Device SQLite Cache:** File directories are converted locally into a cached schema layout stored entirely within an isolated, sandboxed **AndroidX Room SQLite database** directly inside the physical memory space of your mobile device.

### 3. Offline Artificial Intelligence Execution
Chetna interacts with localized AI environments:
* **Local Loopback Processing:** All artificial intelligence queries are structured as secure JSON payloads dispatched strictly to local network addresses (`http://127.0.0.1:11434` or local host environments).
* **No Server-Side Sub-processors:** This app does not rely on API keys routed through external generative AI cloud providers unless configured explicitly and privately by the user on their own host machinery.

### 4. Data Retention, Control, and Deletion
Because your data is never synchronized with a remote platform server or corporate cloud silo, you maintain absolute control:
* Uninstalling the Chetna application completely purges the underlying application sandbox cache, immediately removing all indexed file data logs and SQLite caches from your device hardware permanently.

---

### Contact Information
For technical feedback, architectural auditing inquiries, or support, please open an issue tracking request directly on our distribution channel workspace.
