# auto-commit

🌳 Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

[![Auto commit](https://github.com/fariid37/auto-commit/workflows/Auto%20commit/badge.svg)](https://github.com/fariid37/auto-commit/actions?query=workflow%3A%22Auto+commit%22)

## Make it your own

- Create your own repo with click "**Use this template**" button (forked repo will not work)

Or just do in the manual way:

- Create your own repo
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `email` or create Secret Email and `name` information on file [autocommit.yml, line 29 and 30](https://github.com/fariid37/auto-commit/blob/master/.github/workflows/autocommit.yml#L29)
- Change the scheduling time on file [autocommit.yml, line 10](https://github.com/fariid37/auto-commit/blob/master/.github/workflows/autocommit.yml#L10). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- Consider to support me, at least click the 🌟 button

<div align="center">
    <img src="https://github.com/fariid37/fariid37/raw/main/logo.svg?sanitize=true">
</div>

---

© 2022 Crafted by Farid Syahrudin
