---
layout: post
title: "BloodlessAPI - Offline API surface mapper"
date: 2026-08-14
category: creations
image: /assets/img/light.png
---

Sometimes during a penetration test, you are given or you find `.json` of one or multiple APIs - to aid myself and others in that exact situation, I built ***"BloodlessAPI*** - it's a completely offline tool that once you paste or upload the `.json`, it creates you a map of the API, methods, params, etc. - you name it, and even suggests what's worth a look (of course, if there's sth that's even worth a look)


BloodlessAPI has 2 main themes (dark and light):
![dark](/assets/img/dark.png)

![light](/assets/img/light.png)

## Features:

- Offline - no need to upload potentially sensitive data to any website (or similar) to map the API
- Clean endpoint tree generation
- Suggests what's worth a look
- Detailed view
- One click export to Markdown (.md) or cURL, or just copy the URL
- Export all cURL
- Paste the copied .json directly
- Clean design


## Installation:
```
git clone https://github.com/SAsecurityN/BloodlessAPI.git
cd BloodlessAPI
```


## Usage:
```
python bloodlessapi.py
```

## Github page:
[BloodlessAPI on Github](https://github.com/SAsecurityN/BloodlessAPI)
