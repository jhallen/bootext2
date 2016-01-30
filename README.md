## x86 Boot Loaders

Here are boot loaders for Linux on x86, including replacement Master Boot
Record and single block Linux loaders which understand the EXT2 filesystem.

John F. Reiser (who ported UNIX to VAX in 1978!) extended these to use
larger disks.

[mbr - My original MBR in MASM](mbr)

[bootext2 - My original EXT2 loader in MASM](bootext2)

[bootfat - My original FAT loader in MASM](bootfat)

[mbr03 - John Reiser's updated version of MBR in a86](mbr03)

[e2boot4c - John Reiser's updated version of bootext2 in a86](e2boot4c)
