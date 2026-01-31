[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Coze](https://img.shields.io/badge/Platform-Coze-4285F4.svg)](https://www.coze.cn/)
[![LLM: Doubao-pro-32k](https://img.shields.io/badge/LLM-Doubao--pro--32k-76B900.svg)](https://www.doubao.com/)
[![Coverage: 100% Thesis Scenarios](https://img.shields.io/badge/Coverage-Thesis%20Full%20Cycle-green.svg)]()
[![Response Time: 1-2 mins](https://img.shields.io/badge/Response-1--2%20mins-blue.svg)]()

# 🎓 学位论文提交问答咨询服务智能体
### AI-Powered Thesis Submission FAQ Assistant for Fudan University

> 「自助答疑+专家协同+知识进化」的校园服务智能化解决方案，让论文提交咨询更高效、更省心。

---

## 📌 项目背景与核心价值
### 🔍 解决的痛点
高校学位论文提交阶段，传统人工咨询模式面临三大核心问题：
- **负荷沉重**：年咨询量 3000+ 人次，高峰期（5/6/12月）日均 30+ 咨询，80% 为复杂问题，人工解决耗时 5-30 分钟/个；
- **重复与新增挑战**：同类问题日均重复 10+ 次，系统更新导致大量新问题，人工经验难以快速覆盖；
- **时效不足**：依赖工作时间响应，无法满足学生 7×24h 咨询需求，响应延迟影响办事效率。

### ✨ 核心价值
- 学生：**零等待获取精准答案**，非工作时段也能解决问题，复杂问题可快速对接专家；
- 教师：**减少 80%-90% 重复性咨询**，聚焦疑难问题处理，知识库自动迭代无需手动维护；
- 校园：构建数据驱动的治理新模式，推动校务服务从“人工响应”向“智能预判”转型。

---

## 🔗 快速体验 (Quick Links)
| 角色       | 访问链接                                                                 | 说明                     |
|------------|--------------------------------------------------------------------------|--------------------------|
| 学生 (Student) | [学生端 Agent](https://www.coze.cn/store/agent/7571829568286326824?bid=6iv6ue8kg1g0j)          | 无需授权，直接提问       |
| 教师 (Admin)  | [教师端 Agent](https://www.coze.cn/s/y0q4GOcg6uc/)          | 授权码：1905（身份验证） |
| 问题展示 (Demo) | [飞书文档 Lark](https://l0s0bl6jrtd.feishu.cn/base/NfyFbN7IjaDuWms9EHjcxqM9nkf?table=tbltllZDLnKW1K0E&view=vewm0vrJC6) | 快速预览所有问题并手动修改状态         |

---

## 🎯 核心功能 (Core Features)
### 👨‍🎓 学生端：7×24h 自助答疑
| 功能                | 细节描述                                                                 |
|---------------------|--------------------------------------------------------------------------|
| 全场景覆盖          | 支持论文选题、格式规范、提交流程、系统操作等全生命周期问题咨询；         |
| 精准智能检索        | 基于 RAG 架构+结构化知识库，大模型精准匹配答案，避免无效回复；           |
| 意图智能引导        | 自动识别非论文相关问题，引导聚焦核心咨询场景，提升服务效率；             |
| 紧急问题转办        | 未命中知识库的问题，可标记紧急程度+预留邮箱，自动转交教师端跟进；         |
| 历史记录追溯        | 保存过往咨询记录，方便学生二次查阅，避免重复提问。                       |
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/学生1.png" width="600" />
  <br/>
  <sub>图 1：学生端智能问答启动台</sub>
  
</div>
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/学生2.png" width="600" />
  <br/>
  <sub>图 2：回答知识库中已包含的问题</sub>
</div>
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/学生3.png" width="600" />
  <br/>
  <sub>图 3：回答知识库中未包含的问题</sub>
</div>
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/学生4.png" width="600" />
  <br/>
  <sub>图 4：设置紧急程度并添加邮件联系方式</sub>
</div>



### 👩‍🏫 教师端：高效管理与知识迭代
| 功能                | 细节描述                                                                 |
|---------------------|--------------------------------------------------------------------------|
| 待处理问题清单      | 按“紧急程度+提问时间”排序，集中展示未解答问题，一目了然；                 |
| 一键回复与通知      | 录入答案后，系统自动生成标准化邮件发送给学生，无需手动编辑；             |
| 知识库实时更新      | 可选择将优质答案同步至学生端知识库，实现“解答一次，永久复用”；           |
| 操作全程可追溯      | 问题处理记录同步至飞书，支持数据复盘与合规审计；                         |
| 权限安全校验        | 4位授权码（1905）验证身份，保障学术管理权限不泄露。                     |
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/老师2.png" width="600" />
  <br/>
  <sub>图 5：教师端验证并自动遍历飞书表格中未回答的问题</sub>
</div>
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/老师2.png" width="600" />
  <br/>
  <sub>图 6：教师回答问题、选择是否添加到知识库中并自动向学生发送邮件</sub>
</div>
<br/>
<div align="center" style="margin-bottom: 40px;">
  <img src="assets/邮件.png" width="300" />
  <br/>
  <sub>图 7：自动回复邮件内容展示</sub>
</div>
<br/>
<div align="center">
  <img src="assets/飞书.png" width="600" />
  <br/>
  <sub>图 8：飞书表格问题回答内容与状态自动更新</sub>
</div>



### 🔄 服务闭环：从自助到专家的无缝衔接
```mermaid
graph LR
A[学生提问] --> B{知识库命中？}
B -->|是| C[1-2分钟智能回复]
B -->|否| D[标记紧急程度+留邮箱]
D --> E[教师端接收待处理任务]
E --> F[教师解答+选择是否入库]
F --> G[邮件通知学生]
F -->|入库| H[知识库更新]
H --> B[下次同类问题自动解答]
