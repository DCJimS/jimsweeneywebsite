---
layout: post
title: "AWS goes down? Let's back up and look at the facts!"
---


OK.  The bashing of Amazon Web Services (AWS) after one of their Northern Virginia data centers went down as a result of major storms in the DC area a week ago is almost over.  Now it is time to look at the facts.

Did the data center lose power in the storm and go down?  Yes, it did, along with hundreds of thousands of other facilities/homes.  But let.s look at the issues.  As I have blogged about many times before and discuss thoroughly in my book .Get Your Head in the Cloud: Unraveling the Mystery for Public Sector,. many Cloud providers are designed around their data centers not going down.  Ever.  Take for example, Terremark.  You can visit their impressive facility in Culpeper, Virginia (with an appointment and a good reason, of course), where you will see multiple generators and numerous gas storage tanks.  You will hear about the contracts they have (with SLA.s ) to deliver fuel in time to keep those generators running in case of power failure. That is not how AWS is structured.

AWS is designed specifically to absorb a failure in one or more of their data centers.  Let me recap for a second.  AWS is divided into regions (there are two in the U.S., appropriately called U.S. east and U.S. west).  Within each region are multiple zones. Assuming that you have architected your application correctly, when one zone fails, virtual machines in another zone pick up the slack.   However, many newcomers to Cloud don.t understand this critical piece of information.  Therefore, they do not architect and design their application correctly.  I cannot tell you how many times I say this to potential customers:  .If you move your standard three tier application from your single data center into one zone of the AWS Cloud, you have accomplished absolutely nothing in terms of taking advantage of the flexibility, availability and redundancy of Cloud..

That.s why our Technology Leadership Seminar on Making Cloud a Reality this week (July 18th at the Ronald Reagan Building) will answer some tough questions like:

1.  How do I purchase Cloud?

2.  What applications should I move to the Cloud and why?

3.  What do I do if I am unhappy with my Cloud provider?

I suggest you register for this event today.

Now, before I close, I will tell you that AWS did in fact have trouble with their control plane that fateful Friday, meaning that communications between the failed zone (or data center) and other working zones were disrupted.  And for that, no one can take the blame except AWS.  There will be lessons learned, to be sure, and I know AWS will make changes to improve that part of their service, but knowing why it is OK for an AWS zone to go offline is what you really need to know.  This will enable you to better architect and design your application to take maximum advantage of this redundancy, availability and flexibility.  I hope to see you on the 18th!

Thanks for reading.  

*Follow me on twitter @DCJimS*
