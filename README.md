# clean-code

[tortoisegit](https://tortoisegit.org/)

代码整洁准则:

- [ ] 使用见名知意、完整的单词作为变量名，少用拼音和缩略语
- [ ] 同一项目中表示同一个东西的时候使用相同的变量名
- [ ] 使用便于搜索的命名方式
- [ ] 不要在变量名中加一些不必要冗余的东西
- [ ] 必要的话给函数参数赋默认值，同时显式说明参数的类型
- [ ] 函数参数个数尽量不要超过三个
- [ ] 一个函数只需要负责一件事情
- [ ] 函数名称需要表达它的功能
- [ ] 函数应该只有一层抽象
- [ ] 函数要避免副作用(side effect)，避免引用外层变量、更改引用型参数
- [ ] 设计类时应遵循`SOLID`五大原则，即单一职责原则、开闭原则、里式替换原则、接口隔离原则和依赖倒置原则
- [ ] 项目里不要重复代码（DRY）
- [ ] 善用jsdoc注释

重构


```py
from typing import Union, Dict, NamedTuple, TypedDict, List, Generator, Iterator, Tuple, AnyStr
from dataclasses import astuple, dataclass
from importlib import metadata


```

> 正则命名分组和纯函数

<https://immutable-js.com/>
