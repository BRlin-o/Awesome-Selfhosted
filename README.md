# Awesome-Selfhosted

[![GitHub stars](https://img.shields.io/github/stars/your_username/Awesome-Selfhosted.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/BRlin-o/Awesome-Selfhosted/stargazers/)
[![GitHub forks](https://img.shields.io/github/forks/your_username/Awesome-Selfhosted.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/BRlin-o/Awesome-Selfhosted/network/)
[![GitHub issues](https://img.shields.io/github/issues/your_username/Awesome-Selfhosted.svg)](https://GitHub.com/BRlin-o/Awesome-Selfhosted/issues/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)

Awesome-Selfhosted is a collection of awesome projects that can be hosted on your own servers. These projects cover a wide range of domains, such as cloud storage, streaming, network tools, and more. Most of them support docker deployment, which makes it easy to set up and run.

The goal of this project is to provide a curated list of self-hosted alternatives to popular online services and applications. Whether you want to protect your privacy, save some money, or just have fun, you can find something interesting and useful here.

## Table of Contents

- [Awesome-Selfhosted](#awesome-selfhosted)
  - [Table of Contents](#table-of-contents)
  - [Cloud Storage](#cloud-storage)
  - [Streaming](#streaming)
  - [File Transfer \& Synchronization](#file-transfer--synchronization)
  - [Reader](#reader)
  - [Home Automation](#home-automation)
  - [Data Visualization](#data-visualization)
  - [Downloader](#downloader)
  - [Online Editor](#online-editor)
  - [Reverse Proxy](#reverse-proxy)
  - [Dynamic DNS](#dynamic-dns)
  - [VPN Server](#vpn-server)
  - [AirPlay Server](#airplay-server)
  - [Network Tools](#network-tools)
  - [Others...](#others)
  - [Speed Test](#speed-test)
  - [Bookmark Manager](#bookmark-manager)
  - [Password Manager](#password-manager)
  - [AI Drawing](#ai-drawing)
  - [And more...](#and-more)


## Cloud Storage
- [Alist](https://github.com/Xhofe/alist) - A simple and elegant file list server that supports multiple cloud drives. ([Source Code](https://github.com/Xhofe/alist)) `MIT` `Go`
  - 部屬方式：支援 Docker、Heroku、OpenWrt 等
  - 客戶端支援：支援 Web 瀏覽器、WebDAV 協議
- [Zfile](https://github.com/zhaojun1998/zfile) - A powerful online disk system that supports multiple storage types and protocols. ([Source Code](https://github.com/zhaojun1998/zfile)) `GPL-3.0` `Java`
  - 部屬方式：支援 Docker、Tomcat、JAR 包等
  - 客戶端支援：支援 Web 瀏覽器、WebDAV 協議
- [ownCloud](https://owncloud.org/) - A self-hosted file sync and share server. ([Source Code](https://github.com/owncloud/core)) `AGPL-3.0` `PHP`
  - 部屬方式：支援 Docker、Snap、Linux 套件等
  - 客戶端支援：支援 Web 瀏覽器、WebDAV 協議、Windows、MacOS、Linux、Android、iOS 等
- [Nextcloud](https://nextcloud.com/) - A safe home for all your data. Access & share your files, calendars, contacts, mail & more from any device, on your terms. ([Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Source Code](https://github.com/haiwen/seafile)) `GPL-2.0` `Python`
- [And more...](#and-more)

## Streaming

- [Jellyfin](https://jellyfin.org/) - The Free Software Media System. It is an alternative to the proprietary Emby and Plex, to provide media from a dedicated server to end-user devices via multiple apps. ([Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- [Streama](https://streamaserver.org/) - Self hosted streaming media server. ([Source Code](https://github.com/streamaserver/streama)) `MIT` `Java`
- [And more...](#and-more)

## File Transfer & Synchronization

- [Resilio-sync](https://www.resilio.com/individuals/) - A fast, reliable, and simple file sync and share solution, powered by P2P technology. ([Source Code](https://github.com/bt-sync/sync-docker)) `Proprietary` `C++`
  - 部屬方式：支援 Docker、Windows、MacOS、Linux 等
  - 客戶端支援：支援 Windows、MacOS、Linux、Android、iOS 等
- [Aliyundrive Webdav](https://github.com/messense/aliyundrive-webdav) - A WebDAV server for AliyunDrive, mainly for streaming media content to TV via client apps like Infuse and nPlayer. ([Source Code](https://github.com/messense/aliyundrive-webdav)) `MIT` `Rust`
  - 部屬方式：支援 Docker、Snapcraft、OpenWrt 等
  - 客戶端支援：支援任何符合 WebDAV 協議的客戶端
- [BaiduNetDisk](https://github.com/gshang2017/docker/tree/master/baidunetdisk) - A dockerized Baidu Netdisk client that can be accessed via browser or VNC remote desktop. (Source Code) GPL-3.0 Java
  - 部屬方式：支援 Docker
  - 客戶端支援：支援 Web 瀏覽器、VNC 遠程桌面

## Reader
- [Kavita](https://github.com/Kareadita/Kavita) - A fast, feature rich, cross platform manga and comic server. ([Source Code](https://github.com/Kareadita/Kavita)) `GPL-3.0` `C#`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器、Android、iOS 等
- [Mango](https://github.com/hkalexling/Mango) - A self-hosted manga server and reader. ([Source Code](https://github.com/hkalexling/Mango)) `GPL-3.0` `Crystal`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器、OPDS 協議

## Home Automation

- [Home Assistant](https://www.home-assistant.io/) - An open source home automation platform that puts local control and privacy first. ([Source Code](https://github.com/home-assistant/core)) `Apache-2.0` `Python`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器、Android、iOS 等
- [HomeBridge](https://homebridge.io/) - A lightweight Node.js server you can run on your home network that emulates the iOS HomeKit API. ([Source Code](https://github.com/homebridge/homebridge)) `Apache-2.0` `JavaScript`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援任何符合 HomeKit 協議的客戶端

## Data Visualization

- [Grafana](https://grafana.com/) - An open source platform for monitoring and observability. ([Source Code](https://github.com/grafana/grafana)) `AGPL-3.0` `Go`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## Downloader

- [Cloud Torrent](https://github.com/jpillora/cloud-torrent) - A self-hosted remote torrent client. ([Source Code](https://github.com/jpillora/cloud-torrent)) `MIT` `Go`
  - 部屬方式：支援 Docker、Heroku、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## Online Editor

- [CodeServer](https://github.com/cdr/code-server) - Run VS Code on any machine anywhere and access it in the browser. ([Source Code](https://github.com/cdr/code-server)) `MIT` `TypeScript`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## Reverse Proxy

- [Nginx Proxy Manager](https://nginxproxymanager.com/) - A web interface for managing Nginx proxy hosts with a simple, powerful interface. ([Source Code](https://github.com/jc21/nginx-proxy-manager)) `MIT` `Node.js`
  - 部屬方式：支援 Docker、QNAP NAS 等
  - 客戶端支援：支援 Web 瀏覽器

## Dynamic DNS

- [DDNS-go](https://github.com/jeessy2/ddns-go) - A simple and easy to use DDNS client for multiple DNS providers. ([Source Code](https://github.com/jeessy2/ddns-go)) `MIT` `Go`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## VPN Server

- [OpenVPN](https://openvpn.net/) - An open source VPN solution that provides both server and client software. ([Source Code](https://github.com/OpenVPN/openvpn)) `GPL-2.0` `C`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Windows、MacOS、Linux、Android、iOS 等

## AirPlay Server

- [rahul-thakoor/balena-rpiplay](https://github.com/rahul-thakoor/balena-rpiplay) - Turn a Raspberry Pi into an Airplay server using RPiPlay to enable screen mirroring on tvs, monitors and projectors. ([Source Code](https://github.com/rahul-thakoor/balena-rpiplay)) `Unknown` `Shell`
  - 部屬方式：支援 Docker、balenaCloud 等
  - 客戶端支援：支援任何符合 AirPlay 協議的客戶端
- [FD-/RPiPlay](https://github.com/FD-/RPiPlay) - An open-source implementation of an AirPlay mirroring server for the Raspberry Pi. ([Source Code](https://github.com/FD-/RPiPlay)) `Unknown` `C`
  - 部屬方式：支援 Linux、Raspbian 等
  - 客戶端支援：支援 iOS 9 或更新版本、最新的 macOS 版本等

## Network Tools

- [Nmap](https://nmap.org/) - A free and open source utility for network discovery and security auditing. ([Source Code](https://svn.nmap.org/nmap/)) `GPL-2.0` `C++`
- [Wireshark](https://www.wireshark.org/) - The world’s foremost and widely-used network protocol analyzer. ([Source Code](https://gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`
- [And more...](#and-more)

## Others...
- [ms365-E5-renew-x](https://github.com/DavidDengHui/Microsoft365_E5_Renew_X_Server) - A web service for renewing Microsoft 365 E5 developer subscription using Outlook API. ([Source Code](https://github.com/DavidDengHui/Microsoft365_E5_Renew_X_Server)) `Unknown` `C#`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## Speed Test

- [openspeedtest](https://github.com/librespeed/speedtest) - A self-hosted HTML5 speed test that works with PHP, Node.js, ASP.NET and more. ([Source Code](https://github.com/librespeed/speedtest)) `GPL-3.0` `PHP`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器

## Bookmark Manager

- [shiori](https://github.com/go-shiori/shiori) - A simple bookmark manager built with Go. ([Source Code](https://github.com/go-shiori/shiori)) `MIT` `Go`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器、Android、iOS 等

## Password Manager

- [bitwarden](https://bitwarden.com/) - An open source password management solution for individuals, teams, and business organizations. ([Source Code](https://github.com/bitwarden)) `GPL-3.0` `C#`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援 Web 瀏覽器、Windows、MacOS、Linux、Android、iOS 等
- [vaultwarden](https://github.com/dani-garcia/vaultwarden) - An unofficial Bitwarden compatible server written in Rust. ([Source Code](https://github.com/dani-garcia/vaultwarden)) `GPL-3.0` `Rust`
  - 部屬方式：支援 Docker、Linux、MacOS、Windows 等
  - 客戶端支援：支援任何符合 Bitwarden 協議的客戶端

## AI Drawing

- [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - A browser interface based on Gradio library for Stable Diffusion. ([Source Code](https://github.com/AUTOMATIC1111/stable-diffusion-webui)) `Unknown` `Python`
  - 部屬方式：支援 Linux 等
  - 客戶端支援：支援 Web 瀏覽器
- [stable-duffision-webui-docker](https://github.com/AbdBarho/stable-diffusion-webui-docker) - A Docker setup for Stable Diffusion with user-friendly UI. ([Source Code](https://github.com/AbdBarho/stable-diffusion-webui-docker)) `Unknown` `Python`
  - 部屬方式：支援 Docker 等
  - 客戶端支援：支援 Web 瀏覽器

## And more...

This is just a sample of the awesome projects that you can find in this list. For the full list, please check out the [Awesome-Selfhosted GitHub repository](https://github.com/your_username/Awesome-Selfhosted).