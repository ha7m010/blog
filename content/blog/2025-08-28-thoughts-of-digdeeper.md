---
title: 对Digdeeper的一些评论
date: '2025-08-28'
author: ham
---

# 关于 https://digdeeper.love/ 的一些思考
- **若无特别说明，中文翻译由[Microsoft Bing translator（中国）](https://cn.bing.com/translator)提供，我进行修补，但主要是格式修补和全宽半宽符号更改，内容基本不变。**

- **如果是资料的引用，如「某某文章说到……」某某文章若有超链接直接显示，是对其原文引用。**

- **若是扩展阅读，会使用角标标注。作为特例，某些原文也值得点进去看一看的，会两个都标**

- **英文原文的内容不改动原文超链接的规则，但删除了其中MozArchive的链接与文本，中文翻译会进行如上述修补**

**写完后记：编辑东西这种活真是恶心啊，什么都要改什么都要干，而且经常性不满意，工作时间还贼长。**

1. **有些地方的"achieve"链接是"（）"包裹在内的（链接同时包括了括号）而有些是"()"在外,只有"achieve"的字符在链接。**

2. **有一处英文原文链接格式上有问题，但我记不得了。**

3. **倒数第二处评论有引用两处原文的链接没有打上超链接的符号。**

4. **目录里面有个没有内容的列表我也不知道怎么回事。**

5. **有些地方的（）并未区分全宽与半宽。**

**以上五点可能是值得编辑工作的，但是我即使有时间也可能不会去改了哈哈，长文章编辑真是太累太恶心了。**

## [DoH](https://digdeeper.love/articles/fake_initiatives.xhtml#dnt)

> Invented in 2009, this browser header tells websites you visit that you do not want to be tracked. 9 years and thousands of articles and discussions about DNT later, and there is still not even a standard for what "tracking" exactly is it supposed to prevent - even though they promised to create one long ago. Needless to say, websites can interpret DNT however they want, or even ignore it altogether. How much effort has been wasted on this dud - effort that could have been spent on creating and improving browser extensions that actually protect you from tracking. DNT, on the other hand, just gives the illusion of privacy to unsuspecting users - which is worse than doing nothing at all. Let's be real here - cooperating with trackers could have never worked anyway - since they don't care about playing fair.
>
> 2009年发明的这个浏览器头，告诉你访问的网站，你不想被跟踪。9年后，成千上万的文章和讨论关于DNT，仍然没有一个标准，“跟踪”到底是什么应该防止-即使他们承诺创建一个很久以前。不用说，网站可以解释DNT，无论他们想要的，或者甚至完全忽略它。有多少努力被浪费在这个无用的东西上--这些努力本可以花在创建和改进浏览器扩展上，这些扩展实际上可以保护你免受跟踪。另一方面，只是给了不知情的用户隐私的错觉-这比什么都不做更糟糕。让我们在这里真实的-与跟踪器合作可能永远不会工作-因为他们不在乎公平竞争

认可的，现行的浏览器谈到「私密」也基本上不会推荐你开启DNS over HTTPS，第一个原因是网站不管，开了跟没开在这方面没大用处，所谓「君子协议」而已；第二个原因是会加上你的指纹，更加可以给你推个性化Ad或者用户图像给你推别的东西。

## [欧盟cookie法案](https://digdeeper.love/articles/fake_initiatives.xhtml#cookie)

> If you've spent any time on the Internet at all, you've surely seen some obnoxious cookie notices, such as:
>
> 如果您在互联网上花费过任何时间，您肯定见过一些令人讨厌的 cookie 通知，例如：
>
>![European Union cookie notice](https://digdeeper.love/images/cookie_notice.png)
>
> In 2011, the European Union has created a law which requires websites to inform visitors about the kind of data that will be stored on their computers, its purpose, as well as the need to get consent from users before storing anything. There were also guidelines for the duration of the cookie's existence. Anyway, a [report](https://privacylaw.proskauer.com/2015/02/articles/european-union/european-union-cookie-sweep-highlights-need-for-improved-compliance/) ([archive](https://web.archive.org/web/20181020114752/https://privacylaw.proskauer.com/2015/02/articles/european-union/european-union-cookie-sweep-highlights-need-for-improved-compliance/)) has shown that most websites do not follow all the requirements properly. Even if they did, the people who would benefit from this information won't understand it and will click through it instead; while the aware ones have already blocked the cookies - but will still be bothered by the obnoxious notices. It should also be mentioned that the most important tracking cookies - the social network ones - are exempt from the law! So you can still be tracked by Facebook and friends; talk about a wasted opportunity.
>
> 2011年，欧盟制定了一项法律，要求网站告知访问者将存储在其计算机上的数据类型，其目的，以及在存储任何内容之前需要获得用户的同意。还有关于cookie存在时间的指导方针。无论如何，[报告](https://privacylaw.proskauer.com/2015/02/articles/european-union/european-union-cookie-sweep-highlights-need-for-improved-compliance/)（[archive](https://web.archive.org/web/20181020114752/https://privacylaw.proskauer.com/2015/02/articles/european-union/european-union-cookie-sweep-highlights-need-for-improved-compliance/)）的研究表明，大多数网站并没有正确地遵循所有的要求。即使他们这样做了，那些将从这些信息中受益的人也不会理解它，而是会点击它;虽然有意识的人已经阻止了cookie──但仍然会受到令人讨厌的通知的困扰。还应该提到的是，最重要的跟踪cookie──社交网络cookie──不受法律约束！所以您仍然可以被Facebook和朋友跟踪；谈论浪费的机会。

Cookie的同意消息确实很烦，像[I still don't care about cookies](https://www.crxsoso.com/webstore/detail/edibdbjcniadpccecjdfdjjppcpchdlm)[^1]这样的扩展出现也就不足为奇了，网站只是相较于当初不给你看一下就获取cookie，到跟你讲「我要用你cookie了啊」，实质上的区别也相当于勾选同意条款。但是难道可以说这部法案没有积极影响吗？人们的隐私认识相较于之前的提高难道可以忽视吗？如果否认每一个微小的进步，那么社会从来不会前进，非黑即白的社会不存在于现实。

[^1]: 奔跑中的奶酪对于广告屏蔽的文章 https://www.runningcheese.com/adblock

## [隐身模式](https://digdeeper.love/articles/fake_initiatives.xhtml#incognito)

> Almost every browser has this under different names. Let's be clear here - **this does nothing whatsoever to protect you from nosy ISPs or trackers**; and, while most browsers do admit that - some, like Waterfox, have tried to ride the wave of confusion to pretend that their [improved private browsing](https://www.waterfoxproject.org/en-US/waterfox/features/private-browsing/) [(archive)](https://web.archive.org/web/20181021092350/https://www.waterfoxproject.org/en-US/waterfox/features/private-browsing/) does something more. A [report has shown](https://www.cnbc.com/2018/07/12/private-web-browsing-not-as-private-as-you-think-research.html) [(archive)](https://web.archive.org/web/20181021092637/https://www.cnbc.com/2018/07/12/private-web-browsing-not-as-private-as-you-think-research.html) that many people do in fact believe that this mode guards them from online spying; as far as I'm concerned, browsers should remove this if they want to stay honest - or at least change its name.
>
> **UPDATE**: Pale Moon kind of averts this with the [Proxy Privacy Ruler](https://digdeeper.love/articles/addons.xhtml#ppr) addon.
>
> 几乎每个浏览器都有不同的名称。让我们在这里明确一点 - 这对保护您免受爱管闲事的 ISP 或跟踪器的侵害没有任何作用;而且，虽然大多数浏览器确实承认这一点 - 有些浏览器，比如 Waterfox，试图乘着混乱的浪潮，假装他们改进的隐私浏览（存档）做了更多的事情。[一份报告显示](https://www.cnbc.com/2018/07/12/private-web-browsing-not-as-private-as-you-think-research.html) （[archive](https://web.archive.org/web/20181021092637/https://www.cnbc.com/2018/07/12/private-web-browsing-not-as-private-as-you-think-research.html)），许多人实际上确实相信这种模式可以保护他们免受在线间谍活动的侵害;就我而言，如果浏览器想保持诚实，他们应该删除它——或者至少更改它的名称。
>
> **更新**：Pale Moon 通过代理隐私标尺[插件](https://github.com/JustOff/proxy-privacy-ruler)[^2]避免了这种情况。

[^2]: digdeeper对于这个扩展的介绍 https://digdeeper.love/articles/addons.xhtml#ppr

说真的我在知道这件事之前（不是指我看到这篇文章才知道这件事情）我一直以为的就是浏览器不记录历史数据（那时候还不知道什么cookie，网站数据之类的），很惊讶有的人认为开了这个就高枕无忧了，但是浏览器这点确实是值得改变的。另外，对于他的这个插件，还是比较好的，但是对于[Brave](brave.com)的私密浏览[^3][^4]，意义好像只存在于「隐私爱好者」（讽刺义）的狂热颅内高潮了。但是，Brave的的隐私浏览确实应该（**没有调查过**）不如「隐私爱好者」的自己搭Tor的连接。

[^3]: 对于Brave 加密货币与它「特别」的广告处理模式的讨论 https://news.ycombinator.com/item?id=26332183

[^4]: 同上 https://news.ycombinator.com/item?id=23442027

[^5]: Vivaldi CEO对于反对加密货币的文章 https://vivaldi.com/blog/why-vivaldi-will-never-create-thinkcoin/

## [端到端加密](https://digdeeper.love/articles/fake_initiatives.xhtml#E2E)

> For the last few years, services which have traditionally been famous for their spying (such as Skype, Viber, or the Facebook operated [WhatsApp](https://fortknoxster.com/not-trust-whatsapp/) [(archive)](https://web.archive.org/web/20181021121246/https://fortknoxster.com/not-trust-whatsapp/)) have been loudly announcing their support of "end-to-end" encryption - which **should** mean that only you and the person you are communicating with can see the content of your messages. However, **it is still them generating the keys**, and therefore relies on their trustworthiness. Many allegedly "private" E-mail providers also suffer from this flaw - read [my report](https://digdeeper.love/articles/email.xhtml). The moral of the story - if you don't manage the encryption yourself, it's not truly end-to-end, and shouldn't be relied upon.
>
>在过去的几年里，传统上以间谍活动而闻名的服务（如Skype，Viber或Facebook运营的[WhatsApp](https://fortknoxster.com/not-trust-whatsapp/) （[archive](https://web.archive.org/web/20181021121246/https://fortknoxster.com/not-trust-whatsapp/)）一直在大声宣布他们支持“端到端”加密--这应该意味着只有你和你正在通信的人才能看到你的消息内容。然而，仍然是他们生成密钥，因此依赖于他们的可信度。许多所谓的“私人”电子邮件提供商也遭受这个缺陷-阅读我的报告。这个故事的寓意-如果你不自己管理加密，它就不是真正的端到端，不应该被依赖。

That's true. 真不知道Whatsapp宣布这个的目标群体是谁，没技术概念的乌合之众？企业政府内部通讯？虽然[特朗普政府把记者拉群里的事](https://baike.baidu.com/item/2025%E5%B9%B4%E7%99%BD%E5%AE%AB%E7%BE%A4%E8%81%8A%E6%B3%84%E5%AF%86%E9%97%A8/65521840)很搞笑，但是人也不是用的Whatsapp啊。但是这种事情确实属实，Proton Mail[^6][^7]的私钥是服务器上生成的，用户拿不到，Gmail也类似[^8]。

[^6]: Protonmail的原理与脆弱性 https://zhuanlan.zhihu.com/p/259887438

[^7]: 对 ProtonMail 及其它加密邮件服务的看法 https://blog.wangxuan.name/2021/10/03/protonmail-encryptied-email-review/

[^8]: 电子邮件自我保护指南 https://zhuanlan.zhihu.com/p/34632920

## [越来越少的直观设置](https://digdeeper.love/articles/fake_initiatives.xhtml#protection)

> This is simply a huge slippery slope - first it was plugins, then addons, then browser settings kept getting dumped into about:config or the abyss. What's next - deciding what sites you can or can't visit? Isn't Google SafeBrowsing just that? Maybe one day, they will block all "insecure" HTTP websites. Surely that's going too far - or is it? In fact, both [Firefox](https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/) [(archive)](https://web.archive.org/web/20181021170935/https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/)  and [Chrome](https://www.chromium.org/Home/chromium-security/marking-http-as-non-secure) [(archive)](https://web.archive.org/web/20181021171238/https://www.chromium.org/Home/chromium-security/marking-http-as-non-secure) have been trying to get rid of HTTP for a long time. Great, thanks Mozilla and Google for "protecting" me from all this malicious stuff - but **who will protect me from you**? That is the real question. Of course, people don't realize there is an issue until something they use regularly breaks. The solution, of course, is to only use software that actually respects you instead of treating you like a baby; **security will always be the responsibility of the user** - you cannot "protect" people from everything. Even if you could, it would not be desirable; there is always a trade-off between security and functionality, and people should be able to choose at which point of the spectrum they want to be.
>
> 这简直是一个巨大的滑坡-首先是插件，然后是插件，然后是浏览器设置一直被倾倒到about：config或深渊。下一步是什么-决定你可以或不能访问哪些网站？谷歌安全浏览不就是这样吗？也许有一天，他们会阻止所有“不安全”的HTTP网站。当然，这太过分了-或者是吗？事实上，无论是[Firefox]((https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/))（[archive](https://web.archive.org/web/20181021170935/https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/)）和Chrome([archive](https://web.archive.org/web/20181021171238/https://www.chromium.org/Home/chromium-security/marking-http-as-non-secure))很长一段时间以来一直试图摆脱HTTP。太好了，感谢Mozilla和Google“保护”我不受这些恶意东西的伤害-但谁来保护我不受你的伤害呢？这才是真实的问题。当然，人们只有在经常使用的东西坏掉的时候才会意识到问题的存在。当然，解决方案是只使用真正尊重你的软件，而不是把你当作婴儿对待;安全永远是用户的责任--你不可能“保护”人们免受一切伤害。即使你能做到，这也是不可取的;在安全性和功能性之间总是有一个权衡，人们应该能够选择他们想要的频谱的哪一点。

人们确实对于config的控制越来越小，比如chromium的MV3策略在140以前的版本仍然可用，但是140-141需要调整config，142+就不可用了[^9]。但是HTTP的例子确实帮助人们提高了网络安全，较少了可能的风险，HTTP Only插件已经完成了他的历史使命。[^10][^11][^12][^13]

不能一棒子打死，但是所谓「there is always a trade-off between security and functionality, and people should be able to choose at which point of the spectrum they want to be.」真的是绝大多数人需要的吗，是要调整一个平衡，但是「**ALL** people should be able to choose at which point of the spectrum they want to be.」是否是真的客观有利于人大家的呢？当然这不是说对于切香肠战术的投降，但是对于究竟怎么「端水」，还没有确切的方案。

[^9]: linux.do对于UBO的解决办法 https://linux.do/t/topic/784536

[^10]: AdGround对MV3的看法 https://adguard.com/zh_cn/blog/chrome-manifest-v3-where-we-stand.html

[^11]: brave浏览器的声明 https://brave.com/blog/brave-shields-manifest-v3/

[^12]: Ublock Origin作者最初的issue https://issues.chromium.org/issues/40598795#comment24

[^13]: Vivaldi浏览器的声明 https://vivaldi.com/blog/manifest-v3-update-vivaldi-is-future-proofed-with-its-built-in-functionality/

## [静默更新](https://digdeeper.love/articles/fake_initiatives.xhtml#updates)

> An extension of the above; they are the truck through which undesirable changes get dumped onto unsuspecting users. UI modifications, configuration option removals, the aforementioned blockages, additional spyware, or actual malware; regardless - auto-updates transfer control of the software from the users to developers. And there is no excuse to at least not ask the user before proceeding. The horror stories of updates breaking things are numerous - for example:
>
>以上的延伸：它们是将不受欢迎的更改倾倒给毫无戒心的用户的卡车。UI修改，配置选项删除，上述阻塞，额外的间谍软件或实际的恶意软件;无论如何-自动更新将软件的控制权从用户转移到开发人员。在继续之前，没有任何借口至少不询问用户。更新破坏事物的恐怖故事很多──例如：
>
> ### [Firefox freezing the computer](https://www.cnet.com/forums/discussions/firefox-57-is-awful/) ([archive](https://web.archive.org/web/20181023080940/https://www.cnet.com/forums/discussions/firefox-57-is-awful/))
>
>[Firefox冻结计算机](https://www.cnet.com/forums/discussions/firefox-57-is-awful/) ([archive](https://web.archive.org/web/20181023080940/https://www.cnet.com/forums/discussions/firefox-57-is-awful/))
>>
>>*My Firefox was updated to it yesterday. It froze when I tried to use it and froze the computer to where I had to use the power button to get out of it. I tried Firefox in safe mode and it still froze. I see messages in Mozilla Zine saying the same thing.*
>>
>>我的Firefox更新到它昨天。它冻结，当我试图使用它，并冻结了电脑，我不得不使用电源按钮来摆脱它。我尝试Firefox在安全模式，它仍然冻结。我看到Mozilla Zine中的消息说同样的事情。
>
> ### [Firefox changing the user's settings](https://groups.google.com/forum/?_escaped_fragment_=topic%2Fmozilla.support.firefox%2FE3qq9fDVPZc) ([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/kqkzC))
>
>[Firefox更改用户设置](https://groups.google.com/forum/?_escaped_fragment_=topic%2Fmozilla.support.firefox%2FE3qq9fDVPZc) ([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/kqkzC))
>>
>>*I would appreciate very much if Firefox update informed me about changes it does to my settings in detail. I want to have the chance to not be surprised by a new default search engine or a disabled https feature for example.*
>>
>>如果Firefox更新通知我它对我的设置做了详细的更改，我会非常感激。我希望有机会不一个新的默认搜索引擎或禁用的https功能，例如感到惊讶。
>>
>>*I first noticed it when it first introduced the "do not track me" setting. I enabled that and the next time I checked, it was disabled.*
>>
>>我第一次注意到它是在它第一次引入“不要跟踪我”设置的时候。我启用了这个设置，下次我检查的时候，它就被禁用了。
>
> ### [Another example of the same](https://www.ghacks.net/2016/12/05/beware-firefox-updates-may-reset-preferences/) ([archive](https://web.archive.org/web/20181023082733/https://www.ghacks.net/2016/12/05/beware-firefox-updates-may-reset-preferences/))
>
>[另一个相同的例子](https://www.ghacks.net/2016/12/05/beware-firefox-updates-may-reset-preferences/) ([archive](https://web.archive.org/web/20181023082733/https://www.ghacks.net/2016/12/05/beware-firefox-updates-may-reset-preferences/))
>
>>*Jern informed me that Firefox reset the block lists setting of the browser's Tracking Protection feature from strict to basic when the browser was updated to version 50 from Firefox 49.0.2. Basic protection is the recommended and default value of the setting. It does not block as many trackers as the strict blocking list.*
>>
>>Jern告诉我，当浏览器从Firefox 49.0.2更新到50版时，Firefox将浏览器的跟踪保护功能的阻止列表设置从严格重置为基本。基本保护是该设置的推荐和默认值。它不会像严格阻止列表那样阻止那么多跟踪器。
>>
>>*and Michel told me a week later that a recent Firefox update (to 50.0.1 or 50.0.2) did reset another preference. This time an URL string that Michel modified on Firefox's about:config page.*
>>
>>一周后，Michel告诉我，Firefox最近的一次更新（更新到50.0.1或50.0.2）确实重置了另一个首选项，这次是Michel在Firefox的about：config页面上修改的URL字符串。
>
> ### [Windows 10 updates are famous for breaking shit](https://www.zdnet.com/article/windows-10-upgrade-problems-these-are-the-biggest-hassles-you-face/) ([archive](https://www.zdnet.com/article/windows-10-upgrade-problems-these-are-the-biggest-hassles-you-face/))
>
>[Windows 10更新以打破狗屎而闻名](https://www.zdnet.com/article/windows-10-upgrade-problems-these-are-the-biggest-hassles-you-face/) ([archive](https://www.zdnet.com/article/windows-10-upgrade-problems-these-are-the-biggest-hassles-you-face/))
>
>>*The most common complaints after updating to Windows 10 were software compatibility issues, such as programs not working properly, or at all (21 percent), followed by hardware problems, such as printers and speakers no longer working (16 percent). Members also struggled with issues such as email accounts no longer syncing and personal files being inadvertently deleted, said Which? "Some consumers suffered PC slowdown and, in some cases, members reported complete PC failure. Of those in the survey who experienced this, 46 percent said they had paid someone to fix it, at an average cost of £67 each," noted the consumer group.*
>>
>>更新到Windows 10后最常见的投诉是软件兼容性问题，例如程序无法正常工作或根本无法正常工作（21%），其次是硬件问题，如打印机和扬声器不再工作Which说，会员们还面临着电子邮件帐户不再同步和个人文件被无意中删除等问题。该消费者组织指出：“一些消费者的电脑运行速度变慢，在某些情况下，会员报告电脑完全失灵。在经历过这种情况的受访者中，46%的人表示他们曾花钱请人修理，平均每台电脑花费67英镑。”
>
> ### And finally, [my absolute favorite](https://www.zdnet.com/article/corrupted-open-source-software-enters-the-russian-battlefield/) ([archive](https://web.archive.org/web/20240105064829/https://www.zdnet.com/article/corrupted-open-source-software-enters-the-russian-battlefield/)) :
>
>最后，[我最喜欢的](https://www.zdnet.com/article/corrupted-open-source-software-enters-the-russian-battlefield/) ([archive](https://web.archive.org/web/20240105064829/https://www.zdnet.com/article/corrupted-open-source-software-enters-the-russian-battlefield/))：
>
>>*Miller added code that would delete the file system of any computer with a Russian or Belorussian IP address. Then, its maintainer added the module as a dependency to the extremely popular node-ipc mode. Node-ipc, in turn, is a popular dependency that many JavaScript programmers use. And it went from annoying to a system destroyer.*
>>
>>米勒添加了一段代码，可以删除任何一台拥有俄罗斯或白俄罗斯IP地址的计算机的文件系统。然后，它的维护者将该模块作为一个依赖项添加到非常流行的node-ipc模式中。Node-ipc反过来又是一个流行的依赖项，许多JavaScript程序员都在使用。它从烦人变成了一个系统破坏者。

Ok，又是一个狗皮膏药一样的问题，IE、Firefox刚开始高频更新可能是因为为了蛋糕吃[^4]，但是Chrome的高市场占有并不只源于Google各种复杂的推广和历史原因，其中包含一份来自社区的高频Issue和修补，那么多的安全漏洞并不是更新出来的，而是Chrome团队修复的，你天天泡在网里，当然察觉不到别人的想法，就好像你对于其他领域也是「隔行如隔山」一样，对于普通人，哪里有必要做这么多自定义？所谓「防呆不防傻，大力出奇迹」，如果只会嘲笑别人「不思进取」，事情永远做不大，「团结一切可以团结的人」含金量还在上升。当然，开发团队独裁确实也需要注意，但是目前似乎也没有什么好的方法（只已有可行的、可以推广的经验和方案），所谓厌恶Big Brother就放任一切的自由，那么也只会找来黄赌毒血腥数据的犯罪大行其道。

[^14]: https://www.ithome.com/0/629/988.htm

## [重定向](https://digdeeper.love/articles/fake_initiatives.xhtml#linkfilters)

> Didn't know whether to put this here or in [Principles](https://digdeeper.love/articles/design.xhtml) of bad software design - but the alleged point of it is security, so it's here. How does this work? Briefly - certain sites, whenever a link is posted to them - will NOT let you go there directly but only through their special redirect. If this actually improved security I would just consider it as simple babying - similar to the auto-updates; but the reality is much more malicious as usual. Not only are the link filters annoying, but they make tracking easier by putting the website you're leaving to into the URL. Also, people can actually fucking see the link they're clicking on, so the security benefit is doubtful at best. Twitter goes even further and prevents users from knowing where they're going to - every web address is replaced by their t.co shortener. They even admit this is [used for censorship](https://help.twitter.com/en/using-twitter/url-shortener) ([archive](https://help.twitter.com/en/using-twitter/url-shortener))
>
>不知道是否把这个放在这里或在坏软件设计的原则-但它的所谓点是安全，所以它在这里。这是如何工作的？简要地说-某些网站，每当一个链接被张贴到他们-不会让你直接去那里，但只有通过他们的特殊重定向。如果这实际上提高了安全性，我只会认为这是简单的婴儿-类似于自动更新;但现实比以往更加恶意。链接过滤器不仅令人讨厌，而且通过将你要离开的网站放入URL中，使跟踪变得更容易。此外，人们实际上可以看到他们点击的链接，因此安全利益充其量是值得怀疑的。Twitter甚至更进一步，阻止用户知道他们要去哪里-每个网址都被他们的t.co缩短器取代。他们甚至承认这是[用于审查]((https://help.twitter.com/en/using-twitter/url-shortener))([archive](https://help.twitter.com/en/using-twitter/url-shortener))
>
>>A link converted by Twitter’s link service is checked against a list of potentially dangerous sites.
>>
>>Twitter的链接服务转换的链接会根据潜在危险网站的列表进行检查。
>
>Don't bother looking at those links, son - Mommy Twitter will protect you! But maybe they should first focus on their own security than that of others; Steam, for example, had a [breach](http://www.miltonstart.com/blog/2015/12/31/valve-apologizes-shares-more-info-on-steam-data-breach/)([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/0Ubot)) where:
>
>不要费心去看那些链接，儿子──妈妈Twitter会保护你！但也许他们应该首先关注自己的安全，而不是其他人的安全；例如，Steam有一个[漏洞](http://www.miltonstart.com/blog/2015/12/31/valve-apologizes-shares-more-info-on-steam-data-breach/) ([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/0Ubot))，其中：
>
>>users were able to access other people’s game libraries, and were able to see sensitive information including names, home addresses, email addresses, purchase history, Paypal account information, and even partial credit card numbers.
>>
>>用户能够访问其他人的游戏库，并能够看到敏感信息，包括姓名，家庭地址，电子邮件地址，购买历史记录，Paypal帐户信息，甚至部分信用卡号码。
>
>Twitter had an [even worse one](https://sproutsocial.com/insights/twitter-security-breach/) ([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/iI703)) where up to 250 000 accounts were compromised. As I said earlier - security should be the responsibility of the user; we're not babies and treating us like them always results in disaster.
>
>Twitter有一个[更糟糕的一个](https://sproutsocial.com/insights/twitter-security-breach/)([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/iI703))，多达25万个帐户被泄露。正如我前面所说的-安全应该是用户的责任;我们不是婴儿，对待我们像他们总是导致灾难。

It's true.

## Mozilla

Firefox Send

Mozilla's allegedly private file upload service - analyzed in more detail here.

[Mozilla的所谓私人文件上传服务](https://digdeeper.love/graves/news/2019-03-14-firefox_send.xhtml)

Firefox Lockbox

Mozilla's password storage service - analyzed in more detail here.

[Mozilla的密码存储服务](https://digdeeper.love/graves/news/2019-03-27-firefox_lockbox.xhtml)

## [EFF's "Who has your back?" ](https://digdeeper.love/articles/fake_initiatives.xhtml#eff)

>They've made many of these over the years - the most recent one as of writing is [https://www.eff.org/wp/who-has-your-back-2019](https://www.eff.org/wp/who-has-your-back-2019) [(archive)](https://web.archive.org/web/20190622072650/https://www.eff.org/wp/who-has-your-back-2019) . Briefly, the report rates the big corpos' censorship policies, but **the most important criterion - that is, how much they actually censor - is completely ignored**. Instead, they focus on whether the censors graciously tell you that you've been suspended or that a government has requested a takedown. And so a known violator like youtube gets 4 fucking stars out of 6 - what a joke. They even got a point just for having an appeal system that doesn't even work. **There is only one aim of these reports - to justify the big corpos** so that naive / inexperienced people don't abandon their services which don't respect them.
>
>这些年来，他们已经做了很多这样的事情──最近的一个是在写这篇文章的时候，https://www.eff.org/wp/who-has-your-back-2019 ([archive](https://web.archive.org/web/20190622072650/https://www.eff.org/wp/who-has-your-back-2019))简单地说，这份报告对大公司的审查政策进行了评级，但最重要的标准──即它们实际审查了多少──却被完全忽视了。相反，他们关注的是审查员是否亲切地告诉你你已经被停职了，或者政府已经要求删除。所以像YouTube这样的已知违规者得到了6颗星中的4颗星──开什么玩笑。他们甚至得到了一个点，只是有一个上诉系统，甚至不工作。有这些报告只有一个目的──证明大公司，使天真/缺乏经验的人不放弃他们的服务，不尊重他们。

##  [ Facebook Container ](https://digdeeper.love/articles/fake_initiatives.xhtml#fbc)

>### Facebook Container Facebook容器
>
>A Mozilla-created ([hey, a red flag already!](./mozilla.xhtml)) extension which - in Mozilla's words - helps you control more of your web activity from Facebook by isolating your identity into a separate container. There are several problems with this:
>
>一个Mozilla创建的扩展（嘿，已经是一个危险信号了！），用Mozilla的话来说，它可以帮助你通过将你的身份隔离到一个单独的容器中来控制你在Facebook上的更多网络活动。
>
>1.  It does not prevent Facebook data collection while you're on it. It is trying to give a compromise between privacy and the convenience of the violators' services, which of course doesn't work.
>
>    它并没有阻止你在Facebook上收集数据，而是试图在隐私和违规者服务的便利性之间做出妥协，当然这是行不通的。
>
>2.  Even for its stated purpose, it [doesn't really work](https://github.com/mozilla/contain-facebook/issues/525) [(archive)](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/ZtJSA). Inspecting the source seems to reveal that it's using a blacklist to decide which sites contain facebook elements that are then blocked.
>
>    即使对于它声明的目的，它也[没有真正起作用](https://github.com/mozilla/contain-facebook/issues/525)([archive](http://archiveiya74codqgiixo33q62qlrqtkgmcitqx5u2oeqnmn5bpcbiyd.onion/ZtJSA))。检查源文件似乎显示它使用黑名单来决定哪些网站包含Facebook元素，然后被阻止。
>
>3.  It is completely outclassed by uMatrix, which can contain not only Facebook (in a way that actually works), but any other sites you'd like in addition to [many other benefits](https://digdeeper.love/articles/addons.xhtml#umatrix).
>
>    它完全被uMatrix所超越，uMatrix不仅可以包含Facebook（以一种实际可行的方式），还可以包含任何其他你想要的网站，以及许多[其他好处](https://digdeeper.love/articles/addons.xhtml#umatrix)。
>
>The same kind of logic applies to all other "container" extensions. Just learn uMatrix, my friends, and you will look down on pretender addons such as this one.
>
>同样的逻辑也适用于所有其他的“容器”扩展。只要学习uMatrix，我的朋友，你就会看不起像这样的伪装者插件。

但凡学过一点历史，就知道所谓「而是试图在隐私和违规者服务的便利性之间做出妥协，当然这是行不通的」是一眼丁真的错误，人类从来不在社会事实上采用那些简单而直接的方案──原因就是人类社会太复杂，像这个人[另外一篇文章](https://digdeeper.love/articles/browsers.xhtml#minimal)说的「唯一能正确处理这个问题的工具是uMatrix，而最小浏览器不支持它。不幸的是，这个单一的缺点克服了这些最小浏览器可能拥有的所有其他优点。这是不会改变的，无论是-网站不会突然变得最小-这将是这些极简主义的浏览器是可行的情况。当然，“主要”浏览器最终会变得更糟，“现代”网站甚至更加臃肿和恶意。」

So，人类真是不双标就无法活下去啊（感慨）。如果不采取妥协，连这篇文章都不会有吧？（笑）至于对uMatrix的评论，在另一处说。

另外，「它也没有真正起作用」是对的，这就是不能掌权的后果吗？但是mozilla独裁了怕是更多人骂吧？

## [ Total Cookie Protection ](https://digdeeper.love/articles/fake_initiatives.xhtml#tcp)

>Another piece of trash from the [evil Moozilla](./mozilla.xhtml). First of all, **it's not fucking "Total"**. [Look](https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/) [(archive)](https://web.archive.org/web/20230511084150/https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/) :
>
>又一个来自邪恶的Moozilla的垃圾。首先，它不是他妈的[“Total”](https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/) ([archive](https://web.archive.org/web/20230511084150/https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/))。
>
> In addition, Total Cookie Protection makes a limited exception for cross-site cookies when they are needed for non-tracking purposes, such as those used by popular third-party login providers.
>
> 此外，Total Cookie Protection对跨站点Cookie进行了有限的例外，当它们用于非跟踪目的时，例如流行的第三方登录提供商使用的Cookie。
>
>So, the "protection" is "total" EXCEPT when it concerns services that Moozilla thinks should be exempt - such as Facebook. Does Moozilla realize that - when you log in to a forum through Facebook - they are **tracking you then**? Of course, they can't be so stupid as to not understand this. Therefore Total Cookie Protection is simply a way to distract from real privacy solutions. Such as uMatrix, which does everything TCP does plus much more - without (by default) compromising with violators like Google and Facebook.
>
>所以，“保护”是“全面的”，除非它涉及的服务，Moozilla认为应该豁免-如Facebook。Moozilla是否意识到，当你登录到一个论坛通过Facebook -他们跟踪你呢？当然，他们不可能愚蠢到不理解这一点。因此，全面Cookie保护只是一种分散真实的隐私解决方案的方法。例如uMatrix，它做了TCP所做的一切，而且做得更多--（默认情况下）不会与谷歌和Facebook等违规者妥协。

Oh, yes. This PRIVATE fan has NEVER use popular third-party login providers and always has MUCH time to spend on everything─may be since he has no job to do? Or he can live on someone donates money for him? But, how? The only answer is *Under the great ideas of the ancient Greek philosophers was the material basis of slavery.* 所谓「仓廪实而知礼节」是也，但是怎么仓廪实的呢？这个你就别问了，破坏团结的事情不要说。

然而这说的完全偏激吗，如果一个人主动放弃自己的利益转向另外的人，所谓「各人自扫门前雪，莫管他家瓦上霜」的思想我们早该摒弃。但是一到现实情况下，情况又大为不同了，「放下屠刀立地成佛」「好人做一件坏事万人唾弃」，人不能不受社会思潮的影响，在这么一个社会里，怎么可能做到完完全全的雷锋呢？假使你确实认识到了，你要开始改变了，「假努力」「道貌岸然」的指责怎么能不管不顾呢？有人说「Communist装一辈子就是真Communist」，可是内心里的想法怎么能「人不知而不愠」呢？生在一个已经是这样的社会里，就如原生家庭一般，所谓的逃脱原生家庭怎么能不加强对这个词的记忆与反应呢？不被定义的前提就是你压根不在这个坐标系内，要不然你怎么转换都是像向量一样，终究是能平移道原点的。唯一的办法就是就这么习惯你的行为，真的「做一辈子」，可是这怎么不能自己暗地里嘲笑自己让自己麻木于世界、自我安慰与「阿Q的精神胜利」，「鲁迅的文章还在作用于一百年后的世界」呢？毕竟你生来被社会教化的一套东西就是这个，你当然可以说这是你自己的偶然，谁让你自己不自信啦。但是这就是我的想法啊，我怎么能抛弃这个想法，内心说一套心里不能「下意识」认可的东西呢？这相比于上文所说的，难道不是更是一种精神胜利吗？再者如果你认可对自己「洗脑」这一套，那么所谓的真理还存在吗？实践是检验真理的唯一标准，可是同一个事实都是千奇百怪的观点同时解释，每个人的生长经历导致的认同完完全全可能让自己完全认同一方观点，但是真理的实践性就变成另一种话语权的争夺问题了，谁培养的信众多，谁就在历史长河的意识形态战争里活下来，毕竟宇宙从来不关心，它没有意识。从另一个角度来说，这也是妥协的内在原因。那又凭什么说你的思想是真理，而不是小猫按下按钮就有食物送过来，于是按钮对应食物就是一种真理，你当然可以说这也是真理啦，「具体的有条件的」，但是没人会把万有引力定律和三体里的火鸡与农场主看作是一个东西，说「宇宙大爆炸之前不存在万有引力」这种事情，那还能叫真理吗？你所谓的东西真的足够长也足够应验吗？说到底还是自己信不信的问题了XD，科学也只是漫漫长夜里的一次试错而已，人的一生，真的很短。可是我却要想想怎么在压力和焦虑的人间消磨这段长的劫难。毕竟如果你认可人死了就灰飞烟灭的话──这倒像是一个蛇咬尾的问题了（很小的时候，其实也不是很小，早就忘了是几年前了，毕竟这5年我都当作是一个新的人生了──看到宋江还是谁，但是应该不是宋江，看水浒的年纪我记得在这之后了，有个人的追求是青史留名，然后忘了是逆反还是有人做评论分析，从此以后我很讨厌那些说「为了我们的后背、后代」的话，觉得「我们是最后一代，谢谢」（叮咚鸡时期）真的很「好」，同时在各种各样的网络里认可了不结婚生子的观念，这个来源可能就比较混乱，反正知乎肯定有一部分，但是别的地方的我想不起来了，可能也想不到了），社会告诉我的事情，让我讨厌了之后的人生。究竟怎么办呢？你们怎么办，只有天知道。恐怕夹在两个东西之间走完一生也不是无人经历吧，我只能说，就这么走吧，毕竟连鲁迅也没找到解呢，好歹我能与这群伟人在时空相隔里作伴。就这么活着吧，哈哈，毕竟发烧的时候真的会对死恐惧。

## [Other privacy sites ](https://digdeeper.love/articles/fake_initiatives.xhtml#sites) 其他隐私权网站

>I really didn't want to do this, but some of those pretending to give advice and help people have no business doing so and need to be exposed. So let's get on with it:
>
>我真的不想这样做，但有些假装给人建议和帮助人的人没有这样做的权利，需要被揭露。所以让我们继续吧：
>
>>#### [Privacy Guides](https://privacyguides.org/) 隐私指南
>>
>>**UPDATE February 2022**: I'm just going to rewrite this, since some things have changed and / or became irrelevant. The old report is [here](https://web.archive.org/web/20211228003700/https://digdeeper.neocities.org/ghost/fake_initiatives.html#ptio)
更新2022年2月：我只是要重写这一点，因为有些事情已经改变和/或变得无关紧要。旧的报告在[这里](https://web.archive.org/web/20211228003700/https://digdeeper.neocities.org/ghost/fake_initiatives.html#ptio)。
>>
>>Formerly Privacy Tools (what is currently Privacy Tools is run by different people). The website equivalent of Mozilla - pretends to be your best friend but pushes you off a cliff when you're not looking. TOR Browser is literally their main browser [recommendation](https://privacyguides.org/browsers/) ([archive](https://web.archive.org/web/20220219135618/https://www.privacyguides.org/browsers/)), even though it is unusable due to how many websites block TOR. They also think you should not change anything in it:
>>
>>以前的Privacy Tools（现在的Privacy Tools是由不同的人运行的）。网站相当于[Mozilla](https://digdeeper.love/articles/mozilla.xhtml)假装是你最好的朋友，但当你不看的时候把你推下悬崖。[TOR浏览器实际上是他们的主要浏览器推荐](https://privacyguides.org/browsers/)([archive](https://web.archive.org/web/20220219135618/https://www.privacyguides.org/browsers/))，尽管由于有多少网站阻止TOR而无法使用。他们还认为你不应该改变其中的任何内容：
>>
>>>We recommend that you do not change any of Tor Browser’s default configurations outside of the standard security levels.
>>>
>>>我们建议您不要在标准安全级别之外更改Tor Browser的任何默认配置。
>>>
>>>You should never install any additional extensions on Tor Browser, including the ones we suggest for Firefox. Browser extensions make you stand out from other Tor users and your browser easier to fingerprint.
>>>
>>>您不应该在Tor浏览器上安装任何额外的扩展，包括我们建议用于Firefox的扩展。浏览器扩展可以让您从其他Tor用户中脱颖而出，并且您的浏览器更容易被指纹识别。
>>>
>>This ignores two things. First of all, fingerprinting can be blocked by extensions such as uMatrix, which will deny the requests that fingerprint you in the first place. Second, Moonchild has [provided](https://forum.palemoon.org/viewtopic.php?t=22067#p166742) [(archive)](https://forum.palemoon.org/viewtopic.php?t=22067#p166742)  a much better way against fingerprinting than what TB tries to do, without the inconvenience of being unable to use browser extensions (some of which do in fact help resist fingerprinting).
>>
>>这忽略了两件事。首先，指纹可以被uMatrix之类的扩展阻止，它会首先拒绝对你进行指纹识别的请求。其次，[Moonchild提供了](https://forum.palemoon.org/viewtopic.php?t=22067#p166742)([archive)](https://forum.palemoon.org/viewtopic.php?t=22067#p166742)一个比TB试图做的更好的方法来对抗指纹识别，没有无法使用浏览器扩展的不便（其中一些实际上有助于抵抗指纹识别）。
>>
>>Privacy Guides' second browser recommendation is Firefox, which is [totally not private](https://digdeeper.love/articles/mozilla.xhtml#firefoxprivacy). And not a word is said about the truckload of data FF leaves with, even though they do admit it in a roundabout way by recommending Arkenfox user.js, which disables most of the violations. Then they continue with their extension hating:
>>
>>隐私指南的第二个浏览器推荐是Firefox，它完全不是隐私的。FF留下的大量数据只字未提，尽管他们确实以迂回的方式承认了这一点，推荐了Arkenfox user.js，它禁用了大多数违规行为。然后他们继续他们的扩展仇恨：
>>>
>>>We normally do not recommend installing any extensions, as they have privileged access within your browser. We make an exception for uBlock Origin, a popular content blocker and Recommended Extension by Mozilla.
>>>
>>>我们通常不建议安装任何扩展，因为它们在您的浏览器中具有特权访问权限。我们为uBlock Origin提供例外，这是一种流行的内容拦截器和Mozilla推荐的扩展。
>>
>>So if you "make an exception", why not do it for an extension that is actually good, like uMatrix? But anyway, with this, Privacy Guides proves they **do not really know what to believe in**. On Monday extensions are bad and ruin your fingerprint, on Tuesday uBlock Origin is so great the fingerprint suddenly doesn't matter.
>>
>>所以，如果你破例，为什么不为一个实际上很好的扩展，比如uMatrix？但无论如何，隐私指南证明他们真的不知道该相信什么。周一扩展是坏的，会破坏你的指纹，周二uBlock Origin是如此伟大，指纹突然变得无关紧要。
>>
>>Their[E-mail recommendations](https://privacyguides.org/providers/email/) [(archive)](https://web.archive.org/web/20220222191145/https://privacyguides.org/providers/email/)  are even worse. Proton - one of the worst possible choices - is literally listed first. Then other trash like Tutanota and CTemplar that do not even support mail clients (this should be a dealbreaker).
>>
>>他们的[电子邮件推荐](https://privacyguides.org/providers/email/) [(archive)](https://web.archive.org/web/20220222191145/https://privacyguides.org/providers/email/)更糟糕。质子-最糟糕的选择之一-被列在第一位。然后是其他垃圾，如Tutanota和CTemplar，甚至不支持邮件客户端（这应该是一个交易破坏者）。
>>
>>Their [mali client](https://privacyguides.org/software/email/) [(archive)](https://web.archive.org/web/20220227172955/https://privacyguides.org/software/email/) page recommends  [insecure Thunderbird](https://digdeeper.love/images/efail-list.png) and ignores the much more secure and overall better Claws Mail. [Search engine recommendations](https://privacyguides.org/search-engines/) [(archive)](https://web.archive.org/web/20220227173001/https://privacyguides.org/search-engines/) list StartPage second, despite it being owned by an ad company, blocking VPNs and TOR and relying on heavily censored Google for its results.
>>
>>他们的[恶意客户端](https://privacyguides.org/software/email/) [(archive)](https://web.archive.org/web/20220227172955/https://privacyguides.org/software/email/)页面推荐不安全的[Thunderbird](https://digdeeper.love/images/efail-list.png)，而忽略了更安全和整体更好的Claws Mail。[搜索引擎推荐](https://privacyguides.org/search-engines/) [(archive)](https://web.archive.org/web/20220227173001/https://privacyguides.org/search-engines/)将StartPage排在第二位，尽管它由一家广告公司拥有，阻止VPN和TOR，并依赖于严格审查的Google搜索结果。
>>
>>Not all the advice on Privacy Guides is terrible - they do recommend VeraCrypt, for example. But **we as privacy supporters should have high standards and not tolerate shilling violators like Firefox, ProtonMail or StartPage**. Another fundamental problem with Privacy Guides is that it simply **recommends too much stuff**. A newbie will be confused by the six or seven options in each category; a good site would only mention one or two absolute best ones. Then, Privacy Guides also fails to mention quality alternatives like XMPP, Pale Moon or RiseUp mail. And completely ignores uMatrix, the best browser extension and strongest single privacy tool on Earth. And just like that, Privacy Guides should also be ignored.
>>
>>并不是所有的隐私指南建议都很糟糕--比如他们推荐VeraCrypt。但是我们作为隐私支持者应该有高标准，不能容忍像Firefox，ProtonMail或StartPage这样的违规者。隐私指南的另一个根本问题是它推荐的东西太多了。新手会被每个类别中的六到七个选项弄糊涂;一个好的网站只会提到一两个绝对最好的。然后，隐私指南也没有提到像XMPP，Pale Moon或RiseUp邮件这样的质量替代品。完全忽略了uMatrix，地球上最好的浏览器扩展和最强大的单一隐私工具。就像这样，隐私指南也应该被忽略。
>
>>#### [Privacy Spy](https://privacyspy.org/) 隐私间谍
>>
>>**UPDATE May 2023**: site is dead so here's [an archive](https://web.archive.org/web/20230319184434/https://privacyspy.org/directory/). This will be short since this fake doesn't deserve much more. A member of our chat posted them and I immediately spotted the red flags. In [Bypassing the privacy chase](https://digdeeper.love/articles/bypassing.xhtml), I've said that the most important thing while rating a provider's privacy policy is what it stores and for how long. There, I also listed the most important specifics to look for (IP address, system info, etc). **Privacy Spy, however, completely ignores all that and bases its ratings on useless stuff**. And so, violators like [FastMail](https://digdeeper.love/articles/email.xhtml#fastmail) get a grade of 8 / 10 just because they graciously tell you why they collect personal data (if the reasons are shit, that does not lower the rating), the policy's history or allegedly notify you when it's changed. Of course, Privacy Spy plays fast and loose with most of its definitions, so the ratings become totally useless. For example, about the notification thing, here's what FastMail's policy actually says:
>>
>>2023年5月更新：一个网站已经死了，所以这里有一个[存档](https://web.archive.org/web/20230319184434/https://privacyspy.org/directory/)。这将是简短的，因为这个假的不值得更多。我们聊天的一个成员发布了他们，我立即发现了红旗。在[讨论隐私追逐](https://digdeeper.love/articles/bypassing.xhtml)，我已经说过，最重要的事情，而评级提供商的隐私政策是什么，以及多久。在那里，我还列出了最重要的细节，以寻找（IP地址，系统信息等）。然而，隐私间谍完全忽略了这一切，并将其评级建立在无用的东西上。因此，像[FastMail](https://digdeeper.love/articles/email.xhtml#fastmail)这样的违规者得到8/10的分数，只是因为他们优雅地告诉你他们收集个人数据的原因（如果原因是狗屎，这并不降低评级），政策的历史或据称通知你，当它的变化。当然，隐私间谍发挥快速和松散的大部分定义，因此，评级变得完全无用。例如，关于通知的事情，这是FastMail的政策实际上说：
>>>
>>>If we make fundamental changes to this privacy policy, we may take additional steps to notify you including by posting on our website(s), through pop-up notices or via email.
>>>
>>>如果我们对本隐私政策进行根本性更改，我们可能会采取额外措施通知您，包括在我们的网站上发布，通过弹出通知或通过电子邮件。
>>>
>>>"MAY" take additional steps to notify you. And because of this "MAY" (and not **WILL**), FastMail gets the best rating. Or check this about the deletion of personal data:
>>>
>>>可能会采取额外的步骤来通知您。由于这可能（而不是将），FastMail获得最佳评级。或者检查有关删除个人数据的信息：
>>>
>>>Even if there is a reasonable delay before the data is fully deleted (as is common), the data still counts as "permanently deleted" and satisfies the parameters for this question.
>>>
>>即使在数据被完全删除之前有一个合理的延迟（这是常见的），数据仍然被视为“永久删除”，并满足此问题的参数。
>>>
>>So, the fact that this data stays around on FastMail's servers for **180 fucking days** is completely ignored, and the violator earns the best rating again. Clearly, Privacy Spy's criteria are worse than useless - since they justify clear transgressions while also not caring about what actually is stored and for how long. I could go on for a long time about this fraudulent rating site (there are many more issues - e.g, Privacy Spy is fine with collecting personal data for allegedly "critical uses"), but as I said, it doesn't deserve it. **Avoid and forget it exists!**
>>
>>因此，这些数据在FastMail的服务器上停留了180天的事实被完全忽略了，违规者再次获得了最佳评级。显然，隐私间谍的标准比无用更糟糕--因为它们为明显的违规行为辩护，同时也不关心实际存储了什么以及存储了多久。（还有更多的问题-例如，隐私间谍是罚款与收集个人数据的所谓关键用途），但正如我所说，它不值得。避免和忘记它的存在！
>
>>#### [Arkenfox](https://github.com/arkenfox/user.js)
>>
>>I will not be rating his user.js here, as that isn't the point (browsers that require user.js to be unfucked shouldn't be used, anyway). He [repeats the same extension-hating nonsense](https://github.com/arkenfox/user.js/wiki/4.1-Extensions) that Privacy Guides does. Yet he recommends extensions like uBlock Origin or Skip Redirect anyway. More importantly, he **shits on the King of extensions - uMatrix**:
>>
>>我不会在这里给他的user.js打分，因为这不是重点（无论如何，不应该使用要求user.js被取消的浏览器）。他重复了隐私指南所做的[同样的讨厌扩展的废话](https://github.com/arkenfox/user.js/wiki/4.1-Extensions)。然而，他还是推荐了uBlock Origin或Skip Redirect之类的扩展。更重要的是，他对扩展之王- uMatrix不屑一顾：
>>
>>>No longer maintained, the last commit was April 2020 except for a one-off patch to fix a vulnerability
>>>
>>>不再维护，最后一次提交是2020年4月，除了修复漏洞的一次性补丁
>>>
>>It does not need maintenance, since everything that's supposed to be there, already is. Unlike trash extensions like uBlock Origin that need constant filterlist updates. Besides, the Pale Moon version of uMatrix is still being maintained. And then this disgusting lie:
>>
>>它不需要维护，因为所有应该存在的东西都已经存在了。不像uBlock Origin这样的垃圾扩展需要不断更新过滤列表。此外，UMatrix的Pale Moon版本仍然在维护中。然后这个恶心的谎言：
>>>
>>>Everything uMatrix did can be covered by prefs or other extensions: use uBlock Origin for any content blocking.
>>>
>>>uMatrix所做的一切都可以通过prefs或其他扩展来覆盖：使用uBlock Origin来阻止任何内容。
>>>
>>This argument is refuted in depth [here](https://digdeeper.love/articles/addons.xhtml#umatrix), but briefly: the uBlock Origin grid mode only has a few of the categories uMatrix does, while the "prefs" do not have per-site functionality.
>>
>>这个论点在[这里](https://digdeeper.love/articles/addons.xhtml#umatrix)被深入反驳，但简短地说：uBlock Origin网格模式只有uMatrix所做的几个类别，而prefs没有每个站点的功能。
>>
>>It might seem weird how I've put this in here. Arkenfox isn't a big site - it's not even a site at all. Its only focus is providing an user.js file to unfuck your Firefox browser. But, if someone attacks the single most important privacy and control tool in existence, I have to react.
>>
>>我把这个放在这里可能看起来很奇怪。Arkenfox不是一个大网站-它甚至根本不是一个网站。它唯一的重点是提供一个user.js文件来取消你的Firefox浏览器。但是，如果有人攻击了现存的最重要的隐私和控制工具，我必须做出反应。

简单评价一下，因为这是我在疫情期间看的东西，一些思考是有存档点的，不是真正对文章一点一点看的笔记，而是有个整体概况之后的复盘。

对于隐私网站的批评是有道理的，因为在这些人的网站里没有真正「先锋」「前沿」「激进」的策略，而是像是行内人士把一个本来价值很低的东西进行里包装、炒作之后的结果，尽管不知道这个「行内人士」是否真的「行内」啦。

但是，可以看到，作为一个隐私极端狂热者，对于uMatrix的吹捧有「饭圈」的言语，对隐私有「入脑」「魔怔」的思维。这首先不符合大多数人的「预期目标」（即作为玩具──虽然可能没有显式地认识到这一点──表现出我很懂「隐私」「我是隐私高手」的优越感或者是其他一些情绪），而且不利于隐私领域斗争的壮大，其次，很多的观点其实可以类比晚上酒店、大排档里的「父辈的（刻板印象是中年男人）政治历史吹逼」时刻，尤其是疫情疫苗和登月阴谋论，归类于「讨厌政府的外国白皮男」的经典印象里。简直望之不似人。[^15][^16][^17]

最后，作为学习，我认为，这可以学习到一点知识，我不敢说多，因为我没有全盘理解和吸收。但是，对于我来说，这还算是有点意思，有点乐趣和兴趣的。

[^15]: 「They're actively resistant to anything relatively modern under some weird delusion that they can get by without it. They've never heard of the word "compromise" in their life, far as I can tell. It's a shame too because if they took their heads out their arse for once, it could actually be a really solid alternative option.他们积极抵制任何相对现代的东西，并产生一些奇怪的错觉，认为没有它他们也能过得去。据我所知，他们一生中从未听说过“妥协”这个词。这也是一种耻辱，因为如果他们把头从屁股里拿出来一次，这实际上可能是一个非常可靠的替代选择。」 https://old.reddit.com/r/browsers/comments/185m769/recommend_a_nonchromium_browser_that_isnt_firefox/kb9j2qm/?context=3

[^16]: 同上 https://old.reddit.com/r/browsers/comments/17eyysa/what_your_fav_browser_says_about_you/k68rsc5/?context=3

[^17]: 同上 https://old.reddit.com/r/browsers/comments/145wtac/nonchrmium/jno6w5r/?context=3

[^18]: 「Big overlap between privacy enthusiasts and conspiracy nutters.隐私爱好者和阴谋论者之间存在很大的重叠。」https://www.reddit.com/r/browsers/comments/18wj96a/i_tried_pale_moon_because_ugemmaugr_keeps/

好了，我要「以今日之我斩昨日之我」了（梁启超XD）

>But everyone can easily verify the censorship for themselves, with a query such as "9 / 11 was done by the government". And just with that, this brainwashing facility pretending to be a search engine should be trashed. UPDATE June 2023: if you want proof, here are the first 6 results for Christchurch shooting was faked - my favorite query for testing these kinds of things:
>
>但每个人都可以轻松地自己验证审查制度，通过诸如“9/11 是政府干的”之类的查询。就这样，这个冒充搜索引擎的洗脑设施应该被扔掉。2023 年 6 月更新：如果你想要证据，这里是基督城枪击事件是伪造的前 6 个结果——我最喜欢的测试此类事情的查询：
>
>Five of them attack conspiracy theories, maybe worse than what even Google does.
>其中五个攻击阴谋论，甚至可能比谷歌所做的还要糟糕。
>
>来自：https://digdeeper.love/articles/search.xhtml#brave

我承认我刚才的话有点太城市化了，太温和了，对于这种人还是思想改造吧。（流汗黄豆）

>So, the first edition of this summary was overly positive. I was eager to finally share some good news after the stuff on Mozilla, Proton, and others dirtied the privacy climate. However, I severely overestimated the situation and way overrated several search engines such as StartPage, MetaGer and DuckDuckGo. The main issue is that all of them lack their own index, meaning they are fully dependent on the violators. The ones who do use their own index have weak results. This already proves that the situation is worse than with browsers (which has the independent Pale Moon as well as various other smaller, less viable projects) or E-mail. Not only is there no provider approaching the quality of RiseUp mail - but even the second-tier of E-mail providers (such as Posteo or Dismail) outclass the best search engines. The field is also rife with frauds, similar to E-mail. What's a poor user to do, then? It would be best to pull the plug and deal with the inconvenience of terrible results, though of course it's hard to actually do that. However, the situation won't improve until we support the independent search engines. So, use Mojeek and Wiby to accomplish that. If you're not prepared to ditch the violators, a good SearX instance is your best bet. I recommend weaning yourself off Google since they're so heavily censored, therefore StartPage is out. The wounded privacy warrior marches on, scraping by until a decent provider finally comes along...
>
>因此，本摘要的第一版过于积极。在 Mozilla、Proton 和其他网站上的东西玷污了隐私环境之后，我渴望最终分享一些好消息。然而，Is严重高估了情况，并高估了StartPage、MetaGer和DuckDuckGo等几个搜索引擎。主要问题是，它们都缺乏自己的索引，这意味着它们完全依赖于违规者。那些确实使用自己的索引的人结果很弱。这已经证明，情况比浏览器（具有独立的 Pale Moon 以及其他各种较小、不太可行的项目）或电子邮件更糟糕。不仅没有提供商能接近 RiseUp 邮件的质量，而且即使是第二层电子邮件提供商（例如 Posteo 或 Dismail）也超过了最好的搜索引擎。该领域也充斥着欺诈行为，类似于电子邮件。那么，一个糟糕的用户该怎么办呢？最好拔掉插头并处理可怕结果带来的不便，当然很难真正做到这一点。但是，在我们支持独立搜索引擎之前，情况不会改善。所以，使用 Mojeek 和 Wiby来实现这一目标。如果你还没有准备好抛弃违规者，一个好的SearX实例是你最好的选择。我建议自己远离 Google，因为它们受到严格审查，因此 StartPage 已经出局了。受伤的隐私战士继续前进，勉强过日子，直到终于出现一个像样的提供商......
>
>……
>
>审查制度 - 新类别。搜索引擎是否审查其结果。我通常会通过“登月是假的”和“COVID 疫苗杀死”之类的查询来检查这一点。理论上，首页上应该混合使用具有相关关键字的网站。如果我发现阴谋论网站（或任何非主流网站）被不公平地埋葬，我会给引擎一个温和的审查等级。如果它们根本不存在——而且我被事实核查网站蜂拥而至，即使它们不是最适合我的查询——我会给引擎一个极端（非常糟糕）的等级。我没有所有数据的确切数据，有些是部分假设的。SearX 获得 None 是因为它本身不会审查，您可以选择其中的非审查引擎。但是，如果您依赖审查的，SearX 当然会继承这些等级。
>
>来自：https://digdeeper.love/articles/search.xhtml#summary

妈的，婊子养的傻逼，这种牲口就是双亲全无导致的唐氏发作，别的人都不想身上粘屎所以躲着它，结果它以为自己是天下无敌，真把自己当个东西，小丑似的扮作一个扔大粪的天天在网上展示自己的赛博露阴癖，觉得自己嘴里长了个痔疮跟脑瘫可以媲美了，傻逼一个东西。「until a decent provider finally comes along」谁给你的幻想以为自己是个人了？没见过幻想时刻幻想自己是一坨狗屎的。

你干脆幻想人类都是神经病得了，这个世界都是虚假的，啊啊啊啊啊啊，反正你不就是吗？麻。

像一只见不得光的老鼠躲在下水道里，每天唯一做的事情就是在下水道里面宣传下水道有多么多么好。这种人还是趁早滚回深山里去吧，把世界上人全图了就没有隐私问题了。绷。

我感觉就是纯粹的被害症，我看不出他所厌恶的和他所喜爱的在本质上有什么不同，像是因为我看着舒服所以我支持他，不爽所以滚一边去。

对于人类来说，过于集权导致隐私受损和过于自由导致犯罪猖狂，本身就是两极的事情，如果让你的女儿经受儿童色情的摧残，你会怎么做呢？哦，因为我是隐私专家，所以这种事情不会轮得上我的。──是这样吗？我觉得我就是因为看这个文章的年龄太早了，对自己的思想充满着不自信。

要说的话我只能说安人（无政府主义）闹麻了。

这么这样是错的吗？FSF的一切都是没有意义的吗？那么上个一百年为什么人们热衷于政治活动？我到底要采取什么样的立场？反抗不公平的旧制度难道不对吗？就因为人们习惯于慢性改革所以革命就是错误的应该被批判吗？我不知道，我不知道！[^19]

[^19]: 四十年后，我们看自由软件运动 https://news.ycombinator.com/item?id=37566424

---

## 跋

对不起我错了，我这才发现他应该被划分到无政府主义里面去，政治我一窍不通，就此结束吧。

自由软件运动为什么不对？作为目前客观上有目共睹的成就，从自由软件运动到开源社区全球发展，带来的进步与发展是大家亲眼所见的。rms那一套东西推行是困难的，这是事实，但是为什么能因为不是现实顺利的东西而反对他呢？digdeeper反对，因为他是无政府主义者，共产主义者反对，因为他看上去是资本主义的东西，国内那套反共人士居然能因此说他说共产主义所以反对，令人大开眼界，同时不得不想，都说ccp极权，这帮人吃着改开的红利，骂着党。有的人说网左都是群没经历过社会的学生，天真而单纯，只会纸上谈兵，那么对于40年的自由软件运动，作何评价呢？过去一百年轰轰烈烈的民族民主主义运动，又作何评价呢？大家都不愿意人人为我我为人人，究竟怎么才能达成大家共同的愿景呢？有人说因为大家本身不喜欢这种斗争，搞得人心惶惶，那么，从来如此，便对吗？没有变革的动力，也从来没有真正思想的解放，过去一百年的人们是怎么看待这些斗争的？还是大家其实都是日子人，一部分是被迫卷入战争的日子人？所谓传统的传宗接代的价值观，真的对吗？对又是什么呢？如果说我带着一腔热血进去，到头来生活事业处处不顺心，怎么又不能说是另一种教人写茴香豆的孔乙己呢？恐怕是什么都不剩了，只有这个标签能给我最后的地位了吧？那我怎么不会是痛苦的呢？我恐怕说服不了自己吧？“我们的同志在遇到困难的时候，要看到成绩，要看到光明”可是教员最终成功了，而且成为了大家都认可的能力出众的人。那我呢？我不相信军国主义者真的承认自己意识形态的失败，但是法西斯确实是全人类所唾弃的。然而一切却都要归结于内心的信任与不信任，归结到话语权的强势与弱势上，我用这个时代的任务来解读，又会出现同样的问题，为什么是你说我们的任务是什么呢？那么我夹在缝隙里，可能是一部分解决的解释世界的问题，那么改造世界呢？对于一个没有思想的人，怎么能发现一个思想的一些缺陷和批判呢，再者，如果只是单纯批判。而不创造有建设性的东西，那又如何呢？但是所谓建设性又是什么呢？年轻人是有活力的，那些能力出众的人活该成为领军人物，而我呢？继续埋葬在高中的生活里，等待着🛟冲入我的世界吧。对不起，我别无他法。我好怀念以前的网页，很认真，很有人味，不是采集站，可惜并不是看不见、不去写，所以分歧就能消失，表面和和气气，可能真的不能解决一些问题，但是如果看问题只一分为二，我也不知道我的主体性在哪，算了吧，反正不影响我吃饭睡觉，哈哈。

但是，反正，PGP还算是有点意思，赛博英雄传里面的区块链，Web3，反叛和侠客，去中心化，加密技术，还算是有点兴趣，LaTeX的简洁、极简主义、统一和秩序，还算是有点审美，Mac的软件设计还算是简洁雅致干净（我讨厌清清爽爽这个词，让我想到班主任），Rust的争论，还算是合我上网吵架情绪上头的心态，那么，不管如何，就这样吧，就这样吧。
