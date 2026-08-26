# chrisgao1219.github.io — Chrisgao 个人网站

这是 **chrisgao1219.com** 的 GitHub Pages 源仓库。向 `master` 分支推送后，GitHub Pages 会自动构建并部署（约 1 分钟生效）。

## 主要文件

- `index.html` — 首页（纯文字名片）
- `rocketshu-skills.html` — 火箭叔精选 Skill 页（收录 110 个开源仓库、11 个分类）
- `skills-gallery/` — AI Skills 推荐库子站
- `CNAME` — 绑定 chrisgao1219.com 域名

## 如何更新页面

1. 编辑对应 HTML 文件
2. `git add <文件>` → `git commit -m "改动说明"` → `git push origin master`
3. 等约 1 分钟，访问 https://chrisgao1219.com/ 验证

## rocketshu-skills.html 数据说明

- 数据来源于 https://cc.obuudo.com/github-repos（跨境圈群聊 GitHub 仓库清单）
- 页面为自包含静态 HTML，数据在 `<script>` 的 `CATEGORIES` 数组里
- 本机有一键部署脚本：`projects/deploy-site.sh`
- 数据生成与构建脚本在本机用户目录：`additions.js`（新增 repo 数据）、`build_skills.js`（重新生成 HTML）
