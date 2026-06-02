---
title: "Update Set sys_ids: What Actually Happens When You Move Them Between Instances"
url: "https://www.servicenow.com/community/developer-blog/update-set-sys-ids-what-actually-happens-when-you-move-them/ba-p/3550415"
date: "2026-05-28"
author: "Daniel Draes"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/board?board.id=developer-blog"
---
You've built a #ReleaseOps pipeline and want to run an Instance Scan against freshly committed update sets in TEST as a quality gate. You wire it up, point it at TEST, feed it the sys_ids from the deployment request — and it fails. The update sets can't be found The sys_ids you have are from DEV.
