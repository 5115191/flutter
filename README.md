# flutter
flutter学习记录

#### 类型为数字(int/double)的变量如果没有初始化其值也是 null
#### assert：断言
assert(text != null);
assert 判断的条件可以是任何可以转化为 boolean 类型的对象，即使是函数也可以(此时判断的是函数返回值)。
如果assert 的判断为true, 则继续执行下面的语句。反之则会丢出一个异 AssertionError 。
