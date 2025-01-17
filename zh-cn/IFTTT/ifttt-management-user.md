# 触发类

!> **更新时间**：{docsify-updated}  


## 开启或关闭用户场景
>开启或关闭用户场景。
 1、接口定义

?> **接入地 址：**  `/iftttscene/scene/operationUserScene`  
 **HTTP Method：** POST

**输入参数**  

| 参数名  | 类型    | 最大长度  |位置  | 必填|说明|
| ------- |:------:|:-----:|:----:|:----:|:----:|         
| familyId| String |32| Body| 必填|家庭Id | 
| sceneId| String |32| Body| 必填|&emsp; | 
| status| String |32| Body| 必填|目前可取值 0：取消激活；1：激活场景| 
     

**输出参数**  

|   名称      |     类型      | 位置  |必填 |说明|
| ------------- |:----------:|:-----:|:--------:|:---------:|
|  data  | Object| Body  |必填|显示为：null|



## 手动执行用户场景

>手动执行用户场景。


 1、接口定义

?> **接入地 址：**  `/iftttscene/scene/triggerUserScene `  
 **HTTP Method：** POST

**输入参数**  

| 参数名  | 类型    | 最大长度  |位置  | 必填|说明|
| ------- |:------:|:-----:|:----:|:----:|:----:|         
| familyId| String |32| Body| 必填|家庭Id | 
| sceneId| String |32| Body| 必填|&emsp; | 

     

**输出参数**  

|   名称      |     类型      | 位置  |必填 |说明|
| ------------- |:----------:|:-----:|:--------:|:---------:|
|  data  | Object| Body  |必填|显示为：null|


## 手动执行用户场景带返回值

>手动执行用户场景，返回sn，执行请求唯一标识。


 1、接口定义

?> **接入地 址：**  `/iftttscene/scene/v2/triggerUserScene `  
 **HTTP Method：** POST

**输入参数**  

| 参数名  | 类型    | 最大长度  |位置  | 必填|说明|
| ------- |:------:|:-----:|:----:|:----:|:----:|         
| familyId| String |32| Body| 必填|&emsp; | 
| sceneId| String |32| Body| 必填|&emsp; | 

     

**输出参数**  

|   名称      |     类型      | 位置  |必填 |说明|
| ------------- |:----------:|:-----:|:--------:|:---------:|
|  data  | Object| Body  |必填|返回场景执行唯一标识sn|

