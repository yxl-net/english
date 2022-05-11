# 编程语言中的单词
+ [目录](README.md)
## as
+ 音标
    + 英 \[æz,əz]
    + 美 \[æz,əz]
+ 解释
    + 
        + 像
        + 如同
        + 作为
        + 当作
    + 
        + (比较时用)像…一样，如同
        + (指事情以同样的方式发生)和…一样;
    + 
        + 当…时
        + 随着
        + 照…方式
        + 因为
        + 由于
+ SQL Server
    + 查询项的别名
        + select 表达式 as 别名
    + 函数参数的别名
        + create function 函数名(@参数名 as 类型) returns 类型 begin return 值 end
    + 变量的类型
        + declare @变量名 as 类型
    + 表类型定义
        + create type 表类型 as table (表定义) 
    + 存储过程的过程体或程序集方法
        + create proc 过程名 as 过程体
        + create proc 过程名 as external name 程序集方法
    + 函数的函数体或程序集方法
        + create function 方法名 returns 类型 as begin return 值 end
        + create function 方法名 returns 类型 as external name 程序集方法
    + 触发器的执行句柄或程序集方法    
    + 合并语句的目标表别名和源表别名
## from
+ [目录](README.md)
+ 音标
    + 英 [frəm]
    + 美 [frəm]
+ 解释 
    + (表示起始点)从…起，始于
    + (表示开始的时间)从…开始
    + (表示由某人发出或给出)寄自，得自;
+ SQL Server
    + 查询的表
        + SELECT * **FROM** 表名
    + 删除的表
        + DELETE **FROM** 表名
    + 批量文本导入
        + BULK INSERT 表名 **FROM** '文件路径'
    + 别名类型
        + CREATE TYPE 别名 **FROM** 类型
## OVERRIDE
+ [目录](README.md)
+ 音标
    + 英 [ˌəʊvəˈraɪd]
    + 美 [ˌoʊvərˈraɪd]
+ 解释
    + 推翻
    + 凌驾
    + (以权力)否决
    + 不理会
    + 比…更重要
    + 超控(使自动控制暂时失效，改用手工控制);
+ SQL Server
    + 应用服务器配置不检查
        + RECONFIGURE WITH OVERRIDE
+ C#
    + 函数重载符
        + protected override 方法名(){方法体}
