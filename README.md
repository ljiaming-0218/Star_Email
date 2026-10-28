# 星尘邮差

一个无需安装依赖的单文件 Canvas 游戏。直接打开 `index.html` 即可开始；游戏进度保存在浏览器的 localStorage 中。

## 操作

星图上选择相邻星球并出发，在邮局接信和升级。飞行时使用方向键或 WASD 移动、Shift 加速、空格释放护盾，P 暂停；触屏使用左侧摇杆和右侧按钮。对话框可点击加速文字并选择答案。

飞行中追逐成串星尘：3 秒内连续拾取，第 5 枚可获得 3 点星尘；擦过陨石但不碰撞会获得 2 点星尘，穿过金色星环可补充燃料并获得 3 点星尘。无伤抵达还能获得 5 点奖励。

## 部署到 Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/ljiaming-0218/Star_Email)

点击按钮并连接此 GitHub 仓库，Render 将根据 `render.yaml` 创建静态站点。也可以手动创建 Static Site：分支选择 `main`，Build Command 填 `echo "Static site ready"`，Publish Directory 填 `.`。本项目不需要密钥或环境变量。
