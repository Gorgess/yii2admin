# yii2admin

1、下载源文件或git clone https://github.com/Gorgess/yii2admin.git  
2、composer install     
3、common/config/main.php #配置数据库      
4、Nginx和Apache配置，并设置hosts文件     
5  PHP版本<=7
数据库文件：yii2-admin.sql     
管理员账号：admin     
管理员密码：123456     



错误处理
报错 : Script php init --env=Development --overwrite=n handling the post-install-cmd event returned with error code 255

composer.lock
init
init.bat
requirements.php

把上面的几个文件删除，然后再执行 composer install试试

报错:The file or directory to be published does not exist: E:\www\yii2admin/vendor\bower/bootstrap/dist

将vendor下bower-asset重命名为bower