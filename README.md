# 🧬 Discord Server Cloner Pro

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/downloads/)
[![Version: 1.2.0](https://img.shields.io/badge/Version-1.2.0-orange.svg)]()

**Server Cloner Pro** is a powerful automation tool designed to create an exact structural replica of any Discord server. It doesn't just copy names—it mirrors the entire ecosystem, including complex role hierarchies, bitwise permissions, and bot configurations.


* **Full Infrastructure Mirroring:** Recreates every Category, Text Channel, and Voice Channel with original positioning.
* **Bitwise Permission Mapping:** Copies exact "Allow" and "Deny" flags for every role across every channel.
* **Bot Template System:** Automatically detects bot-managed roles and recreates them as "Template Roles," allowing bots to regain full permissions instantly upon re-invitation.
* **@everyone Sync:** Maps the global `@everyone` settings from the source to the destination.
* **One-Click Wipe:** Features a "Wipe Destination" button to clear the target server's default channels before starting a clone.
* **Anti-Rate Limit Logic:** Built-in delays to ensure the account remains safe from Discord's API flags.


### **Modern Dark UI**
> Built with a sleek CustomTkinter interface for professional-grade performance.


### **Permission Hierarchy Logic**
> The cloner follows a strict "Top-Down" creation logic to ensure roles and channel overrides stay synchronized.


---

## 🛠️ Installation & Usage

### **Requirements**
* **Permissions:** Your account must have **Administrator** or **Manage Channels** permissions in the Destination server.
* **Tool:** Download the latest [Release](https://github.com/yourusername/repo/releases).

### **Steps to Clone**
1.  **Run** the `ServerClonerPro.exe` (Use your access password).
2.  **Input** your Discord Token and the Source/Destination IDs.
3.  **Wipe (Optional):** Click "Wipe Destination" to start with a blank canvas.
4.  **Execute:** Click "Start Full Clone" and monitor the live terminal.
5.  **Reconnect Bots:** After the script finishes, invite your bots. Assign them the "Template Roles" created by the script to instantly restore their channel-specific powers.
