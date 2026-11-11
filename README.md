# CI detection fixture

Npm@1 task form with `command: custom` + `customCommand: run test`. The command is in an input, not in a script line. Regression for 23e37f2.

Expected verdict line in the Octiq chat:

    Tests required - CI runs `npm run test`
