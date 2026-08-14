---
layout: post
title: "JSlooting - JavaScript files analysis for sensitive/interesting info"
date: 2026-08-14
category: creations
image: /assets/img/screenshot1.png
---

During one of my pentests, I have encountered a `.js` file that became a foundational stone in a chain that ended with Admin access, you can read that exact story on my Medium: [How a JS file led to Admin Access](https://medium.com/@0trccccc/how-a-javascript-file-led-me-to-an-admin-access-3acd501ecdc9)

During another pentest, I encountered a `.js` file that exposed API keys.

However, there was one problem with those `.js` files - I had to manually dig through them, `CTRL + F` and search for interesting info, and so on - that's why I decided to build ***JSlooting*** - a tool for extraction and finding of interesting/sensitive information, like:

- Secrets / API Keys
- IP Addresses
- Emails
- Hosts / Subdomains
- URLs
- Cloud storage buckets

...from the uploaded or pasted `.js`

Here's a quick look at the tool:
![img1](/assets/img/screensh.png)

![img2](/assets/img/screenshot1.png)

## Installation:
```bash
git clone https://github.com/SAsecurityN/JSlooting.git
cd JSlooting
```

## Usage:
```bash
python3 jslooting.py
```

## Github page:
[JSlooting on GitHub](https://github.com/SAsecurityN/JSlooting)
