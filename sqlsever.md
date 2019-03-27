［ＴＯＣ］
＃1.查询表是否包含重复段

例如数据库中有两个字段A，B，则用下面的语句查出是否有重复数据
select A,B from table1 group by A,B having count(*) > 1;
