# LAB 7 · AI Safety Challenge

**Çıktı:** AI Fail-Safe Decision · **Evidence Pack:** EP 03 + EP 15 · **Makine:** OPLOG-B2-AMR (TARQAN)

📄 Föy: [Lab7_AI_Safety_Challenge_OPLOG-B2-AMR.pdf](Lab7_AI_Safety_Challenge_OPLOG-B2-AMR.pdf)

## Özet

- YZ yalnız lojistik kararı verir; durdurma kararı her zaman YZ dışındaki safety yolunda kalır.
- Yanlış sınıflandırma → barkod + WMS eşleştirmesi ve insan onayı (human override).
- Manipüle girdi → QR–IMU–enkoder tutarlılık kontrolü, şüphede dur ve alarm (monitoring + fail-safe).
- Düşük güven → validasyonla belirlenen eşik altında insana sor veya deterministik navigasyona geç (threshold + fallback).

[← Ana sayfa](../../README.md)
