---
title: "a bot tracking the James Webb space telescope"
date: "2022-08-06"
---
**edit: X (formerly known as Twitter) has changed their API policy, making this bot no longer easily operable for free, so I've shut it down.**

I like space, and when the James Webb space telescope launched in 2022, I was fascinated with the fact that it was constantly changing observation targets, multiple times per day. Astronomers have a time-sharing system where they submit observation proposals which are then reviewed and approved based on scientific impact

I found the [observation schedules](https://www.stsci.edu/jwst/science-execution/observing-schedules) online, but they were in a really brutish format -- not very readable!

So, I made a Python bot which fetches these schedules, parses them, and then constantly queries for new observation events. Assuming the schedules are kept up-to-date, it will post a tweet in real time when the telescope begins observing a new target

Most of the time when I hear about a new scientific discovery, I learn it was actually completed months or years ago, and only recently published. I like these public observing schedules because each entry has the potential to discover something new about the universe -- and we can follow along in real-time!
      
I am happy to help bring these updates to a broader community -- and hopefully it excites more people about the real-time science being done here!

### links 
[github repository](https://github.com/mataslauzadis/JWST-Observations)

[twitter account](https://twitter.com/JWSTObservation)