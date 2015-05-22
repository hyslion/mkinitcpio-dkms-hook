# mkinitcpio-dkms-hook
A simple hook to build dkms modules before mkinitcpio.

## Installation
1. Copy `dkms` to `/etc/initcpio/install/`
2. Add `dkms` to `HOOKS` array in `/etc/mkinitcpio.conf`
3. It should work everytime during mkinitcpio
