# 2018-ORANGE-FINANCIAL-BIG-DATA-top9
2018-2018年甜橙金融杯大数据建模大赛-初赛第四-复赛线上11-决赛9-复现top1解决方案 

=================================================================================  
**[赛题链接](http://www.pkbigdata.com/common/cmpt/2018%E5%B9%B4%E7%94%9C%E6%A9%99%E9%87%91%E8%9E%8D%E6%9D%AF%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%BB%BA%E6%A8%A1%E5%A4%A7%E8%B5%9B_%E7%AB%9E%E8%B5%9B%E4%BF%A1%E6%81%AF.html)**  
**赛程时间**：2018.10.20-2018.12.14    
**队名**：火锅肠粉烤鸭     
**参与人**：[狗头哥]()、[wangjx](https://github.com/wangjinxile)、[小兔子乖乖](https://github.com/PandasCute)      
百度云盘下载链接:为避免数据丢失，提供数据集下载地址链接：   
**初赛数据集**链接：https://pan.baidu.com/s/1_DfbjLh-zzx2SMNyukIIjQ 提取码：81hy  
**复赛数据集**链接：https://pan.baidu.com/s/1glQ2JN8SgfmgldQce1visw 提取码：vmgx    
# 数据说明  
| 操作详单数据字典  |
| 字段名      | 中文解释 |  字段说明  |
|:-------:|:-------:|:-------:|
| UID      | 用户编号 |  /  |
| day      | 操作日期 |  连续的日期标识，E.g,1为第一天，2为第二天，以此类推  |
| mode      | 操作类型 |  操作类型（例如：修改密码、查询余额...）  |
|success      | 操作状态 |  /  |
|time      | 操作时间点 |  /  |
|os      | 操作系统 |  /  |
|version      | 客户端版本号 |  /  |
|device1      | 操作设备参数1 |  设备名称加密，原字段加“Jack's iphone”  |
|device2      | 操作设备参数2 |  设备型号  |
|device1      | 操作设备唯一标识1 |  设备号唯一标识加密，可用于安卓类设备的唯一标识  |
|device2      | 操作设备唯一标识2 |  设备号唯一标识加密，可用于安卓类设备的唯一标识  |
|mac1      |MAC地址 |  操作设备MAC地址编码加密，原字段如“38：XX:XX:XX:XX:92”  |
|ip1     | ip地址 |  操作设备IP地址编码加密  |
|ip2     | ip地址 |  操作电脑IP地址编码加密  |
|device_code3     | 操作设备唯一标识3 |  设备号唯一标识加密，可用于苹果类设备的唯一标识  |
|mac2     | mac地址 |  WIFI MAC地址编码加密，原字段如“02：XX:XX:XX:XX:03”  |
|wifi     | WIFI名称 |  WIFI名称，原字段“A的wifi”  |
|geo_code     | 地理信息 |  经纬度GeoHash编码  |
|ip1_sub     | IP地址 |  前三位操作设备IP地址编码加密（ip前三位IP地址）比如，原字段为12,34,56,7和12,34,56,8的ip地址前三位都为12,34,56，故脱敏后的值是一样的   |
|ip2_sub     | ip地址 |  前三位操作电脑IP地址编码加密（ip2前三位IP地址）  |
