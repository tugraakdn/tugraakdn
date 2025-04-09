# 1. DevOps'un iş dünyasında ne gibi katkıları var

Gelişen yazılım dünyasında vakit ve kalite en önemli şey haline gelmeye başladığı için yazılan kodun tutarlı, stabil, sorunsuz çalışması ve projenin en kısa sürede bitirilmesi önemsemmektedir devops da tam olarak bu işeyarar büyük şirketlerdeki bir proje geliştiren yazılımcı guruplarının arasındaki bağlantıyı sağlayarak daha verimli, hızlı, sorunsuz proje geliştirme ortamı sağlar devops cular bu yolu
![](https://www.easyredmine.com/EasyRedmine/media/images/articles/p14/f3732/easy-redmine-devops-plugins.jpg?width=1920&height=0&rmode=min&quality=75&token=a7vd96XfaUO%2Bniyr13y7Er0VdEJpUGpsapr6kxMghEo%3D)
Kullandıkları ve geliştirdikleri araçlar sayesinde iş pilanlaması yaparak iş akışını düzenliyip aradaki bağlantıları kurarak iş verimliliğini var olan sorunları var olabilicek potansiyel sorunları ve gereksiz vakit kaybını ortadan kaldırır bu artılar sayesinde işbirliği gelişir, proje hızlıca pazara sunulur, entegrasyonlar yapıp köntürol ederler bu sayede oluşan versiyon çakışmalarını ve oluşabilecek bağlantı sorunlarını minimuma indirir, daha kaliteli projeler yapılabilir, projeyi her aşamasıyla takip edip sürdürdükleri için hataları analiz ederler geri bildirimleri alırlar ve bu sayede risk durumunu azaltırlar bu artı sebeplerden kaynaklı büyük yazılım şirketlerinin olmazsa olmazı lardır bence bir nevi middleware görevi görürler. 
## 2. DevOps'un workflow'unda ana komponentler neler 

Devops da iş akışı belirli birleşenlere ayrılır bu birleşenler

- **planlama aşaması :** bu aşamada var olan proje parçalara bölünerek ekiplere aktarır bu sayede her ekip düzenli şekilde görev dağlımı yaparak çalışırlar.

- **geliştirme aşaması :** bur da githup, gitlab, bitbucket gibi araçları kullanarak kodun ekip üyeleri tarafından birleştirme, test edilme, versiyon ayarlarını yapılacağı evredir.

- **sürekli entegrasyon (CI) :** bu aşamada takım üyeleri kendi görevleri olan geliştirmeleri yapark anakod dizinine entegre eder bu sırada versiyon çakışmaları düzenlenir ev gerekli testler yapılır.

- **sürekli dağıtım (CD) :** test edilen ve başarıyla onaydan geçen proje otomatik olarak kullanıcıya sunar bu sayede geliştiricilerin ürütkenliği ve hızını artırır.

- **test ve güvenlik :** bu aşamada otomatik olarak kullanılan uygulamalar tarafından testler yapılarak açıklar saptanmaya çalışılmaktadır.

- **gözlem aşaması :** bu aşamada kodun hızını ve işlevselliğini etkiliyen unsurlar belirlenip müşteri memluniyeti için ekibin hızlıca bu hataları düzeltir.

- **geribilidirim :** bu evrede devops ekipleri geri bildirimleri alarak her bir sürümü değenlendirip iyileştirmeler için raporlar oluştutular.

## 3. DevOps Lifecycle da DevOps fazları neler                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             
![](https://avatars.mds.yandex.net/i?id=fc6d63b4e74a7de47dd8ccfaca72f4246243ac87-8376360-images-thumbs&n=13)

1. Sürekli Gelişim
2. Sürekli Entegrasyon
3. Sürekli Test
4. Sürekli Dağıtım/Sürekli Teslim
5. Sürekli İzleme
6. Sürekli Geri Bildirim
7. Sürekli Operasyonlar


## 4. Trend olan DevOps toolları neler 

**Datadog** : yapayzeka destekli izleme ve analiz sağlıyarak sistem performansını gerçek zamanlı olarak takip etmeyi sağlar.

**Spacerlift** : kullanıcı deneyimine odaklanan moderm bir altyapı dağıtım aracıdır, birden fazla altyapı aracıyla çalışır ve tüm altyapı sağlama yaşam döngüsünü otomatikleştirme mize yardımcı olur.

**Git** : dallanma ve birleştirme gibi güçlü özellikler nedeniyle karmaşık projelerde kesintisiz sürüm yönetimi sağlaması sebebiyle devops da en yaygın kullanılan araçlardandır.

**Githup** : en yaygın kullanılan kod deposu yönetim sistemidir, Geliştiricileri etkinleştirmek için özellik istekleri, görev yönetimi, CI / CD, wiki'ler ve daha pek çok özellik ve işlevle birlikte dağıtılmış sürüm kontrol projelerini yönetmek için kolay bir yol sağlar.

![](https://www.lambdatest.com/blog/wp-content/uploads/2023/05/Integration-Image-3x.png)

## 5. Başarılı bir DevOps süreci neleri kapsar 

başarılı devops süreci bütün yaşam döngüsü aşamalarının minimum zaman ve efor harcayarak projeyi başarıyla tamamlamaktır proje olabilicek en kısa zamanda en az problem le tamamlanır ve geribildirimler düzgün şekilde toplanarak en verimli şekilde raporlanıp gelecek projeler için daha verimli bir ortam geliştirmek için kullanılır.

## 6. Container nedir ve DevOps ile bağı nedir

Konteyner uygulamaları tekbir paket içerisinde hazır şekilde şirket sunucusunda ya da kişisel bilgiseyarda çalıştırmak için kullanılan hafif taşınabilir izole bir nevi sanal bilgiseyardır en popiler şekilde docker ile kullanılır. Devops da konteynırlar ayrılmaz bir ikili gibidir sebebi devopsun amacı büyük projeleri görevdağlımı yaparak ekiplere dağıtıp daha hzılı bir geliştirme ortamı yapmaktır ama her geliştirici aynı işletim sistemini aynı araçları ve aynı kütübaneleri kullanamdığı için geliştiricinin bilgiseyarından başka bi yerde çalışmama gibi uyumsuzluklar ortaya çıktığından kaynaklı çok duyarız benim bilgiseyarımda çalışıyor kelimesini bu kelimenin önüne geçebilmek için devops cular ve geliştiriciler uygun bir geliştirme ortamı (konteynır) oluşturarak orda geliştirme yapıyorlar ve bu ortam sanalda olduğundna kaynaklı fiziksel olarak kod aktarımından, şirket dışı bir yerden projeye ulaşabilmek için ve her geliştirici tarafından aynı ortamda geliştirip aynı hataları ve sonuçları alarak daha stabil bir geliştirme ortamı oluşturmasını sağlar ve bu da pekçok şeyi doğrudan artı yönde etkiliyeceği için devops cular tarafından ayrılmaz bir bütündür.

## 7. DevOps'da sürüm kontrolü neden çok önemlidir 

Sürüm kontrol sistemi(VCS) projenin geçmiş versiyonlarını ellerinde bulundururlar yapılan değişiklikleri kimin ne zaman yaptıklarını görebilirler ve önemli olan bu yapılan değişiklikde eklemede var olan bir sorun fark edildiği zaman en kısa zamanda önceki sürüme geçerek var olan sorunu minimum kullanıcıya yansıtarak var olan hatayı düzelterek yeni sürümü tekrar yayınlayabilirler böyle sorunlar olmaması için genelde git kullanarak bölümlere ayrıp o şekilde geliştirmeler yaparak ana kod da var olabilicek hataların önüne geçerler ve tüm geliştirmeler hatasız şekilde gerçekleştirildiğinde ise yeni sürüm olarak yayınlanır. 

## 8. CI nedir 

Sürekli entegrasyon(CI) geliştiricinini kodun uygulanabildiğini hızlı bir şekilde geri bildirim almak için otomatikleşmiş işlemlerdir kodlar otomatik olarka bir sunucuya aktarılır ve orda birleştirilir bu sayede hatalar testbit edilerek düzenlenir bu projenin daha verimli ilerlemesini ve hataların kamraşılıklaşmadan önce hızlıca testbit edilerek önüne geçilmesini sağlar.

## 9. CD nedir 

Sürekli Teslimat, Sürekli Entegrasyonu bir adım daha ileri götürür. Sadece kod tabanının her zaman konuşlandırılabilir durumda olmasını sağlamakla kalmaz, aynı zamanda kodun herhangi bir zamanda üretime dağıtılabilmesini sağlar. Bu, üretime hazır yapı eserini her zaman kullanılabilir tutarak elde edilir.

## 10. HTTP request type'ları nelerdir

http de farklı istekler vardır get, post, put, delete, patch sık kullanılan request typeları dır

- get genelde sunucudan veri çekerken kullanılır bunun sebebi daha hızlı olmasından ve url içerisinden çekilen datanın bilgileri yazmasından kaynaklanır.

- post metodu get e göre birazdaha yavaştır ama daha güvenliklidir en bariz farkı url de get de olduğu gibi çekilen databilgisi yer almaz sadece konum bilgisi yer alır .

- put metodu servis kaynağındaki veriyi güncellemek için kullanılır.

- delete metodu ile sunucudaki istenilen veriyi silinebilir.

- patch metodu ise kaynağa istenilen değişikliği yapmaya yarar ama genelde bunlar küçük değişikliklerdir.

## 11. DevOps da otomasyonun önemi nedir 

İhtiyaç duyulan iş yükünü otomatik sistemler tarafından yaparak hız ve insan yükü önemli ölçüde azalır aynı zamanda insanların yapabileceği hataların önüne geçilir yeni bu işi öğrenmeye başlayan ya da fiziksel, pisikolojik olarak iyi olamyan bir durumda yaptıkları ve yapabilecekleri potansiyel hataların önüne geçer ve işleri önemli ölçüde hızlandırarak iş akışını daha iyi bir hale getirir.

## 12. Container ve VM arasındaki farklar nelerdir

VM ler (sanal bilgiseyar’lar) bir işletim sistemini taklit ederek daha büyük sistem gücü ihtiyacı duarak birnevi bir bilgiseyar görevi görür daha karmaşık işlemler yapılabilir ve uygulamalar çalıştırılabilir ama konteynırlar ise bir projenin çalıştırılabilmesi, oluştutulabilmesi için kullanılan sanal bir ortam sağlar çok az sistem gereksimine ihtiyaç duyar aynı eşkilde bir işletim sistemini taklit ederek gerekli araçları ve kütübahaneleri barındırarak projeyi çalıştırır.

[image 1](https://www.easyredmine.com/EasyRedmine/media/images/articles/p14/f3732/easy-redmine-devops-plugins.jpg?width=1920&height=0&rmode=min&quality=75&token=a7vd96XfaUO%2Bniyr13y7Er0VdEJpUGpsapr6kxMghEo%3D)

[image 2](https://www.lambdatest.com/blog/wp-content/uploads/2023/05/Integration-Image-3x.png)

[image 3](https://avatars.mds.yandex.net/i?id=fc6d63b4e74a7de47dd8ccfaca72f4246243ac87-8376360-images-thumbs&n=13)

[DevOps'un iş dünyasında ne gibi katkıları var 1](https://www.techrepublic.com/article/devops-benefits/)

[DevOps'un iş dünyasında ne gibi katkıları var 2](https://www.techrepublic.com/article/devops-guide/)

[DevOps'un iş dünyasında ne gibi katkıları var 3](https://medium.com/devopsturkiye/4-devops-nedir-faydalar%C4%B1-nelerdir-ne-t%C3%BCr-ara%C3%A7lar-kullan%C4%B1r-d9efc9094cb3)

[DevOps'un workflow'unda ana komponentler neler 1](https://medium.com/@mert-kilicaslan/devops-nedir-8698bc3c6238)

[DevOps'un workflow'unda ana komponentler neler 2](https://coderspace.io/sozluk/devops/)

[DevOps'un workflow'unda ana komponentler neler 3](https://azure.microsoft.com/tr-tr/resources/cloud-computing-dictionary/what-is-devops)

[DevOps Lifecycle da DevOps fazları neler](https://instatus.com/blog/devops-lifecycle)

[Trend olan DevOps toolları neler 1](https://spacelift.io/blog/devops-tools)

[Trend olan DevOps toolları neler 2](https://medium.com/devopsturkiye/teknolojileri-ile-hayat-kurtaran-32-devops-arac%C4%B1-4eb35b234c88)

[Container nedir ve DevOps ile bağı nedir 1](https://builtin.com/software-engineering-perspectives/containerization)

[Container nedir ve DevOps ile bağı nedir 2](https://www.papertrail.com/solution/tips/what-are-containers-and-containerization-in-devops/)

[Container nedir ve DevOps ile bağı nedir 3](https://www.docker.com/blog/docker-for-devops/)

[Container nedir ve DevOps ile bağı nedir 4](https://www.youtube.com/watch?v=dMJXptcnJoY&t=610s)

[Container nedir ve DevOps ile bağı nedir 5](https://www.youtube.com/watch?v=QupPTc-_6-c)

[DevOps'da sürüm kontrolü neden çok önemlidir 1](https://medium.com/@smitgabani/version-control-source-control-platforms-and-their-role-in-devops-3d115e06a10d)

[DevOps'da sürüm kontrolü neden çok önemlidir 2](https://www.bmc.com/blogs/devops-source-version-control/)

[DevOps'da sürüm kontrolü neden çok önemlidir 3](https://unity.com/topics/what-is-version-control)

[CI nedir 1](https://www.bb.com.tr/blog/yazilim-gelistirme/yazilim-gelistirmenin-temel-taslari-cicd-surecleri#:~:text=S%C3%BCrekli%20Entegrasyon%20(CI)%2C%20geli%C5%9Ftiricilerin,kod%20deposuna%20entegre%20etti%C4%9Fi%20uygulamad%C4%B1r.)

[CI nedir 2](https://www.datamarket.com.tr/sozluk/ci-cd/)

[CD nedir 1](https://spot.io/resources/ci-cd/what-is-ci-cd-continuous-integration-continuous-deployment/)

[CD nedir 2](https://about.gitlab.com/topics/ci-cd/)

[CD nedir 3](https://www.ibm.com/think/topics/ci-cd-pipeline)

[CD nedir 4](https://github.com/resources/articles/devops/ci-cd)

[HTTP request type'ları nelerdir](https://mbilgil0.medium.com/http-metotlar%C4%B1-http-request-methods-90d57d574dfa)

[Container ve VM arasındaki farklar nelerdir](https://aws.amazon.com/tr/compare/the-difference-between-docker-vm/#:~:text=Sanalla%C5%9Ft%C4%B1r%C4%B1lm%C4%B1%C5%9F%20donan%C4%B1m%20da%20dahil%20olmak,%C3%A7al%C4%B1%C5%9Ft%C4%B1ran%20fiziksel%20bir%20makinenin%20%C3%B6yk%C3%BCnmesi.&text=Container%2C%20uygulama%20kodundaki%20i%C5%9Fletim%20sistemi,uygulama%20kodundaki%20donan%C4%B1m%20ayr%C4%B1nt%C4%B1lar%C4%B1n%C4%B1%20soyutlar.&text=Donan%C4%B1m%20ayr%C4%B1nt%C4%B1lar%C4%B1n%C4%B1%20soyutlamak%20ve%20donan%C4%B1m%20kullan%C4%B1m%C4%B1n%C4%B1%20art%C4%B1rmak.)

[Container ve VM arasındaki farklar nelerdir](https://circleci.com/blog/containers-vs-virtual-machines/)

[Container ve VM arasındaki farklar nelerdir](https://www.atlassian.com/microservices/cloud-computing/containers-vs-vms)
