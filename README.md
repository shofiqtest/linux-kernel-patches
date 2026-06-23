# Linux Kernel Patches

Patches submitted to the mainline Linux kernel by **Md Shofiqul Islam**.

Patch archive: https://lore.kernel.org (search: shofiqtest@gmail.com)

---

## Submitted Patches

| # | Patch | Subsystem | Type | Company |
|---|-------|-----------|------|---------|
| 1 | [ASoC: nau8825: Fix typos in comments](0001-ASoC-nau8825-Fix-typos-in-comments.patch) | Sound/ASoC | Comment fix | — |
| 2 | [power: supply: Fix typos in comments](0001-power-supply-Fix-typos-in-comments.patch) | Power Supply | Comment fix | — |
| 3 | [mfd: si476x: Fix typos in comments](0001-mfd-si476x-Fix-typos-in-comments.patch) | MFD | Comment fix | — |
| 4 | [fs: gfs2: Fix typos in comments](0001-fs-gfs2-Fix-typos-in-comments.patch) | GFS2 Filesystem | Comment fix | Red Hat |
| 5 | [ASoC: atmel: Fix typo in comment](0001-ASoC-atmel-Fix-typo-in-comment.patch) | Sound/ASoC | Comment fix | — |
| 6 | [scsi: scsi_scan: Fix typo in comment](0001-scsi-scsi_scan-Fix-typo-in-comment.patch) | SCSI | Comment fix | — |
| 7 | [xfs: Fix typo in comment](0001-xfs-Fix-typo-in-comment.patch) | XFS Filesystem | Comment fix | Red Hat |
| 8 | [scsi: storvsc: Replace symbolic permissions with octal](0001-scsi-storvsc-Replace-symbolic-permissions-with-octal.patch) | Hyper-V Storage | Code fix | Microsoft |
| 9 | [wifi: iwlwifi: Fix typo in comment](0001-wifi-iwlwifi-Fix-typo-in-comment.patch) | Intel WiFi | Comment fix | Intel |
| 10 | [igb: Remove redundant extern declarations](0001-igb-Remove-redundant-extern-declarations.patch) | Intel Ethernet | Code fix | Intel |
| 11 | [soc: ti: knav_qmss_queue: free resources in remove callback](0001-soc-ti-knav_qmss_queue-free-resources-in-remove-call.patch) | TI Keystone SOC | Bug fix (v3) | Texas Instruments |
| 12 | [iio: health: add MAX86150 ECG and PPG biosensor driver](0001-iio-health-add-MAX86150-ECG-and-PPG-biosensor-driver.patch) | IIO / Health | **New driver** | Analog Devices |

---

## Skills Demonstrated

- Linux kernel patch workflow (git format-patch, git send-email)
- Kernel coding style (checkpatch.pl, 0 errors / 0 warnings)
- Full IIO driver authorship: triggered buffer, regmap_noinc_read(), hardware FIFO, DT binding YAML
- Working with upstream maintainers at Intel, Microsoft, Red Hat, TI, Analog Devices
- Responding to reviewer feedback and submitting revised patches (v2, v3)
- Subsystems: IIO/Health, XFS, GFS2, Hyper-V, iwlwifi, igb, ASoC, SCSI, MFD, Power Supply, TI Keystone

---

## About

These patches were submitted directly to kernel mailing lists following the
official Linux kernel contribution process. Each patch was reviewed by
checkpatch.pl before submission and sent to the correct maintainers.

The knav_qmss_queue patch went through 3 rounds of review with
Nishanth Menon (Texas Instruments maintainer), demonstrating real
upstream collaboration.

The MAX86150 driver (patch #12) is the first complete new driver submission:
512 lines of IIO driver code for a combined ECG + PPG biosensor, including
DT binding YAML schema, Kconfig entry, and MAINTAINERS record. Submitted
to Jonathan Cameron (IIO maintainer) on 2026-06-23.
