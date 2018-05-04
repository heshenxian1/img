# img
lib of img

## Github 图片引用 

将原有图片地址：
> https://github.com/heshenxian1/img/blob/master/bound-world-170806.001.png
>

改为
> https://raw.githubusercontent.com/heshenxian1/img/master/bound-world-170806.001.png
>

其中字段标准化操作是：
「https://raw.githubusercontent.com/ 」字段+「(heshenxian1)/」字段 (heshenxian1 代表任意Github个人账号) + 图片链接字段「img/bound-world-170806.001.png」。
图片链接字段通过「Copy Path」即可获得。

若直接用 Markdown Here 获取图片链接，结果如下：
> [img/bound-world-170806.001.png at master · heshenxian1/img](https://github.com/heshenxian1/img/blob/master/bound-world-170806.001.png)

如上是在Github上提供图片链接的一种解决方案，但尚不够优雅，进一步自动化批量化处理方法，需要迭代。

应用七牛在线上传图片生成Markdown 链接是一种方法。


## ChangeLog
 - 20180503 何燊贤建立，小结以前上传图片建立软链接的小办法。
 -
 
