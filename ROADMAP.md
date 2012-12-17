v8
- feature: [better height preference UI (github #5)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/5)
- feature: detect active pid and ask before exiting the shell? (or detach it?)
- feature: use settings from gnome-terminal
- code: investigate argb colors not working

v9
- feature: prompt to kill the possible active pid on logout to avoid loosing something
- bugfix: [when switching Workspaces DD Terminal flashes in and out (github #4)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/4)
- code: investigate how to have proper theming of the border (using the generic popup border or at least make it customisable through CSS)

v10
- feature (maybe): autohide (asked by step-2)
- feature (maybe): multi tabs (5 votes for, 6 votes against)
- feature (maybe): allow custom width (suggested by Dreamsorcerer)
- feature (maybe): dnd (already tried, not that simple)
- bugfix: investigate the focus issue preventing using the BLOCK cursor
- bugfix (maybe): [add icon/name to panel (github #7)](https://github.com/zzrough/gs-extensions-drop-down-terminal/issues/7)

future:
- feature: pause the child process if term closed and no active pid (for powersaving, maybe an additional pref?)
