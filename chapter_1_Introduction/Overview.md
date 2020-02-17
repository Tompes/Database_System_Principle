# OverView 绪论
### 1. DataBase 数据库（DB）：
数据库是指``长期存储``在计算机内 ， 有组织 、可共享的数据集合。

---
### 2. DataBase Management Sys 数据库管理系统（DBMS）：
DBMS是由 <u>数据库</u> <large>+</large> <u>一组用于``访问``、``管理``、``更新``这些数据的程序</u> 构成的。
    
#### Advantages of DBMS （特性）：
1. 数据访问的``高效率``和``可扩展``性
    > 有特定的机制用于提高数据操作的效率，易于扩展规模且不会影响现有数据。
2. 集成常用操作，缩短应用开发时间
3. ``数据独立性`` （物理独立性/逻辑独立性）
    > 数据独立于物理设备和特定的操作系统，降低了迁移与适配的工作量与成本。
4. 数据的``完整性``和``安全性``
    > DBMS 会依据用户设定来保证数据的完整性，同时有一套完备的机制用于保证数据安全。
5. ``并发``访问和``鲁棒性``（恢复）
    > DBMS 支持数据的并发访问及操作 ， 而且有应对宕机、磁盘故障等情景的机制，具有很强的鲁棒性。
#### History of DBMS (发展历程)：
1. ``文件处理系统``（File Processing System） | 1950s~1960s
    > 文件处理系统是最原始的计算机数据管理系统
2. ``网状和层次型DBMS`` (Network and hierarchical DBMS) | 1960s~1970s
    > * 网状数据模型 Network Data Model --> 网状数据库 Network Database 
    > * 层次数据模型 Hierarchical Data Model --> 层次数据库 Hierarchial Database
    >  
    >   其结构复杂，且当时硬件性能弱，使用很困难 <br>
    It was not efficient at  60 70s,due to several reasons which like hardware performance. 
3. ``关系型DBMS`` (Relational DBMS or RDBMS)
    > * 关系模型 Relational Model（1970，E.F. Codd）
    > * 1970s, RDBMS开始发展 ``Developing``
    > * 1980s, RDBMS走向市场 ``Commercialize``
    > * 1990s, RDBMS技术成熟 ``Mature``
