SoytariNumber 🕵️‍♀️


SoytariNumber, telefon numaralarını analiz eden güçlü bir araç! Numaranın ülkesini, operatörünü, türünü (mobil/sabit) ve spam riskini anında öğren. Türkçe, İngilizce, İspanyolca destekli, karanlık, neon veya pastel temalarla şık bir deneyim sunar.
🌟 Özellikler



📞 Ülke, operatör ve bölge bilgisi.  


🌐 Spam/dolandırıcılık kontrolü.  


📊 Toplu numara analizi.  


📄 Metin veya PDF raporlar.  


🎨 Karanlık, neon, pastel temalar.  


🌍 Türkçe, İngilizce, İspanyolca dil desteği.



🛠️ SoytariNumber Kurulumu (Termux ve Kali Linux)
SoytariNumber’ı Termux veya Kali Linux’ta çalıştırmak için bu 3 adımı takip et. %100 çalışır, basit ve hızlı!



1. SoytariNumber’ı İndir
GitHub’dan projeyi çek ve klasöre gir:
Komut:

---
git clone https://github.com/JASEY507/SOYTARI-number-query.git
--
cd SOYTARI-number-query
--


Not: "Klasör zaten var" hatası alırsan, sil ve tekrar indir:
Komut:

---
rm -rf SOYTARI-number-query
git clone https://github.com/JASEY507/SOYTARI-number-query.git
--
cd SOYTARI-number-query
----

2. Kütüphaneleri Kur
Programın çalışması için gereken Python kütüphanelerini yükle:
Termux için:

---
pip3 install phonenumbers colorama tqdm requests beautifulsoup4
-----


Kali Linux için:

---
pip3 install phonenumbers colorama tqdm requests beautifulsoup4 --break-system-packages
-----



3. SoytariNumber’ı Çalıştır
Programı başlat (ana dosya main.py):
Komut:

---
python3 main.py
---


Not: Dosya adını doğrulamak için:
Komut:

---
ls
---


Eğer dosya main.py değilse (örneğin, başka bir isim), listedeki doğru adı kullan:
Komut:

-----
python3 <doğru_dosya_adı>.py
-----

PDF Raporları için LaTeX (İsteğe Bağlı)
Raporları PDF olarak kaydetmek istersen LaTeX kur. Gerek yoksa bu adımı atla:
Termux için:

---
pkg install texlive-installer
---

Kali Linux için:

----
sudo apt update
sudo apt install texlive-latex-base latexmk
---

📋 Nasıl Kullanılır?


SoytariNumber açılınca menüden seçim yap.  
Tek numara sorgula veya bir dosyadaki numaraları toplu analiz et.  
Sonuçlar metin dosyasına, LaTeX kurduysan PDF’e kaydedilir.




🤝 Katkıda Bulun
Fikirlerinle SoytariNumber’ı geliştir! GitHub Issues sayfasında paylaş.
📜 Lisans
MIT Lisansı. Detaylar için LICENSE dosyasını oku.
