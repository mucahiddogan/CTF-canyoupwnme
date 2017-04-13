# Crypto50

# OldSchool

![ctf](img/ctf.png)

Bu soruda ise 2 tane karışık harflerden oluşan string verilmiş.
Soruda Keyi kullanarak Text i çözümlememiz isteniyor bu verilerle şifrenin Vigenere şifreleme
ile oluşturulduğu belli oluyor.

Vigenere Cipher linki: [Vigenere](http://rumkin.com/tools/cipher/vigenere.php)

![vigenere](img/vigenere.png)

Ardından ise ortaya çıkan metin "jevgrvagbsyntsbezng" yeni bir şifreleme yöntemi ile çözülmesi gerekiyor.
Çoğu yöntemleri denedikten sonra Bunun Ceaser şifrelemenin en bilineni ROT13 ile şifrelendiği ortaya çıkıyor.

ROT13 Linki: [ROT13](http://www.rot13.com/)

![rot13](img/rot13.png)

Flag:

```
cypwn_{writeintoflagformat}
```
