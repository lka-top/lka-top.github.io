+++
title = "代码高亮与样式测试"
description = "测试一下 Stack 主题在处理各种 Markdown 语法和代码块时的表现。"
date = "2026-07-03"
categories = ["技术分享"]
tags = ["代码", "Markdown", "测试"]
+++

## 代码高亮测试

Stack 主题对代码高亮的支持非常好。下面是一段 Python 代码的演示：

```python
def fibonacci(n):
    """生成斐波那契数列"""
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    
    sequence = [0, 1]
    while len(sequence) < n:
        sequence.append(sequence[-1] + sequence[-2])
    return sequence

print(fibonacci(10))
```

## 引用与提示框

平时写技术文章经常会用到引用和提示框功能。

> 这是一段普通的引用文字。很多时候用来引用别人的名人名言或者官方文档的解释。

Stack 主题其实还支持很多高级排版，后续再慢慢探索。
