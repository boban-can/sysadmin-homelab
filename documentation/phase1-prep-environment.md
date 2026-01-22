#Preparing Environment - Windows 11 Laptop
Install Hyper-V - ran into the first issue, can't install Hyper-V.
I went to enable it in the Windows Feature section and checked "Hyper-V Management Tools". However, "Hyper-V platform" is grayed out.
Virtualization isn't enabled in BIOS/UEFI.
Restarted my laptop, entered BIOS/UEFI, found Virtualization, and enabled "Intel Virtualization Technology" and "Intel VT-D Feature".
Navigated to Windows Features again and checked "Hyper-V Management Tools" and "Hyper-V platform" > clicked OK > clicked Restart Now to complete installing the requested changes.
