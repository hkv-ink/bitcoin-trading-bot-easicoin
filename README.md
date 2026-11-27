# MountAlpha 阿尔法峰 EasiCoin 版（分析大师）

面向 EasiCoin USDT 永续合约的 Windows 中文比特币自动交易软件。支持比特币（BTC）和以太坊（ETH），提供模拟账户、独立的实盘控制、持仓与订单记录、加密客服、公告和文件接收。

## 下载 Windows 安装包

[下载 MountAlpha-EasiCoin-Setup.exe](https://github.com/hkv-ink/bitcoin-trading-bot-easicoin/releases/latest/download/MountAlpha-EasiCoin-Setup.exe) · [版本说明和 SHA-256 校验](https://github.com/hkv-ink/bitcoin-trading-bot-easicoin/releases/latest) · [中文安装说明](https://hkv-ink.github.io/bitcoin-trading-bot-okx/easicoin/)

需要 64 位 Windows。安装后从桌面「分析大师」进入，建议先使用模拟；模拟不需要交易所 API 或实盘授权。实盘需要有效设备授权、自己的 EasiCoin API 和手动启动。

已有分析大师文件传输版的用户，请在安全维护时段退出客户端及后台，再覆盖升级。**不要先卸载**：升级保留 API 设置、账本、授权和客服记录；卸载会清理运行和账户数据。安装器不会下单、平仓或撤单。

安装前可在 PowerShell 执行 `Get-FileHash -Algorithm SHA256 .\MountAlpha-EasiCoin-Setup.exe`，与发行页中的 `SHA256SUMS.txt` 对比。不要向他人发送 API 密钥、授权数据或整个已安装目录。

## 其他交易所版本

[Binance 英文版](https://github.com/hkv-ink/bitcoin-trading-bot-binance) · [OKX 欧易中文版](https://github.com/hkv-ink/bitcoin-trading-bot-okx)。三版的交易所接口、账户设置及授权相互独立。

MountAlpha 是独立第三方软件，并非 EasiCoin 官方产品。杠杆交易可能造成重大损失，模拟和历史结果不代表未来收益。缺价、断网或退出程序时，不保证本地保护继续执行。

客户端使用的开源客服组件对应源码和许可证见[附带源码包](https://github.com/hkv-ink/bitcoin-trading-bot-easicoin/releases/latest/download/MountAlpha-EasiCoin-Support-Source.zip)；不包含私有策略源码或后台工作台。
