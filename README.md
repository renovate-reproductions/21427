# Minimal Reproduction for Renovate Bot Discussion https://github.com/renovatebot/renovate/discussions/21427

## Expected

The used schedule in this `renovate.json`:
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "config:base"
  ],
   "schedule": ["every 2 months on the first saturday of the month"]
}
```

should work.

According the _Codepen_ mentioned here: https://docs.renovatebot.com/configuration-options/#schedule it is valid:

> ![image](https://user-images.githubusercontent.com/5927148/231407689-f4d8a261-a82a-4ad9-ad03-e2e939de279f.png)



## Outcome

Renovate creates an issue https://github.com/renovate-reproductions/21427/issues/1 and complains about invalid schedule.
