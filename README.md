# Lancer
同步两个DB之间的schema,配置如下:
sourceHost=127.0.0.1:3306
sourceUser=root
sourcePass=123123123
sourceSchema=mystique_db
sourceCharset=utf8

targetHost=127.0.0.1:3306
targetUser=root
targetPass=123123123
targetSchema=mystique_test
targetCharset=utf8

autoExecute=YES //此处表明自动同步
