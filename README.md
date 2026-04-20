# rxcare-showcase

rxcare 项目展示页，托管在 GitHub Pages。

🔗 **在线预览**：https://calwade.github.io/rxcare-showcase/

## 关于

这是 [rxcare](https://github.com/CalWade/rxcare) 项目的静态展示页，用于简历与面试展示。

- **风格**：极简单页
- **技术**：纯 HTML + CSS，无构建工具链
- **部署**：GitHub Pages（推送 `main` 即生效）

## 文件结构

```
rxcare-showcase/
├── index.html       主页（全部内容）
├── assets/          图片资源（证书、Logo 等）
├── screenshots/     App 功能截图
└── README.md
```

## 本地预览

```bash
# 任选一种
python3 -m http.server 8080
npx serve .
```

然后打开 http://localhost:8080。

## 开启 GitHub Pages

仓库 → Settings → Pages → Source 选 `Deploy from a branch` → Branch 选 `main` / `/ (root)` → Save。

## License

Private · CalWade
