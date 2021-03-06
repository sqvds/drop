# MongoDB安全问题

## 什么是MongoDB
MongoDB是基于分布式文件存储的数据库，也就是我们常说的NoSql，与传统关系型数据库不同的是，其数据是非结构化的，
并且查询速度极快，可达到10亿/秒

## 特点
1. 文件存储格式BSON(一种json的扩展)
2. 模式自由：数据格式不受限于表的结构
3. 支持动态查询
4. 支持完全索引
5. 使用高效的二进制数据存储
6. 支持各类语言
7. 查询速度快，搞并发，高容量

## MongoDB与关系型数据库对比
| 对比项        | MongoDB           | 关系型数据库  |
| ------------- |:-------------:| -----:|
| 数据库      | 数据库 | 数据库 |
| 表      | 数据集      |   二维表 |
| 表中的一行数据 | 文档      |    一条记录 |
| 表字段   | 键 | 列 |
| 主外键 | 无 |   PK、FK |
| 扩展性 | 极高 | 无 |

## 使用Docker部署php/nginx/mongodb/mysql环境
