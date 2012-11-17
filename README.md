Acer Embedded Controler forked to use Sys::PortIO . So it work on any OS that provide this perl module.
Switching off wifi: acer_ec.pl := 0x71 0x00
Manual fan speed setting: acer_ec.pl := 0x93 0x14
 and then set the speed at 0x94 : 0x00 full, 0xff off
acer_ec.pl := 0x94 0xbb <-- very low fan speed
