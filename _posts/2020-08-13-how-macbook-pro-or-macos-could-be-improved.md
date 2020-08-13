---
layout: post
title: How MacBook Pro or macOS could be improved
image: "/assets/images/posts/macos/macbook.jpg"
headerImage: true
tag:
- MacBook Pro
- macOS
- improvements
category: blog
author: ietsism
description: How the software of MacBook Pro (macOS) could be improved on 9 points
published: true
date: 2020-08-13 09:00
---

I love my MacBook Pro (15", 2018) probably even more than my iPhone. However, just like [iPhone]({% post_url 2020-08-08-how-iphone-or-ios-could-be-improved %}), the device is not perfect. In this article I would like to discuss how MacBook Pro and macOS could be improved. Therefore, I have selected about 9 improvements. Hopefully Apple will implement these one day.

*At the time of writing, the version of macOS that I was running was `10.15.5` (Catalina). I believe these limitations were still present, at least up to that version.*

## LED for built-in camera

Some consider MacBook Pro to be a secure computer. The LED that lights up to indicate that the camera is in use, is one of those security features. However, it is or was possible to activate the camera without the LED turning on.[^1] That should now have been fixed as the camera and LED are connected to the same circuit (a.k.a. hardwired). Yet, there is still an issue: once you see the LED lighting up, you are too late. Taking a snapshot with the camera might even be possible without anyone noticing the light turning on. And since Apple discourages the use of camera covers[^2], you would have to improvise in case you like to open and close your MacBook. (In other words, if you want to use your MacBook as a portable device.)
> Fix: implement a setting to set a delay between the light turning on and the camera being ready for use.

## LED for built-in microphone

Much like a camera can be abused for malicious purposes, a microphone can be used in a similar way.[^3] There is currently no visual indication that the microphone is recording. It would help to implement an extra LED, preferably with a different color than the camera LED, as a visual cue for the microphone listening. Perhaps with Siri and the microphone constantly listening for *Hey Siri* or the like this feature could be cumbersome, but I am sure Apple is able to overcome that.
> Fix: add an extra LED that indicates when the microphone is listening (and also add the delay feature described above). Even better than visual indicators would be to have a physical switch to turn your camera or microphone off completely.[^4] Only then you can be sure that input devices are not eavesdropping on you. If you trust such a switch, of course.

## Full screen windows

As a user of Windows, a feature you often use without thinking is maximizing a window. On macOS that works slightly differently: once you go full screen, the window is moved to its own space. That tends to work well, besides having to remember what screen is to the left and right from your current screen. However, once you move away from the trackpad this feature becomes cumbersome: try to use these nifty gestures on your regular mouse. Ain't gonna work without some key combinations for the keyboard I always tend to forget.
> Fix: add a setting to make full screen windows behave more like Windows, not separating them in their own space.

## Better mouse support

After buying a fancy mouse with a back and forward button (very useful when browsing) it turned out this is not natively supported on macOS. Wait, so a computer that costs thousands of dollars cannot cope with two extra buttons on a mouse? How horrible.
> Fix: support back and forward buttons on computer mouses natively. Until then, I will rely on *SensibleSideButtons*.[^5]

{% include image.html url="/assets/images/posts/macos/mouse.jpg" description="Fancy computer mouse with silver back and forward button on the side" %}

## Scroll direction of mouse

Another unbelievable design decision: the scroll direction of your mouse is always equal to your trackpad. That means that when you use the trackpad with the default scroll direction (known as *Natural*), the scroll wheel on your external mouse has to be used counter-intuitively: scrolling up makes pages go down, scrolling down makes pages go up. Unbelievable.
> Fix: just separate the scroll direction of the trackpad from an external mouse.

## More, useful, and custom gestures

MacBook Pro's trackpad is good. However, as someone who uses a Chromebook on the side, I wish there were more gestures, or at least an option for custom gestures out of the box. Chromebook is great for browsing with its built-in gestures.[^6] Want to open a link in a new tab? Just click the link with three fingers. Closing a tab? Three-finger click on the tab. Scrolling through your tabs? Three fingers.
> Fix: implement Chrome OS-like gestures, or just give us the option for creating such gestures ourselves.

## Default email client

I like Outlook. Try setting that up as your default email client without first setting up Mail on your Mac. No can do. Boo-hoo.
> Fix: Apple, let us set our default programs without using yours first.  

## Energy settings

I believe this is going to be added soon, but I am still missing more settings related to power consumption. Sometimes you want your computer to last a bit longer (low power mode). Sometimes you want your computer to just keep running no matter what.[^7]
> Fix: add more settings related to energy consumption.

{% include image.html url="/assets/images/posts/macos/lp_mode.jpg" description="This would not be too difficult for macOS, would it?" %}

## Finder

Finder. Great name for a program that always makes me find how to use it (again). Not so intuitive and quite ugly. Also, as a fervent user of cut and paste in Windows this is what I am missing almost daily. I know you can use a key combination or holding down `option` to mimick Windows' cut, but it is just, eh, not cutting it for me. I really want a *cut* option when I right click on something.

Hidden folders and files? Constantly using key combinations to make them appear is annoying, especially when you quickly want to use your mouse only. Just implement an option to permanently show hidden folders and files. Oh and while you are at it, just add *Trash* to the Finder's sidebar permanently. (Or should Finder be added to Trash instead?)
> Fix: ditch Finder, implement Windows Explorer or File Explorer as it is called nowadays.

## Last words

Like [iPhone]({% post_url 2020-08-08-how-iphone-or-ios-could-be-improved %}), MacBook also has its flaws. Finder is quite difficult to use in my opinion, especially when coming from the user-friendly File Explorer on Windows. Nowadays I tend to use the command-line to replace finder anyway, but having a graphical user interface is nice for a change. However, when shelling out a small fortune to buy a computer, you should expect something good, right? Apple can do better than this. What is your pet peeve?

### References

[^1]: It is or it was possible to [covertly activate the camera](https://www.intego.com/mac-security-blog/your-macs-camera-can-be-hacked/) on MacBooks
[^2]: ["Don't close your MacBook, MacBook Air, or MacBook Pro with a cover over the camera"](https://support.apple.com/en-us/HT211148)
[^3]: Built-in microphones [should be easier to block](https://www.pcworld.com/article/3393254/computer-privacy-why-your-laptops-microphone-should-be-easier-to-block.html)
[^4]: Hardware kill switches are [not science fiction](https://puri.sm/learn/hardware-kill-switches/)
[^5]: [SensibleSideButtons](https://sensible-side-buttons.archagon.net/) adds support for side buttons on mice
[^6]: Chromebook or Chrome OS has [great gestures for browsing](https://support.google.com/chromebook/answer/1047367)
[^7]: [Amphetamine](https://apps.apple.com/nl/app/amphetamine/id937984704) to the rescue
