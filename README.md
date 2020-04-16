# smalltips
some small gists during the leetcode~
python 字典：
    1.每个键值对用‘：’分割，每个对之间用‘，’分割，整个字典包括在‘{}’中
    2.键必须是唯一的，而值却不用
    3.dict[key] = value
    4.常用方法：添加信息-直接添加
              删除信息- del dict['Key'] #删除键Key
                      del clear() #清空字典
                      del dict #删除字典
    5.字典不允许同一个键出现两次，创建时如果同一个键被赋值两次，后一个值会被记住
    （存疑）6.键必须不可变，所以可以用数字，字符串或者元祖充当，而用列表就不行。
