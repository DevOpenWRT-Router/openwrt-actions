# OpenWrt-Actions

Build OpenWrt using GitHub Actions

Thank P3TERX for [his template](https://github.com/P3TERX/Actions-OpenWrt)

[Read the details in p3terx blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- Use Github SSH to customize the `.config` file and it will be uploaded in [release page](https://github.com/Suwmlee/openwrt-actions/releases)
- All packages will be uploaded in [`Artifacts`](https://github.com/Suwmlee/openwrt-actions/actions), you can find all compiled `ipk` files

#### Config Setting

__built-in__:
- luci-compat
- luci-mod-admin-full
- luci-app-sqm
- dnsmasq-full
- block-mount

[Find more packages](https://github.com/Suwmlee/openwrt-packages)

### Tips

It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).

Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.

## Acknowledgments

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © P3TERX
