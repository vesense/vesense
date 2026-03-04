# SOTA Large Language Models by Category (2026)

> 当前不同类型的 SOTA 大模型汇总 | Last updated: March 2026

---

## 📋 目录

- [通用对话模型](#通用对话模型)
- [代码专用模型](#代码专用模型)
- [多模态模型](#多模态模型)
- [长上下文模型](#长上下文模型)
- [开源/可本地部署模型](#开源可本地部署模型)
- [垂直领域模型](#垂直领域模型)

---

## 通用对话模型

| 模型 | 公司 | 上下文 | 特点 |
|------|------|--------|------|
| **GPT-4.1 / GPT-4o** | OpenAI | 128K | 多模态支持，工具调用，实时响应 |
| **Claude 3.7 Sonnet** | Anthropic | 200K | 强推理能力，代码生成，安全性高 |
| **Gemini 2.0 Pro** | Google | 1M+ | 原生多模态，长上下文，Google 生态集成 |
| **Grok-3** | xAI | 128K | 实时 X 数据访问，推理优化 |
| **Qwen 2.5 Max** | 阿里云 | 256K | 中文优化，多语言支持，代码能力 |
| **DeepSeek-V3** | 深度求索 | 128K | MoE 架构，高性能推理 |

---

## 代码专用模型

| 模型 | 公司 | 上下文 | 特点 |
|------|------|--------|------|
| **Claude 3.7 Sonnet** | Anthropic | 200K | 综合代码能力最强 |
| **GPT-4.1** | OpenAI | 128K | 多语言支持，调试能力强 |
| **Gemini Codey 2.0** | Google | 128K | Google 生态集成 |
| **CodeQwen 2.5** | 阿里云 | 128K | 中文注释友好 |
| **DeepSeek Coder V2** | 深度求索 | 128K | 开源，多语言支持 |
| **StarCoder2-15B** | BigCode | 16K | 开源，可本地部署 |
| **Cursor AI** | Cursor | - | IDE 集成，上下文感知 |

---

## 多模态模型

| 模型 | 公司 | 输入 | 输出 | 特点 |
|------|------|------|------|------|
| **GPT-4o** | OpenAI | 文本 + 图像 + 音频 | 文本 + 图像 | 实时语音对话 |
| **Gemini 2.0** | Google | 文本 + 图像 + 视频 | 文本 + 图像 | 视频理解最强 |
| **Claude 3.7** | Anthropic | 文本 + 图像 | 文本 | 图像分析准确 |
| **Qwen2.5-VL** | 阿里云 | 文本 + 图像 | 文本 + 图像 | 中文 OCR 优化 |
| **LLaVA-NeXT** | 开源社区 | 文本 + 图像 | 文本 | 开源可部署 |

---

## 长上下文模型

| 模型 | 公司 | 上下文 | 特点 |
|------|------|--------|------|
| **Gemini 2.0 Pro** | Google | 1M+ tokens | 最长上下文，视频分析 |
| **Claude 3.7 Sonnet** | Anthropic | 200K tokens | 长文档理解最佳 |
| **Qwen 2.5 Max** | 阿里云 | 256K tokens | 中文长文档优化 |
| **GPT-4.1 Turbo** | OpenAI | 128K tokens | 平衡性能与成本 |
| **Jamba 1.5** | AI21 Labs | 256K tokens | 混合架构，高效 |

---

## 开源/可本地部署模型

| 模型 | 参数量 | 上下文 | 许可证 | 特点 |
|------|--------|--------|--------|------|
| **Llama 3.3 70B** | 70B | 128K | Llama License | 综合最强开源 |
| **Llama 3.3 8B** | 8B | 128K | Llama License | 轻量级，可消费级 GPU |
| **Qwen 2.5 72B** | 72B | 128K | Apache 2.0 | 中文优化，商用友好 |
| **Qwen 2.5 32B** | 32B | 128K | Apache 2.0 | 性能/资源平衡 |
| **DeepSeek-V3** | 671B (MoE) | 128K | MIT | MoE 架构，高效 |
| **Mistral Large 2** | 123B | 128K | Proprietary | 欧洲模型，多语言 |
| **Command R+** | 104B | 128K | CC-BY-NC | RAG 优化 |

### 小型可本地部署模型

| 模型 | 参数量 | 推荐用途 |
|------|--------|----------|
| **Llama 3.2 3B** | 3B | 边缘设备，移动端 |
| **Qwen 2.5 7B** | 7B | 消费级 GPU |
| **Phi-3.5 Mini** | 3.8B | 微软出品，轻量高效 |
| **Gemma 2 9B** | 9B | Google 出品，研究友好 |

---

## 垂直领域模型

### 医疗

| 模型 | 公司 | 特点 |
|------|------|------|
| **Med-PaLM 2** | Google | 医疗问答，临床支持 |
| **HuatuoGPT** | 开源 | 中医领域，中文优化 |

### 法律

| 模型 | 公司 | 特点 |
|------|------|------|
| **Law Llama** | 开源 | 法律问答，案例检索 |
| **ChatLaw** | 开源 | 中文法律咨询 |

### 金融

| 模型 | 公司 | 特点 |
|------|------|------|
| **BloombergGPT** | Bloomberg | 金融数据，市场洞察 |
| **FinGPT** | 开源 | 金融分析，情感预测 |

### 科学/研究

| 模型 | 公司 | 特点 |
|------|------|------|
| **Galactica** | Meta | 科学论文，公式推导 |
| **SciLLM** | 开源 | 科学文献理解 |

---

## 模型选择建议

### 企业生产环境
- **首选**: Claude 3.7 Sonnet / GPT-4.1
- **理由**: 稳定性高，API 成熟，安全合规

### 成本敏感场景
- **首选**: Qwen 2.5 32B / Llama 3.3 70B (自部署)
- **理由**: 开源许可证友好，可控制成本

### 中文场景
- **首选**: Qwen 2.5 Max / DeepSeek-V3
- **理由**: 中文理解最佳，本地化支持

### 代码开发
- **首选**: Claude 3.7 Sonnet / Cursor AI
- **理由**: 代码理解深，IDE 集成好

### 长文档处理
- **首选**: Gemini 2.0 Pro / Claude 3.7
- **理由**: 上下文最长，检索准确

---

## 参考资源

- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
- [LMSys Chatbot Arena](https://chat.lmsys.org/)
- [Papers With Code - LLM](https://paperswithcode.com/task/large-language-models)

---

*本文档持续更新，欢迎贡献 | Maintained by @vesense*
