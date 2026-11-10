# Safety 4.0 Bootcamp — Laboratuvar Föyleri · OPLOG-B2-AMR

Safety 4.0 Bootcamp (Inspecco × Kriptarium) kapsamındaki yedi laboratuvar föyünün, jenerik şişeleme hattı yerine **OPLOG-B2-AMR** (OPLOG'un TARQAN otonom mobil robotu) üzerine uyarlanmış çözümleridir. Föylere ek olarak bu makine için **kör nokta tespiti** ve **SWOT analizi** de yapılmıştır.

| | |
| --- | --- |
| **Ad Soyad** | Özgür Kerem Öncel |
| **Numara** | 225541072 |
| **Şube** | Gece 4/B |
| **Bölüm** | Yazılım Mühendisliği, Fırat Üniversitesi |
| **Örnek makine** | OPLOG-B2-AMR — TARQAN goods-to-person AMR |

## İçindekiler

| # | Çalışma | Çıktı | Evidence Pack | Dosya |
| --- | --- | --- | --- | --- |
| 1 | [Safety Architecture](labs/lab-01-safety-architecture) | Safety Function Map | EP 03 | [PDF](labs/lab-01-safety-architecture/Lab1_Safety_Architecture_OPLOG-B2-AMR.pdf) |
| 2 | [IEC 62443 Mini Workshop](labs/lab-02-iec62443-zone-conduit) | Zone / Conduit Diagram | EP 05 | [PDF](labs/lab-02-iec62443-zone-conduit/Lab2_IEC62443_Zone_Conduit_OPLOG-B2-AMR.pdf) |
| 3 | [Threat & Risk + Risk Matrix](labs/lab-03-threat-risk-matrix) | Risk Register | EP 04 | [PDF](labs/lab-03-threat-risk-matrix/Lab3_Threat_Risk_Matrix_OPLOG-B2-AMR.pdf) |
| 4 | [Secure Remote Access](labs/lab-04-secure-remote-access) | Secure Architecture | EP 02 + 06 | [PDF](labs/lab-04-secure-remote-access/Lab4_Secure_Remote_Access_OPLOG-B2-AMR.pdf) |
| 5 | [SBOM / CVE / Patch](labs/lab-05-sbom-cve-patch) | Vulnerability Decision | EP 09 · 10 · 11 | [PDF](labs/lab-05-sbom-cve-patch/Lab5_SBOM_CVE_Patch_OPLOG-B2-AMR.pdf) |
| 6 | [CRA Incident Simulation](labs/lab-06-cra-incident-simulation) | Incident Workflow | EP 13 | [PDF](labs/lab-06-cra-incident-simulation/Lab6_CRA_Incident_Simulation_OPLOG-B2-AMR.pdf) |
| 7 | [AI Safety Challenge](labs/lab-07-ai-safety-challenge) | AI Fail-Safe Decision | EP 03 + 15 | [PDF](labs/lab-07-ai-safety-challenge/Lab7_AI_Safety_Challenge_OPLOG-B2-AMR.pdf) |
| A | [Kör Nokta Tespiti](analiz/kor-nokta-tespiti) | Blind Spot Register | — | [PDF](analiz/kor-nokta-tespiti/Kor_Nokta_Tespiti_OPLOG-B2-AMR.pdf) |
| B | [SWOT Analizi](analiz/swot-analizi) | SWOT + TOWS | — | [PDF](analiz/swot-analizi/SWOT_Analizi_OPLOG-B2-AMR.pdf) |

Kapak: [docs/kapak.pdf](docs/kapak.pdf)

## Makine özeti

| Özellik | Değer |
| --- | --- |
| Boyut | 950 × 770 × 194 mm |
| Robot kütlesi | 150 kg |
| Yük kapasitesi | 1.000 kg (raf kaldırma) |
| Hız | 2 m/s yüksüz · 1,5 m/s tam yüklü |
| Navigasyon | Ataletsel sensör + zemin QR kodu + motor enkoderi (10 mm sapma) |
| Enerji | ≈5 sa çalışma · ≈1 sa şarj · 3.000 çevrim batarya |
| Yazılım | Akıllı filo yönetimi; WMS ve OPLOG ONE ile entegre |
| Filo | Depo başına 50'ye kadar robot |

Tam yüklü robot + raf (≈1.150 kg) 1,5 m/s'de ≈1.294 J kinetik enerji taşır; risk puanlamalarındaki şiddet değerlerinin dayanağı budur.

## Yöntem

- Makine verileri yalnızca OPLOG'un resmî sayfalarından ve üretici ürün kayıtlarından alındı; **mock veri kullanılmadı**.
- Kaynaklarda bulunmayan emniyet ve siber güvenlik bilgileri (emniyet sensörleri, PLr/SIL, ISO 3691-4/CE, ağ, uzak erişim, SBOM) uydurulmadı. Her biri **"doğrulanacak varsayım / kör nokta"** olarak işaretlendi ve [Kör Nokta Tespiti](analiz/kor-nokta-tespiti) sayfasında toplandı.
- Mevzuat çerçevesi: AB 2023/1230 Makine Yönetmeliği (20.01.2027'den itibaren zorunlu; Ek III 1.1.9 ve 1.2.1) ve AB 2024/2847 Siber Dayanıklılık Yasası (CRA; bildirim yükümlülükleri 11.09.2026'dan beri yürürlükte).

## Kaynaklar

- [OPLOG — Ana sayfa](https://www.oplog.io/tr)
- [OPLOG — TARQAN Fulfillment Robotu](https://www.oplog.io/tr/tarqan)
- [OPLOG — Teknoloji](https://www.oplog.io/tr/teknoloji)
- [OPLOG — OPLOG ONE](https://www.oplog.io/tr/oplog-one)
- [DirectIndustry — TARQAN MK3 teknik özellikleri](https://www.directindustry.com/prod/tarqan-robotics/product-4597254-2750692.html)
- [Mobile Robot Directory — Tarquan TRQ-TD-003](https://www.mobile-robots.com/manufacturer/tarquan/)
- [SAMİB — Sakarya Makine İmalatçıları Birliği](https://samib.org.tr/)
- [UL — EU Machinery Regulation 2023/1230](https://www.ul.com/resources/navigating-new-eu-machinery-regulation-eu-20231230)
- [cyberresilienceact.eu — CRA bildirim yükümlülükleri](https://www.cyberresilienceact.eu/reporting.html)

## Uyarı

Bu çalışma bir eğitim çıktısıdır. Resmî denetim, uygunluk değerlendirmesi veya belgelendirme değildir ve CE / mevzuat uygunluğu garantisi vermez. OPLOG ve TARQAN adları yalnızca örnek makineyi tanımlamak için kullanılmıştır; bu çalışma OPLOG ile bağlantılı değildir.
