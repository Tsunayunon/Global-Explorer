
---

# Ülke Arama ve Bilgi Sorgulama Programı

Bu Python programı, kullanıcının kıta, para birimi, telefon kodu gibi özelliklere göre ülke bilgilerini görüntülemesini ve sorgulamasını sağlar. Program, JSON formatındaki veri dosyalarından ülke verilerini alır ve kullanıcı arayüzü üzerinden erişilebilir bir şekilde sunar.

## Kullanım

1. `main.py` dosyasını çalıştırın.
2. Menüdeki seçenekler arasından birini seçin:
   - Kıtaları ve ülkeleri görüntülemek için "Kıtaları Göster"
   - Para birimine göre ülkeleri bulmak için "Para Biriminden Ülke Bul"
   - Telefon koduna göre ülkeleri bulmak için "Telefon Kodundan Ülke Bul"
   - Ülke isimlerini görüntülemek için "Ülke İsimlerini Göster"
   - Bir ülke hakkında detaylı bilgi sorgulamak için "Ülke Bilgisi Sorgula"
   - Programdan çıkmak için "Çıkış"
3. İlgili seçeneği seçtikten sonra, programın yönergelerini izleyin.

## Sınıflar ve Metodlar

- `Menu`: Kullanıcı arayüzünü sağlar ve kullanıcının seçimlerini işler.
- `load_json_data`: JSON formatındaki veri dosyalarını yükler.
- `show_continents`: Kıtalar ve ülkeleri görüntüler.
- `find_country_by_currency`: Para birimine göre ülkeleri bulur.
- `find_country_by_phone`: Telefon koduna göre ülkeleri bulur.
- `show_country_names`: Ülke isimlerini görüntüler.
- `query_country_info`: Bir ülke hakkında detaylı bilgi sorgular.

## Dosyalar

- `continent.json`: Kıta verilerini içeren JSON dosyası.
- `currency.json`: Para birimi verilerini içeren JSON dosyası.
- `iso3.json`: ISO3 kodu verilerini içeren JSON dosyası.
- `phone.json`: Telefon kodu verilerini içeren JSON dosyası.
- `names.json`: Ülke isimlerini içeren JSON dosyası.

## Geliştirme

Bu program, temel bir ülke arama ve bilgi sorgulama aracıdır. Geliştirmek için şunları yapabilirsiniz:

- Mevcut veri dosyalarını güncelleyin veya yeni veri kaynakları ekleyin.
- Kullanıcı arayüzünü geliştirin ve daha kullanıcı dostu hale getirin.
- Ek özellikler ekleyin, örneğin, ülke arama fonksiyonlarına filtreleme veya sıralama seçenekleri ekleyin.

## Lisans

Bu program MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasını inceleyin.

---
