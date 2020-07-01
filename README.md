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
harga antena bervariasi. Tiang tower dapat memakai tower triangle/fourangle. Harga tiang bermacam-macam, umumnya dihitung per meter ketinggian.
### Kapal 1
Kapal 1 terletak di laut jawa [lat:-6,635976 long:112.5075](https://goo.gl/maps/cGWQihGx88Sr25Ue7)
![Loc](/images/airlink_kapal_2.JPG)
![Loc](/images/Port-Kapal1.JPG)
Receiver dapat menggunakan LTU-Pro dengan spesifikasi [berikut](https://store.ui.com/collections/operator-airmax-and-ltu/products/ltu-pro) dan datasheet [berikut](http://ui.com/downloads/ds/ltu-pro), harga USD179
### Kapal 2
Kapal 2 terletak di laut jawa [lat:-6,623547 long:112,2531](https://goo.gl/maps/cGWQihGx88Sr25Ue7)
![Loc](/images/airlink_kapal_1.JPG)
![Loc](/images/Port-Kapal2.JPG)
Receiver dapat menggunakan LTU-LR dengan spesifikasi [berikut](https://store.ui.com/collections/operator-airmax-and-ltu/products/ltu-lr) dan datasheet [berikut](https://dl.ui.com/ds/ltu-lr_ds.pdf), harga USD129
### Pros-Cons
1. Pros:
- lebih murah
2. Cons:
- rentan gangguan
- pemasangan ribet
- mudah loss bila terlalu jauh dari garis pantai
- agak tidak mungkin membuat tiang terlalu tinggi, juga kecepatan angin pantai yang berhembus (baik siang/malam).
- tiang antena kapal terlalu tinggi (Kapal 1-->terjauh butuh hingga 9m) rawan tersambar petir

## Satelit dengan VSAT
![vsat gyro](https://ecs7.tokopedia.net/img/cache/700/product-1/2018/11/15/11554200/11554200_b8932015-152d-426f-8395-3b29c41d9af0_800_800.jpg.webp)
VSAT Maritime **DIREKOMENDASIKAN** untuk industri maritim, terlebih pada kapal-kapal penangkap ikan. VSAT Maritim dilengkapi dengan gyro yang berfungsi menstabilkan arah pancaran sinyal tepat menuju satelit melalui rotasi lengan. Biaya layanan bervariasi. Untuk akses internet digunakan Ku-Band. Beberapa penyedia jasa juga menawarkan sewa perangkat. Misalnya, [Primadona Net](primadonanet.co.id)

*KU Band merupakan jaringan yang lahir setelah C Band. KU Band memiliki rentang frekuensi 11,7-12,2 GHz untuk komunikasi dari satelit ke penerima di bumi (downlink).  14,0-14,5 GHz untuk komunikasi dari penerima di bumi ke satelit (uplink). KU Band, biasanya, digunakan untuk siaran dan koneksi internet dua arah. Rentang frekuensi KU Band dialokasikan secara eksklusif untuk digunakan oleh sistem komunikasi satelit, sehingga menghilangkan masalah interferensi dengan sistem terestrial gelombang mikro. Karena panjang gelombang yang lebih kecil dan bandwidth yang lebih lebar, maka dimungkinkan untuk menggunakan antena penerima beserta power yang lebih kecil namun kapasitas kecepatan internet-nya lebih besar.*
### Pros
Pada awal komunikasi satelit, C band adalah satu-satunya pilihan. Kehadiran KU Band berhasil menggeser kepopuleran C Band karena beberapa alasan. Sinyal yang dipancarkan KU Band sangat kuat, padahal menggunakan dish berukuran mini bahkan seukuran tutup panci untuk menerima sinyal siaran dan tahan terhadap kebisingan. Sistem perangkat antena dan paket layanan berbasis internet yang lebih praktis dan murahpun menguntungkan pelanggan. Walau dikenal lemah ketika musim penghujan, kini dampak dari hujan lebat telah dapat dikurangi. Dengan disain engineering dan peralatan teknologi mutakhir layanan pada frekuensi KU Band dapat mengimbangi keadaan cuaca di negara tropis.
Dengan begitu sistem perangkat kini sanggup bertahan online saat hujan. Layanan KU Band banyak digunakan oleh lembaga komersil yang menerapkan biaya berlangganan kepada konsumennya. Khususnya bagi mereka yang selalu mencari inovasi untuk menurunkan biaya berlangganan dan pembelian antena bagi pelanggan. Banyak pula kantor cabang perusahaan-perusahaan yang membutuhkan kecepatan internet VSAT broadband puas ketika menggunakan layanan ini. Layanan jaringan pada frekuensi KU Band juga cocok digunakan untuk berbagai service application pada sosial media.
### Cons
Memang sistem perangkat 1,2meter KU Band lebih murah dari C Band, namun ketahanannya terhadap cuaca harus diakui masih berada sedikit dibawah C Band. Sinyal akan hilang (sesaat) pada awal terjadinya hujan besar, sesaat setelah sistem perangkat KU Band selesai melakukan restart maka sistem akan menghidupkan kembali akses internet dengan modulasi yang lebih rendah secara otomatis. [sumber: https://ksinergi.co.id/pilih-ku-band-atau-c-band/](https://ksinergi.co.id/pilih-ku-band-atau-c-band/)

Harga perangkat dan layanan  mahal.
Ukuran antena cenderung besar (kurang cocok untuk kapal nelayan kecil)

Area coverage tergantung wilayah cover satelit. Tiap-tiap penyedia jasa memiliki batas jangkauan masing-masing. Alangkah lebih baik bila membuat kerjasama dengan penyedia layanan (penawaran biasanya berbeda-beda).

### Detil harga
Layanan perangkat oleh Primadona Net Rp12.5 juta/bln (opsi beli perangkat+layanan), Rp25 juta/bln (opsi sewa perangkat+layanan), [link Tokopedia](https://www.tokopedia.com/primadona-net/layanan-internet-satelit-vsat-maritim-vsat-kapal-gyro-vsat) baca comment
Perangkat VSAT antena gyro oleh Primadona Net Rp100 juta [link tokopedia](https://www.tokopedia.com/primadona-net/perangkat-gyro-vsat-satellite-untuk-kapal-laut)
Perangkat VSAT antenna oleh Intellian harga:USD24740 (merek lain untuk kapal2 penangkap besar) [https://www.satphonestore.com/application-browsing/new-satellite-phone/intellian-v65-65cm-ku-band-marine-vsat-antenna-system-18964.html](https://www.satphonestore.com/application-browsing/new-satellite-phone/intellian-v65-65cm-ku-band-marine-vsat-antenna-system-18964.html)
Beberapa perusahaan VSAT lain menawarkan layanan ku-band sebagai berikut
- UBIQU-PSN [Pasifik Satelit Nusantara](ubiqu.id)
- [Primacom Interbuana](primacom.com)
