linux-lts-ck-archlinux
======================

ArchLinux LTS kernel, patched with the CK patchset

CHANGELOG:

3.10.35-1
  * UPPKG: https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.35

3.10.34-1
  * UPPKG: https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.34
  * New GCC Optimisations: http://repo-ck.com/source/gcc_patch/enable_additional_cpu_optimizations_for_gcc.patch.gz

3.10.33-1
  * UPPKG: https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.33

3.10.32-1
  * UPPKG: 3.10.32-1 https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.32

3.10.31-1
  * UPPKG: 3.10.31-1 https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.31

3.10.30-2
  * UPBFQ: v7r2 for 3.10.8+

3.10.30-1
  * UPPKG: 3.10.30-1 https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.30
  * UPBFQ: v7r1 for 3.10.8+

3.10.29-2
  * UPBFQ: BFQ v7r1 for 3.10

3.10.29-1
  * https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.29
  
3.10.82-3
  * Include timespec patch. https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=8f5829c435869a9384d6c1a4dd85636dda3e7c4b
  * remove CONFIG_FIRMWARE_IN_KERNL https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=50bf97fa699d2b353034887dc43737173a18c9a3
  * set SCSI_SCAN_ASYNC=y https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=325cba71f0fad2c507441aac5f0bf190b2db6bf5
  * remove EFI_VAR, add YAMA https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=aa78faa55d546541319cf3e778756f32dfd675ed
  * increase NR_CPU to 128 for x86_64 https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=ecd7251da3d0490004da3d2c0e12088551827ce5
  * disable MTD_NAND and CHIPIDEA https://projects.archlinux.org/svntogit/packages.git/commit/trunk?h=packages/linux-lts&id=7ae7ac8c2038826e355b97d3e91961ffc5e67509
  
3.10.28-2
  
  * Adjusted 0004*.patch and edited PKGBUILD to make it an opt-out option
  * BFQ v7 backported for 3.10: http://algo.ing.unimo.it/people/paolo/disk_sched/patches/3.10.0-v7/

3.10.28-1
  
  * https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.28

3.10.27-2

  * Removed logitech-dj.patch. See https://www.kernel.org/pub/linux/kernel/v3.x/ChangeLog-3.10.27
  
3.10-27-1

  * New package ownership.
