# ~~咱也不知道，咱也不敢问~~

### 幻化成希望——Amagi_Yukisaki(项目组RBQ)

### 所有成员请及时同步master分支

### ~~现在是组长单打独斗时间~~

## Master Changelog From 2020.06.11(众所周知这是个栈)

### 2020.06.23

完善文档 & 修改前端

~~用户文档怎么写啊啊啊啊啊啊啊啊啊啊啊啊啊啊啊~~

~~我裂开惹！~~

### 2020.06.22

全员复习数分，摸了～

### 2020.06.21

优化`B+`树操作合法性检查。

调整缓存大小。

当前性能：`Basic 238503ms 7188KB`, `Pressure 665076ms 7680KB`

当前成绩：分数`(42+8.5)/(42+40)`

最后一天卡常疯狂交`Pressure`似乎有点不道德，尤其是有些组仍在调试`Basic`的情况。

~~不卡了，躺平被日~~

公开此`Repo`

### 2020.06.20

重构并修正`Query_Transfer`

通过`Pressure`，当前分数`(42+8.5)/(42+40)`

更新文档。

细节调优中。

### 2020.06.19

修正初始化问题。

重构`Query_Ticket`

通过`Basic`，当前分数`(42+0)/(42+40)`

### 2020.06.18

~~修正数组大小~~

当前分数`(36+0)/(42+40)`

### 2020.06.17

完成缓存，当前分数`(29+0)/(42+40)`

### 2020.06.16

完成`B+`树。

### 2020.06.15

前端增加初始化系统。

### 2020.06.14

修改`B+`树的`modify`函数接口。

前端基本完成。

### 2020.06.13

后端`Ctrl+C`不再导致数据损毁。

修改了`.gitignore`以忽略编译生成文件。

前后端结合代码`Debug`

### 2020.06.12

前后端结合代码。

### 2020.06.11

修改了`.gitignore`

删除了测试数据(导致评测超时)和根目录中的`main.cpp`

## Todo

- [x] 完善文档

- [x] 性能优化

- [x] 完善开发文档

- [ ] 制作用户文档

#### Backend

- [x] B+树

- [x] B+树缓存(基于`map`实现`LRU`算法，读写同池，懒惰写入(被换出或程序结束时进行写入)) -> 队长负责？

- [x] Query Ticket 优化

- [ ] ~~日志式操作？~~

#### Frontend

- [x] `modify_profile`不可用

- [x] 所有需要多行输出的操作`(query_train, query_order, query_transfer, query_ticket)`

- [x] 初始化系统

- [ ] 输入合法性检查

- [ ] 美化(添加图片等)

- [x] 细节调整：显示用户`name`而不是`username`

- [x] 易用性优化

- [ ] 权限系统