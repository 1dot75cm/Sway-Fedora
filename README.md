## Sway packages for Fedora

[![Build Status](https://travis-ci.org/nrechn/Sway-Fedora.svg?branch=master)](https://travis-ci.org/nrechn/Sway-Fedora)

<br>
This repo contains sway package spec file and wlc package spec file in order to build related packages for Fedora users.

You can view these packages through Fedora copr: [nrechn/Sway](https://copr.fedorainfracloud.org/coprs/nrechn/Sway/)

<br>
#### What is Sway?
"**S**irCmpwn's **Way**land window manager" is a **work in progress** i3-compatible window manager for [Wayland](http://wayland.freedesktop.org/). Vist [SirCmpwn/sway](https://github.com/SirCmpwn/sway) for more details.

You can also read my blog about the [review of Sway on Wayland](https://gyz.io/2016/05/05/wayland-sway-review/) if you would like to.
> **Note**: The blog is all written in simplified Chinese.

<br>
#### Installation Instructions
The latest stable version is available in Fedora copr.

Enable the repository via `dnf`:

```
dnf copr enable nrechn/Sway
```

Update repository:

```
dnf update
```

Install Sway:

```
dnf install sway
```

