

A resource for tracking the various image sizes needed for common resources related to web development. Feel free to contribute (via issues or pull request).

##Facebook
###Profile Photo
150 x 150 (scales down to 130 x 130, though)

[Source](https://www.facebook.com/help/315809258465467)

###Cover Photo
815 x 315

[Source](https://www.facebook.com/help/125379114252045)

##Twitter
###Profile Photo
48x48 - Normal

[Source](https://dev.twitter.com/docs/user-profile-images-and-banners)

###Header Photo
Recommended 1252 x 626

[Source](https://support.twitter.com/groups/50-welcome-to-twitter/topics/204-the-basics/articles/127871-editing-your-profile)

##iOS
List each size on separate line.

~~~html
<link rel="apple-touch-icon" href="touch-icon-iphone.png">
<link rel="apple-touch-icon" sizes="76x76" href="touch-icon-ipad.png">
<link rel="apple-touch-icon" sizes="120x120" href="touch-icon-iphone-retina.png">
<link rel="apple-touch-icon" sizes="152x152" href="touch-icon-ipad-retina.png">
~~~

[Source](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html)

|| iOS 7 | iOS 7 | iOS 6 | iOS 6|
|-----| ----- | --- | ----| ------ |
|| iPhone  | iPad | iPhone | iPad |
| Retina | 120 x 120 | 152 x 152  | 114 x 114 | 144 x 144 |
| Standard | 60 x 60 |  76 x 76   | 57 x 57 | 72 x 72  |

[Source](https://developer.apple.com/LIBRARY/IOS/qa/qa1686/_index.html)

##Android
Standard: 48 x 48

Other sizes based on pixel dimensions:

* 72 x 72 (1.5x)
* 96 x 96 (2x)
* 144 x 144 (3x)
* 192 x 192 (4x)

[Source](http://developer.android.com/design/style/iconography.html)

##Windows
Tile Size | Standard Size | Minimum Size | Recommended Size
--------- | ------------- | ------------ | ----------------
Small     | 70 x 70 | 56 x 56 | 128 x 128
Medium    | 150 x 150 | 120 x 120 | 270 x 270
Wide      | 310 x 150 | 248 x 120 | 558 x 270
Large     | 310 x 310 | 248 x 248 | 558 x 558

[Source](http://msdn.microsoft.com/en-us/library/ie/dn455106\(v=vs.85\).aspx)

##Google+
###Cover Photo
* 1080 x 608 (Recommended size)
* 480 x 270 (Minimum size)
* 2120 x 1192 (Maximum size)

[Source](https://support.google.com/plus/answer/1057172?hl=en)

##Resources
[Iconogen]() - Converts .png file into Apple Touch, favicon, and Windows Tile icons

<a href="https://github.com/higley/graphicsizes"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_darkblue_121621.png" alt="Fork me on GitHub"></a>
