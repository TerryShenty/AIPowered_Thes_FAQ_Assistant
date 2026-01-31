[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# AI_Powered_Thes_FAQ_Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# 🎓 学位论文提交问答咨询服务智能体 
### AI-Powered Thesis Submission FAQ Assistant

本项目是专为复旦大学学位论文提交设计的智能化咨询解决方案。采用**学生端**与**教师端**双端口独立设计，构建了“自助答疑-专家协同-知识更新”的服务闭环。

---

## 🔗 快速链接 (Quick Links)
- **👨‍🎓 学生端 Agent (Student Portal):** [点击体验](https://www.coze.cn/store/agent/7571829568286326824?bid=6iv6ue8kg1g0j)
- **👩‍🏫 教师端 Agent (Admin Portal):** [点击体验](https://www.coze.cn/s/y0q4GOcg6uc/) *(授权码：1905)*

---

## 🌟 核心功能 (Core Features)

### 1. 学生端：7×24h 自助答疑
* **精准检索**：基于大语言模型（LLM）与结构化知识库，覆盖选题、格式规范、提交流程等全场景。
* **意图引导**：自动识别非相关问题并进行引导，确保咨询服务的专注度。
* **紧急转办**：当问题超出知识库范围时，支持一键转交通过邮件联系专家。

### 2. 教师端：高效管理与知识迭代
* **待处理清单**：集中展示学生提交的疑难问题，支持按紧急程度排序。
* **一键回复**：集成邮件通知功能，教师录入答案后自动同步给学生。
* **知识入库**：教师解答的新知识可选择同步至学生端知识库，实现系统自我进化。

---

## 🛠️ 技术实现 (Tech Stack)

* **平台**: Coze (扣子)
* **大模型**: Doubao-pro-32k
* **集成服务**: 
    * **飞书 (Feishu)**：用于数据存储与问题记录。
    * **SMTP 协议**：实现自动邮件通知。
    * **RAG 架构**：通过检索增强生成确保回答的权威性。

---

## 📂 项目结构说明 (Project Structure)

由于本项目主要基于 Coze 低代码平台开发，核心逻辑体现于以下设计：

* `docs/`: 包含系统操作流程图与详细说明。
* `prompts/`: (建议上传) 存放学生端与教师端的 System Prompt 逻辑。
* `assets/`: 存放项目运行截图。

---

## 👥 团队信息 (Team)
* **团队名称**: 切问近思队
* **项目愿景**: 既降低学生信息获取门槛，又显著减轻教师重复性工作负担，推动校园服务智能化转型。

---

## 📄 许可证 (License)
本项目采用 [MIT License](LICENSE) 开源。
