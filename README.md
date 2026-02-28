# Skills Hub

个人 AI 助手技能（Skills）统一管理仓库。

## 已有技能

| 技能 | 说明 |
|------|------|
| [pdf](pdf/) | PDF 处理 - 文本提取、表格提取、合并拆分、表单填充等 |
| [docx](docx/) | Word 文档 - 创建、编辑、修订模式、评论等 |
| [pptx](pptx/) | PowerPoint - 幻灯片创建、编辑、缩略图等 |
| [xlsx](xlsx/) | Excel - 表格处理、公式计算等 |
| [skill-creator](skill-creator/) | 技能创建工具 - 快速创建新技能 |
| [frontend-design](frontend-design/) | 前端设计 |
| [mcp-builder](mcp-builder/) | MCP 服务器构建 |
| [ui-ux-pro-max](ui-ux-pro-max/) | UI/UX 设计 |

## 技能结构

每个技能目录包含：

```
skill-name/
├── SKILL.md          # 技能主文件（YAML frontmatter + Markdown）
├── scripts/          # 可执行脚本（Python/Bash 等）
├── references/       # 参考文档（按需加载）
└── assets/           # 资源文件（模板、图标等）
```

## 快速开始

1. **使用技能**：进入对应技能目录查看 `SKILL.md`
2. **创建技能**：
   ```bash
   python skill-creator/scripts/init_skill.py <skill-name> --path .
   ```
3. **打包技能**：
   ```bash
   python skill-creator/scripts/package_skill.py <skill-folder>
   ```

## License

本仓库仅用于个人整理和管理 AI 助手技能。各技能遵循其原有许可证：

| 技能 | 许可证 |
|------|--------|
| pdf, docx, pptx, xlsx | Proprietary (Anthropic) |
| skill-creator, frontend-design, mcp-builder | Apache 2.0 |
| ui-ux-pro-max | 个人技能 |

除非另有说明，本仓库的结构和组织受版权保护。
