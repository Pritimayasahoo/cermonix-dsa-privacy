# Privacy Policy for Cermonix

**Effective Date:** August 5, 2026  
**Extension Version:** 1.0.0

## 1. Information We Collect
Cermonix ("the Extension") collects and processes the following information strictly to provide its core functionality (AI-assisted DSA guidance and direct GitHub solution syncing):

* **AI Service Credentials (Optional):** The user may provide a Google Gemini API key to activate the AI Coach feature.
* **GitHub Personal Access Token (Optional):** The user may provide a GitHub Fine-Grained Personal Access Token (PAT) to enable one-click solution pushing to their GitHub repositories.
* **Coding Platform Context:** When active on supported competitive programming and problem-solving websites (LeetCode, GeeksforGeeks, Codeforces, and AtCoder), the Extension extracts the problem title, problem statement, current editor code, language, and submission/verdict status.
* **Chat Conversation History:** The messages exchanged with the AI Coach are temporarily held in local memory during your active session to maintain Socratic dialog context.

## 2. How We Use the Information
Collected data is used strictly for:
* Sending prompts and problem context directly to the Google Gemini API (`generativelanguage.googleapis.com`) to generate Socratic hints, edge-case analysis, and code debugging without spoiling solutions.
* Interacting directly with the official GitHub API (`api.github.com`) to list repositories, folders, create files, and commit solutions selected by the user.

**We do NOT:**
* Sell, rent, or trade your data to any third parties.
* Use your data for advertising, marketing, analytics, profiling, or credit scoring.
* Collect any personal identifying information, browsing history outside supported problem pages, or passwords.

## 3. Data Storage and Security
* **Local Storage:** All API keys, GitHub tokens, and preferences are stored exclusively on your device using Chrome's secure storage APIs (`chrome.storage.sync` / `chrome.storage.local`). GitHub tokens are encrypted locally with Web Crypto (AES-GCM 256-bit).
* **Direct HTTPS Communication:**
  - AI requests travel directly from your browser to Google's Gemini servers via HTTPS.
  - GitHub sync operations travel directly from your browser to GitHub's REST API via HTTPS.
* **Zero Backend / Zero Middleman:** We operate no intermediate proxy servers, cloud databases, or tracking services. No developer or third party intercepts your code or tokens.

## 4. Third-Party Services
* **Google Gemini API:** When using the AI Coach, your prompt context is processed under [Google's Privacy Policy](https://policies.google.com/privacy) and [Google Generative AI Terms of Service](https://policies.google.com/terms/generative-ai).
* **GitHub API:** When using GitHub Sync, repository operations are handled under [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

## 5. User Control & Data Deletion
You retain full control of your credentials at all times:
* You can modify or permanently delete your Gemini API key or disconnect your GitHub token at any moment from the in-app settings or the Options page. Deleting credentials purges them immediately from local browser storage.

## 6. Contact & Open Source
For questions, feedback, or privacy inquiries regarding Cermonix, please contact the developer via the official Chrome Web Store support listing or GitHub repository.
