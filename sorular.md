Araştırma Soruları
Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için GitHub docs'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

Git nedir?
Cevap: Git, dağıtık bir sürüm kontrol sistemi (VCS) olarak bilinen açık kaynaklı bir yazılımdır. Sürüm kontrol sistemi, bir projenin kaynak kodu ve dosyalarının değişikliklerinin takip edilmesini ve yönetilmesini sağlar. Git, özellikle yazılım geliştirme projelerinde kullanılan bir araçtır, ancak diğer proje türleri için de kullanılabilir.

Git ile GitHub arasında ne fark var?
Cevap: Git bir sürüm kontrol sistemi olarak çalışırken, GitHub bir Git depolama hizmetidir ve Git projeleri GitHub üzerinde yönetmek için kullanılabilir.

Neden bir branch oluşturuyoruz?
Cevap: Git deposunda branch oluşturmak, mevcut kaynak kodunun veya dosyalarının bir kopyasını oluşturmak ve bu kopya üzerinde değişiklikler yapmak içindir. 

Pull Request'in amacı nedir?
Cevap: önerilen değişikliklerin doğru ve tutarlı bir şekilde ana branch'e eklenmesini sağlamaktır.

Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
Cevap: git checkout

git fetch, git merge ve git pull arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Cevap:
Git Fetch: Bu komut, uzak bir depodan güncelleme bilgilerini yerel depoya indirir. Ancak, yerel dosyalar üzerinde herhangi bir değişiklik yapmaz veya birleştirme işlemi yapmaz. Yani, Git Fetch, yerel depodaki dosyaları değiştirmez, sadece uzak depoda mevcut olan son güncelleme bilgilerini yerel depoya getirir.
Git Merge: Bu komut, bir branch'in başka bir branch ile birleştirilmesi için kullanılır. Yani, farklı iki branch'teki değişikliklerin birleştirilmesini sağlar. Bu komut, yerel dosyalar üzerinde değişiklik yapar ve birleştirme sonucunu kaydeder.
Git Pull: Bu komut, uzak depodaki güncellemeleri indirir ve yerel depo ile birleştirir. Bu, Git Fetch ve Git Merge komutlarının birleşimidir. Yani, Git Pull, uzak depodaki son güncellemeleri indirir, yerel depoya getirir ve ardından bu güncellemeleri yerel branch'le birleştirir.

Merge conflict nedir?
Git'in birleştirme işlemi sırasında karşılaştığı bir sorundur. Bu sorun, iki veya daha fazla branch'in aynı dosyayı değiştirmesi ve birleştirme işleminin bu değişiklikleri nasıl birleştireceğine karar verememesi durumunda ortaya çıkar.

Merge conflict'i nasıl çözeriz?
Merge conflict, birleştirme işlemi sırasında Git tarafından otomatik olarak tespit edilir ve kullanıcılara, birleştirme işleminin nasıl tamamlanacağına karar vermeleri için yardımcı olacak mesajlar verilir. Kullanıcılar, çakışan değişiklikleri düzenleyebilir, belirli değişiklikleri veya tüm değişiklikleri kabul edebilir veya reddedebilir. Sonrasında, birleştirme işlemi tamamlanabilir ve birleştirilmiş dosya kullanılabilir hale gelir.