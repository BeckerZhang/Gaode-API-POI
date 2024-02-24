# **Gaode-API-POI**
to extract the specific POI by utilizing the Gaode API in a specific polygon

# **需要输入的参数**
### **将polygon改成请输入爬取范围坐标串，经度在前，纬度在后，坐标对用'|'分割。经纬度小数点后不得超过6位,首尾坐标对需相同**
_**polygon**_
='120.60961,31.329655|120.629437,31.33265;120.634152,31.332134|120.63657,31.323252|120.634757,31.32129|120.642615,31.292677|120.61638,31.289165|120.610456,31.288028|120.609973,31.289681|120.607675,31.299186|120.605137,31.30621|120.601993,31.309412|120.600301,31.324905|120.603202,31.326144|120.605983,31.329139|120.60961,31.329655'
## **将types改成请输入需要爬取的POI编码串，用'|'分割**
_**types**_ = '090000|090100|090101|090102|090200|090201|090202|090203|090204|090205|090206|090207|090208|090209|090210|090211|090300|090400|090500' 
（types为高德指定的编码信息，见附件amap_poicode.xlsx.zip）

_**key**_ = 'Your_Key'

_**keyword**_ = '医院'

**# 输出的结果（如下表）**
| Name                               | Type                                              | Longitude   | Latitude    | Longitude (WGS84) | Latitude (WGS84) |
|------------------------------------|---------------------------------------------------|--------------|-------------|---------------------|------------------|
| 金阊医院                             | 医疗保健服务;综合医院;综合医院                        | 120.603337   | 31.308515   | 120.599167         | 31.310699       |
| 苏州大学附属儿童医院景德路院区           | 医疗保健服务;专科医院;专科医院\|医疗保健服务;综合医院;综合医院 | 120.612737   | 31.309775   | 120.608465         | 31.311947       |
| 苏州市立医院本部                       | 医疗保健服务;综合医院;三级甲等医院                     | 120.621205   | 31.302023   | 120.616932         | 31.304196       |
| 苏州市立医院(北区)                     | 医疗保健服务;综合医院;三级甲等医院                     | 120.603464   | 31.321736   | 120.599191         | 31.323920       |
| 苏州市立医院东区                       | 医疗保健服务;综合医院;三级甲等医院                     | 120.626775   | 31.318828   | 120.622502         | 31.321002       |
| 苏州大学附属第一医院十梓街院区           | 医疗保健服务;综合医院;三级甲等医院                     | 120.634293   | 31.304140   | 120.630021         | 31.306314       |
| 苏州市中医医院(景德路门诊部)             | 医疗保健服务;诊所;诊所                               | 120.611534   | 31.309865   | 120.607261         | 31.312038       |
| 苏州一〇〇医院                         | 医疗保健服务;综合医院;综合医院                        | 120.627078   | 31.295577   | 120.622806         | 31.297751       |
| 苏州沧浪医院东大街院区                   | 医疗保健服务;综合医院;综合医院                        | 120.617828   | 31.296376   | 120.613556         | 31.298550       |
| 姑苏区金阊街道桃花坞社区卫生服务站         | 医疗保健服务;医疗保健服务场所;医疗保健服务场所           | 120.611465   | 31.325946   | 120.607192         | 31.328120       |
| 双塔街道社区卫生服务中心                 | 医疗保健服务;诊所;诊所                               | 120.625839   | 31.301508   | 120.621566         | 31.303682       |
         
