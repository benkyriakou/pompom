# pompom

pompom is a simple command-line pomodoro application for Mac and Linux. Currently it is audio-only, with fixed 25-minute work intervals and 5 minute breaks, but you can easily tweak these values in the script should you wish.

The usage follows the help information from `pompom -h`:

```
pompom is a simple audio-based command-line pomodoro utility.

It has the following options:

'start [work|break]' will begin either a work or break, and continue
switching modes thereafter until stopped

'stop' will halt the current pomodoro session

'status' will give the current pomodoro interval status and time

'pause' will pause the current pomodoro at the current time interval
until resumed

'resume' will resume a paused pomodoro interval
```

# Install

To install, just download the script and place it in a location that's in your `$PATH`. For example;

```
curl https://github.com/benkyriakou/pompom/blob/master/pompom > pompom
chmod 775 pompom
sudo mv ./pompom /usr/bin/pompom
```
