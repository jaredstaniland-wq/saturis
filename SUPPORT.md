# Saturis — help & support


a real help page cuts one-star reviews that were really support questions.

**Email: saturisapp@gmail.com** — replies within two business days.

---

## Getting started

### How accurate does my pool volume need to be?
Within about 10%. Every dose scales directly with volume, so a 10% error means a 10%
error in the dose, which is well inside the tolerance of a home test kit. If you do not
know it, use Tools › Pool volume and measure the length, width and the depth about
halfway between the shallow and deep ends.

### Do I have to test everything every time?
No. Enter what you measured and skip the rest. Saturis advises on what it was given and
tells you which missing reading is holding it back.

A sensible rhythm: chlorine and pH weekly through the season, alkalinity every couple of
weeks, calcium hardness and stabiliser once a month. Saturis carries the slow-moving
readings forward for you and labels them so you know they are not fresh.

### Why is it asking for my region as well as my units?
Because they are different questions. Units decide whether you see millilitres or fluid
ounces. Region decides which products Saturis doses for — Australian liquid chlorine is
12.5%, US trade chlorine is 10%, and household bleach is 8.25%. The same "add 500 mL"
answer would be wrong for two of those three.

---

## Why the numbers look different to what I expected

### The app wants far more chlorine than the bottle says
Almost certainly because your stabiliser is high. Cyanuric acid binds most of the
chlorine in your water into a reserve that is not sanitising anything, so the level you
actually need scales with it. Saturis targets roughly 11.5% of your CYA for a hand-dosed
pool and about 5% for a salt-water chlorinator.

At CYA 30, three parts per million is fine. At CYA 90, three parts per million is nearly
useless — and that is the most common reason a pool goes green while the test strip still
looks acceptable.

If your CYA has climbed above about 60 for a chlorine pool or 90 for a salt pool, the
real fix is to dilute some water out. Tools › Dilute works out how much.

### My alkalinity reading dropped after I added acid, and I did not want that
That is unavoidable. Acid removes alkalinity and pH together; nothing moves one without
the other. Saturis tells you in advance how much alkalinity a dose will cost.

If you want the alkalinity down but the pH back up, add the acid and then **aerate** —
point a return jet at the surface, or run a water feature. Aeration drives off carbon
dioxide, which lifts pH without putting the alkalinity back. That is the whole trick to
lowering alkalinity, and it is why the app suggests it.

### The app told me to add nothing
Then add nothing. If every reading you gave it is inside its range, your water is fine.
Saturis will not invent a job for you.

### My saturation index is negative but everything reads "in range"
That is exactly the situation the index exists to catch. pH, alkalinity, calcium and
temperature interact, so water where each number is individually acceptable can still be
dissolving plaster or grout. Raising calcium hardness is usually the most durable fix,
because unlike pH it does not drift back.

### Saturis split my dose into stages
On purpose. Stabiliser and calcium cannot be removed except by draining water, and large
alkalinity swings cloud the pool and overshoot pH. Add the first stage, run the pump,
re-test, and the app will tell you what is left.

---

## Reminders

### My reminders are not appearing
Check three things, in order:

1. Care › Allow reminders, and confirm Android granted the permission.
2. Android Settings › Apps › Saturis › Notifications is switched on.
3. Battery optimisation. Some manufacturers — Samsung, Xiaomi, Huawei, OPPO and OnePlus
   in particular — aggressively suspend background work. Set Saturis to "unrestricted"
   or "not optimised" for battery.

Saturis uses inexact alarms deliberately, so a reminder may arrive up to an hour or so
after the time you set. That is a considered trade: asking Android for exact-alarm
privileges to remind you to backwash a filter is not a good use of your battery.

### The free app only reminds me about one thing
Correct. The free tier schedules your single most urgent reminder. Pro schedules all of
them.

---

## Data and backups

### Where is my data?
On your phone, in Saturis' own private storage. There is no account and no server, and
Saturis makes no network requests of its own, so there is nowhere for your information to
go. The `INTERNET` permission you may see listed comes from Google Play Billing, which
handles the Pro purchase and talks to Google, not to us.

### Will my history survive a new phone?
Usually, yes. Android's built-in backup includes Saturis' data file in the backup your
phone already makes to your Google account, and it is restored during setup on the new
device.

Because that is Android's mechanism rather than ours, treat it as very likely rather than
guaranteed. If the history matters to you, use Settings › Export a backup and keep the
file somewhere safe. It is readable JSON, and it restores on any device.

### How do I delete everything?
Settings › Erase everything, then type ERASE to confirm. Uninstalling the app does the
same thing. Neither is reversible, so export a backup first if there is any doubt.

---

## Saturis Pro

### Is it a subscription?
No. One payment, no renewal, no expiry. It is not a subscription and never will be.

### I paid but the app still shows the free tier
Open the upgrade screen and tap "Already bought it? Restore". The unlock is tied to your
Google account, so make sure the device is signed in to the account you bought it with.
If it still does not appear, email saturisapp@gmail.com with the order number from your
Google Play receipt.

### Can I get a refund?
Refunds are handled by Google Play. Within 48 hours of purchase you can usually request
one directly through your Play order history. Outside that window, ask Google — and if
they decline and you think you have a fair case, email us and we will take a look.

### What is deliberately not behind the paywall?
Anything safety related. Doses, warnings, handling instructions, the saturation index
read-out and chlorine targets scaled to your stabiliser are free for everyone, forever.

---

## Reporting a problem

### I think a dose is wrong
Please tell us, and be specific. Email saturisapp@gmail.com with:

- your pool volume and the units you have selected;
- the region setting and the exact product you had selected;
- every reading you entered;
- the dose the app gave, and what you expected instead.

Saturis' chemistry is derived from molar masses rather than lookup tables and is pinned
against published reference doses in an automated test suite, but no engine is beyond
correction — and a wrong dose is the most serious bug this app can have. We take these
first.

### Something crashed or looks broken
Email saturisapp@gmail.com with your phone model, Android version, the app version from
Settings › About, and what you were doing. A screenshot helps more than a description.

### Can you add a feature?
Ask. The roadmap is shaped by what people actually write in. Phosphate and metals
testing, a photo-based test-strip reader, and Wear OS are the most requested so far.
