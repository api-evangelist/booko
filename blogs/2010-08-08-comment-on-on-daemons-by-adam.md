---
title: "Comment on On Daemons by Adam"
url: "https://blog.booko.com.au/2010/08/07/on-daemons/#comment-68"
date: "2010-08-08"
author: "Adam"
feed_url: "https://blog.booko.com.au/comments/feed/"
---
Have you tried the @reboot in Cron? https://help.ubuntu.com/community/CronHowto You probably just need to add: @reboot /usr/bin/service fetcher start FID=0 @reboot /usr/bin/service fetcher start FID=1
