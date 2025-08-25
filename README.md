# enviroment-variable

 işletim sistemi veya uygulamalara bilgi taşıyan isim–değer çiftleri. gerekli ayarları, yolları ve kullanıcı bilgilerini içerir.
# Tüm Değişkenleri Listelemek
```bash
printenv
```
```
echo $PATH
ÇIKTI:/home/esmaerenesmaeren/.local/bin:/usr/local/sbin:/usr/sbin:/sbin:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games

echo $HOME
echo $USER

```
# Yeni Değişken Tanımlamak
```
MYVAR="Merhaba"
echo $MYVAR
```
# Sık Kullanılan Ortam Değişkenleri

* PATH: Komutların aranacağı dizinleri belirtir
* HOME:Kullanıcının ana dizini
* USER:Aktif kullanıcı adı
* SHELL:Kullanılan shell’in yolu (ör. /bin/bash)
* PWD:Bulunduğun dizin


