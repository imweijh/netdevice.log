# 使用logstash处理网络日志


![image](https://user-images.githubusercontent.com/23710675/117534920-0a1f4780-b026-11eb-9059-3f17f977fe55.png)


- 网络设备很多时间不准且不是我能控制，udp日志的接收时间和实际发生时间基本一致，所以不用date filter特殊处理。
- 根据message字段正则匹配，加颜色高亮显示特别关注
![image](https://user-images.githubusercontent.com/23710675/117535095-b7925b00-b026-11eb-8545-30ec6f4c0dc9.png)


