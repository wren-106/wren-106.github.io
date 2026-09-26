# 红楼梦 · AI Agent 名著讲解自动化剪辑 —— 作品展示页

GitHub Pages 部署版（全部素材使用英文 ASCII 路径，GitHub 完全兼容）。

## 文件结构

```
├── index.html          # 作品展示主页
└── assets/
    ├── audio.mp3       # TTS 旁白配音
    ├── video.mp4       # 成片视频
    └── images/         # 视频封面 poster.jpg + 七张分镜图 shot1-7.jpg
```

## 部署到 GitHub Pages 步骤

1. 在 GitHub 新建一个仓库（如 `honglou-showcase`）
2. 将**本文件夹里的全部内容**（`index.html` 和 `assets/` 整个文件夹）上传到仓库**根目录**
   - 注意：不是上传 index.html 单个文件，必须连同 assets 一起
3. 仓库设置 → Pages → Source 选择 `main` 分支 / `(root)` → Save
4. 等待 1-2 分钟，访问 `https://<你的用户名>.github.io/honglou-showcase/` 即可

## 常见问题

- **图片/视频不显示** = 只上传了 index.html，没有上传 assets 文件夹
- 视频约 12MB，低于 GitHub 单文件 100MB 限制，可直接上传
- 建议用 GitHub Desktop 或 `git push` 上传，网页端拖拽上传大文件夹较慢
