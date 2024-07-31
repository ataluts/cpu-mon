# cpu-mon

## Description
Simple terminal monitor of CPU temperature, CPU load and RAM usage for DietPi.

## Usage
`cpu-mon [-n] [-l period]`

`-n`  Do not use color grading for values. 

`-l period`    Log period (in seconds) after which to move output to a new line. 0 = disabled (default).

You can also press `Enter` at any time to log a line.

## Dependencies
CPU data is taken from `G_OBTAIN_CPU_TEMP` and `G_OBTAIN_CPU_USAGE` from `DIETPI_GLOBALS`.

Some color grades use 256 color palette so not all terminals will display colors correctly.

## Output example
![Preview](https://raw.githubusercontent.com/ataluts/cpu-mon/master/screenshot.png)
