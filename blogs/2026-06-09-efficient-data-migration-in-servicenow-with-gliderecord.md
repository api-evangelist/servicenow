---
title: "Efficient Data Migration in ServiceNow with GlideRecord.chooseWindow()"
url: "https://www.servicenow.com/community/developer-blog/efficient-data-migration-in-servicenow-with-gliderecord/ba-p/3556587"
date: "2026-06-09"
author: "Ratnakar7"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/board?board.id=developer-blog"
---
Running bulk updates or migrations in ServiceNow without batching can slow down your instance and create long-running transactions. In this post, we'll look at how GlideRecord.chooseWindow() works like server-side pagination, helping you process records in controlled chunks, improve scalability, and keep large data operations safer and more predictable.
