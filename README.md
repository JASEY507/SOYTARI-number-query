SoytariNumber 🕵️‍♂️


Telefon numaralarını analiz eden süper bir araç! Numaranın ülkesini, operatörünü, türünü (mobil mi, sabit mi) ve spam riskini kolayca öğren. Türkçe, İngilizce ve İspanyolca destekli, karanlık, neon ya da pastel temalarla tarzını yansıt!
🌟 Neler Yapabilir?



📞 Numaranın ülkesini, operatörünü ve bölgesini gösterir.  



🌐 İnternette spam ya da dolandırıcılık izi arar.  



📊 Bir sürü numarayı toplu analiz eder.  



📄 Sonuçları metin ya da PDF olarak kaydeder.  



🎨 Şık temalar: Karanlık, neon, pastel.  



🌍 Türkçe, İngilizce, İspanyolca dil seçenekleri.





🛠️ Kurulum (Termux ve Linux)
SoytariNumber’ı Termux ya da Linux’ta (Kali, Ubuntu gibi) çalıştırmak için aşağıdaki adımları izle. Her şey basit, hızlı ve net!

1. Depoyu İndir
İlk adım, projeyi cihazına çekmek. Aşağıdaki komutla GitHub’dan indir:
-----
git clone https://github.com/JASEY507/SOYTARI-number-query.git
--
cd SOYTARI-number-query
----




Eğer "klasör zaten var" gibi bir hata alırsan, mevcut klasörü sil ve tekrar indir:
Hata Çözümü:




rm -rf SOYTARI-number-query
-
git clone https://github.com/JASEY507/SOYTARI-number-query.git
-
cd SOYTARI-number-query
---------

3. Sanal Ortam Oluştur
Kütüphaneleri sistemine bulaştırmamak için sanal ortam kullanıyoruz. Bu, her şeyi düzenli tutar:



---

python3 -m venv soytari_venv
--
source soytari_venv/bin/activate
--



4. Kütüphaneleri Yükle
Programın çalışması için gerekli Python kütüphanelerini kur:



---
pip install phonenumbers colorama tqdm requests beautifulsoup4
---



5. PDF Raporları için LaTeX Kur (İsteğe Bağlı)
Analiz sonuçlarını PDF olarak kaydetmek istersen LaTeX kur. PDF istemezsen bu adımı atlayabilirsin:
Termux için:




---
pkg install texlive-installer
---




Linux için:

----
sudo apt update
-
sudo apt install texlive-latex-base latexmk
---




5. Programı Çalıştır
Her şey hazır! Şimdi programı başlat:




---
python3 soytari_number.py
---




📋 Nasıl Kullanılır?

Program açılınca bir menü çıkar.  
Tek bir numarayı sorgula ya da bir dosyaya yazdığın numaraları toplu analiz et.  
Sonuçlar otomatik olarak metin dosyasına ve (LaTeX kurduysan) PDF’e kaydedilir.



🤝 Katkıda Bulun
Fikrin mi var? Hata mı buldun? İnstagram: @soytariomer.17 Mesaj Yaz, birlikte geliştirelim!

