# BTC-Mini-Terminal
一个让你上网时顺便盯盘的左下角小插件。它会实时更新比特币价格，还能弹出 K 线图给你看。不上交易所也能监控行情，摸鱼必备神器。

✨ 功能特点
📌 位于浏览器左下角的 BTC 价格面板
📈 内置迷你 K 线图（分、时、天）可切换
🔄 实时行情更新（可自定义周期）
🔌 支持 Binance / CoinGecko 自动切换
🪶 轻量不干扰使用，不影响任何网页布局
🌍 适用于所有网站（全站自动运行）


📦 安装方法
方法一：直接安装脚本（推荐）
先安装油猴（Tampermonkey）扩展
Chrome / Edge
Firefox

点击安装脚本：
👉 点击这里安装脚本


方法二：手动复制脚本
进入你的油猴扩展页面
新建脚本
将仓库中的脚本代码复制进去
保存即可！

🖼 预览截图

示例：左下角 BTC 实时价格 + K 线图

⚙️ 自定义设置（可选）
你可以修改脚本顶部的配置，例如：
const REFRESH_INTERVAL = 5000; // 行情更新间隔（毫秒）
const DEFAULT_TIMEFRAME = "1h"; // 默认 K 线周期：1m / 1h / 1d
const PANEL_SIZE = 280; // K 线图窗口大小


🔧 数据源说明
脚本支持两个数据源：
数据源	用途	备注
Binance	主行情来源（K线 + 实时报价）	更快更稳定
CoinGecko	备用数据（自动 fallback）	全球可访问


🛠 技术实现
使用 Tampermonkey + 原生 JS 编写
内置 Lightweight-Charts 迷你 K 线图
自动检测 API 可用性并切换
无外部 CDN（可选版本），避免 CSP & 网络阻断

📌 未来计划（TODO）
 添加多币种（ETH / SOL / BNB）
 添加深色 / 浅色主题自动切换
 添加简单指标（MA5 / MA30）
 添加交易所切换（OKX / Binance / Bybit）
 自定义面板位置（左下 / 右下 / 左上 / 右上）


💬 反馈 & 联系

如果你发现问题或有功能建议：
可添加：
🐧：1431474270；
📫：chn.dst.cn@gmail.com

欢迎收藏 ⭐ Star，让更多人看到！

📜 开源协议
本项目基于 MIT License 开源，欢迎自由修改与分发。
