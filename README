# HoloISO build toolchain
This is the toolchain used to build HoloISO.

**Why?**
- Because we like to set our version from CI?
- Because i can designate buildname as much as i want just using command line options.
- Much more versatile and customizable than adding thousand && in one command. I mean, isn't it?

**Example usage:**

`startbuild-holo --branch vd_release --version 5.0 --isodir /home/ci/holoiso --rclone drive2:/output/iso --debug print`

***Options:***

**Required:**
- --branch: Self-explainatory, adds branch name to ISO file
- --version: Adds version in filename
- --isodir: ArchISO/HoloISO profile directory

**Optional:**
- --rclone: Copy image to rclone remote drive (Only works on our CI as of now, because telemsg is closed source for obvious reasons)

**Optional (HoloISO maintainer pipeline only):**
- --debug [print]: Debug options, [print - Prints more detailed information about build to CI channel: https://t.me/HoloISO_CI/122]