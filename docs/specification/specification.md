# 规范

本网站是基于 md 进行编辑的，为了方便读者阅读以及内容的规范，你应该遵循以下规范。

## 🙂 链接

你应该避免直接内嵌 HTML 代码

_Good 👍🏻_

```java
[link name](link url) 或者 <link url>
```

_Bad 👎🏻_

```html
<a href="url">链接文本</a>
```

## 🙂 代码

使用单引号 `code` 来表示行内代码，使用三引号来表示代码块

```java
code
```

并且对于代码块，你应该写上对应的语言

_Good 👍🏻_

```java
    ```java
        System.out.println("HelloWorld");
    ```
```

_Bad 👎🏻_

```html
    ```
        System.out.println("HelloWorld");
    ```
```

## 🙂 图片

你应该避免内嵌 HTML 来插入图片

_Good 👍🏻_

```java
![link name](picture url)
```

_Bad 👎🏻_

```html
<img src="url" alt="some_text">
```
