# week-3-homework-1
### 1. Bilgisayarda kaç port vardır?
TCP ve UDP için 16 bit ayrılmış olup 2^16'dan toplam 65.536 adet port vardır. 
### 2. 1024 altı olan portlar neden dış dünyaya açılmıyor? 1024 altı portlarin genel adı nedir? (well-known ports)
1024 altı portlar belirli bir uygulama veya hizmet için tanımlanmış portlardır. Güvenlik sebebiyle bu portlar dış 
dünyaya açılmıyorlar. 1024 altı portların genel adı "Well-known ports"dur. Bir diğer adları ise "Privileged ports"dur. 
### 3. 80 portu dışarıya 8080 açılmış neden?
80 Portu internet erişim protokolü olan http için kullanılan bir bağlantı noktasıdır. Bu port üzerinden istemci, 
sunucuya bir istek gönderir ve iki nokta arasında bağlantı sağlanır. Bazı sunucular port 80 yerine port 8080'i 
kullanırlar çünkü 8080 portu üzerinden kolayca önbellekleme yapılabilir ve proxy sunucusunu kullanır. 
### 4. Nginx nedir?
Nginx ,Engine X, açık kaynak kodlu bir web sunucusudur. Temelde hızlı bir mail istemcisi olarak kodlanmış fakat daha 
sonra tüm sunucular için uygun hale getirilmiştir. Özellikle yüksek trafiğe sahip yoğun web siteleri için 
kullanılmaktadır çünkü eş zamanlı çalışma kabiliyeti sayesinde yüksek performans sergiler. Diğer sunuculara kıyasla 
daha az CPU kullanır. Bir çok işletim sistemi üzerinde çalışabilir. Single Thread yapısına sahiptir ve bu özellik 
sayesinde sayfayı tek hamlede yükleyerek sayfa açma hızında ciddi bir artış sağlar. Nginx yoğun trafiği kaldırabildiği 
için yük dengeleyici olarak da kullanılır. Bunun yanında ayrıca ters proxy sunucusu olarak da çalışabilmektedir.
### 5. Devops nedir? Devops yapısını araştırınız. (sonsuzluk işaretli diagramdaki başlıkların araştırılması)
Devops kelimesi Development ve Operations kelimelerinden türemiştir. Bilgi Teknolojileri içerisinde bulunan iki temel 
birim olan Developers ve Operations ekiplerinin bir arada etkili bir iletişim içerisinde beraber çalışmalarını hedefler.
Uygulama geliştirme yaşam döngüsünü yüksek verimlilik ile sonuç üretme odaklı giderek kısaltmayı hedefler. Sürekli yani
continuous Devops yaşam döngüsüne baktığımızda 7 madde sayabiliriz. 
1. Continuous Development - Bu madde döngüdeki plan ve code basamaklarını kapsar. 
2. Continuous Integration - Bu madde ise çalışma kopyasının günlük entegrasyonunu hedefler. 
3. Continuous Testing
4. Continuous Monitoring - Denetleme
5. Continuous Feedback
6. Continuous Deployment - Son ortam olan production servera deploy aşamasıdır. 
7. Continuous Operations
Buradan özetleyecek olursak;
Geliştirilecek olan uygulamanın planlanması, kodlanması, versiyonlanması ve yayınlanması, update edilmesi, test sürecine
geçilmesi, uygulama ortamının oluşturulması ve uygulama denetimini gerçekleştirmek gibi basamakları barındıran yaşam
döngüsünü temsil  eder.

