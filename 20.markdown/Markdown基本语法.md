Markdown基本语法
===

- 作者：晓白齐齐
- 状态：完成
- 编辑：2021.1.12
- 更新：2023.10.31

---
## 实用工具
- [在线生成表格工具](https://www.tablesgenerator.com/markdown_tables)

---
## 常用链接
- [Markdown 基本语法](https://markdown.com.cn/basic-syntax/)
- [Markdown 扩展语法](https://markdown.com.cn/extended-syntax/)
- [速查表](https://markdown.com.cn/cheat-sheet.html)

---
## 标题语法
- 写法：\# 标题内容  
- 如：\#\# 二级标题
- 注意#号和标题内容之间一定要有一个空格，几级标题就用几个#号
- 大标题（一级标题）在标题下用===进行区分

---
## 分隔线语法
- 写法：\-\-\-
- 在标题上用\-\-\-添加分隔线
- 在需要分隔的前后均添加空行

---
## 段落语法
- 写法：使用空白行将一行或者多行文本进行文本分隔
- html写法：\<p\>段落内容\<\/p\>
- \<p\>、\<\/p\>和段落内容写在同一行
- 不要用空格或者tab缩进段落
- 为了兼容性，使用html写法

---
## 换行语法
- 写法：在一行的末尾添加两个以上的空格按回车键
- html写法：文字\<br\>
- 为了兼容性，使用html写法

---
## 强调语法
### 加粗
- 写法：左右分别用**两个&#42;号**将加粗内容包起来
- 如：\*\*加粗字体\*\*

### 斜体
- 写法：左右分别用*一个&#42;号*将斜体内容包起来
- 如：\*斜体字体\*

### 加粗斜体
- 写法：左右分别用***三个&#42;号***将斜体加粗内容包起来
- 如：\*\*\*斜体加粗字体\*\*\*

---
## 引用语法
- 写法：>引用的段落
- 多个段落引用，每个段落之前添加一个>，并在段落之间添加一个>和空白行
- 嵌套引用，在嵌套的段落前添加一个>>

---
## 列表语法
### 无序列表：
- 写法：*+空格+内容
- 如：* 内容1 
- 注意星号和内容之间一定要有空格

### 有序列表
- 写法：数字+空格+内容
- 如：1. 内容 

### 列表嵌套
- 嵌套列表比上一级列表多输入4个空格

### 列表嵌套其他元素
- 在同一列表中嵌套其他元素，需要对其他元素缩进4个空格
- 代码块一般缩进4个空格，在同一列表中嵌套代码块，需要缩进8个空格

---
## 代码语法
### 单个单词或单行代码
- 写法：左右分别用一个\`（反引号）将代码包起来
- 如：\`int i = 0;\`
  
### 代码中包含一个或多个反引号
- 用双反引号（即2个单反引号）将代码包起来
- 如：\`\`list=\`ls route\` \`\`
- 如果代码的最后一个字符为反引号，则需要与最后的双反引号之间留一个空格

### 代码块
- 写法：代码块上下分别用三个\`（反引号）包起来
- 如：<br>\`\`\`<br>int i = 0;<br> i = i + 1;<br>\`\`\`

---
## 链接语法
- 写法：&#91;链接文字&#93;(链接)
- 如：&#91;百度&#93;(https://www.baidu.com/)
- 给链接添加一个标题，当鼠标悬停在超链接文字时会出现这个标题：&#91;链接文字&#93;(链接 标题)
- 链接和标题之间需要空一格，如：&#91;百度&#93;(https://www.baidu.com/ "点击进入百度")
- 链接的url的空格用%20代替

---
## 图片语法
- 写法：\!&#91;图片名称&#93;(图片地址 ''图片标题'')
- 如：\!&#91;这是一张测试图片&#93;(https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg ''测试图片'')
- 给图片添加链接，将整个图片用一个方括号括起来，在后面用圆括号添加链接

---
## 表格语法
### 基本写法
- 表格写法：
<br>|表头1|表头2|表头3|
<br>|---|----|----|
<br>|内容|内容|内容|
<br>|内容|内容|内容|
- 每一行用|分隔每一列，第2行用三个\-分隔标题

### 表格对齐
- 可以在第二行的\-\-\-左侧添加:，表示这一列文本左对齐，右侧添加:，表示右对齐，左右添加:表示居中对齐
- 单行文字居中：内容两边加-
- 单行文字居右：内容右边加-
- 单行文字居左：默认居左

---
## 删除线语法
- 写法：左右分别用**两个~**将删除的内容包起来
- 如：\~\~删除的内容\~\~

---
## 转义字符语法

- markdown需要进行转义的字符串有

  |字符|名称|
  |:---:|:---:|
  |\\|反斜杠|
  |\`|反引号|
  |\*|星号|
  |\_|下划线|
  |\{\}|大括号|
  |&#91;&#93;|中括号|
  |&#40;&#41;|小括号|
  |\#|井号|
  |\+|加号|
  |\-|减号|
  |\.|英文句号|
  |\!|感叹号|

---
## 特殊符号实体编码

- 个别符号可以通过实体编码表示，例如\&\#42;表示*号
- 以下记录一些特殊符号的实体编码

  |符号|名称|实体编码|
  |:---:|:---:|:---:|
  |&#42;|星号|&#42\;|
  |&#91;|左中括号|&#91\;|
  |&#93;|右中括号|&#93\;|
  |&#40;|左小括号|&#40\;|
  |&#41;|右小括号|&#41\;|

- 注：实体编码以&#开头，以英文分号结尾
- 可通过[此网站](https://www.sojson.com/unicode.html)进行实体编码转换

---
## 其他特殊语法
- [脚注语法](https://markdown.com.cn/extended-syntax/footnotes.html)
- [标题编号](https://markdown.com.cn/extended-syntax/heading-ids.html)
- [复选框任务列表](https://markdown.com.cn/extended-syntax/task-lists.html)

---
## 流程图
- 流程图的编写采用mermaid方式，可以参考以下文章
   - [Mermaid 实用教程](https://blog.csdn.net/fenghuizhidao/article/details/79440583)
   
   - [Mermaid github](https://github.com/mermaid-js/mermaid)
   
   - [使用Mermaid画图](https://www.cnblogs.com/thomaszdxsn/p/shi-yongMermaid-hua-tu.html)

   - [mermaid语法](https://mermaid.js.org/intro/)

---
## Quiver快捷键

- Shift + Enter在文章最后添加新的Cell

- Shift + Command + Enter在当前光标处插入一个新的Cell

---
## 参考文档
- [Markdown 基本语法](https://markdown.com.cn/basic-syntax/)
- [Markdown 扩展语法](https://markdown.com.cn/extended-syntax/)
- [Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed/)
- [Markdown常用语法（缩进、换行、字体大小等）](https://blog.csdn.net/u011732358/article/details/83098211)
- [Markdown常用快捷键](https://www.cnblogs.com/liuweida/p/10787255.html)
- [markdown 需要转义的字符](https://blog.csdn.net/xianghongai/article/details/78976273)
- [HTML 转义字符](http://www.w3chtml.com/html/character.html)

---