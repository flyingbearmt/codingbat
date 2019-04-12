##数据库：
1. 事务的四个特性：acid, 原子性（atomic),一致性（consistancy), 独立性（isolation）持久性（duarable）
2. 数据库的基本操作
	- 选择
	- 投影： 会把重复的行删除
	- 并： 重复的还是会删除，（U）要等目，同源（类型相同）
	- 集差： r－s
	- 笛卡尔积： （矩阵相乘），如果在两个关系中有同名的属性，我们还是把它们看作是不同的属性。（r中有B, s中有B，结果是r.B,s.B）
	- 复合运算（可以使用多种）
	- 更名运算 
	
3. 附加操作
	- 集合交
	- 自然连接
	- 除：r／是（包含所有s的r集合
	- 赋值
	
4. super-key －》
	candidate-key －》
	primary-key
	层层深入
	
5. 基本数据类型 
	- char：（n）固定长度
	- varchar（n）：可变长，最大为n
	- int
	- smallint
	- numeric(p,d): 定点数，p位数字，小数点后d位
	- real,double precision
	- float（n）：精度至少为n
	- null
