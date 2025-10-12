# 欢迎来到 MinerU 用户手册

  <div align="center" xmlns="http://www.w3.org/1999/html">
<!-- logo -->
<p align="center">
  <img src="https://opendatalab.github.io/MinerU/images/MinerU-logo.png" width="300px" style="vertical-align:middle;">
</p>
<div align="center">

[![stars](https://img.shields.io/github/stars/opendatalab/MinerU.svg)](https://github.com/opendatalab/MinerU)
[![MinerU](https://img.shields.io/badge/Official%20Site-blue?logo=web&logoColor=white)](https://mineru.net/)
[![HuggingFace](https://img.shields.io/badge/Demo_on_HuggingFace-yellow.svg?logo=huggingface&logoColor=white)](https://huggingface.co/spaces/opendatalab/MinerU)
[![arXiv](https://img.shields.io/badge/MinerU-Technical%20Report-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2409.18839)
[![arXiv](https://img.shields.io/badge/MinerU2.5-Technical%20Report-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2509.22186)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/opendatalab/MinerU)

</div>

<div align="center" style="font-size:16px;">

<span style="vertical-align: middle; margin-right: 8px;">加入社区:</span>
<a href="https://discord.gg/Tdedn9GTXq" target="_blank">
    <img src="https://img.shields.io/badge/Discord-7289DA?logo=discord&logoColor=white" alt="Discord" style="vertical-align: middle;">
</a>
<a href="https://mineru.net/community-portal/?aliasId=3c430f94" target="_blank" style="margin-left:4px;">
    <img src="https://img.shields.io/badge/WeChat-09b83e?logo=wechat&logoColor=white" alt="WeChat" style="vertical-align: middle;">
</a>

</div>


</div>


<div class="grid cards" markdown>

-   __MinerU 是什么？__

    ---
    MinerU 是 AI 大模型时代的文档解析引擎，能够将 PDF 等格式文档高保真地转换为 Markdown 等结构化的可读格式，精准提取文本、表格、公式、代码及化学符号。MinerU 的代码与模型已在 GitHub 和 HuggingFace 平台开源，并提供网页端、桌面客户端、在线 API 等多种在线服务。[了解更多](about/introduction.md)

-   __MinerU 主要功能__

    ---

    - 输出符合人类阅读顺序的文本，适用于单栏、多栏及复杂排版
    - 保留原文档的结构，包括标题、段落、列表等
    - 提取图像、图片描述、表格、表格标题及脚注
    - 自动识别并转换文档中的公式为 LaTeX 格式
    - 自动识别并转换文档中的表格为 HTML 格式
    - 自动检测扫描版 PDF 和乱码 PDF，并启用 OCR 功能
    - MD 格式自动删除页眉、页脚、脚注、页码等元素，确保语义连贯
    - Pipeline 模式 OCR 支持 84 种语言的检测与识别
    - 支持多种输出格式，如多模态与 NLP 的 Markdown、按阅读顺序排序的 JSON、含有丰富信息的中间格式等
    - 支持多种可视化结果，包括 layout 可视化、span 可视化等，便于高效确认输出效果与质检
    - 支持纯 CPU 环境运行，并支持 GPU(CUDA)/NPU(CANN)/MPS 加速
    - 兼容 Windows、Linux 和 Mac 平台

-   __一、快速开始__

    ---

    - [本地部署](quick-start/local-deployment.md)
    - [网页端/桌面客户端/在线demo](quick-start/web-client.md)
    - [在线 API 服务](quick-start/api-service.md)

-   __二、版本更新说明__

    ---

    - [开源版本](release-notes/open-source.md)
    - [网页端/桌面客户端/在线demo](release-notes/web-client.md)
    - [在线 API 服务](release-notes/api-service.md)

-   __三、使用指南__

    ---
    
    - **本地部署**
        - [多种使用方式](user-guides/local-deployment/index.md)
        - [模型源配置](user-guides/local-deployment/model-source.md)
        - [命令行工具](user-guides/local-deployment/cli-tools.md)
        - [进阶优化参数](user-guides/local-deployment/advanced_cli_parameters.md)
        - [扩展模块安装](user-guides/local-deployment/extension-modules.md)
        - [Docker部署](user-guides/local-deployment/docker-deployment.md)
        - [输出文件格式](user-guides/local-deployment/output-files.md)
    - [网页端/桌面客户端](user-guides/web-client.md)
    - [在线 API 服务](user-guides/api-service.md)
    - **插件与生态**
        - [本章概述](user-guides/plugins/index.md)
        - [Cherry Studio](user-guides/plugins/cherry-studio.md)
        - [Sider](user-guides/plugins/sider.md)
        - [Dify](user-guides/plugins/dify.md)
        - [Coze](user-guides/plugins/coze.md)
        - [N8N](user-guides/plugins/n8n.md)
        - [FastGPT](user-guides/plugins/fasgpt.md)


-   __四、其他信息__

    ---

    - [常见问题](faq.md)
    - [联系我们](contact.md)
    - [友情链接](links.md)

</div>


-   __五、社区与支持__

    ---


!!! question "遇到问题？"

    欢迎加入我们的 **[社区大家庭](contact.md)**
    
    如果您在使用中遇到任何问题，或者有任何功能建议，我们强烈推荐您先查阅 **[常见问题 (FAQ)](faq.md)** 页面。
    
    如果问题仍未解决，欢迎通过 **[联系我们](contact.md)** 中提供的渠道与我们交流，我们非常乐意为您提供帮助。


