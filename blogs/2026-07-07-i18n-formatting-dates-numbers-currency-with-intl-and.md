---
title: "i18n Formatting: Dates, Numbers & Currency with Intl and i18next (2026 Guide)"
url: "https://www.locize.com/blog/i18n-formatting"
date: "2026-07-07"
feed_url: "https://www.locize.com/feed.xml"
---
Hand-rolled "$" + toFixed(2) formatting is a bug in most locales: 1,234.56 is 1.234,56 in German and 1 234 567,89 in French, and yen has no decimal places. This guide covers Intl.NumberFormat, DateTimeFormat, RelativeTimeFormat, and how i18next wires them into translation strings with {{val, number}}, currency, datetime and custom formatters.
