# Janjua File Transfer (bina internet file/app transfer)

Ek phone se doosre phone par files, photos, videos, audio aur apps (APK) bhejein, bina internet ke.
Ye Google Nearby Connections (Bluetooth + Wi-Fi) istemal karti hai.

## APK kaise banayein (sirf phone se, computer ke baghair)

1. github.com par free account banayein aur naya repository banayein (naam: OfflineShare).
2. Is zip ki saari files us repository mein upload karein
   (**.github** folder samet, ye zaroori hai).
3. Repository mein **Actions** tab kholein, **Build APK** workflow chalne dein (ya "Run workflow" dabayein).
4. 3-5 minute baad workflow ke andar **Artifacts** mein **OfflineShare-APK** milega. Download karein, zip kholein, `app-debug.apk` install karein.

## Android Studio se banana ho to

Project folder open karein, phir Build > Build APK(s).

## Istemal

- Dono phones par app install karein, Bluetooth aur Location ON rakhein.
- Ek phone par **Receive**, doosre par **Send** dabayein.
- Sender par receiver ka naam aaye to us par tap karein.
- Connect hone ke baad **Files / Photos / Videos** ya **Apps** chun kar bhejein.
- Wasool hui files yahan save hoti hain: **Downloads/OfflineShare**.

## Zaroori baatein

- Dono phones mein Google Play Services hona chahiye (zyadatar phones mein hota hai).
- Apps sirf base APK ke tor par bheji jati hain; split APK wali bari apps (kuch games) shayad na chalein.
- Install karte waqt "Unknown sources" ki ijazat deni pad sakti hai.
- Transfer ke dauran dono phones ki screen on aur app khuli rakhein.
