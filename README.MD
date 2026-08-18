# Armbian MytvNet1 905X3

Custom OPhub Armbian build for MytvNet1 / MyTVnet-4G S905X3 TV box.

## Tested hardware

- Android model: MyTVnet-4G
- Base board: A95X_F3 / A95XF3-Air 100Mb
- SoC: Amlogic S905X3
- DTB: `meson-sm1-a95xf3-air.dtb`
- Ethernet: 100M internal PHY, working
- Wi-Fi/BT: MediaTek MT7668 SDIO
  - Wi-Fi SDIO: `037a:7608`
  - BT SDIO: `037a:7668`
  - Android Wi-Fi driver: `wlan_mt76x8_sdio`

## Build

GitHub Actions -> Build Armbian MytvNet1 S905X3 -> Run workflow.

Default:

- `armbian_board=s905x3-a95xf3`
- `armbian_kernel=6.12.y_6.18.y`
- `auto_kernel=true`

## Notes


