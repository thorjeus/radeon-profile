Simple application to read current clocks of ATi Radeon cards (xf86-video-ati)


# Troubleshooting


* __"Err" instead of values:__ Try start app as root. Need to read system files.
	
* __"no values":__ Check `/sys/kernel/debug`. If it's empty, try `# mount -t debugfs none /sys/kernel/debug`