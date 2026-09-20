# LifeAdmin background reminders

Private scheduling companion for [LifeAdmin](https://lifeadmin-orbit.anishnudurupati.chatgpt.site/).

The workflow evaluates reminders at minutes 17 and 47 each hour. Quiet hours and delivery preferences are enforced by LifeAdmin. GitHub may delay scheduled runs; see LifeAdmin Settings for the last actual background check.

Credentials are stored only in repository Actions secrets: `LIFE_ENGINE_JOB_TOKEN` and `SITES_ACCESS_TOKEN`. Never commit them. No app documents or personal records are stored in this repository.
