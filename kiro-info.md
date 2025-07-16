# AWS Kiro 核心情报与 kiro.directory 建设指南

## 一、AWS Kiro 核心产品信息

### 核心定位
**Kiro** - AWS 2025年7月发布的"Agentic AI IDE"，主打规范驱动开发(spec-driven development)和智能体钩子(agent hooks)，从需求到代码交付的全流程AI化[1][2]。

### 关键特性
- **架构**：基于Code OSS，完整兼容VS Code和Open VSX插件生态
- **平台**：支持Windows、Mac、Linux，支持Github/Google/AWS账户登录
- **AI模型**：集成Claude 4与Sonnet 3.7，基于Amazon Bedrock构建
- **核心功能**：
  - 规范驱动开发：自动生成EARS格式需求、技术方案、测试用例
  - Agent Hooks：事件驱动自动化(文档、测试、安全检查)
  - 多模态输入：代码、文件、URL等复杂任务AI规划执行

### 定价策略
| 版本 | 价格/月 | 交互限额 |
|------|---------|----------|
| Free | $0 | 50次 |
| Pro | $19 | 1,000次 |
| Pro+ | $39 | 3,000次 |

### 竞争优势
区别于传统代码助手(Copilot/Cursor)的"vibe coding"，Kiro强调**可投产代码**和**全流程规范化**，解决AI生成代码的维护性和文档化问题。

## 二、kiro.directory 网站架构与策略

### 核心页面结构
1. **Tips & Tricks** - Kiro使用技巧、规范文件撰写、agent hooks配置案例
2. **Cheat Sheets** - EARS语法、hooks模板、prompt语言速查表
3. **Comparisons** - Kiro vs Copilot/Cursor等主流AI IDE对比
4. **Pricing** - 版本对比与竞品价格分析
5. **Guides** - 技术细节、spec机制、hooks原理深度解析

### 内容策略
- **实时更新**：追踪Kiro官方动态、社区热门案例
- **竞品监控**：持续对比AWS Q Developer、Cursor、Copilot等工具升级
- **社区驱动**：支持用户贡献配置文件、最佳实践案例

### SEO重点
- **核心关键词**：AWS Kiro tips, agent hooks, spec-driven development, Kiro vs Copilot
- **技术SEO**：结构化数据标记、内链策略、FAQ优化
- **长尾流量**：插件适配、痛点解决方案、使用场景细分

### 技术实现
- **架构**：Next.js/React + Headless CMS (Strapi/Contentful)
- **基础设施**：AWS无服务器服务(Lambda, S3, CloudFront)
- **特性**：Markdown支持、代码高亮、社区投稿系统

## 三、发展方向与关键参考

### 产品演进趋势
- **模型扩展**：支持更多第三方大模型和插件生态
- **Hooks生态**：深化自定义自动化工作流，全流程AI化开发
- **企业集成**：与CI/CD、安全、QA系统深度集成

### 核心观察点
- Kiro以独立品牌运营，淡化AWS标识，主攻通用开发者市场
- 基于VS Code生态，降低用户迁移成本
- 官方资源：kiro.dev博客和社区为主要信息源

### 建设建议
**kiro.directory定位**：打造AI IDE领域专业内容门户，以"实用技巧+深度对比"为核心，建立开发者社群和企业用户的信息枢纽。

## 核心参考资源

### 官方资源
- [Kiro 官方博客](https://kiro.dev/blog/introducing-kiro/)
- [Kiro 定价页面](https://kiro.dev/pricing/)
- [AWS 官方发布](https://aws.amazon.com/q/developer/pricing/)

### 重要分析文章
- [GeekWire: Amazon targets vibe coding chaos](https://www.geekwire.com/2025/amazon-targets-vibe-coding-chaos-with-new-kiro-ai-software-development-tool/)
- [PCMag: Amazon Kiro tame vibe coding chaos](https://www.pcmag.com/news/amazon-kiro-is-here-to-tame-the-vibe-coding-chaos)
- [Dev.to: Meet Kiro](https://dev.to/aspittel/meet-kiro-4m0o)

### 技术深度文章
- [Repost AWS: Kiro agentic AI IDE](https://repost.aws/articles/AROjWKtr5RTjy6T2HbFJD_Mw/%F0%9F%91%BB-kiro-agentic-ai-ide-beyond-a-coding-assistant-full-stack-software-development-with-spec-driven-ai)
- [Reddit 社区讨论](https://www.reddit.com/r/ClaudeAI/comments/1lzsvot/amazons_new_claudepowered_specdriven_ide_kiro/)
- [CNBC 发布报道](https://www.cnbc.com/2025/07/14/aws-launches-kiro-ai-coding-program.html)


