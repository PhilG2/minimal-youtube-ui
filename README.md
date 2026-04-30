# Minimal-YouTube-UI
An uBlock filter list for minimal YouTube UI
some additional included non UI rules:
- members only content filtered by the "members only" text on the start page

Note: Using this filter list slightly increases YouTube video load times

Removes the transcript and queue as well, since they cannot be kept without also keeping the recommended videos sidebar, which shows as an empty box when unused/recommendations are blocked. The queue can still be accessed in fullscreen mode. I haven't found a way without disabling the ###secondary filter .

hide all shorts:
https://github.com/gijsdev/ublock-hide-yt-shorts
