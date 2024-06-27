项目来自于黑马程序员redis课程中项目
视频地址：https://www.bilibili.com/video/BV1cr4y1671t?p=24&vd_source=bef1f44c0725fd1ce28e09b6d45e8635
## 实战篇项目导入

### 1、启动后端项目

后端项目导入后，如果想最快的方式启动项目，需要修改以下文件

![image](https://github.com/wind-woo/heima-redis/assets/171944271/0a458baf-077e-4f2c-9be6-2e1c48b49efa)

执行sql文件建表

后端项目就能正常运行了

访问http://localhost:8081/shop-type/list

![image-20240627225153699](https://github.com/wind-woo/heima-redis/assets/171944271/a85ec6f7-0608-4ec8-8483-e1dc5f5e06b9)

### 2、启动前端项目

使用nginx启动  `start nginx.exe`

![image-20240627231157024](https://github.com/wind-woo/heima-redis/assets/171944271/069a1b71-6209-46e1-bb25-278872e27190)（启动和关闭命令）

注意：nginx的存放位置不要有中文，不然nginx将无法正常启动

启动后，黑窗口不能关闭，打开浏览器访问：http://localhost:8080/

![image-20240627231423865](https://github.com/wind-woo/heima-redis/assets/171944271/67244e62-e59e-47ac-8e21-e302f1d89065)

页面启动成功，至此，前后端项目启动完成！


