---

layout: post

title: Markdown 常用语法学习（一）

date: 2020-03-13

categories: Markdown 语法

tags: Markdown

description: Mardown 语法入门很容易，但用好需要一些训练。

---

# Markdown 常用语法学习（一）

## 1 Markdown 语法所用符号

 Markdown 语法系由一些经过精挑细选的符号所组成，其作用一目了然，以下半角英文符号在 Markdown 语法中具有特殊意义，各符号所表示的特殊意义详见下文。

|半角英文符号|中文名称|
|:-:|:-:|
|   \\   |反斜杠|
|`|反引号|
|*|星号|
|_|底线|
|{}|花括号|
|[]|方括号|
|()|括弧|
|#|井字号|
|+|加号|
|-|减号|
|.|英文句点|
|!|惊叹号|

此外，Markdown 语法采用在这些具有特殊意义符号前加反斜杠("\\")来表示其普通（本来）意义。

## 2 标题

Markdown 标题以"#"开头并用前置"#"的个数表示标题的级别，最多六级标题，前置"#"和标题文本间至少键入一个空格。

\#      一级标题  
\##     二级标题  
\###    三级标题  
\####   四级标题  
\#####  五级标题  
\###### 六级标题

上述语法显示效果如下：

># 一级标题
>## 二级标题  
>### 三级标题  
>#### 四级标题  
>##### 五级标题  
>###### 六级标题

## 3 段落与换行

### 3.1 段落

一个 Markdown 段落由一个或多个连续的文本行构成，它的前后要有一个以上的空行。空行是显示上看起来像是空的，便会被视为空行。比如，某一行只包含空格和制表符，则该行会被视为空行。普通段落不应用空格或制表符来缩进。示例如下：

> 这是一个段落。这个段落只有一行。

### 3.2 换行

Markdown 允许段落内的强制换行（插入换行符），具体方法为在插入处先键入两个以上的空格然后回车。示例如下：

> 这也是一个段落。  
这个段落有两行。

## 4 文本格式

### 4.1 加粗

文本加粗格式：加粗文本前后加"\*\*"或"\_\_"。

|语法|显示效果|
|:-:|:-:|
|\*\*加粗\*\*|**粗体**|
|\_\_粗体\_\_|__粗体__|

### 4.2 斜体

文本斜体格式：斜体文本前后加"\*"或"\_"。

|语法|显示效果|
|:-:|:-:|
|\*斜体\*|*斜体*|
|\_斜体\_|_斜体_|

### 4.3 加粗斜体

文本加粗斜体格式：加粗斜体文本前后加"\*\*\*"或"\_\_\_"。

|语法|显示效果|
|:-:|:-:|
|\*\*\*加粗斜体\*\*\*|***加粗斜体***|
|\_\_\_加粗斜体\_\_\_|___加粗斜体___|

### 4.4 删除线

文本删除线：删除线文本前后加"\~\~"。

|语法|显示效果|
|:-:|:-:|
|\~\~删除线\~\~|~~删除线~~|

### 4.5 下划线

文本下划线：可以采用 HTML 的 "\<u\>" 标签来实现，即在下划线文本前后分别加"\<u\>"和"\</u\>"。

|语法|显示效果|
|:-:|:-:|
|\<u\>下划线\</u\>|<u>下划线</u>|
