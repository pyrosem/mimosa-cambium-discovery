# Mimosa & Cambium Discovery Tool

🔍 **IP adresinden bağımsız olarak Mimosa ve Cambium kablosuz ağ cihazlarını bulan araç.**

## Özellikler

- ✅ IP adresi bilinmese bile cihazları bulur (Layer 2 sniffing)
- ✅ Mimosa ve Cambium cihazlarını otomatik tespit eder
- ✅ Türkçe ve İngilizce dil desteği
- ✅ Otomatik güncelleme kontrolü
- ✅ Npcap otomatik kurulum desteği

## Kurulum

### Hazır EXE (Önerilen)
1. [Releases](https://github.com/pasbery/mimosa-cambium-discovery/releases) sayfasından `WirelessDiscoverySetup.exe` indirin
2. Kurulumu çalıştırın
3. Npcap kurulumu sırasında **"Install Npcap in WinPcap API-compatible Mode"** seçeneğini işaretleyin

> ⚠️ **Windows SmartScreen Uyarısı:** İlk çalıştırmada "Windows kişisel bilgisayarınızı korudu" uyarısı çıkabilir. **"Daha fazla bilgi"** → **"Yine de çalıştır"** butonuna tıklayarak devam edebilirsiniz. Bu uyarı, programın henüz dijital imzası olmadığı için çıkmaktadır.

### Kaynak Koddan
```bash
pip install scapy
python mimosa_discovery_v3.py
```

## Kullanım

1. Programı **Yönetici olarak** çalıştırın
2. Ağ arayüzünü seçin veya "OTOMATİK" modunu kullanın
3. "DİNLEMEYİ BAŞLAT" butonuna tıklayın
4. Mimosa/Cambium cihazının fişini çekip takın (cihaz paket gönderecektir)
5. Cihaz listede görünecektir

## Desteklenen Cihazlar

| Üretici | MAC OUI |
|---------|---------|
| Mimosa | 20:B5:C6 |
| Cambium | 00:04:56, 30:CB:C7, 58:C1:7A, 90:14:AF, 90:6D:62, B4:A2:5C, BC:A9:93, BC:E6:7C, FC:11:65 |

## Gereksinimler

- Windows 10/11
- Npcap (kurulum sırasında otomatik yüklenir)
- Yönetici yetkisi

## Lisans

MIT License
