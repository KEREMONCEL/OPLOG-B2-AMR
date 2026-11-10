# LAB 1 · Safety Architecture

**Çıktı:** Safety Function Map · **Evidence Pack:** EP 03 · **Makine:** OPLOG-B2-AMR (TARQAN)

📄 Föy: [Lab1_Safety_Architecture_OPLOG-B2-AMR.pdf](Lab1_Safety_Architecture_OPLOG-B2-AMR.pdf)

## Özet

- Tehlike: ≈1.150 kg robot + raf, 1,5–2 m/s hızda çarpma ve sıkışma (≈1.294 J); raf kaldırmada ezilme.
- Ana emniyet fonksiyonu: insan algılandığında koruyucu durdurma (SF-2); ek olarak acil stop, güvenli hız, ışık perdesi, kaldırma freni.
- Safe state: STO + mekanik fren; raf düşürülmeden tutulur, reset yalnız yerinde.
- Dijital kesişim noktası: filo yönetiminden gelen bölge hız limiti + koruma alanı seti.
- Kör nokta: TARQAN'ın PLr değeri yayımlanmamış.

[← Ana sayfa](../../README.md)
