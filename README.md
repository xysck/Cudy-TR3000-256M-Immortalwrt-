# 项目说明
- 设备型号：Cudy TR3000
- 固件默认管理地址：`192.168.1.1` 默认用户：`root` 默认密码：`password`
- 源码：https://github.com/padavanonly/immortalwrt-mt798x-6.6
- 云编译来源：https://github.com/haiibo/OpenWrt
# USB供电开关方法
If you want to turn off USB Power, run

```bash
echo 0 > /sys/class/gpio/modem_power/value
```

and get the power back by

```bash
echo 1 > /sys/class/gpio/modem_power/value
```

third-party packages:
- [OpenClash](https://github.com/vernesong/OpenClash)
- [Bandix](https://github.com/timsaya/luci-app-bandix)
- [luci-theme-aurora](https://github.com/eamonxg/luci-theme-aurora)
- luci-app-upnp
- kmod-usb-net-cdc-ether
- kmod-usb-net-rndis

## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
