---
title: "Filtering Intune Records from the Last 24 Hours in ServiceNow Using the Execute Before Script"
url: "https://www.servicenow.com/community/developer-blog/filtering-intune-records-from-the-last-24-hours-in-servicenow/ba-p/3536042"
date: "Sun, 10 May 2026 11:47:41 GMT"
author: "Jaspal Singh"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/board?board.id=developer-blog"
---
Intune does not natively support rolling time-window filters such as “updated within the last 24 hours.” However, ServiceNow’s Robust Transformer can handle this effectively. Here’s a clean approach using an Execute Before Script with timestamp millisecond comparison to achieve the same outcome.
