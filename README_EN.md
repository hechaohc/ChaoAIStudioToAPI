# Google AI Studio to API Adapter

[中文文档](README.md) | English

ChaoAIStudioToAPI
A secondary development based on AIStudioToAPI, an API conversion tool optimized for low-profile servers.
✨ Project Features
Low resource footprint: Adapted for 4-core 4GB (4H4G) servers for stable long-term operation
Multi-account support: Supports concurrent access with 3 accounts logged in simultaneously
Stability optimizations: Fixed high resource usage, crashes, and other stability issues of the original project in low-spec environments
🚀 Quick Deployment
Environment Requirements
Server configuration: Minimum 4-core 4GB RAM
OS: Linux / Windows / macOS
Dependencies: Node.js / Python (adjust to match the original project)
Deployment Steps
Clone this repository
bash
运行
git clone https://github.com/hechaohc/ChaoAIStudioToAPI.git
cd ChaoAIStudioToAPI
Install dependencies
bash
运行
# Use the original project’s install command, e.g.:
npm install
# OR
pip install -r requirements.txt
Configure multiple accounts
Add your 3 accounts in the config file, format example:
plaintext
ACCOUNT_1=account1:password
ACCOUNT_2=account2:password
ACCOUNT_3=account3:password
Start the service
bash
运行
# Use the original project’s start command, e.g.:
node index.js
# OR
python main.py
📌 Usage
Service runs on port 7860 by default (configurable)
API format is fully compatible with the original project
3 accounts automatically poll for load balancing and improved stability
📝 Changelog
Optimized resource usage for stable 4H4G server operation
Added concurrent multi-account support (max 3 accounts)
Fixed known stability issues in the original project
❤️ Acknowledgments
This project is a secondary development based on [https://github.com/iBUHub/AIStudioToAPI]. Special thanks to the original author for their open-source contribution.
