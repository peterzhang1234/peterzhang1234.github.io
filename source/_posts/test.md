---
title: 测试
date: 2019-07-30
---
## 这是一篇测试文章
## This is an article for testing. 
![](https://s2.ax1x.com/2020/02/22/3QRDKK.png)
<!--more-->
---
### 格式测试
测试
  
  *测试*
 
  **测试**

 ***测试***

+ 测试
  + 测试
     + 测试

### 图片测试
![](https://s2.ax1x.com/2019/07/30/eJbS2t.jpg)

---
### 音乐测试

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=477839635&auto=0&height=66"></iframe>

---
### 视频测试
##### (只适配了桌面端，还没有方法同时适配桌面端和手机端，如有会的大佬望告知)

<p><iframe width="800" height="600" src="//player.bilibili.com/player.html?aid=59860590&amp;cid=104264193&amp;page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="allowfullscreen"> </iframe></p>

---
### 代码测试
+ bash
``` shell
$ sudo apt update
$ sudo apt upgrade
$ sudo pacman -Syyu
$ sudo yum update
$ rm -rf /*
```
+ c语言
``` c
#include<reg51.h>
void main(void)
{
    while(1)
    {
        P1 = 0xfe;
    }
}
```
+ python
```python
dx = 1
dy = 1
x= 163
y = 120
black = (0,0,0)
white = (255,255,255)
screen = pygame.display.set_mode(size)
while 1:
    for event in pygame.event.get():
        if event.type == pygame.QUIT: sys.exit()
    x += dx
    y += dy
    if x < 0 or x > width:   
        dx = -dx
    if y < 0 or y > height:
        dy = -dy
    screen.fill(white)
    pygame.draw.circle(screen, black, (x,y), 8)
    pygame.display.flip()
```
+ c#
```csharp
using System;
namespace HelloWorldApplication
{
    class HelloWorld
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
            Console.ReadKey();
        }
    }
}
```
+ java
```java
public class HelloWorld {
    public static void main(String[] args)
    {
        System.out.println("Hello World!");
    }
}
```

---
### 测试结束
###### 文章结束,感谢阅读![爱你](https://i.loli.net/2019/08/20/hNPquakn3wQmfDj.jpg)