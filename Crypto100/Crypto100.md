The Secret of The Photo

Soruda Canyoupwn me logosuna stenografi kullanarak gizlenmiş şifreli metni bulmamızı istiyor.

[cypwn](/Crypto100/ctf-canyoupwnme.jpg)

bu fotoğraftaki metine terminalden sneghide sayesine ulaşılabilir.
Steghide indirmek için:
'''
apt-get install steghide
'''

[komutlar](Crypto100/komutlar.png)

Bu komutlar ile Fotoğrafta gizlenen metni Steghide ile ortaya "flag.txt" çıktı.
 daha sonra flagdan çıkan kod sonundaki = işaretinden base64 e benziyor gibi ve yine terminal
 üzerinden base64 olan metni normal haline
 '''echo -n "metinnnnn" | base64 -d '''
komutu ile çevrildi.
çıkan sonuç ise Sezar şifreleme ile oluşturulmuş. Sezar şifreleme rotları ise kod yazılmazsa online
olarak çevrilebilir.
örnek site: [PlanetCalc](https://planetcalc.com/1434/)

[rot](Crypto100/rot23)

bu fotoğrafta Sezar şifrelemenin tüm rotlarda denendiği ve sonucun '''cypwn_{flagbulundu}'''
olarak rot23 te karşımıza çıkıyor.
