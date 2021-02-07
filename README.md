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
