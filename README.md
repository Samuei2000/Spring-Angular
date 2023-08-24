# 如何准备数据库

在Mysql数据库内，运行脚本`refresh-database-with-100-products.sql`

# 如何准备后端/Spring

 1. 运行`./mvnw clean install`
 2. 运行`./mvnw spring-boot:run`，这会启动后端。应用程序启动后，在浏览器上点击 http://localhost:8080/api/   就可以看到所有api

# 如何准备前端

需要安装的东西：
-   nvm [Node Version Manager](https://github.com/nvm-sh/nvm).


检查nvm版本：`nvm --version`
-   npm和node :安装好nvm后，运行`nvm install node`

检查npm和node版本：`node --version`和`npm --version`
-   tsc:运行`npm install -D typescript`
检查tsc版本：`tsc --version`
- Angular：运行`npm install -g @angular/cli`
检查Angular CLI 版本： `ng version`

## 安装注意

 1. 运行`source ~/.bashrc`以把nvm添加到系统路径
 2. 若显示

> The current version of Node (20.4.0) is not supported by Angular.

则运行`nvm list`检查当前使用的nvm版本，运行``nvm use 16.16.0``选择nvm版本，运行`nvm install v16.10.0`安装nvm版本，运行`npm uninstall -g @angular/cli`卸载Angular
## 运行前端
运行`node -v`，`npm -v`，`npm install -g @angular/cli`没有问题后，在前端目录内，运行`npm install`、`ng build`与`ng serve`

