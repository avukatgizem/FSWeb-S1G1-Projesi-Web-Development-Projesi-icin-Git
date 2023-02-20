## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Versiyon kontrol sistemidir. Projenin her zaman son haline ulaşmamızı ve güncel tutmamızı sağlayan bir araçtır.

2. Git ile GitHub arasında ne fark var?
Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür.

Github ise Git repository'lerin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmak gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerimize erişmelerini ve katkı sağlamalarını isteyebiliriz. Online bir servistir ve offline olarak kullanabilmek mümkün değildir.

3. Neden bir branch oluşturuyoruz? 
Kullanıcının  çalıştığı projenin farklı versiyonlarına erişmesini sağlar

4. Pull Request'in amacı nedir?
Açık bir projede değişiklik yapılmak isteniyorsa, ilgili proje forklanılır, daha sonra ilgili değişiklikler yapılır. Yapılan değişiklikler hala kendi bilgisayarımzdadır. Asıl projeye aktarılması için pull request atılır.


5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
-b

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch:
git merge: herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir
git pull:başkaları Remote Repo’da değişiklikler yapmış olabilir önce değişiklikleri alıp sonrasında kendi değişikliklerimizi yapmamızı sağlar.


7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olması.

8. Merge conflict'i nasıl çözeriz?
Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmeli.
