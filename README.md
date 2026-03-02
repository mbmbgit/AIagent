---

## 🤖 AI Issue Responder (Demo)

このリポジトリでは、GitHub ActionsとGemini 2.5 Pro APIを連携させた **AI自動応答システム** を稼働させています。
This repository features an **AI Auto-Response System** powered by GitHub Actions and the Gemini 1.5 Flash API.

### 🛠 使い方と仕様 (How it Works)

1. **Issueを作成またはコメントする (Create or Comment on an Issue)**
   - Issueを立てるか、既存のIssueにコメントをすると、私のAIアシスタント（萬俵AI）が自動で返信します。
   - My AI assistant will automatically respond when you open a new issue or post a comment.
   -https://github.com/mbmbgit/Professional-Resume-AIagent/issues/1
2. **多言語対応 (Multilingual Support)**
   - **日本語で入力すると日本語で**、**English inputs will be answered in English**. 
   - ユーザーが使用した言語をAIが自動で判別し、最適な言語で回答します。
   - The AI detects your language and responds accordingly.

3. **応答時間 (Response Time)**
   - GitHub Actionsの起動とAIの処理を含め、返信まで **通常15秒ほど** かかります。
   - It usually takes about **15 seconds** for the AI to respond, including the workflow trigger and processing time.

### 💡 開発の背景 (Purpose)
このシステムは、単なる自動応答ボットではありません。プロンプトの微調整（Prompt Engineering）による回答精度の向上や、安全性（Safety Settings）の確保、そしてGitHub Actionsを用いた効率的なIssue-opsの実践を目的として研究・運用しています。

This system is a playground for **Prompt Engineering** and **Issue-ops**. I continuously optimize the prompts to ensure high-quality, safe, and context-aware interactions.
