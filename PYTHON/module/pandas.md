数据类型有:Serise,DataFrame

**文件读取:**

pd.read_csv(df,encoding='utf-8',dtype={'name',type},sep=',')

pd.read_table()

pd.read_excel(df,encoding='utf-8',sheet_name='')

pd.read_sql(df,conn=command)



有关pandas显示的问题:

.set_option('display.max_rows',10)

.set_option('display.max_columns',20)

:sunny:

<font color=red>数据分组.groupby([],axis=0): </font>

并不会立即分组, 返回一个分组对象

**分组-运算-合并:**

len() :可以直接获得分组数

.size() :统计个数

.agg(), .transform(), .filter(), .apply()等方法实现分组运算

.agg() :含义指的是当多个数据转换为单个数据的方法.如求和,平均,最大值

