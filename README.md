# Product Listing System

🎉 Bu projede başlık, kategori ve etiketlere göre filtreleme yapılabilen bir ürün listeleme sistemi geliştirdim. Kullanıcı arama kutusuna bir şey yazdıkça başlık, kategori ve etiketlerdeki eşleşen metne göre ürünler dinamik olarak güncelleniyor.

## Özellikler

- **Filtreleme:** Kullanıcı, başlık, kategori ve etiketlere göre ürünleri filtreleyebilir.
- **Dinamik Güncelleme:** Kullanıcı arama kutusuna yazdıkça ürünler filtreye uygun şekilde güncellenir.
- **Case-insensitive Arama:** Metin büyük/küçük harfe duyarsız şekilde aranır.
- **Verimli İşlem:** Filtreye uymayan ürünler atlanarak işlem daha verimli hale getirilir.

## Teknolojiler

- JavaScript
- toLocaleLowerCase
- includes()
- find() Yöntemi

## Kullanım

1. Arama kutusuna yazmaya başladığınızda, başlık, kategori ve etiketlerdeki eşleşen metne göre ürünler dinamik olarak güncellenir.
2. Filtreye uymayan ürünler işlem dışı bırakılır.
