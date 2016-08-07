# linux-netbook package for Arch & Manjaro Linux
The Linux kernel and modules with BFQ and tweaked config, for Intel Atom CPU only.

This kernel is targeted at users on real Intel Atom-based netbook hardware.

Config tweaks so far:
- Set target CPU family to Atom
- Set default CPUFreq governor to Conservative
- Enable BFQ and set as default
- Enable audio (AC97 & HDA) power-save modes
- Set PCI-E ASPM to powersave by default
- Remove all virtualization guest support
- Remove a couple of AMD-specific CPU features
- Remove KSM
- Remove KEXEC


Suggestions welcome, please make GitHub issues.
