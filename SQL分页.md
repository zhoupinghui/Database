# SQL Server 2012使用Offset/Fetch Next实现分页
## 在Sql Server 2012之前，实现分页主要是使用ROW_NUMBER()，在SQL Server2012，可以使用Offset ...Rows  Fetch Next ... Rows only的方式去实现分页数据查询。
### 注意：使用Offset /Fetch Next需要指定排序，即必须有order by column
