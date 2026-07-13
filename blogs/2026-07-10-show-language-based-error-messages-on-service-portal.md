---
title: "Show language-based error messages on service portal"
url: "https://www.servicenow.com/community/developer-blog/show-language-based-error-messages-on-service-portal/ba-p/3571670"
date: "2026-07-10"
author: "Nilesh Pol"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/board?board.id=developer-blog"
---
In ServiceNow Portal (Service Portal / Employee Center), if you want to show language-based error messages without much custom development and as close as possible to OOTB (Out of the Box), use Message Translation and gs.getMessage(). Use System Localization Messages (Recommended): Navigate to: System Localization → Messages Create a message: Key: invalid_user_error Message (English): Invalid user selected. Create translations for the same key: Language: French → Utilisateur non valide sélectionné.
