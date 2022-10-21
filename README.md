# lerna/repro

Run `npx lerna bootstrap` --> will work, `npmClientArgs` is applied

Run `npm run set-version 0.0.2` --> will crash, `npmClientArgs` is _not_ applied
