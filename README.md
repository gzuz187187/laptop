# laptop

## HP EliteBook 820 G2
* Wenn Laptop beim Boot stuck ist in Boot Loop mit "Reset System": https://askubuntu.com/questions/244261/how-do-i-get-my-hp-laptop-to-boot-into-grub-from-my-new-efi-file
  * bootloader "BOOTX64.EFI" und "fbx64.efi" im folder /boot/efi/EFI/BOOT mit "grubx64.efi" aus dem folder /boot/efi/EFI/ubuntu ersetzen (die kopierten Dateien auf den jeweiligen Namen replacen, also z.B. grubx64.efi auf BOOTX64.EFI umbenennen)
