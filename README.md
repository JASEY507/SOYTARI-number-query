# SOYTARI-number-query
Telefon Numarası Sorgu Aracı - Phone Number Search Tool



# SOYTARI Number Query

Telefon numaralarını analiz eden Python tabanlı araç.

---

## Gereksinimler

- Python 3.8+
- İnternet bağlantısı
- Python paketleri:
  - phonenumbers
  - colorama
  - tqdm
  - requests
  - beautifulsoup4

---

## Kurulum ve Çalıştırma

### Kali Linux & Linux

```bash
sudo apt update && sudo apt install python3 python3-pip -y
pip3 install phonenumbers colorama tqdm requests beautifulsoup4
git clone https://github.com/JASEY507/SOYTARI-number-query.git
cd SOYTARI-number-query
python3 soytarinumber.py
Termux (Android Terminal)
bash
Kopyala
Düzenle
pkg update && pkg upgrade -y
pkg install python git -y
pip install --upgrade pip
pip install phonenumbers colorama tqdm requests beautifulsoup4
git clone https://github.com/JASEY507/SOYTARI-number-query.git
cd SOYTARI-number-query
python soytarinumber.py
Not: Termux’ta LaTeX yoksa PDF rapor oluşturulmaz, sorun değil.

Pydroid (Android IDE)
Pydroid uygulamasını açın.

Modülleri Paket Yöneticisi’nden kurun: phonenumbers, colorama, tqdm, requests, beautifulsoup4

Repoyu zip indirip Pydroid klasörüne kopyalayın veya dosyaları manuel aktarın.

soytarinumber.py dosyasını açıp çalıştırın.

Not: Pydroid’te otomatik modül yükleme çalışmayabilir, elle kurulum önerilir.

Kullanım
Programı başlatınca menü gelir, numara sorgulama, toplu analiz ve raporlama yapabilirsiniz.

