# 雷东龙 · 作品集

**线上地址：https://thuhien20086-maker.github.io/**（已开通）

## 改内容
- 每个项目是一段 `<div class="item">`；状态标签 `chip live`（在跑）/ `chip build`（迭代中）
- 联系方式在「联系我」区块

## 换成你自己的微信二维码
现在的 `wx-qr.png` 是占位图（扫出来是一句提示文案）。换成真码：

```bash
cd ~/Projects/作品集
# 方法一：把自己的微信二维码图片存成 wx-qr.png 覆盖
# 方法二：用文字生成一张码（示例）
qrencode -o wx-qr.png "微信号：xxxxx"
git add -A && git commit -m "update qr" && git push
```
推送后 1 分钟内线上生效。

## 本地预览
```bash
open index.html
```

## 部署原理
仓库名 `thuhien20086-maker.github.io` = GitHub 用户页仓库，推 `main` 即自动发布到根域名 `https://thuhien20086-maker.github.io/`，无需额外配置。
