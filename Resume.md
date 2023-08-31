 <center>
     <h1>韦启蒙</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13668544995
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             598516744@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://mgv80.github.io/mgv-program/">MGV80</a>
         </span>
         ·<br/>
         <span>
         性别：男
         </span>|
         <span>
         年龄：27
         </span>|
         <span>
         工作经验：2年
         </span>|
         <span>
         元岛社区成员
         </span>
     </div>
 </center>


 ## <img src="assets/info-circle-solid.svg" width="30px"> 所获荣誉 

 - 天津商业大学信息工程学院新生军训“优秀学员”|2015.08 
 - 天津商业大学信息工程学院“优秀学生干部”|2018.08 15 
 - 天津商业大学软件工程专业网站页面设计小组赛“二等奖”|2018.10 
 - 中国国际“互联网+”大学生创新创业大赛贵州省金奖|2023.08

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，天津商业大学，软件工程专业，2015.9~2019.6

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **深圳法本信息技术股份有限公司，助理工程师，2020**
- **北京粉笔天下教育科技有限公司，助理老师，2022-2023**

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **公考培训面试学习网站**

- **技术架构：**Vue、Django、Django REST framework、mysql 

  为考生提供学习氛围良好的交流平台，节省开销，提升效率。采用前后端分离方式开发，为后续迭代提供可拓展性。

- **项目细节：** 

  1. Authentication用户认证设置、动态设置Permission、Authentication、Validators实现字段验证
  2. Serializer、ModelSerializer、动态设置Serializer
  3. Json Web Token方式登录、手机注册 / 支付宝支付、第三方登录
  4. Apiview方式实现API接口 / GenericView方式实现API接口、Viewset和Router方式实现API接口和URL配置、Django_filter、SearchFilter、OrderFilter、分页 / 通用Mixins
  5. 文档自动化管理 / Django REST framework的缓存、Throttling对用户和IP进行限速

  ---

  

- **数据管理平台**

- **技术架构：**Flume、HDFS、Spark Core、HBase、Redis、MySQL、ElasticSearch 

  该平台通过聚合第一方数据和第二方数据构造用户画像，将这些数据加工成有价值的用户标签，DSP 利用这些标签以 RTB 方式在ADX中进行精准的广告投放

- **项目流程：** 

  1. 每日数据存在服务器本地磁盘,利用 Flume 监听磁盘上的文件夹目录把数据 写入到 HDFS 
  2. 清洗初始日志数据转换为 Parquet 文件 
  3. 用 Spark Core 统计数据指标，并给每一个用户打上对应的标签，利用 Spark Graphx 图计算技术打通以不同 ID 出现的同一个用户数据,把每天的标签数据存 入到 HBase 中 
  4. 最终的标签数据存储到 ElasticSearch 中，对数据做衰减操作 
  5. 用 Spark SQL 从地域分布、终端设备、渠道等维度统计指标,包括原始请求 数、有效请求数、广告请求数、参与竞价数、竞价成功数、展示数、点击数、DSP 广告消费、DSP 广告成本等等 
  6. 将报表数据存入到 MySQL，生成可视化报表展示到前端页面 



## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 程序语言： Java、python、HTML|CSS|javascript
- 框架：Django、DRF(Django REST framework)、Vue、Bootstrap
- 工具：Pycharm、IDEA、Navicat、Visual Studio Code、Xmind