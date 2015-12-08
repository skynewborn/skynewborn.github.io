# 毛豆荚的github
关于我的一些star项目的分类与整理

## 1、Android

### UI控件及一些很炫的动画

AVLoadingIndicatorView： https://github.com/81813780/AVLoadingIndicatorView

一组加载动画实现。

WaveSwipeRefreshLayout： https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout

下拉刷新效果。

TextSurface： https://github.com/elevenetc/TextSurface

动画展示文本的库。

Material Scrolling： https://github.com/satorufujiwara/material-scrolling

实现Material Design中那种带头图Parallax滚动、ToolBar自动隐藏/显示的效果。

ExplosionField： https://github.com/tyrantgit/ExplosionField

爆炸效果控件。MIUI 7 Launcher应用卸载的效果。

Android-ConvenientBanner： https://github.com/saiwu-bigkoo/Android-ConvenientBanner

轮播图控件。

TransitionPlayer： https://github.com/linfaxin/TransitionPlayer

一个方便创建与控制Transition动画的库。

ArcAnimator： https://github.com/asyl/ArcAnimator

帮助实现弧形transition效果。

AndroidFillableLoaders： https://github.com/JorgeCastilloPrz/AndroidFillableLoaders

利用矢量图的加载效果。

AndroidScrollingImageView： https://github.com/Q42/AndroidScrollingImageView

图片分层滚动效果控件，可用来实现一些循环播放的动画。

Blurry： https://github.com/wasabeef/Blurry

对图像进行模糊渲染。

500px-android-blur： https://github.com/500px/500px-android-blur

可显示图像模糊效果的控件

CustomActivityOnCrash： https://github.com/Ereza/CustomActivityOnCrash

很有趣的库，可以在应用crash时显示自定义的提示界面。

EaseInterpolator： https://github.com/cimi-chen/EaseInterpolator

动画插值算法集合。

Leonids： https://github.com/plattysoft/Leonids

粒子系统。

TourGuide： https://github.com/worker8/TourGuide

类似于原生Launcher，可显示蒙层点击指示与提示文字的控件。

BottomSheet： https://github.com/Flipboard/bottomsheet

底部浮层控件。

MaterialViewPager： https://github.com/florent37/MaterialViewPager

不解释。

SmartTabLayout： https://github.com/ogaclejapan/SmartTabLayout

一个ViewPager的tab标识。

shimmer-android： https://github.com/facebook/shimmer-android

Facebook出品，可为任意的View加入闪亮动态效果。

SystemBarTint： https://github.com/jgilfelt/SystemBarTint

在4.4以上的translucent模式下帮助状态栏着色。

ToggleButton： https://github.com/zcweng/ToggleButton

开关控件。

WaveView： https://github.com/john990/WaveView

波浪效果，可用于进度条。

android-Ultra-Pull-To-Refresh： https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh

下拉刷新框架，可实现较复杂的自定义效果。

MaterialEditText： https://github.com/rengwuxian/MaterialEditText

仿MD的输入框效果，比support库中自带控件要略全面些，可向前兼容到2.1。

### 有用的库

Scissors： https://github.com/lyft/scissors

一个图片剪裁库。

SimpleCropView： https://github.com/IsseiAoki/SimpleCropView

另一个图片剪裁库。

android-job： https://github.com/evernote/android-job

Evernote出品，一个后台定时任务的库。

Android Priority Job Queue： https://github.com/yigit/android-priority-jobqueue

注：优先用自己的fork，会定期同步。
带优先级控制的后台任务执行库，可将任务持久化以便在应用遭遇异常后仍能恢复之前的任务。

ReLinker： https://github.com/KeepSafe/ReLinker

一个native库安全加载的方案，解决一些由于安装时错误造成native库无法加载的UnsatisfiedLinkError。

Let： https://github.com/canelmas/let

基于Annotation的运行时权限申请库（6.0 Marshmallow新增）

Dexter： https://github.com/Karumi/Dexter

一个类似的库，也是为了简化运行时权限申请的麻烦流程。

Phrase： https://github.com/square/phrase

资源模板，可通过定义占位符的方式进行文本替换。

Dagger 2： https://github.com/google/dagger

Google从Square接手进行实现的依赖注入库。Dagger 2不再使用反射，性能上应优于1。

LeakCanary： https://github.com/square/leakcanary

内存泄露检测好帮手，用上就爱不释手。

Fresco： https://github.com/facebook/fresco

Facebook出品的图片加载库，除jpeg、png外还支持webp、gif。使用了一些黑科技以减少系统对图像内容所占内存的回收。

LoganSquare： https://github.com/bluelinelabs/LoganSquare

号称最快的JSON库，在ART上性能超出GSON，Jackson等库400%以上。

ig-json-parser： https://github.com/Instagram/ig-json-parser

Instagram出品的一个JSON库。

json2view： https://github.com/Avocarrot/json2view

利用JSON动态改变布局显示，有点意思。

libsuperuser： https://github.com/Chainfire/libsuperuser

Root用。

### 动态加载、热修复相关
android-dynamical-loading： https://github.com/kaedea/android-dynamical-loading

动态加载相关的一些项目的集合，收藏以备后用。

DroidPlugin： https://github.com/Qihoo360/DroidPlugin

360的插件开源实现，据说有些黑科技。

Dexposed： https://github.com/alibaba/dexposed

阿里出品的AOP框架，通过类似于Xposed框架的原理，通过hook方法的方式实现对方法代码执行的控制。

NuWa（女娲）： https://github.com/jasonross/Nuwa

一个热修复的纯Java实现，原理是利用了ClassLoader加载dex的工作流程。

AndroidChangeSkin： https://github.com/hongyangAndroid/AndroidChangeSkin

号称无侵入换肤。没尝试过，备后续有需要的时候再看。

### Rx相关

RxJava： https://github.com/ReactiveX/RxJava

不用介绍了吧，万物皆为流的概念还是很Mind-blowing的！

RxAndroid： https://github.com/ReactiveX/RxAndroid

Android上使用RxJava必备。

Retrofit： https://github.com/square/retrofit

HTTP请求的库，和RxJava是绝配有木有。Square出品，品质有保证。

sqlbrite： https://github.com/square/sqlbrite

Rx方式操作SQLite数据库。

tray: https://github.com/grandcentrix/tray

号称SharedPreferences替代，可支持多线程。

### Android相关工具

AndResGuard： https://github.com/shwenzhang/AndResGuard

微信Team出品，可以对资源进行混淆压缩，实测有效。用在生产环境里需要注意仔细配置白名单，否则分分钟遇到资源找不到的崩溃，尤其是对于需要通过名称获得或者反射找到资源的情况（多见于一些第三方SDK）。

MultiChannelPackageTool： https://github.com/seven456/MultiChannelPackageTool

一个多渠道打包工具，利用了zip文件格式的特点，做到了无需重压缩/解压/签名等。还是很有意思的。

vectalign： https://github.com/bonnyfone/vectalign

可以用两个VectorDrawable生产两者过渡的路径（类似Material Design的那个“菜单<->返回”）的工具。


### App应用实例

WeChatLuckyMoney： https://github.com/geeeeeeeeek/WeChatLuckyMoney

一个微信抢红包的app，留作观摩用。

BuildingBlocks： https://github.com/tangqi92/BuildingBlocks

一个知乎日报的三方客户端，MD风格。

SmsCodeHelper： https://github.com/drakeet/SmsCodeHelper

短信验证码助手。

Universal Music Player： https://github.com/googlesamples/android-UniversalMusicPlayer

Google官方出品的展示MD的一个音乐播放器应用。

## 2、JavaScript
//TODO
