<!---
[]()
-->

> Please help me contribute to this list, for non-experience iOS developers or someone who need a come-in-handy library list to refer or to use in their projects. Fork, edit and send a PR are all things you can do!

## Table of Contents
- [UI Component](#ui-component)
	- [Collection](#collection)
	- [Menu](#menu)
	- [Button](#button)
	- [Chart](#chart)
	- [Tabbar](#tabbar)
	- [HUD](#hud)
	- [Font](#font)
	- [Animation](#animation)
		- [Text animation](#text-animation)
	- [Breadcrumbs](#breadcrumbs)
	- [Scroll View](#scroll-view)
	- [Minor View](#minor-view)

- [Transition Animation](#transition-animation)

- [Multimedia](#multimedia)
	- [Audio](#audio)
	- [Video](#video)
	- [Image](#image)
		- [Image Processing](#image-processing)
		- [Image Viewer](#image-viewer)
		- [Others](#others)
- [Networking](#networking)
	- [Network](#network)
	- [Downloader](#downloader)
- [Cache Technique](#cache-technique)
- [Database](#database)
- [Social Sharing](#social-sharing)
- [PDF](#pdf)
- [Drawing](#drawing)
- [Development Tool](#development-tool)
	- [Xcode Plugin](#xcode-plugin)
	- [Logging](#logging)
	- [Deployment Tool](#deployment-tool)
- [Completed Product](#completed-product)

> All libraries are ordered randomly.

## UI Component 
#### Collection
- [tapkulibrary](https://github.com/devinross/tapkulibrary). TapkuLibrary is an iOS library built on Cocoa and UIKit intended for broad use in applications. Support many customized UI Components. 

#### Menu
- [REMenu](https://github.com/romaonthego/REMenu). Dropdown menu inspired by Vine.
- [StackMenu](https://github.com/istsest/StackMenu). Stack menu looks like Dock bar in Mac OS X.
- [AwesomeMenu](https://github.com/levey/AwesomeMenu). AwesomeMenu is a menu with the same look as the story menu of [Path](https://path.com/).
- [JASidePanels](https://github.com/gotosleep/JASidePanels). Reveal side ViewControllers similar to Facebook/Path's menu.
- [RESideMenu](https://github.com/romaonthego/RESideMenu). iOS 7 style side menu with parallax effect.
- [ViewDeck](https://github.com/Inferis/ViewDeck). An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps.
- [TumblrMenu](https://github.com/cyndibaby905/TumblrMenu). Tumblr iOS app like menu view completely created using core animation.
- [GHContextMenu](https://github.com/GnosisHub/GHContextMenu). Pinterest like context menu control for iOS. It also likes gestures in [Prismatic](https://itunes.apple.com/vn/app/prismatic-always-interesting/id551206444?mt=8).

#### Button

#### Chart
- [PNChart](https://github.com/kevinzhow/PNChart). A simple and beautiful chart lib used in Piner for iOS. Support bar chart, circle chart, line chart. 
- [iOSPlot](https://github.com/honcheng/iOSPlot). A chart library for pie chart, line chart.
- [XYPieChart](https://github.com/xyfeng/XYPieChart). A simple and animated Pie Chart for your iOS app.
- [HUChart](https://github.com/hugo53/HUChart). A simple (but the first) semi circle 
chart (half pie chart) for iOS.
- [JYRadarChart](https://github.com/johnnywjy/JYRadarChart). A library for radar chart.
- [TEAChart](https://github.com/xhacker/TEAChart). A simple and intuitive iOS chart library, includes Contribution graph (like of github), clock chart, and bar chart.
- [Core Plot](http://core-plot.googlecode.com/hg/documentation/html/iOS/index.html). Extensive charting, graphing, and plotting. Tightly integrated with Apple technologies like Core Animation, Core Data, and Cocoa Bindings.

#### Tabbar
- [TabBarKit](https://github.com/davidmorford/TabBarKit). A flexible Tab Bar implementation for iPhone and iPad.
- [AKTabBarController](https://github.com/alikaragoz/AKTabBarController). Adaptative and customizable tab bar for iOS.

#### HUD
- [MBProgressHUD](https://github.com/jdg/MBProgressHUD). MBProgressHUD is an iOS drop-in class that displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. 
- [SVProgressHUD](https://github.com/samvermette/SVProgressHUD). A clean and lightweight progress HUD for iOS app. SVProgressHUD is an easy-to-use HUD meant to display the progress of an ongoing task.
- [MBAlertView](https://github.com/mobitar/MBAlertView). A fast block-based alert and HUD library with a simple API.
- [SDCAlertView](https://github.com/Scott90/SDCAlertView). SDCAlertView is intended as a pixel-for-pixel UIAlertView.

#### Font
- [FBDigitalFont](https://github.com/lyokato/FBDigitalFont). This library includes some kind of digital fonts. It is not TTF or OTF , just draw by CoreGraphics. Really awesome!
- [ios-fontawesome](https://github.com/alexdrone/ios-fontawesome). Font awesome is an iconic font for iOS.

#### Animation
- [MPFoldTransition](https://github.com/mpospese/MPFoldTransition). Easily add custom folding and page-flipping transitions to UIViews and UIViewControllers, including flip page, fold page.
- [POP-MCAnimate](https://github.com/matthewcheok/POP-MCAnimate). Concise syntax for the Pop animation framework.
- [PAImageView](https://github.com/abiaad/PAImageView). Rounded async imageview downloader based on AFNetworking 2 and lightly cached.

##### Text animation
- [RQShineLabel](https://github.com/zipme/RQShineLabel). Secret app like text animation.
- [Shimmer](https://github.com/facebook/Shimmer). An easy way to add a simple shimmering effect to any view in an iOS app, which is particularly useful as an unobtrusive loading indicator.


#### Breadcrumbs
- [RMStepsController](https://github.com/CooperRS/RMStepsController). This is an iOS control for guiding users through a process step-by-step. Take a look at [here](http://cooperrs.github.io/RMStepsController/Images/Screen3-animated.gif).

#### Scroll View
##### Horizontal Scroll View (left-right scroll)
- [SwipeView](https://github.com/nicklockwood/SwipeView). SwipeView is a class designed to simplify the implementation of horizontal, paged scrolling views on iOS. It is based on a UIScrollView, but adds convenient functionality such as a UITableView-style dataSource/delegate interface for loading views dynamically, and efficient view loading, unloading and recycling. 
- [MNPageViewController](https://github.com/min/MNPageViewController). Simple scrolling page view container for UIViewControllers modelled after UIPageViewController.

> We can use UIPageViewController for this purpose (horizontal scrolling), but there is a bug on iOS 6 through iOS 7 if we use option UIPageViewControllerTransitionStyleScroll. See [this video](http://www.apeth.com/PageViewControllerBug.mov) for more details.

##### Vertical Scroll View (top-bottom scroll)
- [SoloComponents-iOS](https://github.com/andreyvit/SoloComponents-iOS/tree/master/ATPagingView). UIView-based scrolling vertically.

#### Minor View
- [EAIntroView](https://github.com/ealeksandrov/EAIntroView). Highly customizable drop-in solution for introduction views.
- [ICETutorial](https://github.com/icepat/ICETutorial). A nice tutorial like the one introduced in the Path 3.X App.


## Transition Animation
- [AMWaveTransition](https://github.com/andreamazz/AMWaveTransition). Custom transition between viewcontrollers holding tableviews like a wave.


## Multimedia
#### Audio
- [TheAmazingAudioEngine](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine). Core Audio, Cordially: A sophisticated framework for iOS audio applications, built so you don't have to. 
- [SoundManager](https://github.com/nicklockwood/SoundManager). Simple sound and music player class for playing audio on Mac and iPhone.
- [AudioStreamer](https://github.com/mattgallagher/AudioStreamer). A streaming audio player class  for Mac OS X and iPhone.
- [SNRMusicKit](https://github.com/indragiek/SNRMusicKit). All-in-one framework for browsing and playing music from various sources on iOS and OS X.

#### Video
- [GPUImage](https://github.com/BradLarson/GPUImage). An open source iOS framework for GPU-based image and video processing.
- [LBYouTubeView](https://github.com/larcus94/LBYouTubeView). A MPMoviePlayerViewController subclass that can display YouTube videos.
- [VideoPlayerKit](https://github.com/blizzard-op/VideoPlayerKit). A full video player, sharing integrated. 
- [MusicPlayerViewController](https://github.com/BeamApp/MusicPlayerViewController). An iPhone view controller to visualize and control music playback.

#### Image
##### Image Processing
- [GPUImage](https://github.com/BradLarson/GPUImage). An open source iOS framework for GPU-based image and video processing.
- [CLImageEditor ](https://github.com/yackle/CLImageEditor). A code for using some image processing tasks for Image, such as crop, rotate, adjustment, Tone Curve, ...
- [TDImageColors](https://github.com/timominous/TDImageColors). iOS Library used to detect a number of most used colors in a UIImage.

##### Image Viewer
- [iCarousel](https://github.com/nicklockwood/iCarousel). A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS. 
- [MHFacebookImageViewer](https://github.com/michaelhenry/MHFacebookImageViewer). Image Viewer likes Photo Viewer of  Facebook.
- [ETFoursquareImages](https://github.com/EugeneTrapeznikov/ETFoursquareImages). Image Viewer (at top of page) likes Foursquare.
- [SSUIViewMiniMe](https://github.com/sSegev/SSUIViewMiniMe). SSUIViewMiniMe takes your UIView and creates a small version of it with an indicator of your location on the original UIView.
- [YSViewer](https://github.com/yashigani/YSViewer). Image Viewer like Tweetbot 3.

##### Others 
- [SDWebImage](https://github.com/rs/SDWebImage). Asynchronous image downloader with cache support with an UIImageView category.


## Networking
#### Network
- [AFNetworking](https://github.com/AFNetworking/AFNetworking). A delightful iOS and OS X networking framework.
- [RestKit](https://github.com/RestKit/RestKit). RestKit is a modern Objective-C framework for implementing RESTful web services clients on iOS and Mac OS X. It provides a powerful object mapping engine that seamlessly integrates with Core Data and a simple set of networking primitives for mapping HTTP requests and responses built on top of AFNetworking.
- [SocketRocket](https://github.com/square/SocketRocket). A conforming Objective-C WebSocket client library.

#### Downloader
- [TCBlobDownload](https://github.com/thibaultCha/TCBlobDownload). Competitive big files downloads in Cocoa. Tested with files from approx 150MB to approx 1.2GB, mostly videos.
- [SDWebImage](https://github.com/rs/SDWebImage). Asynchronous image downloader with cache support with an UIImageView category.


## Cache Technique
- [FastImageCache](https://github.com/hugo53/FastImageCache). iOS library for quickly displaying images while scrolling.
- [SDURLCache](https://github.com/rs/SDURLCache). URLCache subclass with on-disk cache support on iPhone/iPad.
- [TMCache](https://github.com/tumblr/TMCache). Fast parallel object cache for iOS and OS X. TMCache is a key/value store designed for persisting temporary objects that are expensive to reproduce, such as downloaded data or the results of slow processing.
- [MKNetworkKit](https://github.com/MugunthKumar/MKNetworkKit). Networking Framework with built in authentication and HTTP 1.1 caching standards support for iOS 5+ devices.

## Database
- [fmdb](https://github.com/ccgus/fmdb). A Cocoa / Objective-C wrapper around SQLite.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord). MagicalRecord makes setting up and using Core Data fast and easy.

## Social Sharing
- [ShareKit](https://github.com/ideashower/ShareKit). Drop in sharing features for all iPhone and iPad apps. Support Facebook, Twitter, Delicious, Email, Google Reader,Instapaper, Pinboard, Read It Later, Tumblr. 
- [CFShareCircle](https://github.com/camdenfullmer/CFShareCircle). CFShareCircle is a user interface component for iOS that can be integrated into an app as a sharing mechanism for any kind of content.

## PDF
- [ThatPDF](https://github.com/Ink/ThatPDF). ThatPDF is an open source application for reading and annotating pdfs. 
- [PDFKitten](https://github.com/KurtCode/PDFKitten). A framework for extracting data from PDFs in iOS. Support search, highlight PDF.
- [Viewer](https://github.com/vfr/Viewer). PDF Viewer Library for iOS.
- [Reader](https://github.com/vfr/Reader). PDF Reader Core for iOS. 
- [FastPdfKit](https://github.com/mobfarm/FastPdfKit). A Static Library to be embedded on iOS applications to display pdf documents. It's a powerful framework for showing PDF, but it's just a framework, not open all source.
- [ILPDFKit](https://github.com/iwelabs/ILPDFKit). A simple toolkit for filling out PDF forms in iOS.

## Drawing
- [Inkpad](https://github.com/sprang/Inkpad). Vector illustration app for the iPad. It supports paths, compound paths, text, images, groups, masks, gradient fills, and an unlimited number of layers.
- [Brushes](https://github.com/sprang/Brushes). Painting app for the iPhone and iPad.

## Development Tool
#### Xcode Plugin
- [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode). Xcode plug-in which helps you write Javadoc style documents easier. Just type /// and write documented comment. Support XCode 4 \& Xcode 5.
- [XAlign](https://github.com/qfish/XAlign). An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns. Support Xcode 5.
- [XToDo](https://github.com/trawor/XToDo). Xcode plugin to collect and list the TODO, FIXME,???,!!!!.

#### Logging
- [UALogger](https://github.com/UrbanApps/UALogger). A powerful and flexible logging utility for Mac/iOS apps. Help show log better.
- [CocoaLumberjack](https://github.com/robbiehanson/CocoaLumberjack) fast & simple logging framework for Objective-C.

#### Deployment Tool
- [CocoaPods](https://github.com/cocoapods/cocoapods) CocoaPods manages dependencies for your Xcode project.

## Completed Product
- [cheddar-ios](https://github.com/nothingmagical/cheddar-ios). Cheddar for iOS is the universal iPhone and iPad application for Cheddar, a simple \& instant task manager.
- [Inkpad](https://github.com/sprang/Inkpad). Vector illustration app for the iPad. It supports paths, compound paths, text, images, groups, masks, gradient fills, and an unlimited number of layers.
- [Brushes](https://github.com/sprang/Brushes). Painting app for the iPhone and iPad.
- [iReddit](https://github.com/reddit/iReddit). The iReddit iPhone app for reddit addicts.
- [News/YC](https://github.com/bennyguitar/News-YC---iPhone). The iPhone version of News/YC, a Hacker News reader and interactive iOS application.
- [Hacker-News-for-iOS](https://github.com/mmackh/Hacker-News-for-iOS). Hacker News client for iPad and iPhone.
- [Mobile-Canberra](https://github.com/actgov/Mobile-Canberra). A powerful platform for showing points of interest and services on a map for both Android and iOS.
- [Doppio](https://github.com/chroman/Doppio). An open source iOS app to find the nearest Starbucks store using NSURLSession, AFNetworking 2.0, Mantle and Starbucks private API. The app demonstrates how to use MapKit, Core Location, AFNetworking 2.0 and Mantle frameworks.
- [TaskPaper](https://github.com/jessegrosjean/NOTTaskPaperForIOS). Source code of [TaskPaper](https://itunes.apple.com/en/app/taskpaper-simple-to-do-lists/id354540092?mt=8) - a to-do list application. It has approximate 500 reviews in iTunes store but the source code still goes public.

#### News/Magazine App
- [Libreliodev](https://github.com/libreliodev/iOS). Magazine and multimedia publishing app on iOS 
http://www.librelio.com. Libreliodev provides framework to make wonderful iOS, Android, Windows Phone magazine app, support both HTML and PDF content.
- [Puzha](https://github.com/stheakanath/Puzha-RSS-Feeder). iPhone app for Puzha.com, Malayalam magazine to aggregate all RSS data.

> [More than 100 real apps open source here](https://maniacdev.com/2010/06/35-open-source-iphone-app-store-apps-updated-with-10-new-apps).

<!---
[]()
-->



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/hugo53/ill/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

