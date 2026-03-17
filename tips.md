## 使用 GitHub Actions 自动部署
 1. 创建新的 GitHub Actions 工作流文件 .github/workflows/deploy-github-pages.yml
 2. 配置工作流在推送到 main 分支时触发
 3. 使用 actions/upload-pages-artifact 和 actions/deploy-pages actions 部署
 4. 在 GitHub 仓库设置中启用 GitHub Pages 并选择 "GitHub Actions" 作为源

## 启用 GitHub Pages
 在 GitHub 仓库中进行以下配置:
 1. 进入仓库的 Settings → Pages
 2. 在 "Build and deployment" 部分
 3. Source 选择: "GitHub Actions"
 4. 保存设置

## 部署
 1. 将工作流文件提交到 main 分支
 2. 推送到 GitHub
 3. GitHub Actions 会自动运行并部署
 4. 部署完成后,网站将在 https://<username>.github.io/<repository-name>/ 可访问
