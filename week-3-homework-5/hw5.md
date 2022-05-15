# week-3-homework-5
### 1. Kernel ile Shell farkı
Çekirdek, bilgisayarın işletim sisteminin çekirdeği olarak işlev gören ve sistemdeki her şey üzerinde denetime sahip 
olan bir bilgisayar programıdır. Kabuk, işletim sistemi tarafından sağlanan hizmetlere erişmek için arayüz olarak 
çalışan bir bilgisayar programıdır.
### 2. Docker portainer
Portainer, Docker veya Docker Swarm Cluster’ımızı yönetmemizi sağlayan bir yönetim arayüzüdür. Docker’ı terminalden 
kullanmadan işleri daha hızlı ve kolay yapmayı sağlar. ayrıca containerlara dair monitoring sağlamaktadır.
### 3. Cross origin
Cross-Origin Resource Sharing (Kökenler arası kaynak paylaşımı) anlamına gelen CORS, web tarayıcısı tarafından yönetilen
ve ek HTTP başlıkları kullanılarak, bir kökende çalışan web uygulamasının, farklı bir kökende yer alan web uygulamasına
erişim izni kontrolünü sağlayan mekanizmadır. Web uygulaması, internet tarayıcısı üzerinden farklı bir kökene (protokol,
domain ve port) herhangi bir istek gönderirse cross-origin HTTP isteği oluşturmuş olur.
### 4. Application server: Tomcat, Wildfly, Nginx
Sadece belli bir uygulamanın veya yazılımın çalıştırılması için kullanılan sunuculardır. Bu uygulamalar son kullanıcının
erişerek işlem yaptığı uygulamalar olabileceği gibi son kullanıcıya kapalı, sadece diğer sunucuların farklı bilgilere 
erişmek için kullandığı sunucular da olabilir.
### 5. CVCS - DVCS
Birden fazla kişinin bir proje üzerinde etkin çalışması için ortaya atılmış versiyonlama sistemidir. CVS, SVN birer 
merkezi versiyon kontrol sistemleridir. 
Bu sistemde proje ortak bir respository’de tutulur ve birden fazla geliştirici 
aynı respository üzerinde checkout ve commit işlemlerini gerçekleştirmektedir. Bu yöntemde herkesin projeye katkı 
sağlamasının yanısıra bazı ciddi sorunları vardır. Tek merkezli sunucu 1 saatliğine arızalanması durumunda, kullanıcılar
1 saat boyunca çalışmalarını veya çalıştıkları projenin sürümlenmiş kopyalarını kaydetmeleri mümkün olmayacaktır.
Merkez versiyon sistemlerinin geliştiricilerin offline çalışabilmesi ve respository’nin zarar görmesi durumunda geri 
getirme gibi eksikliklerinden dolayı ortaya atılmış bir versiyon sistemidir. Git, Mercurial, BitKeeper… dağıtık versiyon
sistemleri örnek gösterilebilir. 
Bu sistemlerde merkezi bir respository olmayıp, proje üzerinde çalışan her makine, 
projenin kopyasını kendi yerel bilgisayarında tutmaktadır. Geliştiriciler proje üzerinde değişiklik yapmak veya proje 
geçmişine göz atmak istediklerinde, uzak depo ile iletişime geçmek zorunda değildir. Sunuculardan biri çökerse ve o 
sunucu üzerinde ortak çalışma yürüten sistemler varsa, geliştircilerden birinin projeyi sunucuya geri yükleyerek sistem 
kurtarılabilir. Özet olarak aynı projede farklı geliştiriciler, farklı biçimlerde çalışma yürüterek, farklı iş akışları 
ile çalışabilmeyi sağlar.

