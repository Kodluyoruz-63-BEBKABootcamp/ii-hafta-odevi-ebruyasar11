## Ödev 2
### **Yeni bir Github repository oluştururken ekleyebileceğimiz lisanslar nelerdir? Bu lisanlar arasındaki farklar nelerdir?**
**Apache License 2.0:**
- Yazılımın dağıtımı yapılırken kaynak kodun halka açık olmasına gerek yoktur.
- Yazılımda yapılan değişiklikler herhangi bir lisans altında yayınlanabilir.
- Kaynak koda yapılan değişikliklerin belgelendirilmesi gerekir.
- Projede bulunan ticari markalı isimlerin kullanılmasını açıkça yasaklar.

Apache License 2.0 kullanan popüler projeler Android, Apache ve Swift'dir.

**GNU General Public License v3.0:**
- Yazılımda yapılan her değişiklik **aynı lisans** altında yayınlanmalıdır.
- Yazılımın dağıtımı yapılırken kaynak kod herkese açık hale getirilmelidir.
- Kaynak kodda yapılan değişiklikler belgelenmelidir.
- Yazılımın oluşturulmasında patentli materyal kullanılmışsa kullanıcılara onu kullanma hakkı verir. Kullanıcı, patentli materyalin kullanımı nedeniyle herhangi birine dava açarsa yazılımı kullanma hakkını kaybeder.

GPL v2.0'ın GPL v3.0'dan temel farkı patent hibe hükümleridir.

GPL v3.0 kullanan popüler projeler Bash ve GIMP'dir. Ayrıca Linux da GPL v2.0 kullanır.

**MIT License:**
1988 yılında Massachusetts Teknoloji Enstitüsü (MIT) tarafından hazırlanmış, çoğu araştırmaya göre günümüzden en sık kullanılan açık kaynak ve özgür yazılım lisansıdır.

- Yazılımın dağıtımı yapılırken  kaynak kodun halka açık olmasına gerek yoktur.
- Yazılımda yapılan değişiklikler herhangi bir lisans altında yayınlanabilir.
- Kaynak koda yapılan değişikliklerin belgelendirilmesi zorunlu değildir.

MIT kullanan popüler projeler Angular.js, jQuery, Rails, Boostrap vb.

**Berkeley Software Distribution(BSD):**
2-Clause ve 3-Clause olmak üzere iki ana versiyonu vardır. Her ikisi de kullanıcılara Apache License 2.0'dan daha fazla esneklik sunar.

- Yazılımın dağıtımı yapılırken  kaynak kodun halka açık olmasına gerek yoktur.
- Yazılımda yapılan değişiklikler herhangi bir lisans altında yayınlanabilir.
- Kaynak koda yapılan değişikliklerin belgelendirilmesi zorunlu değildir.
- Lisans ve telif hakkı bildirimi, kaynak kodun derlenmiş sürümünün belgelerine dahil edilmelidir.

