# TDD 井字游戏 -Java练习
## 需求：
"井字游戏"是两个人使用纸和铅笔玩的一种游戏，双方轮流在一个3 * 3的网格中画X和O，最先在水平、垂直或对角线上将自己的3个标记连起来的玩家获胜。

￼![](./img/game_steps.png)

有关这款游戏的更详细信息，请参与维基百科：http://en.wikipedia.org/wiki/Tic-tac-toe


1. 不要求实现游戏的UI,只用实现游戏的运行逻辑。
2. 所有实现的游戏逻辑都需要有单元测试覆盖。

## 挑战:

1. 使用TDD来完成这个游戏的核心逻辑实现。
2. 利用Tasking,分解出无强耦合的任务列表。
3. 利用实例化需求，为每个测试用例设计合理测试数据。
4. 为单元测试方法取有意义的名字。
5. 实例化单元测试结构。
6. 初步应用理解 Java 8 Stream API。
7. 小步重构，随时保证代码整洁，模块职责单一。
8. 确保测试能够覆盖必要的异常情况验证。

## 要求:

1. 利用Tasking分解，小步实现。
2. 在写代码前，先设计和编写测试用例与测试。
3. 使用Junit进行测试实现，配合assertj断言。
4. 为单位测试和方法命名有意义的名称。
5. 单元测试应涵盖所有业务逻辑。
6. 代码通过小步骤提交并附上意义的评论。
7. 通过IDE快捷键编码。

## 交付物:
请将你的代码提交到教练指定的仓库，其中需要包含：

a)	核心业务模块的单元测试
b)	单元测试用例
c)  使测试通过的实现代码

## 环境

Java 8

## 开始：

get the practice repository:
```
 git clone https://github.com/ThoughtWorks-School-Showcase/unit-test-java
```

Stack Initial and build:

```
Mac/Linux: ./gradlew idea   
Whindows:  gradlew.bat idea  
```
```
Mac/Linux: ./gradlew clean build   
Whindows:  gradlew.bat clean build 
```

Test:
```
Mac/Linux: ./gradlew clean test 
Whindows:  gradlew.bat clean test.
```

## 学习资源:

1. [任务分解](https://www.zybuluo.com/jtong/note/504192)
2. [Gradle基础教程](http://tutorials.jenkov.com/gradle/gradle-tutorial.html)
3. [Java 基础](http://www.runoob.com/java/java-tutorial.html)
4. [Git 参考手册](http://gitref.org/zh/index.html)
5. [Junit](http://junit.org/junit5/docs/current/user-guide/#writing-tests-assertions)
6. [Mockito](http://site.mockito.org/)