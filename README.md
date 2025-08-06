TodoApp, kullanıcıların yapılacak görevlerini ekleyip takip edebileceği basit ve kullanışlı bir masaüstü uygulamasıdır. Java ile geliştirilmiş bu uygulama, görevleri yerel olarak .json formatında kaydeder ve hatırlatmalar için popup ile birlikte sesli alarm sistemi kullanır.

Özellikler
Görev ekleme, silme ve düzenleme

Görev tarih ve saat belirleme

Zamanı gelen görevler için popup bildirimi ve sesli alarm

Görevleri yukarı ve aşağı taşıma

Uygulama açıldığında güncel görevlere göre otomatik bildirim gösterme

Görevler data.json adlı dosyada saklanır

Kurulum
Gereksinimler
Java 17 veya üzeri

JavaFX kütüphaneleri (OpenJFX ya da Gluon ile uyumlu)

Adımlar
Bu projeyi klonlayın:

bash
Kopyala
Düzenle
git clone https://github.com/kullaniciadi/TodoApp.git
cd TodoApp
Gerekli bağımlılıkları ve JavaFX yapılandırmasını sağlayın.

Projeyi IDE (IntelliJ, NetBeans, VSCode) ile açarak veya komut satırı üzerinden derleyip çalıştırın.

Kullanım
Uygulama açıldığında, daha önce kaydedilmiş görevleri data.json dosyasından yükler. Görev saati gelen kayıtlar için bildirim ekranı ve alarm sesi devreye girer. Yeni görevler ekleyebilir, mevcutları düzenleyebilir veya silebilirsiniz.

Notlar
Uygulama platform bağımsızdır, fakat JavaFX destekli sistemlerde çalıştırılmalıdır.

Android için ayrıca Gluon desteği üzerinden derleme yapılabilir.

