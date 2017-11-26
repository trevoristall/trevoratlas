---
layout: post
title: "Facebook Ad Blocking"
date: 2016-10-22
categories:
featured_image: /images/facebook-ads.jpg
---

If you want to block sidebar ads on Facebook now that they changed it to be harder to block:

Assuming you are using [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en) (you should be)


1. Click the extension button

2. Click the eyedropper and it will bring up the rule creation dialog.

3. Paste the following text into that text area:

```css
###rightCol div:nth-child(n+5)
##.ego_unit
```

That's it! Your sidebar should now resemble this:

![alt facebook sidebar](https://i.imgur.com/hKoILRY.png)
