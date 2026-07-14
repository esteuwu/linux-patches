# Linux kernel patches

Targeting SM8450 QoL changes and SM8475 & motorola-bronco bringup. Patches are separated as follows:

## Accepted/Sent
- applied: Patches accepted into the kernel
- b4/q6v5-handover: Patches to stop remoteproc handover spam in dmesg
  - Sent as RFC
- b4/sm8450-ipa: Patches to get IPA (modem) working
  - v1 sent upstream
- b4/sm8450-qol-dispcc: Patches to get a flickerless boot in SM8475
  - v3 sent upstream
- b4/sm8450-qol-dts: Patches modifying the SM8450 devicetree
  - v2 sent upstream
- b4/sm8450-qol-qmp: Patches modifying phy-qcom-qmp-combo source code
  - v2 sent upstream
- b4/sm8450-qol-smmu: Patches to allow mdss driver to work properly
  - v2 sent upstream

## Work area
- bronco-bup: Bringup for Motorola ThinkPhone by motorola
  - Not sent upstream yet, pending
- sm8475-bup: Device tree and (some) peripherals bringup for SM8475 SoC
  - Not sent upstream yet, pending
- unsorted: Various patches for various things
  - Not sent upstream yet, pending

Tested on 7.1.0-rc2 (mainline) and linux-next.

Next may occasionally break; use mainline or stable instead.
