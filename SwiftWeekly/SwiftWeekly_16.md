## 前言

**本期是 Swift 编辑组自主整理周报的第七期**，每个模块已初步成型。各位读者如果有好的提议，欢迎在文末留言。

Swift 周报在 [GitHub 开源](https://github.com/SwiftCommunityRes/SwiftWeekly "SwiftWeekly")，欢迎提交 issue，投稿或推荐内容。目前计划每两周周一发布，欢迎志同道合的朋友一起加入周报整理。

当你来到双水村以外的大世界，你的人生目标便不单单是一名庄稼人了。**Swift社区**陪你一起成长，一起创造更多可能！👊👊👊

> **周报精选**
>
> 新闻和社区：【挑战上岛】适配实时活动和灵动岛
> 
> 提案：函数反向部署
> 
> Swift 论坛：围绕 Swift 6 lock 展开的讨论
>
> 推荐博文：推荐 500+ 款 App UI 设计
>
> 工具推荐：妙言
> 
> **话题讨论：** 如果您年龄超过 35 岁被裁员，再入职时能接受降薪吗？

## 新闻和社区

### 挑战上岛：适配实时活动和灵动岛

Apple 大中华区设计与开发加速器推出全新挑战活动，邀请开发团队限期完成实时活动和灵动岛适配。

实时活动用于在 iPhone 锁屏以及灵动岛上显示来自 App 的最新信息，帮助用户及时查看当前任务和事件的进展。参与此次活动，您将了解如何设计和开发您的实时活动，以及如何利用灵动岛带来更出色的用户体验。

我们会提供主题设计与开发讲座，您将了解如何设计和开发您的实时活动，以及如何利用灵动岛带来更出色的用户体验。

参与讲座的开发团队可在讲座当天报名参与实时活动和灵动岛适配挑战，通过审核后可获得一对一的咨询与深度辅导。参加挑战，并能够在 2022 年 12 月 20 日前完成适配和上线的团队，将有机会获得更多 App 的推广机会。

名额有限。请在 2022 年 11 月 8 日前报名参加。

要报名参加，您必须是位于大中华区的 Apple Developer Program 成员。

### 用 SwiftUI 实现 App 导航

导航是一个 App 的核心，它可以将用户带往 App 里功能不同的页面当中，因此，清晰而强大的导航架构对 App 而言是非常重要的。通过本次活动，我们将从设计和研发两方面来为您介绍，如何使用 SwiftUI 来实现 App 的导航架构，让用户能快速定位到 App 的各项功能。

名额有限。请在 2022 年 11 月 7 日前报名参加。

要报名参加，您必须是位于大中华区的 Apple Developer Program 成员。

### 使用最新 Beta 版本，做好充足准备

Beta 版iOS 16.2、iPadOS 16.2、 macOS 13.1、Apple tvOS 16.2 和 watchOS 9.2 现已推出。请确认您的 App 在这些版本上工作正常，确保 App 做好准备。要利用最新 SDK 中的改进功能，请务必使用 Xcode 14.1 RC 2 进行构建和测试。

要了解之前 Beta 版本中的已知问题是否已解决或是否有临时应对办法，请查看最新的发布说明。如果您遇到问题或有其他反馈，请告诉我们。我们十分重视您的反馈，并相信您的反馈对我们解决问题、优化功能和更新文档将大有助益。

### Apple Search Ads 推出全新广告投放位置，现已亮相 App Store

![](https://devimages-cdn.apple.com/wwdc-services/articles/images/D69BBA69-3F0C-4470-8190-56498AE2116C/2048.jpeg)

Apple Search Ads 让您能轻松地在 App Store 上推广自己的 App。现在，借助全新的“Today”标签页和产品页广告投放位置，您在 App Store 上提升 App 曝光度的机会大大增加 — 当人们首次登陆、搜索特定内容和浏览要下载的 App 时，都是您推广自己 App 的大好时机。

在中国大陆的 App Store 上暂不可用。

## 提案

### 通过的提案

[SE-0375](https://github.com/apple/swift-evolution/blob/main/proposals/0375-opening-existential-optional.md "SE-0375") **允许非可选非空参数传递给可选类型的参数** 提案已通过。该提案已在[十五期周报](https://mp.weixin.qq.com/s/x-ufc5MauRGfoY571WePFA)正在审查的提案模块做了详细介绍。

[SE-0373](https://github.com/apple/swift-evolution/blob/main/proposals/0373-vars-without-limits-in-result-builders.md "SE-0373") **取消 `result builders` 中对变量的所有限制** 提案已通过。该提案已在[十五期周报](https://mp.weixin.qq.com/s/x-ufc5MauRGfoY571WePFA)正在审查的提案模块做了详细介绍。

### 正在审查的提案

[SE-0377](https://github.com/apple/swift-evolution/blob/main/proposals/0377-parameter-ownership-modifiers.md "SE-0377") **提出了新的 `borrow` 和 `take` 参数修饰符** 正在审查。

本提案提出的 `borrow` 和 `take` 参数修饰符，允许开发人员自主选择函数，用于接收不可变参数的所有权约定。这样可以通过减少调用函数所需的 ARC 来优化性能，并为 `move-only` 类型提供了必要的先决条件，指定函数是否会消耗 `move-only` 值。

[SE-0376](https://github.com/apple/swift-evolution/blob/main/proposals/0376-function-back-deployment.md "SE-0376") **函数反向部署** 提案正在审查。

弹性 Swift 资源库，例如 Apple 平台 SDK 中存在的库，作为动态库分发。这些库的作者使用 `@available` 注释来指示引入声明的操作系统版本。

函数反向部署可以避免下面的缺点：

1. 当原始库可用时，首选使用原始库的 API。
2. 当客户端二进制文件永远不会使用时，API 实现的后备副本不存在。

[SE-0366](https://github.com/apple/swift-evolution/blob/main/proposals/0366-move-function.md "SE-0366") **代码上下文新增敏感关键字 move** 修订后，重新审查。该提案已在[十一期周报](https://mp.weixin.qq.com/s/i5a-jhRRdf36KUNRoMX_8w)正在审查的提案模块做了详细介绍。

## Swift论坛

1) 提议[隔离函数 Value 和 Sendable](https://forums.swift.org/t/pitch-isolated-function-values-and-sendable/61046 "隔离函数 Value 和 Sendable")

2) 提议[Swift Distributed Actors (Cluster)](https://forums.swift.org/t/pitch-swift-distributed-actors-cluster/61061 "Swift 分布式 Actors (集群)")

**提议动机:** 在 Swift 5.7 中，分布式 Actor 被引入为名义类型。 与 Actors 类似，它们可以使用 `distributed actor` 关键字对来声明。 就它们自己而言，它们不能真正做任何事情， 所有分布式的行为比如 actor 的行为实际上都由给定 actor 类型相关联的 ActorSystem 处理。具体来说，一个 actor 必须声明它将与什么类型的 actor 系统一起使用，如下所示：

```Swift
import Distributed
import DistributedCluster
distributed actor Greeter {
    typealias ActorSystem = ClusterSystem
    distributed func hello(name: String) -> String {
        return "Hello \(name)!"
    }
}
```
这样的 Greeter 声明可以在集群分布式 actors 系统中使用此类。 也可以声明一个模块范围的默认分布式 actor 系统类型。有关更多信息，可以参考 [Swift Distributed Actor Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0344-distributed-actor-runtime.md "Swift Distributed Actor Runtime") 和 [Swift Distributed Actor Isolation](https://github.com/apple/swift-evolution/blob/main/proposals/0336-distributed-actor-isolation.md "Swift Distributed Actor Isolation") 这是大多数用户可能使用此功能的方式，如下所示：

```Swift
typealias DefaultDistributedActorSystem = ClusterSystem
```
为了避免在每个分布式 actor 模块中重复声明 ActorSystem 类型别名。这里提出的包提供了 ClusterSystem 的实现。

**解决方案:** DistributedCluster 中包括 ClusterSystem 类型，它是库的核心部分。 创建之后，它会绑定到主机/端口对并开始监听传入连接:

```Swift
@main
struct Main {
    static func main() async throws {
        let system = await ClusterSystem("FirstSystem") { settings in
            settings.endpoint.host = "127.0.0.1"
            settings.endpoint.port = 7337
        }
        
        try await system.terminated
    }
}
```

3）提议[Package Registry Authentication](https://forums.swift.org/t/pitch-package-registry-authentication/61047 "Package Registry Authentication")

在[SE-0292](https://github.com/apple/swift-evolution/blob/main/proposals/0292-package-registry-service.md)（API 规范）中提出的package registry服务可能需要对其部分或全部 API 进行身份验证，以便识别执行操作的用户并相应地授权请求。

**提议动机：** Web 服务中常见的身份验证方法包括基本验证 (authentication), access token 和 OAuth。 SwiftPM 目前仅支持基本验证，这限制了它与包注册服务交互的能力。
建议的解决方案: 建议修改 swift package-registry 指令和 registry 的配置并且加入 token authentication 的支持。 这些更改还应确保将来可以灵活地添加其他验证方法。

4）提议[方便的 AsyncThrowingStream.makeStream 方法](https://forums.swift.org/t/pitch-convenience-async-throwing-stream-makestream-methods/61030 "方便的 AsyncThrowingStream.makeStream 方法")

在[SE-0314](https://github.com/apple/swift-evolution/blob/main/proposals/0314-async-stream.md)中介绍了 AsyncStream 和 AsyncThrowingStream，它们充当标准库提供的 AsyncSequence。

提议动机：在使用 Async[Throwing]Stream 一段时间后，我们发现一个常见的用法是将 continuation 和 Async[Throwing]Stream 传递到不同的地方。这需要将 Async[Throwing]Stream.Continuation excaping 并且出传递给初始化程序的闭包。Escaping continuation 使用起来不方便，因为它需要对隐式 optional value 进行格外的操作。

建议的解决方案：为了填补这个不足，建议在 AsyncStream 和 AsyncThrowingStream 上添加一个新的静态方法 makeStream ，它返回 stream 和 continuation。

5) 讨论[围绕 Swift 6 lock 展开的讨论](https://forums.swift.org/t/what-does-use-async-safe-scoped-locking-instead-even-mean/61029 "围绕 Swift 6 lock 展开的讨论")

6) 讨论[围绕 leetcode 2259 题 Remove Digit From Number to Maximize Result 展开的讨论](https://forums.swift.org/t/remove-digit-from-number-to-maximize-result/61049 "围绕 leetcode 2259 题 Remove Digit From Number to Maximize Result 展开的讨论")

## 推荐博文

[7 个大型 iOS 项目的 Xcode 快捷方式](https://github.com/SwiftCommunityRes/article-ios/blob/main/resource/7个大型iOS项目的Xcode快捷方式.pdf "7 个大型 iOS 项目的 Xcode 快捷方式")

**摘要：** 分享的 7 个 Xcode 快捷方式，非常的实用。希望能对你的项目开发有所帮助。

[SwiftUI 锁屏小组件](https://mp.weixin.qq.com/s/jYbRAJhhdE8H8xeoBnTEaA)

**摘要：** iOS 呼声最高的功能之一是可定制的锁屏。终于，在最新发布的 iOS 16 得以实现。我们可以用可浏览的小组件填充锁屏。

[iOS16 中的 3 种新字体宽度样式](https://mp.weixin.qq.com/s/84TG_7yFxpsXF7cHTbVbFw)

**摘要：** 在 iOS 16 中，Apple 引入了三种新的宽度样式字体到 SF 字体库。1、Compressed，2、Condensed，3、Expend。

[推荐 500+ 款 App UI 设计](https://mp.weixin.qq.com/s/MsFjb49JUtZlGn6XSJghyQ)

**摘要：** 500+ 款 App UI 设计，激发你的设计灵感。

[Swift社区回馈读者](https://mp.weixin.qq.com/s/V1KLRAVK-DEWr7Gneatr1A)

**摘要：** Swift社区回馈读者 -- 送书活动还在进行中，机会不要错过，马上参与吧。

## 工具推荐

**妙言：** 一个简洁好看的开源的 Mac Markdown 编辑器，没有任何多余的功能，使用原生 Swift 开发，轻量性能高，安全纯本地使用，具备语法高亮、黑暗模式、自动格式化、单独编辑、演示模式、图床等功能。

![](https://user-images.githubusercontent.com/8736212/193432093-113a3667-c0b7-4711-9479-5679abed83af.png)

## 话题讨论

**如果您年龄超过 35 岁被裁员，再入职时能接受降薪吗?**

## 关于我们

**Swift社区**是由 Swift 爱好者共同维护的公益组织，我们在国内以微信公众号的运营为主，我们会分享以 **Swift实战**、**SwiftUl**、**Swift基础**为核心的技术内容，也整理收集优秀的学习资料。

欢迎关注公众号:Swift社区，后台点击进群，可以进入我们社区的交流讨论群。希望我们Swift社区是大家在网络空间中的另一份共同的归属。

<img width="500" alt="Swift社区" src="https://user-images.githubusercontent.com/24238160/132703149-34121c6c-fd18-491c-a697-58a0fabf3060.png">

特别感谢 Swift社区 编辑部的每一位编辑，感谢大家的辛苦付出，为 Swift社区 提供优质内容，为 Swift 语言的发展贡献自己的力量。
