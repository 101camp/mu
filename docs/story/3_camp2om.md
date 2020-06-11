# 在线课堂
> 时隔多年, 忽然又有了机会

## 背景
> PyCon2012China 筹备

- 无意间接触到某机构创始人
- 虽然没就 Python 中国大会的赞助形成决议
- 但是, 意外明确到双方对什么是学习有相似体验~

## 社群

- 所以, 后来对应机构成立社群时, 邀请进入号称必须博士或双学位才能进入的微信群
- 从一开始就有不同以往微群的气势
- 长期组织各种很有份量的在线分享
- 仅仅10个月的聊天记录, 经过整理就出版成书

## 学堂
> 社区有了稳定成员之后应该作什么?

- 作为认知学派, 当然是要开坛宣法了 ;-)
- 启动在线课程简直太自然了...
- 只是, 大家都不知道怎么开展, 于是找到俺来架构
- 当然是将 **蠎营** 的自学过程扛出来哪
- 但是, 无论怎么讨论, 大家都认为风险太大


### 旗舰班
于是在试一试的整体情绪中, 紧急上线了:

- 课程内容发在 网易云课堂[^2] 
- 助教们协同在: Tower (同前, 原因只是有合作关系)
- 私人备课在: 私人维基 [^4]
- 学员练习在: coursera 
- 定期答疑用: WeChat
- 定期直播在: GoToMeeting
    + 录像发布在: Youtube 
- 代码在: github 
- 笔记在: gitbook [^8]
- ...

流程简化为:

- 头一周, 进入各种环境, 当大家完成基本的 fork, 发布 gitbook 之类准备
- 再7周, 每周一个小任务, 围绕一个软件需求逐步实用化:
    + 从简单的 CLI 交互
    + 追加 GUI 
    + 到本地 Web 网站
    + 再发布到外网
    + 尝试发布为移动 web 应用
    + 最后包装为 微信公众号后台
    + ... 这样在过程中经历一个可用软件可能涉及到的所有领域
- 留4周, 大家分组快速完成一个可演示实用作品
- 最后, 用了一周时间逐一线上进行演示发布
- 收功 [^11]

![pyicamp-flow-all_wsd-napkin.png(PNG 图像,530x513 像素)](http://s5.zoomquiet.top/110226-why-pythonicamp/i/map/pyicamp-flow-all_wsd-napkin.png?imageView2/2/w/420)


### 第二期
> 由于反应良好, 也摸清了在线课程的各种坑, 马上正式班也来上线了

- 根据复盘经验, 从头重构了课程
- 核心任务线索不变, 但是简化了课程环境:
    + 课程代码: github 
    + 课程笔记: gitbook
    + 定期直播+答疑: OBS推流到斗鱼
        * 辅以 TermRecord[^21] 录制的终端动画影片 [^22] 来演示技术
    + 助教协同也在: github

因为刚好人在广州工作, 所以, 追加了线下交流
```
    Communicate
    Coding  for √ Teaching
                  Thinking
                √ Thursday
                  Technique
```

- 中文名称: **同侪汇**
- E文代号: **C2T2**
- 内容:
    + 以代码为媒介
    + 现场编程为主要行为
    + 串接各种可能的内容/项目/自学...
- 期望: 如 `R2T2` 那样,可以从整体上掌握越来越多的语言技能
- 特色
    - 以`学员互助`为主,学员互助自由交流时间必须大于教练一对多单向输出的时间
    - 参与者需要在活动结束 42 小时内发布纪要链接到报名 issue 中
        - 并附带 42 字内文字说说自己今天最大的收获
- 注意:弃用`面基`一词,因为 `面基` 是个极其恶意的 KUSO 名词
    - 最好不要使用
    - 或是给出特殊解释
    - 统一使用 `同侪汇` 这种原创活动品牌!

只是这样一来, 每次就得一人顶整个团队来完成直播:

![obs](http://101.zoomquiet.top/res/snap/omooc2py5obs.jpg)

- 现场主持(有学员到现场来交流)
- 斗鱼主持
- 微信群主持
- 主题讲师
- 幻灯翻页
- OBStuido 直播导播
- 音乐DJ
- 现场录音
- 接待
- ...

当时直播用幻灯 [^15]...

- 整体节奏没变:
    + 一周进入
    + 七周演习
    + 四周作品
- 简化了课程环境, 又追加了线下交流, 仅仅俺参加的就有:
    + 广州 12 次
    + 上海 1 次
    + 北京 2 次
    + ...还有各地区长主持的定期交流20多次
- 最后效果更好 
    + 甚至于还有怀孕也坚持完课程, 并成功发布作品的 [^20]

> 于是, 开始想规模化...

### ...后来
> 卡片式自学系统...

- 在编程入门班稳定运营的同时, 加大投入连续发布了 写作班/信息分析课/黑客/...
- 着重介绍 `纳博科夫`的卡片写作方法, 并加以认知学知识/技巧
- 并进一步认为, 这种写作方法也是自学任何知识的好形式
- 为此专门开发了移动应用, 要求所有课程都要将内容卡片化
- 到了之后, 所有内容都在 app 中, 虽然 github 的使用还是原先架构
- 但是, 助教人数加倍后, 却全是新人了, 几乎所有行动/指标/文案/... 都要从新再教一次
- 也正好进入创业期, 难以兼顾, 就退为顾问
    + 社区运营
    + 课程设计
    + 技术支持
    + ... 各种需要的方向上顾问
- 主要也就是主持开学/毕业典礼的单口
- 效果也维持住了 [^23][^24]


## 感触
> 感谢 某机构 提供的机会, 得以触及商业课程的运营过程

也共同探索明确:

- 学员质量决定几乎一切
- 课程环境越简洁越好
- 线下当面交流质量永远最强
- 助教数量并不测定课程体验
- ...
- 在线教育真的有搞头...



## refer
> 删除部分失效链接...

[^2]: [Python编程入门 - 网易云课堂](http://skm.zoomquiet.top/data/20170329212207/index.html)

[^3]: [[大妈吐糟]Tower 之功能残念集 - 简书](https://www.jianshu.com/p/3e02dbc7a2e5)

[^4]: [ls /omooc Zoom.Quiet Personal Static Wiki](http://wiki.zoomquiet.io/omooc/)


[^11]: [3个月,编程小白做出了5个直戳生活痛点的程序](http://skm.zoomquiet.top/data/20160123234857/index.html)

[^13]: [教程该怎么写 | 蔡美娟的py学习笔记](https://picklecai.gitbooks.io/omooc2py/draft/how2tutorial.html)


[^15]: [_presentaions](https://drive.google.com/drive/folders/0BwPxePCteZKoNVVILU9lcUlwbWc?usp=sharing)


[^20]: [Suprise与不插电试验 | Zoe的Python星际之旅](https://zoejane.gitbooks.io/omooc2py/content/1sTry/surprise.html)
> 这周最大的surprise当属发现自己怀孕了

[^21]: [theonewolf/TermRecord: Terminal session recorder that outputs self-contained HTML!](https://github.com/theonewolf/TermRecord)

[^22]: [Index of /res/tr {gen. by gen4idx.py v13.4.18 from Zoom.Quiet}](http://openmindclub.zoomquiet.top/res/tr/index.html)

[^23]: [通向极客世界的任意门:Zoom Quiet | 浚宇的博客](https://blog.junyu.io/posts/1002-zoom-quiet-meetup.html)

[^24]: [半年:完成从小白到"黑客"的蜕变 Py103/LearningSummary.md at master · leiyunhe/Py103](https://github.com/leiyunhe/Py103/blob/master/Chap8/note/LearningSummary.md)

