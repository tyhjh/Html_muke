# 网页开发初体验

标签（空格分隔）： Html

---

一直想学一下网页的，都没机会也不知道从何下手。平时常上的网页都很好看，觉得很有意思，最近就想模仿一下 [慕课网](http://www.imooc.com/)的首页，做一个像样子的网页。
其实之前也写过两次网页，都是为了交作业，虽然感觉还是挺有意思的，但是也没有深入了解，时间久了就忘的差不多了。

花了三天时间，总算是做完了，效果图([打开网页](http://tyhj5.com/wallPaper))：
![](http://a2.qpic.cn/psb?/V11FnAqi1JZY5X/JeJMF2kg643whjAqZahTQzzOMSWaZfGWjN7QaDKRhus!/b/dD0BAAAAAAAA&ek=1&kp=1&pt=0&bo=5AiOBeQIjgURECc!&vuin=1043315346&tm=1502456400&sce=60-2-2&rf=viewer_311)

我感觉还好，想不到这么快就完成了，其实很简单，就是html+javaScript+css而已，都是边做边学。

自己觉得要注意的地方：
```html
/*垂直居中*/
            position: relative;
            top: 50%;
            transform: translateY(-50%);
            
/*列表横排*/
            display: inline;
            
            
/*鼠标移动变小手*/
        cursor: pointer;
        
/*input设置无边框*/
            color: grey;
            border-top-width: 0px;
            border-right-width: 0px;
            border-bottom-width: 1.2px;
            border-left-width: 0px;
            border-top-style: none;
            border-right-style: none;
            border-bottom-style: solid;
            border-left-style: none;
            border-bottom-color: gainsboro;
            outline: medium;
            height: 30px;
            
/*实现阴影*/
            box-shadow: 0px 5px 10px gainsboro;
            
/*全屏无边距*/
        html, body {
            margin: 0px;
            height: 100%;
            width: 100%;
            font-family: "Microsoft YaHei";
        }
```

其实并没写完，也没用完全一样，但是真的有意思。







