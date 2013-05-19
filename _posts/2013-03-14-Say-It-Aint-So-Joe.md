---
layout: post
title: "Say It Ain't So, Joe!"
---


First, let me take a moment to say that I am thrilled to be part of the V3 team!  As the newest member of the management team, I can tell you that this is an exciting time to be here.  Desktop virtualization deployments are expected to significantly increase over the next few years and we have some exciting technology that is making desktop virtualization a  viable, cost-effective and smart option for companies today.

I recently came across a Desktop Virtualization Trends survey done by Gartner in December of last year. (See the full report).  As you might expect, this survey begins with the majority of respondents selecting lower TCO and OPEX costs and follow-me/anywhere desktop features as the main business drivers for adopting desktop virtualization. 

Also as expected, respondents were pretty evenly split between using VMware and Citrix virtualization stacks, with Microsoft starting to make a real showing.  But it quickly goes downhill from there.

Here is where the problem lies.  Almost 60% of the survey respondents selected Enterprise Storage Array as their storage choice for desktop virtualization deployments.  Yet enterprise storage has been proven time and time again to be the wrong choice for virtual desktop deployments, and I have the numbers to back it up!  Take, for example, Children’s Hospital of Birmingham, Al. (The full case study is here).  While you can read the case study (it’s only 4 pages), the facts are clear. 

Enterprise storage and a few networking issues got the hospital to a performance metric that was totally unacceptable to them.  To be plain, it was taking them 1 minute and 15 seconds to load a virtual desktop.  Many of us, including me, do not possess the virtue of patience (a fact that my 5th grade nun pointed out to me every day of that very long school year); but even for those folks who are patient, this is an unacceptable performance metric!  Fixing the network issues only reduced this time to 50 seconds, which is better, but still unacceptable for the users. 

Here is how V3’s Appliance improved the bottom line.  With absolutely no tuning of the master image, a new pool was created using the V3 Appliance, and immediately the load time was reduced to approximately 22 seconds. That’s a 50% performance increase simply by switching to an appliance approach!

There are many good reasons for selecting an appliance approach, and performance is definitely one of the first on the list. For this reason, we recommend that you use your enterprise storage only for user data (like file shares and such), since virtualized desktops require faster performance than enterprise storage can deliver.  Let’s face it: Desktop OSs were not built to wait while bits travel through SAN switches to the SAN and then back again to the desktop OS.  

When you are looking at Desktop Virtualization projects or pilots, you need to be looking at the appliance approach.  In future posts, I’ll tell you what V3 has that makes us the leader of all the appliances, but for now…….

Thanks for reading.

Follow me on twitter at @V3Jim



