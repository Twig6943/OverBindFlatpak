Attempt to package the app as a flatpak

as of right now when executed it gives this crash

```
flatpak --user run io.github.cjonas1999.overbind 
Reading settings from /home/twig/.var/app/io.github.cjonas1999.overbind/data/OverBind/OverBind_app_settings.json
[2025-12-24][11:43:15][ERROR][overbind] PanicHookInfo { payload: Any { .. }, location: Location { file: "src/main.rs", line: 357, col: 14 }, can_unwind: true, force_no_backtrace: false }
PanicHookInfo { payload: Any { .. }, location: Location { file: "src/main.rs", line: 357, col: 14 }, can_unwind: true, force_no_backtrace: false }
```
