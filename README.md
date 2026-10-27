# 雷东龙 · 作品集（静态页）

## 本地预览
直接双击 `index.html`，或：

```bash
open index.html
```

## 上线到 GitHub Pages（3 步）
```bash
cd ~/Projects/作品集
git init && git add . && git commit -m "portfolio"
# 先在 GitHub 建一个空仓库，比如 long-portfolio，然后：
git remote add origin git@github.com:<你的用户名>/long-portfolio.git
git push -u origin main
```
推完去仓库 → Settings → Pages → Source 选 `main` / root → 保存。
1 分钟后地址是 `https://<用户名>.github.io/long-portfolio/`。

## 只差 3 个待填项
`index.html` 里搜「待填」：
1. 微信号 / 二维码
2. 公众号名称
3. 邮箱

填完再推一次即可。

## 想改内容
每个项目是一段 `<div class="item">`；状态标签用 `chip live`（在跑）/ `chip build`（迭代中）。
