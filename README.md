# tp5-lotusadmin
最初始后台搭建



> 到网址下载：https://gitee.com/wenhainan/LotusAdmin

设置域名要到public目录：LotusAdmin/public

改后台 config.php
```php
// 默认模块名
'default_module'         => 'admin',
// 禁止访问模块
'deny_module_list'       => ['common'],
// 默认控制器名
'default_controller'     => 'Index',
```


改数据库 database.php
```php
'hostname'        => 'localhost',
// 数据库名
'database'        => 'nongken',
// 用户名
'username'        => 'root',
// 密码
'password'        => 'root',
// 端口
'hostport'        => '3306',
```

伪静态 .htaccess文件
