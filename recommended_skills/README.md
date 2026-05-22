# 🎁 自用 Skills 礼包（19 个）

> 来自公众号「AI and Economics」粉丝破万福利

这是我日常最常用的 **19 个 Claude Code Agent Skills**，涵盖文档处理、前端设计、网络研究、演示文稿、中文优化等场景。每一个都经过长时间的筛选、测试和迭代打磨。

---

## 📦 安装方法

打开 Claude Code / Codex / OpenCode，对它说：

```
把这个 skill 压缩包解压缩，把里面的 skills 放到 ~/.claude/skills/ 目录下。
```

或者手动操作：

```bash
# 将所有 skill 文件夹复制到 Claude Code 的 skills 目录
cp -r recommended_skills/* ~/.claude/skills/
```

安装完成后，在 Claude Code 中输入 `/skill-name` 即可调用对应 Skill。

---

## 📋 Skills 一览

### 一、Anthropic 官方出品（7 个）

| Skill                    | 说明                                                           |
| ------------------------ | -------------------------------------------------------------- |
| `/docx`                | 📄 Word 文档处理——创建、读取、编辑，支持表格、目录、页眉页脚 |
| `/xlsx`                | 📊 电子表格——创建、编辑、清洗数据、写公式、生成图表          |
| `/pdf`                 | 📑 PDF 万能工具——读取、合并拆分、旋转、水印、加密、OCR       |
| `/pptx`                | 📽️ PowerPoint 处理——创建、编辑、提取内容、模板操作         |
| `/frontend-design`     | 🎨 前端设计——生成高质量网页界面，支持 React/Vue/HTML         |
| `/skill-creator`       | 🛠️ Skill 开发工具——从零创建 Skill、迭代优化、跑评测        |
| `/command-development` | ⌨️ 自定义命令开发——创建斜杠命令，支持 YAML 配置和动态参数  |

### 二、社区精选（6 个）

| Skill              | 来源        | 说明                                                          |
| ------------------ | ----------- | ------------------------------------------------------------- |
| `/web-research`  | LangChain   | 🔍 多源网络搜索 + 子代理协作 + 带引用的研究报告               |
| `/ui-ux-pro-max` | Skills 社区 | 🎯 内置 50+ 设计风格、97 种配色、57 种字体搭配、99 条 UX 准则 |
| `/markitdown`    | Microsoft   | 🔄 将 PDF/Office/图片/音频等 20+ 种格式转为 Markdown          |
| `/arxiv`         | Skills 社区 | 📚 arXiv 论文搜索，支持快速了解/深入分析/文献综述三种模式     |
| `/agent-browser` | Skills 社区 | 🌐 浏览器自动化——打开网页、填表、点击、截图、爬取数据       |
| `/web-access`    | 一泽 Eze    | 🔗 完整联网能力——智能联网策略 + CDP 浏览器操作              |

### 三、自制 Skills（6 个）

| Skill                        | 说明                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------ |
| `/do-agent`                | 🚀**最常用**——多代理任务执行框架，自动拆解为规划→执行→审阅→修订，最多 10 个子代理并行 |
| `/marp-slides-creator`     | 🎬 演示文稿创建——内置 14 款主题，自动多维度审阅，适合课堂和学术报告                            |
| `/marp-export`             | 📤 演示文稿导出——支持 PDF/HTML/PPTX/PNG 格式                                                   |
| `/md-to-docx`              | 📝 Markdown 转 Word——仿宋字体、1.5 倍行距、首行缩进，专为中文学术/公文优化                     |
| `/fix-chinese`             | ✍️ 中文去 AI 味——自动修正翻译腔，处理中英混排格式（主动触发，无需手动调用）                  |
| `/chinese-quote-converter` | 🔤 中英引号转换——一键将英文直引号转为中文弯引号，自动跳过代码块                                |

---

## 💡 使用建议

- **文档处理**：`/docx` + `/xlsx` + `/pdf` + `/pptx` 覆盖日常办公
- **做课件/报告**：`/marp-slides-creator` + `/marp-export`
- **写中文内容**：`/fix-chinese`（自动生效）+ `/chinese-quote-converter`（发布前转引号）
- **深度研究**：`/web-research` + `/arxiv`
- **复杂任务**：`/do-agent` 自动拆解并行执行
- **格式转换**：任何文件先用 `/markitdown` 转 Markdown，再做后续处理

---

## 🔗 相关链接

- 公众号：**AI and Economics**
- 详细介绍见公众号文章《粉丝破万福利：我最常用的19个Agent Skills，打包送你》
