# flash‑trade‑core

**高并发核心交易与异步清结算参考架构**<br>• 通用状态机引擎驱动订单生命周期，支持分布式异步对账防漏单<br>• `Redis + Lua` 防重幂等、乐观锁防覆盖、MQ 削峰与死信补偿<br>• 集成 `K8s` 部署与 `SkyWalking + Prometheus` 监控大盘（单节点压测 P99 < 35ms）
