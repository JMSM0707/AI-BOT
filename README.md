# AI Gaea tarmoq BOT
AI Gaea tarmoq BOT

Bu yerda roʻyxatdan oʻting : [AI Gaea Network](https://app.aigaea.net/register?ref=ga7GghLTUytlcs) | Referal koddan foydalaning: ga7GghLTUytlcs

## Xususiyat

  - Hisob ma'lumotlarini avtomatik olish
  - Agar siz 1 tani tanlasangiz, avtomatik proksi bilan avtomatik ishga tushirish [foydalaning [Monosans Proxy](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt)]
  - Agar siz 2 ta tanlasangiz, qo‘lda proksi bilan avtomatik ishga tushirish [shaxsiy proksini manual_proxy.txt ga joylashtirish]
  - Agar siz 3 ni tanlasangiz, proksisiz avtomatik ishga tushirish
  - Mavjud topshiriqni avtomatik bajarish
  - Avtomatik xabarlarni har 15 daqiqada qabul qilish
  - Boshqaruv paneli va kengaytma tarmog'ini avtomatik ulash
  - Mavzular bilan ko'p hisoblar

## Shart

Python3.9 dan yuqori va PIP o'rnatilganligiga ishonch hosil qiling.

## O'rnatish

1. **Repozitoriy klonlash:**
   ```bash
   git clone https://github.com/JMSM0707/AI-BOT.git
      ```
   ```bash
   cd AI-BOT-master.zip
   ```

2. **O'rnatish talablari:**
   ```bash
   python INSTALL.BAT yoki pip install -r requirements.txt #yoki pip3 install -r requirements.txt
   ```
![image](https://github.com/user-attachments/assets/39bcdbfd-705e-45a3-bdb4-a88ef694bad9)

## Konfigurasi

### Screenshots

<div style="text-align: center;">
  <h4><strong>brauzer identifikatorining birinchi 8 ta raqami ID</strong></h4>
  <img src="image.png" alt="Image" width="500"/>
</div>

- **accounts.json:** Siz faylni accounts.json loyiha katalogida topasiz. accounts.json unda skript formatiga mos keladigan ma'lumotlar mavjudligiga ishonch hosil qiling, aks holda skript ishlamaydi. Mana fayl formatlariga misollar:


  ```bash
    [
        {
            "Browser_ID": "The first 8 digits of your browser_id 1",
            "Token": "Your aigaea_bearer_token 1"
        },
        {
            "Browser_ID": "The first 8 digits of your browser_id 2",
            "Token": "Your aigaea_bearer_token 2"
        }
    ]
  ```
- **manual_proxy.txt:** Anda akan menemukan file `manual_proxy.txt` di dalam direktori proyek. Pastikan `manual_proxy.txt` berisi data yang sesuai dengan format yang diharapkan oleh skrip. Berikut adalah contoh format file:
  ```bash
    ip:port #http or socks5 - change schemes in line 113
    http://ip:port
    socks4://ip:port
    socks5://ip:port
    http://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks4://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks5://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
  ```

## Jalankan

```bash
python bot.py #or python3 bot.py
```

## Penutup

Terima kasih telah mengunjungi repository ini, jangan lupa untuk memberikan kontribusi berupa follow dan stars.
Jika Anda memiliki pertanyaan, menemukan masalah, atau memiliki saran untuk perbaikan, jangan ragu untuk menghubungi saya atau membuka *issue* di repositori GitHub ini.

**vonssy**
