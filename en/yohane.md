---
title: "Yohane Commands"
old_id: 4
---
Berikut ini adalah command-command yang ada di bot Yohane.

## Yohane In-Game

### General commands
- `!roll [angka]` - Memberikan random number
- `!help` - Memberikan daftar bantuan
- `!subscribe pp [options]` - Untuk menampilkan status pp seperti limit dan notifikasi jika sudah selesai [submit score](https://cdn.discordapp.com/attachments/265909019976138754/801454622346444860/unknown.png). (options : `set`,`get`,`unset`,`toggle`)
- `!boardshow [options]` - [Experimental] Untuk menyembunyikan diri dari leaderboard (options : `others`,`normal`)
- `!report` - Jika kalian menemukan cheater, silahkan gunakan command ini.
- `!faq list` - Daftar hal yang sering dibutuhkan dalam chat.

### Multiplayer commands

Semua command yang ditampilkan disini hanya yang secara umum atau membutuhkan penjelasan. Mohon gunakan `!mp help` apabila bingung dengan command yang tidak terdaftar.

- `!mp help` - Untuk menampilkan command multiplayer selengkapnya.
- `!mp make [name]` - Membuat room multi
- `!mp close` - Menutup room multi
- `!mp checkperm` - Menampilkan permission level pada pengirim.
- `!mp listref` - Menampilkan referee pada room.
- `!mp addref <username>` - Menambahkan user menjadi referee pada room.
- `!mp rmref <username>` - Mengeluarkan user dari referee pada room.
- `!mp start [timer]` - Membuat semua pemain siap secara otomatis dan memulai permainan setelah waktu habis (Default: `0`). Dapat dilakukan untuk solo-play pada multi room.
- `!mp abort` - Untuk membatalkan permainan tersebut. *Hal ini berbeda dengan menggunakan `Escape`-key pada solo-play*

Note: untuk semua operasi menggunakan Username Lookup, dapat menggunakan `#<UserID>` sebagai penggantinya.

### Admin commands
- `!system restart` - Restart the server. Everyone will be disconnected and reconnected automatically
- `!system status` - Show server status
- `!system reload` - Reload bancho settings (the one that are editable from DAP)
- `!system maintenance on/off` - Turn on/off bancho maintenance mode
- `!moderated on/off` - Turn on/off moderated mode for the current channel
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence a user
- `!removesilence <target>` - Remove target's silence
- `!kick <username>` - Kick an user from the server
- `!ban <username>` - Ban and kick someone
- `!unban <username>` - Unban someone
- `!restrict <username>` - Restrict someone
- `!unrestrict <username>` - Unrestrict someone  
- `!fokabot reconnect` - Reconnect YohaneBOT if he's not on online users list anymore  
- `!alert <message>` - Send a notification to every user connected to bancho
- `!alertuser  <username> <message>` - Send a notification to a specific user
- `!whitelist <username> <mode> <type> [procedure]` - Melakukan whitelisting pada PP limit pada suatu user.
    
    | Parameter | Nilai | Fungsi |
    | :-- | :-: | :-- |
    | `mode` | `vanilla`, `relax` | Menentukan mode permainan yang di-*whitelist* |
    | `type` | `total`, `all` | Menentukan jenis batasan yang di-*whitelist* |
    | `procedure` | `add`, `set` | *Optional*<br>Menentukan operasi pengubahan nilai *whitelist* PP |
- `!map <command> <type> <ID>` - Melakukan operasi pada suatu map(set)
    
    | Parameter | Nilai | Fungsi |
    | :-- | :-: | :-- |
    | `command` | `rank`, `love`, `unrank`, `reset` | Melakukan pengubahan status map langsung. |
    | `command`\* | `auto-rank`, `auto-love`, `auto-cancel` | **Khusus yang dapat mengatur autorank**<br>Menentukan kelayakan suatu map untuk mendapatkan auto-rank. |
    | `type` | `set`, `set-of`, `map` | `set` - menggunakan **mapset ID** dalam mengambil data.<br>`set-of` - menggunakan **map ID** untuk mendapatkan **daftar map dengan mapset ID** dari **map ID** yang diberikan<br>`map` - menggunakan **map ID** dalam mengambil data. |
    
    Untuk lebih jelasnya, dapat memperhatikan [contoh berikut](https://cdn.discordapp.com/attachments/265909019976138754/801471868699410473/unknown.png)

### Note
Jika kalian ingin menggunakan command melalui private message Yohane, tidak perlu menggunakan prefiks-"!"
- Diluar itu, prefiks-"!" diperlukan untuk memanggil command Yohane.

## YohaneBot Discord
- `@faq help` - Untuk menampilkan seluruh command
- `@stats [options] [nickname]` - Untuk menampilkan status profile (options : `vanilla`,`relax`)
- `@recent [options] [nickname]` - Untuk menampilkan recent score (options : `vanilla`,`relax`)
- `@top [options] [nickname]` - Untuk menampilkan top score (options : `vanilla`,`relax`)
