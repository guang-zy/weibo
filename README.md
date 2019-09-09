## http服务器 自制类Flask MVC+Web框架 类微博项目
 
 ### 技术栈        
 Python + HTTP + Socket + MySQL + jinjia2  
  
### HTTP 服务器 
- 利用 Socket 实现了简单的 HTTP 服务器 
- 服务器能对响应进行接收、解析、返回  
- 使用 Python 多线程实现服务的并发 
### MVC  Web 框架  
- View 视图层使用 Jinja2 模板实现页面的渲染 
- Controller 层使用高阶函数对用户权限验证字典实现路由的分发 
- Model 层使用 MySQL 作为数据库，并自制对象关系映射对增删查改的 SQL 语句进行封装 

#演示
### 登录解析

 ![图片](/demo_app/static/登录解析.gif)
 
### 微博修改和删除评论
 
 ![图片](/demo_app/static/微博修改和删除评论.gif)