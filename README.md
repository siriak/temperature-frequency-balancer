# Temperature-Frequency Balancer

This script aims to maintain a stable CPU temperature by increasing and decreasing the clock multiplier as temperature changes. Modern CPUs have similar features built into them, but they don't allow setting target temperature as this script does.

On i7-7820X with the target temperature of 58 centigrade, it manages to maintain 58+-2 degrees under room temperatures ranging from 10 to about 40 degrees and load changing from no to full.
