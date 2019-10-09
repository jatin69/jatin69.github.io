---
layout: project
title:  "Codechef Contest Calendar"
bannerDescription: "Custom Google Calendar for upcoming codechef contests. Contests are scraped from the codechef website. The scraping task is run as a cron job."
techUsed: Python, Google Calendar API
githubRepo: jatin69/codechef-contest-calendar
comments: true
priority: 7
date: 2018-10-20
---

## Codechef Contest Calendar

A Custom Google Calendar for upcoming codechef contests. Contest information scraped from codechef website and added to calendar.

## Demo

Checkout the demo [here](https://jatin69.github.io/codechef-contest-calendar/)

## How to Use

### Google Calendar ( recommended )

The Calendar is publically available [here](https://calendar.google.com/calendar?cid=N2RxbWZuNm12cmVpcWIyNmpkbjVydWs1amtAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ). Simply click this link and tap `yes` on the popup for `Add to Calendar`. You can also add the calendar by visiting it [here](https://jatin69.github.io/codechef-contest-calendar/) and then using the `+` sign at the bottom right of calendar to add to your calendar.

Once added, it will sync all contests periodically. You are done.

### iCal file

You can also download the `ical` file from [here](https://calendar.google.com/calendar/ical/7dqmfn6mvreiqb26jdn5ruk5jk%40group.calendar.google.com/public/basic.ics) if you want to add all events to your primary calendar.

No sync will occur when events are added from `ical` file.

## FAQ

#### Codechef Calendar not showing up Google Calendar App?

New Calendars are sometimes hidden by default in the Calendar App. To make it visible, go to `settings` in the calendar app. You'll see a `show more` button under your id. Tap it, select `Codechef Contest Calendar` and turn the `sync` on.
Calendar will now show in your main calendar. If you want to hide it at any point of time, open the side menu and simply unset the checkbox in front of the calendar.

#### I accidently added all events from ical file. How do i delete them?

There isn't an official way to delete them. However [this post](http://blog.tomverhoeff.nl/2011/01/31/howto-undo-ical-import-in-google-calendar/) might be handy. 
Simply open the `ical` file in a text editor & replace all occurences of `CONFIRMED` with `CANCELLED` & re-import the file. This should delete all the events. Good luck.

## Future plans

- setup a cron job on cloud to run the scraper script periodically.
