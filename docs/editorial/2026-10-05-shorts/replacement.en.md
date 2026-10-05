---
title: "How to Block YouTube Shorts: Hide Desktop Feeds and Limit Mobile Viewing"
date: 2026-03-29T16:00:00+09:00
lastmod: 2026-10-05T13:00:00+09:00
draft: true
categories: ["Productivity", "Tech"]
tags: ["Digital Detox", "YouTube", "Focus", "Unhook"]
author: "Tikklabs Editor"
slug: "how-to-block-youtube-shorts"
translationKey: "youtube-shorts-guide"
cover:
  image: "/images/focus_thumbnail.png"
  alt: "An illustration of focusing on a laptop"
description: "Hide YouTube recommendations in a desktop browser and set a mobile Shorts feed limit, with clear explanations of what each method can and cannot do."
showToc: true
---

If a quick YouTube search keeps turning into a long viewing session, changing what appears on screen may help. Start by distinguishing **reducing recommendations, hiding interface elements, and setting a viewing limit**. These controls have different scopes.

This replacement draft was checked against official documentation and developer listings on October 5, 2026. It is not a hands-on installation or device test.

## Choose a method for your device

| Environment | Method | Scope and limitation |
|---|---|---|
| Desktop Chrome, Edge, Firefox | Unhook | Hides elements in that browser. Does not configure the YouTube app or other browsers. |
| Firefox for Android | Unhook | The developer lists mobile-web support. Does not affect the native app. |
| Android or iPhone YouTube app | Shorts feed limit | Includes zero minutes; personal-account reminders can be ignored. |
| App Home feed | Show fewer Shorts | Recommendation feedback, rather than an access block. |
| Account history settings | Delete and turn off watch history | YouTube documents this for removing Home recommendations; deletion loses existing history. |

## Desktop: hide recommendations with Unhook

Install through the developer's official listing, checking that the publisher is Unhook.

- [Chrome listing](https://chromewebstore.google.com/detail/unhook-remove-youtube-rec/khncfooichmfjbepaaaebmommgaepoid)
- [Firefox listing](https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos/)
- [Edge listing](https://microsoftedge.microsoft.com/addons/detail/unhook-remove-youtube-r/hebpjnnclppdnfghdnmhgdljmjpfhggk)

1. Install the extension and reload YouTube.
2. Open its popup and enable **Hide Homepage Feed**.
3. Enable its Shorts option. The Chrome description lists **Hide YouTube Shorts**, while Firefox lists **Hide Shorts Tab**; labels can differ.
4. Optionally hide related videos and disable autoplay.
5. Check Home, search results, a regular video and a direct Shorts link separately.

Hiding the interface does not establish that every Shorts URL is inaccessible. YouTube changes can also affect the result. If normal viewing breaks, turn options off individually or disable the extension and reload.

## Mobile app: set a Shorts feed limit

YouTube's official instructions specify signing in, opening **You → Settings → Time management → Shorts feed limit**, then selecting a duration, including zero.

When the limit is reached, a reminder appears. The documentation says users can dismiss or ignore it. Treat this personal-account setting as a viewing reminder, not an irreversible lock. If the menu is missing, check your app update and account state against the current help page. Do not assume the same setting works on desktop web.

[Official instructions: Set a Shorts feed limit](https://support.google.com/youtube/answer/16671528?hl=en)

## Reduce recommendations without an extension

In the app's Home feed, open the menu above a Shorts grid and choose **Show fewer Shorts**. This reduces recommendations; it does not remove access to every Short.

YouTube also documents deleting and turning off watch history if you do not want Home recommendations. Deletion loses your previous watch history, so consider whether that trade-off is necessary. This is not a Shorts-only control.

[Official instructions: Manage recommendations and search results](https://support.google.com/youtube/answer/6342839?hl=en)

## Before using uBlock Origin filters

The previous article's rules were cosmetic filters, not network filters. Their ability to remove the entire Home feed was not established. The first selector, `ytd-rich-grid-row`, can match rows without checking whether they contain Shorts, potentially hiding regular videos too.

Current Chrome no longer supports the Manifest V2 extension framework used by original uBlock Origin. Firefox's uBlock Origin and uBlock Origin Lite should not be presented as the same product with identical settings.

This draft does not replace those rules with another untested snippet. Any future filter example needs testing in the named browser and extension version across Home, search, subscriptions, regular videos and Shorts.

[Developer documentation: uBlock Origin](https://github.com/gorhill/uBlock)
[Chrome documentation: Manifest V2 timeline](https://developer.chrome.com/docs/extensions/develop/migrate/mv2-deprecation-timeline)

## Measure the effect on your own use

These settings cannot guarantee a particular number of hours saved. Compare your viewing time and interruptions for a few days before and after making a change.

The purpose is to make intentional searches and viewing easier. Claims about dopamine levels, brain changes or medical treatment are not needed to explain these controls.

[Related article: Stone-age brain vs GPT](/post/stone-age-brain-vs-gpt/)
