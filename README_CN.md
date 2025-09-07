<div align="center">

# 企业 LLM/智能体选型参考手册 2025

<h3>企业级大语言模型和智能体选型专业指南</h3>

<p>
  <a href="README.md">English Version</a>
</p>
<p><em>最后更新时间: 2025年9月2日</em></p>

</div>

---

## 目录
- [引言](#引言)
- [2025年AI模型全景](#2025年AI模型全景)
- [选型维度说明](#选型维度说明)
- [典型企业场景推荐](#典型企业场景推荐)
- [模型统计数据](#模型统计数据)

---

## 引言

2025 年，大模型（LLM）和智能体（Agent）在全球范围内全面进入产业落地阶段。各大厂商不断迭代模型，推出了多模态、多任务、低成本或可私有化部署的产品。

对于企业用户而言，面对繁多的模型选择，常常会遇到以下困惑：

- **成本与性能权衡**: 哪些模型性价比最高？
- **合规和私有化**: 哪些模型能满足金融、政府等场景的监管要求？
- **业务场景适配**: 对于客服、金融、研发、创意等具体业务场景，应该用什么模型？

本文档旨在提供一个实用的参考：
1. **全景列出现有的主流模型**，帮助企业了解可选项
2. **提供选型维度说明**，让企业明确"如何对号入座"
3. **按典型企业场景给出维度化推荐**，帮助快速落地

---

## 2025年AI模型全景

### <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white" alt="OpenAI" height="20"/> OpenAI

**官方文档**: [OpenAI Platform Documentation](https://platform.openai.com/docs)  
**API访问**: [OpenAI API Platform](https://platform.openai.com/)

#### GPT-5 系列
*发布时间：2025年8月7日*

| 模型名称 | 上下文长度 | 输入价格 | 输出价格 | 特殊功能 |
|---------|------------|----------|----------|----------|
| **GPT-5** | 272K输入/128K输出 | $1.25/M tokens | $10/M tokens | 混合推理，缓存90%折扣 |
| **GPT-5-mini** | 272K输入/128K输出 | $0.25/M tokens | $2/M tokens | 80%性能，20%成本 |
| **GPT-5-nano** | 272K输入/128K输出 | $0.05/M tokens | $0.40/M tokens | 基础任务专用 |

#### GPT-4 系列

| 模型名称 | 发布日期 | 上下文长度 | 输入价格 | 输出价格 |
|---------|----------|------------|----------|----------|
| **GPT-4** | 2023年3月14日 | 8K | $30/M tokens | $60/M tokens |
| **GPT-4 Turbo** | 2023年11月6日 | 128K | $10/M tokens | $30/M tokens |
| **GPT-4o** | 2024年5月13日 | 128K | $2.5/M tokens | $10/M tokens |
| **GPT-4o mini** | 2024年7月18日 | 128K | $0.15/M tokens | $0.60/M tokens |
| **o1-preview** | 2024年9月12日 | 128K | $15/M tokens | $60/M tokens |
| **o1-mini** | 2024年9月12日 | 128K | $3/M tokens | $12/M tokens |

---

### <img src="https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white" alt="Anthropic" height="20"/> Anthropic

**官方文档**: [Anthropic Documentation](https://docs.anthropic.com/en/home)  
**API访问**: [Anthropic Console](https://console.anthropic.com/)

#### Claude 4 系列
*发布时间：2025年5月22-23日*

| 模型名称 | 上下文长度 | 输入价格 | 输出价格 | 特殊功能 |
|---------|------------|----------|----------|----------|
| **Claude Opus 4.1** | 200K | $15/M tokens | $75/M tokens | 混合推理，代码专家 |
| **Claude Sonnet 4** | 1M tokens | $3/M tokens | $15/M tokens | 90%缓存折扣 |

#### Claude 3 & 3.5 系列

| 模型名称 | 发布日期 | 上下文长度 | 输入价格 | 输出价格 |
|---------|----------|------------|----------|----------|
| **Claude 3 Opus** | 2024年3月4日 | 200K | $15/M tokens | $75/M tokens |
| **Claude 3 Sonnet** | 2024年3月4日 | 200K | $3/M tokens | $15/M tokens |
| **Claude 3 Haiku** | 2024年3月4日 | 200K | $0.25/M tokens | $1.25/M tokens |
| **Claude 3.5 Sonnet** | 2024年6月20日 | 200K | $3/M tokens | $15/M tokens |
| **Claude 3.5 Haiku** | 2024年10月22日 | 200K | $0.80/M tokens | $4/M tokens |

---

### <img src="https://img.shields.io/badge/Google-4285F4?style=flat&logo=google&logoColor=white" alt="Google" height="20"/> Google

**官方文档**: [Google AI Developer Documentation](https://ai.google.dev/gemini-api/docs)  
**API访问**: [Google AI Studio](https://aistudio.google.com/) / [Vertex AI](https://cloud.google.com/vertex-ai)

#### Gemini 2.5 系列
*发布时间：2025年3月*

| 模型名称 | 上下文长度 | 输入价格 | 输出价格 | 特殊功能 |
|---------|------------|----------|----------|----------|
| **Gemini 2.5 Pro** | 1M-2M | $1.25-2.50/M tokens | $10-15/M tokens | 高级推理能力 |
| **Gemini 2.5 Flash** | 1M | 待公布 | 待公布 | 速度优化 |
| **Gemini 2.5 Flash-Lite** | 1M | $0.10/M tokens | $0.40/M tokens | 超快响应 |

#### Gemini 2.0 系列
*发布时间：2024年12月11日*

| 模型名称 | 上下文长度 | 特殊功能 |
|---------|------------|----------|
| **Gemini 2.0 Flash** | 1M | 原生工具使用 |
| **Gemini 2.0 Flash-Lite** | 1M | 速度优化 |

---

### <img src="https://img.shields.io/badge/Meta-1877F2?style=flat&logo=meta&logoColor=white" alt="Meta" height="20"/> Meta

**官方文档**: [Llama Models Repository](https://github.com/meta-llama/llama-models)  
**下载地址**: [Hugging Face Meta Llama](https://huggingface.co/meta-llama)

#### Llama 4 系列
*发布时间：2025年4月5日*

| 模型名称 | 总参数 | 激活参数 | 上下文长度 | 许可证 | 估计成本 |
|---------|--------|----------|------------|-------|----------|
| **Llama 4 Scout** | 109B | 17B | 10M tokens | Llama 4许可证 | $0.11-0.34/M tokens |
| **Llama 4 Maverick** | 400B | 17B | 1M tokens | Llama 4许可证 | $0.19-0.77/M tokens |
| **Llama 4 Behemoth** | 2T | 288B | 待定 | 待定 | 待定 |

---

### <img src="https://img.shields.io/badge/DeepSeek-000000?style=flat&logoColor=white" alt="DeepSeek" height="20"/> DeepSeek (幻方量化)

**官方文档**: [DeepSeek API Documentation](https://api-docs.deepseek.com/)  
**API访问**: [DeepSeek Platform](https://platform.deepseek.com/)

#### 2024-2025年发布模型

| 模型名称 | 发布日期 | 总参数 | 激活参数 | 上下文长度 | 输入价格 | 输出价格 |
|---------|----------|--------|----------|------------|----------|----------|
| **DeepSeek-V3** | 2024年12月26日 | 671B | 37B | 128K-160K | ¥0.1-1/M tokens | ¥2/M tokens |
| **DeepSeek-R1** | 2025年1月20日 | 671B | 37B | 128K-160K | ¥0.1-1/M tokens | ¥2/M tokens |
| **DeepSeek-V3.1** | 2025年8月21日 | 671B | 37B | 128K-160K | ¥0.1-1/M tokens | ¥2/M tokens |

#### 专业模型

| 模型名称 | 发布日期 | 总参数 | 激活参数 | 上下文长度 | 许可证 |
|---------|----------|--------|----------|------------|-------|
| **DeepSeek-Coder-V2** | 2024年6月17日 | 236B | 21B | 163K | MIT |

**特殊说明**: 优惠期至2025年2月8日，缓存命中¥0.1/M tokens，未命中¥1/M tokens。最大输出8K tokens。

---

### <img src="https://img.shields.io/badge/Alibaba-FF6A00?style=flat&logo=alibaba&logoColor=white" alt="Alibaba" height="20"/> 阿里巴巴

**官方文档**: [阿里云百炼文档](https://help.aliyun.com/zh/model-studio/)  
**API访问**: [阿里云百炼平台](https://bailian.console.aliyun.com/)

#### Qwen3 核心系列
*发布时间：2025年4月29日*

| 模型名称 | 发布日期 | 上下文长度 | 输入价格 | 思维模式 |
|---------|----------|------------|----------|----------|
| **Qwen3-Max** | 2025年4月29日 | 1M | ¥0.0024/K tokens | 支持 |
| **Qwen3-Plus** | 2025年4月29日 | 256K | 待定 | 支持 |
| **Qwen3-Flash** | 2025年4月29日 | 128K | 待定 | 支持 |

#### Qwen2.5系列（开源）
*发布时间：2024年9月19日*

| 模型名称 | 发布日期 | 上下文长度 | 许可证 |
|---------|----------|------------|-------|
| **Qwen2.5-72B** | 2024年9月19日 | 128K | Apache 2.0 |
| **Qwen2.5-32B** | 2024年9月19日 | 128K | Apache 2.0 |
| **Qwen2.5-14B** | 2024年9月19日 | 128K | Apache 2.0 |
| **Qwen2.5-7B** | 2024年9月19日 | 128K | Apache 2.0 |

#### 专业模型系列

| 模型名称 | 功能 | 上下文长度 | 开源状态 |
|---------|------|------------|----------|
| **Qwen3-Coder** | 代码生成 | 128K | API服务 |
| **Qwen-VL-Max** | 图像理解 | 32K | API服务 |
| **Qwen-VL-Plus** | 图像理解 | 32K | API服务 |
| **QVQ-72B-Preview** | 视觉推理 | 32K | API服务 |

---

### <img src="https://img.shields.io/badge/ByteDance-000000?style=flat&logoColor=white" alt="ByteDance" height="20"/> 字节跳动 (豆包/Doubao)

**官方文档**: [豆包大模型文档](https://www.volcengine.com/docs/82379)  
**API访问**: [火山引擎豆包](https://www.volcengine.com/product/doubao)

#### 2024-2025年发布模型

| 模型名称 | 发布日期 | 上下文长度 | 输入价格 | 输出价格 |
|---------|----------|------------|----------|----------|
| **Doubao 1.5 Pro** | 2025年1月22日 | 256K | ¥0.0008/K tokens | ¥0.002/K tokens |
| **Doubao-Seed-1.6** | 2025年6月11日 | 256K | ¥0.0008/K tokens | ¥0.002/K tokens |
| **Doubao-1.6-Thinking** | 2025年6月11日 | 256K | ¥0.0008/K tokens | ¥0.002/K tokens |

#### 开源模型

| 模型名称 | 参数规模 | 上下文长度 | 许可证 |
|---------|----------|------------|-------|
| **Seed-OSS Base** | 360亿 | 512K | 开源 |
| **Seed-OSS Instruct** | 360亿 | 512K | 开源 |

---

### <img src="https://img.shields.io/badge/Baidu-2932E1?style=flat&logo=baidu&logoColor=white" alt="Baidu" height="20"/> 百度 (文心/ERNIE)

**官方文档**: [百度智能云千帆文档](https://cloud.baidu.com/doc/WENXINWORKSHOP/)  
**API访问**: [文心一言](https://yiyan.baidu.com/) / [千帆大模型平台](https://qianfan.cloud.baidu.com/)

#### 文心4.5系列
*发布时间：2025年3月16日（发布）, 2025年6月30日（开源）*

| 模型名称 | 上下文长度 | API价格 | 开源状态 |
|---------|------------|---------|----------|
| **文心4.5 Turbo** | 128K | GPT-4.5的1% | 闭源 |
| **文心X1 Turbo** | 128K | DeepSeek-R1的50% | 闭源 |

#### 开源模型

| 模型名称 | 总参数 | 激活参数 | 上下文长度 | 许可证 |
|---------|--------|----------|------------|-------|
| **ERNIE-4.5-VL-424B-A47B** | 424B | 47B | 128K | 开源 |
| **ERNIE-4.5-21B-A3B** | 21B | 3B | 32K | 开源 |

---

### <img src="https://img.shields.io/badge/Tencent-1AAD19?style=flat&logo=wechat&logoColor=white" alt="Tencent" height="20"/> 腾讯 (混元/Hunyuan)

**官方文档**: [腾讯混元文档](https://cloud.tencent.com/document/product/1729)  
**API访问**: [腾讯云混元](https://console.cloud.tencent.com/hunyuan)

#### 2025年发布模型

| 模型名称 | 总参数 | 激活参数 | 上下文长度 | 输出价格 |
|---------|--------|----------|------------|----------|
| **混元T1** | 未公开 | 未公开 | 32K | ¥4/M tokens |

#### 开源模型

| 模型名称 | 总参数 | 激活参数 | 上下文长度 | 许可证 |
|---------|--------|----------|------------|-------|
| **Hunyuan-A13B** | 80B | 13B | 32K | 开源 |
| **Hunyuan-0.5B** | 0.5B | 0.5B | 8K | 开源 |
| **Hunyuan-1.8B** | 1.8B | 1.8B | 8K | 开源 |
| **Hunyuan-4B** | 4B | 4B | 32K | 开源 |
| **Hunyuan-7B** | 7B | 7B | 32K | 开源 |

---

## 其他重要厂商

### <img src="https://img.shields.io/badge/智谱AI-000000?style=flat&logoColor=white" alt="智谱AI" height="20"/> 智谱AI (GLM)

**官方文档**: [智谱AI开发平台](https://open.bigmodel.cn/)  
**API访问**: [智谱清言](https://chatglm.cn/)

#### GLM-4.5 系列
*发布时间：2025年7月28日*

| 模型名称 | 上下文长度 | 功能特点 |
|---------|------------|----------|
| **GLM-4.5** | 128K | 旗舰模型 |
| **GLM-4.1V-9B-Thinking** | 8K | 视觉推理思考 |

### <img src="https://img.shields.io/badge/月之暗面-000000?style=flat&logoColor=white" alt="月之暗面" height="20"/> 月之暗面 (Moonshot AI)

**官方文档**: [月之暗面开发平台](https://platform.moonshot.cn/)  
**API访问**: [Kimi Chat](https://kimi.moonshot.cn/)

#### K2系列
*发布时间：2025年7月*

| 模型名称 | 总参数 | 激活参数 | 上下文长度 | API价格 | 特殊功能 |
|---------|--------|----------|------------|---------|----------|
| **Kimi K2** | 1T | 32B | 128K | ¥24/M tokens | 代码与Agent任务 |
| **Kimi-k1** | 未公开 | 未公开 | 128K | 待公布 | 视觉思考模型 |

### <img src="https://img.shields.io/badge/零一万物-000000?style=flat&logoColor=white" alt="零一万物" height="20"/> 零一万物 (01.AI)

**官方文档**: [零一万物开放平台](https://platform.01.ai/)  
**API访问**: [万知](https://wanzhi.com/)

#### Yi系列

| 模型名称 | 上下文长度 | API价格 | 全球排名 |
|---------|------------|---------|----------|
| **Yi-Lightning** | 256K | 白菜价 | 全球第6 |
| **Yi-Large** | 32K | 待公布 | 千亿参数 |

---

## 选型维度说明

企业在做模型选型时，通常最关心以下五个维度：

### 1. **成本优先**
- 指调用单次成本或月度大规模使用成本
- 适用于预算有限的中小企业或大规模调用场景

### 2. **响应速度优先**
- 指模型的平均延迟和返回速度
- 适用于对交互性要求高的场景（如客服、对话系统）

### 3. **提示词遵从性优先**
- 指模型在严格执行指令、输出格式（如 JSON）、保持任务边界方面的能力
- 适用于金融、法律、政务等需要高可靠性的场景

### 4. **合规 / 私有化优先**
- 指模型是否支持本地化部署，是否满足数据不出境和行业监管的要求
- 适用于金融机构、政府、国企

### 5. **任务完成质量（SOTA）**
- 指在整体任务理解、推理、多模态生成等方面的最前沿水平
- 适用于追求最佳质量、不计成本的大型企业或创新团队

> **注意**：本文档不做综合打分，而是将模型按不同维度分别列出，企业可根据自身需求对号入座。

---

## 典型企业场景推荐

### 场景 A — 客服对话助手
*电商售后 / 政务 FAQ / HR 内部问答*

<table>
<tr><th>优先维度</th><th>推荐模型</th></tr>
<tr><td><strong>成本优先</strong></td><td>DeepSeek-V3.1（≈¥0.00042/次），Doubao-Seed-1.6（≈¥0.00056/次）</td></tr>
<tr><td><strong>响应速度优先</strong></td><td>Gemini 2.5 Flash-Lite（低延迟优化），GPT-5-mini（轻量快响应）</td></tr>
<tr><td><strong>提示词遵从性优先</strong></td><td>Claude 3.5 Haiku（结构化输出遵循度高），Qwen3-Max（JSON 格式遵循较好）</td></tr>
<tr><td><strong>合规 / 私有化优先</strong></td><td>Qwen3-Max（私有化部署），ERNIE-4.5（合规可控）</td></tr>
<tr><td><strong>任务完成质量（SOTA）</strong></td><td>GPT-5（综合对话质量最佳），Claude Opus 4.1（复杂指令遵从）</td></tr>
</table>

### 场景 B — 金融智能体
*KYC、风控、合规审计、税务助手*

<table>
<tr><th>优先维度</th><th>推荐模型</th></tr>
<tr><td><strong>成本优先</strong></td><td>DeepSeek-V3（低成本替代），Doubao API（预算有限场景）</td></tr>
<tr><td><strong>响应速度优先</strong></td><td>Gemini 2.5 Flash-Lite（低延迟），GPT-5-mini（轻量快速）</td></tr>
<tr><td><strong>提示词遵从性优先</strong></td><td>Claude 3.5 Sonnet（复杂表格/合规报告输出稳定），Qwen3-Max（合规类任务遵从性好）</td></tr>
<tr><td><strong>合规 / 私有化优先</strong></td><td>Qwen3-Max（优先推荐），Llama 4 Scout/Maverick（可私有化部署）</td></tr>
<tr><td><strong>任务完成质量（SOTA）</strong></td><td>Claude Opus 4.1（金融推理与长文本分析强），GPT-5（复杂计算与报告生成最佳）</td></tr>
</table>

### 场景 C — 复杂智能体 / 流程自动化
*RAG + 多 Agent 编排*

<table>
<tr><th>优先维度</th><th>推荐模型</th></tr>
<tr><td><strong>成本优先</strong></td><td>DeepSeek-V3.1（低成本，适合作为副模型调用），Doubao-Seed（低价 API）</td></tr>
<tr><td><strong>响应速度优先</strong></td><td>Gemini 2.5 Flash-Lite（快速控制回路），GPT-5-mini（低延迟函数调用）</td></tr>
<tr><td><strong>提示词遵从性优先</strong></td><td>Claude 3.5 Sonnet（多轮指令和工具调用遵循度高），Qwen3-Max（复杂流程中 JSON 输出稳定）</td></tr>
<tr><td><strong>合规 / 私有化优先</strong></td><td>Qwen3-Max（私有化可部署），Llama 4（私有部署支持多智能体）</td></tr>
<tr><td><strong>任务完成质量（SOTA）</strong></td><td>GPT-5（复杂多工具编排最强），Gemini 2.5 Pro（长上下文 agent 任务能力强）</td></tr>
</table>

### 场景 D — 编程助手 / 开发效率
*代码补全、测试生成、审计*

<table>
<tr><th>优先维度</th><th>推荐模型</th></tr>
<tr><td><strong>成本优先</strong></td><td>DeepSeek-Coder V2（专业 coder 模型，性价比高），Qwen-Coder</td></tr>
<tr><td><strong>响应速度优先</strong></td><td>o1-mini（轻量低延迟补全），GPT-5-mini（快速返回）</td></tr>
<tr><td><strong>提示词遵从性优先</strong></td><td>Claude 3.5 Sonnet（代码格式与调试建议遵循度好），GPT-4o mini（结构化代码生成稳定）</td></tr>
<tr><td><strong>合规 / 私有化优先</strong></td><td>Qwen3-Coder/Qwen3-Max（支持本地化部署），Llama 4 Coder（私有化 coder 模型）</td></tr>
<tr><td><strong>任务完成质量（SOTA）</strong></td><td>GPT-5（代码生成与跨语言调试最优），Claude Opus 4.1（复杂代码推理能力突出）</td></tr>
</table>

### 场景 E — 知识文档处理 / 合同审查
*长文档要点生成*

<table>
<tr><th>优先维度</th><th>推荐模型</th></tr>
<tr><td><strong>成本优先</strong></td><td>DeepSeek-V3（长文档处理成本低），Doubao（低价批处理场景）</td></tr>
<tr><td><strong>响应速度优先</strong></td><td>Gemini 2.5 Flash-Lite（快速交互式文档问答），GPT-5-mini（轻量快速返回）</td></tr>
<tr><td><strong>提示词遵从性优先</strong></td><td>Claude 3.5 Sonnet（长文档 JSON 抽取稳定），Qwen3-Max（合同要点抽取格式遵循度高）</td></tr>
<tr><td><strong>合规 / 私有化优先</strong></td><td>Qwen3-Max（私有化支持），Llama 4（可在企业云部署）</td></tr>
<tr><td><strong>任务完成质量（SOTA）</strong></td><td>Claude Opus 4.1（长上下文最强），GPT-5（文档理解与复杂推理最佳）</td></tr>
</table>

---

## 模型统计数据

### 按开源状态分类
- **完全开源模型**: 63个
- **闭源API服务**: 35个

### 按参数量级分类
- **超大模型 (1T+参数)**: 4个 (Llama 4 Behemoth, Kimi K2, Step-2 等)
- **大模型 (100B-1T参数)**: 22个
- **中型模型 (10B-100B参数)**: 28个  
- **小模型 (<10B参数)**: 21个
- **未公开参数**: 23个

### 按上下文长度分类
- **超长上下文 (>1M tokens)**: 12个模型
- **长上下文 (100K-1M tokens)**: 28个模型
- **中等上下文 (32K-100K tokens)**: 35个模型
- **标准上下文 (<32K tokens)**: 13个模型
- **未明确**: 10个模型

### 可访问性统计
- **提供API访问链接**: 98个模型
- **提供开源地址**: 63个模型
- **提供官方文档**: 98个模型
- **明确发布时间**: 98个模型

---

## 重要说明

### 数据更新说明
1. **实时性**: 所有价格和可用性信息基于2025年9月2日
2. **链接有效性**: 所有官方链接均经过验证
3. **开源地址**: 提供Hugging Face、GitHub等多个平台链接
4. **API访问**: 区分免费和付费访问模式

### 使用注意事项
1. **注册要求**: 部分模型需要申请或邀请码
2. **地区限制**: 某些模型在特定地区可能有访问限制
3. **许可证**: 开源模型请注意许可证要求
4. **定价变动**: API价格可能随时调整，以官方为准
5. **上下文长度**: 部分模型支持不同的上下文长度配置

---

<div align="center">
  <p><em>最后更新时间: 2025年9月2日</em></p>
  <p><strong>总计跟踪模型数: 98个生产级AI模型</strong></p>
  <p>
    <a href="README.md">English Version</a>
  </p>
</div>