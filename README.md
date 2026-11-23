<div align="center">

# İbrahim Umut Eke

**Elektrik-Elektronik Mühendisliği Öğrencisi**
Güç Elektroniği · Donanım Tasarımı · Gömülü Sistemler

Sakarya Üniversitesi

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahim-umut-eke-4673913ab)

</div>

---

### Hakkımda

Sakarya Üniversitesi Elektrik-Elektronik Mühendisliği bölümünde 2. sınıf öğrencisiyim. Çalışmalarımı **elektronik kart (PCB) tasarımı** ve **gömülü sistemler** üzerine yoğunlaştırıyorum. Şu anda insansız hava aracı (İHA) ve savunma sanayii projeleri için elektronik kart tasarımı yapıyorum. Ayrıca lityum-iyon bataryalar için aktif hücre dengeleme üzerine hazırladığım **TÜBİTAK 2209-A** araştırma projesinin yürütücüsüyüm.

Teorik bilgiyi sahada çalışan donanıma dönüştürmeyi hedefliyorum. Şematik tasarım, devre simülasyonu ve mikrodenetleyici programlama alanlarında kendimi sürekli geliştiriyorum.

---

### Çalışma Alanları

- **Güç Elektroniği:** DC-DC dönüştürücüler, gate sürücü devreleri ve batarya yönetim sistemleri (BMS)
- **Elektronik Kart Tasarımı:** Şematik çizimi, bileşen seçimi ve PCB yerleşim-yönlendirme
- **Devre Analizi ve Simülasyon:** Analog ve güç devrelerinin tasarım öncesi doğrulanması
- **Gömülü Sistemler:** Mikrodenetleyici tabanlı sistemlerin donanım ve yazılım geliştirmesi
- **Havacılık ve Savunma Elektroniği:** Zorlu çalışma koşullarına uygun kart tasarımı

---

### Projeler

#### [İki Hücreli Lityum-İyon Bataryalar İçin Gerilim Tabanlı Aktif Dengeleme Yönetim Algoritması](https://github.com/ibrahimumuteke/aktif-hucre-dengeleme)
*TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri · Proje Yürütücüsü (güç katı ve donanım tasarımı)*

Seri bağlı Li-iyon hücreler arasındaki gerilim farkını gideren bir **aktif hücre dengeleme** sistemi geliştiriyorum. Sistem, enerjiyi yüksek gerilimli hücreden düşük gerilimli hücreye bir bobin üzerinden aktarıyor. Geliştirilen yöntem, aynı kart üzerindeki direnç tabanlı **pasif dengeleme** ile deneysel olarak karşılaştırılacak.

- **Topoloji:** Tek bobinli, yarım köprü buck-boost aktif dengeleyici (2S Li-iyon paket)
- **Donanım:** STM32F103, IR2104 bootstrap gate sürücü, IRLZ44N MOSFET'ler, INA219 akım/gerilim ölçümü, NTC ile sıcaklık izleme, TVS/snubber koruma
- **Kontrol:** 25 kHz, %50 doluluk oranlı tamamlayıcı PWM ve ölü zaman. Enerji aktarım yönü, ayrı bir yön kararı gerekmeden hücre gerilimleri tarafından kendiliğinden belirlenir.
- **Yönetim algoritması:** Dört durumlu durum makinesi (bekleme, dengeleme, durdurma, hata). Dengeleme 30 mV eşiğine göre başlatılır ve durdurulur; aşırı akım, gerilim ve sıcaklıkta köprü kapatılır.
- **Ön benzetim (LTspice):** 200 mV başlangıç farkında pasif yönteme göre yaklaşık **1,6 kat daha hızlı** dengeleme, **%94,4** güç katı aktarım verimi ve **çok daha düşük enerji kaybı** (0,021 J'e karşı 0,341 J) *(ölçekli model, ön tasarım değerleri)*
- **Deneysel doğrulama:** Farklı başlangıç gerilim farklarında (50/100/200 mV) dengeleme süresi, enerji kaybı, aktarım verimi ve termal kamera ile kart sıcaklığı ölçümü
- **Süreç:** Tasarım hesapları → LTspice benzetimi → gömülü yazılım ve kalibrasyon → çift katmanlı PCB → karşılaştırmalı deneyler → analiz

#### Diğer Çalışmalar

| Proje | Kapsam | Rolüm |
|---|---|---|
| **[Akıllı Güç Dağıtım Kartı (İHA)](https://github.com/ibrahimumuteke/akilli-pdb)** | 6S / 80 A İHA için yedekli aviyonik beslemeli, elektronik kill switch'li 4 katmanlı güç dağıtım kartı *(geliştirme aşamasında)* | Kişisel proje, tasarım |
| **Savunma Sanayii Projesi** | Savunma sistemlerine yönelik elektronik kart geliştirme | Kart tasarımı |

---

### Teknik Yetkinlikler

| Alan | Araçlar |
|---|---|
| **PCB ve Şematik Tasarım** | ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) |
| **Devre Simülasyonu** | ![LTspice](https://img.shields.io/badge/LTspice-555555?style=flat-square) ![Tinkercad](https://img.shields.io/badge/Tinkercad-1477D1?style=flat-square&logo=tinkercad&logoColor=white) |
| **Mikrodenetleyiciler** | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) |
| **Programlama** | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) |
| **Teknik Çizim** | ![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?style=flat-square&logo=autodesk&logoColor=white) |
| **Geliştirme Ortamları** | ![STM32CubeMX](https://img.shields.io/badge/STM32CubeMX-03234B?style=flat-square) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Code::Blocks](https://img.shields.io/badge/Code::Blocks-41AD48?style=flat-square) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

### Güncel Hedefler

- C dilinde ileri seviye gömülü yazılım geliştirme
- STM32 mikrodenetleyicileri ile çevre birimi (UART, SPI, I2C, ADC) uygulamaları
- Çok katmanlı PCB tasarımı ve sinyal bütünlüğü
- Aktif hücre dengeleme prototipini tamamlayıp deneysel sonuçları yayımlamak
- Kart tasarımlarımı ve gömülü yazılım çalışmalarımı bu profilde paylaşmak

---

### İletişim

Projelerim, staj ve iş birliği fırsatları için LinkedIn üzerinden ulaşabilirsiniz.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-İbrahim%20Umut%20Eke-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahim-umut-eke-4673913ab)

---

<details>
<summary><b>English</b></summary>

<br>

**İbrahim Umut Eke**, Electrical and Electronics Engineering Student at Sakarya University

I am a second-year Electrical and Electronics Engineering student focusing on **power electronics**, **PCB design** and **embedded systems**. I am currently designing electronic boards for a UAV project and for defense industry projects.

I am also the principal investigator of a **TÜBİTAK 2209-A** undergraduate research project: *Development and Experimental Validation of a Voltage-Based Active Balancing Algorithm for Two-Cell Lithium-Ion Batteries*. The project uses an inductor-based half-bridge buck-boost balancer driven by an STM32F103 and compares it experimentally with passive (resistive) balancing.

**Focus areas:** power electronics and battery management, schematic and PCB design, circuit simulation, microcontroller-based embedded systems, aerospace and defense electronics.

**Tools:** KiCad, LTspice, Tinkercad, STM32 (CubeMX), Arduino, C, AutoCAD, VS Code, Git.

**Contact:** [LinkedIn](https://www.linkedin.com/in/ibrahim-umut-eke-4673913ab)

</details>
