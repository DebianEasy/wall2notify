# wall2notufy
NODE wall-to-notify-send program
```
Usage: wall2notify [Arguments]
 Need root privilege

Arguments:
 --new-tty              'yes' to use new tty for every logined user, 'no' to use current tty, which may disturb tty users
 --always-check-users   'yes' to check users and send wall messages for them all the time, 'no' to only send messages to users logined at the time wall2notify runs
 --limit-users          'yes' to only allow users in /etc/wall2notify/users to use wall2notify, which can help to reduce disturbance
 --refresh-time          seconds to wait between every time wall2notify check wall messages

Default value of arguments are set in /etc/wall2notify/conf:
 new_tty                default value of --new-tty
 always_check_users     default value of --always-check-users
 limit_users            default value of --limit-users
 refresh_time           default value of --refresh-time

```
