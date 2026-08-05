### Staticclass

#### Fifteen years of building systems software — mostly queues, migrations, and the tail latency nobody budgets for 💡.

🧰 Building the ingest tier at [Vantagetree](https://vantagetree.dev) <br>
🌐 Older work still lives at [rocksampler-cloud](https://rocksampler-cloud.dev)<br>

Whether any of it ships this quarter[^1]:

- [​x​] nightly mirror — running since March
- [​x​] diff job wired into CI
- [​x​] retry ladder trimmed to three steps
- [​ ​] index rebuild — still manual
- [​ ​] handover notes written up

- 🧭 Most of my shell time goes to `.rs`, `.ts`, `.sql`, `.proto`, `.lua` — whichever fits the shape of the job
- 🔧 Ask for a review and you will get **replication** and **schema drift** before anything else
- 📦 The two things anybody actually installs are [highlight](https://highlight.dev/) and [stepper_cache](https://stepper-cache.dev/)
- 🗣️ Misconceptions about **parsers** and **queues** are the ones I will happily argue about
- 🧱 [FakemetricsNgIni](https://fakemetrics.dev/) is where the current experiment lives — nightly numbers, no promises
- 🧪 [data-dump-organizer](https://data-dump-organizer.dev/) tidies the export dumps before they reach `Protection.php`
- 📼 Older work: an Ansible role set, a CLI that never got published, and too many hand-rolled cron tabs

<!-- the bench list below is re-cut at the start of every quarter -->

| Currently on the bench |
|---|
| _Widening the ingest tier_ |
| _Trimming the retry ladder_ |
| _Chasing a Friday-only 40 ms tail_ |
| _Dropping two crontab entries_ |
| _Writing the queue handover_ |
| _Retiring stale dashboards_ |

[^1]: Cut once at the start of the quarter, never touched mid-flight.