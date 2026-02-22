# Merhaba C Programı (Türkçe Karakter Destekli)

Bu repository, C dilinde yazılmış ve Windows konsolunda Türkçe karakter desteği sağlayan basit bir “Merhaba Dünya” programını içerir.

## Kullanım
1. `merhaba.c` dosyasını bir C derleyicisi ile derleyin.  
2. Programı çalıştırın ve konsolda Türkçe karakter içeren mesajı görüntüleyin.

## Özellikler
- Windows konsolu için UTF-8 karakter desteği (`SetConsoleOutputCP` kullanımı)
- Türkçe karakterlerle doğru çıktı (İ, ı, ö, ç, ş, ğ, ü)
- Basit ve taşınabilir C program yapısı

## Geliştirme Ortamı
- **İşletim Sistemi:** Windows 11  
- **Derleyici / IDE:** Embarcadero Dev-C++ (IDE üzerinde “Derle ve Çalıştır” ile test edilmiştir)  
- **Dil Standardı:** ANSI C (C89/90) uyumludur. Windows’a özgü Türkçe karakter desteği için `windows.h` kullanılmıştır.

## Notlar
- Kaynak dosyanın **UTF-8 encoding** ile kaydedilmesi önerilir.
- Türkçe karakterlerin doğru görüntülenmesi için Windows konsolunun UTF-8 kod sayfasına geçirilmesi gerekmektedir.

## Lisans
MIT Lisansı ile lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.