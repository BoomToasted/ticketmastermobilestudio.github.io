---
title: "Google Assistant Development for Android Devs (Part 1)"
author: Patrick Jackson
categories: Development
featured-image: https://storage.googleapis.com/banjotms.appspot.com/actions-on-google-kotlin-share.png
tags: [Google Assistant, Actions on Google, conversational interfaces, Android, Kotlin]
---


![](https://storage.googleapis.com/banjotms.appspot.com/assistant_surfaces.png)

There is a lot of buzz and excitement around the [Google Assistant Actions](https://developers.google.com/actions/){:target='_blank'}, and with good reason:  this is an entirely new platform for building experiences for multiple devices.  Building a conversational Action with Google Assistant means it will be available on Android, iOS, Google Home, and others as they become available.

<!--more-->

Actions on Google are third-party apps that can be built using Google's APIs.  Actions extend what the Google Assistant can do by allowing a conversation between the user and your Action.  They can be accessed with trigger words such as 'Ok Google, talk to Ticketmaster', or 'Ok Google, ask Ticketmaster to find a Yankees game this weekend'. (Ticketmaster Action coming soon!)

![](https://storage.googleapis.com/banjotms.appspot.com/basic_card_300.png)

At Ticketmaster Mobile Studio, we decided to leverage our expertise with Kotlin/Java, IntelliJ, and Gradle.  This also allows us to reuse some code with Android apps.  Unfortunately, the documentation and examples are only in Node.js and Java/Kotlin is not officially supported.

Looking through the JSON specs and creating response objects to match is pretty tedious, so we have decided to open source an [Actions on Google Kotlin/Java SDK](https://github.com/TicketmasterMobileStudio/actions-on-google-kotlin){:target='_github'}.  This is an early release and we will be adding functionality, with a goal of matching the official SDK.  Currently, all the conversation components are supported.  Using the Kotlin SDK you can get up and running in no time.  And since Kotlin has great interoperability with Java, you can use it from Java as well.

 
Over the next few weeks, I'll be posting about our experience building an Action from the perspective of an Android developer, as well as some updates on the [Actions on Google Kotlin/Java SDK.](https://github.com/TicketmasterMobileStudio/actions-on-google-kotlin){:target='_github'}
