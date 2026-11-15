# 雨夜便利店 · Midnight Konbini

一个可在浏览器中体验的日式雨夜 3D 便利店微场景。

## 在线体验
部署完成后访问：`https://winterrrr-zhou.github.io/rainy-konbini/`

## 本地运行
由于使用 ES modules，建议通过本地 HTTP 服务打开，而不是直接双击 HTML：

```bash
python3 -m http.server 8000
```

然后访问 http://localhost:8000。

## 操作
- 鼠标拖动 / 触屏单指：旋转场景
- 滚轮 / 双指捏合：缩放
- 店内灯光：切换室内照明
- 自动门：开关滑动门
- 自动售货机：选择饮品
- 邀请顾客：让夜归顾客走向便利店
- 雨夜按钮：切换雨天与晴夜

## 技术
- Three.js 0.160.0
- OrbitControls
- 场景模型和雨滴由代码生成
- Three.js 通过 jsDelivr CDN 加载，运行时需要联网

## 部署
项目已包含 GitHub Actions Pages workflow。将仓库的 Pages 构建来源设为 **GitHub Actions** 后，推送到 main 分支即可自动部署。
