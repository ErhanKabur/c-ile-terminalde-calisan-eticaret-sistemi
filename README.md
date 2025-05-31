
## Kullanıcı İşlevleri (Müşteri)

Müşteri girişi yapıldığında şu işlemler yapılabilir:

- Ürün listesini görüntüleme (ID, isim, fiyat, stok bilgisi)
- Sepete ürün ekleme (ID ve adet girerek)
- Aynı ürün tekrar eklendiğinde miktar artırılır
- Stok kontrolü yapılır ve stoktan otomatik düşülür
- Sepetteki ürünleri ve toplam tutarı görüntüleme
- Sipariş oluşturma
- Siparişler `siparisler.txt` dosyasına otomatik olarak kaydedilir
- Sipariş ID'si her siparişte otomatik artar ve `siparis_id.txt` dosyasında tutulur

----

## Yönetici İşlevleri

Yönetici girişi yapıldığında şu işlemler yapılabilir:

1. **Stok Miktarı Artırma**
- Var olan bir ürünün stok miktarı artırılabilir.
- Ürün ID'si ve eklenecek miktar girilir.

2. **Yeni Ürün Ekleme**
- Yeni bir ürün ismi, fiyatı ve stok bilgisi girilerek sisteme eklenebilir.
- Ürün ID’si sistem tarafından otomatik olarak verilir.

3. **Siparişleri Görüntüleme**
- `siparisler.txt` dosyasında bulunan tüm siparişler terminalde listelenir.

4. **Çıkış Yapma**
- Yönetici panelinden çıkılır.

----

## Dosyalar

- `siparisler.txt`: Sipariş kayıtlarını tutar.
- `siparis_id.txt`: Her siparişe özel benzersiz bir ID'yi tutar.
- `eticaret.c`: Projenin kaynak kodu.
