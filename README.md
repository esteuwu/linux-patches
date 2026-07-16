# Linux kernel patches

Targeting SM8450 QoL changes and SM8475 & motorola-bronco bringup. Patches are separated as follows:

## Accepted/Sent
- accepted: Patches in [next](https://git.kernel.org/pub/scm/linux/kernel/git/next/linux-next.git/tree/), will be checked when they arrive in [mainline](https://github.com/torvalds/linux)
- b4/sm8450-ipa: Patches to get IPA (modem) working
  - v1 sent upstream, 0/3 reviewed
- b4/sm8450-qol-dispcc: Patches to get a flickerless boot in SM8475
  - v3 sent upstream, 3/3 reviewed
- b4/sm8450-qol-qmp: Patches modifying phy-qcom-qmp-combo source code
  - v2 sent upstream, 1/2 reviewed
- b4/sm8450-qol-smmu: Patches to allow mdss driver to work properly
  - v2 sent upstream, 1/1 reviewed
- b4/sm8475-bup-pcie: Patches to bringup SM8475 PCIe0 PHY
  - v2 sent upstream, 0/3 reviewed
- b4/sm8475-bup-usbss: Patches to bringup SM8475 QMP USB PHY
  - v2 sent upstream, 0/3 reviewed

## Work area

<!--
I do NOT authorize the upstreaming of patches that fall into this category.
They aren't signed off for a reason.
If I find traces of my patches in LKML YOU WILL NEVER HEAR THE END OF IT.
-->

- bronco-bup: Bringup for Motorola ThinkPhone by motorola
  - Not sent upstream yet, pending
- sm8475-bup: Device tree and (some) peripherals bringup for SM8475 SoC
  - Not sent upstream yet, pending
- unsorted: Various patches for various things
  - Not sent upstream yet, pending

Tested on 7.1.0-rc2 (mainline) and linux-next.

Next may occasionally break; use mainline or stable instead.
