# Applika updates

`latest.json` tells [Applika](https://inferam.eu) (Infera M) which version is the newest. Applika reads it at
startup (at most once a day, can be turned off in Settings) and from **Help → Check for Updates…**. Only this file
is fetched; nothing about the user, the computer or their images is sent.

The file is written automatically by the Applika release workflow. Please do not edit it by hand.

```json
{ "version": "0.5.0", "date": "2026-11-20", "url": "<download page>", "notes": "<release notes, markdown>" }
```
