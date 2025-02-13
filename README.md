<h1 align="center">Rivalz</h1>

> Selamlar, teşvikli Rivalz node va app testleri yaptım. Katılırken birçok şey öğreneceğinizi düşünüyorum.

> Ben Hetzner'den yaptım fakat kendi sunucu sağlayacınızda da benzer şeyleri yaparsınız.
> Donanım kısmı için her sunucu olur, sunucunuz ne kadar iyiyse o kadar ödül demek.

#
<details>
  <summary> <h1> Hetzner VPS Windows Kurulumu</summary> </h1>
    
<h1 align="center">Sadece Hetzner VPS için geçerlidir</h1>


> Windows Server 2019 English'i bulun - Mouth butonuna tıklayın - 3. numaradaki simgeye tıklayın ve sunucunuza bağlanın.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/d0ea7c04-2998-4447-bf6e-62610b76ee5d)

> Açılan yeni sekmede sunucu bilgilerinizi girmenizi isteyecektir. 

> Açılan sekmede sağ altta Ctrl + Alt + Del butonu var, tıkladıktan sonra Windows kurulumu başlayacak.

> Gui seçeneğini seçmeyi unutmayalım.

> Sonrasında mavi arkaplanlı bölüme geçecek, hiçbir ayarı değiştirmeden Next butonuna basıp ardından Install Now butonuna tıklayın. 

> Sonrasında 2. sıradaki Desktop Experince yazana tıklayın.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a09a37af-48c8-43ce-9ae8-007e65ed306f)

> Bir sonraki aşamada Custom: Install Windows only yazana tıklayın ve Hetzner paneline geri dönün. 

> Bu sefer Iso Images kısmına "Virtio" yazın ve fotoğrafdaki işaretli sürümü mounth edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/0c2b193d-aa76-477a-8a4a-e9aef71dc765)

> Sunucuya geri dönün ve Load Driver butonuna tıklayın, ardından görseldeki sürümü seçin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/c016e3b3-fff5-4831-8c0d-cff468c3091f)

> Üç tane Driver göreceksiniz üçü için de delete işlemi yapın.

> Silme işlemi bittikten sonra New butonuna tıklayın ve herhangi bir ayarı değiştirmeden direkt Apply butonuna basın. 

> Sonrasında gelen uyarıda yes butonuna tıklayın.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/3ca7fb7d-0860-4035-a86f-d91817ef8d5e)

> Şimdi Hetzner Paneline tekrar dönün ve Iso images kısmına tıklayın.

> Ve arama yerinden Windows Server 2019 English'i tekrar mounth edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/ad01131d-99ff-4db5-88fb-4b749bbe2b9b)

> Sunucuya geri dönün, Refresh butonuna basın ardından Next butonuna basın. Windows'un kurulmasını bekleyin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a07cb8bb-9327-4d1b-9fc5-e9e759c981e6)

> Sunucumuza off/on yapıyor tekrar bağlanıyoruz.

> Ardından şifre belirleme alanı geliyor burada 8 haneli bir şifre girin büyük harf istiyor.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8d513ee7-7302-47b4-8a31-0fa04f5c2d61)

> Windows'un kilit ekranı kısmına geldiğinizde sağ alttaki Ctrl + Alt + Del butonuna tıklayın ve masaüstüne geçiş yapın. 

> İlk açılışta Server Manager kısmı açılıyor. Alttaki görseli takip edin 3 ve 4. kısımdaki tikler fotoğraftakiyle aynı olmalı.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8f38a679-dea8-49a9-b931-4b01994a5173)

> Kurulum Aşaması bitti, şimdi Ayar kısımlarına geçin.

> Hetznere geri dönün ve Iso Images kısmından bu sefer Virtio win 248'i mounth edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/210356bd-462c-43db-b27e-f04487dce13a)

> Sunucuya geri dönün Windows logosuna sağ tıklayın ve Device Manager'i seçin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/9fb7f205-719c-481f-8051-ad88603a0328)

> Açılan ekranda Other Devices bölümünde 3 veya 4 tane Sarı ünlem görüyorsunuz.

> Önce Ethernet yazana sağ tık yapın ve update driverse tıklayın.

> Browse my computer... yazanı seçin ve fotoğraftaki adımları takip edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/acc911b3-fcfb-4570-9614-c7f9e2e9623f)

> Sağ kısımda Mavi panel açılacak Network başlıklı, Yes butonuna basın. 

> Geri kalan 2 veya 3 Adet sarı ünleme aynı işlemleri yapın.

#

> Windows logosuna tıklayın ve arama yerine Remote Desktop Settings yazın.

> Açılan ekrandaki Enable Remote Desktop kısmını aktif edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/448d8fd2-e841-4719-b95b-a765faf9e707)


> Kişisel bilgisayarınızda Uzaktan Masaüstü bağlantı programı var onu açın.

> Mac'de Microsoft Remote Desktop - Windows'da Windows Remot isminde olmalı.

