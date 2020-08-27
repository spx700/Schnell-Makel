# Schnell-Makel
This project is an attempt to develop a general distributed system (be it ticket bookings or online payments) which has ginormously high concurrency and success rate.
## Mission behind the project
Couple of weeks ago I came across a post on Quora where a fellow Quorian asked the **Indian Railway Catering And Tourism Corporation** (IRCTC) through an RTI about their systems and handling high number of concurrent requests. From that post, I came to know that IRCTC has a better infrastructure than Facebook (IRCTC can allow a maximum number of 500,000 requests at a time whereas for facebook this number is 485,000). Inspite of having a better infrastructure the realtime stats are way lower than theoretically stated. <br/> 
This called for a better development on software side of the systems. And from there this idea of developing one such distributed system offering an efficient ability to handle several thousand requests every second.
## Deciding through technology
When it comes to handle concurrency, we (me and my friend, the co-author) thought nothing could be better than **Go**. As far as the frameworks are concerned, after spending a good time on deciding between Revel and Beego we came down to using Beego for the project for its enhanced support in the community.


