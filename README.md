# awesome-iOS
本文主要汇集Swift学习相关资源，以方便初学者或中高级开发者学习参考，欢迎大家共同参与维护。

----------
## 目录结构
* [0#入门指南](#welcome)
* [1#开发工具](#dev_tools)
* [2#文档教程](#doc_cources)
* [3#开源项目](#open_projects)
* [4#网站社区](#website)



----------
## <a id="welcome"></a>0#入门指南
苹果为 [Swift](http://www.apple.com/swift/)（[中文介绍](http://www.apple.com/cn/swift/)）开发者提供的[官方文档入口](https://developer.apple.com/swift/)，包括 [概述](https://developer.apple.com/swift/)，[博客](https://developer.apple.com/swift/blog/)（[中文镜像](https://github.com/ipader/SwiftGuide/tree/master/mirror/Swift%20Blog%20-%20Apple%20Developer)）及 [开发资源](https://developer.apple.com/swift/resources/)。其中以下几份文档（Swift 3）为入门级必备（[iBooks 版](https://itunes.apple.com/us/book-series/swift-programming-series/id888896989?mt=11)）：

* [Swift Programming Language](https://developer.apple.com/swift/)（[中文版](http://gg.swiftguide.cn)｜[PDF 版](http://wiki.jikexueyuan.com/download/swift/pdf/) By [SwiftGG翻译组](http://weibo.com/swiftguide)）

* [Start Developing iOS Apps](https://developer.apple.com/swift/resources/) 
* [Using Swift with Cocoa and Objective-C](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/BuildingCocoaApps/index.html)（[中文版](https://github.com/CocoaChina-editors/Welcome-to-Swift/blob/master/UsingSwiftwithCocoaandObjective-C%E4%B8%AD%E6%96%87%E6%89%8B%E5%86%8C.md) By [@CocoaChina](http://weibo.com/cocoachina)）

*苹果同时也维护着相应 Beta 版（Swift 3）文档：[Swift Programming Language](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/Swift_Programming_Language/index.html)，[Start Developing iOS Apps](https://developer.apple.com/library/prerelease/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/index.html)，[Using Swift with Cocoa and Objective-C](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/BuildingCocoaApps/index.html)。*

学习实践的角度，标准库示例代码 [Swift Standard Library.playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) 是很棒的学习伴侣。

如果是Swift开源及跨平台开发，可以关注 [swift.org](https://swift.org/)

----------
## <a id="dev_tools"></a>1#开发工具
### 1. 编程工具
* [Xcode 下载](https://developer.apple.com/swift/resources/)：苹果应用集成开发环境。支持 C/C++, Objective C, Swift 等。不用购买开发者计划，直接下载。
* [Textmate](http://macromates.com/)：Mac OS X 上一个可高度自定义的编辑器，尤其在我想做出一个快速改变但又不想等待 Xcode 加载的时候。该工具目前已经[开源](https://github.com/textmate/textmate)
* [Mou](http://mouapp.com/)：OS X 上一款 Markdown 的编辑器。非常适用于编写自述文件、变更日志以及其他方面的内容。作者：[罗晨](http://chenluois.com/)
* [MacDown](https://macdown.uranusjr.com/): macOS上一款非常好用的开源Markdown编辑器。
* [Markdown Edit](https://stackedit.io/editor) a good online Markdown edit, export PDF perfectly using Chrome
* [Sublime Text ($)](http://www.sublimetext.com/)：Mac OS X 上另一款非常受欢迎的轻量级，可高度自定义的编辑器。
* [RunSwift](http://www.runswiftlang.com/):正在犹豫是否入手苹果电脑开始一段 Swift 编程旅程的同学们，或仅仅为了试验一段简单 Swift 代码又懒得打开 Xcode，可以试试这款 Web 版 Swift 编译环境 RunSwift。
* [InfinitApps - Bezel](http://infinitapps.com/bezel/)：“嫌 Xcode 6 目前提供的 Watch 模拟器不够直观？Bezel 是一个用于视觉预览 WatchKit 所开发程序效果的小工具，前提是你安装了 xScope 软件（Mac端）或 xScopeMirror（iPhone端）。 By [@WatchKit开发](http://weibo.com/twios)”
* [Markdown -> Playground](https://github.com/jas/playground)：该开源项目可将内含有 Swift 代码的 Markdown 自动转换为 Xcode Playgrounds 文件。喜欢用 Markdown 编辑的同学很激动吧。P.S. 这款工具写于 NodeJS，原因作者有交待。
* [iOS/Mac Autolayout Constraints](https://autolayoutconstraints.com)：这个工具不错，很直观，布局时可以省不少工夫。推荐者：[@荧星诉语](http://weibo.com/qq184675420)
* [在线生成 AppStore 审核用截图](https://appscreens.io/yK7cLuBNij)：便捷的生产力工具。免费，易操作，可自定义。
* [IBM Swift Sandbox](https://swiftlang.ng.bluemix.net/#/repl)：IBM的在线Swift网站，需要翻墙。
* [SwiftStub](http://swiftstub.com/)：另外一个Swift在线练习网站。

### 2. 代码管理
* [GitHub](https://github.com/)：声望日盛的资源分享之地。
* [GitHub for Mac](https://desktop.github.com/)：一个设计的非常美观的 git 客户端，不能取代你从命令行获得的所有功能，但使用起来非常简单。
* [GitCafe](https://gitcafe.com/)：GitCafe is a source code hosting service based on version control system Git。国内的代码托管服务，基于 Git，值得一提的是最近也推出了和 GitHub Pages 类似的服务 Gitcafe Pages。因为是在国内，所以相比较 GitHub 有速度优势，在网络环境差的情况下也许可以作为 GitHub 的备用。
* [Bitbucket](https://bitbucket.org/)：国外的代码托管服务，不同于 GitHub 的是，Bitbucket 可以免费建立 private 项目。
* [Git](https://git-scm.com/)：分布式版本控制系统和源码管理系统，其优点是：快和简单易用。对于新手来说，可在此查看免费电子书籍。
* [SourceTree](https://www.sourcetreeapp.com/)：A free Git & Mercurial client for Windows or Mac.免费的Git和Mercurial客户端，当然也可以配合Bitbucket使用。

### 3. Xcode 插件
* [CocoaPods](http://beta.cocoapods.org/)：第三方库的管理利器，允许你简单地把第三方库整合进自己的应用中。对我个人来说，我基本上每个项目都使用 CocoaPods。
* [CocoaPods Xcode Plugin](https://github.com/kattrali/cocoapods-xcode-plugin)：一款 Xcode 插件，允许你直接从 Xcode 管理 CocoaPod 依赖。
* [onevcat/VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode)：快捷注释 Xcode 插件。By [@onevcat](http://weibo.com/onevcat)
* [ColorSense](https://github.com/omz/ColorSense-for-Xcode)：一款显示颜色数值的插件，还可以直接通过系统的ColorPicker来自动生成对应颜色代码
* [Xcode 优秀插件整理](https://github.com/sopig/DeepIniOS):持续保持整理更新的 Xcode 插件整理 By [@ddapps](https://github.com/ddapps)
* [CodeEagle/SwiftCodeSnippets](https://github.com/CodeEagle/SwiftCodeSnippets)：自动下载指定 Xcode Snippet 源的 Xcode Plugin。项目缺省提供 Snippet 代码源 [burczyk/XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets/tree/master/plist) 。
* [realm/SwiftLint](https://github.com/realm/SwiftLint)：Realm 采用 Swift 编写的基于 GitHub's Swift Style Guide 规则的检查工具。除了命令行运行方式，也提供集成 Xcode 的方法。对于新团队，这样的工具可以自动约束大家遵循编程规范。
* [XCode 升级后插件失效的原理与修复办法](http://joeshang.github.io/2015/04/10/fix-xcode-upgrade-plugin-invalid/)：由一条命令引发的分析文章。[@_TongJZ](http://weibo.com/u/2068840121)
* [feinstruktur/CoPilot](https://github.com/feinstruktur/CoPilot)：通过此插件，Xcode 可以协同编程了（采用 WebSocket 通讯）。如此强大的“黑工具”，不爱它能行吗。[演示视频](https://vimeo.com/128713880)
* [Carthage](https://github.com/Carthage/Carthage)：新兴起的去中心化的依赖管理器，目标是用最简单的方式来管理Cocoa第三方框架。优势很明显，但是也有不足，看后面的发展吧。

### 4. 管理工具
* [swiftenv](https://github.com/kylef/swiftenv)：Swift 版本管理器。类似 rvm（Ruby）, nvm（Node.js）。
* [HomeBrew](http://brew.sh/index_zh-cn.html)：OS X 上非常出色的包管理工具。
* [Transmit ($)](http://panic.com/transmit/)：一个Mac OS X 上 FTP 客户端，有着非常漂亮的用户界面和有用的功能。

### 5. 调试工具
* [mattt/fuckingclangwarnings.com](http://fuckingclangwarnings.com/)：警告与语义对照表。以后再也不用为 Xcode 各种警告纠结啦！By [@foogry](http://weibo.com/foogry)

### 6. 设计工具
* [sketch](http://www.sketchapp.com/)：更适合开发应用的矢量设计工具。通过插件还支持与代码协同工作。推荐书籍：[Learn Sketch 3](https://designcode.io/sketch)
* [PaintCode](http://www.paintcodeapp.com/)
:PaintCode是Apple Designer入门APP开发最合适的辅助工具之一，她可以把你绘制的矢量UI自动转化为适用于iOS/OS X的Objective-C代码。



----------

## <a id="doc_cources"></a>2#文档教程

视频教程方面，苹果力荐了斯坦福课程 [Stanford University: Developing iOS 8 Apps with Swift](https://itunes.com/StanfordSwift)（[中文字幕版](http://open.163.com/special/opencourse/ios8.html) By [@网易公开课](http://weibo.com/163open)）

[iOS Developer Library](https://developer.apple.com/library/ios/navigation/) 还为开发者提供了更庞大、系统化的开发文档支持。

* [The Swift Programming Language (Swift 3.0.1)](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/index.html#//apple_ref/doc/uid/TP40014097-CH3-XID_0) online document


以下列举了几份已有第三方中文翻译文档：

* [API Design Guidelines](https://swift.org/documentation/api-design-guidelines/)（[中文版](http://swift.gg/2016/05/18/api-design-guidelines/) By [@SwiftGG翻译组](http://weibo.com/u/5174822990)）
* [App Extension Programming Guide](https://developer.apple.com/library/ios/documentation/General/Conceptual/ExtensibilityPG/index.html)（[中译镜像](https://github.com/ipader/SwiftGuide/tree/master/mirror/App%20Extension%20Programming%20Guide)）
* [iOS Human Interface Guidelines](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/index.html)（[中文版](https://isux.tencent.com/?s=iOS+9+%E4%BA%BA%E6%9C%BA%E7%95%8C%E9%9D%A2%E6%8C%87%E5%8D%97)｜[PDF 版](http://ixdc.org/2016/files/ISUX[%E8%AF%91]iOS9%20human%20Interface%20Guideline.pdf) By [@腾讯ISUX](http://weibo.com/txisux)）
* [HomeKit Developer Guide](https://developer.apple.com/library/ios/documentation/NetworkingInternet/Conceptual/HomeKitDeveloperGuide/Introduction/Introduction.html)（[中文版](http://www.cocoachina.com/ios/20150324/11411.html) By [@CocoaChina](http://weibo.com/cocoachina)）

值得称道的还有：苹果为 [Apple TV Tech Talks](https://developer.apple.com/videos/) 和 [WWDC 2015](https://developer.apple.com/videos/wwdc2015/) 的视频添加简体中文字幕，从而方便中国开发者观看来自官方的权威技术分享。



----------
## <a id="open_projects"></a>3#开源项目
* [SwiftEducation](https://github.com/SwiftEducation)：“这是建立在 GitHub 上的一个 Swift 学习资料汇集，包括了有关幻灯和多个练手的应用程序源码。By @极客头条”。的确有不少基础实用的好[教程](https://github.com/SwiftEducation/presentations)。这对于基础学起的同学有福了。
* [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education)：整理地如此美妙的学习资源，实在让人太欢喜了。
* [iOS Cookies](http://www.ioscookies.com/)：分类合理、排序靠谱的 Swift 开源类库集合。
* [matteocrippa/awesome-swift](https://github.com/matteocrippa/awesome-swift)：这个版本的 Swift 资源集合内容丰富，分类也不错。作者：[Matteo Crippa](https://github.com/matteocrippa)
* [适合iOS开发者的 15 大网站推荐](http://www.csdn.net/article/2015-03-04/2824108-ios-developers-sites/1)：的确很全、很主流的国外 iOS 开发者网站。
* [掘金 Swift 版块](http://gold.xitu.io/#/tag/Swift)
* [码农周刊 －《Swift 特刊》](http://weekly.manong.io/issues/33?ref=swift)
* [CocoaChina －《Swift 新手入门汇集帖》](http://www.cocoachina.com/bbs/read.php?tid=204512)
* [CSDN_CODE －《Swift 编程语言资料大合集》](http://code.csdn.net/news/2820075)
* [InfoQ －《学习苹果 Swift 语言的一些在线资源（英文）》](http://www.infoq.com/cn/news/2014/06/apple-swift-learning-resources)
* [刘兰涛 －《Swift 学习资源》](https://github.com/Lax/iOS-Swift-Demos/wiki) By [@懒桃儿吃桃儿](http://weibo.com/u/1653644220)
* [learnswift.tips](http://www.learnswift.tips/)：国外主流 Swift 学习资源集合。
* [Awesome iOS](https://github.com/vsouza/awesome-ios)：一个 iOS 的各类优秀的开源项目集合。真不错！可惜Swift开源项目资源不足。
* [iOS Developer Tips](http://iosdevelopertips.com/)：还是有关 iOS 的开发资源及文章合集。
* [Wolg/awesome-swift](https://github.com/Wolg/awesome-swift)：一位俄罗斯朋友分类整理的 Swift 资源列表（有持续更新）。
* [Aufree/trip-to-iOS](https://github.com/Aufree/trip-to-iOS)：显然作者很用心的做了非常深入的整理。它对于开发者拓展学习范围及开发知识面非常有益。
* [Robin Eggenkamp - Awesome Swift](https://swift.zeef.com/robin.eggenkamp)：“一个收集了很多 Swift 开发资源的网站”。
* [iOS 开发技术前线](https://github.com/hehonghui/iOS-tech-frontier)：“一个定期翻译、发布国内外iOS优质的技术、开源库、软件架构设计、测试等文章的开源项目”。主要翻译来源 Ray Wenderlich，App Coda，Medium。来源：[@开发技术前线](http://weibo.com/u/5589212242)
* [11个超棒的 iOS 开发学习网站](http://www.cocoachina.com/ios/20150626/11348.html)：还算比较主流的归纳。不过，缺了raywenderlich.com 和 ioscreator.com 这两个重量级教程网站实在是不应该啊。



----------
## <a id="website"></a>4#网站社区
* [Awesome Swift](https://github.com/matteocrippa/awesome-swift) A collaborative list of awesome swift resources
* [iOS](https://github.com/vsouza/awesome-ios) A curated list of awesome iOS frameworks, libraries, tutorials, Xcode plugins, components and much more
* [Library and tools for iOS](https://github.com/joeljfischer/awesome-apple/blob/master/README.md) A list of awesome 3rd party libraries and tools for Apple platform development, iOS and Mac
* [MobDevGroup](http://mobdevgroup.com) iOS design and tool
* [Swift third library](http://www.ioscookies.com/) swift good third party library and search in the website
* [Jianshu](http://www.jianshu.com/u/da467cfe4cc8)
