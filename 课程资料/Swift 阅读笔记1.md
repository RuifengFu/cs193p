# Swift 阅读笔记1

要阅读NOTE

## The Basics

swift和包含了c语言的基本类型。

但是swift的常值类型更安全，引入了optional types。

swift是类型安全的。

### Constants and Variables

``` swift
let maximumNumberOfLoginAttempts = 10 //Constant can't be changed once it's set.
var currentLoginAttempts = 0 // variable
// NOTE: 只有当一个数可能被修改的时候再用变量
var s:  String // Type Annotations 类型注释
var red, green, blue: Double
// NOTE：如果包含了初始化值，Swift可以推断出值的类型
let π = 3.14159 // MARK: 可以使用Unicode字符
let 你好 = "你好世界"
let 🐶🐮 = "dogcow"//有些太阴间的命名不行，变量名一经分配不得修改类型
// NOTE： 如果将一个关键字用作变量名请在它前面加上`
print("The current value of friendlyWelcome is \(friendlyWelcome)")
```

### Comments

与c类似，多行注释可以嵌套。

### Semicolons （分号）

用于同一行的多个语句的分割

### Integers

和c类似

### Floating-Point Numbers

首选Double（15位），Float（6位）





