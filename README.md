# Chores

Open `index.html` or `Chores.html` in a modern browser. Both files contain the same app; no account or installation is required.

The five editable examples cover every recurring task type:

| Task | Schedule |
| --- | --- |
| Laundry | Weekly: Pending Monday, Due Today Wednesday, Overdue Thursday. |
| Water Plants | Every 7 days after completion: goes straight to Due Today, then Overdue the next day. |
| Pay Bills | Monthly: Pending on the 25th, Due Today on the last day of the month, Overdue on the 1st. |
| Make Dinner | Daily; new example defaults to **Mark as missed**. |
| Exercise | 4 times per week, resetting Monday; missed weeks are tracked separately. |

Monthly tasks have separate Pending and Due days. If Pending begins later in the month than the due day, the window runs into the next month. Days 29–31 use the last day in shorter months. A completed task stays Done until its next Pending day.

The calendar awards Perfect Week for each 7 consecutive Clean Sweeps, Rescue Mission each time an overdue day ends with nothing overdue, and Perfect Month for a Clean Sweep on every day of a full calendar month. Badges can be earned repeatedly. Today's badges are shown as "so far" until the day ends; correcting a completion updates the affected awards. Emergency Days cannot count toward a Perfect Week or Perfect Month. Planned pauses follow the usual Clean Sweep rules. Missing awards are recovered from saved daily results when the app opens. Full House has been retired.

Your tasks and completion history are saved in your browser on that device. Sharing the HTML file or ZIP shares the app and its examples, without your saved task data. Existing users keep their own tasks when the app is updated.

For an iPhone home-screen shortcut, host the app on a static website, open it in Safari, and choose Add to Home Screen. The optional home-screen icon loads from the app's repository.


## Overdue versus missed

In a task's Edit screen, **When a deadline passes** offers **Carry forward** (the original behavior: a missed obligation stays overdue until it is completed) or **Mark as missed** (the old period ends and the new period starts fresh). This setting applies to daily, weekly, and monthly tasks. *Every N days* always carries forward because its deadline is based on the last completion. *Times per Week* always resets weekly and tracks each failed week as a separate missed occurrence.

Each expired unrecorded day or period appears as its **own** red Missed card above current tasks. If you fail to record Sunday and Monday, both remain there until each is logged for the correct date or acknowledged; Monday's work never automatically satisfies Sunday's record. For quotas, each missed week shows how many sessions short it was, and backdating a session updates that historical week's count.

**Acknowledge** only changes the reminder's visibility; it does not create a completion or improve any statistics. Acknowledged cards move to the **Acknowledged misses** section at the bottom (collapsed by default) for seven days after acknowledgment. You can restore them or log the actual completion there, or manually dismiss the reminder. Expiration and dismissal hide reminders only; task history is retained.

The old completion switch has been replaced by a clearly labeled **Done today** button; an actual overdue carry-forward task instead offers **Choose date**. Use **History / Log date** to add or remove completions on a particular past date, including exercise sessions. The history also shows timestamps for changes made after this update. Older events may not have a timestamp.

Existing saved tasks **retain Carry forward** unless explicitly edited. To change a previously saved task to Mark as missed, edit that task: tracking begins with the most recent elapsed deadline (or yesterday for daily tasks) to avoid generating an enormous backlog of historical reminders. Records and awards from earlier dates are retained. New example data defaults Make Dinner to Mark as missed.
