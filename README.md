# MinerU 用户手册

<div align="center">
  <img src="https://opendatalab.github.io/MinerU/images/MinerU-logo.png" width="300px" alt="MinerU Logo">
</div>




[![stars](https://img.shields.io/github/stars/opendatalab/MinerU.svg)](https://github.com/opendatalab/MinerU)
[![arXiv](https://img.shields.io/badge/arXiv-2409.18839-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2409.18839)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/opendatalab/MinerU)

## 简介

这是 **MinerU** 的官方用户手册仓库，尽可能提供完整的中文使用文档和指南。

MinerU 是一款高效的 PDF 文档提取工具，能够将文档转化为机器可读的结构化格式（如 Markdown、JSON）。项目起源于针对大模型预训练过程中语料提取的最佳实践，旨在从文档中提取可直接用于大模型训练的 AI-Ready 语料，为 RAG 知识库的构建与应用提供可靠的工具基础。我们将秉持“Tokenize Everything”的技术远景，持续拓展异构数据智能解析的广度与深度。

## 快速体验

- 🌐 **[MinerU 官网](https://mineru.net/?source=github)** - 在线版，即开即用
- 🤗 **[HuggingFace Demo](https://huggingface.co/spaces/opendatalab/MinerU)** - 在线体验
- 🔬 **[Github 开源项目](https://mineru.net/)** - 项目源码
## 文档导航

### 01. 产品形态对比

|  | 网页端/桌面客户端 | 本地部署开源版 | 在线API服务 |
|:---|:---|:---|:---|
| **适用用户** | 常规用户/研究者 | 研究者/开发者/高级用户 | 开发者 |
| **使用方式** | 图形化界面(GUI) | WebUI/命令行/代码 | HTTP请求 |
| **部署要求** | 无需部署，即开即用 | 需要Python/Docker环境 | 无需部署，网络调用 |
| **定制能力** | 无 | 高(可修改源代码) | 中(API参数控制) |

### 02. 文档结构

- **[产品简介](docs/about/introduction.md)** - 了解MinerU的核心功能和特性
- **[快速开始](docs/quick-start/)** - 快速上手MinerU
  - [本地部署](docs/quick-start/local-deployment.md)
  - [网页/桌面客户端](docs/quick-start/web-client.md)
  - [在线API服务](docs/quick-start/api-service.md)
  - [插件与生态](docs/quick-start/plugins/)
- **[使用指南](docs/user-guides/)** - 详细的使用说明
- **[版本更新](docs/release-notes/)** - 各版本更新说明
- **[常见问题](docs/faq.md)** - FAQ和故障排除
- **[联系我们](docs/contact.md)** - 获取帮助和支持

## 03. 主要功能

- **智能文档解析** - 输出符合人类阅读顺序的文本，适用于单栏、多栏及复杂排版
- **结构保持** - 保留原文档的结构，包括标题、段落、列表等
- **多媒体提取** - 提取图像、图片描述、表格、表格标题及脚注
- **公式识别** - 自动识别并转换文档中的公式为LaTeX格式
- **表格处理** - 自动识别并转换文档中的表格为HTML格式
- **OCR支持** - 自动检测扫描版PDF和乱码PDF，启用OCR功能
- **多语言支持** - Pipeline模式OCR支持84种语言的检测与识别
- **多格式输出** - 支持Markdown、JSON等多种输出格式
- **可视化结果** - 支持layout可视化、span可视化等，便于确认输出效果
- **性能优化** - 支持纯CPU环境运行，并支持GPU(CUDA)/NPU(CANN)/MPS加速
- **跨平台** - 兼容Windows、Linux和Mac平台

## 04. 插件生态

MinerU 支持多种插件，多个产品平台也集成了MinerU相关接口：

- **[Dify](docs/quick-start/plugins/dify.md)** - 与Dify平台集成
- **[N8N](docs/quick-start/plugins/n8n.md)** - 与N8N工作流集成
- **[Coze](docs/quick-start/plugins/coze.md)** - 与Coze平台集成
- **[Cherry Studio](docs/quick-start/plugins/cherry-studio.md)** - 与Cherry Studio集成
- **[Sider](docs/quick-start/plugins/sider.md)** - 与Sider浏览器扩展集成

## 05.社区与支持

### 获取帮助
- **[常见问题](docs/faq.md)** - 查看FAQ解决常见问题
- **[DeepWiki](https://deepwiki.com/opendatalab/MinerU)** - AI助手在线答疑
- **[微信群](https://mineru.net/community-portal/?aliasId=3c430f94)** - 加入微信交流群
- **[Discord](https://discord.gg/Tdedn9GTXq)** - 加入Discord社区
- **[邮箱支持](mailto:OpenDataLab@pjlab.org.cn)** - 邮件联系

### 贡献指南
- **[报告问题](https://github.com/opendatalab/MinerU/issues)** - 提交Bug报告
- **[功能建议](https://github.com/opendatalab/MinerU/issues)** - 提出新功能建议
- **[文档改进](https://github.com/Natt-code216/MinerU_UM)** - 改进文档内容

## 许可证

本项目采用Apache 2.0 开源许可证，详情请查看 [LICENSE](https://www.apache.org/licenses/LICENSE-2.0) 文件。

---

<div align="center">

**如果这个用户文档对您有帮助，请给我们一个Star！**

</div>
