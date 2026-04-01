# ai-agent-deep-dive-report

1OpenAPI.com
⼤模型API：1OpenAPI.com

https://github.com/thinker007/ai-agent-deep-dive-report

这次到底研究了什么
这次不是只看某一个 prompt 文件，也不是只做“目录级扫一眼”。这次研究的核心，是把公开
发布包中可分析的信息整理成系统性研究材料，并沿着以下主线做拆解：
‧ Claude Code 的整体架构
‧ 主系统提示词如何动态拼装
‧ AgentTool / SkillTool 的模型侧协议
‧ built‑in agents 的角色分工
‧ Agent 调度链路如何跑通
‧ Plugin / Skill / Hook / MCP 如何接入并影响运行时
‧ Permission / Tool execution / Hook decision 如何协同
‧ 它为什么在体验上比“普通 LLM + 工具调用器”强很多
