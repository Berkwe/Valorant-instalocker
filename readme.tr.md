<p align="center">
      🌐 <a href=https://github.com/Berkwe/Valorant-instalocker/blob/main/README.md>English</a>  |  Türkçe
</p>

# 🛠️ Valorant Instalocker

Valorant Instalocker, Riot Games’in Valorant oyunu için hızlı ve güvenilir bir otomatik ajan kilitleme aracıdır. Genellikle Valorant instalock aracı veya ajan seçici olarak adlandırılır. Seçtiğiniz ajanı resmi Valorant API’sini kullanarak otomatik olarak seçer ve kilitler. Program Python ile yazılmıştır, basit bir CLI (konsol arayüzü) içerir ve ajan seçme aşamasını önemli ölçüde hızlandıran hafif bir instalocker betiği olarak çalışır. (ve evet bu yazı ai ile yazıldı)

# ❗ÖNEMLİ
**Bu sürüm hala deneme aşamasındadır hatalarınız  [sorunlar](https://github.com/Berkwe/Valorant-instalocker/issues) kısmından iletin lütfen.**

---

## 🆕 Yeni Özellikler v1.7

* **[Masaüstü Kısayol Oluşturma](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#-k%C4%B1sayol-kullan%C4%B1m%C4%B1):** Belirli ajanlar ve modlar için masaüstüne kısayol oluşturabilirsiniz. Kısayolu çalıştırarak hızlıca instalock atabilirsiniz.
* **Dil Desteği:** Instalocker artık birden fazla dil destekliyor, yalnız deneysel bir özellik bu sebeple hataları [Issues](https://github.com/Berkwe/Valorant-instalocker/issues) kısmından bildirebilirsiniz.
* **Otomatik Dil Algılama:** Dil desteği için otomatik dili algılar, valorant ayarlarına göre değişebilir. Yine de [belirli komutlarla](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#a%C5%9Fa%C4%9F%C4%B1daki-komutlar%C4%B1-ajan-ismi-belirleme-k%C4%B1sm%C4%B1nda-kullanabilirsiniz-) değiştirebilirsiniz.
---

## 🚀 Öne Çıkan Özellikler

* **[Komutlar](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#%EF%B8%8F-komutlar):** Instalocker bazı özel komutların kullanılmasına izin verir.
* **[Ajan Kilitleme Modu](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#%EF%B8%8F-ajan-se%C3%A7imi-ve-modlar):** Seçilen ajanı kilitler, klasik instalock.
* **[Sadece Seçme Modu](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#%EF%B8%8F-ajan-se%C3%A7imi-ve-modlar):** Ajanı seçer fakat kilitlemez. Maç sırasında bilgisayar başında olmanıza gerek yok.
* **[Bozma Mekaniği](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#-instalocker-%C3%BCzerinden-ma%C3%A7-bozmak-):** Ajan kitlendikten sonra tek tuşla maç bozabilir, ana menüye dönülür.
* **[Ajan İsim Kısaltma](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#%EF%B8%8F-ajan-i%CC%87sim-k%C4%B1saltmalar%C4%B1):** Uzun isimlere sahip ajanların isimlerini kısaltarak hızlı seçim yapabilirsiniz.
* **[Otomatik Ajan Güncellemesi](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#%EF%B8%8F-otomatik-ajan-g%C3%BCncellemesi):** Yeni ajanlar eklendiğinde otomatik olarak eklenir.
* **[Log Sistemi](https://github.com/Berkwe/Valorant-instalocker/blob/main/readme.tr.md#-log-sistemi):** Hataları kaydeder ve geliştiriciye bildirme kolaylığı sağlar.

---

## 📦 Kurulum

### 💾 Exe ile:

1. **Exe'yi İndirin:**
   [Instalocker.exe](https://github.com/Berkwe/Valorant-instalocker/releases/latest/download/Instalocker.exe)
2. **Çalıştırın:** İki kez tıkla ve çalıştır?

### 🐍 Python ile:

#### Gereksinimler

* Python 3.9+
* Ek modüller (requirements.txt)
* **_Not : Bazı özellikler çalışmayabilir_**
#### Adımlar

1. **Projeyi İndirin:**

   - **[Zip Dosyasını İndirin](https://github.com/Berkwe/Valorant-instalocker/archive/refs/heads/main.zip)**  

   **VEYA**  

   - **Git ile Klonlayın:**
   ```
   git clone https://github.com/Berkwe/Valorant-instalocker
   cd Valorant-instalocker
   ```
2. **Modülleri Kurun:**

   ```bash
   pip install -r requirements.txt
   ```
3. **Çalıştırın:**

   ```bash
   python instalocker.py
   ```

---

## 🛠️ Kullanım

### ⚙️ Ajan Seçimi ve Modlar

- **Ajan Kitleme Modu:** Ajanı kilitler, klasik instalock.
  
- **Sadece Seçme Modu:** Ajanı seçer fakat kitlemez. Bu şekilde maç aranırken bilgisayarda olmanıza gerek yok.

### ⏩ Kısayol Kullanımı

* Masaüstüne kısayol oluşturmak için ajan seçim ekranında E/H yazın.
  
* Masaüstünde ajan isminize ve kullanım modunuza göre bir kısayol belirir.

### 🚫 **Instalocker üzerinden maç bozmak :**
- Ajan kitlendikden sonra konsola e veya y yazmanız yeterlidir. Bozarsanız Instalocker tekrardan başlar, cezalar yine de verilir.

### ⚙️ Komutlar
#### **Aşağıdaki komutları mod seçimi kısmında kullanabilirsiniz :**

```
- 1 : Ajanı seçer ve kilitler, normal (varsayılan) moddur. 
      Hızlı geçmek için Enter’a basabilirsiniz.

- 2 : Ajanı sadece seçer, kilitlemez. 
      Rekabetçi maçlarda veya dereceli modlarda, seçim ekranında bilgisayar başında olmanıza gerek kalmaz.

- 3 yardım / help : Bu yardım mesajını gösterir.
```
#### **Aşağıdaki komutları ajan ismi belirleme kısmında kullanabilirsiniz :**
```
- ajanlar / agents
  → Ajan listesini okunaklı biçimde döndürür.

- ajanlar-l / agents-l
  → Ajan listesini 'liste' biçiminde döndürür.

- güncelle / update
  → Ajan listesini ve dil dosyasını günceller.

- yb / re
  → Uygulamayı hızlıca yeniden başlatır.

- liste-konumu / agents-folder
  → Ajan listesinin konumunu döndürür.

- kayıt-konumu / logs-folder
  → Kayıt dosyasının konumunu döndürür.

- yardım / help
  → Bu yardım mesajını görüntüler.

- türkçe / english
  → Dili Türkçe veya İngilizce olarak değiştirir.
```




### ✂️ Ajan İsim Kısaltmaları
- Ajanların hızlı seçilebilinmesi için eklenen basit bir mekanik. artık 5 karakter üstü isimlere sahip olan ajanların isimlerini kısaltsanız bile seçebileceksiniz, fakat yazılan isim en az 4 karakter olmak zorunda. 

### Kafan mı karıştı? işte bir örnek : 


  ```text
  ✅ brim → geçerli
  ❌ reyn → geçersiz
  ```

### 🔄 Sunucu algılama

* Sunucu otomatik algılanır, manuel giriş olağanüstü durumlarda etkinleşir.(ne olduğunu anlamadıysan bak geç)

### ⬇️ Otomatik ajan güncellemesi:
- #### İnstalocker Artık ajan listesini otomatik olarak sürekli güncelliyor. Fakat bir insan evladı olduğumdan ben de hata yapabilirim, bu yüzden manuel olarak güncellemek gerekebilir. Böyle bir durum olursa aşşağıdaki adımları uygulayın : 
    #### - 1. adım :
    - **CMD(komut istemi) Uygulamasını açın.**
    #### - 2. adım 
    - **Aşşağıdaki kodu yapıştırın :**
    ####
      curl "https://raw.githubusercontent.com/Berkwe/Valorant-instalocker/refs/heads/main/agents.json" > %LOCALAPPDATA%\VALORANT\agents.json

### 🪲 Log Sistemi

* **Instalocker, hata ayıklama ve yönetimi kolaylaştırmak için sürekli olarak log (kayıt) tutar. Logları ayrıntılı hale getirmek için, mod seçimi ekranındayken konsola ‘debug’ yazabilirsiniz. Bu sayede log dosyasını geliştiriciye gönderdiğinizde hatanın anlaşılması daha kolay olacaktır.**

* **Instalocker.log dosyasını bulmak için Windows+R tuş kombinasyonu ile açılan ‘Çalıştır’ penceresine aşağıdaki komutu girebilirsiniz.**

* ```
  %LOCALAPPDATA%/VALORANT
  ```


---


## ⓘ Performans ve Geri Bildirim

* **Performans sorunları veya önerileriniz için** [Issues](https://github.com/Berkwe/Valorant-instalocker/issues) **sayfasını kullanabilirsiniz.**

---

## 🖤 Ayrıca Teşekkürler
- **Projeye direkt katkısı olmasada valorant apisini [dökümanlaştıran](https://github.com/techchrism/valorant-api-docs) [techchrism'e](https://github.com/techchrism) ve bu apiyi modülleştiren [colinhartigan'a](https://github.com/colinhartigan) teşekkürler.**

---

## 🌟 Diğer Projelerim

* [ADB Brute-Force](https://github.com/Berkwe/ADB-bruteforce)
* [Audio Converter](https://github.com/Berkwe/Audio-converter)

---

## 📞 İletişim

<a href="https://discord.gg/Xagnh5aYSy" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Berkwe" height="30" width="40" /></a>

---

## 📝 Lisans

Bu proje [MIT Lisansı](https://github.com/Berkwe/Valorant-instalocker/blob/main/LICENSE) altında lisanslanmıştır.

### 🔑 Anahtar kelimeler
valorant instalocker, valorant auto lock, valorant agent locker, valorant instalock script, valorant agent picker, valorant instalocker gui








