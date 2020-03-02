# Chroot Setup

This is a quick & dirty script used to create a minimal chroot environment for experimentation.

Run 

```
chmod +x env_setup
```

to make it executable, and 

```
./env_setup $CHROOT_DIR [chroot]
```
to run the script, where $CHROOT_DIR is the absolute path to your environment root, and `chroot` is the string "chroot". 

If "chroot" is passed, the script will invoke `sudo chroot $CHROOT_DIR`. 

# Why not use debootstrap?

I do. I made this mostly for finer grained control. 

# TODO

- [ ] Teardown script 
- [ ] Code cleanup
