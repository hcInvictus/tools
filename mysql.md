1 mysql命令行导出查询数据
// 查询命令需要用单引号括起来，里边的where字段如果有字符串需要用双引号括起来
mysql -uroot -h127.0.0.1  -p"123456" -P3306 -e 'select uid from db.table where a= "test"' > a.txt
