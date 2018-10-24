# cron-countdown-viz
General idea is to input cronjob expression, and give back a "Time till cron execution"

Example:
```
30 2 * * *
```
Then figure out local time/timezone and calculate how long till the job executes
