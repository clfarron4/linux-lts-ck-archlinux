linux-lts-ck-archlinux
======================

ArchLinux LTS kernel, patched with the CK patchset

CHANGELOG:
  
3.10.82-3
  * Include timespec patch. https://github.com/clfarron4/linux-lts-ck-archlinux/commit/47420b0af7dd690cb5f19ad3d5fc8a095d6e6c30
  * remove CONFIG_FIRMWARE_IN_KERNL https://github.com/clfarron4/linux-lts-ck-archlinux/commit/12aabea5972ffa4d93a5441fa53d9f7e60178fdf
  * set SCSI_SCAN_ASYNC=y https://github.com/clfarron4/linux-lts-ck-archlinux/commit/86ec20a96e4aa3a04ad606486a5d861d2195e2ab
  * remove EFI_VAR, add YAMA https://github.com/clfarron4/linux-lts-ck-archlinux/commit/d86c41fd0a5377aa2eac57779035dc68f39f2475
  * increase NR_CPU to 128 for x86_64 https://github.com/clfarron4/linux-lts-ck-archlinux/commit/01ec93cd9bcf533e116fb10dea3d0dd1b88cffcc
  * disable MTD_NAND and CHIPIDEA https://github.com/clfarron4/linux-lts-ck-archlinux/commit/d4ed322a9e7424da57d5043a1af7dc48c7ba6976
  
3.10.28-2
  
  * Adjusted 0004*.patch and edited PKGBUILD to make it an opt-out option
  * BFQ v7 backported for 3.10: http://algo.ing.unimo.it/people/paolo/disk_sched/patches/3.10.0-v7/

3.10.28-1
  
  * https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.28

3.10.27-2

  * Removed logitech-dj.patch. See https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.27
  
3.10-27-1

  * New package ownership.
