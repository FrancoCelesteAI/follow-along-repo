---
name: site-check
description: Checks the small business website in this folder before a customer sees it. Compares every fact on the page with business-facts.md, checks links and buttons, checks the phone layout, and reports in plain words. Use when the person types /site-check or asks "is my site ready", "check my website", or "check the page".
---

# Site check

Check the website in this folder the way a careful owner would before showing it to a customer. Do not change any file. Report only.

## Steps

1. Find the page. Look for `index.html` in this folder. If there is no HTML file, say so and stop.
2. **Facts.** Read `business-facts.md`. Read the page. List every fact on the page (name, hours, prices, phone, email, address, rules) and mark each one:
   - MATCHES the facts file
   - DIFFERENT from the facts file (show both)
   - NOT IN the facts file (it may have been invented)
3. **Links and buttons.** For every link and button, say where it goes. Flag any that go nowhere.
4. **Phone.** Read the CSS. Flag anything with a fixed width wider than a phone screen, text smaller than 16 pixels, or buttons that look smaller than a fingertip.
5. **Pictures.** List every image and say whether it is a placeholder.
6. **Leftovers.** Flag placeholder text such as "Lorem ipsum" or "TODO".

## Report

Use this shape, in plain words, no jargon:

```
SITE CHECK

Facts:      X match, Y different, Z not in your facts file
Links:      X work, Y go nowhere
Phone:      ready / needs work
Pictures:   X placeholders to replace
Leftovers:  none / list

Fix first:
1. ...
2. ...
3. ...
```

End with one sentence: ready to show a customer, or not yet, and why.
