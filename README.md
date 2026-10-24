# SSH 前端 3 群 · AI 泔水合集

## 写在前面

这个 repo 只是收集群友自己做的一些小玩具。**「AI 泔水」只是对 vibe coding 的戏称，与捧踩无关。** 如有不适，欢迎联系维护者，或提交 PR 自行删除对应条目。

这里收录 SSH 前端 3 群群友用 AI 辅助开发的工具、游戏、实验与个人二开项目，按作者整理，方便发现作品、交流实现、参与贡献。

本仓库是一个 **README-first 的链接索引**。

## 目录

- [项目索引](#项目索引)
- [收录规则](#收录规则)
- [如何贡献](#如何贡献)
- [使用与归属说明](#使用与归属说明)

## 项目索引

按作者分组，同组内并列展示。项目名称链接到 GitHub 仓库；标注「二开」的条目指向群友维护的个人版本。作者使用公开昵称署名。

### less

- **[doubao-tts](https://github.com/Loveyless/doubao-tts)**：豆包文本转语音客户端与服务化改造，个人二开。

### 五

- **[d-switch](https://github.com/GinWU05/d-switch)**：macOS 跨显示器鼠标指针切换工具，个人二开。
- **[socrates-pig](https://github.com/GinWU05/socrates-pig)**：「痛苦的苏格拉底／快乐的猪」趣味测试。
- **[claudecodeui](https://github.com/GinWU05/claudecodeui)**：加入 Pi 支持、修复与权限控制改动的个人分支，基于 CloudCLI / Claude Code UI 二开。

### 兔子弟

- **[qwen3-tts-web](https://github.com/NOTF-API/qwen3-tts-web)**：基于 Qwen3-TTS 的本地语音合成与声音克隆应用。
- **[qwen-image-web](https://github.com/NOTF-API/qwen-image-web)**：基于 Qwen Image 的本地生图工具。
- **[vocal-extractor](https://github.com/NOTF-API/vocal-extractor)**：本地音频人声／伴奏分离工具。

### 花花

- **[rts-game](https://github.com/oWinnieo/rts-game)**：太空 RTS 游戏实验。
- **[my-pvz](https://github.com/oWinnieo/my-pvz)**：植物大战僵尸复刻练习项目。

### 😨😨害怕

- **[ESP-monitor](https://github.com/3721915/ESP-monitor)**：基于 ESP32 的 Codex 外接状态小屏。

### 小登

- **[NiuLai](https://github.com/VecSum/NiuLai)**：币安现货与合约行情的只读命令行观察工具。

### 家诚+×

- **[new-tab-components](https://github.com/lainbo/new-tab-components)**：前端组件与交互实验。
- **[API Proxy](https://github.com/lainbo/api-proxy)**：Go 实现的 AI/API 薄反向代理，按路径前缀选择上游并转发原始请求。
- **[Synopsis](https://github.com/lainbo/synopsis)**：部署在 Cloudflare Workers 上的个人邮件中枢：把自有域名的邮件转存到 Gmail，并把域名邮件和直接发到 Gmail 的邮件都整理成 AI 摘要推送到 Telegram bot。

### 吃饭不喝热水

- **[subbit](https://github.com/sywyyhykkk/subbit)**：本地优先的订阅与买断软件成本管理工具，支持 macOS、Windows。
- **[UIgly](https://github.com/sywyyhykkk/uigly)**：收集文案、命名与布局等常见界面问题的独立 HTML/CSS 案例，并直接提供案例源码。
- **[Magpie Screen](https://github.com/sywyyhykkk/magpie-screen)**：基于 ESP32-S3 的 Magpie 独立 Wi-Fi 数据屏，显示额度、实时路由和今日用量，并提供 Web 预览工具。

## 收录规则

1. **与群友有关**：项目由群友开发、维护，或有实质性的个人二开。
2. **有公开仓库**：提供可公开访问的 GitHub 项目链接；只有截图、演示站或构想的作品，等仓库公开后再收录。
3. **描述可核对**：用一句话说明项目解决什么问题，功能、效果与性能描述注明项目 README 或作者说明中的来源。
4. **保留来源**：欢迎 fork 与二开，条目需明确标注；底层模型、框架、上游代码及素材保留各自贡献者的署名与归属。
5. **避免重复**：同一项目改名、发布新版本或增加安装包时更新原条目。用途不同、独立维护的项目可以分别收录。
6. **尊重隐私与意愿**：只收录公开项目及必要署名，不提交聊天截图、私人联系方式、密钥或非公开群资料。作者可提出更正或移除。

欢迎各阶段的 AI 辅助开发作品，按上述规则收录。

## 如何贡献

直接修改本仓库的 `README.md` 并提交 Pull Request；不方便提交 PR，也可以通过 [Issue](https://github.com/ssh-wechat-group3/group-ai-slop/issues) 提供线索。

### 新增项目

在对应作者的小节下增加一项。没有作者小节时，按下面的格式新增；使用作者愿意公开的昵称。

```markdown
### 作者昵称

- **[项目名称](https://github.com/owner/repo)**：一句话说明用途；如为二开，请明确标注。
```

提交时请说明：

- 作者的公开署名及其与项目的关系。
- 公开 GitHub 仓库地址。
- 项目的一句话用途。
- 是否属于 fork、二开或已有条目的改名。

维护者会检查链接、归属和重复情况；群友身份有疑问时由维护者另行确认。

### 更正、迁移或移除

仓库迁移、项目改名、简介需更正或作者希望撤下时，请提交 PR 或 Issue，指出对应条目与所需变更。仓库失效时先确认迁移情况，再更新链接或移除条目。

## 使用与归属说明

- **使用说明**：安装、配置、模型需求、费用和维护状态，见目标仓库的当前文档。
- **许可证与归属**：各项目及其依赖、模型和素材遵循各自许可证与使用条款，商用和再分发按相应条款执行。
- **问题找对地方**：运行问题、功能需求与漏洞反馈请前往对应项目；本仓库的 Issue 用于索引维护。敏感漏洞请按目标项目的安全政策私下报告。
- **群聊数据授权**：使用消息展示或统计类工具采集、发布成员数据与聊天记录时，需取得相应授权。

---

由 [ssh-wechat-group3](https://github.com/ssh-wechat-group3) 维护。欢迎把你做出来的下一个小东西放进来。
