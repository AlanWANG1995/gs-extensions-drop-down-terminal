v5
- bugfix: [terminal lost after screen is locked (github #6)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/6)

v6
- feature: [better height preference UI (github #5)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/5)
- feature: detect active pid and ask before exiting the shell? (or detach it?)
- code: investigate argb colors not working

v7
- feature: prompt to kill the possible active pid on logout to avoid loosing something
- bugfix: [when switching Workspaces DD Terminal flashes in and out (github #4)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/4)
- bugfix: [no focus given on ctrl-alt-tab (github #8)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/8)
- code: investigate how to have proper theming of the border (using the generic popup border or at least make it customisable through CSS)

v8
- feature (maybe): autohide (asked by step-2)
- feature (maybe): multi tabs (2 votes for, 2 votes against, andyfitz: tabs would just clutter it up)
- bugfix: investigate the focus issue preventing using the BLOCK cursor
- bugfix (maybe): [add icon/name to panel (github #7)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/7)

v9
- feature: pause the child process if term closed and no active pid (for powersaving, maybe an additional pref?)
- code: global review
