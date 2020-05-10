# pompom

pompom is a simple command-line pomodoro application for Mac and Linux. It has audio and visual notifications, 25-minute work intervals, and 5 minute breaks, but you can easily tweak these options (see below).

The usage follows the help information from `pompom -h`:

```
pompom is a simple command-line pomodoro utility.

It has the following options:

'start [work|break]' will begin either a work or break, and continue
switching modes thereafter until stopped

'stop' will halt the current pomodoro session

'status' will give the current pomodoro interval status and time

'pause' will pause the current pomodoro at the current time interval
until resumed

'resume' will resume a paused pomodoro interval

'config' will show the current configuration
```

## Install

To install, just download the script and place it in a location that's in your `$PATH`. For example;

```
curl https://raw.githubusercontent.com/benkyriakou/pompom/master/pompom > pompom
chmod 775 pompom
sudo mv ./pompom /usr/bin/pompom
```

## Configuration

The following environment variables can be set to change the behaviour of pompom;

```
POMPOM_WORK_INTERVAL sets the work interval in minutes
POMPOM_BREAK_INTERVAL sets the break interval in minutes
POMPOM_SILENT disables audio notifications when set to 1
POMPOM_INVIS disables visual notifications when set to 1
```
