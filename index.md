### 基本信息：
#### 姓    名：	程建	性    别：	男	
#### 出生年月：	1989/09/10	工作经验： 	8年	
#### 学    历：	本科	住    址：		
#### 专    业：	计算机科学与应用	联系电话：	17807132844	
#### 电子信箱：	chengjianjob@126.cn	
#### 籍    贯：	湖北省大冶市	
#### 求职意向：
#### 目标职位:	Windchill顾问
#### 目标地点:	
#### 【工作经验】
#### 时间	单位	职位	所属部门
#### 2010/04—2013/7	华为技术有限公司	Windchill顾问	IT
#### 2013/7-至今	联想集团	windchill自由顾问	研发部
#### 【IT技能】
#### 1.	Windchil PDMLink  Windchill PartsLink
2.	Oracle  Java，xml，JSP，SQL/PLSQL，javascript  JSON
【个人经验】
1.	熟练掌握 Windchill客制化开发,了解Windchill系统架构及业务实施，Windchill10.0底层函数修改。
2.	熟练掌握 工作流、生命周期、权限的配置、等OOTB操作。了解Windchill MVC 架构及开发，PLM系统常用的优化措施。
3.	专注于PDM项目开发，具备四年PDM项目开发经验，对PDM项目研究有深刻的理解。
【工作经历详细介绍】
项目名称: 美的PLM运维项目
1. 运维组负责人，负责Windchill 各模块，流程，报表维护，分析生产环境出现的各种问题
2. ESB和Webservice, restful与EAM，SRM，GPLM系统集成
3. 数据模型搭建，数据原型和技术预研工作
3. 实现Windchill 与Extjs开发的供应商平台管理系统数据传输
4. Windchill队列维护等
项目名称: 小米PLM项目
1.	分类基本信息维护
a. 在研发分类上维护编码规则，中文描述，英文描述规则
b. 在研发分类节点上维护跟采购分类的对应关系
c. 在采购分类上维护采购员, 四个流程角色的维护
2.	单个物料创建
a. 物料属性类型/OIR/Lifecycle
b.	物料编码生成 根据分类阶段上维护的编码规则，生成物料编码，建模一张表记录每个前缀的最大序列号，需要考虑编码查重的情况，合成编码后要到系统查重，有重复要再去取新的序列
c.	物料描述合成包 括中文描述，英文描述
d.	单个物料创建入口，OOTB UI调整
e.	创建物料UI采购分类根据研发分类自动带出
f.	厂商下来枚举从原厂列表读取
3.	物料批量创建
a. 批量创建菜单/UI批量创建入口，UI，UI上元素的enable，disable控制等（预览有错误，导入按钮要disable）
b.	选择分类节点分类节点可以多选
c.	生成Excel模板 需要考虑属性定义了枚举类型，要在excel中生成约束值，让用户选
d.	导入数据预校验、错误警告再UI显示创建场景下，如果属性windchill定义为必填要检查excel是否输入
e.	数据导入要考虑创建，编辑，维护二供物料等不同的场景
f.	名称/编码/描述生成在单个物料创建功能实现编码/描述合成功能，这里准备好合成输入，复用合成功能
g.	启动物料申请流程电子，机电按照小分类启动不同的物料申请流程，其他启动一个物料申请流程
h.	单元测试
4.	物料批量导出
a. 根据导入模板将物料批量导出
5.	物料集成
a.	SKU 与物料集成
b.	SKU与分类集成
c.	SAP集成
6.	BOM 模块
a. 定制一个展示BOM Tree 显示其 DescribeLink,UsageLink,SubstituteLink 关系
项目名称: 联想集团(深圳)有限公司
1.	项目：moto convergency product project
a.	负责SDD，DDD文档编写；
b.	ECM模块：OB，Reactive 流程开发; ECMECN，Freeze流程二次开发; 
c.	通用模块：Fastrack,设置参与者，RejectReason等通用功能开发;
d.	EMS模块：EMS 模块后期CR开发；(FullBom Report,DeltaBOM Report,Top Seller Flag)
e.	客制化一个Bom Tree,显示其UsageLink,DescribeLink,SubtituteLink关系
f.	同步数据到一个外部系统，通过监听 将Part，Document 等数据，传输到另外一个系统的数据库，考虑性能，建立中间表，利用Queue 每隔一定时间统一同步
2.	对Fiexd Bom 的一些流程进行回归测试; 2015/4-2015/5
3.	APEM SO Data Collection; 2014/9/2014/12
a.	负责SDD,DDD文档编写
b.	客制化一个定期执行生成POR报表的Queue.
c.	根据业务生成IPG/TPG的POR报表
d.	发送报表至指定FTP
4.	loadSheet 自动和手动share/unshared 2014/7-2014/9
a.	负责SDD,DDD文档编写
b.	实现手动通过loadsheet方式把MTM share到对应的ODM
c.	自动新建Document记录上述通过loadsheet share
d.	实现手动通过loadsheet方式把MTM从对应的ODM里移除
e.	对MTM更新自动起share流程时,检查流程里的MTM并且根据业务自动share对应MTM
5.	SWR项目模块开发：2013/7/2013/10
e.	负责SDD,DDD文档编写
f.	客制化带有SWR关系BOM结构详细页面
g.	SWRREPORT 报表函数大数据量的优化
h.	客制化SWR JpOffice报表
6.	ESS项目模块的开发：  2013/12-/2014/5
a.	负责SDD,DDD文档编写
b.	客制化windchill端接收CRM传送过来IDOC并解析
c.	客制化自动添加ESS_FLAG和ESS_PARTS信息到文档对象
d.	客制化Single country/Mutiple country不同逻辑下自动添加Service PNs到MTM BOM
e.	客制化datamigration工具以及其他工具类的维护
f.	项目上线支持
7.	CTO Simplification 2 CR004
a.	负责SDD,DDD文档编写
b.	客制化发放CC Table到LSC系统
c.	客制化读取文件CC Table Number List批量获取CC Table对象并按其规则修改主内容信息并上载主内容
d.	将所有CC TABLE打包上传FTP
项目名称: 华为终端TPDM项目一期（TPDM  Windchill10.0）
开发工具: eclipse Oracle
项目描述：终端TPDM项目，作为华为有史以来最大的一个PLM项目，此项目只是使用了windchill核心包。所有功能都有自主研发。
职责描述:
(1)	负责前期的概要设计文档，详细设计文档的编写。
(2)	文档模块通用组件的开发
(3)	独立完成制造文档验证流程，包括OPUC的编写，工作流模板，生命周期模板，数据库存储结构设计，前台页面的开发。
(4)	用axure软件设计首页，用extjs技术独立开发TPDM首页。
(5)	担任UI组SA负责 前台技术重构一套适用于华为研发系统的UI框架。并且制定一套前台开发规范。
项目名称: 华为终端TPDM项目迭代二期（TPDM  Windchill10.0）
开发工具: eclipse Oracle
项目描述：在一期的基础上扩展一些功能，并且优化系统。
职责描述： 
(1)协同完成软件版本发布流程
(2)后期前台页面的维护。
(3)文档流程自动赋值
项目名称:OPPO移动通讯有限公司PLM项目(Windchill10.0 M020)
开发工具: Myeclipse Oracle
项目描述：Windchill系统提供高科技解决方案，大力完善管理电子产品数据的业务流程实现自动化、文档、cad图纸、部件数据管控等等。本系统核心功能如下：
职责描述:
(1) 点击文件夹内容时，自动根据选择的文件夹类型显示对应数据                 
(2) 创建工作区后自动设置文件夹路径
(2) 工作区检入对象时增加一个提示灯
(3) 重构系统默认检索承担者的规则
(4) 文件夹中显示检出用户为中文名。
(5) 图纸外发流程供应商设置 
(6) 编码规则器、评审角色非空判断、BOM导出
(7) 我的任务中升级请求类型取消链接

