# 简介
通过统计学生的成绩，找到排名前列但是有偏科的学生。



# 输入

1.输入文件（自己随机生成）：一张100*100的成绩单，即100个学生的100门课的成绩，课程成绩：最低分0分，最高分100。

2.输入两个值：即X（排名前X名的学生）和Y（偏科的定义：低于课程平均成绩Y%的）

# 输出

1.找到我们定义的偏科学生，并输出相关信息（总成绩排名是多少？哪门偏科，比平均值低多少分？等）

# 函数功能
  
  function_1.读取数据，并显示数据的基本信息，课程的平均分和学生的总成绩与平均分。
  
  
  function_2.根据总成绩排序，并根据提前输入的X，显示总成绩前X名学生的信息，包括姓名、各科成绩、总成绩和平均分。
  
  
  function_3.找到偏科的学生。偏科的定义是，其中一门成绩低于班级平均值Y%的（y是提前输入的）。找到偏科的学生和相关科目，并显示哪门偏科，比平均值低多少分？
  
# 所需的库：
  
  xlrd xlwt xlutils pandas
