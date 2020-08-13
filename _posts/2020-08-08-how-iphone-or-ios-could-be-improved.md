---
title: "How iPhone or iOS could be improved"
layout: post
date: 2020-08-08 09:00
image: /assets/images/posts/ios/iphone.jpg
headerImage: true
tag:
- iPhone
- iOS
- improvements
category: blog
author: ietsism
description: How the software of iPhone (iOS) could be improved on 10 points
published: true
---

I like my iPhone. It has almost been a decade since I have started using one. Before that I owned a 2nd-gen iPod Touch that came with iOS 2. So, with the exception of the first iPhone OS release, I have worked with and experienced all iOS versions on various different hardware (iPod, iPhone, and iPad). In these years I have run into the limitations of the software on several occasions. In this article I would like to share 10 of these limitations and my proposed fixes. Hopefully Apple will implement these one day. And while they are at it, maybe they can checkout [macOS]({% post_url 2020-08-13-how-macbook-pro-or-macos-could-be-improved %}) too?

*At the time of writing, the latest version of iOS was `13.6`. I believe these limitations were still present, at least up to that version.*

## Low battery notifications

I am sure you have all encountered these; persistent pop-up notifications about your battery either being below a 20% or 10% charge. The only way to get rid of these notifications is by pressing the *Dismiss* or *Close* button.
> Fix: include setting to turn these notifications off.

{% include image.html url="/assets/images/posts/ios/battery.jpg" description="Persistent low battery notification on iOS" %}

## Phone call recording

A feature I used to use on my old Sony Ericsson dumbphone[^1] was recording phone calls. Especially when receiving important phone calls, being able to record them and listening to them at a later point tends to be useful. (Or maybe you would just like to record your own or the other person's voice?) However, it seems like in some countries, like the US of A, this is not allowed without the other person's consent. Nonetheless, we know that Apple is open to adapting their products to various regions. (or is Apple forced to by a certain Asian country?)[^2] But if so, why not enable call recording as well for certain countries?
> Fix: you guessed it, incorporate an option to record phone calls (preferably with a button the call screen).

## Automatic download of updates

*I believe this has been fixed nowadays*

One of my pet peeves is that iOS tends to download updates when your device is connected to Wi-Fi and is charging. On my 16GB iPhone (:weary:) this meant: 1) random notifications about iPhone reaching its maximum storage capacity, and 2) me going into *Settings* to remove the 1GB+ update.
> Fix: provide setting to not automatically download (or is it *force*?) updates.

## Incoming call screen

Something I encounter regularly: someone (or some *bot*) trying to reach you while you do not want to answer. There is no way to get rid of the incoming call screen unless the other person hangs up or you hit the lock button twice. However, when you do the latter, the other person will receive a busy signal. In case of telemarketers this means that they know the number is in use. For your mother-in-law it means she knows what you are up to. I just want to keep on doing whatever I was doing, ignoring the incoming call without the other side knowing about it.
> Fix: include option to get out of the incoming call screen unnoticeably.

{% include image.html url="/assets/images/posts/ios/call_screen.png" description="A wild call screen appears!" %}

## iOS version numbering

The version numbering of iOS is a bit awkward. At first I thought that Apple wanted to get to iOS 10 ASAP, to have the same version number as its Mac equivalent: OS X (OS 10). But no, Apple changed OS X to *macOS*, ditching the version number implicitly. (Maybe because of Windows 10?) Apple releases a new version every year. The yearly release cycle seems a bit artificial. Sometimes new versions release with not-so-major changes, at least that is how it appears to the naked eye. The forced version numbering also has another caveat: it renders software for non-supported hardware, like iPhone 5, to be stuck on something ugly such as `10.3.4`, likely forever.
> Fix: stick with same major version number for over 1 year.

## Safari web browser

Safari might be a good web browser to some, others dub it the new Internet Explorer.[^3] That cannot be a compliment.[^4] Although it may appear like you can install Chrome or Firefox on your device, under the hood this is not the case: they all use the Safari engine. Every browser on iOS is thus limited in some way.
> Fix: allow third party browsers and *full* support for extensions.[^5]

