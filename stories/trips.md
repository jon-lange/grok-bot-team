# Travel (Trips)

**Group:** Home and family  
**Use:** Active. One of the first things I handed off.

## Origin

Travel was among the first real handoffs. Before the Chief of Staff pattern existed, a travel bot was already pulling upcoming trips out of mail and calendar, flagging wrong flight times, and offering to watch for changes.

That early loop became the template: find the facts, flag what is wrong, set quiet routines that only speak when something changed, and never book without my yes.

## What it does now

Owns family trips: flights, hotels, ground transport, seats, check-in timing. Runs a daily travel-mail check and a day-before flight brief. Fills airline and airport web forms when that helps, then stops for approval. When a flight moves, it flags the mismatch and proposes the calendar fix. It does not change calendar events on its own.

## Off my plate

I do not hunt for schedule-change emails by hand. The bot watches the mailbox, flags when a flight moves, proposes the calendar fix, and briefs me the night before I fly.

![Earned-autonomy ladder](../docs/autonomy-ladder.svg)

## Autonomy

**Earned:** Quiet watches on travel mail and calendar; day-before flight briefs that report when something changed.

**Still needs a yes:** Changing calendar events when flights move (it flags and proposes the fix); booking; paying; messaging an airline or hotel; any first contact with a new vendor.
