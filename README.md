# exp
表达式引擎, 用于自动化测试断言

``` python
env = {'a': {'b': [{'c': '2'}]}}
print(run('a.b.0.c == (1+(2*(4/4))-1) & (!(1>2))', env))
```
