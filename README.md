# Marlin 3D 打印机硬件
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

  * [设置 & 编辑](/Documentation/Compilation.md)
  * 支持
    * [特性](/Documentation/Features.md)
    * [硬件](/Documentation/Hardware.md)
    * [GCodes](/Documentation/GCodes.md)
  * 注意
    * [自动热床高度校正](/Documentation/BedLeveling.md)
    * [Filament Sensor](/Documentation/FilamentSensor.md)
    * [Ramps伺服马达电源](/Documentation/RampsServoPower.md)

##### [RepRap.org Wiki页面](http://reprap.org/wiki/Marlin)

## 快速简介
这是一个适用于reprap单处理器硬件的固件
同样也可以运行在Ultimaker的PCB板上。它支持从文件或是SD打印，and look-ahead trajectory planning.
这个固件从[Sprinter](https://github.com/kliment/Sprinter), [grbl](https://github.com/simen/grbl)与其他固件整合而来

## Current Status: Bug Fixing
## 现在的状态：修复bug

The Marlin development is currently revived. There's a long list of reported issues and pull requests, which we are working on currently.
Marlin development版本重新开始了。
We are actively looking for testers. So please try the current development version and report new issues and feedback.

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

What bugs are we working on: [Bug Fixing Round 2](https://github.com/MarlinFirmware/Marlin/milestones/Bug%20Fixing%20Round%202)

## Contact

__IRC:__ #marlin-firmware @freenode ([WebChat Client](https://webchat.freenode.net/?channels=marlin-firmware), [Archive](http://energymonitor-dk.dns4e.net/marlin-firmware-log/))

__Mailing List:__ marlin@lists.0l.de ([Subscribe](http://lists.0l.de/mailman/listinfo/marlin), [Archive](http://lists.0l.de/pipermail/marlin/))

## Credits

The current Marlin dev team consists of:

 - Erik van der Zalm ([@ErikZalm](https://github.com/ErikZalm))
 - [@daid](https://github.com/daid)
 
Sprinters lead developers are Kliment and caru.
Grbls lead developer is Simen Svale Skogsrud.
Sonney Jeon (Chamnit) improved some parts of grbl
A fork by bkubicek for the Ultimaker was merged.

More features have been added by:
  - Lampmaker,
  - Bradley Feldman,
  - and others...

## Licence

Marlin is published unde the [GPL license](/Documentation/COPYING.md) because I believe in open development.
Please do not use this code in products (3D printers, CNC etc) that are closed source or are crippled by a patent.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
