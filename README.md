# 6-Bit-kodlama-sistemi-ile-karakter-Tabanl-Toplama-uygulamas-
Proje Başlığı: Tek Haneli Sayı Toplama ve Kontrol Programı
Kısa Açıklama
Bu C programı, kullanıcıdan girilen tek haneli iki sayı karakterini (0-9 arası) alır, sayıya dönüştürür ve toplar. Toplamın da tek haneli (yani ≤9) olup olmadığını kontrol eder. Kullanıcı isterse işlemi tekrarlayabilir.

Özellikler
Giriş Doğrulama: Girilen karakterlerin gerçekten tek haneli bir rakam (0-9) olup olmadığını kontrol eder.

Hata Kontrolü: Geçersiz girişler için kullanıcıya net hata mesajları sunar.

İşlem Kontrolü: İki tek haneli sayının toplamının da tek haneli (maksimum 9) olması kuralını uygular ve bu kurala uymayan sonuçlar için hata verir.

Döngü Yapısı: Kullanıcıya yeni bir işlem yapma veya programı sonlandırma seçeneği sunar.

Nasıl Çalışır?
Program, kullanıcıdan ilk tek haneli sayı karakterini girmesini ister.

Girişin 0-9 arasında ve tek karakter olduğundan emin olmak için doğrulama yapılır.

Aynı adımlar ikinci karakter için de uygulanır.

Geçerli iki karakter girildikten sonra, bunlar tamsayıya dönüştürülür ve toplanır.

Toplam 9'dan büyükse hata mesajı gösterilir. Aksi takdirde, sonuç ekrana yazdırılır.

Kullanıcıya yeni bir işlem yapıp yapmayacağı sorulur (1 = Evet, 0 = Hayır).

Geçerli bir devam cevabı (1 veya 0) alınmazsa veya kullanıcı 0'ı seçerse program sonlanır.

Kullanılan Kütüphaneler
stdio.h: Giriş/Çıkış işlemleri için (printf, scanf).

string.h: Karakter dizisi uzunluğunu kontrol etmek için (strlen).
