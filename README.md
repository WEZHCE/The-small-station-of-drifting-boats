# ⛵ 船只悠悠的小站

> 一条慢悠悠的船，泊在互联网边上。
> 一个整站伪装成"一台老电脑"的手写个人主页——从开机动画、桌面窗口、任务栏，到 CRT 关机、BIOS 重启，全流程都是戏。

**在线访问**：[wezhce.github.io/The-small-station-of-drifting-boats](https://wezhce.github.io/The-small-station-of-drifting-boats/)

| 白天 | 夜航模式（19:00~6:00 自动开启） |
|---|---|
| ![](docs/preview-day.png) | ![](docs/preview-night.png) |

## ✨ 它是什么

- 纯 `HTML + CSS + JS` 单文件手写，**没有框架、没有后端、没有构建**，全部代码在一个 `index.html` 里
- 复古 Win98 视觉：记事本窗口、凹凸按钮、手绘像素画、CRT 开机
- 留言板基于 GitHub Discussions（[giscus](https://giscus.app/zh-CN)），留言永久保存在本仓库里，全世界可见

## 🖥 这台"电脑"有什么

**开机与关机**
- 粒子汇聚开机动画（每个浏览器会话只播一次，尊重系统"减少动态效果"设置）
- 开始菜单 → 关机：CRT 白线坍缩收场；船侧翻睡觉冒 Zzz；再点电源键，BIOS 自检打字 + 蜂鸣，白闪重新开机

**桌面与任务栏**
- 任务栏：开始菜单、cmd、帮助.chm、计算器、扫雷.EXE、托盘点灯、真实时钟
- 仿真 cmd：启动 banner、`↑↓` 历史命令、`help / ver / echo / tree / start / sudo` 等一整套命令（彩蛋无数）
- 帮助.chm：全站彩蛋的官方使用手册（弹窗，可拖动）
- 所有窗口都能拖标题栏移动、点击置顶

**内容板块**
- 关于我 / 近况（项目带仓库链接）/ 像素相册（灯箱浏览，←→ 切换）/ 留言板（giscus + 全文搜索）
- 船舱日记：按天轮换的小日记，可前后翻页
- 漂流瓶：一键从留言里随机捞一条陌生人的话

**彩蛋（冰山一角，完整清单在站内 帮助.chm）**
- 站名 / 副标题 / 运行天数 / 板块标题 / 便利贴 / 时钟——挨个点过去，全都有回应
- 小船养成：点右下角小船攒航程，10 海里红帆 / 30 海鸥 / 60 金帆 / 100 夜灯
- Konami Code（`↑↑↓↓←→←→BA`）触发彩虹模式
- 60 秒不动鼠标，屏保自己开演：小船在星空里替你开船
- 夜航模式：整站深夜海色，小船点灯，giscus 同步换夜主题

## 🗂 仓库结构

```
├── index.html       全站本体（单文件应用，含全部样式与脚本）
├── 404.html         404 彩蛋页（翻船 + 回甲板）
├── theme.css        giscus 白天主题（羊皮纸）
├── theme-night.css  giscus 夜航主题（深夜海色）
└── docs/            截图
```

## 🔧 想改成你自己的？

所有内容都在 `index.html` 里，搜索关键词即可定位：

| 想改什么 | 搜哪里 |
|---|---|
| 昵称 / 生日 / 社交链接 | `关于我` |
| 近况与项目链接 | `近况` |
| 船舱日记 | `var DIARY` |
| 每日副标题 / 宜忌语录 | `SUBS` / `YI` / `JI` |
| 留言板配置 | `GISCUS_CFG`（仓库需开启 Discussions 并安装 [giscus 应用](https://github.com/apps/giscus)） |
| 像素画 | `SPRITES`（16×16 字符画，渲染器自动加描边 / 受光 / 投影 / 光晕） |

## ▶ 本地预览

直接双击 `index.html` 即可（留言板、漂流瓶等功能需要联网）。
或者起个静态服务器：`npx serve .`

## 📄 其他

- © 2026 船只悠悠 — 手写，慢慢更新
- 留言数据保存在本仓库的 [Discussions](https://github.com/WEZHCE/The-small-station-of-drifting-boats/discussions) 里
