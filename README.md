<div align="center">

# 小亿套利

### 🚀 加密货币套利工具

[![GitHub stars](https://img.shields.io/github/stars/Xiaoyiclub/xiaoyi?style=for-the-badge)](https://github.com/Xiaoyiclub/xiaoyi/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Xiaoyiclub/xiaoyi?style=for-the-badge)](https://github.com/Xiaoyiclub/xiaoyi/network)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](LICENSE)

[🌐 官网](https://xiaoyiclub.com) | [📱 Twitter](https://x.com/xiaoyiclub) | [💬 Telegram](https://t.me/xiaoyiclub) | [👥 加入社群](https://t.me/xiaoyi2023)

</div>

---

## 📖 目录

- [软件简介](#软件简介)
- [核心特性](#✨-核心特性)
- [硬件要求](#-硬件要求)
- [软件安装](#-软件安装)
- [验证安装](#-验证安装)
- [检查可访问性](#-检查可访问性)
- [开始使用](#-开始使用)
- [官方高额返佣](#-官方高额返佣)
- [常见问题](#-常见问题)
- [联系我们](#-联系我们)
- [许可证](#-许可证)

---

## 软件简介

小亿套利(免费版)是一款加密货币套利工具，支持各主流交易所的现货vs现货、永续vs永续以及现货vs永续的对冲套利。

## ✨ 核心特性

<table>
<tr>
<td width="50%">

### 🎯 多策略支持
- 现货 vs 现货套利
- 永续 vs 永续套利
- 现货 vs 永续套利
- 自定义策略配置

</td>
<td width="50%">

### 🏦 多交易所支持
- Binance / OKX / Bybit
- Bitget / Gate / Kucoin
- Huobi / Hyperliquid
- Backpack / Aster

</td>
</tr>
<tr>
<td width="50%">

### 🔒 安全可靠
- 本地部署，数据安全
- API权限可控
- 实时风控监控
- 自动止损保护

</td>
<td width="50%">

### 💰 高额返佣
- 最高60%手续费返佣
- 永久有效，自动到账
- 降低交易成本
- 提升整体收益

</td>
</tr>
</table>

---

## 💻 硬件要求

需要拥有独立的公网IP的服务器，可在亚马逊云、阿里云、腾讯云等租用符合特定网络（如可直接访问交易所官网）要求的服务器

- **操作系统**：CentOS 7.x 或 CentOS 8.x

- **最低硬件**：2核2G

## 📦 软件安装

使用PuTTY或其他SSH管理软件连接并登录您的服务器，在命令行中输入如下代码，耐心等待服务器下载安装包并自动安装。

```bash
rpm -ivh https://github.com/Xiaoyiclub/xiaoyi/releases/download/v1.0.0/xiaoyi-free-1.0.0.rpm
```

**注意事项**：非root权限请在上述安装命令前加sudo，如下所示：

```bash
sudo rpm -ivh https://github.com/Xiaoyiclub/xiaoyi/releases/download/v1.0.0/xiaoyi-free-1.0.0.rpm
```

## ✅ 验证安装

在服务器命令行中输入如下代码并回车：

```bash
systemctl status cbbshdfree
```

如在命令行窗口看到"**Active: active (running)**"字样，则表示软件已正常运行。

### 本地电脑浏览器打开管理网址

在你本地电脑的浏览器中输入：

```plaintext
http://您的服务器公网IP:6680/
```

## 🔧 检查可访问性

在你本地电脑的浏览器中输入`http://您的服务器公网IP:6680/`，如果无法访问，则检查"云服务器安全组（防火墙）"和"操作系统防火墙"这两项：

### 1. 云服务器安全组（防火墙）

登录云服务器控制台，确保云服务器所在安全组（防火墙）开放了**6680端口**。

### 2. 操作系统防火墙

在云服务器安全组（防火墙）确认已开放了6680端口后，如果仍然无法正常访问，请在操作系统防火墙中开放6680端口，具体方法请查阅搜索引擎解决。

## 🚀 开始使用

在您本地电脑的浏览器中输入`http://您的服务器公网IP:6680/`，如果无法打开相应网址，请重新执行"验证安装"和"检查可访问性"这两个步骤。

软件初始登录时，未配置任何登录账户，登录时的登录选项请选择"**通讯密钥**"登录，默认密码为**123456**，登录后请立即修改通讯密钥。

最后在软件中的"**通用配置**"→"**软件授权**"里，登录您的邮箱即可开始使用，登录邮箱仅为方便开发者统计数据，不影响软件的免费使用。

## 🎁 官方高额返佣

小亿套利经过与各大交易所沟通，已获得**40%-60% 永久手续费返佣**，我们将提供给各位伙伴，以降低量化交易成本，提高收益。

| 交易所 | 返佣比例 | 邀请码 | 注册链接 |
|--------|----------|--------|----------|
| **Binance** | 永久次月减免20% | XIAOYI88 | [注册账户](https://www.binance.com/join?ref=XIAOYI88) |
| **OKX** | 永久次月减免40% | XIAOYI88 | [注册账户](https://www.okx.com/join/XIAOYI88) |
| **Bybit** | 永久自动减免45% | - | [注册账户](https://partner.bybit.com/b/tw00000033) |
| **Bitget** | 永久自动减免45% | XIAOYI88 | [注册账户](https://partner.bitget.com/bg/xiaoyi88) |
| **Gate** | 永久自动减免60% | XIAOYICB | [注册账户](https://www.gate.tv/share/xiaoyicb) |
| **Kucoin** | 永久自动减免60% | XIAOYI88 | [注册账户](https://www.kucoin.com/r/af/XIAOYI88) |
| **Huobi** | 永久自动减免58% | XIAOYI88 | [注册账户](https://www.htx.com.pk/invite/zh-cn/1h?invite_code=xiaoyi88) |
| **Hyperliquid** | 永久自动减免4% | XIAOYI | [注册账户](https://app.hyperliquid.xyz/join/XIAOYI) |
| **Backpack** | 永久自动减免35% | XIAOYI | [注册账户](https://backpack.exchange/join/xiaoyi) |
| **Aster** | 永久自动减免10% | 431284 | [注册账户](https://www.asterdex.com/zh-CN/referral/431284) |

### 返佣支付

- **实时自返**：直接到主账户
- **次月返佣**：次月1-2个工作日到账

### 返佣说明

- 各交易所因政策变化导致返佣比例变更，我们将同步调整
- **Binance、OKX**：单月低于 10U 不支付
- **Bitget、Bybit、Gate、Huobi**：注册后请告知UID和注册邮箱，需要后台设置

## ❓ 常见问题

<details>
<summary><b>Q1: 需要什么样的服务器配置？</b></summary>

最低配置：2核2G，独立公网IP，CentOS 7.x/8.x系统。推荐使用阿里云、腾讯云、AWS等云服务商。

</details>

<details>
<summary><b>Q2: 软件是免费的吗？</b></summary>

是的，软件完全免费使用。我们通过交易所返佣来维持项目运营。

</details>

<details>
<summary><b>Q3: 如何获得更高的返佣比例？</b></summary>

使用我们提供的专属邀请链接注册交易所账户。部分交易所（Bitget、Bybit、Gate、Huobi）需要提供UID和邮箱进行后台设置。

</details>

<details>
<summary><b>Q4: 软件安全吗？</b></summary>

软件部署在您自己的服务器上，所有数据完全由您控制。API密钥仅需只读和交易权限，不需要提币权限。

</details>

<details>
<summary><b>Q5: 套利收益如何？</b></summary>

收益取决于市场波动性、资金量、手续费等多种因素。一般情况下，年化收益在5%-20%之间。请理性看待收益，注意风险控制。

</details>

<details>
<summary><b>Q6: 遇到问题如何获得帮助？</b></summary>

您可以通过以下方式获得帮助：
- 加入Telegram群组：[t.me/xiaoyi2023](https://t.me/xiaoyi2023)
- 在GitHub提交Issue
- 访问知识库：[xiaoyiclub.com](https://xiaoyiclub.com)

</details>

## 📞 联系我们

- **Twitter**：[x.com/xiaoyiclub](https://x.com/xiaoyiclub)
- **Telegram**：[t.me/xiaoyiclub](https://t.me/xiaoyiclub)
- **Telegram 群组**：[t.me/xiaoyi2023](https://t.me/xiaoyi2023)
- **小亿知识库**：[xiaoyiclub.com](https://xiaoyiclub.com)

## 📄 许可证

本项目仅供学习交流使用，投资有风险，请谨慎决策。

---

## 💖 支持项目

如果这个项目对您有帮助，请给我们一个 ⭐️ Star！

---

<div align="center">

**[⬆ 返回顶部](#小亿套利)**

Made with ❤️ by [Xiao Yi](https://github.com/Xiaoyiclub)

</div>
