## 标题
```markdown
# 一级标题 {#my_id}
## 二级标题 {.class1}
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

注:属性选择器是MPE扩展的特性，不一定兼容
```
# 一级标题 {#my_id}
## 二级标题 {.class1}
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

注：上面的`#id`成功了，但是`.class`失败...
___
## 正文
正文直接输入即可  

## 换行
换行：在行尾空两行  
隔行换行：空一行即可

## 代码块
一对```可以插入代码块，不同语言在第一行末尾加上语言名称  
```java
//Java代码块
Public class Test{
    public static void main(String[] args){
       String[] arr={"beijing","shanghai","shenzhen"};
       for(String x:arr){
       System.out.println(x);
      }
    }
}
```
```js
//JS代码块
var div=document.getElementsByTagName("div");
div[0].onclick=function(){
  alert("Hello World!");
};
```

## 行内代码
正文代码通过一对双反引号进行输出，比如``echo "Hello World";``

## 有序列表
格式：数字+点+空格，使用``Tab``键添加子列表
1. 星期一
2. 星期二
3. 星期三
   1. 早上
   2. 中午
   3. 晚上

## 无序列表
格式：短横杠+空格
- 1月
  - 1号
  - 2号
- 2月
  - 27号
  - 28号
    - 早上
    - 晚上

## 加粗和倾斜
一对``*``，*倾斜*  
一对``**``，**加粗**  
一对``***``，***加粗和倾斜***

注：双下划线也能实现相同的效果

## 图片和链接
### 图片
```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### 超链接
1. 自动生成  
https://github.com
2. ``[GitHub](https://github.com)``  
[GitHub](https://github.com)

## 引用
马尔克斯在《百年孤独》的开头这样写道： 
> Muchos años después, frente al pelotón de fusilamiento, el coronel Aureliano Buendía había de
recordar aquella tarde remota en que su padre lo llevó a conocer el hielo.  

> 多年以后，面对行刑队，奥雷里亚诺·布恩迪亚上校将会回想起父亲带他去见识冰块的那个遥远的下午。

## 分割线
```

```