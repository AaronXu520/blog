# js

## string
- 字符串长度太大，可以在每行的末尾使用反斜杠（\）表示字符串将在下一行继续
- trim（），删除字符串开头或结尾的尾随空格
- startWith（），检查字符串是否以指定的字符串开头，返回布尔值
- endsWith（），检查字符串是否以指定的子字符串结尾。返回布尔值
- search（），以子字符串作为参数，返回第一个匹配项的索引。搜索值可以是字符串或者正则表达式
- match，将子字符串或正则表达式作为参数，如果匹配则返回一个数组，否则返回null
- repeat(): 它接收一个数字作为参数，并返回字符串的重复版本

## 强制转换
### 字符串数字转数字
- parseInt（）
- Number（）
- `+` 运算符，如果操作数不是number，会试图将其转换为number

### 字符串浮点数转数字
- parseFloat（）
- Number（）
- `+` 运算符

### 浮点数转整数
- parseInt