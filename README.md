<h1 align="center"> Verify Discord Bot </h1>

> **Verify Bot Discord menggunakan discord.js (v13) dan Berbahasa Indonesia serta dikhususkan untuk server Discord SA-MP**
## 🚀 | Fitur
- 1 Command [(prefix)verify]
- Custom Prefix |  **Default:** ```!```
- Bot Activity + Type (Custom)
- Jika Error, Otomatis Menampilkan Error Pada Console
- Menambahkan Role
- Menambahkan Tag Pada Nickname (Custom)
- Merubah Nickname (Max 25)
- Anti NonRpName (Custom)
- Anti Nickname Berbentuk Angka
- Hanya Dapat Menggunakan Command Pada 1 Channel (Custom)
## ℹ️ | Dibutuhkan
- Discord Bot Token | [Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot) | [Developer Portal](https://discord.com/developers/applications)
- NodeJS V16+ | [Download](https://nodejs.org/en/download/)
- Discord.JS 13+ | [Npm](https://www.npmjs.com/package/discord.js?source=post_page-----7b5fe27cb6fa----------------------) | [Docs](https://discord.js.org/#/)
- ```MANAGE ROLES``` & ```MANAGE NICKNAMES``` Permission
## ⚙️ | Konfigurasi
Berikut adalah format & contoh config.json
> Note: config.json **Wajib** Untuk Diisi
```json
{
  "Bot": {
    "prefix": "",
    "activity": "",
    "actType": ""
  },
  "Verify": {
    "roleID": "",
    "channelID": "",
    "nickTag": "", 
    "nRpName": []
  }
}
```
Contoh config.json:
```json
{
  "Bot": {
    "prefix": "!",
    "activity": "GITHUB",
    "actType": "PLAYING"
  },
  "Verify": {
    "roleID": "929828476222334",
    "channelID": "877982229998877",
    "nickTag": "[WARGA]",
    "nRpName": [
      "NonRpName1",
      "NonRpName2",
      "NonRpName3",
      ]
  }
}
```
## 📸 | Screenshoot
![SCREENSHOT](Screenshot/1.png "Screenshot Verify Discord Bot")
![SCREENSHOT](Screenshot/2.png "Screenshot Verify Discord Bot")
## 👑 | Credits
[@Xzanx](https://github.com/Xzanx)
## 📱 | Discord Server
<a href="https://discord.gg/zY7JfVanSy"><img width="400" height="150" src="https://discord.com/api/guilds/862987839422726164/widget.png?style=banner3"></a>
