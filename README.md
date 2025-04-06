# **CodeLens - 实时 Web 代码沙盒**

## **📌 项目简介**
**CodeLens** 是一款基于浏览器的 **HTML/CSS/JS 实时编辑器**，支持：
- **实时预览** - 编写代码的同时即时查看渲染效果
- **控制台调试** - 捕获并显示 `console.log` / `error` / `warn` 输出
- **多面板布局** - 可拖拽调整编辑器、预览和控制台的大小
- **主题切换** - 支持亮色/暗色模式及多种代码高亮主题
- **一键导出** - 快速下载完整 HTML 文件
- **响应式设计** - 适配桌面和移动设备

**适用场景**：
- 快速测试前端代码片段
- 教学演示 HTML/CSS/JS 实时效果
- 调试和分享代码示例

---

## **🚀 快速部署**
### **1. Cloudflare Pages（推荐）**
**步骤**：
1. **Fork 或上传代码** 到你的 GitHub/GitLab 仓库
2. 登录 [Cloudflare Pages](https://pages.cloudflare.com/)
3. 点击 **"Create a project"** 并连接你的代码仓库
4. 设置 **构建设置**：
   - **Framework preset**: `None`（纯静态 HTML，无需构建）
   - **Build command**: 留空
   - **Build output directory**: `/`（根目录）
5. 点击 **"Save and Deploy"**，稍等片刻即可获得 `*.pages.dev` 的免费域名

**特点**：
✅ 全球 CDN 加速  
✅ 免费 HTTPS  
✅ 自动部署  

---

### **2. GitHub Pages**
**步骤**：
1. **Fork 本项目** 或上传代码到你的 GitHub 仓库
2. 进入仓库 **Settings → Pages**
3. 选择 **GitHub Actions** 或 **Deploy from a branch**
4. 选择 **`main` 分支** 和 **`/ (root)` 目录**
5. 点击 **Save**，稍等片刻即可访问 `https://<username>.github.io/<repo-name>/`

**特点**：
✅ 完全免费  
✅ 适合小型项目  
⚠️ 国内访问可能较慢  

---

### **3. Vercel**
**步骤**：
1. **Fork 或上传代码** 到你的 GitHub/GitLab 仓库
2. 登录 [Vercel](https://vercel.com/)
3. 点击 **"Add New Project"** 并导入你的仓库
4. 设置 **构建设置**：
   - **Framework**: `Static`（纯静态）
   - **Build command**: 留空
   - **Output directory**: `/`（根目录）
5. 点击 **Deploy**，稍等片刻即可获得 `*.vercel.app` 的免费域名

**特点**：
✅ 全球边缘网络加速  
✅ 自动 HTTPS  
✅ 支持自定义域名  

---

## **🛠️ 本地开发**
### **运行方式 1：直接打开 `index.html`**
- 无需服务器，直接双击 `index.html` 即可运行（部分功能可能受限）

### **运行方式 2：使用 Live Server（推荐）**
1. 安装 VS Code 插件 **"Live Server"**
2. 右键 `index.html` → **"Open with Live Server"**
3. 浏览器会自动打开 `http://localhost:5500`

---

## **📜 开源协议**
本项目采用 **MIT License**，允许自由使用、修改和分发。

---

## **💡 贡献指南**
欢迎提交 Issue 或 PR！贡献方向包括：
- 优化 UI 设计
- 增加更多代码高亮主题
- 改进移动端适配

---

## **🌐 在线 Demo**
- [Demo](https://codelens.haib.top/)
