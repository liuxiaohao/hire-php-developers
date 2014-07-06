# 后端招聘题目

## Part I

用简洁准确的语言回答以下问题。

- OAuth 协议是如何保证安全的？
- 使用 MVC 和 ORM 有哪些优点和缺点?

可选题目：

- Yii Framework 使用 Components 模式有哪些优点和缺点？
- Laravel 使用 Facade 模式有哪些优点和缺点？

## Part II

使用 PHP + MySQL 编写一个软件，实现以下目标：

- 从 Yahoo Finance 抓取 Apple Inc. 指定日期范围内的每日收盘价。
- 将数据存储存储到 MySQL。

可选题目：

- 使用 HighCharts 显示股价走势图。
- 求出平均股价。

## Part III

有一天，你收到且只收到这么一段代码：

```php
function filter($arr, $check, $check2 = null)
{
    $new_arr = [];
    while ($i < count($arr)) {
        if (strpos($arr[$i], $check) || strpos($arr[$i], $check2))
          $new_arr[] = $arr[$i];
        $i++;
    }
    return $new_arr;
}
```

原来的编写者试图将出现过两种特定字符串的元素挑出来，而我们认为这个方法很糟糕。
于是，你接到了任务：找出这段代码所存在的问题，并且重构这个方法。