> Sunucu bilgilerinizi yazıp bağlanın.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/90d5a984-c824-4834-9966-835fc4cee65d)
</details>

<details>
  <summary> <h1> Contabo VPS Windows Kurulumu</summary> </h1>
    
<h1 align="center">Sadece Contabo VPS için geçerlidir</h1>

> Bu işlem için contabo  Aylık 1.5$ istiyor. Normalde Contaboya Windows kurmak isterseniz 6$ masraf çıkartıyor ama bu yöntemle bunu 1.5$a düşebiliyorsunuz.

> Contabo hesabınıza giriş yapın, Control panelinden Custom Imagese tıklayın. Add Custom image butonuna tıklayın.

> Bilgilendirme mesajı gösterirse yes diyip geçin 1. kısımda anlattığım şeyi söylüyor size.

> Karşınıza açılan Panelde verdiğim bilgileri girin.

> Image URL: https://archive.org/download/newIsoForContabo/newIsoForContabo.iso
>
> Image Name: Windows Contabo
>
> Os Type: Windows
>
> Version: 2019
>
> Description: Rues
![image](https://github.com/enzifiri/Rivalz/assets/76253089/71a3ff23-0075-4abc-934a-c6208623d7ac)

> Upload butonuna basın ve dolmasını bekleyin. Bu adımda yüklenmesi contabodan kaynaklı olarak 1-2 saat sürebiliyor. Yüklendikten sonra diğer adıma geçin.

# Kurduğumuz İso dosyasını sunucuya mounth etme adımı
> Vps kontrol kısmına gidin, Önce Cloud init kısmını yeşil yapın, sonra Re install butonuna basın.
![image](https://github.com/enzifiri/Rivalz/assets/76253089/d00b1652-51e7-4239-9ce6-5333a1adcf60)

> Görseldeki adımları sırasıyla yapın.
> Windows Contaboyu seçtikten sonra Install butonuna basın. 5 Dakika sonra bir sonraki adıma geçin.
![image](https://github.com/ruesandora/Rivalz/assets/76253089/ea4eac88-f4a9-4291-b9e1-bb7a4fd854bf)


# Windows kurulumu başlayacak, şimdi VNC ile sunucumuza bağlanmamız gerekiyor. 
> Windows pc kullanıyosanız Mobaxterm ile bağlanabilirsiniz.
> New Session oluşturup VNCyi seçin, VNC bağlantı bilgilerinizi bir sonraki adımda nasıl öğrenebileceğinizi göstereceğim.
![image](https://github.com/enzifiri/Rivalz/assets/76253089/ee192e2b-1ded-48fc-b558-109a04c2a553)

# VNC bilgilerinim nerede?

> VPS control kısmında sunucunuzu bulun ve manage butonuna tıklayın VNC Informationda bilgileriniz yazıyor.

> VNC ile bağlanınca mouse sıkıntısı oluyor, bu yüzden mouse kullanmak yerine TAB tuşu ve Enter tuşu ile gerekli işlemleri yapabilirsiniz.
![image](https://github.com/enzifiri/Rivalz/assets/76253089/cc81709b-df3b-49e6-94e4-0b3f1717dfa3)

# Windows Kurulumunu tamamlayalım.

> Mavi arkaplanlı kısım gelecek hiçbir ayarı değiştirmeden Next'e basın ve ardından Install Now butonuna tıklayın. 

> Sonrasında 2. sıradaki Desktop Experince yazana tıklıyoruz.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a09a37af-48c8-43ce-9ae8-007e65ed306f)

> Sonraki aşamada Custom: Install Windows only yazana tıklayın.

> Bu kısımı lütfen iyi okuyun atlarsanız diskiniz gözükmeyecektir.

> Load Driver butonuna tıklayın
> Browse butonuna tıklayın ve ardından D: disketindeki (177 ile başlayan) > virio-win klasörü > amd64 > 2k19 klasörünü seçin ve Ok butonuna tıklayın.
> Eğer doğru klasörünü seçtiyseniz Red Hat SCSI ... ile başlayan bir text gelecek onu seçip next butonuna basın.

![image](https://github.com/enzifiri/Rivalz/assets/76253089/1fc9b04f-d7f9-4bbf-9677-3e0f2a89e0dc)

> New butonuna basın, hiçbir ayarı değiştirmeden Apply butonuna basın ve Next yapın.

![image](https://github.com/enzifiri/Rivalz/assets/76253089/7a6a13cb-72c5-4cd7-940d-dd0a8043e613)

> Sunucumuza off/on yapıyor tekrar bağlanıyoruz. (EĞER SİYAH EKRANDA KALDIYSANIZ BUNU YAPIN NORMALDE OTOMATİK YAPIYOR.)

> Akabinde şifre belirleme alanı geliyor burda 8 haneli bir şifre girin büyük harf istiyor.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8d513ee7-7302-47b4-8a31-0fa04f5c2d61)

> Windowsun kilit ekranı kısmına geldiğinizde sağ alttaki Ctrl + Alt + Del butonuna tıklayın ve masaüstüne geçiş yapın.
![image](https://github.com/enzifiri/Rivalz/assets/76253089/1796694a-5a90-479d-9c98-6682684c5a3b)

> İlk açılışta Server Manager kısmı açılıyor. Alttaki görseli takip edin 3 ve 4. kısımdaki tikler fotoğraftakiyle aynı olsun.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8f38a679-dea8-49a9-b931-4b01994a5173)

# Windows Server Ayarlarımızı tamamlayalım. 

> Şifreyi ayarlayıp giriş yaptıktan sonra Windows logosuna sağ tıklayın ve Device Manager'i seçin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/9fb7f205-719c-481f-8051-ad88603a0328)

> Açılan ekranda Other Devices bölümünde 3 veya 4 tane Sarı ünlem görüyorsunuz.

> Önce Ethernet yazana sağ tık yapın ve update driver'e tıklayın.

> Browse my computer... yazanı seçin ve fotoğraftaki adımları takip edin.

![image](https://github.com/enzifiri/Rivalz/assets/76253089/e207a615-4ac1-40fb-a087-b1fe919b1660)


> Sağ kısımda Mavi panel açılacak Network başlıklı, Yes butonuna basın. 

> Geri kalan 2 veya 3 Adet sarı ünleme aynı işlemleri yapın.

#

> Windows logosuna tıklayın ve arama yerine Remote Desktop Settings yazın.

> Açılan ekrandaki Enable Remote Desktop kısmını aktif edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/448d8fd2-e841-4719-b95b-a765faf9e707)


> Kişisel bilgisayarınızda Uzaktan Masaüstü bağlantı programı var onu açın.

> Mac'de Microsoft Remote Desktop - Windows'da Windows Remote isminde olmalı.

> Sunucu bilgilerinizi yazıp bağlanın.
> Kullanıcı Adı: Administrator
> Şifre: Windows kururken girdiğiniz şifre
![image](https://github.com/enzifiri/Rivalz/assets/76253089/454b08a5-bdf5-4c1b-b9a9-3b31cc7ac67b)

# Windows kurulumu bitti, Şimdi Rivalz Node'yi kurmaya devam edebilirsiniz.

</details>

<details>
  <summary> <h1> Ubuntu VPS Sunucu Kurulumu </summary> </h1>
    <h1 align="center">Sadece Ubuntu için geçerlidir</h1>
    
> Sunucuya bağlandığınızı farz ederek devam edelim.
> Sunucu güncelleme, libfuse2 ve gereklilikleri yüklüyoruz.
```
sudo apt update -y && sudo apt upgrade -y
```
```
sudo apt-get install -y gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget libgbm-dev libnss3-dev libfuse2
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/72cb8fa9-4079-47f1-a41f-5b609cc4a3a1)

> ekran açın.
```
screen -S rivalz
```

> rivalz clienti indirin.
```
wget https://api.rivalz.ai/fragmentz/clients/rClient-latest.AppImage
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/c1393ff3-f43b-4b3b-8620-79db8c937b50)

> indirdiğiniz dosyayı executable yapın.
```
chmod +x rClient-latest.AppImage
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/cb35396c-4c4b-4f16-ad0a-ab7ed3ca0501)

> dosyayı açın.
```
./rClient-latest.AppImage --no-sandbox
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/e556d8ba-64d0-4bf9-aec6-02beb0ae9fb4)
> bir sorun çıkmaz ise karşınıza bu ekran gelecek.
> 
> bundan sonra storage belirleyip, wallet girerek yapabilirsiniz. Tebrikler! Linuxda rclient açabiliyorsunuz artık.

![image](https://github.com/awelmisin/Rivalz/assets/73443933/0ab8f196-0c17-44bc-b536-e1a25445357a)

</details>

# Rivalz Node Kurulumu

> Rivalz hesap açıyoruz [buradan](https://rivalz.ai?r=Ruesandora0)

> Burada cüzdan, X (formerly Twitter), Discord ve her şeyi bağlayın.

#

> Remote ile bağlandığımız ekrana geri dönün.

> Microsoft Edge'yi Remote'ye yani sunucuya indirin.

> rivalz.ai sitesine girip downland Windows deyin.

> Kurulumu yapıyoruz.

#

> Kurulum tamamlandıktan sonra, önce Metamask cüzdan adresinizi girin.

> Storage Control'den free space neye müsade ediyorsa o rakamı girin.

> 3-4 GB daha düşük yazın.

> Sonra başlatıyoruz node'yi ve hayırlı olsun.

>  rClient uygulamasında sol üstte view sekmesi var oradan reload'a basıp, node'yi tekrar çalıştırın.

<img width="1251" alt="Ekran Resmi 2024-05-25 00 38 38" src="https://github.com/ruesandora/Rivalz/assets/101149671/cdf68d07-c897-4e5a-93d8-b34e2c4a82ee">

#

> Akabinde rivalz'da LOYALTY NFTs kısmını yapmayı unutmayın ve 10 NFT'yi mint edin.
