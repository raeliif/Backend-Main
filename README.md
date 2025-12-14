# Mekanbul Backend

**DEMO:** [Bana Tıkla](https://backend-main-three.vercel.app/)

Bu repo **Mekanbul Backend** uygulamasının basit **Node.js + Express + Mongoose** backend’idir.

## Kısa Açıklama

* API, mekan (venue) verilerini yönetir: listeleme, ekleme, görüntüleme, güncelleme ve silme.
* MongoDB Cloud kullanır. Bağlantı bilgisi için: `app_api/models/db.js`

## Kurulum

```bash
cd /path/to/backend
npm install
```

## Uygulamayı Çalıştırma

```bash
npm start
```

## API Endpoints

* Tüm mekanları listele: **GET** `/api/venues`
* Yeni mekan ekle: **POST** `/api/venues`
* Mekan detayını getir: **GET** `/api/venues/:venueid`
* Mekanı güncelle: **PUT** `/api/venues/:venueid`
* Mekanı sil: **DELETE** `/api/venues/:venueid`
* Yorum ekle (mekana): **POST** `/api/venues/:venueid/comments`
* Yorum getir: **GET** `/api/venues/:venueid/comments/:commentid`
* Yorum güncelle: **PUT** `/api/venues/:venueid/comments/:commentid`
* Yorum sil: **DELETE** `/api/venues/:venueid/comments/:commentid`

## Postman Test Sonucu

Aşağıda Postman ile alınmış test sonuçlarının ekran görüntüsü bulunmaktadır.

![MEKAN LISTELE](./tests/MekanListele.png)
![MEKAN EKLE](./tests/MekanEkle.png)
![MEKAN GETIR](./tests/MekanGetir.png)
![MEKAN GUNCELLE](./tests/MekanGüncelle.png)
![MEKAN SIL](./tests/MekanSil.png)
![YORUM EKLE](./tests/YorumEkle.png)
![YORUM GETIR](./tests/YorumGetir.png)
![YORUM GUNCELLE](./tests/YorumGüncelle.png)
![YORUM SIL](./tests/YorumSil.png)