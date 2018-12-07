# Week 1

## Unit 1

### chroot (file system isolation)

### SELinux (security/access control)

## Unit 2

### namespaces (mnt, pid, net, ipc, hostname, user ids)

Namespaces are a feature of the Linux kernel that isolates and virtualizes system resources of a collection of processes. Examples of resources that can be virtualized include process IDs, hostnames, user IDs, network access, interprocess communication, and filesystems.

As of kernel version 3.8, there are 6 kinds of namespaces. Namespace functionality is the same across all kinds: each process is associated with a namespace and can only see or use the resources associated with that namespace, and descendant namespaces where applicable. This way each process (or group thereof) can have a unique view on the resource.

The kernel assigns each process a symbolic link per namespace kind in `/proc/<pid>/ns/`

### cgroups (cpu, memory, disk, i/o)

### seccomp (computation isolation)

## Unit 3

### Linux containers

### Docker containers vs VM
