# 🛠️ Valorant Instalocker

Valorant Instalocker, valorant apisini kullanarak hızlıca ajan kitlemeye yarayan bir uygulamadır. Konsol üzerinden çalışır ve temel ihtiyacı [valclient](https://github.com/colinhartigan/valclient.py) modülüdür.

## 🚀 Özellikler
### 🆕 Sürüm v1.5
- **Derleyici değişimi :** Kodun derleyicisi değiştirildi, artık çok daha hızlı.
- **Manuel bozma :** Artık ajan seçme ekranındayken Instalocker üzerinden tek tuşla maçı bozabileceksiniz. Oyundan çıkmadan ana menüye atar (cezalar yine de verilir).
- **Yeni komutlar :** Yeni komutlar ile birkaç işlevsel metot eklendi.
- **Log sistemi :** Log sistemi ile kullanıcılar hata aldıklarında log dosyasını göndererek geliştirme hızını arttırabilecekler.
- **Seçme Modu :** Ajan kitlenmeden seçilebileceği bir mod eklendi, artık küfür yemek yok!
- **Otomatik Sunucu Algılama :** Sunucu girme zahmetinden kurtuldunuz.
- **Ajan İsim Kısaltma Desteği :** Ajan isimleri kısaltıldı, artık zahmetsizce ajan kitlenebilecek.
- **Ajan güncellemesi :** Artık ajanlar sunucudan otomatik olarak çekilebilecek, kullanıcının sürekli uygulamayı güncellemesine gerek kalmayacak [Daha fazla bilgi için tıklayın](https://github.com/Berkwe/Valorant-instalocker?tab=readme-ov-file#-otomatik-ajan-güncellemesi). 

## 📦 Kurulum

### 💾 Exe ile:

1. **Exe'yi İndirin:**
   [Instalocker.exe](https://github.com/Berkwe/Valorant-instalocker/releases/latest/download/Instalocker.exe)

2. **Çalıştırın:**
   - iki kez tıkla ve çalıştır?

### 🐍 Python ile:

#### Gereksinimler
- **Python 3.6+**
- **Birkaç ek modül**

#### Adımlar

1. **Projeyi İndirin:**

- **[Zip Dosyasını İndirin](https://github.com/Berkwe/Valorant-instalocker/archive/refs/heads/main.zip)**  
  Veya  
- **Git ile Klonlayın:**
  ```
  git clone https://github.com/Berkwe/Valorant-instalocker
  cd Valorant-instalocker
  ```

1. **Modülleri İndirmek için proje klasöründe çalıştırın:**
```
pip install -r requirements.txt
```

3. **Çalıştırın:**
```
python instalocker.py
```

## 🛠️ Kullanım

### **Yeni mekanikler detaylı açıklama :**
- **Ajan Kitleme Modu:** Ajanı kilitler, klasik instalock.
- **Sadece Seçme Modu:** Ajanı seçer fakat kitlemez. Bu şekilde maç aranırken bilgisayarda olmanıza gerek yok.

### **Instalocker üzerinden maç bozmak :**
- **Ajan kitlendikden sonra konsola e veya y yazmanız yeterlidir. Bozarsanız Instalocker tekrardan başlar**

### **Ajan İsmi Kısaltmaları:**
- Ajanların hızlı seçilebilinmesi için eklenen basit bir mekanik. artık 5 karakter üstü isimlere sahip olan ajanların isimlerini kısaltsanız bile seçebileceksiniz, fakat yazılan isim en az 4 karakter olmak zorunda. 

### Kafan mı karıştı? işte bir örnek : 

## ✅
```
lütfen bir ajan seçin : brim
```
## ❌
```
lütfen bir ajan seçin : reyn
```

### 🤖 **Otomatik Sunucu Algılama:**
- Eskiden elle girilen sunucular artık otomatik algılanıyor! Fakat bir hata olursa diye manuel olarak da girebilirsiniz.

### 🤖 **Otomatik ajan güncellemesi:**
- #### İnstalocker Artık ajan listesini otomatik olarak sürekli güncelliyor. Fakat bir insan evladı olduğumdan ben de hata yapabilirim bu yüzden manuel olarak güncellemek gerekebilir. Böyle bir durum olursa aşşağıdaki adımları uygulayın : 
    #### - 1. adım :
    - CMD(komut istemi) Uygulamasını açın.
    #### - 2. adım 
    - Aşşağıdaki kodu yapıştırın :
    ####
      curl "https://raw.githubusercontent.com/Berkwe/Valorant-instalocker/refs/heads/Newmain/agents.json" > %LOCALAPPDATA%\VALORANT\agents.json


## 🆙 Yeni bir proje...
- **Hiç beklenmeyen İnstalockerin arayüzlü sürümü geliyor, Çok yakında... (yaklaşık birkaç iş yılı)**
   <img src="https://github.com/user-attachments/assets/96bce6e4-a03f-4ffc-a698-3543a0a7401b" alt="Açıklama" width="500" height="200">
## ⓘ Performans ve Geri Bildirim
- Performans sorunları veya önerileriniz için [Issues](https://github.com/Berkwe/Valorant-instalocker/issues) sayfasını kullanabilirsiniz.

  
## 🖤 Ayrıca Teşekkürler
- **Projeye direkt katkısı olmasada valorant apisini [dökümanlaştıran](https://github.com/techchrism/valorant-api-docs) [techchrism'e](https://github.com/techchrism) ve bu apiyi modülleştiren [colinhartigan'a](https://github.com/colinhartigan) teşekkürler.**

## 🌟 Diğer Projelerim

- **[ADB Brute-Force](https://github.com/Berkwe/ADB-bruteforce): Kablosuz ADB açık cihazlara Brute-Force uygulamak.**
- **[Audio Converter](https://github.com/Berkwe/Audio-converter): Ses dosyalarını kolayca dönüştürmek için araç.**

## 📞 İletişim

<a href="https://discord.gg/Xagnh5aYSy" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Berkwe" height="30" width="40" /></a>

## 📝 Lisans

Bu proje [MIT Lisansı](https://github.com/Berkwe/Valorant-instalocker/blob/main/LICENSE) altında lisanslanmıştır.
