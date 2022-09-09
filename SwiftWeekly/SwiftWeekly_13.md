## 前言

**本期是 Swift 编辑组自主整理周报的第四期**，每个模块还在调整磨合期。各位读者如果有好的提议，欢迎在文末留言。

Swift 周报在 [GitHub 开源](https://github.com/SwiftCommunityRes/SwiftWeekly "SwiftWeekly")，欢迎提交 issue，投稿或推荐内容。目前计划每两周周一发布，欢迎志同道合的朋友一起加入周报整理。

昔孔子登泰山而小天下， 今诸君阅**Swift社区**皆足矣。请君浅读，与君共勉！👊👊👊

> **周报精选**
>
> 新闻和社区：iPhone14 Pro 刘海变“灵动岛”
> 
> 提案：大量提案审核结果已发布
> 
> Swift 论坛：论坛内容丰富，欢迎参与讨论
>
> 推荐博文：增加 App 排名的 ASO 小技巧

## 新闻和社区

### iPhone14 Pro 刘海变“灵动岛”

iPhone14 Pro 来了，从外观看两个亮点，第一是新配色 #iPhone14Pro 灭霸紫# 好看吗？第二是刘海变成了药丸，不是感叹号，但是带来了 #iPhone14Pro 灵动岛#，和显示动画合为一体。

本次发布会，iphone14pro 刘海依旧，但刘海减少 30% 变更为“药丸”，并引入灵动岛设计，通过刘海变换多种交互UI。视网膜 XDR2000 尼特峰值，实现息屏显示。使用新的 A16 4nm 芯片，搭载 4800 像素主摄像头，比 iPhone 13 Pro 大了 65%，新增配“灭霸紫”配色。

9月8日凌晨，苹果秋季发布会推出 iPhone14 系列产品，其中最大亮点为 iPhone14pro 系列新增正面设计“灵动岛”。正面摄像头有一个较小的切口，在不同状态下挖孔形态不同，支持第三方应用。iPhone14 系列售价：iPhone14 5999元起，iPhone14plus 6999元起，iPhone14pro 7999元起，iPhone 14pro max 8999元起。9 月 9 日开始预售，9 月 16 日正式发售。

![](https://raw.githubusercontent.com/SwiftCommunityRes/image/main/weekly/iPhone.png)

### 库克：苹果将捐款支持四川地震灾区救援和重建工作

9 月 7 日消息，苹果 CEO 蒂姆库克的认证微博发布消息称：“我们心系所有受地震影响的四川民众和社区。苹果将捐款支持救援和重建工作。”

![](https://raw.githubusercontent.com/SwiftCommunityRes/image/main/weekly/weekly1301.png)

此前，小米、宁德时代、阿里巴巴、网易、字节跳动、联想、辛选集团、比亚迪、拼多多、理想汽车等都宣布向四川地震灾区进行捐赠。

### 苹果为老款 iPhone / iPad / iPod 发布 iOS 12.5.6 更新，修复严重漏洞

IT之家 9 月 1 日消息，苹果今日为老款 iPhone 发布了 iOS 12.5.6（内部版本号：16H71）更新，针对无法更新到 iOS 15 的设备进行了安全更新和错误修复。

这是自 2021 年 9 月以来苹果对 iOS 12 的首次更新，当时苹果修复了一个问题，该问题使恶意制作的 PDF、Web 内容和 App 能够执行代码。最新更新解决了自上次更新以来已在 iOS 15 中修补的漏洞。

IT之家了解到，苹果会针对无法更新到 iOS 12 之后的旧 iPhone、iPad 和 iPod 提供定期更新。这些更新不会提供任何重大的功能更改或 UI 改进，但会针对旧设备可能容易受到的已知攻击提供保护。

苹果安全更新网站声明如下：

一位匿名研究人员提交的 CVE-2022-32893。

更新适用于：iPhone 5s、iPhone 6、iPhone 6 Plus、iPad Air、iPad mini 2、iPad mini 3 和 iPod touch（第 6 代）

影响：恶意制作的 Web 内容可能会执行任意代码。有报告称此问题可能已被积极利用。

描述：已通过改进边界检查解决越界写入问题。(来源： IT之家)

![](https://raw.githubusercontent.com/SwiftCommunityRes/image/main/weekly/weekly1302.png)

### 苹果 iOS 16 更新，天气 App 新功能盘点

IT之家 8 月 31 日消息，苹果在 iOS 16 中对天气应用进行了一些改变，包括新的通知类型，并增加了一些信息，从湿度、温度到能见度全方位为你提供服务。

此外，新版天气 App 中的许多新功能都融入了苹果此前收购的 Dark Sky 内容。

天气应用程序的整体设计没有重大更新，但苹果提供了更多信息。长期以来，天气应用一直都有一些小模块，从而向你显示各种信息，包括 10 天内预报、每日气温、空气质量、降水、紫外线指数、日落 / 日出时间、风、湿度、感官温度、能见度和压力等等，现在你可以点击进入这些模块中的任何一个来获取更多信息，还支持快速切换。

温度部分展示了全天的温度曲线图，包括最高和最低。这应该可以解决 iOS 15 天气应用中存在的一个问题，从而不会再有用户抱怨不清楚气温何时才是每日最低点。此外，这一部分还提供了天气状况的文本概述。在 10 天的天气预报中，你可以点击任何一天查看每日温度范围的图表，还有一个选项可以查看更大的彩色温度地图。

空气质量这块展示了您所在地区当前空气状况的图表，以及当前状况和主要污染物对健康影响的附加信息。此外，你还可以看到更大的空气质量地图，预计国内同样是由“和风天气”提供信息。

新的“降水”类似于之前版本的降水信息，显示了风暴将袭击的位置地图，还可以放大显示 12 小时降雨预报，还有一个界面显示了过去 24 小时内的降水总量详情，以及在什么时间下了多少雨、雨夹雪或雪。

感官温度提供了第二个温度图表，结合温度、湿度，风等一些其他因素，你可以更好地了解周围环境温度变化。

紫外线指数显示当前的紫外线等级和白天的最高紫外线水平。同时，它还会提供一段介绍，例如建议防晒等级。

“日落和日出”可以让你知道日出或日落的时间，同时它还包括每月日出和日落的平均值和总日光的读数。

“风”主要是提供每天的风速摘要，以及全天的风速、风向图表。

湿度部分显示了全天湿度的图表，分为六个小时的增量。它还提供平均湿度和露点等信息。

“能见度”可提供全天的能见度范围，并提供每日摘要。

“压强”显示了当前的压强、全天压强，以及压强是上升还是下降的读数。

“极端天气警报”和之前一样，会显示重大的暴雨、洪水、飓风、热浪、龙卷风等其他灾害警告，预计国内还是和风天气提供信息。

“天气锁屏”虽然不是天气应用程序的一部分，但在 iOS 16 中有一个专门的天气锁屏。如果是晴天，你会看到太阳，如果是雨天，你会看到下雨。

还有许多不同的天气小部件，你可以添加到任何锁屏中，还有一个更大的读数与温度，当前条件，高 / 低随着个别空气质量，紫外线指数，和温度选项。

“iPad 天气”，随着 iOS 16/ iPadOS 16 更新，终于有了适用于 iPad 的天气应用，相比 iPhone 版本可以更好地适应 iPad 的大显示屏。

总之，iOS 16 更新了好多新奇的功能哦，小伙伴快去试试吧。(来源： IT之家)

## 提案

### 通过的提案

[SE-0370](https://github.com/apple/swift-evolution/blob/main/proposals/0370-pointer-family-initialization-improvements.md "SE-0370") **改进指针系列初始化和缓冲区** 提案已通过。该提案已在[十二期周报](https://mp.weixin.qq.com/s/IXP8PNT4aoCnyB-V2qMY_Q)正在审查的提案模块做了详细介绍。

[SE-0365](https://github.com/apple/swift-evolution/blob/main/proposals/0365-implicit-self-weak-capture.md "SE-0365") **增加对协议 CustomDebugStringConvertible 到 AnyKeyPath 的一致性** 提案已通过。该提案已在[十二期周报](https://mp.weixin.qq.com/s/IXP8PNT4aoCnyB-V2qMY_Q)正在审查的提案模块做了详细介绍。

[SE-0368](https://github.com/apple/swift-evolution/blob/main/proposals/0368-staticbigint.md "SE-0368") **StaticBigInt** 提案已通过。该提案已在[十一期周报](https://mp.weixin.qq.com/s/i5a-jhRRdf36KUNRoMX_8w)正在审查的提案模块做了详细介绍。

### 拒绝的提案

[SE-0371](https://github.com/apple/swift-evolution/blob/main/proposals/0371-isolated-synchronous-deinit.md "SE-0371") **Isolated synchronous deinit** 被拒绝，重新修订。该提案已在[十二期周报](https://mp.weixin.qq.com/s/IXP8PNT4aoCnyB-V2qMY_Q)正在审查的提案模块做了详细介绍。

[SE-0366](https://github.com/apple/swift-evolution/blob/main/proposals/0366-move-function.md "SE-0366") **代码上下文新增敏感关键字 move** 被拒绝，重新修订。该提案已在[十一期周报](https://mp.weixin.qq.com/s/i5a-jhRRdf36KUNRoMX_8w)正在审查的提案模块做了详细介绍。

### 正在审查的提案

[SE-0372](https://github.com/apple/swift-evolution/blob/main/proposals/0372-document-sorting-as-stable.md "SE-0372") **更新稳定排序文档** 提案正在审查。

Swift 的排序算法在 Swift 5 之前已经更改为稳定排序，但是文档一直没有更新。本提案致力于更新稳定的排序算法文档，方便开发者使用。


## Swift论坛
1) 讨论 [Automatic 类型的一致性](https://forums.swift.org/t/automatic-type-conformance/60111 "Automatic 类型的一致性")

出发点：

```Swift
private func cachedImage(for path: String?) -> AnyPublisher<UIImage?, Never> {
    guard let path = path else {
        return Just(nil)
            .eraseToAnyPublisher()
    }
    if let image = imageCache.object(forKey: NSString(string: path)) {
        return Just(image)
            .eraseToAnyPublisher()
    }
    return image(for: path)
        .handleEvents(receiveOutput: { [weak imageCache] (image) in
            imageCache?.setObject(image, forKey: NSString(string: path))
        })
        .eraseToAnyPublisher()
}
```

```Swift
.eraseToAnyPublisher()
```

被用到了很多次

把它提出来，写一个 Just 的 extension

```Swift
extension Just: TypeConvertable {
    var convertable: AnyPublisher<Output, Never> {
        self.eraseToAnyPublisher()
    }
}
```

于是代码变得简洁了很多

```Swift
private func cachedImage(for path: String?) -> AnyPublisher<UIImage?, Never> {
    guard let path = path else {
        return Just(nil)
    }
    if let image = imageCache.object(forKey: NSString(string: path)) {
        return Just(image)
    }
    return image(for: path)
        .handleEvents(receiveOutput: { [weak imageCache] (image) in
             imageCache?.setObject(image, forKey: NSString(string: path))
        })
}
```

把例子变得通用一些

```Swift
protocol TypeConvertable {
    associatedtype ReturnType
    var convertable: ReturnType { get }
}
```

当定义一个类型转变的时候，编译器应该可以决定对应的类型和相应的转变结果。
在这个例子中返回的类型是由给定类型决定的

2) 讨论 [Xcode14 RC 不能序列化 protocol 类型](https://forums.swift.org/t/xcode-14-rc-cannot-specialize-protocol-type/60171 "Xcode14 RC 不能序列化 protocol 类型")

```
// ❌ Cannot specialize protocol type 'Collection'
extension Collection<MyType> { ... }

// ❌ Cannot specialize protocol type 'Sequence'
func foo(_ x: some Sequence<String>) { ... }
```

可能原因 macOS 12 SDK 仍然使用 Swift5.6，而不是 5.7.
Swift 5.7 支持：

* 自定义 protocol 可以有 associated types。 参考链接：https://github.com/apple/swift-evolution/blob/main/proposals/0358-primary-associated-types-in-stdlib.md
* 在 protocol 里使用 associated type 要注意传入的类型与返回类型

3) [Swift coding style guide](https://forums.swift.org/t/swift-style-guide/60177/5 "Swift coding style guide")

一个很好的 swift style 总集文档：https://google.github.io/swift/#line-wrapping

4) 讨论 [C++ Abstract Class Inheritance and C++-Interop (to Swift Protocols)](https://forums.swift.org/t/c-abstract-class-inheritance-and-c-interop-to-swift-protocols/60170 "C++ Abstract Class Inheritance and C++-Interop (to Swift Protocols)")

5) 提问 [如何处理空的网络返回值](https://forums.swift.org/t/how-to-handle-empty-response-in-responseserializer/60155/1 "如何处理空的网络返回值")

可以参考 Alamofire 的处理方法.
参考链接: https://github.com/Alamofire/Alamofire/blob/master/Source/ResponseSerialization.swift#L925
当网络请求返回是空的时候可以判定为请求失败，同时查看返回代码是不是在 200～299 之间

## 推荐博文

[SwiftUI 锁屏小组件](https://swiftwithmajid.com/2022/08/30/lock-screen-widgets-in-swiftui/ "SwiftUI 锁屏小组件")

**摘要：** 随着 iOS 16 的发布，赶快来适配一下 iOS 16 最为重要的更新之一，锁屏小组件吧！

[Sourcery 的 Swift Package 命令行插件](https://www.polpiella.dev/sourcery-swift-package-command-plugin "Sourcery 的 Swift Package 命令行插件")

**摘要：** 作为 Swift 最流程的代码生成工具，sourcery 能够快速的生成模板代码来帮助开发者节省大量的时间。

[项目中第三方库并不是必须的](https://mp.weixin.qq.com/s/p_MoRthVdlfhqSyxCkDkow)

**摘要：** 作者充分的论述了第三方库在提供便利的同时也带来了相当的风险。为是否选择集成第三方库提供了一套有意义的思路。

[增加 App 排名的 ASO 小技巧](https://blog.nielsmouthaan.nl/aso-tips-and-tricks-to-increase-your-apps-ranking "增加 App 排名的 ASO 小技巧")

**摘要：** 偶尔也可以关注一下技术之外的东西，从另一个方面提升自己的竞争力。

[云音乐 iOS 端网络图片下载优化实践](https://mp.weixin.qq.com/s/R1XLp9hjHDBdYcOI6w8psw "云音乐 iOS 端网络图片下载优化实践")

**摘要：** 本文介绍了网易云音乐在图片下载的优化下实践。从想法到技术方案，再从 `SDWebImage` 源码入手，到最后的再次封装实现，都很值得一看。

## 关于我们

**Swift社区**是由 Swift 爱好者共同维护的公益组织，我们在国内以微信公众号的运营为主，我们会分享以 **Swift实战**、**SwiftUl**、**Swift基础**为核心的技术内容，也整理收集优秀的学习资料。

欢迎关注公众号:Swift社区，后台点击进群，可以进入我们社区的交流讨论群。希望我们Swift社区是大家在网络空间中的另一份共同的归属。

<img width="500" alt="Swift社区" src="https://user-images.githubusercontent.com/24238160/132703149-34121c6c-fd18-491c-a697-58a0fabf3060.png">

特别感谢 Swift社区 编辑部的每一位编辑，感谢大家的辛苦付出，为 Swift社区 提供优质内容，为 Swift 语言的发展贡献自己的力量。
