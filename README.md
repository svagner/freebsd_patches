freebsd_patches
===============

Patch collection for FreeBSD (which not added in base)
-- core_only_stack.patch - patch for create mini-coredumps (STACK_ONLY). Added new option for MALLOC_OPTIONS="S". Valid for 901000<(__FreeBSD_version)<=901504 
-- shminf.patch - patch for get data about pids, which attached to shared segments. Added new options for ipcs(1) - "-P". Added struct shminfo in the kernel. Valid for 901000<(__FreeBSD_version)<=901504
-- core_only_stack.patch - patch for create mini-coredumps (STACK_ONLY). Added new option for MALLOC_OPTIONS="S". Valid for __FreeBSD_version==901505
-- shminf.patch - patch for get data about pids, which attached to shared segments. Added new options for ipcs(1) - "-P". Added struct shminfo in the kernel. Valid for __FreeBSD_version==901505

