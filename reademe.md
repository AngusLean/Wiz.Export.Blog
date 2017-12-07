为知笔记导出工具，用于导出笔记为博客使用的格式。 

## 当前仅仅实现了导出markdown笔记为[Hexo](https://hexo.io/zh-cn/docs/commands.html)的博客格式
做的操作：

- 读取笔记的标签，并且在导出的文件头中添加

>
	tags:
	  - xxx
	  - xxx


- 读取笔记的分类，并且在导出的文件头中添加

>
	categories:
	  - xxx 
	  - xxx

 
- 读取笔记的标题，并且在导出的文件头中添加
>
	title: xxx

- 读取笔记的修改时间，并且在导出的文件头中添加
>
	date: xxx


## tips
- 在为知笔记中编写的markdown文本必须满足markdown格式</br>
**直接粘贴图片到markdown中，导出时无法显示图片。 必须使用外链的方式才能通用**

## todo
- 编写markdown图片上传插件，便于直接上传图片
- 编写笔记内容分析， 自动给笔记设置合适的头