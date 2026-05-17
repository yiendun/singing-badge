# 岭南歌唱达人 — 微课唱歌互动网页

扫码唱粤语童谣《齐齐望过去》，集齐动物碎片，获得岭南歌唱达人徽章！

## 部署方法

### 方法一：GitHub Pages（推荐，免费）

1. 在 GitHub 新建仓库，取名如 `singing-badge`
2. 将本文件夹内容推送到仓库：
   ```bash
   git remote add origin https://github.com/你的用户名/singing-badge.git
   git add -A
   git commit -m "岭南歌唱达人微课"
   git push -u origin main
   ```
3. 在 GitHub 仓库 → Settings → Pages → Source 选 `main` 分支 → Save
4. 等 1-2 分钟，访问 `https://你的用户名.github.io/singing-badge/`
5. 页面底部会自动显示二维码，扫码即可在手机上打开

### 方法二：其他托管

- **Vercel**：导入 GitHub 仓库，自动部署，国内访问更快
- **腾讯云静态托管**：上传 index.html 即可

## 使用说明

- 推荐在 **Chrome 浏览器**（Android）上使用语音识别功能
- iOS Safari 会自动切换到跟唱模式
- 每唱完一句获取一个动物碎片，集齐 4 个解锁徽章
- 徽章可长按或点击"保存徽章"下载到手机

## 技术信息

- 纯前端 HTML，使用 Web Speech API 识别粤语
- Canvas 绘制岭南风格徽章（镬耳墙 + 木棉花 + 舞狮元素）
