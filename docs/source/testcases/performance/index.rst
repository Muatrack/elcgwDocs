性能测试
===========

稳定性
-----------

满载设备24小时持续运行    
    #. 读子设备遥测数据
    #. 写子设备配置数据
    #. 周期分合闸

网关WEB可访问性
    * 周期发起http请求, 网关的web应当保持7*24小时能够响应请求。

        #. 查询**网关状态**信息
        #. 查询**断路器**列表

    * 监测网关是否发生重启、是否触发任务看门狗

断路器通信持续性
    * 周期性发起http请求，读取指定断路器的遥测数据、设置指定断路器的配置, 保持7x24小时响应请求
    
        #. 查询**断路器**的电流、电压、开关状态
        #. 设置**断路器**开关状态（设置于当前状态相反的值）

    * 监测网关是否发生重启、是否触发任务看门狗

MODBUS-TCP 可访问性
    * 固定间隔读取单台设备遥测数据
    * 固定间隔读取全量设备遥测数据


异常
-----------
    
断电
    ...

总线断开
    ...

网络断开
    #. 有线网-静态IP重连
    #. 有线网-动态IP重连
    #. 无线网-静态IP重连
    #. 无线网-动态IP重连

环境与机械
    #. 振动
    #. 温、湿度
    #. 粉尘、高盐

APP(略)
-----------