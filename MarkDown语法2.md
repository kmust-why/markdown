# MarkDown语法2
## 链接demo
其中[]里面的内容为文字，()里面的内容为链接的地址
### 内嵌式链接
- 外部链接
[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文档:
[内部链接1](README.md)
- 内部链接2，链接本文档的其他部分:
[代码块demo](MarkDown语法2.md#代码块demo)
### 引用式链接
- 外部链接
[百度]
[百度][baidu] 取一个别名
- 内部链接1，链接仓库的其他文档:
[内部链接1]
- 内部链接2，链接本文档的其他部分:
[代码块demo]

## 图片demo
其中[]里面放的为alt,()里面放的为url,text，  
- 图片的MarkDown语法  
         ![alt](url text)
- 外部图片  
![baidu](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1502687968157&di=0c8b12b9630c5a93ae34b4327b3412e2&imgtype=0&src=http%3A%2F%2Fgb.cri.cn%2Fmmsource%2Fimages%2F2008%2F02%2F13%2Fei080213005.jpg '百度图片')
- 仓库内的图片 ，此时alt,text参数可以省略  
![](images/timg.jpg)
- 图片的引用式链接  
![baidu][baidu_logo]


## 引用demo
>这是一句引文。  
出自《出自》
- 多次引用。
>>>这是多重引文

## 代码块demo
- 行内代码
该变量的定义为:`int aa = 90`，打印的结果通过`printf(aa)`。

- 块式代码  
```javascript
var a = 10;
console.log(a);
```

<!--下面为本文档中用到的链接-->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[内部链接1]:README.md
[代码块demo]:MarkDown语法2.md#代码块demo
[baidu_logo]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1502687968157&di=0c8b12b9630c5a93ae34b4327b3412e2&imgtype=0&src=http%3A%2F%2Fgb.cri.cn%2Fmmsource%2Fimages%2F2008%2F02%2F13%2Fei080213005.jpg
