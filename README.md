[![官方项目](http://jb.gg/badges/official.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)
[![最新稳定版本](https://img.shields.io/github/v/release/JetBrains/compose-jb?color=brightgreen&label=latest%20release)](https://github.com/JetBrains/compose-jb/releases/latest)
[![最新构建版本](https://img.shields.io/github/v/release/JetBrains/compose-jb?color=orange&include_prereleases&label=latest%20build)](https://github.com/JetBrains/compose-jb/releases)

# 一个由JetBrains创作的Compose Multiplatform, 由JetBrains提供,Overrun Organization翻译
![](artwork/readme/apps.png)
编写Kotlin开放式UI框架，用于桌面平台(macOS, Linux, Windows)和Web的compose核心 [Compose 存储库](https://android.googlesource.com/platform/frameworks/support).

预览功能(检查您的应用程序UI而不构建/运行它)对于桌面平台可以通过它 [IDEA 插件](https://plugins.jetbrains.com/plugin/16541-compose-multiplatform-ide-support).

## 教程列表
### Compose 桌面版
* [入门](tutorials/Getting_Started)
* [图像和图标处理](tutorials/Image_And_Icons_Manipulations)
* [鼠标和鼠标悬停事件](tutorials/Mouse_Events)
* [滚动和滚动条](tutorials/Desktop_Components#scrollbars)
* [工具提示](tutorials/Desktop_Components#tooltips)
* [上下文菜单](tutorials/Context_Menu/README.md)
* [顶层窗口管理器](tutorials/Window_API_new)
* [菜单，托盘，和通知](tutorials/Tray_Notifications_MenuBar_new)
* [键盘支持](tutorials/Keyboard)
* [选项卡焦点导航](tutorials/Tab_Navigation)
* [Swing互相操作性](tutorials/Swing_Integration)
* [导航栏](tutorials/Navigation)
* [辅助](https://github.com/JetBrains/compose-jb/tree/master/tutorials/Accessibility)
* [Building a native distribution](tutorials/Native_distributions_and_local_execution)

Also, see [Foundation](https://developer.android.com/jetpack/compose/documentation#core) and [Design](https://developer.android.com/jetpack/compose/documentation#design) docs from Google. They were originally written for Android, but most of information applies to Compose for Desktop as well.

### Compose for Web HTML
* [Getting started](tutorials/Web/Getting_Started) 
* [Building web UI](tutorials/Web/Building_UI)
* [Handling Events](tutorials/Web/Events_Handling)
* [Controlled and Uncontrolled inputs](tutorials/Web/Controlled_Uncontrolled_Inputs)
* [Style DSL](tutorials/Web/Style_Dsl)
* [Using test-utils](tutorials/Web/Using_Test_Utils)

### Jetpack Compose for Android
Compose Multiplatform uses Jetpack Compose developed by Google when you target Android platform. See more info about it [here](tutorials/Development_for_Android).

[The docs](https://developer.android.com/jetpack/compose/documentation) published by Google are great and decribe how to develop on Compose for Android.

Note that when you use Compose Multiplatform, you setup your project differently. You can create a multiplatform project with Android support via IDEA Project Wizard, or by copying [multiplatform template](https://github.com/JetBrains/compose-jb/tree/master/templates/multiplatform-template). In `androidMain` source set you can use almost all information from the docs, and in `commonMain` source set you can use information from Foundation and Design sections.

### Experimental targets
The other targets (iOS, Compose for Web Canvas) are experimental and under development. Use them at your own risk.

## Examples
   * [codeviewer](examples/codeviewer) - File Browser and Code Viewer application for Android and Desktop
   * [imageviewer](examples/imageviewer) - Image Viewer application for Android and Desktop
   * [issues](examples/issues) - GitHub issue tracker with an adaptive UI and ktor-client
   * [Falling Balls](examples/falling-balls) - Simple game
   * [notepad](examples/notepad) - Notepad, using the new experimental Composable Window API
   * [todoapp](examples/todoapp) - TODO items tracker with persistence and multiple screens, written with external navigation library
   * [todoapp-lite](examples/todoapp-lite) - A simplified version of [todoapp](examples/todoapp), fully based on Compose
   * [widgets gallery](examples/widgets-gallery) - Gallery of standard widgets
   * [IDEA plugin](examples/intellij-plugin) - Plugin for IDEA using Compose for Desktop
   * [compose-bird](examples/web-compose-bird) - A flappy bird clone using Compose for Web
   * [web-landing](examples/web-landing) - A landing page built using Compose for Web (HTML composable api)
   * [compose-web-with-react](examples/web-with-react) - Using compose-in-react and react-in-compose
   * [compose-web-in-js](examples/web-compose-in-js) - Using Html based composables in js

## Other ##
* [artwork](artwork) - design artifacts
* [benchmarks](benchmarks) - collection of benchmarks
* [compose](compose) - composite build of [Compose Multiplatform sources](https://github.com/JetBrains/androidx)
* [ci](ci) - Continuous Integration helpers
* [gradle-plugins](gradle-plugins) - a plugin, simplifying usage of Compose Multiplatform with Gradle
* [templates](templates) - new application templates
* [components](components) - custom components of Compose Multiplatform
   * [Split Pane](components/SplitPane)
* [experimental](experimental) - experimental components and examples
   * [examples](experimental/examples) - examples that use new experimental functionality
   * [cef](experimental/cef) - CEF integration in Jetpack Compose (somewhat outdated)
   * [Video Player](experimental/components/VideoPlayer)
   * [LWJGL integration](experimental/lwjgl-integration) - An example showing how to integrate Compose with [LWJGL](https://www.lwjgl.org)
   * [CLI example](experimental/build_from_cli) - An example showing how to build Compose without Gradle
       
## Versions ##

* [The latest stable release](https://github.com/JetBrains/compose-jb/releases/latest)
* [The latest dev release](https://github.com/JetBrains/compose-jb/releases)
* [Compatibility and versioning overview](VERSIONING.md)
* [Changelog](CHANGELOG.md)
