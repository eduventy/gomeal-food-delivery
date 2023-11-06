Eduventy - FrontEnd Development Eğitim Programı 


## Uygulamalayı Geliştirirken İzlenecek Yol

- Git reposu yaratın
- Bir NextJS uygulaması oluşturup repoya pushlayın 
- Proje içindeki **public** klasörü içinde **assets** klasörü yaratın
- Size erişimi verilen **Figma** dosyasındaki assetleri (icon,image vb) assets klasörüne gruplayarak export edin
- Figma tasarımındaki font/fontları google web fonts dan bulup projenize import edin
- Tasarımın genel renk tonlarını / başlık yazı vb font stillerini boyutlarını vb ortak kullanım css class ları haline getirin
- Anasayfa'yı nextjs in **app** klasörü içinde oluşturun. _(İçerikleri elle girin)_.
  -  Anasayfa'da yer alan ve başka sayfalarda kullanılacak componentleri parçalayarak ilgili yere taşıyın _( components klasörü )_
- Diğer Sayfaları da yaratın ve içerisine dummy bir yazı koyun sadece 
  - Food Order, Favorite, Order History, Settings
- İçeriklerin size verilen API 'den gelmesini sağlayın.
- Sepet vb yerler için ***Redux*** geliştirmelerini yapın (actions, reducer, dispatch, useSelector vb kullanımı
- Login ve Signup için modal olarak çalışan sayfaları yaratın
- NextAuth kurulumunu yapın ve sayfalar içinde session / auth kullanmaya başlayın

# SAYFALAR / EKRANLAR

## Anasayfa
Kategoriler, Popüler yemekler/menüler ve Daha önce verilen siparişleri listeler. 
Figma tasarımına göre yapın. Verilen tamamı size verilen API 'den gelecektir. 

## Food Order
Yemek Sipariş aşamalarının olduğu çok adımlı ekran. Figmada bulunan tasarıma göre yapın.
Aşamaların her birinde size verilen API ile etkileşerek ilerleyin.

## Favorite
Favorilere eklenmiş olan yemeklerin listesidir. Figmada yer alan tasarıma göre yapın.
Favori yemeklerin listesini size verilen API'den çekin.

## Order History
Daha önce verilen siparişlerin geçmişini listeler. Figmada yer alan tasarıma göre yapın.
Datayı size verilen API 'den çekiniz.