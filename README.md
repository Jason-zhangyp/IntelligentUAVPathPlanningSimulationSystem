# IntelligentUAVPathPlanningSimulationSystem
智能无人机路径规划仿真系统是一个具有操作控制精细、平台整合性强、全方向模型建立与应用自动化特点的软件。它以A、B两国在C区开展无人机战争为背景，该系统的核心功能是通过仿真平台规划无人机航线，并进行验证输出，数据可导入真实无人机，使其按照规定路线精准抵达战场任一位置，支持多人多设备编队联合行动。

系统以开源无人机仿真平台SITL为支撑，通过FlightGear渲染真实战场环境，集成了动力学模型建模、二维俯视、三维模拟、脚本控制、地面站监控、数据处理等功能，此外，仿真系统支持加载多种全球地图，模拟各大重点地域的三维环境，可应用于全球各处遥感监测的场景中。
######1. 软件界面
![软件界面](https://upload-images.jianshu.io/upload_images/11477676-8e8e1baaf5e4765f.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)
######2. 软件架构（部分扩展功能的插件待实现）
![软件架构](https://upload-images.jianshu.io/upload_images/11477676-75a58c797fd81724.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
######3. 代码编写
![代码编写](https://upload-images.jianshu.io/upload_images/11477676-99430237636eddc4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
######4. 多维视图
![二维视图（一）](https://upload-images.jianshu.io/upload_images/11477676-ee18d747a10e15ef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![二维视图（二）](https://upload-images.jianshu.io/upload_images/11477676-b106388223e90c9f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![三维视图](https://upload-images.jianshu.io/upload_images/11477676-d35cca6b7dc56251.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
######5. 无人机控制
![控制台控制](https://upload-images.jianshu.io/upload_images/11477676-85ba41325f9385d1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![智能控制](https://upload-images.jianshu.io/upload_images/11477676-0a5f03880f5782c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![地面站控制](https://upload-images.jianshu.io/upload_images/11477676-7adb73baeee55dea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
######6. 制定飞行任务
![飞行任务（一）](https://upload-images.jianshu.io/upload_images/11477676-e99d85e3d16fec4f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![飞行任务（二）](https://upload-images.jianshu.io/upload_images/11477676-ffd111fcf902e18b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![飞行任务（三）](https://upload-images.jianshu.io/upload_images/11477676-2609a653c0741d08.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##二、解决问题

智能无人机路径规划仿真系统解决了普通无人机无法精准规划路径的问题，且普通无人机不够托底，不便控制，难以运用于实际战争。本软件可以预先为飞行任务设计航线，使用飞行模拟器记录无人机在飞行任务中的实时状态，通过地面站模块强化无人机在体系对抗中的受控度，模拟无人机群联合行动的战术战法，然后输出航行数据供真实无人机使用，将无人机体型短小、行动迅速、资源庞大的优势尽可能的释放出来。

##三、应用场景及效益

截止目前，全世界已有40多个国家在从事研究和生产无人机，60多个国家在使用无人机。无人机在战场发挥作用是未来战争的趋势。

使用该软件的优点是吸收国外已获得成果，将运行环境从Linux系统重新编译移植到Windows等其他操作系统，除仿真三维环境模块外均使用Python语言编写，程序易维护、易修改。通过Pyqt5编写的软件界面集成了软件各个模块，加入后台提示功能，设计智能控制脚本简化系统使用流程，联动FlightGear模拟器、MissionPlanner地面站程序进行可视化，以提高真实无人机飞行路径精准度、指定飞行计划为根本目的。

##四、感谢
**CSDN：**
https://blog.csdn.net/qinguoxiaoziyangyue/article/details/77712064
https://blog.csdn.net/guojunxiu/article/details/79158843
https://blog.csdn.net/huihut/article/details/86587782
https://blog.csdn.net/u010946448/article/details/90718264
https://blog.csdn.net/jzhd2015/article/details/108987818
https://blog.csdn.net/jzhd2015/article/details/108663961<br>
**Zhihu:**
https://zhuanlan.zhihu.com/p/50900595
https://zhuanlan.zhihu.com/p/62017292
**Freesion：**
https://www.freesion.com/article/2344608320/
**Gitee：**
https://gitee.com/wwy2018/XTDrone
**Github：**
https://github.com/dhondta/dronesploit

简书地址：
Gitee：
欢迎star！！！
