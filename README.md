# ThinkPad-t440-oc0.6.6-Mod-hachintosh
ThinkPad T440 OpenCore 0.6.6MOD EFI for BigSur 11.2 and Catalina 10.15.7 
Bios Settings

The bios must be properly configured prior to installing MacOS.

In Security menu, set the following settings:

Security > Security Chip: must be Disabled,
Memory Protection > Execution Prevention: must be Enabled,
Internal Device Access > Bottom Cover Tamper Detection: must be Disabled,
Anti-Theft > Current Setting: must be Disabled,
Anti-Theft > Computrace > Current Setting: must be Disabled,
Secure Boot > Secure Boot: must be Disabled.
In Startup menu, set the following options:

UEFI/Legacy Boot: Both,
UEFI/Legacy Priority: UEFI First,
CSM Support: Yes.
Now you can go through the install.

OC's config.plist Instead of editing with OpenCORE configurator, open it with propertree, generate it with "serial number generator" of hackintol, copy the value to "MLB", "systemserialnumber" and "systemuuid", corresponding to "mainboard serial number", "serial number" and "system ID" in hackintol.
When editing with configurator, some default values may be changed, resulting in code before boot into the boot interface.
I put it in the EFI bag on the net disk config.plist The 3-yard position is empty, just generate and fill it directly.

