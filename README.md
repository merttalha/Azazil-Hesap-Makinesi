# Azazil-Hesap-Makinesi
Azazil Türkçesi Yazılım Dili ile Hesap Makinesi Yaptık

işte kod:

```python
fonksiyon topla(sayı1, sayı2):
    sonuç = sayı1 + sayı2
    yazdır("Sonuç: " + str(sonuç))

fonksiyon çıkar(sayı1, sayı2):
    sonuç = sayı1 - sayı2
    yazdır("Sonuç: " + str(sonuç))

fonksiyon çarp(sayı1, sayı2):
    sonuç = sayı1 * sayı2
    yazdır("Sonuç: " + str(sonuç))

fonksiyon böl(sayı1, sayı2):
    eğer sayı2 == 0:
        yazdır("Bir sayıyı 0'a bölemezsiniz!")
    değilse:
        sonuç = sayı1 / sayı2
        yazdır("Sonuç: " + str(sonuç))

fonksiyon hesap_makinesi():
    yazdır("Hesap Makinesi")
    yazdır("1: Topla")
    yazdır("2: Çıkar")
    yazdır("3: Çarp")
    yazdır("4: Böl")
    
    seçim = giriş("Bir işlem seçin (1/2/3/4): ")

    eğer seçim içinde ['1', '2', '3', '4']:
        sayı1 = float(giriş("Birinci sayıyı girin: "))
        sayı2 = float(giriş("İkinci sayıyı girin: "))

        eğer seçim == '1':
            topla(sayı1, sayı2)
        iken seçim == '2':
            çıkar(sayı1, sayı2)
        iken seçim == '3':
            çarp(sayı1, sayı2)
        iken seçim == '4':
            böl(sayı1, sayı2)
    değilse:
        yazdır("Geçersiz seçim, lütfen 1-4 arasında bir sayı seçin.")
    giriş("Programı kapatmak için bir tuşa basın...")

# Hesap makinesini çalıştır
hesap_makinesi()


```
