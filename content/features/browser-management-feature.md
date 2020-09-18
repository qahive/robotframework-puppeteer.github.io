---
title: "Browser Management Feature"
type: features
date: 2018-07-12T16:54:54+06:00
description : "Robot framework puppeteer browser management demo"
category: ["features"]
submitDate: September 14, 2020
author: Atthaboon S.
---
### Open/Close browser and handle new page
RF Puppeteer allow you to open / close browser with following keywords
- Open browser
- Close Browser
- Close All Browser
- Close Puppeteer
- Switch Window
- Wait For New Window Open

#### Example: 
![Handle browser image](/images/features/browser-management-feature/demo1.jpg)
{{< gist atthaboon 2631f9e868869b5534ae49fa1071d180 >}}

- Line 9 - 11: `Wait For New Window Open` wait until new window open during click the button for open a new tab.
- Line 12: `Switch Window` switch to `NEW` open window
- Line 14: `Switch Window` switch to existing window by `window title`
