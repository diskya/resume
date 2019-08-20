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
