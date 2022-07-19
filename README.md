# Mr.-Wang-project
It's part of the project "CloudIQC".   
The format of measurement reading from TESA is like "00.00;2022/2/16;下午 10:52:00" separated by semicolon ; ( a csv file saved in folder Mr.-Wang-project/原始測試資料)   
There are two measurement set:   
__a is 10.99+/-0.01mm__   
__b is 7.55+/-0.01mm__   
In pre-processing, use pandas to read csv as dataframe named "data"+"n".   
Create a class "project_class" with 3 methods,   
1. data_clear() to append each "data"+"n" in a a dataframe form with column ["value","data","time"],   
2. time_diff_a() to count time difference of dimension a (00.00),   
3. time_diff_b() to count time difference of dimension b (0.00),   

And save as csv again individually (and now in 2 different folders).
      
   

