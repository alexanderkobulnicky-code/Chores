# Chores

Open `index.html` or `Chores.html` in a modern browser. The app works as a single HTML file; no account or installation is required.

The five editable examples cover every recurring task type:

| Task | Schedule |
| --- | --- |
| Laundry | Weekly: Pending Monday, Due Today Wednesday, Overdue Thursday. |
| Water Plants | Every 7 days after completion: goes straight to Due Today, then Overdue the next day. |
| Pay Bills | Monthly: Pending on the 25th, Due Today on the last day of the month, Overdue on the 1st. |
| Make Dinner | Daily. Can be configured to expire rather than carry forward. |
| Exercise | 4 times per week, resetting Monday. Each finished week is assessed separately. |

Each recurring task has a deadline behavior in its editor: **Carry forward** (the original Overdue model) or **Mark as missed** (a deadline expires without making the next period overdue). Every older unrecorded expired occurrence gets its own red card, so Sunday and Monday dinners remain separate until resolved. Acknowledging a missed occurrence moves it to the bottom of the list without recording a completion. It stays there up to seven days after acknowledgment, can be restored, logged or dismissed sooner, and then automatically leaves the active view. Acknowledgments never change completion records; the **History** button allows correcting dates later. Existing non-quota tasks keep the carry-forward behavior until explicitly edited; weekly quotas inherently reset each week.

Today's completions use explicit buttons rather than adjacent sliders. Backdated entries ask for confirmation, with separate date and entry-time records in the History view for newly logged activity.

Monthly tasks have separate Pending and Due days. If Pending begins later in the month than the due day, the window runs into the next month. Days 29–31 use the last day in shorter months. A completed task stays Done until its next Pending day.

The calendar awards Perfect Week for each 7 consecutive Clean Sweeps, Rescue Mission each time an overdue day ends with nothing overdue, and Perfect Month for a Clean Sweep on every day of a full calendar month. Badges can be earned repeatedly. Today's badges are shown as "so far" until the day ends; correcting a completion updates the affected awards. Emergency Days cannot count toward a Perfect Week or Perfect Month. Planned pauses follow the usual Clean Sweep rules. Missing awards are recovered from saved daily results when the app opens. Full House has been retired.

Your tasks and completion history are saved in your browser on that device. Sharing the HTML file or ZIP shares the app and its examples, without your saved task data. Existing users keep their own tasks when the app is updated.

For an iPhone home-screen shortcut, host the app on a static website, open it in Safari, and choose Add to Home Screen. The optional home-screen icon loads from the app's repository.

