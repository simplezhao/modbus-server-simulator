## 介绍 
modbus server simulator 是基于pymodbus开发的模拟多个modbus客户端的软件。
实现的功能包括：
1. 支持modbus TCP 和 Modbus RTU 的client
2. 支持自定义站点号（1-255）
3. 目前仅支持读取 holding-register的点
4. 支持模拟正弦曲线，固定值，随机值等
5. 提供API接口和UI界面进行操作
5. 最多支持100个模拟设备（Modbus-TCP 和 Modbus-RTU设备共计）
## 计划
1. 实现modbus-rtu的支持

