# 荣县一中成绩分析 · 专项练习预览

访问：<https://yusheng266186-beep.github.io/jianwei-observatory-preview/>

此仓库仅发布 [`jianwei-observatory` 的 `feature/gemini-training` 分支](https://github.com/yusheng266186-beep/jianwei-observatory/tree/feature/gemini-training)，不替换正式站。源代码与后端维护在原项目的分支中，本仓库只保存部署流程。

预览站的成绩材料、教学计划、偏好和教师会话与正式站分别保存在浏览器中。试用时可先从正式站下载完整 JSON 备份，再导入预览站；也可直接导入原始表格。预览站不自动迁移正式站及旧版的本机记录。

学生研究 → 打开学生卡片 → 生成专项练习。首次出题需要私有交接资料中的教师访问口令。密钥保留在独立腾讯云服务中，Pages 仅包含静态前端。

分支更新并完成验证后，在本仓库 Actions 中重新运行 **Publish Gemini branch preview** 即可更新预览。`preview-build.json` 记录当前发布的源代码提交，便于核对版本。正式站继续使用原仓库 `main` 的 Pages 配置。
