# hello-world
My first git repository in my life
#关于列表的练习文件
ten_things = "Apples Oranges Crows Telephone Light Sugar" # 里面有六个东西

print("Wait there are not 10 things in that list. Let's fix that.") # 等等里面只有六个 让我们修复它

stuff = ten_things.split(' ') # 分割
more_stuff = ["Day", "Night", "Song", "Frisbee", "Corn", "Banana", "Girl", "Boy"] # 8个内容的列表

while len(stuff) != 10: # 当stuff的内容数不是10时
    next_one = more_stuff.pop() # next_one是8内容中弹出最后一个 加进去 pop(more_stuff)
    print("Adding: ", next_one) # 加入弹出的这个
    stuff.append(next_one) # stuff append这个 append(stuff, next_one)
    print(f"There are {len(stuff)} items now.")

print("There we go: ", stuff)

print("Let's do some  things with stuff.") # 现在stuff是10内容了

print(stuff[1])
print(stuff[-1]) # whoa! fancy
print(stuff.pop())
print('-'.join(stuff)) # what? cool! 用-链接列表成为字符串
print('#'.join(stuff[3:5])) # super stellar! 第4个和第5个 左闭右开 从0开始
