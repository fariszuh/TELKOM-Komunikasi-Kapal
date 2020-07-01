# TELKOM-Komunikasi-Kapal
dalam project ini dibuat:
- Komunikasi terestrial FULL DUPLEX antara pemancar dan kapal
- Komunikasi satelit dengan VSAT
## Terestrial dengan LTU-AP
Studi kasus diambil dari pantai utara-laut jawa di Kec. Brondong, Lamongan, Jawa Timur. Dipilihnya lokasi ini karena wilayah ini merupakan salah satu sentra pemasok ikan laut tangkap terbesar di Jawa Timur.
Berikut kontur medan di wilayah tsb.
![Medan Kec. Brondong](/images/Kapal_Brondong.JPG) ![Polar](/images/Loc._POLAR_Kapal_Brondong.JPG)
### Pemancar
Pemancar diletakkan di daerah yang tinggi, seperti di bukit Puncak Menculuk Jaya (26 mdpl) [lat:-6,894967 long:112,275141](https://goo.gl/maps/1ktb5UN6UFanX5qy5), angle pemancar digunakan 120 derajat
![mdpl](/images/ketinggian_gunung_pemancar.JPG)
Pemancar menghubungkan 2 kapal, yakni kapal1 (kanan) dan kapal2 (kiri). Digunakan perangkat LTU Rocket dengan spesifikasi [berikut](https://store.ui.com/collections/operator-airmax-and-ltu/products/ltu-rocket) dan datasheet perangkat [berikut](https://dl.ubnt.com/ds/ltu-rocket). Harga USD399
![Loc](/images/airlink_lokasi.JPG)
![Loc zoom](/images/airlink_lokasi_pemancar.JPG)
Untuk antena yang dapat digunakan 
![Loc](/images/antena_ltu_rocket.JPG)
harga antena bervariasi. Tiang tower dapat memakai tower triangle/fourangle
### Kapal 1
Kapal 1 terletak di laut jawa [lat:-6,635976 long:112.5075](https://goo.gl/maps/cGWQihGx88Sr25Ue7)
![Loc](/images/airlink_kapal_2.JPG)
![Loc](/images/Port-Kapal1.JPG)
Receiver dapat menggunakan LTU-Pro dengan spesifikasi [berikut](https://store.ui.com/collections/operator-airmax-and-ltu/products/ltu-pro) dan datasheet [berikut](http://ui.com/downloads/ds/ltu-pro), harga USD179
### Kapal 2
Kapal 2 terletak di laut jawa [lat:-6,623547 long:112,2531](https://goo.gl/maps/cGWQihGx88Sr25Ue7)
![Loc](/images/airlink_kapal_1.JPG)
![Loc](/images/Port-Kapal2.JPG)
Receiver dapat menggunakan LTU-LR dengan spesifikasi [berikut](https://store.ui.com/collections/operator-airmax-and-ltu/products/ltu-lr) dan datasheet [berikut](https://dl.ui.com/ds/ltu-lr_ds.pdf), harga USD179
### Pros-Cons
1. Pros:
- lebih murah
2. Cons:
- rentan gangguan
- pemasangan ribet
- mudah loss bila terlalu jauh dari garis pantai

## Satelit dengan VSAT-Ku Band
