# yonyoujob
用友数据部数据开发实习生日志

# 中山大学附属第一医院HRP项目
## 智慧财务中心、资产分析（数据财务数据中心）
### 工具
中文字段转换为拼音首字母大写  
输入字段名或备注，批量生成sql语句  
### 2022.6.20 第一天
#### 上午
报道，入职手续。
#### 下午
熟悉开发环境：华为云、navicat。  
练习sql题目

### 2022.6.21 第二天
#### 上午
练习sql题目
#### 下午
练习sql题目  
熟悉用友分析云（对数据做各种加工）、用友BDS、kettle

### 2022.6.22 第三天
#### 上午
学习kettle做数据转换
#### 下午
了解数据分层：STG层  ODS层 DWD层 DWM层 DWS层 ADS层   
了解增量、全量抽取，CDC策略（增量抽取，也被称为变化数据捕获）  
了解稽核校验、数据漂移、数据胡、数据建模、维度建模、ETL、webservice 数据分发  
  
在已存在的数据库中抽取数据经过DI清洗在用友分析云做报表、数据可视化：数据连接、数据准备、设计分析

### 2022.6.23 第四天
#### 上午
回总部开会，使用foxmail等
#### 下午
继续抽取数据过DI清洗在用友分析云做报表、数据可视化。

### 2022.6.24 第五天
#### 上午
继续完成报表工作，发现大数据量报表加载过慢问题、第三方数据库地址过期问题。
#### 下午
了解数据中心架构：分层为ODS DW DM
了解ETL策略：全量同步，增量同步
    事实表、维度表
    Kimball所提的维度建模
学习hadoop搭建
优化报表，正在解决：大数据量报表、筛选控件。

### 2022.6.27 第六天
#### 上午
继续完成报表工作。
#### 下午
完成报表。暂无后续工作。
学习Hadoop。

### 2022.6.28 第七天
#### 上午
自习Hadoop
#### 下午
自习hadoop  
对比新旧报表信息，找出错误信息。

### 2022.6.29 第八天
#### 上午
自习hadoop
#### 下午
完成第三方中间库、stg层、ods层之间的接口对接。

### 2022.6.30 第九天
#### 上午
对接项目历史第三方数据库到ods层，完成数据字典。
#### 下午
核对数字资产中心用户权限，核查数据准确性。

### 2022.7.1 第十天
#### 上午
开会
#### 下午
继续协助完成数据字典

### 2022.7.4~7.7
#### 放假

### 2022.7.8 第十一天
#### 上午
从HRP系统增量抽取数据到DW，根据时间范围。
（将生产环境的数据同步到测试环境，以便更方便的进行测试和bug定位）
kettle数据同步、数据比较
kettle位置参数、命名参数、变量
orical的逻辑结构包括表空间（tablespace）、段(segment)、数据块(data block)、模式对象(schema object)
#### 下午
从第三方库表经过DI(KETTLE)全量抽取到stg层，写sql、查数据字典

### 2022.7.11 第十二天
#### 上午
继续完成从第三方库表经DI(KETTLE)全量抽取到stg层
#### 下午
从hrp数据中心报表取数据至stg层

### 2022.7.12 第十三天
#### 上午
完成了第三方库全量抽取到stg层
#### 下午
完成了从HRP数据中心报表搜索原表全量抽取到stg层，用Java编写脚本通过io流读取文本创建百量级表sql语句（给无含义的字段名都更改为字段意思的拼音首字母大写）

### 2022.7.13 第十四天
#### 上午
完成在kettle完成增量抽取的作业流程。
#### 下午
完成将全量增量抽取的转换串联起来。

### 2022.7.14 第十五天
#### 上午
自学Hadoop
#### 下午
自学Hadoop

### 2022.7.15 第十六天
#### 上午
自学Hadoop
#### 下午
完成资产分析指标卡 （在kettle中记录来源表和来源字段）

### 2022.7.18 第十七天
#### 上午
完成资产分析指标卡（根据分析云完成字典）
#### 下午
完成资产分析指标卡 （根据分析云完成字典）

### 2022.7.19 第十八天
#### 上午
完成资产分析指标卡 （根据分析云完成字典）
#### 下午
通过kettle从excel导入数据到数据库（完整的建表建库和kettle设置转换）

### 2022.7.20 第十九天
#### 上午
自学hadoop 
#### 下午
kettle把转换都串起来

### 2022.7.21 第二十天
#### 上午
kettle把转换都串起来
#### 下午
自学Hadoop


