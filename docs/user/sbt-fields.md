---
sidebar_position: 1
---

# SBT 模版与字段信息描述

### 模版
模版分为：身份(identity),  项目(project), 教育(education), 活动(activity), 空白(Blank)

### 如何选用模版？

- **身份(identity)：** DAO 内的身份，比如公会负责人

- **项目(project)：**在DAO内参与活动组织和举办的工作证明

- **教育(education)**：参与课程的凭证

- **活动(activity)**：作为活动参与者获得的活动纪念SBT

- **空白(Blank)**：如果有其他的需要，可以根据需要在空白模版中自行创造SBT

## 基础字段（必选）

- **Blank模版仅包含基础字段，可根据需要点击add添加其他字段**

- **Headline：**SBT 的标题

- **Image：**SBT图片，建议尺寸：800*800px

- **Description：**SBT描述

- **Type：**SBT类型，默认与模版名称相同，分为身份，项目，教育，活动

## 附加字段（选填，可留空）：

### **Identity**

- **Role:** SBT持有者的身份，如第0季/城市联络人计划/城市联络人

- **Level:** 身份的级别

- **Endorser:** SBT 发放者

- **Duration:** 身份有效期（开始时间和结束时间都可以是空白，如果永久有效可两个都空白）

- **Status:** 身份的状态为有效或过期

- **Notes:** 关于身份的备注，可以考虑包括SBT持有人昵称

- **Category:** 用于分类的字段，可以考虑创建为发放组织名称

### Education

- **Role:** 教育活动中的角色名称，通常为学员，如第0季/xx课程/学员

- **Endorser:** 教育内容提供方

- **Duration:** 教育课程起止时间（开始时间和结束时间都可以是空白，如果永久有效可两个都空白）

- **Status:** 课程的状态为完成或rug

- **Notes:** 关于教育的备注，可以考虑包括SBT持有人昵称

- **Category:** 用于分类的字段，可以考虑创建为发放组织名称

### Activity

- **Role:** 在活动中的角色，如参与者

- **Endorser:** SBT 的发放方，如xx项目组

- **Duration:**活动起止时间，如果当天开始当天结束请都填写当天

- **Status:** 活动的状态，为完成或rug

- **Notes:** 关于活动的备注，可以考虑包括SBT持有人昵称

- **Category:** 用于分类的字段，可以考虑创建为发放组织名称

### Project

- **Role:** 在项目中的角色，如志愿者

- **Leader:** 项目组织者

- **Duration:** 项目起止时间

- **Completion:** 项目的完成度，可填写百分比

- **Status:** 项目的状态，为完成或rug

- **Link:** 项目相关的文档或活动链接

- **Notes:** 关于项目的备注



### 自定义字段 (comming soon)

用户可根据实际需求自定义字段的名称和内容