BSD 3-Clause kullanan popüler projeler Go, Pure.css ve Sentry'dir.
### **Merge-Squash-Rebase arasında farklar nelerdir?**
**Merge Commit:** Branch'deki tüm commitleri tutar ve bunları ana branch'deki commitlerle birleştirir.
![image](https://docs.github.com/assets/images/help/pull_requests/standard-merge-commit-diagram.png)

**Squash and Merge:** Bu metod çekme isteğinizin içindeki commitleri alır ve tek commit olacak şekilde ezer. Merge commit'in aksine belli değişikliklerin ne zaman yapıldığı ve bu ezilmiş commitleri kimin yazdığı hakkındaki bilgiler kaybedilir.
![image](https://docs.github.com/assets/images/help/pull_requests/commit-squashing-diagram.png)

**Rebase and Merge:** Rebase tüm commitleri ana branch'in ucuna taşır. Tek sorun diğer geliştiriciler hala orjinali ile çalışıyorken rebase and merge işleminden sonra Git, ana dalın geçmişinin diğerlerinden farklı olduğunu düşünecektir.
![image](https://git.logikum.hu/images/tutorials/merge-rebase/05.svg)
### **Agile-Scrum-Kanban Kavramları**
**Agile (çevik) yöntem**, yazılım geliştirmede kullanılan proje yönetimine özel bir yaklaşımdır. Bu yöntem ekiplerin yazılım geliştirme süreçlerinin öngörülemezliğine cevap vermesine yardımcı olur. Genellikle sprint olarak bilinen artımlı, yinelemeli iş dizilerini kullanır. Agile manifestosu daha iyi bir yazılım geliştirmenin yöntemlerini açıklayan 4 ana madde ve 12 temel ilkeden oluşmaktadır. Ana maddeler şunlardır:

- Bireyler ve etkileşimler, süreçler ve araçlardan;

- Çalışan yazılım, kapsamlı dokümantasyondan;

- Müşteri ile iş birliği, kontrat görüşmesinden;

- Değişikliklere yanıt vermek, bir planı takip etmekten önce gelir.

**Scrum**, Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 3 temel prensip üzerine kurulmuştur. **Şeffaflık**; Projenin ilerleyişi, sorunlar,gelişmeler herkes tarafından görülebilir olmalıdır. **Denetleme**; Projenin ilerleyişi düzenli olarak kontrol edilir. **Uyarlama**; Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.

**Kanban**, çevik yazılım geliştirmeyi uygulamak için kullanılan popüler bir framework'tür. Gerçek zamanlı kapasite iletişimi ve işin tam şeffaflığını gerektirir. Çalışma öğeleri bir kanban panosunda görsel olarak temsil edilir ve ekip üyelerinin her iş parçasının durumunu istedikleri zaman görmelerine olanak tanır.

[Daha fazlası için kaynak](https://medium.com/devopsturkiye/kanban-ile-scrum-39ed01b36f0b)

### **Gang of Four(GOF) Nedir?**
Design Patterns: Elements of Reusable Object-Oriented Software (1994), yazılım tasarım modellerini açıklayan bir yazılım mühendisliği kitabıdır. Kitap, Grady Booch'un önsözüyle Erich Gamma, Richard Helm, Ralph Johnson ve John Vlissides tarafından yazılmıştır. Kitap iki bölüme ayrılmıştır; ilk iki bölüm nesne yönelimli programlamanın yeteneklerini ve tuzaklarını araştırırken kalan bölümler 23 klasik yazılım tasarım modelini açıklamaktadır. Yazarlar genellikle 'Gang of Four' olarak anılırlar.

Tasarım desenleri iki esasa bağlıdır: Tekrar kullanılabilirlik ve esneklik. Yazılan kodlar bu esasa göre yazılmışsa iyi bir yazılım geliştirilmiş denilebilir. Tasarım Desenleri Creational(yaratımsal), Structural(yapısal) ve Behavioral(davranışsal) olmak üzere 3 başlığa ayrılır.

### **Interface ve Abstract Sınıflarının Farkları**
**Abstract class**, ortak özellikleri olan nesneleri bir çatı altında toplamak için kullanılır. Sınıfın önüne “abstract” sözcüğü yazılarak soyutlaştırma işlemi yapılır. Abstract sınıftan kalıtım almak için de “extends” kullanılır. Abstract class üzerinde kullanılan access modifiers: public, static ve final'dır.

Abstract class, is-a ilişkilerinde kullanılır.
- Bir class sadece bir abstract class implement edebilir.
- “new” ile oluşturulamaz.
- Abstract sınıfta metot ve değişkenler tanımlanabilir.

**Interface**'in nesne yönelimli programlamadaki karşılığı metot ve property listesidir. Interfaceler genelde “can-do” ilişkisine göre çalışır.
- Interface içerisinde yalnıza method tanımları bulunur. İçerisine kod parçacığı yazılmaz.
- Interface başka bir interfaceden inherit olabilir.
- “new” ile oluşturulamaz.
- Bir sınıf birden fazla interface implement edebilir.
- Interface içerisine yalnızca boş metot tanımlanabilir.
- Interface içerisinde özellik ve metodlarda erişim belirleyiciler kullanılmaz. Her şey public kabul edilir.

**Abstract vs Interface**

1. Bir sınıf birden fazla interface’i inherit olarak alabilir ama bir sınıfa bir tane abstract class inherit alınabilir.
2. Interface içerisinde boş metodlar tanımlanabilir ama abstract class’larda hem boş metodlar tanımlanabilir hemde içi dolu metodlar tanımlabilir.
3. Abstract classları kullanmak hız açısından avantaj sağlar.
4. Interface de yeni bir metod yazdığımız zaman bu interfaceden implement ettiğimiz tüm classlarda bu metodun içini tek tek doldurmak gerekiyor ancak abstract classlarda durum farklıdır burada bir metod tanımlayıp içini doldurduğumuzda abstract sınıfımızdan türetilmiş bütün sınıflar bu özelliği kazanmış olur.
5. Interfaceler çoklu kalıtımı sağlamaya yardımcı abstract classlar ise çoklu kalıtımı desteklemez.
6. Interface içerisindeki tüm nesnelerin “public” olması gerekirken Abstract classlarda tüm öğelerin “public” olması zorunlu değildir.
7. Interface yapıcı metodlar(constructor) içermez. Abstract class yapıcı metodlar içerebilir.
8. Interface metodlar static olamaz. Abstract class soyut olmayan metodlar static olarak tanımlanabilir.