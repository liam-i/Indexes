# <a name="Indexes"></a>Indexes - 方便我快速查找所收藏的资料
* [我自己的代码库](#我自己的代码库)
* [控件](#控件)
	* [Page](#控件-Page)
	* [PopupMenu](#控件-PopupMenu)
	* [Alert & ActionSheet](#控件-Alert)
	* [HUD](#控件-HUD)
	* [Label](#控件-Label)
	* [Button](#控件-Button)
	* [TextField & TextView](#控件-TextView)
	* [TabBarController](#控件-Tabbar)
	* [NavigationController](#控件-Navbar)
	* [CollectionView](#控件-CollectionView)
	* [RefreshControl](#控件-RefreshControl)
	* [SegmentedControl](#控件-SegmentedControl)
	* [ImagePicker](#控件-ImagePicker)
	* [SearchController](#控件-SearchController)
	* [QRCode](#控件-QRCode)
	* [新手引导](#控件-新手引导)
	* [侧滑菜单](#控件-侧滑菜单)
	* [弹幕](#控件-弹幕)
	* [动画View](#控件-动画View)
	* [转场动画](#控件-转场动画)
	* [弹幕](#控件-弹幕)
	* [IM组件](#控件-IM)
	* [图表](#控件-图表)
	* [EmptyData](#控件-EmptyData)
* [组件](#组件)
	* [WebImage](#组件-WebImage)
	* [JSON / XML & Model](#组件-JSONModel)
	* [AutoLayout](#组件-AutoLayout)
	* [缓存](#组件-缓存)
	* [Color](#组件-Color)
	* [应用内充值](#组件-IAP)
* [数据存储](#数据存储)
* [音视频](#音视频)
* [优化/性能调优/ipa瘦身](#优化/性能调优/ipa瘦身)
* [HTTP/TCP/UDP/SMTP/XMPP等网络协议库](#HTTP/TCP/UDP)
* [日志收集](#日志收集)
* [骨骼/帧动画](#骨骼/帧动画)
* [主题（Dark Mode）](#主题DarkMode)
* [SwiftUI](#SwiftUI)
* [完整APP](#完整APP)
* [精心收集和积累（学习资料/优秀组件）](#精心收集和积累)
* [程序员日常](#程序员日常)
* [服务器](#服务器)
* [游戏引擎](#游戏引擎)
* [人工智能/深度学习](#人工智能深度学习)
* [Android](#Android)
* [前端](#前端)

## <a name="我自己的代码库"></a> 我自己的代码库
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [LPText](https://github.com/leo-lp/LPText) | 学习YYText ||
| [LPResourceFilter](https://github.com/leo-lp/LPResourceFilter) | 检查版本之间的Assets.xcassets差异 ||
| [LPLayoutConstraint](https://github.com/leo-lp/LPLayoutConstraint) |  自动布局组件 ||
| [LPInputBarAccessoryView](https://github.com/leo-lp/LPInputBarAccessoryView)|  ||
| [LPInputView](https://github.com/leo-lp/LPInputView)|  ||
| [LPLinkMap](https://github.com/leo-lp/LPLinkMap)| LinkMap解析工具 ||
| [LPIM](https://github.com/leo-lp/LPIM) | 一个防网易云信的即时通讯demo ||
| [LPPhotoPickerController](https://github.com/leo-lp/LPPhotoPickerController) |  ||
| [LPPhotoBrowser](https://github.com/leo-lp/LPPhotoBrowser) |  ||
| [LPKeyboardManager](https://github.com/leo-lp/LPKeyboardManager) |  ||
| [LPProgressHUD](https://github.com/leo-lp/LPProgressHUD) | 一个**Swift**版的[MBProgressHUD](https://github.com/jdg/MBProgressHUD) ||
| [LPTextView](https://github.com/leo-lp/LPTextView) |  ||
| [LPDelayedSearch](https://github.com/leo-lp/LPDelayedSearch) |  ||
| [LPPresentationController](https://github.com/leo-lp/LPPresentationController) |  ||
| [LPPageBar](https://github.com/leo-lp/LPPageBar) |  ||
| [LPKit](https://github.com/leo-lp/LPKit) |  ||
| [LPLogger](https://github.com/leo-lp/LPLogger) |  ||
| [LPPage](https://github.com/leo-lp/LPPage) |  ||
| [LPEmptyDataSet](https://github.com/leo-lp/LPEmptyDataSet) | `UITableView` / `UICollectionView`父类的扩展，用于在视图无内容时自动显示空数据集 ||
| [LPNetdiag](https://github.com/leo-lp/LPNetdiag) |||
| [Twitter](https://github.com/leo-lp/Twitter) | [twitter-kit-ios](https://github.com/twitter-archive/twitter-kit-ios)精简版 ||

## <a name="控件"></a> 控件
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [QMUI_Web](https://github.com/Tencent/QMUI_Web) | QMUI Web 是一个专注 Web UI 开发，帮助开发者快速实现特定的一整套设计的框架。框架主要由一个强大的 SASS 方法合集与内置的工作流构成。通过 QMUI Web，开发者可以很轻松地提高 Web UI 开发的效率，同时保持了项目的高可维护性与稳健。如果你需要方便地控制项目的整体样式，或者需要应对频繁的界面变动，那么 QMUI Web 框架将会是你最好的解决方案 | [官网](http://qmuiteam.com/web), [Demo](https://github.com/QMUI/QMUIDemo_Web/releases) |
| [QMUI_iOS](https://github.com/Tencent/QMUI_iOS) | [Tencent](https://github.com/Tencent/)的致力于提高项目 UI 开发效率的解决方案 | [官网](http://qmuiteam.com/ios)，[Demo](https://github.com/QMUI/QMUIDemo_iOS) |
| [iOS-blur](https://github.com/JagCesar/iOS-blur) | 在iOS 7中，新视图在多个位置显示，该视图是透明的并且具有很好的模糊效果。但是，Apple尚未向我们提供公共API来使用这种令人惊叹的视图 |  |
| [Tangram-iOS](https://github.com/alibaba/Tangram-iOS) | [alibaba](https://github.com/alibaba)的Tangram，七巧板，几块简单的积木就能拼出大千世界 | [官网](http://tangram.pingguohe.net/) |
| [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) | 很棒的加载动画的集合 ||
| [YYKit](https://github.com/ibireme/YYKit) | [ibireme](https://blog.ibireme.com/)大神的iOS组件的集合 |  |
| [FSCalendar](https://github.com/WenchaoD/FSCalendar) | 完全可定制的iOS日历库，与Objective-C和Swift兼容 |  |
| [CVCalendar](https://github.com/CVCalendar/CVCalendar) | 可自定义日历控件 ||
| [DateScrollPicker](https://github.com/alberdev/DateScrollPicker) | 一个完全可自定义的日期视图，该日历包含无限日期单元格和动画选择的集合，您可以使用自己的字体和颜色来自定义 ||
| [SevenSwitch](https://github.com/bvogelzang/SevenSwitch) | iOS7样式取代UISwitch ||
| [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch) | 在Swift 2.0中开发的Runkeeper设计开关控件（两部分控件） ||
| [InAppSettingsKit](https://github.com/futuretap/InAppSettingsKit) | IASK是一个开放源代码解决方案，可轻松将应用程序内设置添加到您的iPhone应用程序 |  |
| [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) | UIWebView进度界面 |  |
| [FlatUIKit](https://github.com/Grouper/FlatUIKit) | 适用于iOS的很棒的平面UI组件的集合 ||
| [RxWebViewController](https://github.com/Roxasora/RxWebViewController) | 实现类似微信的 webView 导航效果，包括进度条，左滑返回上个网页或者直接关闭，就像 UINavigationController |  |

### <a name="控件-Page"></a> Page
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [JXCategoryView](https://github.com/pujiaxin33/JXCategoryView) | 腾讯新闻、今日头条、QQ音乐、网易云音乐、京东、爱奇艺、腾讯视频、淘宝、天猫、简书、微博等所有主流APP分类切换滚动视图 | |
| [JXPagingView](https://github.com/pujiaxin33/JXPagingView) | 类似微博主页、简书主页等效果。多页面嵌套，既可以上下滑动，也可以左右滑动切换页面。支持HeaderView悬浮、支持下拉刷新、上拉加载更多。 |  |
| [VTMagic](https://github.com/tianzhuo112/VTMagic) | iOS的page库，您可以根据需要通过不同的标识符自定义每个页面控制器。使用起来非常简单 | [博客](http://www.jianshu.com/p/cb2edb21055f) |
| [LTScrollView](https://github.com/gltwy/LTScrollView) | ScrollView嵌套ScrolloView（UITableView、UICollectionView）解决方案，支持OC/Swift | [博客](http://blog.csdn.net/glt_code/article/details/78576628) |
| [FSPagerView](https://github.com/WenchaoD/FSPagerView) | 一个精美的屏幕幻灯片库。对于制作横幅视图，产品展示，欢迎/指南页面，屏幕/ ViewController滑块非常有用 ||
| [SPPage](https://github.com/xichen744/SPPage) | Page Controller |  |
| [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) | 一个容器视图控制器，它使我们可以在视图控制器的集合之间轻松切换。平移手势可用于移至下一个或上一个视图控制器。它显示当前，上一个，下一个子视图控制器的协同指针 |  |
| [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) | 无限循环图片、文字轮播器 |  |
| [ZJScrollPageView](https://github.com/jasnig/ZJScrollPageView) | 网易新闻，腾讯视频，头条等距的滚动视图联动的效果OC版的简单方便的集成，滑块segment，scrollViewController（提供一种简便的方法来达到“分段随内容滚动”的效果） |  |
| [PageMenu](https://github.com/PageMenu/PageMenu) | 一个完全可自定义且灵活的分页菜单控制器，由放置在滚动视图内的其他视图控制器构建而成，使用户可以通过轻松点按或滑动手势在任何一种视图控制器之间进行切换，类似于Spotify，Windows Phone和Instagram的用法 |  |
| [LCAnimatedPageControl](https://github.com/bawn/LCAnimatedPageControl) | 自UIPageControl用一个简单的动画 | [博客](http://bawn.github.io/ios/uipagecontrol/2015/06/16/LCAnimatedPageControl.html) |
| [iCarousel](https://github.com/nicklockwood/iCarousel) | [iCarousel](http://www.charcoaldesign.co.uk/source/cocoa#icarousel)是一个类，旨在简化在iPhone，iPad和Mac OS上各种类型的轮播（页面，滚动视图）的实现。iCarousel实现了许多常见的效果，例如圆柱形，扁平和“ CoverFlow”风格的旋转木马，并提供了挂钩来实现您自己的定制效果 |  |
| [KYAnimatedPageControl](https://github.com/KittenYang/KYAnimatedPageControl) | 具有多个动画的自定义UIPageControl |  |

### <a name="控件-Label"></a> Label
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [YYText](https://github.com/ibireme/YYText) | 适用于iOS的强大文本框架，用于显示和编辑RTF。（它是[YYKit](https://github.com/ibireme/YYKit)的组件） |  |
| [WZLBadge](https://github.com/weng1250/WZLBadge) | 一行代码实现Badge效果 ||
| [TYAttributedLabel](https://github.com/12207480/TYAttributedLabel) | TYAttributedLabel 简单，强大的属性文本控件(无需了解CoreText)，支持图文混排显示，支持添加链接，image和UIView控件，支持自定义排版显示 |  |
| [MarqueeLabel](https://github.com/cbpowell/MarqueeLabel) | 一个UILabel子类，当标签文本超出可用宽度时，添加滚动字幕效果。也可以指定标签的滚动方向和速度/速率 ||
| [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) | 用Swift编写的UILabel的优美变形效果 |  |
| [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift) | UILabel嵌入式替换，支持以Swift编写的Hashtags(＃)，提及(@)，URL(http://)和自定义正则表达式模式 ||
| [MLLabel](https://github.com/molon/MLLabel) | 带有TextKit的UILabel。支持链接和自定义表达式 |  |
| [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) | UILabel的直接替代品，支持属性，数据检测器，链接等 |  |
| [ZCAnimatedLabel](https://github.com/overboming/ZCAnimatedLabel) | UILabel替换为细粒度的出现/消失动画 |  |

### <a name="控件-Button"></a> Button
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [RadioButton-ios](https://github.com/onegray/RadioButton-ios) | 扩展了标准的UIButton功能。可以为每个按钮配置默认和选定状态 |  |
| [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) | 受Google Material Design启发的iOS自定义UIButton效果 |  |
| [M13Checkbox](https://github.com/Marxon13/M13Checkbox) | 适用于iOS的可自定义复选框 |  |
| [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) | **BEMCheckBox**是一个开放源代码库，可轻松为iOS创建漂亮的，高度可定制的动画复选框 |  |
| [fave-button](https://github.com/janselv/fave-button) | FaveButton是一个用Swift编写的类似iOS的可爱动画按钮 |  |
| [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) | 液态[设计](https://www.google.com/design/spec/material-design/introduction.html)中的浮动动作按钮组件，受液态的[Material](http://www.materialup.com/posts/material-in-a-liquid-state)启发。这也是处于液态的旋[转装载机](https://github.com/yoavlt/LiquidLoader)组件 |  |
| [TKAnimatedCheckButton](https://github.com/entotsu/TKAnimatedCheckButton) | 受[1](http://robb.is/working-on/a-hamburger-button-transition/)和[2](https://dribbble.com/shots/1631598-On-Off)启发的动画复选按钮 |  |
| [hamburger-button](https://github.com/robb/hamburger-button) | 一个按钮[过渡动画](http://robb.is/working-on/a-hamburger-button-transition/) |  |
| [DownloadButton](https://github.com/PavelKatunin/DownloadButton) | 可自定义的App Store样式下载[按钮](http://pavelkatunin.github.io/DownloadButton) |  |
| [JSDownloadView](https://github.com/Josin22/JSDownloadView) | 精巧顺滑的[下载动画](http://qiaotongxin.cc/2016/08/30/20160830/) |  |

### <a name="控件-TextView"></a> TextField & TextView
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField) | `浮动标签模式`的美观灵活的文本字段控件实现 | |
| [KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView) | 一个UITextView子类，它增加了对用Swift编写的多行占位符的支持 ||
| [RichEditorView](https://github.com/cjwirth/RichEditorView) | RichEditorView是用于RTF编辑的简单，模块化，嵌入式UIView子类 |  |
| [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) | 带有不断增长的文本输入视图和其他有用消息功能的嵌入式UIViewController子类 | [官网](https://slack.com/) |

### <a name="控件-SegmentedControl"></a> SegmentedControl
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [HMSegmentedControl](https://github.com/HeshamMegid/HMSegmentedControl) | UISegmentedControl的直接替代品，模仿了Google Currents和其他各种Google产品中使用的分段控件的样式 ||
| [JXSegmentedView](https://github.com/pujiaxin33/JXSegmentedView) | 腾讯新闻、今日头条、QQ音乐、网易云音乐、京东、爱奇艺、腾讯视频、淘宝、天猫、简书、微博等所有主流APP分类切换滚动视图 | |

### <a name="控件-SearchController"></a> SearchController
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [YNSearch](https://github.com/younatics/YNSearch) | 🔍令人敬畏的完全自定义搜索视图 | [官网](https://www.cocoacontrols.com/controls/ynsearch) |
| [PYSearch](https://github.com/ko1o/PYSearch) | 🔍 一个优雅的搜索控制器，它取代了UISearchController |  |

### <a name="控件-QRCode"></a> QRCode
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [EFQRCode](https://github.com/EFPrefix/EFQRCode) | 一个轻量级的、用来生成和识别二维码的纯Swift库，可根据输入的水印图和图标产生艺术二维码，基于CoreGraphics、CoreImage和ImageIO进行开发；项目受[qrcode](https://github.com/sylnsfar/qrcode)启发 ||
| [LBXScan](https://github.com/MxABC/LBXScan) | 条形码和二维码扫描器（二维码，扫码，扫一扫，ZXing，ZBar，iOS系统AV基础扫码封装，扫码界面效果封装） ||
| [swiftScan](https://github.com/MxABC/swiftScan) | 条形码和二维码扫描仪（二维码各种码识别，生成，界面效果） ||
 | [QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift) | 简单QRCode阅读器，可解码这些[格式类型](https://developer.apple.com/documentation/avfoundation/avmetadatamachinereadablecodeobject#//apple_ref/doc/constant_group/Machine_Readable_Object_Types) |  |

### <a name="控件-新手引导"></a> 新手引导
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [Interpolate](https://github.com/marmelroy/Interpolate) | App启动引导框架 ||
| [BWWalkthrough](https://github.com/ariok/BWWalkthrough) | App启动引导组件 ||
| [XHLaunchAd](https://github.com/CoderZhuXH/XHLaunchAd) | 开屏广告、启动广告解决方案-支持静态/动态图片广告,mp4视频广告,全屏/半屏广告、兼容iPhone/iPad ||
| [JazzHands](https://github.com/IFTTT/JazzHands) | 一个简单的基于关键帧的UIKit动画框架。非常适合滚动应用介绍 ||
| [liquid-swipe](https://github.com/Cuberto/liquid-swipe) | 一种易于使用的滑动容器控件，可在您的应用程序中使用-例如，用于首次运行的教程 ||

### <a name="控件-侧滑菜单"></a> 侧滑菜单
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [FWSideMenu](https://github.com/CyonLeu/FWSideMenu) | 左右侧滑菜单，支持3D和模糊效果 ||
| [MSDynamicsDrawerViewController](https://github.com/erichoracek/MSDynamicsDrawerViewController) | 容器视图控制器利用UIKit Dynamics提供逼真的抽屉导航范例 ||
| [RNFrostedSidebar](https://github.com/rnystrom/RNFrostedSidebar) | 具有模糊背景和切换动画的Control Center式控件 |  |
| [LLSlideMenu](https://github.com/lilei644/LLSlideMenu) | 这是iOS应用弹簧滑菜单，一个弹性侧滑菜单 |  |
| [SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift) | 基于Google +，iQON，Feedly和Ameba iOS应用的iOS幻灯片菜单视图 |  |
| [ViewDeck](https://github.com/ViewDeck/ViewDeck) | 管理各种侧菜单的框架。它支持左右菜单，并以编程方式和通过用户手势管理侧菜单的显示 |  |
| [REFrostedViewController](https://github.com/romaonthego/REFrostedViewController) | 出现在视图控制器顶部的iOS 7/8样式模糊视图控制器 |  |
| [SWRevealViewController](https://github.com/John-Lluch/SWRevealViewController) | 一个UIViewController子类，用于在Facebook应用程序的启发下，在前控制器后面显示后（左和/或右）视图控制器 |  |
| [Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS) | 具有可定制UI的动画侧菜单 | [博客](https://yalantis.com/?utm_source=github) |
| [ZYSideSlipFilter](https://github.com/liuzhiyi1992/ZYSideSlipFilter) | 侧边栏条件筛选器，筛选区域模块插拔，AutoLayout动态适配区域高度 |  |
| [SwiftSideslipLikeQQ](https://github.com/johnlui/SwiftSideslipLikeQQ) | 再造“手机QQ”[侧滑菜单](http://lvwenhan.com/ios/445.html) ||
| [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) |  轻巧易用的侧边抽屉导航控制器 |  |
| [SideMenu](https://github.com/jonkykong/SideMenu) | 适用于iOS的简单侧面/幻灯片菜单控件，无需代码！很多定制 |  |
| [RESideMenu](https://github.com/romaonthego/RESideMenu) | 具有视差效果的iOS 7/8样式侧面菜单 |  |

### <a name="控件-弹幕"></a> 弹幕
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [QHDanumuDemo](https://github.com/chenqihui/QHDanumuDemo) | 弹幕系统。[新版](https://github.com/chenqihui/QHDanmu2Demo) ||
| [OCBarrage](https://github.com/w1531724247/OCBarrage) | 弹幕, 同时渲染5000条弹幕也不卡, 轻量, 可拓展, 高度自定义动画, 超高性能, 简单易上手 |  |
| [HJDanmakuDemo](https://github.com/panghaijiao/HJDanmakuDemo) | iOS[弹幕解决方案](http://www.olinone.com/?p=755) |  |
| [BarrageRenderer](https://github.com/unash/BarrageRenderer) | 一个iOS上的弹幕渲染库 |  |

### <a name="控件-IM"></a> IM组件
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [InputBarAccessoryView](https://github.com/nathantannar4/InputBarAccessoryView) | 一个简单且易于自定义的InputAccessoryView，用于通过自动完成和附件制作功能强大的输入栏 |  |
| [Messenger](https://github.com/relatedcode/Messenger) | 开源的本机iOS [Messenger](http://related.blog/)，具有音频/视频通话和实时聊天对话（全面的离线支持） ||
| [MessageKit](https://github.com/MessageKit/MessageKit) | 聊天UI组件，[JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController)的替代品 | [博客](https://messagekit.github.io) |
| [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) | 一个类似微信App的IM应用，拥有发送文字、图片、语音、视频、地理位置消息，管理本地通信录、分享朋友圈、漂流交友、摇一摇和更多有趣的功能 |  |
| [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) | 适用于iOS的精美消息UI库 | [博客](https://www.jessesquires.com/blog/officially-deprecating-jsqmessagesviewcontroller/) |
| [WeChat](https://github.com/zhengwenming/WeChat) | 实现类似微信朋友圈或者QQ空间，评论回复，贴吧盖楼，九宫格布局。处理键盘弹出后定位到当前点击的被评论人处 |  |
| [Chatto](https://github.com/badoo/Chatto) | 一个用于构建聊天应用程序的Swift轻量级框架 |  |
| [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) | 适用于iOS的聊天和消息传递UI组件 | [官网](https://layer.com/) |

### <a name="控件-图表"></a> 图表
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [Charts](https://github.com/danielgindi/Charts) | 精美图表！跨平台MPAndroidChart的Apple端 ||
| [PNChart](https://github.com/kevinzhow/PNChart) | Piner和[CoinsMan for iOS中使用的简单美观的图表库 ||
| [PNChart-Swift](https://github.com/kevinzhow/PNChart-Swift) | 一个简单漂亮的[图表库](https://github.com/kevinzhow/PNChart) ||
| [iOS-Echarts](https://github.com/Pluto-Y/iOS-Echarts) | 本项目是将百度的ECharts(Echarts2)工具封装成对应的iOS和Mac的控件，并且将其中javascript的属性封装成对应的对象。并且提供了链式编程，方面大家进行配置Echarts的属性 |  |
| [ScrollableGraphView](https://github.com/philackm/ScrollableGraphView) | 适用于iOS的自适应可滚动图形视图，用于可视化简单的离散数据集。用Swift编写 |  |

### <a name="控件-EmptyData"></a> EmptyData
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) | 下拉式UITableView / UICollectionView超类类别，用于在视图无内容可显示时显示空数据集 | [官网](https://www.cocoacontrols.com/controls/dznemptydataset) |
| [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) | 模板自动布局单元，用于自动计算UITableViewCell高度 |  |
| [EmptyDataSet-Swift](https://github.com/Xiaoye220/EmptyDataSet-Swift) | [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet)的**Swift**版本 ||

### <a name="控件-Alert"></a> Alert & ActionSheet
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [TYAlertController](https://github.com/12207480/TYAlertController) | 功能强大，易于使用的警报视图或控制器和窗口上的弹出视图，支持模糊效果，自定义视图和动画 |  |
| [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) | Swift编写的iOS消息栏，非常灵活 ||
| [SwiftEntryKit](https://github.com/huri000/SwiftEntryKit) | 一个用Swift编写的简单而通用的消息提示器 |  |
| [PMAlertController](https://github.com/pmusolino/PMAlertController) | PMAlertController是一个很棒的可自定义警报，可以替代UIAlertController | |
| [SDCAlertView](https://github.com/sberrevoets/SDCAlertView) | SDCAlertView最初是从看起来与相同的警报开始的UIAlertView，但是它支持自定义内容视图。随着UIAlertControlleriOS 8 的引入，该项目已更新为UIAlertController带来的更现代的API ||
| [SCLAlertView](https://github.com/dogo/SCLAlertView) | 用Swift编写的动画警报视图，但已移植到Objective-C，可用作a UIAlertView或UIAlertController替代 |  |
| [SweetAlert-iOS](https://github.com/codestergit/SweetAlert-iOS) | 美丽的动画自定义警报视图，其灵感来自javascript库[SweetAlert](http://tristanedwards.me/sweetalert)。这个SweetAlertView是用Swift编写的，可以在Swift和Objective-C项目中使用 |  |
| [SCLAlertView-Swift](https://github.com/vikmeup/SCLAlertView-Swift) | 动画警报视图，可以用作UIAlertView或UIAlertController替代 |  |

### <a name="控件-HUD"></a> HUD
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [WaveLoadingView](https://github.com/liuzhiyi1992/WaveLoadingView) | 水波等负载指示器 |  |
| [UAProgressView](https://github.com/UrbanApps/UAProgressView) | 一个简单而轻巧但功能强大的动画循环进度视图 ||
| [Whisper](https://github.com/hyperoslo/Whisper) | 📣Whisper是一个组件，可以简化显示消息和应用内通知的任务 |  |
| [JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification) | [iOS]简单，可自定义的通知显示在状态栏顶部。随着进步和活动。iPhone X准备就绪 |  |
| [DACircularProgress](https://github.com/danielamitay/DACircularProgress) | [DACircularProgress](https://github.com/danielamitay)是具有循环UIProgressView属性的UIView子类 |  |
| [KVNProgress](https://github.com/AssistoLab/KVNProgress) | KVNProgress是一个完全可自定义的进度HUD，可以全屏显示，也可以全屏显示 ||
| [Toast-Swift](https://github.com/scalessec/Toast-Swift) | Toast-Swift是一个Swift扩展，它将Toast通知添加到UIView对象类。它旨在简单，轻便且易于使用。大多数吐司通知可以用一行代码触发 ||
| [KYCircularProgress](https://github.com/kentya6/KYCircularProgress) | 用Swift编写的灵活进度条 |  |
| [NotificationBanner](https://github.com/Daltron/NotificationBanner) | 在iOS中的应用程序通知横幅中显示高度可定制的最简单方法 |  |
| [PKHUD](https://github.com/pkluz/PKHUD) | 基于Swift的Apple HUD（音量，铃声，旋转等）的重新实现，适用于iOS 8 |  |
| [MBProgressHUD](https://github.com/jdg/MBProgressHUD) | 一个iOS嵌入式类，在后台线程中完成工作时显示带有指示符和/或标签的半透明HUD | [官网](http://www.bukovinski.com/) |
| [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) | 适用于您的iOS和tvOS应用的干净轻便的进度HUD |  |
| [JGProgressHUD](https://github.com/JonasGessner/JGProgressHUD) | 适用于iOS和tvOS的优雅，简单的进度HUD，与Swift和ObjC兼容 |  |
| [Dodo](https://github.com/evgenyneu/Dodo) | 使用Swift编写的iOS消息栏 |  |
| [EasyTipView](https://github.com/teodorpatras/EasyTipView) | 用Swift编写的完全可定制的工具提示视图，可以用作号召性用语或信息提示 |  |

### <a name="控件-Navbar"></a> NavigationController
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [TLYShyNavBar](https://github.com/telly/TLYShyNavBar) | 与所有那些傲慢的UINavigationBar不同，这一个害羞而谦虚！轻松创建自动滚动的导航栏！ ||
| [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) | 跟随UIScrollView滚动的可滚动UINavigationBar ||
| [HKScrollingNavAndTabBar](https://github.com/HustHank/HKScrollingNavAndTabBar) | 一个易于使用的库，用于在用户滚动时管理导航栏，标签栏或工具栏的隐藏和显示 |  |
| [LTNavigationBar](https://github.com/ltebean/LTNavigationBar/tree/swift3.0) | UINavigationBar扩展可让您动态更改其外观 |  |
| [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) | 一个用来统一管理导航栏转场以及当 push 或者 pop 的时候使动画效果更加顺滑的通用库，并且同时支持竖屏和横屏。你不用为这个库写一行代码，所有的改变都悄然发生 ||
| [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation) | 推入和弹出时更改UINavigationBar的backgroundColor的简单方法 |  |
| [BLKFlexibleHeightBar](https://github.com/bryankeller/BLKFlexibleHeightBar) | 创建像在Facebook，Square Cash和Safari iOS应用程序中看到的冷凝标题栏 ||

### <a name="控件-Tabbar"></a> TabBarController
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [IrregularTabbarCustom](https://github.com/singer1026/IrregularTabbarCustom) | 不规则`Tabbar` ||
| [MyTabbar](https://github.com/singer1026/MyTabbar)  | 不规则`Tabbar` ||
| [WXTabBarController](https://github.com/leichunfeng/WXTabBarController) | 在系统 UITabBarController 的基础上实现安卓版微信 TabBar 的滑动切换功能 |  |
| [Tabman](https://github.com/uias/Tabman) |  带有交互式指示器栏的功能强大的分页视图控制器 | [博客](https://uias.github.io/Tabman/master/) |
| [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) | 一个易于使用的UITableViewCell子类，实现了可滑动的内容视图，该视图公开了实用程序按钮（类似于iOS 7 Mail Application） |  |
| [CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController) | 【中国特色 TabBar】一行代码实现 Lottie 动画TabBar，支持中间带+号的TabBar样式，自带红点角标，支持动态刷新 |  |
| [YPTabBarController](https://github.com/yuping1989/YPTabBarController) | 一款功能十分强大的TabBarController，几乎你所能想到的关于TabBar的需求，它都能实现 |  |
| [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) | [它](https://yalantis.com/)是一个折叠选项卡栏和选项卡栏控制器 |  |
| [FancyTabBar](https://github.com/marvelapp/FancyTabBar) | 适用于iOS的可扩展和可自定义的标签栏 |  |
| [BATabBarController](https://github.com/antiguab/BATabBarController) | [一个TabBarController](https://antiguab.github.io/batabbarcontroller/)，具有用于选择的独特动画 ||

### <a name="控件-PopupMenu"></a> PopupMenu
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [QBPopupMenu](https://github.com/questbeat/QBPopupMenu) | iOS的可自定义弹出菜单 |  |
| [STPopup](https://github.com/kevin0571/STPopup) | STPopup提供了STPopupController，与iPhone和iPad上的UINavigationController以弹出式样式一样 ||
| [MIBlurPopup](https://github.com/MarioIannotta/MIBlurPopup) |使您可以创建背景模糊的弹出窗口 |  |
| [PopMenu](https://github.com/xhzengAIB/PopMenu) | PopMenu是受新浪微博/网易应用启发的流行动画菜单 |  |
| [Popover](https://github.com/corin8823/Popover) | 一个像Facebook应用程序一样的气球库。它写得很快 |  |
| [MMPopupView](https://github.com/adad184/MMPopupView) | 弹出框组件应该是绝大多数应用都少不了的(只有极少数精心设计的APP会用不到) 当然我们的APP也不例外 之前我们APP的弹出框组件是我用pop写的 可是后来发现与系统原生动画有些冲突(pop内部用到了CATransaction 导致跟系统动画同时发生时会有问题) 所以上周花了大半天时间重写了一下MMPopupView这个组件 ||
| [PopoverView](https://github.com/runway20/PopoverView) | [PopoverView](http://www.getosito.com/blog/engineering/popoverview-a-flexible-modal-content-view-for-ios/)一个用CoreGraphics编写的iPhone / iPad的简单UIView弹出控件 |  |

### <a name="控件-动画View"></a> 动画View
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [expanding-collection](https://github.com/Ramotion/expanding-collection) | 一个动画材质设计UI卡监视/弹出控制器. iOS library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [circle-menu](https://github.com/Ramotion/circle-menu) | CircleMenu是一个简单而优雅的UI菜单，具有圆形布局和材质设计动画. Swift UI library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) |  |
| [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) | 一个Swift UI模块库，用于向iOS标签栏项和图标添加动画. iOS library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [preview-transition](https://github.com/Ramotion/preview-transition) | PreviewTransition是具有动画过渡的简单预览库UI控制器. Swift UI library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [reel-search](https://github.com/Ramotion/reel-search) | 🔍RAMReel是一个UI控制器，允许您从列表中选择选项. Swift UI library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [paper-onboarding](https://github.com/Ramotion/paper-onboarding) | PaperOnboarding是一种材质设计UI滑块. Swift UI library by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [navigation-stack](https://github.com/Ramotion/navigation-stack) | 一个堆栈模型的UI导航控制器. Swift UI library made by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) |  |
| [paper-switch](https://github.com/Ramotion/paper-switch) | 🎚RAMPaperSwitch是一个Swift材质设计UI模块，在打开开关时会在父视图上绘画. iOS library by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) ||
| [folding-cell](https://github.com/Ramotion/folding-cell) | 📃FoldingCell是使用@Ramotion制作的动画的扩展内容单元. iOS library by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) |  |
| [adaptive-tab-bar](https://github.com/Ramotion/adaptive-tab-bar) | AdaptiveController是一个“渐进缩减” Swift UI模块，用于向本机或自定义iOS UI元素添加自定义状态. Swift UI component by @Ramotion - [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) |  |
| [Magnetic](https://github.com/efremidze/Magnetic) | 一种可自定义的气泡选择器，类似于Apple Music类型的选择 ||
| [DeepDiff](https://github.com/onmyway133/DeepDiff) | DeepDiff通过编辑步骤告诉2个集合之间的差异以及所做的更改。它还支持[Texture](https://github.com/TextureGroup/Texture)，请参见[Texture示例](https://github.com/onmyway133/DeepDiff/tree/master/Example/DeepDiffTexture)；阅读更多[使用diff框架在Swift中更新UICollectionView数据的更好方法](https://medium.com/flawless-app-stories/a-better-way-to-update-uicollectionview-data-in-swift-with-diff-framework-924db158db86) ||
| [Canvas](https://github.com/CanvasPod/Canvas) | 动画View组件 | 
| [TBIconTransitionKit](https://github.com/AlexeyBelezeko/TBIconTransitionKit) | 图标过渡组件，可从一种形状平滑地转换为另一种形状 ||
| [DMHeartFlyAnimation](https://github.com/singer1026/DMHeartFlyAnimation) | 仿映客,花椒等直播APP点赞动画 ||
| [LNBRippleEffect](https://github.com/bharathlalgudinatarajan/LNBRippleEffect) | 创建带有波纹动画的类似Tinder的按钮 |  |
| [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) | 一个用于轻松构建复杂的iOS UIView动画的库 ||
| [LoginCritter](https://github.com/cgoldsby/LoginCritter) | 一个有意思的登录界面（动物的脸部表情会根据光标位置移动） ||
| [QQBubbleView](https://github.com/Yasic/QQBubbleView) | 利用三阶贝塞尔曲线模仿QQ空间直播页面右下角的礼物冒泡特效 |  |
| [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) | 一个不错的粘稠效果菜单 |  |
| [BCGenieEffect](https://github.com/Ciechan/BCGenieEffect) | iOS应用程序内的**OSX**风格精灵效果 |  |
| [SXWaveAnimate](https://github.com/dsxNiubility/SXWaveAnimate) | 实现非常美观的灌水动画 |  |
| [CoreLock](https://github.com/CharlinFeng/CoreLock) | 高仿支付宝解锁 ||
| [MMTweenAnimation](https://github.com/adad184/MMTweenAnimation) | POP（来自facebook）自定义动画的扩展。受[tweaner](https://code.google.com/p/tweaner)的启发，MMTweanerAnimation 在使用POP时提供10种类型的自定义动画 |  |
| [RBBAnimation](https://github.com/robb/RBBAnimation) | `RBBAnimation`是的子类，`CAKeyframeAnimation`它允许您**使用块**声明**动画**，而不用写出所有单独的关键帧 ||
| [Shimmer](https://github.com/facebook/Shimmer) | [facebook](https://github.com/facebook)的闪光是向应用程序中任何视图添加闪光效果的简便方法。用作不显眼的加载指示器很有用 |  |
| [BAFluidView](https://github.com/antiguab/BAFluidView) | UIView模拟运动中的流体的2D视图 |  |
| [pop](https://github.com/facebook/pop) | 一个可扩展的iOS和MacOS动画库，对于基于物理的交互非常有用 |  |
| [AGGeometryKit-POP](https://github.com/agens-no/AGGeometryKit-POP) | 使用POP将AGGeometryKit与POP桥接，可实现惊人的动态效果和动画效果 |  |
| [Spring](https://github.com/MengTo/Spring) | 一个用于简化Swift中的动画的库 ||
| [KYWaterWaveView](https://github.com/KittenYang/KYWaterWaveView) | 实现波浪正弦动画并带有小鱼跳跃溅起水花 |  |
| [15DaysofAnimationsinSwift](https://github.com/larrynatalicio/15DaysofAnimationsinSwift) | 一个学习动画的项目，受[Sam Lu 的Swift](https://twitter.com/samvlu)的[100 Days](http://samvlu.com/index.html)和[Allen Wang 的Swift](https://twitter.com/creativewang)的[30 Days](https://github.com/allenwong/30DaysofSwift)项目的启发 |  |
| [Advance](https://github.com/timdonnelly/Advance) | 适用于iOS，tvOS和macOS的动画库，该库使用基于物理的动画（包括弹簧） |  |
| [Motion](https://github.com/CosmicMind/Motion) | 这个库用于为iOS创建漂亮的动画和过渡 | [官网](http://cosmicmind.com/) |
| [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) | 使用IBAnimatable在Interface Builder中为可用于App Store的应用程序设计和原型定制UI，交互，导航，过渡和动画 |  |

### <a name="控件-转场动画"></a> 转场动画
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [FloatingPanel](https://github.com/SCENEE/FloatingPanel) | 适用于 iOS 应用程序（如Apple Maps）的干净轻巧的浮动面板UI ||
| [VCTransitionsLibrary](https://github.com/ColinEberhardt/VCTransitionsLibrary) | iOS7动画控制器和交互控制器的集合，提供翻转，折叠和各种其他过渡 |  |
| [BubbleTransition](https://github.com/andreamazz/BubbleTransition) | 一个自定义的模态过渡，用于呈现和消除具有扩展气泡效果的控制器 |  |
| [Hero](https://github.com/HeroTransitions/Hero) | 用于构建iOS视图控制器过渡的库。它在UIKit繁琐的过渡API之上提供了一个声明性层-使自定义过渡对于开发人员而言是一项轻松的任务 | [博客](http://lkzhao.com/2016/12/28/hero.html) |
| [StarWars.iOS](https://github.com/Yalantis/StarWars.iOS) | 该组件实现了过渡动画，以将视图控制器粉碎成小块 | [官网](https://yalantis.com/)，[博客](https://yalantis.com/blog/uidynamics-uikit-or-opengl-3-types-of-ios-animations-for-the-star-wars/) |
| [DeckTransition](https://github.com/HarshilShah/DeckTransition) | 一个类似于Apple Music播放卡片的过渡效果 |  |
| [PinterestSwift](https://github.com/demonnico/PinterestSwift) | Pinterest展示了如何view过渡效果 |  |
| [WXSTransition](https://github.com/alanwangmodify/WXSTransition) | 🍎界面转场动画集 |  |
| [TKSubmitTransition](https://github.com/entotsu/TKSubmitTransition) | 加载动画和过渡动画的动画UIButton |  |
| [Material](https://github.com/CosmicMind/Material) | 一个用于创建漂亮应用程序的UI/UX框架。利用[Motion](https://github.com/CosmicMind/Motion)专用于动画和过渡的库 | [官网](http://cosmicmind.com/) |
| [CardAnimation](https://github.com/seedante/CardAnimation) | 卡平移手势翻转动画 ||

### <a name="控件-ImagePicker"></a> ImagePicker
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [ImagePicker](https://github.com/hyperoslo/ImagePicker) | 适用于iOS应用程序的多合一相机解决方案。它使您的用户可以从库中选择图像并同时拍照。作为开发人员，您可以立即获得所有用户交互的通知，并免费获得漂亮的UI，就这么简单 | [博客](http://hyper.no) |
| [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) |  一个支持多选、选原图和视频的图片选择器，同时有预览、裁剪功能，支持iOS6+ ||
| [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) | 照片和视频播放器 ||
| [Paparazzo](https://github.com/avito-tech/Paparazzo) | 具有编辑功能的自定义iOS相机和照片选择器 ||
| [DKImagePickerController](https://github.com/zhangao0086/DKImagePickerController) | 适用于iOS的Image Picker Controller |  |
| [ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser) | 方便易用的相册多选框架，支持预览/相册内拍照及录视频、拖拽/滑动选择，3DTouch预览，编辑裁剪图片/视频，导出视频(可添加水印，粒子特效，视频转码)；支持多语言国际化(中文简/繁，英语，日语，可手动切换)；在线下载iCloud端图片；支持预览网络及本地图片/视频 |  |
| [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) | 适用于iOS的图像裁剪器/照片裁剪器 ||
| [BSImagePicker](https://github.com/mikaoj/BSImagePicker) | 适用于iOS的多图像选择器 ||
| [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) | 具有自定义图像选择器和图像裁剪功能的相机视图控制器 |  ||
| [Toucan](https://github.com/gavinbunney/Toucan) | Toucan是一个Swift库，提供了一个干净，快速的API用于处理图像。它极大地简化了图像的生成，支持调整图像的大小，裁剪和样式化 ||
| [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) | 一个简单的iOS照片和视频浏览器，具有网格视图，标题和选择 | [官网](http://michael.typify.io) |
| [YBImageBrowser](https://github.com/indulgeIn/YBImageBrowser) | iOS image browser / iOS 图片浏览器 (支持视频) |  |
| [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) | ImagePickerSheetController是在iMessage中复制自定义照片操作表的组件。它与UIAlertController非常相似，它使使用变得简洁明了。 ⚠️您还可以[在这里](https://github.com/lbrndnr/ImagePickerTrayController)找到此库的iOS 10版本⚠️ | [官网](http://laurinbrandner.ch/) |
| [TOCropViewController](https://github.com/TimOliver/TOCropViewController) | 用于裁剪UIImage对象的各个部分以及执行基本旋转。它非常适合编辑个人资料图片或在线共享照片的一部分 | [博客](http://www.timoliver.com.au/2015/06/21/tocropviewcontroller-an-open-source-image-cropper-for-ios/) |
| [PeekPop](https://github.com/marmelroy/PeekPop) | Peek and Pop是iPhone 6S和6S +引入的一项出色的iOS新功能，可让您使用3D触摸轻松预览内容。可悲的是，几乎60％的iOS用户使用的是旧设备。PeekPop是一个Swift框架，为Peek和Pop带来了向后兼容性 |  |
| [CocoaPicker](https://github.com/nsleejian/CocoaPicker) | 仿QQ图片选择器 ||
| [PixPic](https://github.com/Yalantis/PixPic) | [PixPic](https://yalantis.com/)照片编辑应用程序 |  |
| [ZYCornerRadius](https://github.com/liuzhiyi1992/ZYCornerRadius) | 使UIImageView的cornerRadius没有Offscreen-Rendered的类别，可以提高效率 |  |
| [HYBImageCliped](https://github.com/CoderJackyHuang/HYBImageCliped) | 开源高效处理圆角的扩展，包括UIImageView、UIView、UIButton、UIImage的扩展API，可根据图片颜色生成图片带任意圆角，可给UIButton根据不同状态处理图片 |  |

### <a name="控件-RefreshControl"></a> RefreshControl
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [RCTRefreshControl](https://github.com/Shuangzuan/RCTRefreshControl) | 下拉刷新控件 ||
| [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) | 加载时播放BreakOut-使用SpriteKit进行可播放拉动以刷新视图 |  |
| [pull-to-refresh](https://github.com/eggswift/pull-to-refresh) | ESPullToRefresh是一个非常易于开发者使用的下拉刷新和加载更多组件 |  |
| [MJRefresh](https://github.com/CoderMJLee/MJRefresh) | MJ.一种简单的使用立即刷新的方法 |  |
| [PullToRefresh](https://github.com/Yalantis/PullToRefresh) | 一个下拉刷新控件 | [官网](https://yalantis.com/) |
| [PullToBounce](https://github.com/entotsu/PullToBounce) | 动画的UIScrollView“拉动刷新”库 |  |
| [ODRefreshControl](https://github.com/Sephiroth87/ODRefreshControl) | 下拉菜单以刷新控件，例如Apple的iOS6 Mail App中的控件 |  |
| [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) | 弹性拉动可刷新Swift中开发的组件 |  |
| [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) | UIRefreshControl的自定义动画。受此[运球镜头](https://dribbble.com/shots/1974767-gear-powered-pull[-to-refresh-animation?list=animated&sort=popular&timeframe=now&offset=19)和[本教程](http://www.jackrabbitmobile.com/design/ios-custom-pull-to-refresh-control/)的启发 ||

### <a name="控件-CollectionView"></a> TableView & CollectionView
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [CollectionViewClassifyMenu](https://github.com/ChenYilong/CollectionViewClassifyMenu) | `CollectionView`做的两级菜单，可以折叠第二级菜单 ||
| [StickyCollectionView](https://github.com/matbeich/StickyCollectionView) |  UICollectionView布局，用于显示重叠的单元格.[Swift版](https://github.com/matbeich/StickyCollectionView-Swift)|  |
| [DifferenceKit](https://github.com/ra1028/DifferenceKit) | 快速，灵活的O（n）差异算法框架，用于Swift收集 | [博客](https://ra1028.github.io/DifferenceKit) |
| [CollectionViewSlantedLayout](https://github.com/yacir/CollectionViewSlantedLayout) | 显示倾斜单元格的CollectionView布局 | [官网](https://yassir.dev/CollectionViewSlantedLayout/) |
| [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit) | 基于Mail.app的可滑动UITableViewCell/UICollectionViewCell，在Swift中实现 | [官网](https://jerkoch.com/2017/02/07/swiper-no-swiping.html) |
| [AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout) | 一个UICollectionViewLayout子类，可在不影响您现有代码的情况下向UICollectionView添加自定义过渡/动画 |  |
| [IGListKit](https://github.com/Instagram/IGListKit) | 一个`UICollectionView `用于构建快速灵活列表的数据驱动框架 | [文档](https://instagram.github.io/IGListKit/) |
| [LxGridView](https://github.com/DeveloperLx/LxGridView) | 通过继承UICollectionView模仿Apple iOS系统桌面图标的排列和交互！ |  |
| [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) | UICollectionView的瀑布（即类似[Pinterest](http://pinterest.com/)的）布局。它还与[PSTCollectionView](https://github.com/steipete/PSTCollectionView)兼容 |  |
| [LazyScrollView](https://github.com/alibaba/LazyScrollView) | iOS 高性能异构滚动视图构建方案 |  |
| [Eureka](https://github.com/xmartlabs/Eureka) | 优雅的iOS表单生成器。由[XMARTLABS](http://xmartlabs.com/)精心编写，是[XLForm](https://github.com/xmartlabs/XLForm)的Swift版本 | [官网](https://eurekacommunity.github.io/) |
| [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) | 易于使用的UITableViewCell子类，可显示具有各种转换的可滑动按钮 |  |
| [Koloda](https://github.com/Yalantis/Koloda) | KolodaView是一个旨在简化Tinder类卡在iOS上的实现的类。它添加了方便的功能，例如用于动态加载视图的UITableView样式的dataSource / delegate接口，以及有效的视图加载和卸载 | [博客](https://yalantis.com/blog/how-we-built-tinder-like-koloda-in-swift/) |
| [Owl](https://github.com/malcommac/Owl) | 一个声明式类型安全框架，用于使用UITableViews和UICollectionViews构建快速灵活的列表 | [博客](https://danielemargutti.com/) |

## <a name="组件"></a>组件
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit) | 一个完全由Swift 5.0制作的轻量级iOS库，用于解析、格式化和验证国际电话号码 ||
| [M13OrderedDictionary](https://github.com/Marxon13/M13OrderedDictionary) |  NSArray和NSDictionary之间的交叉。它包含对象和键的有序列表 ||
| [OrderedDictionary](https://github.com/nicklockwood/OrderedDictionary) | OC中**有序字典**数据结构 ||
| [OrderedDictionary](https://github.com/lukaskubanek/OrderedDictionary) | Swift中**有序字典**数据结构的轻量级实现 |  |
| [git-remote-dropbox](https://github.com/anishathalye/git-remote-dropbox) | Git和Dropbox之间的[透明桥梁](http://www.anishathalye.com/2015/08/19/git-remote-dropbox/)-将Dropbox（共享）文件夹用作Git远程！ 🎁 |  |
| [lumen](https://github.com/anishathalye/lumen) | 基于屏幕内容的魔术[自动亮度](http://www.anishathalye.com/2016/07/31/lumen/)💡 |  |
| [KVOController](https://github.com/facebook/KVOController) | 键值观察是用于在模型-视图-控制器应用程序中的各层之间进行通信的一种特别有用的技术 |  |
| [FLEX](https://github.com/Flipboard/FLEX) | 适用于iOS的应用内调试和探索工具 |  |
| [ZipArchive](https://github.com/ZipArchive/ZipArchive) | ZipArchive是一个简单的实用程序类，用于在iOS，macOS和tvOS上压缩和解压缩文件 |  |
| [Parse-SDK-iOS-OSX](https://github.com/parse-community/Parse-SDK-iOS-OSX) | 一个[库](https://parseplatform.org/)，可让您从iOS或macOS应用访问强大的Parse Server后端 |  |
| [OpenSSL-for-iPhone](https://github.com/x2on/OpenSSL-for-iPhone) | 用于为iOS设备编译OpenSSL的脚本 | [官网](https://www.felixschulze.de/) |
| [facebook-swift-sdk](https://github.com/facebookarchive/facebook-swift-sdk) | 将您的iOS应用程序与Swift集成到[Facebook](https://developers.facebook.com/docs/swift)平台中 |  |
| [nimbus](https://github.com/jverkoey/nimbus) | [Nimbus](http://nimbuskit.info/)是一个iOS框架，其功能集的增长仅与其文档一样快 |  |
| [BlocksKit](https://github.com/BlocksKit/BlocksKit) | 您一直希望拥有的Objective-C块实用程序 |  |
| [peertalk](https://github.com/rsms/peertalk) | [PeerTalk](https://rsms.me/peertalk/)是一个iOS和Mac Cocoa库，用于通过USB进行通信 |  |
| [RandomKit](https://github.com/nvzqz/RandomKit) | 一个Swift框架，可简化随机数据的生成 | [博客](https://nvzqz.github.io/RandomKit/docs/) |  
| [LinkMap](https://github.com/huanxsd/LinkMap) | 检查每个类占用空间大小工具 | |
| [WeChatPlugin-MacOS](https://github.com/leo-lp/WeChatPlugin-MacOS) | 一款功能强大的macOS版微信小助手 ||
| [WeChatPlugin-iOS](https://github.com/leo-lp/WeChatPlugin-iOS) | 微信小助手-iOS版 ||
| [DoraemonKit](https://github.com/didi/DoraemonKit) | 一款功能齐全的客户端（ iOS 、Android、微信小程序 ）研发助手 ||
| [app-host](https://github.com/pluosi/app-host) | 一个轻量级的包托管网站，app-host 主要用于 iOS 和 Android 的包管理，作用类似于fir.im ||
| [coobjc](https://github.com/alibaba/coobjc) | coobjc为Objective-C和Swift提供协程支持。我们添加了一个等待方法，生成器和参与者模型，例如C＃，Javascript和Kotlin。为了方便起见，我们在cokit框架中为某些Foundation和UIKit API添加了协程类别，例如NSFileManager，JSON，NSData，UIImage等。我们还在coobjc中添加了元组支持 ||
| [Repeat](https://github.com/malcommac/Repeat) | 使用GCD制作的Swift，Debouncer和Throttler的现代计时器（替代NSTimer） ||
| [SwiftDate](https://github.com/malcommac/SwiftDate) | 在Swift中解析，验证，操作和显示日期，时区和时区 ||
| [Hydra](https://github.com/malcommac/Hydra) | 轻量级功能齐全的Promises，Async和Await库 ||
| [SwiftRichString](https://github.com/malcommac/SwiftRichString) | 优雅，简单，快捷的方式来创建属性字符串 ||
| [SwiftLocation](https://github.com/malcommac/SwiftLocation) | 高效/便捷的GPS跟踪，反向地理编码，区域监控自动完成，适用于iOS的信标 ||
| [weui](https://github.com/Tencent/weui) | WeUI 为微信 Web 服务量身设计 | [官网](https://weui.io) |
| [SwiftSoup](https://github.com/scinfu/SwiftSoup) | 纯Swift HTML解析器，具有DOM，CSS和jquery的优点（支持Linux，iOS，Mac，tvOS，watchOS） | [官网](http://www.scinfu.com/SwiftSoup/) |
| [twitter-text](https://github.com/twitter/twitter-text) | Twitter文字库 ||
| [JLRoutes](https://github.com/joeldev/JLRoutes) | 适用于iOS的URL路由库，带有基于块的简单API ||
| [twitter-kit-ios](https://github.com/twitter-archive/twitter-kit-ios) | TwitterKit是一个本地SDK，用于在移动应用程序中包含Twitter内容。Twitter工具包旨在使与Twitter的交互无缝且高效 ||
| [Swifter](https://github.com/mattdonnelly/Swifter) | 🐦用Swift编写的iOS和OS X的Twitter框架 |  |
| [swift-corelibs-libdispatch](https://github.com/apple/swift-corelibs-libdispatch) | libdispatch项目（又名Grand Central Dispatch），用于多核硬件上的并发性 | [官网](http://swift.org) |
| [swift-corelibs-foundation](https://github.com/apple/swift-corelibs-foundation) | 基础项目，提供核心实用程序，国际化和操作系统独立性 | [官网](http://swift.org) |
| [R.swift](https://github.com/mac-cain13/R.swift) | 在Swift项目中获得强大的类型化，自动完成的资源，例如图像，字体和序列 |  |
| [puppeteer](https://github.com/puppeteer/puppeteer) | Puppeteer是一个Node库，它提供了高级API来通过[DevTools协议](https://chromedevtools.github.io/devtools-protocol/)控制Chrome或Chromium 。Puppeteer 默认情况下无头运行，但可以配置为运行完整（无头）的Chrome或Chromium | [官网](https://pptr.dev/) |
| [libui](https://github.com/andlabs/libui) | C语言中的简单且可移植（但不灵活）的GUI库，使用其支持的每个平台的本机GUI技术 |  |
| [mapbox-navigation-ios](https://github.com/mapbox/mapbox-navigation-ios) | iOS上Swift中的逐行导航逻辑和UI | [官网](https://docs.mapbox.com/ios/navigation/) |
| [fishhook](https://github.com/facebook/fishhook) | 它可以在模拟器和设备上的iOS上运行的Mach-O二进制文件中动态重新绑定符 |  |
| [omi](https://github.com/Tencent/omi) | 前端跨框架跨平台框架，基于 Web Components 并支持 IE8+(omio)，小程序(omi-kbone) 和 任意前端框架集成 | [官网](http://omijs.org) |
| [rap2-delos](https://github.com/thx/rap2-delos) | 阿里妈妈前端团队出品的开源接口管理工具RAP第二代 | [官网](http://rap2.taobao.org) |
| [TextAttributes](https://github.com/delba/TextAttributes) | TextAttributes使编写属性字符串变得容易 |  |
| [knockout](https://github.com/knockout/knockout) | Knockout是JavaScript [MVVM](http://en.wikipedia.org/wiki/Model_View_ViewModel)（MVC的现代变体）库，它使使用JavaScript和HTML创建丰富的，类似于桌面的用户界面更加容易。它使用观察者使您的UI自动与基础数据模型保持同步，并具有一组功能强大且可扩展的声明性绑定，以实现高效的开发 | [官网](http://knockoutjs.com/) |
| [LPDMvvmRouterKit](https://github.com/foxsofter/LPDMvvmRouterKit) | 适用于iOS的优雅路由器套件 | [官网](http://cocoapods.org/pods/LPDMvvmRouterKit) |
| [cachecloud](https://github.com/sohutv/cachecloud) | 搜狐视频(sohu tv)Redis私有云平台  | [官网](http://cachecloud.github.io/) |
| [AGGeometryKit](https://github.com/agens-no/AGGeometryKit) | CALayer（分别控制每个角点），CGGeometry函数，UIView / CALayer属性和其他宝贵工具的四边形 ||
| [AliOS-Things](https://github.com/alibaba/AliOS-Things) | AliOS Things发布于[2017年杭州云栖大会](https://yunqi.aliyun.com/)， 是 AliOS 家族旗下的、面向IoT领域的、高可伸缩的物联网操作系统 |  |
| [SwiftyTimer](https://github.com/radex/SwiftyTimer) | NSTimer的Swifty API | [文档](http://radex.io/swift/nstimer) |
| [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) | iOS的图标字体库。目前支持Font-Awesome，Foundation图标，Zocial和ionicons |  |
| [mpush](https://github.com/mpusher/mpush) | MPush开源实时消息推送系统 | [官网](https://mpusher.github.io/) |
| [RxSwift](https://github.com/ReactiveX/RxSwift) | Swift中的响应式编程 |  |
| [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) | Swift中的响应式编程 |  |
| [LiteOS](https://github.com/LiteOS/LiteOS) | Huawei LiteOS是华为面向物联网领域开发的一个基于实时内核的轻量级操作系统 | [官网](http://developer.huawei.com/ict/cn/site-iot/product/liteos) |
| [Hue](https://github.com/zenangst/Hue) | 🎨色相是您永远需要的多功能着色工具 ||
| [WechatKit](https://github.com/Xinguang/WechatKit) | 一种快速实现微信第三方登录的框架 | [文档](https://xinguang.github.io/WechatKit) |
| [Hodor](https://github.com/Aufree/Hodor) | Hodor 是一套可让你的应用快速支持**本地化**的解决方案, 允许你在应用内直接更改应用语言而无需退出应用, 类似微信 |  |
| [Guide-to-Swift-Strings-Sample-Code](https://github.com/Flight-School/Guide-to-Swift-Strings-Sample-Code) | 该存储库包含《[飞行学校Swift字符串指南](https://flight.school/books/strings)》中使用的示例代码 |  |
| [Unicoder4Mac](https://github.com/gifjoke/Unicoder4Mac) | Swift实现，Mac端字符串编码、解码小工具 | [官网](http://unicoder.cn/) |
| [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) | 一个非常容易使用的蓝牙库,适用于ios和os |  |
| [PromiseKit](https://github.com/mxcl/PromiseKit) | Promises简化了异步编程，使您可以腾出时间专注于更重要的事情。它们易于学习，易于掌握，并且代码更清晰，可读性更好 ||
| [Permission](https://github.com/delba/Permission) | 权限公开了一个统一的API，可以在iOS上请求权限 |  |
| [PermissionScope](https://github.com/nickoneill/PermissionScope) | 智能iOS权限UI和统一的API |  |
| [Pastel](https://github.com/cruisediary/Pastel) | 🎨像Instagram这样的渐变动画效果；🎨自定义渐变色 |  |
| [aws-sdk-ruby](https://github.com/aws/aws-sdk-ruby) | [官方](https://aws.amazon.com/sdk-for-ruby/)的适用于Ruby的AWS开发工具包 |  |
| [Knuff](https://github.com/KnuffApp/Knuff) | Apple推送通知服务（APN）的调试应用程序 |  |
| [Async](https://github.com/duemunk/Async) | Swift中的语法糖用于[Grand Central Dispatch](https://developer.apple.com/library/prerelease/ios/documentation/Performance/Reference/GCD_libdispatch_Ref/index.html)中的异步调度 |  |
| [Texture](https://github.com/TextureGroup/Texture) | 流畅的iOS应用程序异步用户界面，了解[AsyncDisplayKit](https://github.com/facebookarchive/AsyncDisplayKit) ||
| [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift) | 响应式编程 ||
| [DeviceKit](https://github.com/devicekit/DeviceKit) | DeviceKit是UIDevice的值类型替换 |  |
| [SwiftKotlin](https://github.com/angelolloqui/SwiftKotlin) | 将Swift代码转换为Kotlin的工具 |  |
| [SocialSDK](https://github.com/GagSquad/SocialSDK) | iOS实现新浪、微信、QQ登录、分享功能，Share，ShareSDK，高仿友盟SocialSDK UI 实现，可自定义UI实现 |  |
| [SwiftJavaScriptCore](https://github.com/YanlongMa/SwiftJavaScriptCore) | Swift使用JavaScriptCore与JS进行交互 | [博客](http://www.mayanlong.com/) |
| [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) |  无代码插入式通用库可防止键盘滑落并覆盖UITextField / UITextView。无需编写任何代码，也不需要任何设置，甚至更多|  |
| [DAKeyboardControl](https://github.com/danielamitay/DAKeyboardControl) | DAKeyboardControl仅需一行代码即可向任何视图添加键盘识别功能和滚动关闭功能 |  |
 |  |
| [wax](https://github.com/alibaba/wax) | [alibaba](https://github.com/alibaba).可让您使用[Lua](http://www.lua.org/about.html)编写本机iPhone应用程序 ||
| [openshare](https://github.com/100apps/openshare) | 不用官方SDK，利用社交软件移动客户端(微信/QQ/微博/人人/支付宝)分享/登录/支付 | [官网](http://www.gfzj.us/series/openshare/) |
| [warp-ctc](https://github.com/baidu-research/warp-ctc) | [百度](https://github.com/baidu-research)Warp-CTC是一个可以应用在CPU和GPU上高效并行的CTC代码库 （library） 介绍 CTCConnectionist Temporal Classification作为一个损失函数，用于在序列数据上进行监督式学习，不需要对齐输入数据及标签 |  |
| [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) | 一个iOS / OSX桥，用于在WKWebViews，UIWebViews和WebViews中的Obj-C和JavaScript之间发送消息 | [官网](http://marcuswest.in/) |
| [WinObjC](https://github.com/microsoft/WinObjC) | 适用于Windows的Objective-C |  |
| [homebrew-core](https://github.com/Homebrew/homebrew-core) | 🍻macOS缺少的软件包管理器 | [官网](https://brew.sh/) |
| [webkit](https://github.com/WebKit/webkit) | WebKit是一个跨平台的Web浏览器引擎。在iOS和macOS上，它支持Safari，Mail，iBooks和许多其他应用程序 | [官网](http://www.webkit.org/) |
| [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) | Swift算法俱乐部 |  |
| [swiftenv](https://github.com/kylef/swiftenv) | Swift版本管理器，允许您轻松安装并在多个版本的Swift之间切换 | [官网](https://swiftenv.fuller.li/) |
| [SwiftTask](https://github.com/ReactKit/SwiftTask) | Promise + progress + pause + cancel + retry for Swift. |  |
| [Timepiece](https://github.com/naoty/Timepiece) | Swift中直观的日期处理 |  |
| [Nimble](https://github.com/Quick/Nimble) | Swift和Objective-C的Matcher框架。灵感来自[Cedar](https://github.com/pivotal/cedar) |  |
| [ZFDownload](https://github.com/renzifeng/ZFDownload) | 断点下载，支持后台下载，再次打开程序、异常退出记录下载进度 |  |
| [go](https://github.com/golang/go) | Go编程语言 | [官网](https://golang.org/) |
| [swift](https://github.com/apple/swift) | Swift编程语言 | [官网](https://swift.org/) |
| [swift-evolution](https://github.com/apple/swift-evolution) | Swift语言所有提案 | [官网](https://apple.github.io/swift-evolution/) |
| [swift-package-manager](https://github.com/apple/swift-package-manager) | Swift编程语言的软件包管理器 |  |
| [certbot](https://github.com/certbot/certbot) | Certbot是EFF的工具，可从“加密”获取证书，并（可选）在服务器上自动启用HTTPS。它也可以充当使用ACME协议的任何其他CA的客户端 ||
| [MonkeyKing](https://github.com/nixzhu/MonkeyKing) | MonkeyKing可以帮助您将消息发布到中文社交网络 |  |
| [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) | 便捷的500多种Swift扩展集合，可提高我们的开发效率 | [官网](https://swifterswift.com/) |
| [yoga](https://github.com/facebook/yoga) | [facebook](https://github.com/facebook)的实现Flexbox的跨平台布局引擎 | [官网](https://yogalayout.com/) |
| [infer](https://github.com/facebook/infer) | Java，C，C ++和Objective-C的静态分析器 | [官网](http://fbinfer.com/) |
| [curl](https://github.com/curl/curl) | 命令行工具和库，用于使用URL语法传输数据，支持HTTP, HTTPS, FTP, FTPS, GOPHER, TFTP, SCP, SFTP, SMB, TELNET, DICT, LDAP, LDAPS, FILE, IMAP, SMTP, POP3, RTSP and RTMP. | [官网](https://curl.haxx.se/) |
| [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) | Bolts是一组低级库，旨在简化开发移动应用程序。Bolts是由Parse和Facebook设计的 |  |
| [appledoc](https://github.com/tomaz/appledoc) | Objective-C代码Apple样式文档集生成器 | [官网](http://gentlebytes.com/) |
| [jazzy](https://github.com/realm/jazzy) | 一个命令行实用程序，可为Swift或Objective-C生成文档 | [官网](https://realm.io/) |
| [linux](https://github.com/torvalds/linux) | Linux内核源代码树 |  |
| [rvm](https://github.com/rvm/rvm) | Ruby环境管理器 [RVM](https://rvm.io/) |  |
| [openssl](https://github.com/openssl/openssl) | TLS / SSL和加密库 | [官网](https://www.openssl.org/) |
| [ruby](https://github.com/ruby/ruby) | Ruby编程语言[镜像] | [官网](https://www.ruby-lang.org/) |
| [BeeHive](https://github.com/alibaba/BeeHive) | `BeeHive`是[alibaba](https://github.com/alibaba)开源的用于iOS的App模块化编程的框架实现方案，吸收了`Spring`框架`Service`的理念来实现模块间的`API`耦合 |  |
| [ReSwift](https://github.com/ReSwift/ReSwift) | Swift中的单向数据流 | [官网](http://reswift.github.io/ReSwift/) |
| [ios-snapshot-test-case](https://github.com/uber/ios-snapshot-test-case/) | 适用于iOS的快照视图单元测试；以前为[FBSnapshotTestCase](https://github.com/facebookarchive/ios-snapshot-test-case) |  |
| [ocmock](https://github.com/erikdoe/ocmock) | OCMock是模拟对象的Objective-C实现 | [官网](http://ocmock.org/) |
| [chisel](https://github.com/facebook/chisel) | Chisel是LLDB命令的集合，可帮助调试iOS应用 |  |
| [idb](https://github.com/facebook/idb) | idb是用于自动化iOS模拟器和设备的灵活命令行界面 |  |
| [glm](https://github.com/g-truc/glm) | [OpenGL Mathematics](http://glm.g-truc.net/)（GLM）是基于[OpenGL Shading Language（GLSL）规范](https://www.opengl.org/registry/doc/GLSLangSpec.4.50.diff.pdf)的图形软件的仅头C ++数学库 ||
| [GitUp](https://github.com/git-up/GitUp) | 快速，安全，无头痛地工作。您一生都想念的[Git界面](http://gitup.co/)终于来了 |  |
| [SwiftMoment](https://github.com/akosma/SwiftMoment) | 一时间和日历处理库的iOS 9+，MACOS 10.11+，tvOS 9+，watchOS 2+ | [官网](http://akosma.github.io/SwiftMoment) |
| [Surge](https://github.com/Jounce/Surge) | 一个使用Accelerate框架的Swift库，为矩阵数学，数字信号处理和图像处理提供高性能的功能 ||
| [PostalCodeValidator](https://github.com/FormatterKit/PostalCodeValidator) | 支持200多个地区的邮政编码的验证器 ||
| [google-api-objectivec-client-for-rest](https://github.com/google/google-api-objectivec-client-for-rest) | 该库由Google编写，是用于访问JSON API的灵活高效的Objective-C框架 |  |
| [docker-ipsec-vpn-server](https://github.com/hwdsl2/docker-ipsec-vpn-server) | 使用这个Docker镜像快速搭建IPsec VPN服务器。支持`IPsec/L2TP`和`Cisco IPsec`协议 ||
| [setup-ipsec-vpn](https://github.com/hwdsl2/setup-ipsec-vpn) | 在Ubuntu，Debian和CentOS上使用IPsec / L2TP和Cisco IPsec来构建自己的IPsec VPN服务器的脚本 ||
| [facebook-ios-sdk](https://github.com/facebook/facebook-ios-sdk) | 用于将Facebook平台与iOS和tvOS应用程序集成 ||
| [Apollo-11](https://github.com/chrislgarry/Apollo-11) | 阿波罗11号制导计算机（AGC）中指令模块（Comanche055）和登月模块（Luminary099）原始代码。由[虚拟AGC](http://www.ibiblio.org/apollo/)和[MIT科学博物馆](http://web.mit.edu/museum/)的伙计们完成电子化。本仓库存在的目的是存储阿波罗11号原始代码 ||
| [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) | 蓝牙套件.使用BLE在iOS / OSX设备之间轻松通信 |  |
| [ExSwift](https://github.com/pNre/ExSwift) | 一组用于标准类型和类的Swift扩展 ||
| [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) | [Swift](https://swift.org/)编写的加密组件 |  |
| [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) | [Swift](https://swift.org/)编写的加密库 |  |
| [lantern](https://github.com/getlantern/lantern) | VPN组件 |  |
| [Quick](https://github.com/Quick/Quick) | Quick是Swift和OC的行为驱动开发框架。受[RSpec](https://github.com/rspec/rspec)，[Specta](https://github.com/specta/specta)和[Ginkgo](https://github.com/onsi/ginkgo)启发 |  |
| [CareKit](https://github.com/carekit-apple/CareKit) | CareKit™是一个开放源代码软件框架，用于创建可帮助人们更好地理解和管理其健康的应用程序 |  |
| [github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator) | 从GitHub上的标签，问题，标签和拉取请求自动生成更改日志 ||
| [Chameleon](https://github.com/viccalexander/Chameleon) | Swift和Objective-C的颜色框架（渐变颜色，十六进制代码支持，图像颜色等等） |  |
| [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) | 在Objective-C和Swift中易于阅读和编写可链接动画 |  |
| [DKChainableAnimationKit](https://github.com/draveness/DKChainableAnimationKit) | 使用DSL可以在Swift上的iOS上轻松制作动画，该项目受到[JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations)的极大启发 |  |
| [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) | 这是一个通用的嵌入式解决方案，用于将文本字段移出iOS中的键盘 | [博客](http://atastypixel.com/blog/a-drop-in-universal-solution-for-moving-text-fields-out-of-the-way-of-the-keyboard/) |
| [TYDownloadManager](https://github.com/12207480/TYDownloadManager) | 下载文件管理器包装了NSURLSessionDataTask和NSURLSessionDownloadTask，提供了进度更新和状态更改 ||
| [Bolts-ObjC](https://github.com/BoltsFramework/Bolts-ObjC) | Bolts是一组低级库，旨在简化开发移动应用程序 |  |
| [Dollar](https://github.com/ankurp/Dollar) | [Dollar](https://www.dollarswift.org/)是一个Swift库，可提供有用的功能编程辅助方法，而无需扩展任何内置对象。它类似于Java中的[Lo-Dash](https://lodash.com/)或[Underscore.js](http://underscorejs.org/) |  |
| [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) | Xcode插件，可帮助您为Objective-C和Swift轻松编写文档注释 |  |
| [gulps](https://github.com/FancyPixel/gulps) | Gulps是适用于iOS和Apple Watch的开源应用程序，可让您跟踪每日的用水量 |  |
| [IntentKit](https://github.com/intentkit/IntentKit) | 在iOS应用中处理第三方URL方案的更简便方法 | [官网](http://intentkit.github.io/) |
| [iOS-WebView-JavaScript](https://github.com/shaojiankui/iOS-WebView-JavaScript) | iOS UIWebView，WKWebView与html5 JavaScript的深度交互，iOS和安卓同时与html5 JavaScript的深度交互 |  |
| [ShareKit](https://github.com/ShareKit/ShareKit) | 提供所有iPhone和iPad应用程序的共享功能 |  |
| [PushMeBaby](https://github.com/stefanhafeneger/PushMeBaby) | 您可以在iOS推送通知开发期间使用此应用，以从Mac推送设备上的通知 |  |
| [SmartPush](https://github.com/shaojiankui/SmartPush) | SmartPush,一款iOS苹果远程推送测试程序,Mac OS下的APNS工具APP,iOS Push Notification Debug App |  |
| [iHasApp](https://github.com/danielamitay/iHasApp) | iHasApp iOS框架允许您检测用户设备上已安装的应用程序 |  |
| [cloc](https://github.com/AlDanial/cloc) | cloc计算许多编程语言中源代码的空行，注释行和物理行 ||
| [ex-baiduyunpan](https://github.com/gxvv/ex-baiduyunpan) | 百度云盘企业版解除大文件限制，批量复制链接 ||
| [FileBrowser](https://github.com/marmelroy/FileBrowser) | 使用Swift编写的Finder风格的iOS文件浏览器 ||
| [wechaty](https://github.com/Wechaty/wechaty) | Wechaty是适用于微信个人帐户的Bot SDK ，可以帮助您使用6行javascript创建一个机器人，并具有包括[Linux，Windows，MacOS](https://github.com/wechaty/wechaty/actions?query=workflow%3ANPM)和[Docker](https://github.com/wechaty/wechaty/actions?query=workflow%3ADocker)在内的跨平台支持 ||

### <a name="组件-WebImage"></a> WebImage
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [YYWebImage](https://github.com/ibireme/YYWebImage) | 一个异步图像加载框架（[YYKit](https://github.com/ibireme/YYKit)的组件 ||
| [LKImageKit](https://github.com/Tencent/LKImageKit) | 一个高性能的图片框架，包括了图片控件，图片下载、内存缓存、磁盘缓存、图片解码、图片处理等一系列能力 | |
| [SDWebImage](https://github.com/SDWebImage/SDWebImage) | 具有缓存支持的异步图像下载程序，作为UIImageView类别 | [官网](https://sdwebimage.github.io/) |
| [Kingfisher](https://github.com/onevcat/Kingfisher) | 用于从网络下载和缓存图像。它为您提供了使用纯Swift方法在​​下一个应用程序中处理远程图像的机会 ||
| [FastImageCache](https://github.com/path/FastImageCache) | 快速图像缓存是一种高效，持久且最重要的快速方式，用于在iOS应用程序中存储和检索图像 |  |
| [NSGIF](https://github.com/NSRare/NSGIF) | 🔮iOS库，用于将视频转换为GIF动画 ||
| [YYImage](https://github.com/ibireme/YYImage) | 功能强大的iOS图像框架 |  |
| [libpng](https://github.com/glennrp/libpng) | 可移植网络图形支持，官方libpng存储库 | [官网](http://libpng.sf.net) |
| [APNGKit](https://github.com/onevcat/APNGKit) | 高性能和令人愉悦的方式，可在iOS中使用APNG格式播放 ||
| [ImageScout](https://github.com/kaishin/ImageScout) | Swift版[fastimage](https://pypi.org/project/fastimage/0.2.1/)。支持PNG，GIF和JPEG ||
| [ImageCompress-iOS](https://github.com/Nemocdz/ImageCompress-iOS) | 基于ImageIO支持动静态的图片压缩库 ||
| [ImageOptim](https://github.com/ImageOptim/ImageOptim) | 用于无损图像优化工具的GUI ||
| [Nuke](https://github.com/kean/Nuke) | 强大的图像加载和缓存系统 | [官网](https://kean.github.io) |
| [AlamofireImage](https://github.com/Alamofire/AlamofireImage) | AlamofireImage是Alamofire的图像组件库 |  |
| [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) | 适用于iOS的高性能动画GIF引擎 |  |
| [HanekeSwift](https://github.com/Haneke/HanekeSwift) | 用Swift编写的iOS轻量级通用缓存，对图像特别钟爱 ||
| [apng-canvas](https://github.com/davidmz/apng-canvas) | 在画布上执行[APNG](https://davidmz.github.io/apng-canvas/) |  |
| [AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer) | 一个可让您打开.car文件并浏览/提取其图像的应用程序 ||

### <a name="组件-JSONModel"></a> JSON / XML & Model
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [JSONKit](https://github.com/johnezang/JSONKit) | 一个非常高性能的Objective-C JSON库 |  |
| [KakaJSON](https://github.com/kakaopensource/KakaJSON) | Swift版[MJExtension](https://github.com/CoderMJLee/MJExtension) |  |
| [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) | SwiftyJSON使您可以轻松地在Swift中处理JSON数据 ||
| [jansson](https://github.com/akheron/jansson) | [Jansson](http://www.digip.org/jansson/)是一个C库，用于编码，解码和处理JSON数据 |  |
| [jsonmodel](https://github.com/jsonmodel/jsonmodel) | JSONModel允许快速创建智能数据模型。您可以在iOS，macOS，watchOS和tvOS应用程序中使用它。对模型类和JSON输入的自动内省大大减少了您必须编写的代码量 |  |
| [APIJSON](https://github.com/APIJSON/APIJSON) | APIJSON是一种专为API而生的 JSON网络传输协议 以及 基于这套协议实现的ORM库 | [官网](http://apijson.org/) |
| [fastjson](https://github.com/alibaba/fastjson) | Java的快速JSON解析器/生成器 | [文档](https://github.com/alibaba/fastjson/wiki) |
| [rapidjson](https://github.com/Tencent/rapidjson) | 具有SAX / DOM样式API的C ++的快速JSON解析器/生成器 | [官网](http://rapidjson.org/) |
| [HandyJSON](https://github.com/alibaba/HandyJSON) | [alibaba](https://github.com/alibaba/)的一个用于Swift语言中的JSON序列化/反序列化库 |  |
| [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) | 从服务器获取JSON,并实时自动构建以下本地应用程序 |  |
| [Argo](https://github.com/thoughtbot/Argo) | Swift的JSON解析库 | [官网](https://thoughtbot.com/) |
| [MJExtension](https://github.com/CoderMJLee/MJExtension) | JSON和模型之间的快速，便捷且非侵入式的转换框架。您的模型类不需要扩展任何基类。您无需修改​​任何模型文件 | |
| [YYModel](https://github.com/ibireme/YYModel) | 适用于iOS/OSX的高性能模型框架，它是[YYKit](https://github.com/ibireme/YYKit)的组件 |  |
| [Mantle](https://github.com/Mantle/Mantle) | Mantle使为Cocoa或Cocoa Touch应用程序编写简单的模型层变得容易 |  |
| [ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper) | ObjectMapper是用Swift编写的框架，可让您轻松地将模型对象（类和结构）与JSON相互转换 ||
| [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) | [Alamofire](https://github.com/Alamofire/Alamofire)的扩展，可使用[ObjectMapper](https://github.com/Hearst-DD/ObjectMapper/)自动将JSON响应数据转换为快速对象 |  |
| [SwiftAI](https://github.com/hhfa008/SwiftAI) | SwiftAI，聪明地编写Swift代码。SwiftAI现在可以从JSON生成Model类。支持Codable和HandyJSON |  |
| [KissXML](https://github.com/robbiehanson/KissXML) | 替代Cocoa的NSXML类集群。基于libxml。适用于iOS |  |
| [Ji](https://github.com/honghaoz/Ji) | Swift的XML / HTML解析器 |  |
| [XMLReader](https://github.com/amarcadet/XMLReader) | 基于NSXMLParser的Objective-C XML阅读器 |  |

### <a name="组件-AutoLayout"></a> AutoLayout
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [Neon](https://github.com/mamaral/Neon) | 强大的Swift程序化UI布局框架 |  |
| [masonry](https://github.com/desandro/masonry) | 🏩级联网格[布局插件](https://masonry.desandro.com/) |  |
| [SDAutoLayout](https://github.com/gsdios/SDAutoLayout) | 一行代码实现自动布局。支持单元和Tableview高度自适应，Label和ScrollView内容自适应，致力于做最简单易用的AutoLayout库。autoLayout的最简单方法。基于运行时 |  |
| [PureLayout](https://github.com/PureLayout/PureLayout) | iOS和OS X Auto Layout的终极API-极其简单，功能强大。与Objective-C和Swift兼容 |  |
| [Stevia](https://github.com/freshOS/Stevia) | Auto Layout | [API](http://freshos.org/SteviaDocs/) |
| [Cartography](https://github.com/robb/Cartography) | 用于Swift的声明式自动布局DSL 📱📐 |  |
| [SnapKit](https://github.com/SnapKit/SnapKit) | 适用于iOS和OS X的Swift自动布局DSL | [官网](http://snapkit.io/) |
| [AutoLayout](https://github.com/johnlui/AutoLayout) | 一个自动布局组件 |  |

### <a name="组件-缓存"></a> 缓存
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [YYCache](https://github.com/ibireme/YYCache) | 适用于iOS的高性能缓存框架。它是[YYKit](https://github.com/ibireme/YYKit)的组件 |  |
| [TMCache](https://github.com/TumblrArchive/TMCache) | 适用于iOS和OS X的快速并行对象缓存（不再维护） |  |
| [STMURLCache](https://github.com/ming1016/STMURLCache) | iOS预加载Web页面方案 ||
| [MMKV](https://github.com/Tencent/MMKV) | 基于 mmap 内存映射的 key-value 组件，底层序列化/反序列化使用 protobuf 实现，性能高，稳定性强。从 2015 年中至今在微信上使用，其性能和稳定性经过了时间的验证 ||
| [keychain-swift](https://github.com/evgenyneu/keychain-swift) | 辅助功能，用于在iOS，macOS，tvOS和WatchOS的钥匙串中存储文本 |  |
| [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) | 适用于iOS，watchOS，tvOS和macOS的Keychain的简单Swift包装器 ||
| [SwiftKeychainWrapper](https://github.com/jrendel/SwiftKeychainWrapper) | 一个简单的iOS钥匙串包装器，可让您以类似于“用户默认设置”的方式使用它 |  |

### <a name="组件-Color"></a> Color
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [Colours](https://github.com/bennyguitar/Colours) | 一组漂亮的预定义颜色和一组颜色方法，使您的iOS / OSX开发工作更加轻松 |  |
| [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) | 使用RGBA十六进制字符串创建颜色的便捷方法 |  |
| [DynamicColor](https://github.com/yannickl/DynamicColor) | 可以在Swift和SwiftUI中轻松操纵颜色 | [博客](http://cocoadocs.org/docsets/DynamicColor) |
| [UIImageColors](https://github.com/jathu/UIImageColors) | 适用于UIImage和的iTunes样式的颜色提取器NSImage。它获取最主要和最突出的颜色 |  |

### <a name="组件-IAP"></a> 应用内充值
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) | SwiftyStoreKit是适用于iOS 8.0 +，tvOS 9.0+和macOS 10.10+的轻量级In App Purchases框架 |  |
| [MKStoreKit](https://github.com/MugunthKumar/MKStoreKit) | 这是MKStoreKit的6.1版。仅适用于iOS 8+。MKStoreKit 6是一个完整的改进，与以前的MKStoreKit版本不兼容。但是，重构应该相当简单 |  |
| [CargoBay](https://github.com/mattt/CargoBay) | [StoreKit](http://developer.apple.com/library/ios/#documentation/StoreKit/Reference/StoreKit_Collection/)是进行[应用内购买](https://developer.apple.com/library/IOS/documentation/NetworkingInternet/Conceptual/StoreKitGuide/Introduction.html)的Apple框架。很好，但是边缘有些粗糙 |  |
| [IAPHelper](https://github.com/saturngod/IAPHelper) | 苹果在应用购买中的IAP助手。它使用ARC和块来简化使用 |  |
| [RMStore](https://github.com/robotmedia/RMStore) | 适用于应用内购买的轻量级iOS库 |  |
| [APKit](https://github.com/wilddylan/APKit) | **IAP**组件 |  |
| [FLPayManager](https://github.com/gitkong/FLPayManager) | 项目中支付一般都有支付宝支付以及微信支付，此工具类就是统一管理支付宝和微信支付，自动根据传参进行跳转不同的支付方式 |

## <a name="数据存储"></a>数据存储
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [wcdb](https://github.com/Tencent/wcdb) | [腾讯](https://github.com/Tencent/)开源的一个高效、完整、易用的移动数据库框架，基于[SQLCipher](https://github.com/sqlcipher/sqlcipher)，支持iOS, macOS和Android |  |
| [fmdb](https://github.com/ccgus/fmdb) | 这是一个围绕[SQLite](http://sqlite.org/)的Objective-C包装器 |  |
| [GRDB.swift](https://github.com/groue/GRDB.swift) | 用于SQLite数据库的工具包，重点是应用程序开发 | [官网](http://groue.github.io/GRDB.swift/) |
| [firebase-ios-sdk](https://github.com/firebase/firebase-ios-sdk) | 该存储库包含Firebase iOS SDK源的子集 | [官网](https://firebase.google.com/) |
| [Valet](https://github.com/square/Valet) | Valet使您可以安全地将数据存储在iOS，tvOS，watchOS或macOS钥匙串中，而无需了解钥匙串的工作原理。这简单。我们承诺 |  |
| [realm-cocoa](https://github.com/realm/realm-cocoa) | Realm是一个移动数据库：替代了Core Data＆SQLite | [官网](https://realm.io/) |
| [rocksdb](https://github.com/facebook/rocksdb) | [facebook](https://opensource.facebook.com)提供快速可存储的可嵌入(闪存和RAM存储)持久键值存储的库 | [官网](http://rocksdb.org) |
| [presto](https://github.com/prestodb/presto) | 用于大数据的Presto分布式SQL查询引擎 | [官网](http://prestodb.github.io/) |
| [druid](https://github.com/alibaba/druid) | 阿里巴巴数据库事业部出品，为监控而生的数据库连接池 | [wiki](https://github.com/alibaba/druid/wiki) |
| [pouch](https://github.com/alibaba/pouch) | [alibaba](https://github.com/alibaba)的高效的企业级容器引擎 | [官网](https://pouchcontainer.io/) |
| [Disk](https://github.com/saoudrizwan/Disk) | 一个功能强大且简单的文件管理库，考虑了Apple的[iOS数据存储指南](https://developer.apple.com/icloud/documentation/data-storage/index.html)。磁盘使用CodableSwift 4中引入的新协议来发挥其最大的优势，它使您能够持久保存结构，而不必担心编码/解码。磁盘还可以帮助您以最少的一行代码将图像和其他数据类型保存到磁盘 |  |
| [CoreStore](https://github.com/JohnEstropia/CoreStore) | 一个对CoreData的包装，提供了数据安全的特性，CoreStore现在是[Swift Source Compatibility](https://swift.org/source-compatibility/#current-list-of-projects)项目的一部分 |  |
| [](https://github.com/stephencelis/SQLite.swift) | [SQLite3](http://www.sqlite.org/)上的类型安全的[Swift](https://swift.org/)语言层；[SQLite.swift](https://github.com/stephencelis/SQLite.swift)提供了对SQL语句语法和意图的编译时置信度 |  |
| [GYDataCenter](https://github.com/Zepo/GYDataCenter) | 建立在[FMDB](https://github.com/ccgus/fmdb)之上。它提供了面向对象的接口，同时仍然具有使用原始SQL的灵活性 |  |
| [SugarRecord](https://github.com/modo-studio/SugarRecord) | SugarRecord是一个持久性包装器，旨在以更简单的方式使用诸如CoreData之类的持久性解决方案 |  |
| [FileKit](https://github.com/nvzqz/FileKit) | 一个Swift框架，可用于简单且富有表现力的文件管理 | [文档](https://nvzqz.github.io/FileKit/docs/) |
| [WordPress-iOS](https://github.com/wordpress-mobile/WordPress-iOS) | 适用于iOS的WordPress-官方存储库 | [官网](http://ios.wordpress.org/) |
| [wire-ios](https://github.com/wireapp/wire-ios) | Wire移动应用程序具有一个架构层，我们称为同步引擎。客户端层处理移动应用程序中显示的所有数据。它使用后端处理网络通信和身份验证，推送通知，数据本地缓存，客户端业务逻辑，使用音频视频库进行信号传输，加密和解密（使用较低级别的加密库）以及其他零碎的内容 |  |
| [osquery](https://github.com/osquery/osquery) | 一个由SQL驱动的操作系统检测，监视和分析框架。适用于Linux，macOS，Windows和FreeBSD | [官网](https://osquery.io/) |
| [YapDatabase](https://github.com/yapstudios/YapDatabase) | YapDatabase是一个集合/键/值存储，还有更多。它在sqlite之上构建，面向Swift和Objective-C开发人员，目标是macOS，iOS，tvOS和watchOS |  |
| [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) | 超级棒极了！轻松获取核心数据！该项目已停止维护，已由Core Data本身取代 |  |
| [RestKit](https://github.com/RestKit/RestKit) | RestKit是一个现代的Objective-C框架，用于在iOS和Mac OS X上实现RESTful Web服务客户端。它提供了一个功能强大的[对象映射](https://github.com/RestKit/RestKit/wiki/Object-mapping)引擎，该引擎与[Core Data](http://developer.apple.com/library/mac/#documentation/cocoa/Conceptual/CoreData/cdProgrammingGuide.html)无缝集成，并提供了一组简单的网络原语来映射建立在顶部的HTTP请求和响应。的[AFNetworking](https://github.com/AFNetworking/AFNetworking)。它具有一组经过精心设计的优雅的API，这些API使访问和建模RESTful资源感到不可思议 |  |
| [SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults) | [SwiftyUserDefaults](http://radex.io/swift/nsuserdefaults/static)通过将富有表现力的Swifty API与静态类型的优点相结合，使用户默认值易于使用。在一个位置定义键，轻松使用值类型，并获得额外的安全性和免费的便捷编译时检查 |  |

## <a name="音视频"></a>音视频
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [RecordMyScreen](https://github.com/coolstar/RecordMyScreen) | 即使在未越狱的iPhone上也要记录显示内容 |  |
| [openmeeting2](https://github.com/onlycoder/openmeeting2) | openmeeting2视频会议，仿QQ群视频，实现多人视频，多人语音，文字聊天，表情，共享PPT功能，自由发言，主持人控制发言，按F2发言三种语音模式 ,客户端使用vs2010+qt4.85开发，服务器使用php+go语言，数据库采用mysql 演示系统所有密码都是123456，演示用户 8001~8010 [客户端下载地址](http://pan.baidu.com/s/1gdCikSV) [服务器下载地址](http://pan.baidu.com/s/1bnAo2zP) ,安装包压缩文件内有安装说明书 |  |
| [Bull-Live-Encoder](https://github.com/wenjiegit/Bull-Live-Encoder) | 公牛直播编码器 AND([srs-ble](https://github.com/leo-lp/srs-ble)) |  |
| [openkickflip-ios-sdk](https://github.com/hugoerg56/openkickflip-ios-sdk) | 这是最初的[Kickflip](https://github.com/Kickflip/kickflip-ios-sdk)开源项目和商业平台的[衍生产品](http://kickflip.io/) |  |
| [kickflip-python](https://github.com/Kickflip/python-kickflip) | Kickflip Python库和命令行客户端 |  |
| [facepp-ios-sdk](https://github.com/FacePlusPlus/facepp-ios-sdk) | Fce ++相关[API接口](https://www.faceplusplus.com.cn/)，更新功能：银行卡识别，车牌识别，照片美化 |  |
| [AudioStreamer](https://github.com/mattgallagher/AudioStreamer) | Mac OS X和iPhone的[流音频播放器](http://cocoawithlove.com/)类 |  |
| [LiveSDK-for-iOS](https://github.com/liveservices/LiveSDK-for-iOS) | Live SDK已被[OneDrive API](https://dev.onedrive.com/)和iOS的[OneDrive SDK](https://github.com/OneDrive/onedrive-sdk-ios)取代。所有新项目都应使用OneDrive API而不是Live SDK与OneDrive集成 |  |
| [iOSHardwareDecoder](https://github.com/stevenyao/iOSHardwareDecoder) | 这是iOS硬解码H.264视频的例子 |  |
| [eleVR-Web-Player](https://github.com/hawksley/eleVR-Web-Player) | Oculus上用于360视频的Web播放器 |  |
| [AMSmoothAlert](https://github.com/mtonio91/AMSmoothAlert) | 很酷的AlertView |  |
| [ALMoviePlayerController](https://github.com/lobianco/ALMoviePlayerController) | MPMoviePlayerController的直接替代品 |  |
| [IjkVRPlayer](https://github.com/yrom/IjkVRPlayer) | 此示例展示了基于[ijkplayer](https://github.com/Bilibili/ijkplayer)实现VR视频播放器的简单方法 ||
| [Video-Edit](https://github.com/lishichao/Video-Edit) | 视频剪辑：添加水印，裁剪，合并，添加背景音乐 |  |
| [BeautifyFaceAndDetection](https://github.com/YBYHunter/BeautifyFaceAndDetection) | 使用GPUImage实现人脸美白和人脸识别(磨皮，人脸检测) ||
| [CLiveVideo](https://github.com/wayne798/CLiveVideo) | iOS端librtmp+h264+aac实现的推流demo |  |
| [GotyeLive](https://github.com/QPlus/GotyeLive) | 亲加全民直播 ([GotyeLive](http://www.gotye.com.cn/)) —— 互动视频技术整体解决方案 |  |
| [PerchBroadcast-iOS-SDK](https://github.com/PerchLive/PerchBroadcast-iOS-SDK) | PerchBroadcast是用于直播视频的轻量级iOS SDK，旨在与[django-broadcast](https://github.com/PerchLive/django-broadcast)结合使用。该SDK在[Perch](https://www.perchlive.com/) iOS应用中使用，并且我们尝试使其尽可能通用和模块化，以提供将来的灵活性 |  |
| [iOS-H.264-hareware-encode-and-decode](https://github.com/LevyGG/iOS-H.264-hareware-encode-and-decode) | 使用视频工具箱进行H.264编码 |  |
| [linjiaMusic](https://github.com/ashen-zhao/linjiaMusic) | 模仿天天动听音乐，数据也是抓的天天动听 |  |
| [novocaine](https://github.com/alexbw/novocaine) | iOS和Mac OS X上的无痛高[性能音频](http://alexbw.github.com/novocaine/) |  |
| [YLFaceuDemo](https://github.com/Guikunzhi/YLFaceuDemo) | 一个简单的类似Faceu贴纸效果的iOS演示 |  |
| [MiaowShow](https://github.com/SunLiner/MiaowShow) | iOS视频直播项目 |  |
| [DFStreamDisplayKit](https://github.com/doumafang/DFStreamDisplayKit) | 基于GPUImage和VideoCore的直播组件 |  |
| [GPUImageBeautifyFilter](https://github.com/ClaudeLi/GPUImageBeautifyFilter) | 基于GPUImage美颜滤镜GPUImageBeautifyFilter,GPUImageBeautyFilter |  |
| [MD360Player4iOS](https://github.com/ashqal/MD360Player4iOS) | 这是一个精简库，可为iOS渲染360度全景视频。VR播放器 |  |
| [Periscope-VideoViewController](https://github.com/gontovnik/Periscope-VideoViewController) | 带有Periscope快速倒带控制的视频视图控制器 |  |
| [obs-studio](https://github.com/jp9000/obs-studio) | [OBS Studio](https://obsproject.com/)-免费和开源软件，用于实时流媒体和屏幕录制 |  |
| [OBS](https://github.com/jp9000/OBS) | Open Broadcaster软件（不建议使用：请参见[OBS Studio](https://github.com/jp9000/obs-studio)存储库） |  |
| [pili-ios-camera-recorder](https://github.com/yuyedaidao/pili-ios-camera-recorder) | PLRecorderKit 是为 pili.io 流媒体云服务提供的一套推送直播流 SDK, 旨在解决 iOS 端快速、轻松实现 iOS 设备利用摄像头直播接入，便于 pili.io 的开发者专注于产品业务本身，而不必在技术细节上花费不必要的时间 |  |
| [clappr-ios](https://github.com/clappr/clappr-ios) | iOS的可扩展媒体播放器 ||
| [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) | 类似Weico的播放器，支持竖屏模式下全屏播放 |  |
| [iOS-ffmpeg-player-iosvideokit-trial](https://github.com/tnadus/iOS-ffmpeg-player-iosvideokit-trial) | 基于FFmpeg的iOS播放器（名为[VideoKit](http://iosvideokit.com/)）是面向iOS和tvOS开发人员的功能强大的视频播放和流框架，并使用Objective-C语言进行编码。它支持播放本地和远程文件（mkv，divx，xvid，ogg，vorbis等），并支持流式传输流行的协议和格式（mms，http，rtsp，rtmp，rtp，mjpeg） ||
| [CardboardSDK-iOS](https://github.com/rsanchezsaez/CardboardSDK-iOS) | Google的[CardboardSDK](https://developers.google.com/cardboard/ios/get-started#downloading_and_building_the_app)的iOS端口（移动VR工具包） |  |
| [MTAudioStreamer](https://github.com/Coderii/MTAudioStreamer) | 基于DOUAudioStreamer设计的可断点加载，并且播放缓存与下载缓存逻辑处理节省流量的Demo |  |
| [TheAmazingAudioEngine](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine) | Cordially的Core Audio：针对iOS音频应用程序的复杂框架，因此无需构建 |  |
| [ESTMusicPlayer](https://github.com/Aufree/ESTMusicPlayer) | ESTMusicPlayer是基于DOUAudioStreamer开发的一个优雅简洁的音乐播放器 |  |
| [SwiftVideo](https://github.com/unpause-live/SwiftVideo) | 适用于Linux，macOS和iOS / iPadOS（甚至是tvOS）的视频流和处理框架 | [官网](https://www.unpause.live/) |
| [VideoCore-Inactive](https://github.com/jgh-/VideoCore-Inactive) | VideoCore是一个专为音频和视频处理以及流图设计的项目 |  |
| [SCRecorder](https://github.com/rFlex/SCRecorder) | iOS摄像头引擎，具有类似于Vine的拍击功能，可进行录制，动画滤镜，慢动作，片段编辑 |  |
| [ffmpeg-avplayer-for-ios-tvos](https://github.com/imoreapps/ffmpeg-avplayer-for-ios-tvos) | 一个小巧但功能强大的iOS和Apple TV OS影音播放器框架，基于FFmpeg库 ||
| [FaceRecognitionSystem](https://github.com/z695101385/FaceRecognitionSystem) | 基于opencv的人脸识别Demo |  |
| [HandBrake](https://github.com/HandBrake/HandBrake) | 用于Linux，Mac和Windows的开源视频代码转换器 | [博客](https://handbrake.fr) |
| [SJMP3Player](https://github.com/changsanjiang/SJMP3Player) | mp3播放器, 边下载边播放, 支持调速, 控制台操作 ||
| [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) | React Native的WebRTC模块 | [官网](https://react-native-webrtc.discourse.group/) |
| [video.js](https://github.com/videojs/video.js) | 开源HTML5和Flash视频播放器 | [官网](https://videojs.com) |
| [ROMPlayer](https://github.com/AudioKit/ROMPlayer) | AudioKit样本播放器（ROM播放器）-EXS24，声音字体，Wave播放器 | [官网](http://audiokitpro.com) |
| [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) | 使用CoreImage.framework实现[高通滤镜](https://www.google.com/search?ie=UTF-8&q=photoshop+high+pass+skin+smoothing) |  |
| [Vivid](https://github.com/YuAo/Vivid) | Apple的[Core Image](https://developer.apple.com/library/mac/documentation/GraphicsImaging/Conceptual/CoreImaging/ci_intro/ci_intro.html)框架滤镜 |  |
| [iOS-CoreImage-Swift](https://github.com/zhangao0086/iOS-CoreImage-Swift) | 滤镜库 |  |
| [hls.js](https://github.com/video-dev/hls.js) | hls.js是一个JavaScript库，可实现[HTTP Live Streaming](http://en.wikipedia.org/wiki/HTTP_Live_Streaming)客户端。它依靠[HTML5视频](http://www.html5rocks.com/en/tutorials/video/basics/)和[MediaSource扩展](http://w3c.github.io/media-source/)进行播放 |  |
| [SubtleVolume](https://github.com/andreamazz/SubtleVolume) | 一个音量指示器代替系统音量弹出窗口 |  |
| [JPVideoPlayer](https://github.com/newyjp/JPVideoPlayer) | 该库提供在高速缓存支持的视频播放器UITableView的基础AVPlayer | [博客](http://www.jianshu.com/users/e2f2d779c022/latest_articles) |
| [JSQSystemSoundPlayer](https://github.com/jessesquires/JSQSystemSoundPlayer) | 适用于iOS和OS X的可可[系统声音服务](https://developer.apple.com/library/ios/documentation/AudioToolbox/Reference/SystemSoundServicesReference/Reference/reference.html)的精美Obj-C包装器 | [官网](https://jessesquires.github.io/JSQSystemSoundPlayer/) |
| [ZFPlayer](https://github.com/renzifeng/ZFPlayer) | 支持定制任何播放器SDK和控制层 | [博客](https://www.jianshu.com/p/90e55deb4d51) |
| [ARKit-Sampler](https://github.com/shu223/ARKit-Sampler) | ARKit的代码示例 |  |
| [iina](https://github.com/iina/iina) | 适用于macOS的现代视频播放器，基于[mpv](https://github.com/mpv-player/mpv). | [微博](https://iina.io) |
| [mpv](https://github.com/mpv-player/mpv) | 命令行视频播放器 | [官网](https://mpv.io/) |
| [Swift-MMP](https://github.com/johnlui/Swift-MMP) | 使用 Swift 语言编写的 Material Design 风格的 iOS 流媒体音乐播放器，简称 MMP。基于 [DOUAudioStreamer-Swift](https://github.com/johnlui/DOUAudioStreamer-Swift) |  |
| [360VR](https://github.com/szt243660543/360VR) | 这是一个小型的VR库，可以快速帮助你构建VR应用程序 |  |
| [NeteaseCloudMusic](https://github.com/yezihaohao/NeteaseCloudMusic) | React Native 模仿网易云音乐手机客户端，兼容安卓和IOS两个平台 | [博客](https://yezihaohao.github.io/2017/10/23/ReactNative%E6%A8%A1%E4%BB%BF%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%E6%89%8B%E6%9C%BA%E5%AE%A2%E6%88%B7%E7%AB%AF%EF%BC%8C%E5%85%BC%E5%AE%B9%E5%AE%89%E5%8D%93%E5%92%8CIOS%E4%B8%A4%E4%B8%AA%E5%B9%B3%E5%8F%B0/) |
| [SwiftyCam](https://github.com/Awalz/SwiftyCam) | SwiftyCam是一个简单的Snapchat风格的iOS相机框架，可轻松捕获照片和视频 |  |
| [WebARonARKit](https://github.com/google-ar/WebARonARKit) | 一个适用于iOS的实验性应用，可让开发人员使用网络技术创建增强现实（AR）体验。一个[Android版本](https://github.com/google-ar/WebARonARCore)也已经推出 | [官网](https://developers.google.com/ar/develop/web/getting-started) |
| [SGPlayer](https://github.com/libobjc/SGPlayer) | 适用于iOS，macOS和tvOS的强大的媒体播放框架 |  |
| [Deep-Feature-Flow](https://github.com/msracver/Deep-Feature-Flow) | 视频实时识别 |  |
| [flv.js](https://github.com/bilibili/flv.js) | [bilibili](https://github.com/bilibili)的HTML5 FLV播放器 |  |
| [apprtc-ios](https://github.com/ISBX/apprtc-ios) | 基于WebRTC的本地iOS视频聊天应用 | [服务器](https://appr.tc/)，[官网](https://webrtc.org/) |
| [DOUAudioStreamer](https://github.com/douban/DOUAudioStreamer) | 豆瓣开源的基于Core Audio的流音频播放器 |  |
| [PandoraPlayer](https://github.com/ApplikeySolutions/PandoraPlayer) | 一款基于iOS的轻量级音乐播放器，基于AudioKit | [博客](https://applikeysolutions.com/) |
| [GDLiveStreaming](https://github.com/goodow/GDLiveStreaming) | 实时音频和视频直播库 |  |
| [react-360](https://github.com/facebook/react-360) | 用于创建在您的Web浏览器中运行的交互式360体验的框架 | [官网](https://facebook.github.io/react-360) |
| [howler.js](https://github.com/goldfire/howler.js) | [howler.js](https://howlerjs.com/)是现代网络的音频库。它默认为[Web Audio API](http://webaudio.github.io/web-audio-api/)，而后退为[HTML5 Audio](https://html.spec.whatwg.org/multipage/embedded-content.html#the-audio-element)。这使得在所有平台上使用JavaScript进行音频操作变得轻松可靠 |  |
| [DDDKit](https://github.com/gsabran/DDDKit) | 可支持360个视频和图片。它被设计为通用3D库 |  |
| [avcodec](https://github.com/ireader/avcodec) | 影音编码器/解码器/渲染器/播放器 |  |
| [moviepy](https://github.com/Zulko/moviepy) | MoviePy（完整[文档](http://zulko.github.io/moviepy/)）是一个用于视频编辑的Python库：剪切，串联，标题插入，视频合成（也称为非线性编辑），视频处理以及自定义效果的创建。有关使用示例，请参见[图库](http://zulko.github.io/moviepy/gallery.html) |  |
| [artoolkit5](https://github.com/artoolkit/artoolkit5) | ARToolKit v5.x |  ||
| [XJTV](https://github.com/Paulpang/XJTV) | XJ直播是一款基于Swift3.0开发的直播平台,所有接口都是通过抓包工具获得,仅供学习和交流,不用于商业用途 |  |
| [SoundManager2](https://github.com/scottschiller/SoundManager2) | 一个JavaScript声音API，支持MP3，MPEG4和HTML5音频+ RTMP，可提供可靠的跨浏览器/平台音频控制，最小为12 KB | [博客](http://www.schillmania.com/projects/soundmanager2/) |
| [opencv](https://github.com/opencv/opencv) | 开源计算机视觉库 | [官网](https://opencv.org/) |
| [cineio-broadcast-ios](https://github.com/cine-io/cineio-broadcast-ios) | 这是[cine.io](https://www.cine.io/) [Broadcast iOS SDK](https://www.cine.io/products/broadcast)。该库允许您从iOS设备到支持RTMP或HLS流的任何其他设备（iOS，Android，Web）进行实时实时视频流 |  |
| [licode](https://github.com/lynckia/licode) | 基于WebRTC和云技术的开源通信平台 | [官网](http://lynckia.com/licode) |
| [MGMiaoBo](https://github.com/LYM-mg/MGMiaoBo) | 多视频直播模式，移动直播新体验，多人秀场更好玩 |  |
| [FLWebRTCDemo](https://github.com/qq3200341/FLWebRTCDemo) | 基于webRTC的音视频通话，服务端采用开源项目[SkyRTC](https://github.com/LingyuCoder/SkyRTC)，未实现stunserver和turnserver服务器，因此NAT环境下不可使用 |  |
| [lame-ios-build](https://github.com/kewlbear/lame-ios-build) | 一个构建lame库的脚本 ||
| [muplayer](https://github.com/Baidu-Music-FE/muplayer) | 百度音乐播放内核（不再维护） | [官网](https://886.enimo.cn/muplayer/doc/) |
| [openwebrtc-examples](https://github.com/EricssonResearch/openwebrtc-examples) | 示例应用程序展示了如何使用OpenWebRTC ||
| [DotGPUBeautyFilter](https://github.com/dotEngine/DotGPUBeautyFilter) | GUPImage脸部美容滤镜 |  |
| [EasyPusher](https://github.com/EasyDarwin/EasyPusher) | 免费组件：简单、高效、稳定、免费的一款标准RTSP/RTP协议直播推送库，支持将H.264/H.265/G.711/G.726/AAC等音视频数据推送到RTSP流媒体服务器（例如EasyDarwin）进行低延时直播或者视频通信，支持Windows、Linux、ARM、Android、iOS等平台，EasyPusher配套EasyDarwin流媒体服务器、EasyPlayer RTSP播放器适用于特殊行业的低延时应急指挥需求！ [Android](https://github.com/EasyDarwin/EasyPusher-Android), [iOS](https://github.com/EasyDarwin/EasyPusher-iOS)|  |
| [EasyDarwin](https://github.com/EasyDarwin/EasyDarwin) | 高性能开源RTSP流媒体服务器，基于go语言研发，维护和优化：RTSP推模式转发、RTSP拉模式转发、录像、检索、回放、关键帧缓存、秒开画面、RESTful接口、WEB后台管理、分布式负载均衡等 | [官网](http://www.easydarwin.org/) |
| [srs](https://github.com/ossrs/srs) | 一个简单的流媒体直播集群 | [官网](https://ossrs.net/) |
| [ijkplayer](https://github.com/bilibili/ijkplayer) | 基于FFmpeg n3.4的Android/iOS视频播放器，带有MediaCodec，VideoToolbox支持 |  |
| [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace) | 一种先进的工具，用于面部标志检测，头部姿势估计，面部动作单位识别和视线估计 |  |
| [vlc](https://github.com/videolan/vlc) | VLC是一种流行的自由和开源媒体播放器和多媒体引擎 |  |
| [openh264](https://github.com/cisco/openh264) | [OpenH264](http://www.openh264.org/)是一个编解码器库，支持H.264编码和解码。它适用于WebRTC等实时应用程序 | |
| [CocoaSplit](https://github.com/zakk4223/CocoaSplit) | 流/录制您的桌面/网络摄像头以抽搐/拥有等 |  |
| [OpenEmu](https://github.com/OpenEmu/OpenEmu) | 🕹适用于macOS的复古视频游戏仿真 | [官网](https://openemu.org/) |
| [WMPlayer](https://github.com/zhengwenming/WMPlayer) | AVPlayer的封装，支持pods，手势快进、快退，全面适配全面屏，同时支持网络和本地视频的播放 ||
| [AudioKit](https://github.com/AudioKit/AudioKit) | 适用于iOS，macOS和tvOS的音频合成，处理和分析平台 | [官网](http://audiokit.io/) |
| [AWLive](https://github.com/hardman/AWLive) | 简单的iOS推流代码，视频捕获，软编码(faac，x264)，硬编码（aac，h264），横屏直播，美颜，flv编码，rtmp协议 | [博客](http://www.jianshu.com/u/1240d2400ca1) |
| [Surround360](https://github.com/facebook/Surround360) | [Facebook](https://github.com/facebook)的开源硬件和软件，用于捕获VR的立体3D 360视频。该回购包含硬件设计以及用于相机控制和渲染的软件 |  |
| [streamlink](https://github.com/streamlink/streamlink) | 用于从各种网站将流提取到您选择的视频播放器的CLI | [官网](https://streamlink.github.io/) |
| [youtube-dl](https://github.com/ytdl-org/youtube-dl) | 命令行程序，用于从YouTube.com和其他视频网站下载视频 | [官网](http://ytdl-org.github.io/youtube-dl/) |
| JiaoZiVideoPlayer([old](https://github.com/lipangit/JiaoZiVideoPlayer), [new](https://github.com/Jzvd/JiaoZiVideoPlayer)) | 高度自定义的安卓视频框架 ||
| [YTLiveStreaming](https://github.com/SKrotkih/YTLiveStreaming) | YTLiveStreaming是一个框架，用于在带有Xcode 10的Swift 4.2中使用YouTube实时流API（YouTube数据API v3）在YouTube上创建实时广播和视频流 |  |
| [YUGPUImageHighPassSkinSmoothing](https://github.com/YuAo/YUGPUImageHighPassSkinSmoothing) | 使用GPUImage实现高斯滤镜 |  |
| [BMPlayer](https://github.com/BrikerMan/BMPlayer) | 本项目是基于`AVPlayer`使用`Swift`封装的视频播放器，方便快速集成 | [官网](https://eliyar.biz/) |
| [SGMediaKit](https://github.com/libobjc/SGMediaKit) | SGMediaKit是一个以视频，音频播放为核心的媒体资源处理框架 |  |
| [AudioPlayer](https://github.com/delannoyk/AudioPlayer) | AudioPlayer是AVPlayer的语法和功能。它播放您的音频文件（本地和远程） |  |
| [grumble](https://github.com/mumble-voip/grumble) | 备用[Mumble](http://mumble.info/grumble)服务器 |  |
| [Swift-Radio-Pro](https://github.com/analogcode/Swift-Radio-Pro) | Swift Radio是一款开源广播电台应用程序，具有强大而专业的功能 |  |
| [apprtc](https://github.com/webrtc/apprtc) | 基于[WebRTC](https://github.com/webrtc/)的视频聊天演示应用程序。该项目目前处于暂停状态，维护需求最少。[开发人员指南](https://docs.google.com/document/d/1tn1t6LW2ffzGuYTK3366w1fhTkkzsSvHsBnOHoDfRzY/edit?pli=1#heading=h.e3366rrgmkdk) |  |
| [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) | **XCDYouTubeKit**是适用于iOS，tvOS和macOS的YouTube视频播放器 |  |
| [gvr-ios-sdk](https://github.com/googlevr/gvr-ios-sdk)| 适用于iOS的[Google VR SDK](http://developers.google.com/vr/ios/)，有一个适用于iOS和Android NDK 的新开源[Cardboard SDK](https://developers.google.com/cardboard)，它提供了简化的API，改进的设备兼容性以及内置的查看器配置文件QR码扫描功能 ||
| [openwebrtc](https://github.com/EricssonResearch/openwebrtc) | 基于[GStreamer](http://gstreamer.freedesktop.org/)的跨平台WebRTC客户端框架 | [官网](http://www.openwebrtc.org/) |
| [VRDemo-Swift](https://github.com/Huanhoo/VRDemo-Swift) | VRDemo是用Swift3.0配合OpenGL ES实现的360度全景播放器，本Demo参考了[HTY360Player](https://github.com/hanton/HTY360Player)和[SGPlayer](https://github.com/libobjc/SGPlayer)的实现方式，并拆了一些功能类，简单的实现了播放器的大体功能 |  |
| [HTY360Player](https://github.com/hanton/HTY360Player) | 开源iOS 360度全景视频播放器 ||
| [openHEVC](https://github.com/OpenHEVC/openHEVC) | HEVC解码器 | [官网](http://openhevc.github.io/openHEVC/) |
| [FreeStreamer](https://github.com/muhku/FreeStreamer) | 适用于iOS和OS X的低内存占用的流式音频播放器 | [官网](http://muhku.github.io/FreeStreamer/) ||
| [HysteriaPlayer](https://github.com/StreetVoice/HysteriaPlayer) | 有用的基本播放器功能 |  |
| [EZAudio](https://github.com/syedhali/EZAudio) | 基于Core Audio的iOS和macOS音频可视化框架，对进行实时，低延迟音频处理和可视化的任何人都非常有用 |  |
| [SlateVideo360](https://github.com/islate/SlateVideo360) | iOS VR Player支持360度视频和Google Cardboard |  |
| [TDAudioPlayer](https://github.com/tonyd256/TDAudioPlayer) | 一个用于播放来自HTTP或NSInputStream源的流的库。最初的动机来自于在MultiPeer Connectivity应用程序中通过NSInputStreams流音频的需求，并且还演变为支持HTTP流 |  |
| [muaz-khan/WebRTC-Experiment](https://github.com/muaz-khan/WebRTC-Experiment) | [WebRTC](https://www.webrtc-experiment.com/)，WebRTC和WebRTC。这里的一切都与WebRTC有关！！ |  |
| [TBPlayer](https://github.com/suifengqjn/TBPlayer) | 视频边下边播播，把播放器播放过的数据流缓存到本地，支持重置。采用avplayer |  |
| [BeautifyFaceDemo](https://github.com/Guikunzhi/BeautifyFaceDemo) | 一个基于GPUImage的实时面部美化的简单演示 |  |
| [LeanCloudLiveKit-iOS](https://github.com/leancloud/LeanCloudLiveKit-iOS) | LiveKit是一个专门为视频直播业务提供的一个UI组件，展示如何将[IM](https://github.com/leancloud/ChatKit-OC)模块添加到Live应用 |  |
| [linke](https://github.com/stlndm/linke) | 本项目实现了一个作为一个直播App的基本功能，本地视频流采集，播放，美颜，礼物，点赞出心等。提供一个构造思路，很久没有更新了，望谅解！🤡 |  |
| [apple-tv](https://github.com/Auntie-Player/apple-tv) | 一个Apple TV应用程序，可从BBC访问点播节目 |  |
| [IM_APP](https://github.com/zhuwensheng1987/IM_APP) | IOS视频聊天使用ffmpeg库crtmpserver作为中间转流服务器 |  |
| [HLS-Demo](https://github.com/yangchao0033/HLS-Demo) | IOS HLS视频直播[样例](http://www.jianshu.com/p/8f99202ccb89) |  |
| [simplest_ffmpeg_mobile](https://github.com/leixiaohua1020/simplest_ffmpeg_mobile) | Android/IOS/WinPhone中的[ffmpeg示例](http://leixiaohua1020.github.com/) |  |
| [MetalAcc](https://github.com/wangjwchn/MetalAcc) | 使用Swift编写的Metal的基于GPU的媒体处理库 |  |
| [ScreenRecord](https://github.com/topws/ScreenRecord) | iOS 9.0 新增的接口，屏幕录制，游戏内声音录制，可以选择是否启用麦克风录入周边环境的声音 |  |
| [DPFaceRecognition](https://github.com/dapiaowudi/DPFaceRecognition) | iOS人脸识别 |  |
| [AudioUnitSample](https://github.com/StevenKuo/AudioUnitSample) | 使用remoteIO audioUnit播放流音频 |  |
| [JSIMWebrtcOverMQTT](https://github.com/wenghengcong/JSIMWebrtcOverMQTT) | 利用MQTT当做共振通道，实现Webrtc的视频通话 |  |
| [AppRTCDemo](https://github.com/YK-Unit/AppRTCDemo) | 用于iOS客户端演示的WebRTC。PS：它使用XMPP构建信令服务 |  |
| [TPAACAudioConverter](https://github.com/michaeltyson/TPAACAudioConverter) | 易于使用的Objective-C包装器，用于AAC音频转换 |  |
| [AudioUnitSample](https://github.com/leo-lp/AudioUnitSample-1) | RemoteIO和多通道混音器音频单元的用法示例 |  |
| [douyuTV](https://github.com/xiaomaxuetu/douyuTV) | 实现了斗鱼TV直播视频的播放，播放器采用的是36氪的三方开源播放器,播放源是(Http Live streaming) |  |
| [iOSEchoCancellation](https://github.com/lixing123/iOSEchoCancellation) | 具有/不具有回声消除功能的实时记录和播放示例 |  |
| [ASScreenRecorder](https://github.com/alskipp/ASScreenRecorder) | 将iOS屏幕内容记录为.mp4视频文件 |  |
| [Eleven](https://github.com/sinabio/Eleven) | 一个简单而强大的视频播放器。支持m4v，wmv，3gp，mp4，mov，avi，mkv，mpeg，mpg，flv，VOB格式，输入任何HTTP，RTSP，RTMP，RTP地址播放网络流媒体或直播.11个播放器使用ffmpeg |  |
| [iOSP2PVideoStreaming](https://github.com/trentbrooks/iOSP2PVideoStreaming) | 具有OF前端的iOS设备之间的P2P视频流的各种测试/示例 |  |
| [AirCame](https://github.com/chenliming777/AirCame) | 视频直播，先要配置red5服务器，通过rtmp流将h264数据与aac数据上传服务器，做到直播的效果 |  |
| [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) | 将AR的高精度与GPS数据的规模相结合 ||
| [回到顶部](#Indexes) | 描述 | 备注 |
| [obs-studio](https://github.com/obsproject/obs-studio) | OBS Studio-免费和开源软件，用于实时流媒体和屏幕录制 | [官网](https://obsproject.com/) |
| [GPUImage](https://github.com/BradLarson/GPUImage) | GPUImage框架是BSD许可的iOS库，可让您将GPU加速的滤镜和其他效果应用于图像，实时摄像机视频和电影 ||
| [GPUImage2](https://github.com/BradLarson/GPUImage2) | GPUImage 2是[GPUImage框架](https://github.com/BradLarson/GPUImage)的第二代，这是一个开源项目，用于在Mac，iOS和现在的Linux上执行GPU加速的图像和视频处理。最初的GPUImage框架是用Objective-C编写的，并且针对Mac和iOS，但是此最新版本完全是用Swift编写的，也可以针对Linux和支持Swift代码的未来平台 |  |
| [GPUImage3](https://github.com/BradLarson/GPUImage3) | 用于使用Metal进行GPU加速的视频和图像处理 ||
| [SayHi](https://github.com/illuspas/SayHi) | 本地音频记录/播放（OpenSL ES）和speex编码/解码，由rtmp传输 |  |
| [SayHey](https://github.com/illuspas/SayHey) | Rtmp协议speex编码网络音频聊天的iOS版 |  |
| [kickflip-ios-example](https://github.com/Kickflip/kickflip-ios-example) | 集成[Kickflip iOS SDK](http://kickflip.io/)的示例项目，可实现超级便捷的直播 |  |
| [kickflip-ios-sdk](https://github.com/Kickflip/kickflip-ios-sdk) | 该[Kickflip](http://kickflip.io/)平台为iOS应用程序的完整视频广播解决方案 |  ||
| [SRTHaishinKit.swift](https://github.com/shogo4405/SRTHaishinKit.swift) | 通过SRT for iOS的摄像头和麦克风流媒体库 |  |
| [Live](https://github.com/ltebean/Live) | 一个直播应用程序，包含了iOS客户端和服务器 |  |
| [ios-live-sdk](https://github.com/upyun/ios-live-sdk) | UPYUN 直播 SDK。播放器、采集器、推流器统一集成，功能完备接口简练，可以快速安装使用。采集与音视频处理模块开源，灵活性强可以满足复杂定制需求 | [官网](http://docs.upyun.com/live/) |
| [anyRTC-RTMP-OpenSource](https://github.com/anyRTC/anyRTC-RTMP-OpenSource) | RTMP 推流器，RTMP(HLS)秒开播放器，跨平台（Win,IOS,Android） | [官网](https://www.anyrtc.io/) |
| [StreamingKit](https://github.com/tumtumtum/StreamingKit) | 适用于iOS和Mac OSX的音频播放和流媒体库 |  |
| [SkyRTC](https://github.com/LingyuCoder/SkyRTC) | 服务器端的webRTC库，用于在浏览器中建立实时通信 |  |
| [SkyRTC-demo](https://github.com/LingyuCoder/SkyRTC-demo) | 一个使用[SkyRTC](https://github.com/LingyuCoder/SkyRTC)和[SkyRTC-client](https://github.com/LingyuCoder/SkyRTC-client)构建浏览器中音频，视频，文字聊天室的演示 |  |
| [HaishinKit.swift](https://github.com/shogo4405/HaishinKit.swift) | 通过RTMP，适用于iOS的HLS，macOS，tvOS的摄像头和麦克风流媒体库 |  |
| [KSYLiveiOSSDK](https://github.com/xxfenxx/KSYLiveiOSSDK) | **KSYLiveSDK for iOS**是基于RTMP的推流器 |  |
| [LMLiveStreaming](https://github.com/chenliming777/LMLiveStreaming) | IOS Live，H264和AAC硬编码，支持GPUImage Beauty，rtmp和flv传输，网络丢失帧弱，动态切换速率 |  |
| [LiveVideoCoreSDK](https://github.com/runner365/LiveVideoCoreSDK) | 基于IOS的手机视频直播SDK |  |
| [kxmovie](https://github.com/kolyvan/kxmovie) | 基于[FFmpeg](http://ffmpeg.org/index.html)的iOS电影播放器​​ |  |
| [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) | iOS Live Kit，H264和AAC硬编码，支持GPUImage Beauty，rtmp传输，网络丢帧弱，动态切换率高 |  |
| [Tencent-NOW](https://github.com/ChinaArJun/Tencent-NOW) | 🔥视频直播:仿腾讯旗下 < NOW > 直播 斗鱼 抖音 火山视频 花椒 熊猫 YY 陌陌 映客 直播APP ||
| [srs-librtmp](https://github.com/ossrs/srs-librtmp) | SRS的客户端库srs-librtmp ||
| [LFRtmp](https://github.com/liuf1986/LFRtmp) | 一个全开源的纯OC实现的RTMP推流SDK支持AAC、H264、美颜滤镜、AMF编解码 |  |
| [librtmpex](https://github.com/suxinde2009/librtmpex) | librtmp的改进版本 ||
| [rtmp-wrapper](https://github.com/minsikzzang/rtmp-wrapper) | 适用于iOS的librtmp包装器类 |  |
| [librtmp-for-ipv6](https://github.com/zhenwu1981/librtmp-for-ipv6) | librtmp 运行在ipv6和ipv4的网络下 compile： ./build-librtmp.sh |  |
| [rtmp_streamer_for_ios](https://github.com/Vbytes/rtmp_streamer_for_ios) | 推送h264,AAC rtmp 流到流媒体服务器，包含美颜算法和自适应码率，低延时 |  |
| [pili-librtmp](https://github.com/pili-engineering/pili-librtmp) | [七牛云音视频客户端团队](https://github.com/pili-engineering)维护的一个rtmp协议库 ||
| [mumble](https://github.com/mumble-voip/mumble) | Mumble是在Qt和Opus之上编写的面向游戏玩家的语音聊天程序 | [官网](https://www.mumble.info/) |
| [mumble](https://github.com/mumble-voip/mumble) | [Mumble](https://www.mumble.info/)是一款开源，低延迟，高质量的语音聊天软件，主要用于游戏时使用 |  |
| [mumble-iphoneos](https://github.com/mumble-voip/mumble-iphoneos) | 适用于基于iOS的设备的[Mumble](https://www.mumble.info/)客户端，专注于游戏的社交语音聊天实用程序 ||
| [mumblekit](https://github.com/mumble-voip/mumblekit) | 适用于iOS和Mac OS X的基于Objective-C的[Mumble](http://mumble-voip.github.com/mumblekit/)客户端框架，[Mumble](http://mumble.info/)是专注于游戏的社交语音聊天实用程序 ||
| [libmumble](https://github.com/mumble-voip/libmumble) | libmumble是一种尝试编写用于实现[Mumble](http://mumble.info/)客户端的跨平台C ++库的尝试 ||
| [mumble-releng](https://github.com/mumble-voip/mumble-releng) | [Mumble](http://mumble.info/)的一个发布引擎 |  |
| [mumble-opus](https://github.com/mumble-voip/opus) | [Opus](https://github.com/xiph/opus)的git存储库的镜像 |  |
| [mumo](https://github.com/mumble-voip/mumo) | [mumo](https://wiki.mumble.info/wiki/Mumo)是Mumble主持人框架，它简化了通过Ice连接到Mumble服务器的插件的开发。mumo处理基本的ICE连接，并包含基本的模块加载和消息多路复用 |  |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) | [FFmpeg](https://ffmpeg.org/)用于处理多媒体内容（例如音频，视频，字幕和相关元数据）的库和工具的集合 ||
| [FFmpeg-iOS-build-script](https://github.com/kewlbear/FFmpeg-iOS-build-script) | 这是一个Shell脚本，用于为iOS和tvOS应用程序构建FFmpeg库 |  |

## <a name="优化/性能调优/ipa瘦身"></a>优化/性能调优/ipa瘦身
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) | 有助于分析iOS内存使用情况的iOS工具 |  |
| [QT4i](https://github.com/Tencent/QT4i) | [Tencent](https://github.com/Tencent).QT4i（适用于iOS的快速测试）是适用于iOS应用程序的QTA测试自动化驱动程序 |  |
| [xctool](https://github.com/facebook/xctool) | 苹果公司xcodebuild的扩展，可以更轻松地测试iOS和macOS应用程序 |  |
|[Pecker](https://github.com/woshiccm/Pecker) | 是一个自动检测无用代码的工具，它基于 IndexStoreDB 和 SwiftSyntax。 | [Twitter](https://twitter.com/Roy78463507) | 
| [MTHawkeye](https://github.com/meitu/MTHawkeye) | MTHawkeye是iOS下的调试优化辅助工具集，旨在帮助iOS开发者提升开发效率、辅助优化性能体验 | |
| [matrix](https://github.com/Tencent/matrix) | 一款微信研发并日常使用的应用性能接入框架，支持iOS, macOS和Android。 Matrix通过接入各种性能监控方案，对性能监控项的异常数据进行采集和分析，输出相应的问题分析、定位与优化建议，从而帮助开发者开发出更高质量的应用 | |
| [FengNiao](https://github.com/onevcat/FengNiao) | 一个简单的命令行工具，用于从Xcode项目中删除未使用的图像资源文件 ||
| [iOS-Performance-Optimization](https://github.com/skyming/iOS-Performance-Optimization) | 关于iOS 性能优化梳理、内存泄露、卡顿、网络、GPU、电量、 App 包体积瘦身、启动速度优化等、Instruments 高级技巧、常见的优化技能 ||
| [UnusedClasses](https://github.com/yuanzhi545/UnusedClasses) |  ||
| [Peek](https://github.com/shaps80/Peek) | 代码设计规范检查 | [官网](http://shaps.me/peek) |
| [LSUnusedResources](https://github.com/tinymind/LSUnusedResources) | 一个Mac App，用于在XCode项目中查找未使用的图像和资源 ||
| [fastlane](https://github.com/fastlane/fastlane) | 🚀自动构建和发布iOS和Android应用程序的最简单方法 | [官网](https://fastlane.tools) |
| [OOMDetector](https://github.com/Tencent/OOMDetector) | 一个iOS内存监控组件，应用此组件可以帮助你轻松实现OOM监控、大内存分配监控、内存泄漏检测等功能 ||
| [dSYMTools](https://github.com/answer-huang/dSYMTools) | dSYM分析 ||
| [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) | iOS 平台的自动内存泄漏检测工具，引进 MLeaksFinder 后，就可以在日常的开发，调试业务逻辑的过程中自动地发现并警告内存泄漏 | [wiki](http://wereadteam.github.io/2016/07/20/MLeaksFinder2/) |
| [GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift) | 在状态栏上方显示FPS，CPU和内存使用情况，设备型号，应用和iOS版本，并通过委托报告FPS，CPU和内存使用情况 ||
| [SwiftLint](https://github.com/realm/SwiftLint) | 一个用于强制检查 Swift 代码风格和规定的一个工具，基本上以 [GitHub's Swift 代码风格指南](https://github.com/github/swift-style-guide)为基础 | [官网](https://realm.io/) |
| [ResponseDetective](https://github.com/netguru/ResponseDetective) | 🕵一个非侵入性框架，用于拦截应用程序和服务器之间的所有传出请求和传入响应，以进行调试 ||
| [Nocilla](https://github.com/luisobo/Nocilla) | 适用于iOS和OS X的惊人的HTTP存根。测试HTTP请求从未如此简单 | [Twitter](https://twitter.com/luisobo) |
| [KSCrash](https://github.com/kstenerud/KSCrash) | iOS下崩溃监控 ||
| [HockeySDK-iOS](https://github.com/bitstadium/HockeySDK-iOS) | 实现了在您的iOS应用程序中使用HockeyApp的支持 | [官网](http://hockeyapp.net/releases) |
| [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) | 保留周期是造成内存泄漏的最常见方法之一。创建保留周期非常容易，而且往往很难发现它。FBRetainCycleDetector的目标是帮助在运行时查找保留周期。该项目的功能受到[Circle](https://github.com/mikeash/Circle)的影响 ||
| [iOS-qiniu-tools](https://github.com/leo-lp/iOS-qiniu-tools) | iOS手机网络测试工具 ||
| [NetworkFlow-iOS](https://github.com/1043426357/NetworkFlow-iOS) | 监控流量、测网速 ||
| [android-netdiag](https://github.com/qiniu/android-netdiag) | 网络诊断库，支持Ping/TcpPing/Rtmp/TraceRoute/DNS/外部IP/外部DNS ||
| [iOS-netdiag](https://github.com/qiniu/iOS-netdiag) | 网络诊断库，支持Ping/TcpPing/Rtmp/TraceRoute/DNS/外部IP/外部DNS ||
| [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) | 利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志 ||
| [net-diagnosis](https://github.com/mediaios/net-diagnosis) | 网络诊断SDK，支持对ip和域名的ping,traceroute(udp,icmp协议)，支持tcp ping, 端口扫描，nslookup,局域网活跃ip扫描等功能 ||
| [SimplePing](https://developer.apple.com/library/archive/samplecode/SimplePing/Introduction/Intro.html#//apple_ref/doc/uid/DTS10000716) | Apple的**SimplePing**封装了ping的功能，它利用resolve host，create socket(send & recv data), 解析ICMP包验证checksum等实现了ping功能。并且支持iPv4和iPv6 ||
| [happy-dns-objc](https://github.com/qiniu/happy-dns-objc) | 调用系统底层Dns解析库，可以使用114 等第三方dns解析，也可以集成dnspod等httpdns。另外也有丰富的hosts 域名配置 ||

## <a name="HTTP/TCP/UDP"></a>HTTP/TCP/UDP/SMTP/XMPP等网络协议库
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [Alamofire](https://github.com/Alamofire/Alamofire) | Swift中的优雅HTTP网络 |  |
| [Moya](https://github.com/Moya/Moya) | 用Swift编写的网络抽象层 | [官网](https://moya.github.io/) |
| [AFNetworking](https://github.com/AFNetworking/AFNetworking) | 一个适用于iOS，macOS，watchOS和tvOS的令人愉悦的网络库。它建立在[Foundation URL Loading System](https://developer.apple.com/documentation/foundation/url_loading_system)的基础上，扩展了Cocoa中内置的强大的高级网络抽象 | [官网](http://afnetworking.com/) |
| [YTKNetwork](https://github.com/yuantiku/YTKNetwork) | 猿题库iOS研发团队基于[AFNetworking](https://github.com/AFNetworking/AFNetworking)封装的iOS网络库，其实现了一套High Level的API，提供了更高层次的网络访问抽象 |  |
| [aurora-imui](https://github.com/jpush/aurora-imui) | 通用IM聊天UI组件，已经同时支持Android/iOS/RN ||
| [phxrpc](https://github.com/Tencent/phxrpc) | PhxRPC是微信后台团队推出的一个非常简洁小巧的RPC框架，编译生成的库只有450K | [文档](https://github.com/Tencent/phxrpc/wiki) |
| [dubbo](https://github.com/apache/dubbo) | Apache Dubbo是一个高性能的，基于Java的开源RPC框架 | [官网](http://dubbo.apache.org/) |
| [swoole-src](https://github.com/swoole/swoole-src) | 一个为PHP用C和C++编写的基于事件的高性能异步&协程并行网络通信引擎 | [官网](https://www.swoole.com/) |
| [tcpcopy](https://github.com/session-replay-tools/tcpcopy) | 在线请求复制工具，也是tcp流重播工具，适用于真实测试，性能测试，稳定性测试，压力测试，负载测试，冒烟测试等 ||
| [tcpdive](https://github.com/fastos/tcpdive) | TCP性能分析工具 |  |
| [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) | 适用于Mac和iOS的Objective-C中的XMPP框架 |  |
| [Hedwig](https://github.com/onevcat/Hedwig) | Hedwig是一个Swift软件包，它提供了一组高级API，使您可以轻松地将电子邮件发送到SMTP服务器 |  |
| [pomelo-ioschat](https://github.com/NetEase/pomelo-ioschat) | Pomelo [iOS客户端](https://github.com/NetEase/pomelo-iosclient)的聊天演示[服务器](https://github.com/NetEase/chatofpomelo) |  |
| [NEKit](https://github.com/zhuhaow/NEKit) | 网络扩展框架的工具包。下一代[libnekit](https://github.com/zhuhaow/libnekit) | [官网](https://zhuhaow.github.io/NEKit) |
| [ChatKit-OC](https://github.com/leancloud/ChatKit-OC) | LeanCloud OC SDK ||
| [swift-sdk](https://github.com/leancloud/swift-sdk) | LeanCloud Swift SDK | [demo](https://github.com/leancloud/swift-sdk-demo) |
| [Starscream](https://github.com/daltoniam/Starscream) | Swift中符合标准的WebSocket（[RFC 6455](http://tools.ietf.org/html/rfc6455)）库 |  |
| [RealReachability](https://github.com/dustturtle/RealReachability) | 网络实时监控 |  |
| [kcp](https://github.com/skywind3000/kcp) | KCP是一个快速可靠协议，能以比 TCP浪费10%-20%的带宽的代价，换取平均延迟降低 30%-40%，且最大延迟降低三倍的传输效果 |  |
| [Reachability](https://github.com/tonymillion/Reachability) | 适用于iOS和MacOS的ARC和GCD兼容可达性类。替代苹果可及性 |  |
| [Reachability.swift](https://github.com/ashleymills/Reachability.swift) |替代了Apple的Reachability示例，该示例在Swift中使用闭包进行了重写 |  |
| [SGWiFiUpload](https://github.com/Soulghost/SGWiFiUpload) | 通过WiFi上传文件。通过WiFi上传文件 |  |
| [happy-dns-objc](https://github.com/qiniu/happy-dns-objc) | 可以调用114等第三方dns解析，也可以集成dnspod等httpdns。另外也有丰富的主机域名配置 |  |
| [pomelo-iosclient](https://github.com/NetEase/pomelo-iosclient) | 网易[Pomelo](https://github.com/NetEase/pomelo)的iOS客户端库 |  |
| [HTTPDNS-Swift](https://github.com/yourtion/HTTPDNS-Swift) | HTTPDNS库Swift实现，支持DNSPod，AliYunDNS，Google等 | [Pods](http://cocoapods.org/pods/HTTPDNS-Swift) |
| [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) | 适用于Mac OS X或iOS应用程序的小型，轻巧，可嵌入式HTTP服务器 |  |
| [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) | 适用于Mac和iOS的异步套接字网络库 | [wiki](https://github.com/robbiehanson/CocoaAsyncSocket/wiki) |
| [SwiftAsnycSocket](https://github.com/chouheiwa/SwiftAsnycSocket) | Swift版的[CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) ||
| [swift-nio](https://github.com/apple/swift-nio) | 跨平台的异步事件驱动的网络应用程序框架，用于快速开发可维护的高性能协议服务器和客户端，类似于[Netty](https://netty.io/). | [官网](https://apple.github.io/swift-nio/) |
| [grpc-swift](https://github.com/grpc/grpc-swift) | 基于gRPC-Core的gRPC Swift版 将很快被基于[SwiftNIO](https://github.com/apple/swift-nio)的重新实现所取代 ||
| [grpc](https://github.com/grpc/grpc) | gRPC是一个现代的，开源的，高性能的远程过程调用（RPC）框架，可以在任何地方运行。gRPC使客户端和服务器应用程序可以透明地进行通信，并简化了连接系统的构建 | [官网](https://grpc.io) |
| [protobuf](https://github.com/protocolbuffers/protobuf) | Google的数据交换格式 | [官网](https://developers.google.com/protocol-buffers/) |
| [swift-protobuf](https://github.com/apple/swift-protobuf) | Swift版protobuf ||
| [SocketRocket](https://github.com/facebook/SocketRocket) | 符合标准的Objective-C WebSocket客户端库 |  |
| [BlueSocket](https://github.com/IBM-Swift/BlueSocket) | [IBM](https://github.com/IBM-Swift)的使用Swift软件包管理器的Swift套接字框架。适用于iOS，macOS和Linux |  |
| [SwiftSocket](https://github.com/swiftsocket/SwiftSocket) | SwiftSocket库为服务器或客户端上基于套接字的连接提供了易于使用的接口。同时支持TCP和UDP套接字 |  |
| [SwifterSockets](https://github.com/Balancingrock/SwifterSockets) | Swift中用于Swiftfire Web服务器项目的套接字实用程序的集合 | [博客](http://swiftfire.nl/) |
| [GCDWebServer](https://github.com/swisspol/GCDWebServer) | 适用于iOS，macOS和tvOS的＃1 HTTP服务器（还包括基于Web的上传器和WebDAV服务器） ||
| [socket.io](https://github.com/socketio/socket.io) | 实时应用程序框架（Node.JS服务器） | [官网](http://socket.io/) |
| [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) | 适用于iOS/OS X的Socket.IO客户端 |  |
| [fastsocket](https://github.com/fastos/fastsocket) | Fastsocket是一个高度可扩展的套接字及其Linux内核的基础网络实现。凭借直线线性可扩展性，Fastsocket可以在多核计算机中提供出色的性能。此外，它非常易于使用和维护。结果，它已经被部署在新浪的生产环境中 |  |
| [SwiftWebSocket](https://github.com/tidwall/SwiftWebSocket) | 适用于iOS和Mac OSX的符合WebSocket（[RFC 6455](https://tools.ietf.org/html/rfc6455)）客户端库 |  |
| [go-socket.io](https://github.com/googollee/go-socket.io) | go-socket.io是Golang中[Socket.IO](http://socket.io/) 的实现，[Golang](http://socket.io/)是一个实时应用程序框架 |  |
| [socket.io-client-cpp](https://github.com/socketio/socket.io-client-cpp) | Socket.IO客户端的C ++ 11实现 |  |
| [sockets](https://github.com/vapor-community/sockets) | 🔌 非阻塞TCP套接字层，具有事件驱动的服务器和客户端 |  |
| [Swift-SMTP](https://github.com/IBM-Swift/Swift-SMTP) | Swift SMTP邮件客户端 | |

## <a name="日志收集"></a>日志收集
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) | Swift的彩色，灵活，轻量级日志记录。支持控制台，文件和云平台，非常适合开发和发布 | [博客](https://swiftybeaver.com) |
| [Puree-Swift](https://github.com/cookpad/Puree-Swift) | 过滤、缓冲、批处理、重试 ||
| [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) | XCGLogger是用于Swift项目的原始调试日志模块 ||
| [glog](https://github.com/google/glog) | [Google](https://github.com/google)日志记录模块的C ++实现 ||
| [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) | 适用于Mac和iOS的快速，简单，功能强大且灵活的日志记录框架 | [官网](https://cocoalumberjack.github.io/) |

## <a name="骨骼/帧动画"></a>骨骼/帧动画
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [SVGAPlayer-iOS](https://github.com/yyued/SVGAPlayer-iOS) | 播放After Effects/Animate CC(Flash)动画 | [官网](http://svga.io/) |
| [SVGA-AEConverter](https://github.com/svga/SVGA-AEConverter) |  |  |
| [SVGA-FLConverter](https://github.com/svga/SVGA-FLConverter) |  | [官网](http://svga.io/docute/#/Plug-in) |
| [SVGA-Format](https://github.com/svga/SVGA-Format) | SVGA 是一种动画格式，类似于 Dragonbones / CreateJS ||
| [spine-runtimes](https://github.com/EsotericSoftware/spine-runtimes) | Spine的2D骨骼动画播放库 | [官网](http://esotericsoftware.com/) |
| [lottie-react-native](https://github.com/react-native-community/lottie-react-native) | 适用于React Native的Lottie组件（[iOS](https://github.com/airbnb/lottie-ios)和[Android](https://github.com/airbnb/lottie-android)） |  |
| [lottie-ios](https://github.com/airbnb/lottie-ios) | 一个iOS库，用于原生渲染After Effects矢量动画 | [官网](http://airbnb.io/lottie/) |
| [lottie-android](https://github.com/airbnb/lottie-android) | 在Android和iOS，Web和React Native上本地渲染After Effects动画 | [官网](http://airbnb.io/lottie/) |
| [AiyaEffectsIOS](https://github.com/aiyaapp/AiyaEffectsIOS) | 宝宝特效 AiyaEffectsSDK 涵盖Android、iOS两个平台，基于自主研发的人脸识别模块，作为一款动态贴纸和动画特效高效渲染的解决方案 | [官网](http://www.aiyaapp.com/product/bbtx) |
| [ParticlesLoadingView](https://github.com/BalestraPatrick/ParticlesLoadingView) | SpriteKit粒子动画播放器 ||
| [Gifu](https://github.com/kaishin/Gifu) | Gifu向UIKit添加了基于协议，性能感知的动画GIF支持 |  |

## <a name="主题DarkMode"></a>主题（Dark Mode）
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [DKNightVersion](https://github.com/draveness/DKNightVersion) | 管理色彩、整合白天/夜间多个主题 |  |
| [SwiftTheme](https://github.com/wxxsw/SwiftTheme) | iOS 8+ 主题/换肤, 暗色模式 ||
| [JXTheme](https://github.com/pujiaxin33/JXTheme) | 主题、换肤、暗黑模式 ||
| [QMUITheme](https://github.com/Tencent/QMUI_iOS/tree/master/QMUIKit/QMUIComponents/QMUITheme) | 使用 QMUITheme 实现换肤并适配 iOS 13 Dark Mode ||
| [Gestalt](https://github.com/regexident/Gestalt) | 一款轻巧的iOS应用主题库，支持动画主题切换 ||
| [LEETheme](https://github.com/lixiang1994/LEETheme) | 优雅的主题管理库- 一行代码完成多样式切换 ||
| [NightNight](https://github.com/draveness/NightNight) | 将夜间模式集成到快速项目的优雅方式 ||

## <a name="SwiftUI"></a>SwiftUI
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [fluid-slider](https://github.com/Ramotion/fluid-slider) | 带有弹出气泡的滑块小部件，显示选定的精确值 | | 
|[swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) | Swift UI库，iOS组件和动画 ||
| [Render](https://github.com/alexdrone/Render) | CoreRender是一种受UI启发的SwiftUI API（与iOS 10+和ObjC兼容） ||

## <a name="完整APP"></a>完整APP
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [cli](https://github.com/cli/cli) | GitHub上新官方命令行工具 ||
| [stretchly](https://github.com/hovancik/stretchly) | **定时休息提醒软件**，可以设置, 全屏, 设置小休息间隔和正常间隔, 改变界面颜色和提示音等 ||
| [12306](https://github.com/testerSunshine/12306) | 12306智能刷票，订票 ||
| [py12306](https://github.com/pjialin/py12306) | 🚂12306 购票助手，支持集群，多账号，多任务购票以及Web页面管理 ||
| [easy12306](https://github.com/zhaipro/easy12306) | 使用机器学习算法完成对12306验证码的自动识别 ||
| [StoveFireiOSMenu](https://github.com/joeshang/StoveFireiOSMenu) | 炉火餐饮系统 iPad 点餐端 ||
| [kityminder](https://github.com/fex-team/kityminder) | [百度脑图](http://naotu.baidu.com/) ||
| [SwiftHN](https://github.com/Dimillian/SwiftHN) | Swift中的Hacker News阅读器 ||
| [JokeClient-Swift](https://github.com/YANGReal/JokeClient-Swift) | 用糗事百科的API简单做成一个糗百客户端，可以浏览各种段子，浏览搞笑图片，查看精彩评论等 ||
| [DesignerNewsApp](https://github.com/MengTo/DesignerNewsApp) | 以设计师的身份构建[Swift App](http://designcode.io/) ||
| [youtube-iOS](https://github.com/aslanyanhaik/youtube-iOS) | Youtube iOS模板由[Haik Aslanyan](https://twitter.com/aslanyanhaik)开发并用Swift 3编写 |  |
| [stackedit](https://github.com/benweet/stackedit) | 浏览器内Markdown[编辑器](https://stackedit.io/) | |
| [MVVMReactiveCocoa](https://github.com/leichunfeng/MVVMReactiveCocoa) | 该存储库包含GitBucket iOS应用程序的源代码。它是GitHub的移动客户端应用程序，使用[MVVM](http://en.wikipedia.org/wiki/Model_View_ViewModel)架构模式和一些很棒的框架（例如[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)，[Mantle](https://github.com/MantleFramework/Mantle)，[octokit.objc](https://github.com/octokit/octokit.objc)等）进行[构建](https://github.com/octokit/octokit.objc)。您可以免费将其用于任何目的 |  |
| [GitHawk](https://github.com/GitHawkApp/GitHawk) | 适用于GitHub的最佳iOS应用 | [官网](http://githawk.com) |
| [iSparta](https://github.com/iSparta/iSparta) | APNG，WebP转换器 | [官网](http://isparta.github.io/) |
| [TinyPNG4Mac](https://github.com/kyleduo/TinyPNG4Mac) | 这是[TinyPNG](https://tinypng.com/)的Mac客户端。TinyPNG提供了PNG图片的有损压缩服务。使用TinyPNG4Mac，你可以通过简单的拖拽完成对PNG图片的压缩，无需打开浏览器，无需手动下载图片 ||
| [macdown](https://github.com/MacDownApp/macdown) | 适用于macOS的开源Markdown编辑器 | [官网](https://macdown.uranusjr.com/) |
| [flipper](https://github.com/facebook/flipper) | Flipper(以前称为Sonar)是用于在iOS和Android上调试移动应用程序的平台。通过简单的桌面界面可视化，检查和控制您的应用程序。照常使用Flipper或使用插件API对其进行扩展 |  |
| [WWDC](https://github.com/insidegui/WWDC) | 适用于MacOS的非官方WWDC应用程序 | [官网](https://wwdc.io) |
| [desktop](https://github.com/desktop/desktop) | GitHub Desktop是一个基于[Electron](https://electron.atom.io/)的开源GitHub应用。它是用[TypeScript](http://www.typescriptlang.org/)编写的，并使用[React](https://facebook.github.io/react/). | [官网](https://desktop.github.com/) |
| [hyper](https://github.com/zeit/hyper) | 基于Web技术的终端 | [官网](https://hyper.is) |
| [xi-editor](https://github.com/xi-editor/xi-editor) | 现代的编辑器，后端使用Rust编写 | [官网](https://xi-editor.io) |
| [xi-mac](https://github.com/xi-editor/xi-mac) | xi-editor mac前端 |  |
| [atom](https://github.com/atom/atom) | 可入侵的文本编辑器 | [官网](https://atom.io) |
| [electron](https://github.com/electron/electron) | Electron框架使您可以使用JavaScript，HTML和CSS编写跨平台的桌面应用程序 | [官网](https://electronjs.org/) |
| [ios-oss](https://github.com/kickstarter/ios-oss) | 适用于iOS的Kickstarter。随时随地将新想法带入生活 | [官网](https://www.kickstarter.com/mobile) |
| [firefox-ios](https://github.com/mozilla-mobile/firefox-ios) | 适用于iOS的Firefox | |
| [m-cli](https://github.com/rgcr/m-cli) | MacOS命令行工具 |  |
| [echo](https://github.com/labstack/echo) | 高性能，简约的Go Web框架 | [官网](https://echo.labstack.com/) |
| [vim-go](https://github.com/fatih/vim-go) | Go Vim开发插件 | [官网](https://www.patreon.com/bhcleek) |
| [PHPHub-iOS](https://github.com/Aufree/PHPHub-iOS) | PHPHub是一个用Laravel 4.2编写的论坛项目，也是建立PHP＆Laravel China社区的项目 |  |
| [U17](https://github.com/spicyShrimp/U17) | 精仿有妖气漫画 |  |
| [editor.md](https://github.com/pandao/editor.md) | 基于CodeMirror和jQuery＆Marked的开源可嵌入在线降价编辑器（组件） | [官网](http://editor.md.ipandao.com/) |
| [ofodemo](https://github.com/yagamis/ofodemo) | 仿ofo小黄车的iOS版本源码,教学视频请见[小波说雨燕](http://www.xiaoboswift.com/) |  |
| [Celluloid](https://github.com/100mango/Celluloid) | 照片扩展程序 ||
| [brew](https://github.com/Homebrew/brew) | MacOS下软件包管理器 | [官网](https://brew.sh/) |
| [CocoaPods](https://github.com/CocoaPods/CocoaPods) | CocoaPods管理Xcode项目的依赖关系 | [官网](https://cocoapods.org/) |
| [Carthage](https://github.com/Carthage/Carthage) | 一个简单，分散的Cocoa依赖性经理 |  |
| [LyricsX](https://github.com/ddddxxx/LyricsX) | 🎶 iTunes，Spotify，Vox和Audirvana Plus的歌词 ||
| [TSWeChat](https://github.com/hilen/TSWeChat) | 一种微信替代品，已更新为Swift5 |  |
| [Tars](https://github.com/TarsCloud/Tars) | Tars是腾讯从2008年到今天一直在使用的后台逻辑层的统一应用框架TAF（Total Application Framework），目前支持C++,Java,PHP,Nodejs,Go语言。该框架为用户提供了涉及到开发、运维、以及测试的一整套解决方案，帮助一个产品或者服务快速开发、部署、测试、上线。 它集可扩展协议编解码、高性能RPC通信框架、名字路由与发现、发布监控、日志统计、配置管理等于一体，通过它可以快速用微服务的方式构建自己的稳定可靠的分布式应用，并实现完整有效的服务治理 ||
| [BaiduFM-Swift](https://github.com/belm/BaiduFM-Swift) | 百度FM ||
| [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG) | ShadowsocksX软件 ||
| [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) | [Shadowsocks-libev](https://shadowsocks.org/)是适用于嵌入式设备和低端盒的轻型安全SOCKS5代理 | [官网](http://shadowsocks.org/en/download/servers.html) |
| [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android) | 适用于Android的Shadowsocks客户端 |  |
| [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows) | 适用于windows的Shadowsocks软件 |  |
| [Coding-iOS](https://github.com/Coding/Coding-iOS) | 客户端源代码app | [官网](https://coding.net/u/coding/p/Coding-iOS/git) |
| [atom](https://github.com/atom/atom) | 可入侵的文本编辑器，建立在[Electron](https://github.com/electron/electron)的基础上，并基于我们喜欢的最喜欢的编辑器的所有内容。我们将其设计为高度可定制的，但使用默认配置仍可实现 | [官网](https://atom.io/) |
| [vscode](https://github.com/microsoft/vscode) | 该存储库（“Code-OSS”）是我们（Microsoft）开发[Visual Studio Code](https://code.visualstudio.com/)产品的地方 |  |
| [git](https://github.com/git/git) | Git是一种快速，可扩展的分布式修订版本控制系统，具有异常丰富的命令集，该命令集提供高级操作和对内部组件的完全访问权限 |  |
| [hhvm](https://github.com/facebook/hhvm) | 用于执行用Hack编写的程序的虚拟机 | [官网](https://hhvm.com/) |
| [Signal-iOS](https://github.com/signalapp/Signal-iOS) | Signal是一个免费的开源消息应用程序，用于与朋友进行简单的私人通信。也可以在[Android](https://github.com/signalapp/signal-android)和[Desktop](https://github.com/signalapp/signal-desktop)上使用 ||
| [Bilibili_Wuxianda](https://github.com/MichaelHuyp/Bilibili_Wuxianda) | 高仿Bilibili客户端 - ( ゜- ゜)つロ 乾杯~ |  |
| [radiant-player-mac](https://github.com/radiant-player/radiant-player-mac) | 🎶将Google Play音乐变成与Mac集成的独立，精美的应用程序 |  |
| [ChatSecure-iOS](https://github.com/ChatSecure/ChatSecure-iOS) | [ChatSecure](https://chatsecure.org/)是用于iOS 的免费开放源代码[XMPP](https://en.wikipedia.org/wiki/XMPP)消息客户端，它集成了[OTR](https://en.wikipedia.org/wiki/Off-the-Record_Messaging)和[OMEMO](https://en.wikipedia.org/wiki/OMEMO)加密消息传递支持，并具有可选的集成支持，以支持通过[Tor](https://en.wikipedia.org/wiki/Tor_(anonymity_network))网络的连接 ||
| [breadwallet-ios](https://github.com/voisine/breadwallet-ios) | 比特币钱包 | [官网](http://breadapp.com/) |
| [vim](https://github.com/vim/vim) | Vim是旧的UNIX编辑器Vi的大大改进版本。添加了许多新功能：多级撤消，语法突出显示，命令行历史记录，在线帮助，拼写检查，文件名完成，块操作，脚本语言等。还提供了图形用户界面（GUI） |  |
| [JSONExport](https://github.com/Ahmed-Ali/JSONExport) | Mac OS X的桌面应用程序，它使您能够使用自己喜欢的语言将JSON对象作为关联的构造函数，实用程序方法，setter和getter导出为模型类 ||
| [Aerial](https://github.com/JohnCoates/Aerial) | Aero是基于新Apple TV屏幕保护程序的Mac屏幕保护程序，可显示Apple在纽约，旧金山，夏威夷，中国等地拍摄的空中电影 |  |
| [BackgroundMusic](https://github.com/kyleneideck/BackgroundMusic) | 背景音乐，一种macOS音频实用程序：自动暂停您的音乐，设置单个应用的音量并录制系统音频 |  |
| [CocoaPods-app](https://github.com/CocoaPods/CocoaPods-app) | CocoaPods.app 的首要目标是提供功能齐全且独立的CocoaPods安装，而不是要求用户通过RubyGems或Homebrew安装CocoaPods。除了易于安装之外，它还包括易于更新的功能 |  |
| [CocoaPods-Specs](https://github.com/CocoaPods/Specs) | 该存储库包含公共[CocoaPods](https://github.com/CocoaPods/CocoaPods)规范 ||
| [Dash-iOS](https://github.com/Kapeli/Dash-iOS) | Dash文件阅读器 |  |
| [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) | 用于iOS的漂亮的RTF所见即所得编辑器，带有突出显示语法的源代码视图 |  |
| [Yep](https://github.com/CatchChat/Yep) | [Yep](https://soyep.com/)是一个轻巧而轻巧的社交应用程序，围绕“ Meeting Genius”主题，使用户可以查找特定领域的专家或其他学习者 |  |
| [codelf](https://github.com/unbug/codelf) | 搜索工具可帮助开发人员解决命名问题 |  |
| [CodeHub](https://github.com/CodeHubApp/CodeHub) | CodeHub是在任何iPhone，iPod Touch和iPad设备上浏览和维护GitHub存储库的最佳方法！密切关注您的项目，可以查看从拉取请求到对最新更改集中的单个文件差异进行注释的所有内容。CodeHub以时尚高效的设计将GitHub带到您的指尖 |  |
| [electronic-wechat](https://github.com/geeeeeeeeek/electronic-wechat) | 💬在macOS和Linux上更好的微信。内置[电子](https://github.com/atom/electron) |  |
| [eidolon](https://github.com/artsy/eidolon) | [装饰主义](https://www.artsy.net/)拍卖亭应用 |  |
| [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) | NXDrawKit是一个用于iPhone的简单易用但有用的绘图工具 |  |
| [VPNOn](https://github.com/lexrus/VPNOn) | 像英雄一样打开您的VPN |  |
| [DSLolita](https://github.com/sam408130/DSLolita) | 模仿新浪微博做的一款app，有发送博文，评论，点赞，私聊功能 |  |
| [iBBS-Swift](https://github.com/iAugux/iBBS-Swift) | Swift中的BBS客户端 |  |
| [Eleven](https://github.com/kaixinsoft/Eleven) | Eleven Player是一款简单而强大的视频播放器。请使用ffmpeg |  |
| [meituan](https://github.com/lookingstars/meituan) | 高仿美团iOS版，版本号5.7 ||
| [Lin](https://github.com/questbeat/Lin) | Xcode插件，可为NSLocalizedString提供自动完成功能 |  |
| [mono](https://github.com/mono/mono) | Mono是一个软件平台，旨在使开发人员可以轻松创建跨平台应用程序。它是Microsoft .NET Framework的开源实现，基于C＃的ECMA标准和公共语言运行时 | [博客](http://www.mono-project.com/) |

## <a name="精心收集和积累"></a>精心收集和积累（学习资料/优秀组件）
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [ios_top_1000](https://github.com/iamdaiyuan/ios_top_1000) | 精选的iOS前1000强库的精选列表 |  |
| [awesome-animation](https://github.com/Animatious/awesome-animation) | [Animatious Group](http://anius.io/)制作的大量开源UI Motion库 |  |
| [apple-ios-samples](https://github.com/robovm/apple-ios-samples) | [苹果iOS示例](https://developer.apple.com/library/ios/navigation/#section=Resource%20Types&topic=Sample%20Code)的镜像 |  |
| [Markdown-Syntax-CN](https://github.com/riku/Markdown-Syntax-CN) | Markdown 语法[简体中文版](http://wow.kuapp.com/markdown/)（fork于[繁体中文版](http://markdown.tw/)） |  |
| [iOSTech](https://github.com/kaiyiwang/iOSTech) | 适用于iOS应用程序开发的有用工具或提示列表 |  |
| [awesome-awesomeness-zh_CN](https://github.com/justjavac/awesome-awesomeness-zh_CN) | 一份关于**“资料汇总”**的汇总 |  |
| [iOSBlogCN](https://github.com/tangqiaoboy/iOSBlogCN) | 中文 iOS/Mac 开发博客列表 |  |
| [dev-blog](https://github.com/nixzhu/dev-blog) | 翻译，开发心得或学习笔记 ||
| [swift-summary](https://github.com/jakarmy/swift-summary) | 在Playgrounds上编写的Apple Swift语言摘要 |  |
| [zh-google-styleguide](https://github.com/zh-google-styleguide/zh-google-styleguide) | Google开源项目风格指南（[中文版](http://zh-google-styleguide.readthedocs.org/)） |  |
| [DevLiveBook](https://github.com/DyncLang/DevLiveBook) | 励志成为较全的直播技术导航_AnyRTC(采集、前处理、编码、传输、解码、渲染, 推流, 拉流、连麦、直播、互动、RTMP) |  |
| [Solve-App-Store-Review-Problem](https://github.com/wg689/Solve-App-Store-Review-Problem) | ipv6,ipv6被拒绝,后台定位等审核问题的终极解决方案汇总 |  |
| [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education) | 🔥学习一些Swift |  |
| [30DaysofSwift](https://github.com/allenwong/30DaysofSwift) | 一个自学的项目，用于学习Swift |  |
| [SwiftGuide](https://github.com/ipader/SwiftGuide) | 自2014年WWDC发布Swift语言以来，[本项目](https://github.com/ipader/SwiftGuide/blob/master/2014%20letter.md)一直致力于将主流Swift中文学习、开发资源汇集于此，并且尽力紧密地跟踪、甄选优秀Swift开源项目，以方便开发者快速获得并使用 |  |
| [Programming-iOS-Book-Examples](https://github.com/mattneub/Programming-iOS-Book-Examples) | [我的书籍](http://www.tidbits.com/matt)“使用Swift的iOS 13编程基础知识”（bk1）和“编程iOS 13”（bk2）的可下载代码示例 |  |
| [iOSInterviewQuestions](https://github.com/ChenYilong/iOSInterviewQuestions) | iOS面试题集锦（附答案） |  |
| [Book-Recommend-Github](https://github.com/iOShuyang/Book-Recommend-Github) | 推荐生活当中积累的优秀Objective-C和Swift三方库 |  |
| [Learn-iOS-Swift-by-Examples](https://github.com/Lax/Learn-iOS-Swift-by-Examples) | 精心收集并分类整理的Swift开发学习资源，包括Apple官方提供的示例代码和文档，以及github上的项目和国内外开发者的技术博客 |  |
| [iOS-Weekly](https://github.com/SwiftOldDriver/iOS-Weekly) | 🇨🇳老司机iOS周报 |  |
| [iOSProject](https://github.com/NJHu/iOSProject) | 收集了一些iOS项目 ||
| [awesome](https://github.com/sindresorhus/awesome) | 😎 关于各种有趣主题的真棒列表 |  |
| [awesome-swift](https://github.com/matteocrippa/awesome-swift) | 很棒的Swift库和资源的协作列表。随时贡献！ ||
| [awesome-swift](https://github.com/Wolg/awesome-swift) | 精选的Swift框架，库和软件清单. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php). ||
| [awesome-ios-cn](https://github.com/jobbole/awesome-ios-cn) | iOS 资源大全中文版，内容包括：框架、组件、测试、Apple Store、SDK、XCode、网站、书籍等 |  |
| [awesome-ios](https://github.com/vsouza/awesome-ios) | 精选的iOS组件清单，包括Objective-C和Swift项目 | [官网](http://awesomeios.com/) |
| [awesome-ios-animation](https://github.com/ameizi/awesome-ios-animation) | 精选的iOS动画精选，包括Objective-C和Swift库 ||
| [Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit) | 精选的ARKit项目和资源的精选清单。随时贡献！ ||
| [awesome-mac](https://github.com/jaywcjlove/awesome-mac) | 收集了各种类别非常好用的Mac应用程序、软件以及工具 | [官网](https://git.io/macx) |
| [Awesome-CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) | Core ML的最大型号列表（适用于iOS 11+） | [官网](https://developer.apple.com/documentation/coreml) |
| [fantastic-ios-animation](https://github.com/onmyway133/fantastic-ios-animation) | ☔️iOS动画库的集合 | [官网](https://onmyway133.github.io/) |
| [iOS-11-by-Examples](https://github.com/artemnovichkov/iOS-11-by-Examples) | iOS 11 新API的代码示例 ||
| [iOS-10-Sampler](https://github.com/shu223/iOS-10-Sampler) | iOS 10 新API的代码示例 ||
| [iOS9AdaptationTips](https://github.com/ChenYilong/iOS9AdaptationTips) | iOS9适应系列教程 |  |
| [be-a-professional-programmer](https://github.com/stanzhai/be-a-professional-programmer) | 成为专业程序员路上用到的各种优秀资料、神器及框架.[GitBook](https://thonatos.gitbooks.io/be-a-professional-programmer/) | [博客](http://tools.stanzhai.site/) |
| [ParseSourceCodeStudy](https://github.com/ChenYilong/ParseSourceCodeStudy) | Facebook开源的Parse源码分析【系列】 ||
| [the-swift-programming-language-in-chinese](https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese) | 中文版 Apple 官方 Swift 教程《The Swift Programming Language》。[英文原版在线版](https://docs.swift.org/swift-book/) | [gitbook](https://swiftgg.gitbook.io/swift/) |
| [Swift-30-Projects](https://github.com/soapyigu/Swift-30-Projects) | 30个迷你Swift应用程序供自学 ||
| [CommonUtilLibrary](https://github.com/AbrahamCaiJin/CommonUtilLibrary) | 快速开发工具类收集 |  |
| [material-design-icons](https://github.com/google/material-design-icons) | Google提供的官方[图标集](https://www.google.com/design/spec/style/icons.html#icons-system-icons)。图标是根据[材料设计准则](https://material.io/guidelines/)设计的 ||
| [LearnOpenGLES](https://github.com/loyinglin/LearnOpenGLES) | OpenGL ES的各种尝试，有详细的博客 | [简书](http://www.jianshu.com/notebooks/2135411/latest) |
| [gitignore](https://github.com/github/gitignore) | 这是GitHub的.gitignore文件模板集合。.gitignore创建新的存储库和文件时，我们使用此列表来填充GitHub.com界面中可用的模板选择器 |  |
| [docker_practice](https://github.com/yeasy/docker_practice) | 通过实际的DevOps实践学习和理解[Docker](https://www.docker.com/)技术 | [gitbook](https://www.gitbook.com/book/yeasy/docker_practice) |
| [remote-working](https://github.com/greatghoul/remote-working) | 中国远程工作资料大全 | [社区](https://eleduck.com/?utm_source=remote-working&utm_medium=github-banner&utm_campaign=remote-working-eleduck) |
| TimLiu-iOS([OC](https://github.com/Tim9Liu9/TimLiu-iOS)， [Swift](https://github.com/Tim9Liu9/TimLiu-iOS/blob/master/Swift.md)) | iOS开发常用三方库、插件、知名博客等等 | [iOS开发路线](https://github.com/Tim9Liu9/TimLiu-iOS/blob/master/%E5%9B%BE%E8%B0%B1.jpg) |
| [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | [freeCodeCamp.org](https://www.freecodecamp.org/)的开源代码库和课程 ||
| [free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 📚免费提供的编程书籍 | [书籍](https://ebookfoundation.github.io/free-programming-books/) |
| [iOSBlog](https://github.com/ChenYilong/iOSBlog) | Posted by [微博@iOS程序犭袁](http://weibo.com/luohanchenyilong/) |  |
| [awesome-react-native](https://github.com/jondot/awesome-react-native) | 很棒的React Native组件，新闻，工具和学习资料 | [文档](http://www.awesome-react-native.com/) |
| [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) | 📱开源iOS应用的列表 ||
| [free-programming-books-zh_CN](https://github.com/justjavac/free-programming-books-zh_CN) | 📚免费的计算机编程类中文书籍 | [微博](http://weibo.com/justjavac) |
| [Material-Controls-For-iOS](https://github.com/fpt-software/Material-Controls-For-iOS) | 适用于iOS本机应用程序的许多[Google Material Design](http://www.google.com/design/spec/material-design/introduction.html)控件 ||
| [52-technologies-in-2016](https://github.com/shekhargulati/52-technologies-in-2016) | 让我们每周学习一种新技术。2016年每个星期日都有一个新技术博客 | [博客](https://shekhargulati.com/) |
| [XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets) | 一些为[Swift](https://developer.apple.com/swift/)收集的便捷代码段，所有代码段均更新为Swift 4 ||
| [Xcode-Snippets-Objc](https://github.com/Xcode-Snippets/Objective-C) | 我的Xcode库中的一些代码片段 ||
| [analyze](https://github.com/draveness/analyze) | 记录了阅读开源框架，并进行内容进行详细地分析和理解的心得 | [博客](https://draveness.me/) |
| [react-native-guide](https://github.com/reactnativecn/react-native-guide) | React Native指南汇集了各类react-native学习资源、开源App和组件 ||
| [translations](https://github.com/oldratlee/translations) | 一些不错英文资料的中文翻译 ||
| [Learn-Laravel-5](https://github.com/johnlui/Learn-Laravel-5) | Laravel 系列入门教程 ||
| [iOS-Core-Animation-Advanced-Techniques](https://github.com/qunten/iOS-Core-Animation-Advanced-Techniques) | iOS核心动画高级技术（翻译） ||
| [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) | 📖Swift 5.0中实现的设计模式 ||
| [30dayMakeOS](https://github.com/yourtion/30dayMakeOS) | 《30天自制操作系统》源码中文版。自己制作一个操作系统（[OSASK](https://github.com/yourtion/YOS)）的过程 ||
| [atswift-2016-resources](https://github.com/atConf/atswift-2016-resources) | 2016中国Swift开发者大会源文件，包括keynote, pdf 和源工程文件 ||
| [iOS-Pro](https://github.com/tangqiaoboy/iOS-Pro) | 《 iOS 开发进阶》随书示例程序和勘误 ||
| [iOSAppReverseEngineering](https://github.com/iosre/iOSAppReverseEngineering) | 全球第一本非常详尽的iOS App逆向工程技能书:) ||

## <a name="程序员日常"></a>程序员日常
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [interviews](https://github.com/kdn251/interviews) | 软件工程技术面试指南 ||
| [github-do-not-ban-us](https://github.com/1995parham/github-do-not-ban-us) | GitHub不禁止我们进入开源世界 ||
| [FinancialSupportForOpenSource](https://github.com/wizicer/FinancialSupportForOpenSource) | 开源项目挣钱实用手册 ||
| [996.ICU](https://github.com/996icu/996.ICU) | 996的工作模式 | [微博](https://996.icu) |
| [gold-miner](https://github.com/xitu/gold-miner) | [掘金翻译计划](https://juejin.im/tag/%E6%8E%98%E9%87%91%E7%BF%BB%E8%AF%91%E8%AE%A1%E5%88%92)是一个翻译优质互联网技术文章的社区，文章来源为 [掘金](https://juejin.im/) 上的英文分享文章。内容覆盖[区块链](https://github.com/xitu/gold-miner#%E5%8C%BA%E5%9D%97%E9%93%BE)、[人工智能](https://github.com/xitu/gold-miner#ai--deep-learning--machine-learning)、[Android](https://github.com/xitu/gold-miner#android)、[iOS](https://github.com/xitu/gold-miner#ios)、[前端](https://github.com/xitu/gold-miner#%E5%89%8D%E7%AB%AF)、[后端](https://github.com/xitu/gold-miner#%E5%90%8E%E7%AB%AF)、[设计](https://github.com/xitu/gold-miner#%E8%AE%BE%E8%AE%A1)、[产品](https://github.com/xitu/gold-miner#%E4%BA%A7%E5%93%81)和[其他](https://github.com/xitu/gold-miner#%E5%85%B6%E4%BB%96) 等领域，以及各大型优质 [官方文档及手册](https://github.com/xitu/gold-miner#%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3%E5%8F%8A%E6%89%8B%E5%86%8C)，读者为热爱新技术的新锐开发者 ||
| [p3c](https://github.com/alibaba/p3c) | 阿里巴巴Java编码指南pmd实现和IDE插件 | [wiki](https://github.com/alibaba/p3c/wiki) |
| [material-components-ios](https://github.com/material-components/material-components-ios) | iOS的材料组件（MDC-iOS）可帮助开发人员执行[材料设计](https://material.io/)。这些组件由Google的工程师和UX设计师的核心团队开发，可实现可靠的开发工作流程，以构建美观实用的iOS应用。[在Material Design Platform Adaptation指南中](https://material.io/guidelines/platforms/platform-adaptation.html)了解有关iOS的Material Components如何支持跨平台的设计和可用性最佳实践的更多信息 ||
| [jekyll-now](https://github.com/barryclark/jekyll-now) | 在几分钟之内建立一个Jekyll博客，而无需触摸命令行；[Jekyll](https://github.com/jekyll/jekyll)是一个静态站点生成器，非常适合GitHub托管的博客 | |
| [hexo](https://github.com/hexojs/hexo) | 一个由[Node.js](https://nodejs.org/)支持的快速，简单且功能强大的博客框架 ||
| [startbootstrap](https://github.com/BlackrockDigital/startbootstrap) | 一个免费和开源的[Bootstrap](http://getbootstrap.com/)主题和模板库 | [官网](https://startbootstrap.com/) |
| [jekyll](https://github.com/jekyll/jekyll) | 一个简单的可识别博客的静态网站生成器，非常适合个人，项目或组织网站 | [官网](https://jekyllrb.com/) |
| [hackathon-starter](https://github.com/sahat/hackathon-starter) | Node.js Web应用程序的样板库 | [官网](https://hackathon-starter.walcony.com/) |
| [nodeppt](https://github.com/ksky521/nodeppt) | nodeppt 2.0基于[webslides](https://github.com/webslides/WebSlides)，webpack，markdown-it，posthtml重构，[新效果](https://nodeppt.js.org/) ||
| [OpenLiveWriter](https://github.com/OpenLiveWriter/OpenLiveWriter) | Open Live Writer使您可以轻松地编写，预览和发布到博客 | [官网](http://www.openlivewriter.org/) |
| [objective-c-style-guide](https://github.com/nytimes/objective-c-style-guide) | Objective-C API设计指南 ||
| [swift-style-guide](https://github.com/github/swift-style-guide) | Swift API设计指南 ||
| [javascript](https://github.com/airbnb/javascript) | JavaScript API 设计指南 ||
| [google-styleguide](https://github.com/darcyliu/google-styleguide) | Google 开源项目风格指南 | [官网](http://code.google.com/p/google-styleguide/) |
| [swift-style-guide](https://github.com/raywenderlich/swift-style-guide) | raywenderlich.com的官方Swift样式指南 ||
| [CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines) |《[C ++核心准则](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)》是一组有关C++编码的经过实践检验的准则，规则和最佳实践 ||

## <a name="服务器"></a>服务器
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [kurento-media-server](https://github.com/Kurento/kurento-media-server) | 负责媒体传输，处理，加载和记录的媒体[服务器](https://www.kurento.org/) |  |
| [MonaServer](https://github.com/MonaSolutions/MonaServer) | 轻量级的RTMFP，RTMP，WebSocket和HTTP服务器 | [官网](http://monaserver.ovh/) |
| [SwiftEngine](https://github.com/swiftengine/SwiftEngine) | 基于Apple Swift的HTTP服务器。基于Swift的，一站式，防崩溃，高规模和生产级Web服务器的答案 | [官网](http://swiftengine.io) |
| [Perfect](https://github.com/PerfectlySoft/Perfect) | Swift语言服务器端软件框架 |  |
| [Perfect-Redis](https://github.com/PerfectlySoft/Perfect-Redis) | Redis客户端对[Perfect](https://github.com/PerfectlySoft/Perfect)的支持 | [官网](https://www.perfect.org/) |
| [Perfect-MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) | MySQL客户端库周围的独立Swift包装器，可访问MySQL服务器 | [官网](https://www.perfect.org/) |
| [Perfect-PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) | 围绕libpq客户端库的独立Swift包装器，可访问PostgreSQL服务器 | [官网](https://www.perfect.org/) |
| [Perfect-MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) | MongoDB数据库连接器 ||
| [PerfectDocs](https://github.com/PerfectlySoft/PerfectDocs) | 该库包含运行和使用[Perfect](https://github.com/PerfectlySoft/Perfect)所需的所有参考文档和与API参考相关的材料 ||
| [PerfectAppTemplate](https://github.com/PerfectlySoft/PerfectAppTemplate) | 为大型项目的发展提供结构。它包含一个HTTP Server配置，该配置可从预先分隔的过滤器和路由中加载，一个JSON配置加载器以及可在其中组织处理程序，对象和实用程序功能的目录 | |
| [PerfectTemplate](https://github.com/PerfectlySoft/PerfectTemplate) | [Perfect](https://www.perfect.org) Web服务器项目模板 |  |
| [Perfect-WebSockets](https://github.com/PerfectlySoft/Perfect-WebSockets) | WebSockets对Perfect的支持 |  |
| [Perfect-Notifications](https://github.com/PerfectlySoft/Perfect-Notifications) | Notifications for Perfect之iOS消息推送。此软件包为您的服务器添加了推送通知支持。向iOS/macOS设备发送通知 | [官网](https://www.perfect.org) |
| [Perfect-SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) | 围绕SQLite 3客户端库的独立Swift包装器，可访问SQLite服务器 | [官网](https://www.perfect.org/) |
| [http](https://github.com/vapor/http) | 基于Swift NIO的非阻塞，事件驱动的HTTP |  |
| [mysql-kit](https://github.com/vapor/mysql-kit) | 🐬 基于非阻塞，事件驱动套接字的纯Swift MySQL客户端 |  |
| [Kitura](https://github.com/IBM-Swift/Kitura) | Swift Web框架和HTTP服务器 | [官网](http://www.kitura.io/) |
| [vapor](https://github.com/vapor/vapor) | 服务器端Swift Web框架 | [官网](https://vapor.codes/) |
| [serf](https://github.com/hashicorp/serf) | Serf是一种用于服务发现和编排的分散式解决方案，它轻巧，高度可用且具有容错能力 | [官网](https://www.serf.io/) |
| [coturn](https://github.com/coturn/coturn) | TURN服务器是VoIP媒体流量NAT遍历服务器和网关。它也可以用作通用网络流量TURN服务器和网关。该项目是从项目[rfc5766-turn-server](https://code.google.com/p/rfc5766-turn-server/)演变而来 |  |
| [motan](https://github.com/weibocom/motan) | Motan是用于快速开发高性能分布式服务的跨语言远程过程调用（RPC）框架 |  |
| [nginx](https://github.com/nginx/nginx) | 一个高性能的HTTP和反向代理web服务器 |  |
| [lua-nginx-module](https://github.com/openresty/lua-nginx-module) | 将Lua的力量嵌入NGINX HTTP服务器 | [官网](https://openresty.org/) |
| [rocketmq](https://github.com/apache/rocketmq) | [Apache RocketMQ](https://rocketmq.apache.org/)的镜像,一个分布式消息传递和流媒体平台，具有低延迟，高性能和可靠性，万亿级容量和灵活的可伸缩性 |  |
| [mux](https://github.com/gorilla/mux) | 强大的HTTP路由器和URL匹配器，可用于构建带有以下内容的Go Web服务器🦍 | [官网](http://www.gorillatoolkit.org/pkg/mux) ||
| [gin](https://github.com/gin-gonic/gin) | Gin是用Go（Golang）编写的Web框架。它具有类似于martini的API，其性能比[httprouter](https://github.com/julienschmidt/httprouter)快40倍。如果您需要性能和良好的生产率，您会喜欢Gin | [官网](https://gin-gonic.com/) |
| [cat](https://github.com/dianping/cat) | CAT 作为服务端项目基础组件，提供了 Java, C/C++, Node.js, Python, Go 等多语言客户端，已经在美团点评的基础架构中间件框架（MVC框架，RPC框架，数据库框架，缓存框架等，消息队列，配置系统等）深度集成，为[美团点评](https://github.com/dianping)各业务线提供系统丰富的性能指标、健康状况、实时告警等 |  |
| [zipkin](https://github.com/openzipkin/zipkin) | 由Twitter公司开发并开源，Java语言实现，侵入性相对于CAT要低一点，需要对web.xml之类的配置文件做修改，但依然对代码有侵入 ||
| [pinpoint](https://github.com/naver/pinpoint) | 一个韩国团队开源的产品，运用了字节码增强技术，只需要在启动时添加启动参数即可，对代码无侵入，目前支持Java和PHP语言，底层采用HBase来存储数据，探针收集的数据粒度非常细，但性能损耗大，因其出现的时间较长，完成度也很高，应用的公司较多 ||
| [skywalking](https://github.com/apache/skywalking) | 国人开源的产品，主要开发人员来自于华为，2019年4月17日Apache董事会批准SkyWalking成为顶级项目，支持Java、.Net、NodeJs等探针，数据存储支持Mysql、Elasticsearch等，跟Pinpoint一样采用字节码注入的方式实现代码的无侵入，探针采集数据粒度粗，但性能表现优秀，且对云原生支持，目前增长势头强劲，社区活跃，中文文档没有语言障碍 ||
| [nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module) | 基于NGINX的媒体流服务器 | [博客](http://nginx-rtmp.blogspot.com/) |
| [BLSS](https://github.com/gnolizuh/BLSS) | 基于[nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module)的实时媒体流服务器 |  |
| [nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module) | 基于NGINX的媒体流服务器 | [博客](http://nginx-rtmp.blogspot.com/) |
| [media-server](https://github.com/ireader/media-server) | RTSP / RTP / RTMP / FLV / HLS / MPEG-TS / MPEG-PS / MPEG-DASH / MP4 / fMP4 ||
| [bls](https://github.com/notedit/bls) | BLS是用于Node.js的rtmp服务器框架。该服务器是在Nodejs使用的libuv I / O框架中开发的。因此，在大量客户端同时推送或拉取流数据的情况下，它的性能非常好 ||
| [tengine](https://github.com/alibaba/tengine) | [alibaba](https://github.com/alibaba)的一个网络服务器，由亚洲最大的电子商务网站[淘宝网提供](http://en.wikipedia.org/wiki/Taobao)。它基于[Nginx](http://nginx.org/) HTTP服务器，并具有许多高级功能。在包括[taobao.com](http://www.taobao.com/)和[tmall.com](http://www.tmall.com/)在内的全球前100个网站中，Tengine被证明是非常稳定和高效的 ||
| [elasticsearch](https://github.com/elastic/elasticsearch) | 分布式，RESTful搜索引擎 | [官网](https://www.elastic.co/products/elasticsearch) |
| [swifter](https://github.com/httpswift/swifter) | 用[Swift](https://developer.apple.com/swift/)编程语言编写的微型http服务器引擎 ||
| [kcptun](https://github.com/xtaci/kcptun) | A Stable & Secure Tunnel based on KCP with N:M multiplexing and FEC. Available for ARM, MIPS, 386 and AMD64 ||
| [bootstrap-datepicker](https://github.com/uxsolutions/bootstrap-datepicker) | 引导日期选择器 |  |
| [disconf](https://github.com/knightliao/disconf) | 分布式配置管理平台 | [官网](http://disconf.readthedocs.io/) |
| [janus-gateway](https://github.com/meetecho/janus-gateway) | Janus是由[Meetecho](http://www.meetecho.com/)设计和开发的一种开源通用WebRTC服务器。该版本的服务器专为Linux系统量身定制，尽管它也可以为MacOS机器编译和安装 |  |
| [Zewo](https://github.com/Zewo/Zewo) | 适用于由协程驱动的macOS和Linux上的Swift中Web服务器应用程序的轻量级库 | [官网](http://zewo.io/) |
| [jumpserver](https://github.com/jumpserver/jumpserver) | Jumpserver是全球首款完全开源的堡垒机，使用GNU GPL v2.0开源协议，是符合4A机制的运维安全审计系统 ||
| [KubeOperator](https://github.com/KubeOperator/KubeOperator) | [KubeOperator](https://kubeoperator.io/)是一个开源项目，在离线网络环境下，通过可视化Web UI在VMware，Openstack或物理机上规划，部署和运营生产等级的Kubernetes。KubeOperator是[Jumpserver](https://github.com/jumpserver/jumpserver)明星开源团队在Kubernetes领域的又一新力量 ||
| [FaceRecognitionSystemServer](https://github.com/z695101385/FaceRecognitionSystemServer) | 人脸识别系统服务器 ||
| [pomelo](https://github.com/NetEase/pomelo) | 一个用于Node.js的快速，可扩展的分布式[游戏服务器框架](http://pomelo.netease.com/) ||

## <a name="游戏引擎"></a>游戏引擎
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [2048](https://github.com/danqing/2048) | iOS版本2048，使用SpriteKit制作 |  |
| [cocos2d-x](https://github.com/cocos2d/cocos2d-x) | [Cocos2d-x](https://www.cocos.com/)是一套开放源代码，跨平台的游戏开发工具，被全球数百万开发人员使用 | [官网](http://www.cocos2d-x.org/) |
| [OpenRA](https://github.com/OpenRA/OpenRA) | 一个Libre / Free Real Time Strategy游戏引擎，支持早期的Westwood经典游戏 | |
| [libgdx](https://github.com/libgdx/libgdx) | 基于OpenGL(ES)的跨平台Java游戏开发框架，可在Windows，Linux，Mac OS X，Android，支持WebGL的浏览器和iOS上运行 | [官网](http://www.libgdx.com/) |
| [pygame](https://github.com/pygame/pygame) | 此库是跨平台的，旨在简化使用Python编写多媒体软件（例如游戏）的过程。Pygame需要Python语言和SDL多媒体库。它还可以利用其他几个流行的库 | [官网](https://www.pygame.org) |
| [boardgame.io](https://github.com/nicolodavis/boardgame.io) | 回合制游戏的开源游戏引擎 | [官网](https://boardgame.io/) |
| [GameFramework](https://github.com/EllanJiang/GameFramework) | 这实际上是一个基于Unity游戏引擎的游戏框架。它在开发过程中封装了常用的游戏模块，并在很大程度上标准化了流程，提高了开发速度并确保了产品质量 | [官网](http://GameFramework.cn/) |
| [engine](https://github.com/cocos-creator/engine) | Cocos Creator是游戏开发工具和工作流程的完整软件包，包括游戏引擎，资源管理，场景编辑，游戏预览，调试并将一个项目发布到多个平台 | [官网](http://www.cocos2d-x.org/creator) |
| [behaviac](https://github.com/Tencent/behaviac) | 游戏AI的开发框架组件，也是游戏原型的快速设计工具 | [官网](http://www.behaviac.com/) |
| [cocos2d-objc](https://github.com/cocos2d/cocos2d-objc) | 适用于iOS和OS X的Cocos2d，使用Objective-C构建 | [官网](http://www.cocos2d-objc.org) |
| [FlappySwift](https://github.com/fullstackio/FlappySwift) | Swift的Flappy Bird的iOS 8实现 | [官网](https://www.fullstackedu.com/) |
| [swift-2048](https://github.com/austinzheng/swift-2048) | Swift编写的2048小游戏 ||
| [Gearboy](https://github.com/drhelius/Gearboy) | 适用于iOS，Mac，Raspberry Pi，Windows，Linux和RetroArch的Game Boy / Gameboy Color模拟器 ||

## <a name="人工智能深度学习"></a>人工智能/深度学习
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [faceai](https://github.com/vipstone/faceai) | 一款入门级的人脸、视频、文字检测以及识别的项目. ||
| [MNNKit](https://github.com/alibaba/MNNKitDemo) | 阿里巴巴重磅开源MNNKit：基于端上推理引擎[MNN](https://github.com/alibaba/MNN)的移动端深度学习SDK，支持安卓和iOS ||
| [mace](https://github.com/XiaoMi/mace) | 小米的面向移动端的深度学习框架 ||
| [FeatherCNN](https://github.com/Tencent/FeatherCNN) | 腾讯的面向移动端的深度学习框架（腾讯 AI） ||
| [ncnn](https://github.com/Tencent/ncnn) | 腾讯的面向移动端的深度学习框架（腾讯 优图） ||
| [Paddle](https://github.com/PaddlePaddle/Paddle) | 『飞桨』核心框架，深度学习&机器学习高性能单机、分布式训练和跨平台部署 | [官网](http://www.paddlepaddle.org/) |
| [DeepLearningKit](https://github.com/DeepLearningKit/DeepLearningKit) | 适用于Apple iOS，OS X和tvOS的开源深度学习[框架](http://deeplearningkit.org/) |  |
| [Perfect-TensorFlow](https://github.com/PerfectlySoft/Perfect-TensorFlow) | 为TensorFlow的C语言接口试验性封装函数库，用于Swift在人工智能深度学习上的应用  ||
| [sonnet](https://github.com/deepmind/sonnet) | 基于[TensorFlow](https://www.tensorflow.org/)的神经网络库 | [官网](https://sonnet.dev/) |
| [neon](https://github.com/NervanaSystems/neon) | [neon](https://github.com/NervanaSystems/neon)是英特尔参考深度学习框架，致力于在所有硬件上实现[最佳性能](https://github.com/soumith/convnet-benchmarks)。专为易用性和可扩展性而设计 ||
| [shogun](https://github.com/shogun-toolbox/shogun) | 高效的机器学习框架 | [官网](http://shogun.ml) |
| [scikit-learn](https://github.com/scikit-learn/scikit-learn) | 一个基于SciPy的Python机器学习模块 | [官网](https://scikit-learn.org) |
| [kubeflow](https://github.com/kubeflow/kubeflow) | 基于Google内部机器学习管道的机器学习Cloud Native平台 | [官网文档](http://kubeflow.org/) |
| [nupic](https://github.com/numenta/nupic) | Numenta智能计算平台（NuPIC）是实现[HTM学习算法](https://numenta.com/resources/papers-videos-and-more/)的机器智能平台 ||
| [chainer](https://github.com/chainer/chainer) | 深度学习的神经网络的灵活框架 | [官网](https://chainer.org) |
| [spark](https://github.com/apache/spark) | Spark是用于大规模数据处理的统一分析引擎。它提供了Scala，Java，Python和R中的高级API，以及优化的引擎，该引擎支持用于数据分析的通用计算图。它还支持丰富的高级工具集，包括用于SQL和DataFrames的Spark SQL，用于机器学习的MLlib，用于图形处理的GraphX和用于流处理的结构化流 | [官网](https://spark.apache.org/) |
| [DeepLearningFlappyBird](https://github.com/yenchenlin/DeepLearningFlappyBird) | 深度学习 |  |
| [pattern](https://github.com/clips/pattern) | 用于Python的Web挖掘模块，具有用于抓取，自然语言处理，机器学习，网络分析和可视化的工具 | [官网](https://www.clips.uantwerpen.be/pages/pattern) |
| [caffe](https://github.com/BVLC/caffe) | 一个深度学习框架 | [官网](http://caffe.berkeleyvision.org/) |
| [openface](https://github.com/cmusatyalab/openface) | 深度神经网络的人脸识别 | [官网](http://cmusatyalab.github.io/openface/) |
| [face_recognition](https://github.com/ageitgey/face_recognition) | 使用[dlib](http://dlib.net/)和深度学习构建的最新人脸识别功能构建。该模型在[Wild](http://vis-www.cs.umass.edu/lfw/)基准中的[Labeled Faces](http://vis-www.cs.umass.edu/lfw/)上的准确性为99.38％ |  |
| [tensorflow](https://github.com/tensorflow/tensorflow) | 适用于所有人的开源机器学习框架 | [官网](https://tensorflow.org/) |
| [TensorFlow-models](https://github.com/tensorflow/models) | 使用TensorFlow构建的模型和示例 |  |
| [TensorFlow-fold](https://github.com/tensorflow/fold) | TensorFlow Fold是一个用于创建使用结构化数据的[TensorFlow](https://www.tensorflow.org/)模型的库，其中计算图的结构取决于输入数据的结构。例如，[该模型](https://github.com/tensorflow/fold/blob/master/tensorflow_fold/g3doc/sentiment.ipynb) 实现了[TreeLSTM](https://arxiv.org/abs/1503.00075)，用于对任意形状/大小/深度的解析树进行情感分析 |  |
| [pylearn2](https://github.com/lisa-lab/pylearn2) | 机器学习研究库 |  |
| [turicreate](https://github.com/apple/turicreate) | [apple](https://github.com/apple)的Turi Create简化了自定义机器学习模型的开发 |  |
| [Forge](https://github.com/hollance/Forge) | 用于Metal的神经网络工具包 |  |
| [SwiftOCR](https://github.com/garnele007/SwiftOCR) | 用Swift编写的快速简单的OCR库。它使用神经网络进行图像识别 |  |
| [Swift-AI](https://github.com/Swift-AI/Swift-AI) | Swift AI是完全用Swift编写的高性能深度学习库。我们目前为所有Apple平台提供支持，不久将提供Linux支持 |  |
| [Bull-Live-Server](https://github.com/wenjiegit/Bull-Live-Server) | Bull Live Server，旨在使用C++语言提供强大功能和高性能的流媒体直播服务器 |  |

## <a name="Android"></a>Android
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [mumble-android](https://github.com/pcgod/mumble-android) | Android Mumble客户端 |  |
| [RTMP-Video-Publishing-Android](https://github.com/harshing/RTMP-Video-Publishing-Android) | 一个用于发布和获取RTMP视频流的Android应用程序 |  |
| [spydroid-ipcamera](https://github.com/fyhertz/spydroid-ipcamera) | 一个功能强大且有趣的android应用。将手机的摄像头和麦克风流式传输到浏览器或VLC |  |
| [kickflip-android-example](https://github.com/Kickflip/kickflip-android-example) | 集成Kickflip Android SDK的示例项目，可实现超级便捷的直播 |  |
| [XCL-Charts](https://github.com/xcltapestry/XCL-Charts) | Android开源图表库 |  |
| [Awesome-Android-Architecture](https://github.com/Juude/Awesome-Android-Architecture) | Android架构合集 |  |
| [CameraStreaming](https://github.com/dourgulf/CameraStreaming) | CameraStreaming 是一个Android(4.0以上)摄像头实时输出到RTMP服务器的直播演示 |  |
| [android-gpuimage-plus](https://github.com/wysaid/android-gpuimage-plus) | 基于OpenGL的Android图像和相机滤镜 |  |
| [Android-ffmpeg-CameraRecord](https://github.com/wysaid/Android-ffmpeg-CameraRecord) | 使用JavaCV提供的支持，使用OpenGL实时处理+显示摄像头采集的图像，并使用FFMPEG实时录制音视频 |  |
| [kickflip-android-sdk](https://github.com/Kickflip/kickflip-android-sdk) | [Kickflip Android SDK](https://kickflip.io/)-将实时视频流传输到云 |  |
| [android-open-project-analysis](https://github.com/android-cn/android-open-project-analysis) | android开源项目的[分析实现](https://a.codekk.com/) |  |
| [ShineButton](https://github.com/ChadCSong/ShineButton) | 这是Android的UI库。效果像闪亮 |  |
| [VitamioBundle](https://github.com/yixia/VitamioBundle) | Vitamio是适用于Android和iOS的开放式多媒体框架，具有完整且真实的硬件加速解码器和渲染器 |  |
| [grafika](https://github.com/google/grafika) | Grafika测试应用 |  |
| [android_rtmppush_sdk](https://github.com/runner365/android_rtmppush_sdk) | 基于android的手机视频rtmp推流SDK |  |
| [MD360Player4Android](https://github.com/ashqal/MD360Player4Android) | 这是一个精简库，可为Android渲染360度全景视频。VR播放器 |  |
| [AndFix](https://github.com/alibaba/AndFix) | AndFix是[alibaba](https://github.com/alibaba/)为[Android](https://sites.google.com/a/android.com/tools/tech-docs/new-build-system/aar-format) App提供修复程序的库 |  |
| [SoloPi](https://github.com/alipay/SoloPi) | SoloPi 自动化测试工具 ||
| [atlas](https://github.com/alibaba/atlas) | 强大的Android动态组件框架 |  |
| [tinker](https://github.com/Tencent/tinker) | Tinker是适用于Android的修补程序库，它支持dex，库和资源更新，而无需重新安装apk |  |
| [gvr-android-sdk](https://github.com/googlevr/gvr-android-sdk) | 适用于Android的[Google VR SDK](http://developers.google.com/vr/android/) | 有一个适用于iOS和Android NDK 的新开源[Cardboard SDK](https://developers.google.com/cardboard)，它提供了简化的API，改进的设备兼容性以及内置的查看器配置文件QR码扫描功能 |
| [RxKotlin](https://github.com/ReactiveX/RxKotlin) | RxKotlin是一个轻量级的库，它为[RxJava](https://github.com/ReactiveX/RxJava)添加了方便的扩展功能。您可以直接使用RxJava和Kotlin，但是Kotlin具有语言功能（例如[扩展功能](https://kotlinlang.org/docs/reference/extensions.html)），可以进一步简化RxJava的使用。RxKotlin旨在保守地在一个集中式库中收集这些便利，并标准化将RxJava与Kotlin一起使用的约定 |  |
| [EvilsLive](https://github.com/ThinkKeep/EvilsLive) | 该项目是有关视频流直播的SDK | |
| [ExoPlayer](https://github.com/google/ExoPlayer) | 适用于Android的可扩展媒体播放器 |  |
| [RxAndroid](https://github.com/ReactiveX/RxAndroid) | [RxJava](http://github.com/ReactiveX/RxJava)的 Android特定绑定 |  |
| [RxJava](https://github.com/ReactiveX/RxJava) | RxJava是[Reactive Extensions](http://reactivex.io/)的Java VM实现：该库用于通过使用可观察的序列来组成异步和基于事件的程序 |  |
| [BGAQRCode-Android](https://github.com/bingoogolapple/BGAQRCode-Android) | QRCode 扫描二维码、扫描条形码、相册获取图片后识别、生成带 Logo 二维码、支持微博微信 QQ 二维码扫描样式 |  |
| [facebook-android-sdk](https://github.com/facebook/facebook-android-sdk) | 用于将Android应用程序与Facebook平台集成 | [官网](https://developers.facebook.com/docs/android) |
| [android-open-project](https://github.com/Trinea/android-open-project) | Android开源项目分类汇总，更全更新可见[codekk.com](https://p.codekk.com/) |  |
| [librestreaming](https://github.com/lakeinchina/librestreaming) | Android实时效果滤镜rtmp流库。使用Mediacodec HWencoding＆librtmp流 |  |
| [recyclerview-animators](https://github.com/wasabeef/recyclerview-animators) | 一个Android动画库，可轻松将itemanimator添加到RecyclerView项目 | [android-gpuimage](https://github.com/cats-oss/android-gpuimage) | 基于OpenGL的Android过滤器（来自iOS的[GPUImage](https://github.com/BradLarson/GPUImage2)的思想） |
| [DanmakuFlameMaster](https://github.com/bilibili/DanmakuFlameMaster) |[bilibili](http://app.bilibili.com/)在Android上开源弹幕解析绘制引擎项目 | |
| [SopCastComponent](https://github.com/LaiFeng-Android/SopCastComponent) | 来疯直播安卓控件，支持flv，支持rtmp，支持添加视频特效等等 |  |
| [libstreaming](https://github.com/fyhertz/libstreaming) | 在Android上使用RTP传输H.264，H.263，AMR，AAC的解决方案 |  |
| [MagicCamera](https://github.com/wuhaoyu1990/MagicCamera) | 适用于Android的带有Face Beauty的实时滤镜摄像头和录像机以及ImageEditor ---包含美颜等40余种实时滤机，可拍摄，录像，图片修改 ||
| [MediaStreamRecorder](https://github.com/streamproc/MediaStreamRecorder) | 跨浏览器音频/视频/屏幕录制。它支持Chrome，Firefox，Opera和Microsoft Edge。它甚至可以在Android浏览器上使用。它遵循最新的MediaRecorder API标准，并提供类似的API | [官网](https://www.webrtc-experiment.com/msr/) |
| [ExoMedia](https://github.com/brianwernick/ExoMedia) | 一种媒体播放库，具有与Android MediaPlayer和VideoView相似的API，并在可能的情况下使用[ExoPlayer](https://github.com/google/ExoPlayer)作为支持，否则将使用默认的Android MediaPlayer和VideoView |  |
| [LivePublisher](https://github.com/edu-lance/LivePublisher) | Android rtmp推流器 |  |
| [AppRTCDemo](https://github.com/njovy/AppRTCDemo) | WebRTC项目的Android AppRTC演示 |  |
| [HaishinKit.kt](https://github.com/shogo4405/HaishinKit.kt) | [WIP]适用于Android的通过RTMP的摄像头和麦克风流媒体库 |  |
| [yasea](https://github.com/begeekmyfriend/yasea) | 适用于Android的RTMP实时流客户端 |  |
| [srs-sea](https://github.com/leo-lp/srs-sea) | SEA（Android的流编码器）通过HTTP-FLV将实时流发布到SRS(建议使用[YASEA](https://github.com/begeekmyfriend/yasea)，因为SEA只是Android编码器的演示) |  |

## <a name="前端"></a>前端
| [回到顶部](#Indexes) | 描述 | 备注 |
| :--- | :--- | :--- |
| [foundation-sites](https://github.com/foundation/foundation-sites) | 号称世界上最先进的响应式前端框架。为可在任何设备上运行的站点快速创建原型和生产代 | [官网](https://get.foundation/) |
| [vConsole](https://github.com/Tencent/vConsole) | 一个轻量、可拓展、针对手机网页的前端开发者调试面板 |  |
| [zui](https://github.com/easysoft/zui) | 一个基于 Bootstrap 深度定制开源前端实践方案，帮助你快速构建现代跨屏应用 | [官网](http://zui.sexy/) |
| [ant-design](https://github.com/ant-design/ant-design) | 一套企业级 UI 设计语言和 React 组件库 | [官网](https://ant.design/) |
| [ant-motion](https://github.com/ant-design/ant-motion) | Ant Motion 是 Ant Design 中提炼出来的动效语言。他不仅仅是动效语言，同时也是一套 React 框架动效解决方案，可以帮助开发者，更容易的在项目中使用动效。 我们提供了单项，组合动画，以及整套解决方案 |||
| [element](https://github.com/ElemeFE/element) | 适用于Web的Vue.js 2.0 UI工具包 | [官网](https://element.eleme.io/) |
| [incubator-weex](https://github.com/apache/incubator-weex) | 用于构建移动跨平台UI的框架 | [官网](https://weex.apache.org/) |
| [svelte](https://github.com/sveltejs/svelte) | Svelte是构建Web应用程序的新方法。这是一个使用声明性组件并将其转换为有效JavaScript的编译器，可通过外科方式更新DOM |  |
| [ember.js](https://github.com/emberjs/ember.js) | 一个JavaScript框架，可大大减少构建任何Web应用程序所需的时间，精力和资源 |  |
| [beego](https://github.com/astaxie/beego) | beego是用于Go编程语言的开源，高性能Web框架 | [官网](http://beego.me/) |
| [iris](https://github.com/kataras/iris) | Iris是用于Go的快速，简单但功能齐全且非常有效的Web框架 |  |
| [Mars](https://github.com/AlloyTeam/Mars) | 腾讯移动 Web 前端知识库 |  |
| [WeFlow](https://github.com/Tencent/WeFlow) | 一个基于 [tmt-workflow](https://github.com/weixin/tmt-workflow) 前端工作流的开发工具 | [官网](http://weflow.io/) |
| [backbone](https://github.com/jashkenas/backbone) | Backbone通过为模型提供键值绑定和自定义事件，具有丰富的可枚举函数API的集合，具有声明性事件处理的视图，并通过RESTful JSON接口将其全部连接到现有应用程序，从而为重载JavaScript的应用程序提供结构 | [官网](http://backbonejs.org/) |
| [react-dates](https://github.com/airbnb/react-dates) | 一个易于国际化，易于移动的日期选择器库 | [官网](http://airbnb.io/react-dates) |
| [Chart.js](https://github.com/chartjs/Chart.js) | 适用于设计人员和开发人员的简单而灵活的JavaScript图表 | [官网](https://www.chartjs.org/) |
| [angular.js](https://github.com/angular/angular.js) | AngularJS使您可以像编写更智能的浏览器一样编写客户端Web应用程序 | [官网](https://angularjs.org/) ||
| [angular](https://github.com/angular/angular) | Angular是一个开发平台，用于使用TypeScript / JavaScript和其他语言来构建移动和桌面Web应用程序 | [官网](https://angular.io/) |
| [incubator-echarts](https://github.com/apache/incubator-echarts) | 一个免费的，功能强大的图表和可视化库，它提供了一种简便的方法，可以向您的商业产品中添加直观，交互式和高度可定制的图表。它使用纯JavaScript编写，并基于[zrender](https://github.com/ecomfe/zrender)，这是一个全新的轻量级画布库 |  |
| [echarts-gl](https://github.com/ecomfe/echarts-gl) | ECharts-GL是一个扩展包[echarts](http://echarts.baidu.com/)，它提供3D绘图，地球可视化和WebGL加速 |  ||
| [bootswatch](https://github.com/thomaspark/bootswatch) | Bootswatch是[Bootstrap](https://getbootstrap.com/)的开源主题的集合。在[bootswatch.com](https://bootswatch.com/)上进行检查 |  |
| [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) | 使用[React](https://reactjs.org/)构建[Bootstrap](https://getbootstrap.com/)组件 |  |
| [bootstrap](https://github.com/twbs/bootstrap) | 最受欢迎的HTML，CSS和JavaScript框架，用于在网络上开发响应式，移动优先项目 | [官网](https://getbootstrap.com/) |
| [JSPatch](https://github.com/bang590/JSPatch) | JSPatch 可以让你用 JavaScript 书写原生 iOS APP。只需在项目引入极小的引擎，就可以使用 JavaScript 调用任何 Objective-C 的原生接口，获得脚本语言的优势：为项目动态添加模块，或替换项目原生代码动态修复 bug |  |
| [NIM_Web_Demo_H5](https://github.com/netease-im/NIM_Web_Demo_H5) | 云信WEB DEMO HTML5-VUE版本 (以下简称h5 demo)，是一套使用[网易云信WEB端SDK](http://dev.netease.im/docs/product/IM%E5%8D%B3%E6%97%B6%E9%80%9A%E8%AE%AF/SDK%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90/Web%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90)，以[VUE前端框架](https://cn.vuejs.org/v2/guide/)作为前端UI及缓存数据框架，进行开发的手机移动端适配DEMO |  |
| [amazeui](https://github.com/amazeui/amazeui) | 一个移动优先和模块化的前端框架 | [官网](http://amazeui.org/) |
| [json-lite](https://github.com/lauriro/json-lite) | 适用于Chrome和Firefox的快速无阻塞JSON查看器 |  |
| [react-native-web](https://github.com/necolas/react-native-web) |“React Native for Web”使使用React DOM在Web上运行[React Native](https://facebook.github.io/react-native/)组件和API 成为可能 |  |
| [rax](https://github.com/alibaba/rax) | [alibaba](https://github.com/alibaba)的Rax.js是用于构建通用应用程序的渐进式React框架 | [官网](https://rax.js.org) |
| [reactxp](https://github.com/microsoft/reactxp) | 一个使用React和React Native进行跨平台应用程序开发的库 | [官网](https://microsoft.github.io/reactxp/) |
| [ionic](https://github.com/ionic-team/ionic) | 使用网络技术构建出色的本机和渐进式Web应用程序。一个应用程序可在所有内容上运行🎉 | [官网](https://ionicframework.com/) |
| [react](https://github.com/facebook/react) | 用于构建用户界面的声明性，高效且灵活的JavaScript库 | [官网](https://reactjs.org/) |
| [flow](https://github.com/facebook/flow) | 在JavaScript中添加静态类型，以提高开发人员的工作效率和代码质量 | [官网](https://flow.org/) |
| [react-native-maps](https://github.com/react-native-community/react-native-maps) | 适用于iOS + Android的React Native Mapview组件 |  |
| [react-native-navigation](https://github.com/wix/react-native-navigation) | React Native Navigation在iOS和Android上为React Native应用程序提供100％本机平台导航 | [wiki](https://wix.github.io/react-native-navigation/) |
| [incubator-weex](https://github.com/apache/incubator-weex) | [alibaba](https://github.com/alibaba).用于构建移动跨平台UI的框架 | [官网](https://weex.apache.org/) |
| [react-native](https://github.com/facebook/react-native) | React Native将[React](https://reactjs.org/)的声明式UI框架引入了iOS和Android |  |
| [vue](https://github.com/vuejs/vue) | 🖖Vue.js是一个渐进的，可逐步采用的JavaScript框架，用于在Web上构建UI | [官网](http://vuejs.org/) |
| [node](https://github.com/nodejs/node) | [Node.js](https://nodejs.org/) JavaScript运行时 ✨🐢🚀✨ | |
| [webtorrent](https://github.com/webtorrent/webtorrent) | ⚡️网络流媒体客户端 | [官网](https://webtorrent.io/) |
| [nvm](https://github.com/nvm-sh/nvm) | 节点版本管理器-兼容POSIX的bash脚本，用于管理多个活动的node.js版本 |  |
| [streamlink-twitch-gui](https://github.com/streamlink/streamlink-twitch-gui) | 用于[Streamlink](https://streamlink.github.io/)的多平台[Twitch.tv](https://twitch.tv/)浏览器 |  |
| [redux](https://github.com/reduxjs/redux) | Redux是JavaScript应用程序的可预测状态容器（不要与WordPress框架– [Redux](https://reduxframework.com/)框架相混淆） ||
| [plyr](https://github.com/sampotts/plyr) | 一个简单的HTML5，YouTube和Vimeo播放器，支持[现代](https://github.com/sampotts/plyr#browser-support)浏览器 | [官网](https://plyr.io/) |
| [pili-html5-player-example](https://github.com/pili-engineering/pili-html5-player-example) | 带有Flash和Silverlight垫片的[HTML5<音频>或<视频>播放器](http://mediaelementjs.com/)，模仿HTML5 MediaElement API，从而在所有浏览器中实现一致的UI ||
