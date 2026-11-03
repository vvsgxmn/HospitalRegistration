# 基于SpringBoot+Vue的智慧医院门诊预约挂号系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

HospitalRegistration（智医汇）是一款面向医院门诊的智能预约挂号平台，支持科室导诊、医生排班、智能导医、就诊卡充值、预约扣费、医生叫号开方与管理看板，普通患者、出诊医生与管理员三类角色协同，适合毕设、课设与学习参考。

## 主要功能模块

- **用户认证模块**：支持普通患者、出诊医生、管理员三类角色登录，JWT 鉴权并按角色跳转门户/工作台/后台
- **导诊预约模块**：科室导诊、医生检索、智能导医推荐科室、号源预约与挂号费支付
- **就诊服务模块**：就诊人与就诊卡充值、候诊进度跟踪、电子病历查看与处方缴费评价
- **医生工作台模块**：当日叫号队列、病历开方、本人排班号源与评价回复
- **后台运营模块**：数据看板、科室医生档案、全院排班、订单监管与内容审核
- **资讯运营模块**：健康资讯浏览、轮播海报与评价审核

## 技术架构

- **后端**：Spring Boot 2.7.18 + MyBatis-Plus 3.5.3 + JWT + Lombok
- **前端**：Vue 3.4 + Vue Router + Pinia + Element Plus + Vite 5 + ECharts
- **数据库**：MySQL 8.0

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E5%8C%BB%E7%94%9F%E5%8F%AB%E5%8F%B7%E5%B7%A5%E4%BD%9C%E5%8F%B0.png" alt="医生叫号工作台" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E5%8C%BB%E7%94%9F%E8%AF%A6%E6%83%85%E9%A2%84%E7%BA%A6.png" alt="医生详情预约" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E6%82%A3%E8%80%85%E9%A6%96%E9%A1%B5.png" alt="患者首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E6%88%91%E7%9A%84%E6%8C%82%E5%8F%B7%E8%AE%A2%E5%8D%95.png" alt="我的挂号订单" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E6%99%BA%E8%83%BD%E5%AF%BC%E5%8C%BB.png" alt="智能导医" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E7%A7%91%E5%AE%A4%E5%AF%BC%E8%AF%8A.png" alt="科室导诊" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E7%AE%A1%E7%90%86%E5%90%8E%E5%8F%B0%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF.png" alt="管理后台数据看板" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/hospitalregistration/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<!-- screenshots-end -->

## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）
