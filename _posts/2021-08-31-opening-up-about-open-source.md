---
layout: post
title: "Opening Up About Open-Source"
date: 2021-08-31
---
Last weekend, I began my week-long journey of open sourcing my Windows 11 laptop and my OnePlus 8 Android smartphone. Well, I tried at least... I say tried because I barely lasted 24 hours, even after finding plenty of alternative apps and programs required for the switch. Unfortunately, it just wasn’t a viable option for someone that does not have a lot of spare time. I'm a full time student, so I really can't afford for things to just not work as expected or fail on me. Plus, some programs I needed for certain specialized classes weren't available for Linux and had no good alternatives that would do the job. Some of these apps did a great job of replacing my current closed source counterparts, so much so that I have fully replaced them. However these were too few and far between so I had to switch back to Windows pretty quickly. However, I am open to continue using certain open source projects on my devices and continue to use custom ROMs and Linux on the respective devices. For this project, I will be using Lineage OS on my OnePlus 8 and Zorin OS on my laptop.

![Questioning Android meticulously deciding if they should go the open source or proprietary route](/images/open-source-journey.png)

### Why Go Open Source?

The number one reason for many individuals and companies to open source their projects is because many more developers around the world can see it and thus fix any bugs, improve the code, and adapt the code to their liking. I have seen so many local-music Android apps with the same base code, it’s unreal, but it allows each of those separate apps to be stable, secure, and up to date. The user can decide on their own which one to use based on preference or unique features to one platform compared to the other. It’s also very helpful for the economy too by fueling people with new ideas and because it’s way more efficient than having a small group of developers at a company work on a project themselves. You’d be surprised to know that even Apple and Microsoft have open sourced some of their work, such as Swift and Windows Calculator and even Microsoft's own code base.

![Google Keep versus Joplin](/images/keep-arrow-joplin.png)

### How Did I Prepare?

Now, before you dive right in without thinking about it, slow down and take a little look around. Research open source alternatives to your current apps you use on your phone, your laptop, and any other devices you want. Do they have the same features or maybe even better ones? Are any of your current apps already open source? Does your device meet the requirements for the software (you can’t run Windows executables on Linux that well!). Also, don’t settle for the first app you see, have a look at various options from different stores and see which one will make the best fit (F-Droid has open source only, but you can still search on APK Mirror!).


I ended up installing all of these apps onto my device! I did go a step further and flashed a custom ROM onto my phone, but you don’t have to do that if you don’t know anything about custom ROMs and other custom firmware. I will cover them in a different guide.

| Category     | Usual                           | Open Source Alternative |
| ------------ | ------------------------------- | ----------------------- |
| Note-taking  | Google Keep / OnePlus Notes     | Joplin                  |
| Music        | YouTube Music / Spotify         | Retro Music Player      |
| Messaging    | Android Messages / WhatsApp     | QKSMS and Telegram      |
| Weather      | Google / OnePlus Weather        | Geometric Weather       |
| Video        | YouTube / Streaming             | NewPipe                 |
| Email        | Gmail                           | K9 Mail                 |
| Calendar     | Google Calendar                 | Etar                    |
| Clock        | Google Clock                    | AOSP Clock              |
| Contacts     | Google Contacts                 | AOSP Contacts           |
| Dialler      | Google Phone                    | AOSP Phone              |
| Calculator   | Google Calculator               | AOSP Calculator         |
| Web Browser  | Google Chrome                   | Chromium                |
| Navigation   | Google Maps                     | None                    |
| App Store    | Google Play Store               | F-Droid                 |
| File manager | OnePlus Files / Files by Google | AOSP Files              |
| Keyboard     | Gboard                          | AOSP Keyboard           |
| Launcher     | OnePlus Launcher                | Trebuchet               |
| Mobile Pay   | Google Wallet                   | None                    |
| Passwords    | Google Passwords                | KeyPass                 |
| Social Media | Instagram / Twitter / Facebook  | Friendly / Infinity     |
| VPN          | X-VPN                           | ProtonVPN               |
| Phone Sync   | MS Your Phone                   | Zorin Connect           |
| ------------ | ------------------------------- | ----------------------- |

On Linux, I just used the default apps that come with Zorin OS, along with some of the apps listed above. Joplin and ProtonVPN are two examples of applications that worked on both Linux and Android.

### What Went Wrong?

Ah, the fun part. A lot of stuff went horribly wrong, but I will say it was partly because of me as I rushed through the whole process. I jumped ship to Lineage OS before I even knew of one open source application besides F-Droid, so I spent hours scouring F-Droid for any good apps to use when I could have already been using my device by then. Other than that misstep though, it was primarily because of the lack of general knowledge of these apps that caused the experience to go downhill. My camera app made my camera even worse than it already was, which I didn’t even know was possible. I later looked it up and found out about the Camera2 API and various other proprietary code that of course couldn’t be used, so it wasn’t technically the community’s fault, but it still was an issue. Trying to sync my notes with Joplin on Linux and Android really does not work well, for me at least. Being a college student, I didn’t exactly want to pay for a subscription I would hardly use either, which ruled out cloud storage for me completely. Then, as I went to more and more classes, my experiences dropped further and further. We used a QR code in some classes to check in, but the built-in camera couldn’t scan it and open the link and I had to search for a QR code scanner before it was too late. It took so long to figure out how to add a Google account to Etar and K-9 Mail as well, having to set up a secure ‘app password’ with Google through 2FA and using that password instead of my actual password. A lot of this stuff would be too much for your average user, including the typical tech savvy Gen Z. I eventually gave in and started using Aurora Store to install some proprietary apps such as Snapchat and WhatsApp (my family refused to switch to Telegram), but even some of those didn’t work properly because of their dependence on Google Play Services (GMS). Also, mobile social media websites are clunky and are missing a few key features.

![Fixing a bike](/images/fixing-bike-open-source.jpg)

### How Can It Be Improved?

I think the only way to get more people involved with open source is to 1) make it much more available to more types of people, and 2) make it easier to make and edit code or make it easier to learn to code for these projects. A lot of people have absolutely no clue how to code, and it really shows. I still have plenty of people who genuinely think I’m hacking the government or the college when I’m really just making a website for my programming class. The feeling you get from it is great, don’t get me wrong, but when the a key point for going open source is so the community can generate new ideas, fix bugs faster and for more competition, then that idea is flawed because of the amount of people that cannot be relied upon to keep the community going.


I would love to see open source as the main thing in the near future, but with major corporations sticking to closed source software and continuing to develop in the closed approach, I don’t see much changing any time soon. 


Please leave any comments in the post, especially if you have resources for learning to code, know of other useful open source apps, or just want to share your experiences with open source! Always feel free to comment. :)

