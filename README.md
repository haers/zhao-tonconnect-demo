# Demo dapp with @tonconnect/ui-react

Try it out https://ton-connect.github.io/demo-dapp-with-react-ui/

## Learn more about Ton Connect
- https://docs.ton.org/develop/dapps/ton-connect/
- https://github.com/ton-connect/sdk/tree/main/packages/ui


## 中文参考说明

本 Fork 用于 TON Connect 钱包接入学习，保留官方来源与演示，不是生产钱包或可直接部署的登录服务。

- 官方源码：https://github.com/ton-connect/demo-dapp-with-react-ui
- 官方在线演示：https://ton-connect.github.io/demo-dapp-with-react-ui/
- 官方协议与 SDK：https://github.com/ton-connect/sdk
- 可参考连接与 manifest、TON/Jetton 转账、签名、ton_proof、交易定位、合约部署与 Merkle 演示。真实签名或交易必须由使用者确认。
- src/server 实际通过浏览器 MSW 模拟 API，含公开 JWT 示例密钥；生产挑战、验签、一次性消费和会话签发必须在可信服务端完成，不能只换密钥继续放在浏览器。
- 本示例固定旧依赖版本，采用前按官方 SDK 当前文档核对；本 Fork 保留参考历史，不声称全部功能已通过真实钱包或主网验收。
- 示例仓当前未明确单独代码许可；引用与改造前需确认授权，SDK 自身许可证不自动覆盖整个示例。
