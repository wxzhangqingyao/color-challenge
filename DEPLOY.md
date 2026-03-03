# 部署指南

## 方法一：GitHub Pages

1. **创建GitHub仓库**
   - 访问 [GitHub](https://github.com)
   - 点击右上角的 "+" 按钮，选择 "New repository"
   - 仓库名称：`color-challenge`（或任何你喜欢的名称）
   - 选择 "Public"
   - 点击 "Create repository"

2. **推送代码到GitHub**
   - 在本地仓库目录中运行以下命令：
   ```bash
   # 替换 <your-username> 为你的GitHub用户名
   git remote add origin https://github.com/<your-username>/color-challenge.git
   git push -u origin main
   ```

3. **启用GitHub Pages**
   - 进入你的GitHub仓库
   - 点击 "Settings"
   - 在左侧菜单中点击 "Pages"
   - 在 "Source" 部分，选择 "main" 分支，然后点击 "Save"
   - 等待几分钟，你的网站就会部署完成
   - 访问地址：`https://<your-username>.github.io/color-challenge/`

## 方法二：Vercel

1. **访问Vercel官网**
   - 访问 [Vercel](https://vercel.com)
   - 使用GitHub账号登录

2. **导入项目**
   - 点击 "New Project"
   - 选择 "Import Git Repository"
   - 选择你的 `color-challenge` 仓库
   - 点击 "Import"

3. **部署项目**
   - 保持默认设置
   - 点击 "Deploy"
   - 部署完成后，你会得到一个URL

## 方法三：Netlify

1. **访问Netlify官网**
   - 访问 [Netlify](https://www.netlify.com)
   - 使用GitHub账号登录

2. **导入项目**
   - 点击 "New site from Git"
   - 选择 "GitHub"
   - 选择你的 `color-challenge` 仓库
   - 点击 "Deploy site"

3. **部署项目**
   - 等待部署完成
   - 你会得到一个URL