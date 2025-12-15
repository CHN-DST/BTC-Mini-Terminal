# BTC-Mini-Terminal
一个让你上网时顺便盯盘的左下角小插件。它会实时更新比特币价格，还能弹出 K 线图给你看。不上交易所也能监控行情，摸鱼必备神器。

## ✨ 功能特点
- 📌 位于浏览器左下角的 BTC 价格面板
- 📈 内置迷你 K 线图（分、时、天）可切换
- 🔄 实时行情更新（可自定义周期）
- 🔌 支持 Binance / CoinGecko 自动切换
- 🪶 轻量不干扰使用，不影响任何网页布局
- 🌍 适用于所有网站（全站自动运行）

## 📦 安装方法
### 方法一：直接安装脚本（推荐）
1. 先安装油猴（Tampermonkey）扩展：
   - Chrome / Edge 浏览器
   - Firefox 浏览器
2. 点击安装脚本：
   > 👉 [点击这里安装脚本]([javascript:void(0)](https://greasyfork.org/zh-CN/scripts/558986-btc-mini-terminal))

### 方法二：手动复制脚本
1. 进入你的油猴扩展页面
2. 新建脚本
3. 将仓库中的脚本代码复制进去
4. 保存即可！

## 🖼 预览截图
> 示例：左下角 BTC 实时价格 + K 线图  
> （此处可插入截图链接：`![预览图](截图URL)`）

## ⚙️ 自定义设置
脚本使用以下持久化键（优先使用 GM_getValue / GM_setValue，回退到 localStorage）：
你可以修改脚本顶部的配置参数，示例如下：
```javascript
btc_widget_candles — 当前 K 线点数（50/100/200）。
btc_widget_collapsed — 折叠状态（1 表示折叠，0 表示展开）。
btc_widget_proxy — 可选代理前缀（例如 https://api.allorigins.win/raw?url=），会在脚本进行网络请求失败时作为代理尝试。
```

## 🛠 技术实现
使用 Tampermonkey + 原生 JS 编写
内置 Lightweight-Charts 迷你 K 线图
自动检测 API 可用性并切换

## 💬 反馈 & 联系
如果你发现问题或有功能建议：
可添加：
🐧：1431474270；
📫：chn.dst.cn@gmail.com

欢迎收藏 ⭐ Star！

📜 开源协议
本项目基于 MIT License 开源，欢迎自由修改与分发。
