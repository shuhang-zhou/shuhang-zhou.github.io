---
export_on_save:
  html: true
---
#2023微信聊天年度总结

分析工具来自[YiHui Liu](https://foolishfox.cn/posts/202402-WeChatMsgAnalysis.html)。本文数据由Luminous和On The Road在2023年微信聊天的全部内容分析得到。由于作者在**情感分析**板块的结果明显存在问题，因此此项仅仅展示部分结果。

[TOC]

##数据时间

2023 年 1 月 1 日 - 2023 年 12 月 31 日

##发送消息整体分析

###消息频率

以下是 2023 年消息的频数分布：

![massage_freq_analyse](/images/articles_images/wechat_analyse_2023/massage_freq_analyse_enhanced.png)

横坐标可以看出消息类型被分为了文本，图片，声音，视频和表情包。消息总量来说 ZSS 以 46705 条消息领先于 OTR 的 39200 条消息，大约多发送 **19%** 的消息。但是 OTR 发送的消息种类比 ZSS 更平均。

###消息长度

以下是 2023 年发送消息的长度统计结果：

![massage_length_analyse](/images/articles_images/wechat_analyse_2023/massage_length_analyse_enhanced.png)

明显可以看出，由于 ZSS 发送的信息数目比 OTR 多，所以在发送的每种长度的消息上， ZSS 全面领先。每种长度的文本领先程度不同，但是 ZSS 发送的中长消息类型占比显然比 OTR 同比更高。

##活跃分析

###每日活跃分析

以下是 2023 年每天的活跃时间段：

![daily_active_analyse](/images/articles_images/wechat_analyse_2023/daily_active_analyse_enhanced.png)

和一般情侣的活跃时间分布不同，明显是异地恋且有时差的活跃分布。这里的时间是**巴黎时间**。因此 19 点过后 OTR 的活跃程度明显降低，大概在 2 点之后 OTR 的活跃程度反超 ZSS 。一直到白天两人同时在线的时候交流开始密切。考虑到**巴黎时间**和**北京时间**只有 7 个小时时差（夏令时 6 小时时差），很明显两个人都是夜猫子。

###每周活跃分析

以下是按周来统计活跃指数（消息数）：

![weekly_active_analyse](/images/articles_images/wechat_analyse_2023/weekly_active_analyse_enhanced.png)

消息数基本上平均分布且很多，而且**星期六**双方交流更加密切，可能是可以熬夜吧！

###按周划分年度活跃分析

以下是 2023 年每周的活跃指数（消息数）：

![](/images/articles_images/wechat_analyse_2023/yearly_active%20_analyse_by_week.png)

可以看出，看不出什么来。唯一值得一提的是，05-01的后两周和12-18的后两周明显消息变少了，为什么呢？当然是见面了！

###按日划分年度活跃分析

以下是用热力图的方式展示按日划分的年度活跃情况：

![yearly_active%20_analyse_by_day](/images/articles_images/wechat_analyse_2023/yearly_active%20_analyse_by_day.png)

看不出什么来，每天都会交流这是最基本的。


##聊天热情分析

按周划分的聊天热情分析，每7天内的聊天热情指数，聊天热情指数为发送的消息数减去收到的消息数与总消息数的比值：
$$
E = \frac{Q_\mathrm{S} - Q_\mathrm{R}}{Q_\mathrm{S} + Q_\mathrm{R}}
$$
![](/images/articles_images/wechat_analyse_2023/passion_score_by_week.png)

直观上看双方热情指数差不多，可能由于 ZSS 发送消息数目比较多的缘故， ZSS 更加热情一些（指数为负比较多）

##词语分析

利用分词词典分词，并统计做简单的分析。

###高频词排行

以下是双方的常用词及其贡献：

![high__requency_words_analyse](/images/articles_images/wechat_analyse_2023/high__requency_words_analyse.png)

其实应该做一个标准化，由于 ZSS 说的话更多，两边的相对比较多少失去了一些意义。其中颜色代表了双方说同一个词的比重，说的比例越多，颜色约暖。

###词云分析

OTR 的小兔子词云图：

![wordcloud_analyse_OTR](/images/articles_images/wechat_analyse_2023/wordcloud_analyse_OTR_enhanced.png)

图片有一点不清晰，但是还是很明显的，字体越大代表说的频率越高。
 
ZSS 的小狐狸词云图：

![wordcloud_analyse_ZSS](/images/articles_images/wechat_analyse_2023/wordcloud_analyse_ZSS_enhanced.png)

哈哈哈！很开心！

##情感分析

应该是根据分词之后的词语的情感做的简单的分析吧。但是作者和我说应该是模型不那么匹配导致结果有明显错误。因此只选择一些个人认为正常的图片展示分析

###年度总体情感分布



![annual_sentiment_distribution](/images/articles_images/wechat_analyse_2023/annual_sentiment_distribution.png)

图中每种分数的计数个人觉得没有意义，因为分数的划定是不够标准的，而 ZSS 的消息数更多，因此每种分数都比 OTR 更高一点。统计图完全图一乐，值得注意的是 OTR 的极消极情绪（score = -1）明显高于 ZSS 。还请新的一年 OTR 小朋友更加乐观一些，开开心心的！

###按周统计平均情感指数

![average_sentiment_score](/images/articles_images/wechat_analyse_2023/average_sentiment_score_by_week.png)

ZSS 情感指数更高一点，原因不详，统计可靠程度不详，**但至少**爱从来没有消失。

##总结

微信 2023 年度统计结束，赶在 2024 新年开始前。

当然还有 QQ 统计，数据的导出更加麻烦一点就不统计了。根据我的猜测，双方词云的变化，尤其是 OTR 的会更加明显一些。因为聊师兄师姐科研会更少一点。

明年再接再厉，一定有新的变化！毕竟新的一年新的生活就要到了。

过两天 OTR 回家一定要顺顺利利！