# 能够解出来的 "羊了个羊" 小游戏 Demo

<p>
    <img src="https://img.shields.io/github/package-json/v/StreakingMan/solvable-sheep-game" alt="version"/>
    <img src="https://img.shields.io/github/license/StreakingMan/solvable-sheep-game" alt="license" />
    <img src="https://img.shields.io/github/stars/StreakingMan/solvable-sheep-game?style=social" alt="stars" />
    <img src="https://img.shields.io/github/forks/StreakingMan/solvable-sheep-game?style=social" alt="forks" />
    <img src="https://img.shields.io/github/issues-raw/StreaKingman/solvable-sheep-game" alt="issues" />
    <img src="https://img.shields.io/github/issues-closed-raw/StreaKingman/solvable-sheep-game" alt="issues" />
    <img src="https://img.shields.io/github/commit-activity/m/StreakingMan/solvable-sheep-game" alt="commit-activity" />
    <img src="https://img.shields.io/github/last-commit/StreakingMan/solvable-sheep-game" alt="last-commit" />
    <img src="https://img.shields.io/github/deployments/StreakingMan/solvable-sheep-game/Production?label=proccution%20state" alt="production-state" />
    <img src="https://img.shields.io/github/deployments/StreakingMan/solvable-sheep-game/Preview?label=preview%20state" alt="preview-state" />
</p>

坑爹的小游戏（本来玩法挺有意思的，非得恶心人），根本无解（99.99%无解），气的我自己写了个 demo，
扫二维码或<a href="https://solvable-sheep-game.streakingman.com/" target="_blank">pc 浏览器体验</a>

**声明：本项目仅供交流，禁止商用！否则后果自负。基于此项目的二创都是欢迎的，但非二创请不要删除原仓库地址
（啥都不改唯独删除来源我真的会谢 🙄️，请尊重他人劳动成果）**

![qrcode.png](qrcode.png)

## Feature

-   弹出：弹出队列左侧第一个，无限次数
-   撤销：撤销上一次操作，无限次数
-   洗牌：哗啦哗啦，无限次数
-   关卡：50 关玩到爽，可直接跳
-   内置主题：金轮<img style="width:36px" src="src/themes/jinlun/images/肌肉金轮1.png" />、
    骚猪<img style="width:36px" src="src/themes/pdd/images/1.png" />、
    ikun<img style="width:36px" src="src/themes/ikun/images/kun.png" />（露出黑脚）、
    OW<img style="width:36px" src="src/themes/ow/images/ow.png" />主题等
-   自定义主题：自定义图片和音效，快速整活

开心就好 😄

![preview.png](preview.png)
![preview2.png](preview2.png)

## Contribution

vite+react 实现，欢迎 star、issue、pr、fork（尽量标注原仓库地址）

切换主题参考 `src/themes` 下的代码，欢迎整活

## Related Repo

<a href="https://github.com/opendilab" target="_blank">opendilab</a> 的 AI 整活！移步
<a href="https://github.com/opendilab/DI-sheep" target="_blank">DI-sheep：深度强化学习 + 羊了个羊</a>

<img style="width:360px" src="https://github.com/opendilab/DI-sheep/raw/master/ui/public/demo.gif" alt="" />

## Todo List

-   [x] 基础操作
-   [x] 关卡生成
-   [ ] UI/UX 优化
-   [x] 多主题
-   [ ] 计时、得分排行、保存进度机制
-   [ ] 性能优化
-   [x] BGM/音效
-   [ ] ~~点击时的缓冲队列，优化交互动画效果~~
-   [x] 该游戏似乎涉嫌抄袭，考证后补充来源说明
-   [ ] 桌面应用
-   [x] 路径区分主题
-   [x] 主题自定义
-   [ ] 本地图片、音频配置

## 二次开发

### 环境准备

安装以下内容

-   [git](https://git-scm.com/)
-   [node](https://nodejs.org/en/)

### 克隆仓库

直接克隆本仓库或者 fork

```shell
git clone https://github.com/StreakingMan/solvable-sheep-game.git
```

### 依赖安装

克隆到本地后，在项目内敲命令

```shell
npm install -g yarn

yarn install
```

### 调试运行

```shell
yarn dev
```

## License

[GNU GENERAL PUBLIC LICENSE Version 3](LICENSE.md)