项目名称：宝龙达信息技术股份有限公司ECAD/Windchill集成项目(Windchill9.1 M060)
开发工具: Myeclipse Oracle
项目描述： 集成ECAD与Windchill系统同步图纸数据 功能如下：
职责描述:
(1)技术开发需求业务分析、技术部署文档整理，ECAD Candence集成。
(2)ECAD与Windchill集成,通过把windchill中的物料数据发送到数据库，把物料关联的图纸文件发送到SERV-U(FTP)服务器。然后集成Cadence图纸软件和数据库， cadence通过配置取出数据库view的数据和SERV-U(FTP) 服务器的数据。
(3)设置SERV-U(FTP)服务器权限，指定服务器管理员和普通工程师的权限。

项目名称：博威科技(深圳)有限公司PLM项目(Windchill9.1 M060)
开发工具: Myeclipse Oracle
职责描述：
(6)	编辑BOM时位号栏位限制调整。
(7)	Part BOM报表的开发
(8)	CAPP集成
(9)	PDM系统运维
教育背景：
武汉国防信息学院	计算机科学与应用
自我评价：
热情随和，活泼开朗，具有进取精神和团队精神，有较强的动手能力、学习能力、抗压能力和良好协调沟通能力，适应短长期加班、出差。

![image](https://user-images.githubusercontent.com/94169462/141449618-bd78886e-0f18-4bc6-9f50-8cab6e5dbc03.png)

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).：
For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
