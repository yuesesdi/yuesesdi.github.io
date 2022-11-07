---
layout: post
title:  "9.15.14 Release Notes"
date:   2022-11-5 12:00:00 +0800
categories: blog
---

# Version 9.15.14

Yuesesdi requires Accessibility service to achieve the auto-dial feature. The release of version 9.15.14 introduces a friendly approach to requesting Accessibility service. The default call-to-action now automatically opens the dialer with the generated USSD code.

![Preview of dialog requesting Accessibility permission](/assets/dialog_ask_accessibility.png)

At startup, version 9.15.14 pops up a dialog requesting for permission in enabling the Accessibility service. The user can then have the option to stop showing the dialog on the next launch.

- Dialer is now the default call-to-action
- Auto-dial feature requires the Accessibility service permission
- Dark mode is not available when Accessibility service is not enabled
