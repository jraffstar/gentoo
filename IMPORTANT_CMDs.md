# Kernel install will fail without this
```bash
touch /etc/kernel/preinst.d/05-check-chroot.install
```
# startx and launching firefox will be slow unless you add an alias in /etc/hosts
