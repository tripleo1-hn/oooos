---
title: "Why open source things (pt 2)?"
datePublished: Sat Oct 25 2025 03:08:09 GMT+0000 (Coordinated Universal Time)
cuid: cmh5p9tiy000302jp8y2r5pve
slug: why-open-source-things-pt-2
tags: linux, opensource, zfs

---

### Why Linux?

Because it's free. And also because it's better than all the other free stuff. Because hippies like it. Because the other stuff doesn’t work yet.

Definition of hippie: the kind that like tech but are not your bros

Definition of other stuff: I’m not smart enough to write an exokernel

Definition of yet: hardware support (see non-guix for a cheap shot) and testing/optimization

### Why ZFS?

Because, even though in my use case, it can be simulated with btrfs (compression and subvolumes) and some scripts, it can become very useful.

I wanted to hard-reset/cold-turkey into bcachefs for a while, but during my (very limited) testing about 2 years ago, nixos did not allow setting the rootfs to a subvolume.

It should be noted that it does do root (prob at the time too) on gentoo and nixos.

It should also be noted that Debian did a rug pull. (bleh!)