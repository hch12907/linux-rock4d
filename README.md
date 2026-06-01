linux-rock4d (for Arch Linux ARM)
======

This repo contains the PKGBUILD for a customised version of the Linux kernel made for **Radxa
Rock 4D**. The PKGBUILD itself is derived from Arch Linux ARM's official kernel PKGBUILD, with
the following patches added:

1. Ethernet: `net: phy: realtek: Reset after clock enable`
2. Ethernet: `arm64: dts: rockchip: use MAC TX delay for ROCK 4D`
3. Cooling fan: `Add Rockchip RK3576 PWM Support Through MFPWM`

The patches are all from [Collabora's fork](https://gitlab.collabora.com/hardware-enablement/rockchip-3588/linux).
