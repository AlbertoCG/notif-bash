# notif

**2017/06/09**

It uses notify-send to work with dunst.

*Requires notify-send, amixer and playerctl*

## Notifications `notif [notification]`
- irc: new IRC (weechat) messages. Logs highlights to specified file.
- clear: to clear messages log.
- count: counts log file lines (messages).
- view: reads log using `less`.
- playing: currently playing song. Uses `playerctl`.
- info: status bar. It displays emails count, date, volume, battery and playing song.
