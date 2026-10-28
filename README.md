# 熔毁倒计时

一款无需安装依赖的俯视潜行游戏。反应堆即将熔毁，潜入随机生成的设施，收集三张密钥卡、解锁中央闸门并启动逃生舱。直接打开 `index.html` 即可游玩，也可以在仓库目录执行 `python3 -m http.server 8765` 后在浏览器中打开本地服务。

## 行动指南

- 选择探索、标准或极限难度：难度影响剩余时间、巡逻速度和猎杀者苏醒时间。各难度的最佳通关时间分别保存在浏览器 localStorage 中。
- WASD / 方向键移动，Shift 冲刺，C 蹲行；E 交互，空格投掷诱饵，P 暂停，M 静音。
- 触屏使用左侧摇杆和右侧按钮，建议横屏。
- 观察巡逻机器人的视野与声音反应。激光交替开关，配电箱可以暂时关闭附近的激光。
- 入侵一次性安保终端，可使巡逻机器人停机 8 秒；猎杀者不受影响。留意小地图上青色的终端标记。
- 解锁闸门后，前往逃生舱并坚守 3 秒完成撤离。两名猎杀者会在行动进行一段时间后苏醒，追踪你 8 秒前的足迹。

## 部署到 Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/ljiaming-0218/Star_Email)

连接此 GitHub 仓库后，Render 将根据 `render.yaml` 创建静态站点。也可以手动创建 Static Site：分支选择 `main`，Build Command 填 `echo "Static site ready"`，Publish Directory 填 `.`。本项目不需要密钥或环境变量。
