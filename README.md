Last version of OnHub pre-built binaries with NSS support.

This version of the firmware includes MESH and relayd support

Final kernel SNAPSHOT from OpenWrt 23.05.XX firmware iteration.

If you are not using MESH, disable startup of mesh11sd service.

Because of the NSS drivers and patches, you won't be able to update any kmod drivers.

For this reason, I've included a lot in this binary.  I consider it the "last best" version.

It can be configured as a VPN server with DDNS with OpenVPN or WireGuard too if desired.

Use at your own risk.  NSS patches by @KONG, @ACwifidude and @vochong

See the diffconfig if you want to edit it and compile your own version with fewer or more or different packages.

The manifest lists what all is included in this binary.  It's customized for my needs, so your mileage may vary.
