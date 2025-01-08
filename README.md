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
            "Browser_ID": "Brauzer identifikatoringizning dastlabki 8 ta raqami 1",
            "Token": "Sizning aigaea token belgisi 1"
        },
        {
            "Browser_ID": "Brauzer identifikatoringizning dastlabki 8 ta raqami 2",
            "Token": "Sizning aigaea token belgisi 2"
        }
    ]
  ```
- **manual_proxy.txt:** Siz faylni manual_proxy.txt loyiha katalogida topasiz. manual_proxy.txt unda skript formatiga mos keladigan ma'lumotlar mavjudligiga ishonch hosil qiling aks holda skript ishlamaydi. Mana fayl formatlariga misollar:

  ```bash
  http://user:pass@ip:port
  socks4://user:pass@ip:port
  socks5://user:pass@ip:port
  ```

## Ishga tushurish

 ```bash
python bot.py #yoki python3 bot.py
 ```

## Yopish

Ushbu omborga tashrif buyurganingiz uchun tashakkur, kuzatishlar va yulduzchalar shaklida hissa qo'shishni unutmang. Savollaringiz bo'lsa, muammolarga duch kelsangiz yoki yaxshilash bo'yicha takliflaringiz bo'lsa, men bilan bog'laning yoki ushbu GitHub omborida muammoni oching.

**JMSM0707**
