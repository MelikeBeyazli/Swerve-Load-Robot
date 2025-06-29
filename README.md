# Swerve-Load-Robot — Tasarım & Mekanik Analiz Projesi  
*(Mekatronik Mühendisliği Tasarım Dersi, 2024 Bahar Dönemi)*

Bu depo; makaslı kaldırma mekanizması ve swerve‑drive tahrik sistemine sahip  
dört tekerlekli bir **yük robotunun** SolidWorks CAD dosyalarını ve ANSYS tabanlı  
mekanik analiz çıktılarının özetlerini içerir. Çalışma, 2024 ilkbaharında ders  
projesi olarak yürütülmüş ve aynı yıl bir ulusal sempozyum bildirisi ile hakemli  
dergi makalesi biçiminde yayınlanmıştır.

---

## 1 | Ekip ve Sorumluluklar

| Klasör | İçerik | Sorumlu Öğrenci |
|--------|--------|-----------------|
| `cad/car_body/` | Beş karoser prototipi ve final gövde | **Melike Beyazlı** |
| `cad/chassis/`  | Sigma‑profil şasi tasarımları | **Görkem Burak Taşkın** |
| `cad/wheels/`   | Yedi PU‑kaplı tahrik tekeri modeli | **Sümeyye Alp** |
| `cad/lift/`     | Üç makaslı kaldırma tasarımı | **Zeynep Işık**, **Görkem B. Taşkın** |
| `cad/swerve-load-robot/` | Nihai bütünleşik montaj (.SLDASM) | Tüm ekip |
| `analysis/ansys/` | ANSYS Workbench projeleri (.wbpj) | **Zeynep Işık** |
| `analysis/reports/` | PDF/PNG gerilim‑deformasyon özetleri | Tüm ekip |
| `docs/` | • **Makale**: Mısır, O., Beyazlı, M., Alp, S., Taşkın, G. B., *vd.* (2024). *Design and Mechanical Analyses of Mobile Robot with Swerve Driving System*. **Türk Doğa ve Fen Dergisi, 13(4), 66‑84.** doi:10.46810/tdfd.1506516  <br>• **Bildiri**: Beyazlı, M., Alp, S., Taşkın, G. B., Işık, Z. (2024). *Dört Tekerlekli Yük Taşıma Özelliğine Sahip Otonom Mobil Robotun Geliştirilmesi.* UEBAS’24, 16‑17 Mart 2024. | Derleme: **Melike Beyazlı** |


---

## 2 | Çalışma Takvimi (2024)

| Ay | Önemli Adımlar |
|----|----------------|
| Şubat | Konsept belirleme; ilk karoser ve şasi çizimleri |
| Mart  | Teker prototipleri; IV. Ege Bilimsel Araştırmalar Sempozyumu bildirisi |
| Nisan | ANSYS Workbench kurulumu; malzeme kütüphanesi oluşturma |
| Mayıs | Karoser, şasi, teker ve kaldıraca ait ayrık FEA çalışmaları |
| Haziran | Nihai montaj **Swerve‑Load‑Robot** tamamlandı |
| Temmuz | Bandırma DergiPark makalesi tamaml anıp gönderildi |

---

## 3 | Klasör Yapısı

```
swerve-load-robot/
├── cad/
│   ├── car_body/            # Karoser taslakları
│   ├── chassis/             # Şasi modelleri
│   ├── wheels/              # Teker varyasyonları
│   ├── lift/                # Kaldırma mekanizmaları
│   └── swerve-load-robot/   # Nihai montaj (.SLDASM)
├── analysis/
│   ├── ansys/               # *.wbpj projeleri
│   └── reports/             # PDF/PNG sonuçlar
├── docs/
│   ├── Swerve...Robot_Tasarımı.docx
│   ├── Dört_Tekerlekli_Yük_Taşıma_Robot.pptx
│   └── Sunum_Özeti_Dört_Tekerlekli_Yük_Taşıma.docx
└── README.md
```

---

Bu özet, depodaki her bileşenin **kim** tarafından hazırlandığını ve **nerede**  
bulunduğunu netleştirir. Ayrıntılı CAD modelleri ve analiz raporları ilgili  
klasörlerde mevcuttur.
