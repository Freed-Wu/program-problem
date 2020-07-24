# 编程测试题

## 游戏入口逻辑

*tetris_game.py:15-156* 初始化相关参数（分数等），初始化 UI。
*tetris_game.py:160-178* 初始化侧边栏。包括暂停等行为。
*tetris_game.py:184-224* 初始化主要面板。包括暂停等行为。

## 游戏执行逻辑

*tetris_ai.py:12-143* 计时计分计算下落点。

## 生成新方块的逻辑

*tetris_model.py:6-18* 定义 I, L, J, T, O, S, Z 形方块。
*tetris_model.py:92-109* 随机生成新方块。

## 消除整行方块的逻辑

*tetris_model.py:158-172* 消除整行方块。

## pyqtSignal

```{.py}
PyQt5.QtCore.pyqtSignal(types[, name[, revision=0[, arguments=[]]]])
```

创建一个或多个重载的未绑定信号作为类属性。

### 参数

*类型* 定义信号的C++签名的类型。每种类型都可以是Python类型对象，或者是C++类型的字符串。或者，每个类型都可以是一系列类型参数。在这种情况下，每个序列定义了不同信号过载的特征。第一个重载将是默认值。

*名称* 信号的名称。如果省略，则使用class属性的名称。这只能作为关键字参数给出。

*版本* 输出到QML的信号版本。这只能作为关键字参数给出。
arguments–导出到QML的信号参数的名称序列。这只能作为关键字参数给出。

### 返回类型

未绑定信号

<https://www.riverbankcomputing.com/static/Docs/PyQt5/signals_slots.html>

# 思维测试题

1. E
2. C
3. E
4. D
5. D
6. B
7. D
8. B
9. D
10. D
11. 6
12. 4
13. 59
14. C
15. B
