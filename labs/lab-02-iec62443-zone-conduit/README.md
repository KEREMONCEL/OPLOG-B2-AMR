# LAB 2 · IEC 62443 Mini Workshop

**Çıktı:** Zone / Conduit Diagram · **Evidence Pack:** EP 05 · **Makine:** OPLOG-B2-AMR (TARQAN)

📄 Föy: [Lab2_IEC62443_Zone_Conduit_OPLOG-B2-AMR.pdf](Lab2_IEC62443_Zone_Conduit_OPLOG-B2-AMR.pdf)

## Özet

- Bölgeler: Z0 Safety (SL-3), Z1 Hücre, Z2 Denetim (filo yönetimi, WMS), Z3 Mühendislik, DMZ, Z4 Kurumsal/bulut (OPLOG ONE).
- Safety kontrolörü Z0'da tek başına; hiçbir bölgeden komut almaz, yalnız durum bilgisi verir.
- Conduit'ler C1–C5: izin listeli WMS API, 802.1X robot WLAN, Z0'a yalnız okuma, bakım penceresi, jump server.
- Uzak erişim kararı: Jump server · VPN · MFA · kişisel hesap · tam oturum kaydı · varsayılan kapalı.

[← Ana sayfa](../../README.md)
