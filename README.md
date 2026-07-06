# README

**Expect disaster, patches may and WILL be randomly added and deleted.**

Patches are separated as follows:
- b4/sm8450-ipa: Patches to get IPA (modem) working
  - v1 sent upstream, v2 pending (1 review pending)
- b4/sm8450-qol: Small patches that fix very specific things
  - v1 sent upstream, v2 pending (2 reviews pending)
- bronco-bup: Bringup for Motorola ThinkPhone by motorola
  - Not sent upstream yet, pending
- sm8475-bup: Device tree and (some) peripherals bringup for SM8475 SoC
  - Not sent upstream yet, pending
- unsorted: Various patches for various things
  - Not sent upstream yet, pending

Patches can be applied at any order, if that doesn't work try alphabetically.
Tested on 7.1.0-rc2 (mainline) and linux-next.

WARNING: As of 2026/06/26 linux-next has broken:
- SM8450/SM8475 PCIe support
- ADC5 thermal support
- DisplayPort link training failure handling **(causes kernel panic)**

Using a mainline version may be preferred instead.
