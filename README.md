# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

A template for building OpenWrt with GitHub Actions

## Usage

- Click the [Use this template](https://github.com/AlexPfaltz/MiR3_custom_firmware/generate) button to create a new repository.
- Generate `.config` files using: 
  [x-wrt](https://github.com/x-wrt/x-wrt) source code. ( You can change it through environment variables in the workflow file. )
  or
  Snapshot [OpenWRT](https://github.com/openwrt/openwrt) with [patch](https://github.com/AlexPfaltz/MiR3_custom_firmware/raw/main/patches/mir3.patch) made from X-WRT
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Tips

- WiFi is turned off by default
- X-Wrt http://192.168.15.1/ admin/admin(login/password)  ssh - root/admin(login/password)
- OpenWrt http://192.168.1.1/
- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.

## Credits

- [OpenWrt](https://github.com/openwrt/openwrt)
- [X-Wrt](https://github.com/x-wrt/x-wrt)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
