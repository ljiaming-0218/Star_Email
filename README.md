# 熔毁倒计时

一个无外部资源、无需安装依赖的单文件 Canvas 俯视潜行游戏。反应堆将在 90 秒后熔毁：收集三张密钥卡，解锁中央闸门，再进入逃生舱。直接打开 `index.html` 即可游玩；最佳通关时间保存在浏览器 localStorage 中。

## 操作

- WASD / 方向键：移动；Shift：冲刺；C：蹲行。
- E：交互；空格：投掷诱饵；P：暂停；M：静音。
- 触屏使用左侧摇杆和右侧按钮，建议横屏。
- 激光交替开关；配电箱可以暂时关闭附近的激光。40 秒后两名猎杀者苏醒，沿你 8 秒前的足迹追踪。

## 部署到 Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/ljiaming-0218/Star_Email)

点击按钮并连接此 GitHub 仓库，Render 将根据 `render.yaml` 创建静态站点。也可以手动创建 Static Site：分支选择 `main`，Build Command 填 `echo "Static site ready"`，Publish Directory 填 `.`。本项目不需要密钥或环境变量。
