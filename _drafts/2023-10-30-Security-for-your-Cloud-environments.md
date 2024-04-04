---
layout: post
title: "Security for you Cloud Environments"
date: 2024-03-11
categories: security
---


March 11, 2024

Ages ago, I told you all I  was going to write only on startups and focus
less on technology.  But I can't do it.  As much as I love the
startup community in the DMV area, and I am still actively involed, I still love technology
and I truely believe that technology can help us all live better lives.

Especially in the area of security.  I remember in the old days, when I
had my first Linux server hosted in Northern Virginia, I would peruse
the logs and see the numebr of "script kiddies" that were trying to log
into my linux bow with the username of "administrator".  I was thrilled 
when I found a firewall script that automatically threw all login
attempts from a certain IP address on the floor for an hour after three unsuccessfull login attempts.

Move forward about 20 years and boy have things changed.  Changed a lot!  I am now
working for a security company.  (I have almost always in my life been
on the infrastructure side of things). So taking my infrastructure knowledge and marrying that with 
new security technologies to keep infrastructure safe. It is a real "Drinking from the firehose" situation.

Now "bad actors" are everywhere and I'm now seeing FIRST HAND the attacks that happening in real time for our customers. In fact, as part of my position, I am now working side by side with a customer that was a victim of a ransomware attack a year ago.

So big deal.  Lots of people are involved in cyber-security these days.  ("Your honor, I have a point, I promise".  Judge: "Then make it"). So why... in these crazy times where new hacks are in the news it seems daily, are companies still not even doing the minimal security?

Im talking thing like:
    1.  Leaving default passwords in place
    2.  Leaving access to storage open to the world
    3.  Leaving RDP access to virtual machines open to the world
    4.  Not forcing all users to rotate their passwords 

Here is just a couple of examples.  I am working with a company now where 
the head of all infrastructure for the company shared one password for all 
of his accounts and it had never been rotated! In another, I showed up only 
to find that RDP access to all of their cloud virtual machines was open to 
the world.  When I inquired about it, I was told "Yeah. but you still need 
a username and password".  My reply was simple "OK, username is 
Administrator....and I am half way there!" (They finally agreed that they 
should in fact, lock down that access).
 
Until then, thanks for reading. Follow me on twitter at @DCJimS.
