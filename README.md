# notif

**2017/06/09**

Actualmente utiliza notify-send para trabajar en conjunto con dunst.
It uses notify-send to work with dunst.

*Requires notify-send, amixer and playerctl*

## Notifications `notif [notification]`
- irc: new IRC (weechat) messages. Logs highlights to specified file.
- clear: to clear messages log.
- count: counts log file lines (messages).
- view: reads log using `less`.
- playing: currently playing song. Uses `playerctl`.
- info: status bar. It displays date, volume, battery and playing song.
