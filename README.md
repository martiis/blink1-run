# blink1-run
Shell script runner for [blink1-tool][2]. In order this script to work you must have [command-line][1] tool from blink1. Script provided in this repository can only be run on systems that has bash (Linux, OSX).

## setup
```
# git clone https://github.com/martiis/blink1-run.git
# mv ./blink1-run/bin/blink1-run /usr/local/bin/blink-run
```

## usage
Try out by running a command with blink1-run prefix. f.e. `blink1-run ls`. You should see green light. This runner also checks for exit codes. If exited with code **0 green light**, **else red light**. If a program is running longer it should blink in blue during that period. 

## troubleshoot
 - If you have any problems with permissions try this `chmod u+x /usr/local/bin/blink-run`


[1]: https://blink1.thingm.com/blink1-tool/
[2]: https://blink1.thingm.com