## Flashlight during video calls

Ever video called in a darker room? Good luck trying to turn on your flashlight when you want to show your mom your report card! iOS, flashlights, and (video) calls do not go together. Is it a hardware limitation? Was it Steve Jobs' idea?[^6] We can only guess.
> Fix: allow turning on the flashlight when video calling.

## Headphone jack

Enough has been written about this already. There is/was enough physical room.[^7] Though technically not a software issue, the fact that iOS still supports a headphone jack through its software (if you buy a $9 adapter[^8] that is) is why it makes my list.
> Fix: let Apple drill a 3.5 mm hole in the bottom (or the top) of your device and make sure the hole can communicate with wired headphones.

## Vibrator

Since iPhone 7's *Taptic Engine* that replaced the traditional vibration motor, I oversleep and miss calls more than ever. My older iPhones used to almost vibrate through my nightstand when the alarm would go off, my newer iPhone sounds feeble. Again, more of a hardware issue, but perhaps could be solved with a clever software fix.
> Fix: let iOS unleash Taptic Engine's true character and send all battery power to Taptic Engine for a loud roar.

## Bluetooth and Wi-Fi buttons

Since iOS 11, the Bluetooth and Wi-Fi buttons in *Control Center* actually leave your Bluetooth and Wi-Fi on. The buttons merely allow you to quickly connect and disconnect.[^9] Even worse, Bluetooth and Wi-Fi unexpectedly turn on in certain scenarios, even when you "disabled" them with the buttons. This is a security and privacy risk.[^10] (Apple and others can track your location this way.[^11])
> Fix: let buttons work how they used to prior to iOS 11.

## Last words

Even a near-perfect product like iPhone or [MacBook]({% post_url 2020-08-13-how-macbook-pro-or-macos-could-be-improved %}),has its flaws. As software is not the obstacle to fix these limitations, I am sure that some of them will get fixed in the future. And for those that would not get fixed, Apple might have a good reason not to. What do you feel could be improved? Let's discuss it in the comments below.

### References

[^1]: A phone capable of recording calls was my old Sony Ericsson K750i that came with this awesome [demo video](https://youtu.be/WbNJ5fbUdo4) installed
[^2]: For example, [in China no FaceTime audio calls can be placed](https://www.wakephone.com/2019/02/differences-between-the-u-s-a-china-and-japanese-versions-you-need-to-know-before-buying-iphones-in-bulk/)
[^3]: [Safari is the new Internet Explorer](https://dev.to/nektro/safari-is-the-new-internet-explorer-1df0)
[^4]: [For those of you who hate Internet Explorer (or want to know why it sucks)](http://www.ihateinternetexplorer.com/)
[^5]: For the time being, to block ads on your home network, install [Pi-hole®](https://pi-hole.net/), the best thing since sliced bread
[^6]: Since apparently Steve Jobs was [the killer of thousands of ideas](https://www.inc.com/tommy-mello/according-to-steve-jobs-only-way-to-succeed-is-to-abandon-1000-good-ideas.html)
[^7]: Watch [this](https://youtu.be/utfbE3_uAMA) video if you want to know more
[^8]: [Something that should not be necessary](https://www.apple.com/shop/product/MMX62AM/A/lightning-to-35-mm-headphone-jack-adapter)
[^9]: Read more about Bluetooth and Wi-Fi buttons at [Apple](https://support.apple.com/en-us/HT208086)
[^10]: Read more about risks related these buttons in *Control Center* at [EFF](https://www.eff.org/deeplinks/2017/10/ios-11s-misleading-ish-setting-bluetooth-and-wi-fi-bad-user-security)
[^11]: [Location tracking could be done through Bluetooth](https://www.theverge.com/2019/9/19/20867286/ios-13-bluetooth-permission-privacy-feature-apps)
