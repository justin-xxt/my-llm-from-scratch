## 字符串相关
### 隐式字符串拼接
`隐式字符串拼接`（implicit string concatenation），在括号中多行写字符串常量时，Python 会自动将它们拼接为一个字符串。

只要多个字符串`字面量`（即直接写出来的字符串）在括号内、方括号内或花括号内，就会自动拼接，不需要`+` 或换行符`\`，这是Python的语法糖。

#### 常见应用场景
```python
query = (
    "SELECT * FROM users "
    "WHERE age > 18 "
    "ORDER BY created_at DESC"
)

```
这样写比`+` 拼接更简洁且性能更好。
