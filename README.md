# SOYTARI-number-query
Telefon Numarası Sorgu Aracı - Phone Number Search Tool


## Kurulum ve Çalıştırma Rehberi

**Kali Linux ve Linux Dağıtımları için:** Terminali açıp önce `sudo apt update && sudo apt upgrade -y` komutuyla sistemi güncelleyin. Ardından `sudo apt install python3 python3-pip -y` ile Python ve pip’i kurun. Gerekli Python paketlerini yüklemek için `pip3 install phonenumbers colorama tqdm requests beautifulsoup4` komutunu çalıştırın. Sonra repoyu `git clone https://github.com/JASEY507/SOYTARI-number-query.git` ile klonlayın, `cd SOYTARI-number-query` ile dizine girin ve `python3 soytarinumber.py` komutuyla programı başlatın.

**Termux (Android Terminal) için:** Termux’u açıp `pkg update && pkg upgrade -y` ile paketleri güncelleyin. `pkg install python git -y` ile Python ve git’i yükleyin. `pip install --upgrade pip` ile pip’i güncelleyin, sonra `pip install phonenumbers colorama tqdm requests beautifulsoup4` komutuyla gerekli kütüphaneleri kurun. Repo klonlama ve çalıştırma için sırasıyla `git clone https://github.com/JASEY507/SOYTARI-number-query.git`, `cd SOYTARI-number-query` ve `python soytarinumber.py` komutlarını kullanın. Termux’ta LaTeX genellikle yoktur, PDF raporu oluşturma kısmı çalışmayabilir ama bu temel işlevleri etkilemez.

**Pydroid (Android Python IDE) için:** Pydroid uygulamasını açın ve Paket Yöneticisi’nden `phonenumbers`, `colorama`, `tqdm`, `requests` ve `beautifulsoup4` modüllerini tek tek kurun. Daha sonra GitHub’dan repoyu zip olarak indirip cihazınıza aktarın veya dosyaları manuel kopyalayın. Pydroid içinde `soytarinumber.py` dosyasını açıp çalıştırın. Otomatik modül yükleme çalışmayabilir, bu yüzden modülleri elle kurmanız gereklidir.

---

Program açıldığında kullanımı kolay menü gelir, buradan tek tek veya toplu numara analizleri yapabilir, sonuçları ekranda görebilir ve `.txt` dosyası olarak rapor kaydedebilirsiniz. İnternet bağlantısı gereklidir. PDF rapor için LaTeX kurulu olmalıdır; kurulu değilse sadece metin raporu oluşturulur. Eksik modül hatası alırsanız paketleri manuel yükleyin. Sorun yaşarsanız GitHub Issues üzerinden bildirin.

Bu rehberle Kali Linux, Termux ve Pydroid üzerinde sorunsuz kurulum ve kullanım sağlanır.
