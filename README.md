CCControlExtension
=================
CCControlExtension is an open-source library which provides a lot of convenient control objects for __Cocos2D v1.x__ for iPhone and Mac such as buttons, sliders or many more...

All these controls are subclasses of CCControl, which is inspired by the UIControl API from the UIKit of CocoaTouch. The main goal of CCControl is to simplify the creation of control objects in Cocos2D by providing an interface and a base implementation ala UIKit. I.e that this class manages the target-action pair registration and dispatches them to their targets when events occur.
For iOS 4.0 or later and Snow Leopard the CCControl also uses the power of blocks to dispatch the events. 

*Note: It is ARC compatible (e.g for use with Kobold2D)*

![](http://github.com/YannickL/CCControlExtension/raw/master/screenshots/cccontrolextension.png)

How to use it
====================
- Include the CCControlExtension folder into your project
- In the needed files include this line:

        #import "CCControlExtension.h"

The `CCControlExtension.h` includes all the already made controls such as button, slider, switch, colour picker, etc.
There are various [examples][] to understand how to use controls and the possibilities they offer.

For more informations you can check [my blog][] and the [api documentation].

License
====================
As well as Cocos2D for iPhone, CCControlExtension is licensed under the MIT License. 
You can download cocos2d-for-iphone here: https://github.com/cocos2d/cocos2d-iphone

Build & Runtime Requirements
====================

  * Xcode 4.0 (or newer)
  * iOS 3.0 or newer for iOS games
  * Snow Leopard (v10.5) or newer for Mac games

How to get the source
===================== 

```
    git clone git@github.com:YannickL/CCControlExtension.git

    # to get latest stable source from master branch, use this command:
    git checkout -t origin/master
```

[my blog]: http://yannickloriot.com/2011/08/create-a-control-object-with-cocos2d-for-iphone/
[examples]: https://github.com/YannickL/CCControlExtension/tree/master/CCControlExamples
[api documentation]: http://yannickloriot.com/library/ios/cccontrolextension/
