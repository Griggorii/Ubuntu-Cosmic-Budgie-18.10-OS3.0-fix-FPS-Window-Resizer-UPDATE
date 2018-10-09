# Ubuntu-Cosmic-Budgie-18.10-OS3.0-fix-FPS-Window-Resizer-UPDATE
/etc/X11/xorg.conf.failsafe


Section "Device"
	Identifier	"Configured Video Device"
	Driver		"fbdev"
EndSection

Section "Monitor"
	Identifier	"Configured Monitor"
EndSection

Section "Screen"
	Identifier	"Default Screen"
	Monitor		"Configured Monitor"
	Device		"Configured Video Device"
EndSection
