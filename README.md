# AI 全景学堂｜在线轻量预览版

这是项目的第一版在线轻量预览源文件，包含课程入口、基础概念讲解、课程搜索、明暗主题切换和互动小测。课程体系、教材草稿、AI 协作手册和发布验收清单位于对应文件夹。

## 首次启用 GitHub Pages（必须由仓库所有者完成）
1. 打开仓库 Settings → Pages。
2. 在 Build and deployment 中把 Source 设为 GitHub Actions。
3. 回到 Actions，打开最新的 Deploy AI Panorama to GitHub Pages 运行；若它在你启用 Pages 前失败，请点击 Re-run jobs，或向 main 提交一个新变更触发重跑。
4. 等待运行状态显示成功，再从 Settings → Pages 获取实际发布网址。

当前自动化连接没有创建 Pages 站点所需的管理权限，因此不能代替仓库所有者完成第 1–2 步；不要把一次提交成功误认为网页已上线。

## 重要说明
- 本在线页面是轻量预览版，不等于完整离线 HTML 预览。
- 教材仍在编写和独立审查中，未完成的内容不会冒充正式批准。
- 仓库是公开的，不要提交密码、API Key 或私人资料。
- 官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
