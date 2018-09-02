# Days of the Week Datapack

> A small datapack which displays the day of the week when the sun rises.

![Example of it in action](https://i.imgur.com/cdfqvua.png)

## Notes
You will need the [TimeTools datapack](https://github.com/Brecert/TimeTools-Datapack) installed to use this datapack

Everything in this small pack assumes that your `tt.WEEK` is 7 days.

Since this is a gameplay mechanic it's not really meant to be used like an api, but for documentation purposes they are listed here anyways.

<br>

## Functions
`dspd:display_date`
```
displays the day of the week to everyone.
```

<br>

`dspd:clock : minecraft:tick`
```
executes dspd:display_date if it's the begining of the day
```
