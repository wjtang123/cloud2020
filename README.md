# cloud2020
尚硅谷SpringCloud代码
[配合b站教程进行学习](https://www.bilibili.com/video/BV18E411x7eT?p=17&spm_id_from=pageDriver&vd_source=4b186c40bbc46d6c69bfdcb7f65b0b36)

## 数据库操作
- 安装好mysql，账户名/密码： root/123456
```sql
create databases db2019;
use db2019;
create table if not exists Payment(id BIGINT, serial VARCHAR(100));
```