# 告警百科

> 这个页面会对告警做出解释，并注明是否重要

?> 善用左上角的搜索功能提升效率

?>  [联系厂家](/backbone/contact.md)



## 华为

- `APS_INDI`

  **解释：**

  SDH保护倒换

  **处理：**

  总配置 ➡️ SDH保护子网 ➡️ SDH保护子网管理

  查看子网总数，子网名称，判断在哪一个环

  |                  |                    |
  | ---------------- | ------------------ |
  | 运行（无请求）   | 正常               |
  | 运行（等待恢复） | 倒换过，已恢复     |
  | 运行（）         | 正在倒换中，有问题 |

- 



## 中兴



## 烽火



## 这些可以不用紧张

| 网管            | 告警名称               | 告警源                         | 定位信息                                                     | 备注                                                         |
| --------------- | ---------------------- | ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 华为二干WDM/SDH | R_LOF                  | 249-武威移动机房               | 1-N2SLO1-7(SDH-7)-SPI:1                                      | 经常上，无业务                                               |
| 华为二干WDM/SDH | R_LOF                  | 招银大厦                       |                                                              |                                                              |
| 华为二干WDM/SDH | FAN-FAIL               | 风扇故障                       | 张掖                                                         | 如果是新上的别的地市的告警，如定西联通大厦就要通知朱工以及地市设备维护人员要尽快换风扇以免高温烧坏设备，此时会产生TEMP_OVER的衍生告警 |
| 华为二干WDM/SDH | REMOTE_FAULT           | 局间-招银大厦/6-招银大厦电子架 | 0-招银大厦电子架-9-Y2C210-6(RX6-TX6)-CLIENT:1<br />0-招银大厦电子架-1-Y2C210-3(RX3-TX3)-CLIENT:1 |                                                              |
| 华为二干WDM/SDH | VACT_SQM_VC3           |                                |                                                              | 暂时未带业务，不重要                                         |
| 华为二干WDM/SDH | T_ALOS                 |                                |                                                              | 厂家说不太重要                                               |
| 中兴二干WDM/SDH | 保护组倒换状态告警     | 西环-二枢纽                    | [0-3-1]                                                      |                                                              |
| 中兴二干WDM/SDH | 保护组倒换状态告警     | 武威                           | [0-3-36]/[0-3-6]/[0-3-7]                                     |                                                              |
| 中兴二干WDM/SDH | 保护组倒换状态告警     | 招银                           | [0-3-17]                                                     |                                                              |
| 中兴二干WDM/SDH | 输入无广告警           | 东环-西峰                      |                                                              |                                                              |
| 中兴二干WDM/SDH | PDH-2M物理接口信号丢失 |                                |                                                              |                                                              |
| 烽火二干100G    | 单盘机电管理异常       |                                |                                                              |                                                              |

