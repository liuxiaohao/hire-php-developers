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

指出下面这段代码存在的问题，并重构它：

```php
$arr = array('P.R. China', 'United States', 'Taiwan');
$i = 0;
while($i < count($arr)) {
    echo $arr[$i];
    $i++;
}
```
