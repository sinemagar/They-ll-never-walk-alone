# They-ll-never-walk-alone
# They-ll-never-walk-alone

They’ll never wall alone


Elif Sinem AĞAR-- sinemaar1@gmail.com
Adnan YAĞMUR-- adnan.yagmur.2008@gmail.com
Selman BAŞKAYA-- selmanbaskaya1@gmail.com
Doğukan ÇABADAK-- dogukancabadak@gmail.com

Elif Sinem AĞAR:
Düzce Üniversitesi 2. sınıf Bilgisayar Mühendisliği öğrencisi. Düzce Üniversitesi Mekatek Topluluğu Yazılım ekibinde daha önce Teknofest Robotaksi Binek Otonom yarışmasında görüntü işleme ile levha tanıma ve aracın arayüz tasarımı kısımlarında görev aldı. Ekip lideri, görüntü işleme ve ses ile duygu analizi kısımlarından sorumlu.

Adnan Yağmur:
Düzce Üniversitesi Elektrik Elektronik Mühendisliği bölümü üçüncü sınıf öğrencisi. Düzce Üniversitesi Mekatek Topluluğunda İnsansız Hava Araçları tasarlama ve otonom uçuş görevlerinde yer aldı. Düzce üniversitesi DSC' de aktif üye. Projede, elektronik donanım ve elektronik tasarım görevini üstlenmekte.

Selman BAŞKAYA:
Düzce Üniversitesi Bilgisayar Mühendisliği 3.sınıf öğrencisi. İki ayrı startup ile algoritma mühendisi görevinde çalıştı, çalışmalarından biri koloni robotlar diğeri ise tedarikçi operasyon sistemlerinde makine öğrenmesi üzerine idi. Ekipte mobil, tasarım ve ses ile duygu analizi kısmından sorumlu.

Doğukan ÇABADAK:
Düzce Üniversitesi 2. sınıf Bilgisayar Mühendisliği öğrencisi. Daha önce Realkom firmasını düzenlediği fikir donanım yarışmasında derece aldı. Ekipte donanım ve araştırma görevinde.






Projenin Özeti: 
Hayvan dostlarımızın hayat şartlarını kolaylaştırmayı amaçlayan tasma modelimiz her hayvan için oluşturulan id içerisine Firebase ile oluşturulan veritabanına devamlı olarak sıcaklık ve nabız bilgilerini kayıt edecek. Kullandığımız yapay zeka algoritmaları sayesinde elde edilen görüntü veya sesin analizi ile hayvanın tehlike durumunu gerekli birimlere iletilecek.
Tasarladığımız tasma modeli sistemden aldığı verileri GSM yardımı ile ana bilgisayara yönlendirecek ve dataset eğitimi yapılmış bilgisayarda test edilerek gerekli yorumlamalar yapılacak. Bilindiği üzere her hayvanın acı çekerken çıkardığı ses frekansı vardır. Bu seslerin eğitimi yapıldığından cihazdan bu ses gelirse kameraya bağlanacak ve karışındaki canlıyı tanımlayıp ona göre gerekli birimlere uyarı yollayacaktır. Ek olarak hayvanın devamlı olarak nabız ve sıcaklık durumları kontrol edilebilecektir.

Kullanmayı Hedeflediğimiz Teknolojiler:
•	LabelImg
•	Firebase
•	Google Cloud
•	Jupyter
Kullandığımız Modüller, Kütüphaneler ve Paketler
•	Tensorflow 2.1
•	Anaconda
•	Cuda 11.1
•	CuDNN v8.0.4 for cuda 11.1
•	Keras
•	Mnist (from keras)
•	Numpy
•	Opencv
•	Pandas

Hackathon’da oluşturulmayan Bileşenler:
Kendi oluşturduğumuz dataset ile eğitim yapmayı amaçladık. İlk başta Ubuntu 18.04 de çalışıyorduk bazı güncellemelerden dolayı bazı çakışmalar meydana geldi. Cuda ve cudnn uyuşmazlığı yaşadık ve Windows10 da Anaconda tekrar çalışmaya devam ettik yeni ekte paylaştığımız tensorflow dosyasını eğitime hazır hale getirdik. Ancak buffer ve PythonPath ile alakalı bazı sorunlar nedeni ile eğitim yapamadık, düzgün bir sistemde eğitime hazır dosya oluşturduk. Eğitim yapamadığımız için bir örnek bir görüntü tanıma elde edemedik.
Ses ile duygu analizi kısmında örnek olarak bir hayvanın acı sesini tespit edip hayvanın acı çektiği sonucuna varan bir eğitim yapma durumu düşüncesindeydik ama teknik bilgi yetersizliği nedeni ile gerçekleştirmedik.

Hedeflerimiz: 
İlerleyen süreçlerde paketlerle alakalı sorunları çözüp verimli bir eğitim yapmayı hedeflemekteyiz. Ses frekanslarını çözümleyip ses ile duygu analizi yapmayı hedeflemekteyiz.

Bu proje üzerinde daha önce bir çalışma yapılmamıştır. Yapılan çalışmaların hepsi Hackathon sürecinde ekip arkadaşlarımızla birlikte yapılmıştır.
