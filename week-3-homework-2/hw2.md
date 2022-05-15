# week-3-homework-2
### 1. Statik kod analizi: Sonarqube
Ana branch e merge edilecek bir kodun review edilmeden önce statik kod analizine tabi tutulması kod kalitesi, 
hatasızlık ve review aşamasında zaman kazanmak açısından önemlidir. SonarQube bu ihtiyaca cevap veren hemen Cloud hem de
on-premise olarak kullanılabilen önemli bir tooldur. Bir koddaki bugların bulunması, güvenlik zafiyetlerinin tespit 
edilmesi, kod okunabilirliğini etkileyen code smells düzeltmelerinin yapılması, testlerin kodun ne kadarını kapsadığı, 
tekrar edilen kod bloklarının belirlenmesi gibi konularda SonarQube önemli faydalar sağlamaktadır. Ayrıca CI Pipelineına 
entegre edilerek, SonarQube dan gelecek sonuca göre kodun deploy edilme durumu belirlenebilir.
### 2. Kubernetes yapısı
Container tabanlı işlerin çalıştırılmasını ve yönetilmesini sağlayan açık kaynaklı bir orkestrasyon aracıdır. Mevcut 
konteyner haline getirilmiş uygulamaların otomatik deploy edilmesi, sayılarının arttırılıp azaltılması ve bu 
konteynerların yönetilmesini sağlayan Container Cluster aracıdır.
Kubernetes’in yapısına göz atacak olursak master ve worker denilen nodelardan oluşuyor. Bu worker dediğimiz nodelar 
içerisinde podlar ve podların içerisinde konteynerlarımız bulunmaktadır. Bu yapı kendi içinde overlay dediğimiz bir 
network ile haberleşiyor. 
### 3. Orchestration yapısı
Orchestration kısaca birden fazla konteynırı yönetmek temellidir. Konteynırların nodelar içerisine dağıtılması ve 
yönetilmesi veya cluster yönetilmesidir. Bu sayede, cluster daki tüm nodelar yüksek erişilebilirlik durumunda olur. 
Ayrıca orchestration, tüm clusterı bir bütün olarak yönetme imkanı sağlar. Bu sayede, hem kaynak yönetimi, hem network 
yönetimi kolaylıkla yapılabilir. Orchestration araçlarına örnek olarak, Kubernetes, Fleet, Mesos, Consul, Helios, 
Centurion, Docker swarm verilebilir.
### 4. npm nedir ve niçin kullanılır?
Npm; Node Package Manager ya da Node Packaged Modules olarak bilinmektedir. Java script paket yöneticisidr. Npm temel 
olarak 3. parti yazılımları yüklemeyi sağlayan bir araçtır.
### 5. Agile-Scrum nedir?
Agile modeli proje yönetimi, yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım 
geliştirme modeli taban alınarak geliştirilmiş, sık aralıklarla parça parça yazılım teslimatını ve değişikliği teşvik 
eden bir yazılım geliştirme modeli. Kendi rehberindeki tanımlaması “İnsanların mümkün olan en yüksek değere sahip 
ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir 
çerçeve” olan scrum, agile proje yönetme metodolojilerinden biridir.

