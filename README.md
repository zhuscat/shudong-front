# shudong-front

---

## 要求

7 月 25 日之前制作完毕

大体布局不要用 `absolute`

很多东西可以复用，直接复制过来就好了

可以看一下已经写好代码

到时候直接提交到 shudong 项目下面

大家可以看到，项目的views文件夹下面是tpl的文件，你们写的时候就是写html，html文件放到views文件下面，css,js,图片文件放到static文件夹下面

## 剩下的页面制作

### 1. 管理页面

**重要程度: 紧急**

需要用到ajax的地方：

发送广播，发送通知

书籍管理：下架，删除，删除评论，禁言用户

发送信息的data先不用管，到时候我来填充，我懒得写接口什么的了，把页面写得十全十美就好！！！

返回数据的形式为

```
{
	"success": true,
	"info": "Operation..."
}
```

### 2. 注册页面提示

**重要程度：一般**

样式我没有做，怎么好看怎么弄，简洁大方上档次即可

也是发送ajax检测是否成功，形式同上

### 3. 私信

**重要程度：重要**

仔细看设计页面，交互的形式是先出现窄的那条，一条一条排列写来，然后点击查看是显示下面的那个。