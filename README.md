# LuanNiao Core
We create this project case we need some base operation in the project(This list will be update as we realization new feature).
<br/>
Like this:
1. Union Type: inspiration by [Stack over flow](https://stackoverflow.com/questions/3151702/discriminated-union-in-c-sharp "Stack Overflow")





# How to Use it?

#### UnionType
```C#
  UnionType<int, string, TestClass> _testInstance = 1;
  _testInstance = "";
  _testInstance = new TestClass();
```
Detail demo you can find out in my Unit test project.[UTest](https://github.com/luanniao/Core/tree/master/src/Z.LuanNiao.Core.Test)
