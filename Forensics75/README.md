# Forensics75

# Change is Good

https://ctf.canyoupwn.me/challenges#Change is good

![exam.png](img/exam.png)

Soruda belirtilen Linkte hmm diye adlandırılmış bir dosya var bunu indirip terminalden dosya şeklini sorgulattığımızda data file olduğu ortaya çıkıyor.

![file.png](img/file.png)

Data dosyasını çalıştırmayı denediğimizde sonuç alamayınca cat komutu ile içeriğini inceliyoruz. Burada pdf ifadesi göze bir çok yerlerde çarpıyor.

![cat.png](img/cat.png)

Dosyayı pdf e çevirip document viewerden açınca flag ortaya çıkıyor.

![evince.png](img/evince.png)


Flag:

```
cypwn_{interesting}
```
