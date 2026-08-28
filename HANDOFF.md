# GrokBot Cash App coach — handoff

Repo: https://github.com/brianreborn/grokbot-cashapp-coach
Project files: `/home/workdir/artifacts`

## What a background agent is allowed to finish
- Keep `interface-schemas.json` and `decent_exit.py` consistent
- Refresh `decent_exit_last.json` with a public BTC print
- Keep TEST.md accurate
- Do not add exchange APIs, custody addresses, or Accessibility against Cash App

## What will never appear while you are away
- An APK installed on your phone
- A process that presses Cash App Confirm
- Auto Invest that spends your existing BTC (it spends USD)

## What you test when you come back
1. Open this project. Read TEST.md.
2. If you have USD in Cash: Cash App → Bitcoin → Buy → Auto Invest → weekly → $1 → you Confirm.
3. If you only have BTC: wait for a decent-exit recommendation, then Sell in Cash App yourself.
4. Leave Auto Invest on until you want out. Cancel → Sell → Cash Out.

Default confirm mode stays **development** until you say Production.
