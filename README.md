# Hack Like a Pornstar
-- 通过现实生活中的黑客场景掌握黑客攻击的秘密

## 版权声明
版权所有。未经出版商事先书面许可，不得以任何形式或方式（包括影印，录制或其他电子或机械方法）复制，分发或传播本出版物的任何部分，除非有简短的引文，在严格审查和版权法允许的某些其他非商业用途。

## 前言
这不是一本关于信息安全的书。当然，更不是关于IT。这是一本关于黑客攻击的书：具体来说，如何渗透进一家公司的网络，找到他们最重要的数据，并且不触发那些牛逼轰轰的安全设备告警，虽然这些设备花费了公司大量预算。

无论你是一个崇尚道德的黑客，或是一个被过时的书籍和虚假媒体报道而弄到沮丧的攻击爱好者，这本书绝对适合你。

我们将搭建一个虚拟的，但足够真实的目标，并详细介绍攻陷一家企业的主要步骤：制作恶意钓鱼软件，寻找漏洞，拿下域控，攻陷大型机等。

本书中使用的几乎所有工具和自定义脚本我已经做好了归档。 我强烈建议您在属于自己、而且可控的环境中测试这些工具并掌握其功能（以及了解其局限性）。 当然，期望本书能涵盖所有可以想象到的黑客技术是不可能的，尽管我会尽可能提供各种实例，但考虑到这本书的目的，我还是会坚守“初衷”的。

在本书中，我将简要介绍 IPSEC，TOR 和 NTLM 等概念的工作原理和在攻击场景中的含义。 如果您想要深入了解，我强烈建议您按照我在每个项目附近提供的链接，探索每种技术和工具背后阴暗、有趣的概念。

注意：本书中记录的自定义脚本和特殊命令可在以下链接获取：[作者官网](https://github.com/HackLikeAPornstar/)

## 重要免责声明
本书中的例子完全是虚构的。 提供的工具和技术是开源的，允许所有人使用。 渗透测试工程师会在分配的任务中经常使用它们，但攻击者也会。 如果您最近遭受了破坏，并找到了本书中所示的技术或工具，那么这绝不会导致本书的作者入罪，也不会暗示作者与犯罪者之间存在任何联系。

与本书中包含的材料相关的任何行动和/或活动完全由您自己负责。 滥用本书中的信息可能会导致对相关人员提起刑事指控。 如果对任何滥用本书信息的人违反法律规定提起任何刑事指控，作者将不承担任何责任。

本书不会促进黑客攻击，软件破解和/或盗版。 本书中提供的所有信息仅用于教育目的。 它将帮助公司保护其网络免受攻击，并将帮助调查人员评估事件期间收集到的证据。

未经计算机系统所有者的书面许可,开展任何黑客尝试或测试都是非法的。
