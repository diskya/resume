例1：从键盘输入一个英文句子，除单词和空格外句子中只包含“,”、“.”、“'”、“"”和“!”这几个标点符号，统计句子中包括的每个单词
（将句中大写全部转换成小写）的词频并将结果存入字典中并输出。

````Python
s = input("enter an English sentence: ")
s = s.lower()
sList = s.split()
sDict = {}
for item in sList:    
    if item[-1] in ',.\'"!':
        item = item[:-1]
    if item not in sDict:
        sDict[item] = 1  # 每一个第一次出现的单词计词频为1
    else:
        sDict[item] += 1  # 第二次或之后遇到的单词在原词频上累加1
print(sDict)
# if-else部分为经典的从数据中创建字典的方式，该语句块也常用如下代码替代：
# sDict[item] = sDict.get(item, 0) + 1
````

例2：自定义函数twonums_sum(n, lst)，在列表lst中查找是否有两数之和等于n，若有则返回两数的下标，否则返回-1。对于一个不包含重复数字的有序列表
[1, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 15, 18, 19, 20, 21, 29, 34, 54, 65]，从键盘输入n，调用函数twonums_sum()输出满足条件的两个数的下标
（找到一组即可且要求其中的一个数尽量小），若所有数均不满足条件则输出“not found”。

````Python
def twonums_sum(n, lst):
     d = {}
     for i in range(len(lst)):
          d[lst[i]] = i    # 创建数值-下标对
     for i in range(len(lst)):
          if n - lst[i] in d:
               return i, d[n-lst[i]]             
     return -1


lst = [1, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 15, 18, 19, 20, 21, 29, 34, 54, 65]
n = int(input())
result = twonums_sum(n, lst)
if result == -1:
    print("not found")
else:
    print(result)
````
