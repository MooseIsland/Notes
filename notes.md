Python 3.6以后，格式化字符串还有更为简洁的书写方式，就是在字符串前加上字母f，我们可以使用下面的语法糖来简化上面的代码。
  a, b = 5, 10
  print(f'{a} * {b} = {a * b}')
# 通过enumerate函数处理列表之后再遍历可以同时获得元素索引和值
  for index, elem in enumerate(list1):
      print(index, elem)
