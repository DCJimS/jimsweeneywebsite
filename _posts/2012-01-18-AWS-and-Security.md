---
layout: post
title: "AWS and Security"
---


Recently an article came to light about a group of German researchers that found **Massive Security Flaws** in the Amazon Cloud (full article can be found here). This was a well done study that I am familiar with and I am sure the 
findings are pretty accurate. After all, how many of our users would patch their machines regularly, backup their critical data on a regular basis, and change their passwords on a frequent schedule without us in IT sending them 
reminders or enforcing some other harsher policy which necessitates that they follow a schedule for these things? 
A darned few, in my experience.

The same is true here. The good news: Anyone can give a credit card to Amazon and have a virtual server in a few minutes. But Amazon clearly states that they take care of physical security, hardware, network, storage, and virtualization layer [details can be found here](http://aws.amazon.com/articles/1697?_encoding=UTF8&jiveRedirect=1).  The users are responsible for passwords and credentials, OS, and application patches and the like. The bad news: Most users don't do all the things they need to do to protect themselves.

Therefore, I just don't see the big deal. You may be able to hack into those virtual machines because of lax security on the part of the user, but if I take all the precautions that I should (like patching of the OS and application, proper credential security policies, and encryption of data, etc.), then it will be much harder to hack into mine.

I liken this to SSID and other security issues around wireless. As a best practice, my home SSID broadcast is disabled.  I need your MAC address before letting you onto my network (even if you do figure out the SSID) and all traffic is encrypted with a password that changes on a regular basis. But around my home and office are Network Access Points with none of these simple security policies implemented that are wide open to anyone. Which one do you think is more secure? Which one(s) do you think hackers will try to exploit first?

The researchers are going to present their finding in March.  To me, this report tells us what we already know; use best practices when putting applications and data in the public cloud and you'll be just fine!

Thanks for reading.

*Follow me on twitter at @DCJimS*

