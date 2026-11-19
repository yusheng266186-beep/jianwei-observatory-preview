# 见微 · 专项练习预览 / Jianwei Exercise Preview

[预览站 / Preview](https://yusheng266186-beep.github.io/jianwei-observatory-preview/) · [正式工作区 / Main workspace](https://yusheng266186-beep.github.io/jianwei-observatory/) · [主项目 / Main repository](https://github.com/yusheng266186-beep/jianwei-observatory)

## 中文

这里保存见微专项练习分支的独立发布流程，适合回看 Gemini 专项练习界面或迁移旧预览资料。日常成绩研究和新版本以主仓库的正式站为准。

- **源代码**在主项目的 [feature/gemini-training 分支](https://github.com/yusheng266186-beep/jianwei-observatory/tree/feature/gemini-training)。本库保存 [Pages 发布工作流](.github/workflows/deploy.yml)。
- **本机资料**按站点隔离。预览站的成绩材料、教学计划、教师会话和设置各自保存。先用演示或脱敏表格检查流程，需要迁移时导入有权使用的完整 JSON 备份。
- **练习入口**在「学生研究」中的学生卡片。云端任务需经过教师授权，服务凭据放在对应云服务内。
- **发布核对**在 Actions 手动运行 **Publish Gemini branch preview**。预览页面的 <code>preview-build.json</code> 记录实际源代码提交，可用于比对。

## English

This repository publishes the standalone Gemini exercise preview for Jianwei Observatory. Use it for historical comparisons or to migrate an old preview workspace. The main workspace is the regular entry point for assessment research and current releases.

- **Source** lives on the [feature/gemini-training branch](https://github.com/yusheng266186-beep/jianwei-observatory/tree/feature/gemini-training) of the main project. The [Pages workflow](.github/workflows/deploy.yml) is kept here.
- **Local workspaces** are separate for the preview and main site. Start with demo or de-identified input, then restore an authorized full JSON backup if migration is needed. Materials, plans, preferences, and teacher sessions are local to their own site.
- **Practice flow** starts from a student card in Student Research. Cloud generation requires teacher authorization. Service credentials live in the service environment.
- **Deployment checks** start with **Publish Gemini branch preview** in Actions. Read <code>preview-build.json</code> on the preview site to identify the source commit.
