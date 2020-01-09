---
layout: project
title:  "Codechef Contest Calendar"
bannerDescription: "Custom Google Calendar for upcoming codechef contests. Contests are scraped from the codechef website. The scraping task is run as a cron job."
techUsed: Python, Google Calendar API
githubRepo: jatin69/codechef-contest-calendar
comments: true
priority: 4
date: 2018-10-20
---

## Codechef Contest Calendar

A Custom Google Calendar for upcoming codechef contests. Contest information scraped from codechef website and added to calendar.

## Demo

Checkout the demo [here](https://jatin69.github.io/codechef-contest-calendar/)

## How to Use

### Add to Google Calendar

- The Calendar is publically available [here](https://calendar.google.com/calendar?cid=N2RxbWZuNm12cmVpcWIyNmpkbjVydWs1amtAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ). Simply click this link and tap `yes` on the popup for `Add to Calendar`.
- Alternatively, you can also add the calendar by visiting [the demo](https://jatin69.github.io/codechef-contest-calendar/) and then using the `+` sign at the bottom right of calendar to add to your calendar.

Once added, it will sync all contests periodically. You are done.

If you still can't see the events, or the calendar in your google calendar android app, this is because, new Calendars are sometimes hidden by default in the Calendar App. To make it visible, go to `settings` in the calendar app. You'll see a `show more` button under your id which you used to add the calendar. Tap it, select `Codechef Contest Calendar` and turn the `sync` on.

Calendar will now show in your main calendar. If you want to hide it at any point of time, open the side menu and simply unset the checkbox in front of the calendar.

## Dev

- we first scraped events from codechef website
- Then added them on a newly made google calendar
- Then setup a cron job to periodically auto update the calendar
- Then simply add the calendar to your google account and it'll show up in your google calendar app.

For more details, visit the project on github.