# 关于Markdown
## Markdown基础语法
### Markdown 标题语法
- `#`+一个`sapce` 一级标题
- `##`+一个`space` 二级标题
- `###`+一个`space` 三级标题
- 以此类推……
### Markdown 段落语法
- 中间空一行，示例如下：  

  你好
   
  你也好
### Markdown 换行语法
- 俩`space`+`enter`键换行
### Markdown 强调语法
- **粗体**  
  
  >左右各两个`*`号
- *斜体*
  >左右各一个`*`号
- ***斜体加粗***
  >左右各三个`*`号
### Markdown 引用语法
- 关键字 `>`
- 多个段落的块引用  
  
  > 为段落之间的空白行添加一个符号`>`。
- 嵌套块引用  
  
  > 在要嵌套的段落前添加一个`>>` 
- 带有其它元素的块引用  
  
  > 可以但也不是所有都可以
### Markdown 列表语法
- 有序列表  
  
  > 一个数字(任意数字，只是第一个必须是1)+`.`
- 无序列表  
  
  > `-`+一`space`
- 在列表中嵌套其他元素
  
  >如果不想破坏列表，那么在该元素前缩进四个空格（或一个`Tab`键）
### Markdown 代码语法
- 关键字 `` ` ``
- 转义反引号 ``` `` `` ```
- 代码块
  > 请将代码块的每一行缩进四个`space`或一个`Tab`键

        <html>
            <head>
            </head>
        <html>
### Markdown 分隔线语法
- ``---``  
- ``___``  
- ``***``
> 必须在单独一行，且前后各空一行
### Markdown 链接语法
这是一个超链接[Markdown语法](http://markdown.com.cn "从菜鸟到大佬一站式学习")  

- 标签：``[超链接名](超链接地址 "鼠标移到超链接上时会出现的提示")``
- 网址和Email地址  
  
  >使用`<>`可以很方便地把URL或者Email地址变为可点击的链接
- 带格式化的链接
  - **强调**在链接语法前后添加`**`
  - 将链接表示为代码则在方括号中添加``` `` ```
- 引用类型链接分两种  
   1. `` [链接名称][Label（可以是字母、数字、space或标点）]``
   2. `` [Label]: (<)超链接地址(>) (")链接的标题(")``
   >()表示可加可不加
>有一点要**特别注意**，就是若地址中出现空格不被允许的话，请使用``20%``代替空格
### Markdown 图片语法
- 普通图片
  >\!\[替代文本\](存放照片的目录 "图片的title")  
  
    ![参考书目](物联网导论参考书目.jpg "参考书目")
- 链接图片
  > \[\!\[替代文本\](存放照片的目录 "图片的title")](链接地址)

  [![外网访问](外网.jpg "外网访问入口")](http://n.ustb.edu.cn)

### Markdown 转义字符语法
  - 一般字符均在前面加`\`
  - 特殊字符自动转义
    - `&` -->`&amp;`
    - `<` -->`&lt`
### Markdown 内嵌HTML标签
- 有些HTML标签可直接在Markdown中使用
- 但也并非所有的应用程序都支持，具体见官方提供的手册
## Markdown 扩展语法
### Markdown 表格
- 连字符(`---`)管道字符(`|`)
```
|Syntax|Description|
|---|---|
|Header|Tital|
|Paragraph|Text|
```
|Syntax|Description|
|---|---|
|Header|Tital|
|Paragraph|Text|
- 对齐(依次为左、中、右)
```
|Syntax|Description|Test text|
|:---|:---:|---:|
|Header|Tital|Here's this|
|Paragraph|Text|And more|
```
|Syntax|Description|Test text|
|:---|:---:|---:|
|Header|Tital|Here's this|
|Paragraph|Text|And more|
- 格式化表格中的文字
  - 可加链接、代码、强调
  - 不可加标题、块引用、列表、水平规则、图像或HTML标签
- 在表中转义管道字符
  >`|` -->`&#124`
### Markdown 围栏代码框
- 首尾加` ``` `
- 语法高亮
  >在` ``` `后加上语言名称  

  ```python
  print("hello world")
  ```
### Markdown 脚注
喻锦程[^1]

[^1]:myboy

### Markdown 标题编号

`[Heading IDs](#custom-id)`  

[Heading IDs](#custom-id)
### Markdown 删除线
- 在需要删除的语句首尾加`~~`   
- 就像~~这样~~
### Markdown 任务列表语法
- 注意`[ ]`前后有空格，中间也要有
```
- [x] Write the press replease
- [ ] Update the website
- [ ] Contact the media  
```
- [x] Write the press replease
- [ ] Update the website
- [ ] Contact the media
### 自动网址链接
`http://www.example.com` 

http://www.exanmple.com
