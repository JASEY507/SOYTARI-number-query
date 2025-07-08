SoytariNumber 🕵️‍♂️
Telefon numaralarını analiz eden kullanışlı bir araç! Numaranın ülkesini, operatörünü, türünü (mobil/sabit) ve spam riskini öğrenin. Türkçe, İngilizce ve İspanyolca destekli, şık temalarla!
Özellikler

📞 Numara detaylarını (ülke, operatör, bölge) öğrenin.
🌐 İnternette spam/dolandırıcılık kontrolü yapın.
📊 Birden fazla numarayı toplu analiz edin.
📄 Raporları metin veya PDF olarak kaydedin.
🎨 Karanlık, neon veya pastel tema seçenekleri.
🌍 Türkçe, İngilizce ve İspanyolca dil desteği.

Kurulum (Kali Linux için)
Kali Linux'un kısıtlamaları nedeniyle sanal ortam kullanmanız önerilir. Aşağıdaki adımları takip edin:

Depoyu Klonlayın:
git clone https://github.com/JASEY507/SOYTARI-number-query.git
cd SOYTARI-number-query

Not: Eğer fatal: destination path 'SOYTARI-number-query' already exists hatası alırsanız, mevcut klasörü silin:
rm -rf SOYTARI-number-query

ve tekrar klonlayın.

Sanal Ortam Oluşturun ve Etkinleştirin:
python3 -m venv soytari_venv
source soytari_venv/bin/activate


Bağımlılıkları Yükleyin:
pip install phonenumbers colorama tqdm requests beautifulsoup4

Not: requirements.txt varsa, onunla kurulum yapabilirsiniz:
pip install -r requirements.txt


PDF Raporları için LaTeX Kurun:
sudo apt update
sudo apt install texlive-latex-base latexmk


Programı Çalıştırın:
python3 soytari_number.py



Alternatif: Pipx ile Kurulum
Sanal ortam yerine pipx kullanmak isterseniz:

Pipx'i kurun:sudo apt install pipx


Projeyi yükleyin:cd SOYTARI-number-query
pipx install .


Programı çalıştırın:pipx run soytari_number.py



Kullanım

Programı çalıştırdığınızda bir menü açılır.
Tek numara sorgulayın veya bir dosyaya yazdığınız numaraları toplu analiz edin.
Raporlar otomatik olarak metin ve PDF formatında kaydedilir.

Hata Çözümleri

"externally-managed-environment" Hatası: Sanal ortam (soytari_venv) veya pipx kullanın. Sistem genelinde kurulum yapmaktan kaçının.
"No such file or directory" Hatası: cd SOYTARI-number-query ile doğru klasöre geçtiğinizden emin olun.
Kali Uyarısını Gizleme: Terminaldeki başlangıç mesajını kaldırmak için:touch ~/.hushlogin



Katkıda Bulunun
Fikirlerinizi bekliyoruz! Hata bildirimi veya öneriler için issue açabilirsiniz.
Lisans
MIT Lisansı. Detaylar için LICENSE dosyasını inceleyin.
