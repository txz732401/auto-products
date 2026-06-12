# MarkdownForge 部署清单

## 方式 A: 本地预览 (推荐先跑通)
```
cd E:\trae\auto_saas_agent\output\markdownforge
python -m http.server 8000
# 然后浏览器打开 http://localhost:8000
```

## 方式 B: GitHub Pages
1) 在 GitHub 新建仓库
2) 把本目录 (E:\trae\auto_saas_agent\output\markdownforge) 的内容 push 到 main 分支
3) Settings → Pages → main / root → 等 1 分钟即可拿到 URL

## 方式 C: Vercel / Netlify
拖拽本文件夹到 https://vercel.com/new 或 https://app.netlify.com/drop 即可 1 分钟上线。

## 下一步增长实验
- 给核心功能加 1-2 个真实用户试用
- 统计访问量 + 转化率
- 在 ['markdown', 'online tool', 'developer tool'] 社区发作品帖
