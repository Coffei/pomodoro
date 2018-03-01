Pomodoro timer
==============

Very simple pomodoro timer in bash I wrote when I wanted something really
simple, and installing stuff from `npm` or any other repo seemed like an
overkill.

It counts down a specified timer and displayes a notification when it ends,
that's all. It uses `notify-send` to display the notification. You can customize
the time interval and the notification message.

## Usage
Run `pomodoro X` to run a pomodoro session which takes `X` minutes, e.g. `pomodoro 10`.

Run without any argument for the default 25-minute session.

To customize the notification, you can add the summary and body as additional
arguments, e.g. `pomodoro 5 "Break ended!" "Get back to work."`.
