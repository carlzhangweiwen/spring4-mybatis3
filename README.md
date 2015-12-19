# spring4-mybatis3
spring4-mybatis3

mysql数据库 root登陆 1.创建用户 create USER 'xymz'@'%' identified by '123456';

2.创建数据库 create database xymz;

3.赋权 grant all privileges on xymz.* to 'xymz'@'%' with grant option;

xymz登陆 1.建立测试表 Create DATABASE spring4_mybatis3; USE spring4_mybatis3;

DROP TABLE IF EXISTS t_user; CREATE TABLE t_user ( user_id char(32) NOT NULL, user_name varchar(30) DEFAULT NULL, user_birthday date DEFAULT NULL, user_salary double DEFAULT NULL, PRIMARY KEY (user_id) ) ENGINE=InnoDB DEFAULT CHARSET=utf8;
