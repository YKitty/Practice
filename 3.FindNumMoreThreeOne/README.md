题目：从一个数组中找出超过1/3的数字    
思路：对于一个数组中，超过1/3的数字，最多有两个，所以我们直接就从从找出两个数字   
对于如何来查找数字，采用抵消法    
抵消法：对于每一次查找一个数字，有三种可能    
第一种：当是第一个数字或者第一个数字的计数器为0    
第二种：当是第二个数字或者第二个数字的计数器为0    
第三种：不是前面的两种情况，将两个数字的计数器都进行减1    

