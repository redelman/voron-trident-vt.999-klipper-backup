# voron-trident-vt.xxx-klipper-backup
Automated backup of klipper config

Voron Trident 300mm (unserialed)
- Mainly using fluidd

discord: quok#1849

# About This Printer
[Voron Trident](https://vorondesign.com/voron_trident) built February 2022 from a [Fabreeko](https://fabreeko.com) kit, with some changes and extra mods.

The printer is using a Fysetc Spider 2.2 MCU and TMC 2209 stepper drivers. I have 5160HVs on the way for the A/B (X/Y) steppers and will go 48V at that time. I'm not using the LDO V1/V2 motor kit that was included; instead I am using LDO 42STH48-2504AH steppers. These are the same steppers used in the RatRig vCore 3 I believe. They are 2.5A high temp steppers that should work great with the 5160HVs I have on the way.

This printer makes use of a number of mods, as listed below.

# Mods
- Stealthburner
- Titanium Extrusion Backers
- [Klicky Probe](https://github.com/jlas1/Klicky-Probe)
- [Nozzle Scrubber](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_&_Nozzle_Scrubber)
- Polysulfone Bed Standoffs
- XY Endstop PCB
- Sexbolt Z Endstop
- Pins Mod
- [Rama's Voron Mods inc the new idlers](https://github.com/Ramalama2/Voron-2-Mods)
- [WLED](https://kno.wled.ge/) controlled RGB case lighting using [new moonraker wled component](https://moonraker.readthedocs.io/en/latest/configuration/#wled) running on a separate ESP32

# Other Misc Features
- [Git backup](https://github.com/th33xitus/kiauh/wiki/How-to-autocommit-config-changes-to-github%3F) - using [SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) authentication
- [lcd_tweaks.cfg](https://github.com/VoronDesign/Voron-Documentation/blob/4a825a8704a3c8467606f58fb45ac4c377779842/community/howto/alchemyEngine/lcd_tweaks.cfg)  

# Links
[Voron User Mods](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods)  
[https://vorondesign.com/](https://vorondesign.com/)  

[Klipper](https://www.klipper3d.org/)  

[Ellis' PIF Profile](https://github.com/AndrewEllis93/Ellis-PIF-Profile)  
[Ellis' Print Tuning Guide](https://github.com/AndrewEllis93/Print-Tuning-Guide)  

# Other klipper backups I've found useful
[https://github.com/richardjm/voronpi-klipper-backup](https://github.com/richardjm/voronpi-klipper-backup)
[https://github.com/AndrewEllis93/v2.247_backup_klipper_config](https://github.com/AndrewEllis93/v2.247_backup_klipper_config)  
[https://github.com/pushc6/VoronConfig](https://github.com/pushc6/VoronConfig)  
[https://github.com/kageurufu/3dp-voron2/tree/master/printer](https://github.com/kageurufu/3dp-voron2/tree/master/printer)  
[https://github.com/wile-e1/klipper_config](https://github.com/wile-e1/klipper_config)  
[https://github.com/th33xitus/klipper_config](https://github.com/th33xitus/klipper_config)
