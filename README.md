# Canary3
Canary3 是一个支持用户自定义策略的量化交易平台。通过对 DeFi 数据的实时监控和流式计算，当满足预设交易策略规则时自动进行资产的买入和卖出。

- Canary3 对 UniSwap, PancakeSwap, SushiSwap 等主流 DeFi 应用进行持续性的监控。用户首先通过钱包登录 Canary3 平台，新建策略时选择要监控的 DeFi 产品，设置时间窗口，交易规则，并存入相应的 token 到 dXdY 中。
- Canary3 持续监控链上数据，当检测到当前状态满足策略设置的交易规则时，使用 dXdY 自动触发交易。

demo video: https://www.capcut.cn/share/7177950888768705830?t=1

目前后端部分还没完成(未开源)。前端见 [这里](fe/README.md)。
