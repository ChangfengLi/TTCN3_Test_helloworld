# TTCN3_Test_helloworld
包含有两个hello_world示例程序。
# 编译：
```
ttcn3_makefilegen hello_world.ttcn MyExample.ttcn MyExample.cfg MyExample2.cfg PCOType.cc PCOType.hh -f
make
```
# 仅运行示例1
```
ttcn3_start hello_world MyExample.cfg
```
# 运行两个示例
```
ttcn3_start hello_world MyExample2.cfg
```
