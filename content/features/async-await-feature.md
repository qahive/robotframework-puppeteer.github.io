---
title: "Async Await Feature"
type: features
date: 2018-07-12T16:54:54+06:00
description : "Robot framework puppeteer async & await demo"
category: ["features"]
submitDate: September 14, 2020
author: Atthaboon S.
---
RF Puppeteer allow to interact with UI Element using `Run Async Keywords` keyword.

**Run Async Keywords** allow to combine multiple synchronous keywords and run all keywords at the same time *(asynchronous)*.

#### Example: 
Login with valid password will redirect to login welcome page.
![Login form page image](/images/features/form-handler-feature/login-form-success.jpg)
{{< gist atthaboon 5ab1565fb847e6e64eddc952bcbe788f >}}

**Run Async Keywords** on line 11 that cover keywords line 12 - 13. This will make keyword `Wait For New Window Open` and `Click Element` run as asynchronous.

**AND** on line 12 required for join multiple keywords.
