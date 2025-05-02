### Niğde Ömer Halisdemir Üniversitesi Öğrenci Otomasyon Sistemi

Niğde Ömer Halisdemir Üniversitesi Öğrenci Otomasyon Sistemi
Ben Niğde Ömer Halisdemir Üniversitesi öğrenci otomasyon sistemini kendi ellerimle, çizdiğim planlarla, yazdığım kodlarla hayata geçirdim. Bu proje, üniversitenin öğrenci bilgi sistemini modernleştiren, kullanıcı dostu ve esnek bir yapı sunan mini bir yazılım sistemidir. Hem akademik personelin hem de öğrencilerin rahatına rahatlık katacak bir yapı oluşturdum. Projeyi geliştirirken yazılım mühendisliğinin temel ilkelerinden OOP (Nesne Yönelimli Programlama), SOLID prensipleri ve en iyi yazılım geliştirme tekniklerinden faydalandım.

![Ekran görüntüsü 2025-03-31 201451](https://github.com/user-attachments/assets/019cdc8b-8103-49f3-bfe6-27c7af41d463)

#### Projenin Amacı ve Kullanımı

Bu sistem, öğrencilerin ders kayıtlarını, devamsızlık bilgilerini, akademik notlarını ve kişisel bilgilerini güvenli bir şekilde saklayıp yönetebilecekleri bir platform sunuyor. Aynı zamanda akademisyenler de sisteme girerek ders programlarını düzenleyebilir, not girişi yapabilir ve öğrenci bilgilerini güncelleyebilir.

![nohu2](https://github.com/user-attachments/assets/9c3ea85d-d00a-49b6-8df9-e352d38617f0)

![nohu3](https://github.com/user-attachments/assets/f0e646f8-55f3-48bb-8a9d-d9f41831f420)

#### Sistem neler sunuyor?

- Öğrenci kayıt ve güncelleme sistemi

- Akademisyen girişi(admin) ve ders programı yönetimi

- Kullanıcı dostu cafcaflı arayüz

- Yetkilendirme ve kimlik doğrulama mekanizması

- Raporlama ve belge düzenleme (Jasper Reports)

- Dinamik veri tabanı yönetimi ve SQL işlemleri

![Ekran görüntüsü 2025-03-31 200928](https://github.com/user-attachments/assets/5987520f-82e4-4510-b512-1902c876c3e4)

![Ekran görüntüsü 2025-03-31 200857](https://github.com/user-attachments/assets/8ce748c0-2060-461c-a359-256bb769b751)

#### Kullanılan Teknolojiler ve Bileşenler

Projeyi geliştirirken modern teknolojileri bir araya getirerek performanslı ve optimize bir sistem oluşturdum.
<br>
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=flat-square&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-00758F?style=flat-square&logo=sql&logoColor=white)
![JasperReport](https://img.shields.io/badge/JasperReport-FF7900?style=flat-square&logo=jasperreports&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

![Ekran görüntüsü 2025-03-31 201725](https://github.com/user-attachments/assets/ced83e94-9af3-40e4-82f5-89fa78d24c5d)

#### 1. JavaFX (Java 1.8 ile UI Geliştirme)

Kullanıcı arayüzünü JavaFX kullanarak tasarladım. JavaFX, modern ve esnek bir GUI kütüphanesi olduğu için, uygulamamın hem masaüstü hem de web entegrasyonu açısından esnek olmasını sağladı. CSS desteği sayesinde görsel anlamda şık ve profesyonel bir arayüz oluşturdum. Java 1.8 kullanmamın ana nedeni JavaFX, Java 1.8 ile bütünleşik gelmesi ve paket karmaşası yaratmamasıdır. 

![Ekran görüntüsü 2025-03-31 200435](https://github.com/user-attachments/assets/d5d8a67a-aa0f-4f24-8132-43f036178be1)

![Ekran görüntüsü 2025-03-31 200412](https://github.com/user-attachments/assets/39ce632a-e747-42ba-bbbd-b3372f22f08e)

![Ekran görüntüsü 2025-03-31 200242](https://github.com/user-attachments/assets/97b3b892-fb06-4d2f-9cb1-e39d92878a2e)

#### 2. MySQL ve SQL Kullanarak Veritabanı Tasarımı

Verilerin saklanması ve yönetimi için MySQL kullandım. SQL sorgularını optimize ederek, veri tabanı performansını en uygun hale getirdim. İlişkisel veritabanı yapısı oluşturarak account, student gibi tablolarla mantıklı bir veri yapısı kurdum.

#### 3. JDBC (Java Database Connectivity) ile Veritabanı Bağlantısı

Java ile MySQL arasında veri aktarımını sağlamak için JDBC kütüphanesini kullandım. Bu sayede SQL işlemleri Java kodlarına entegre edilerek güvenli ve hızlı bir bağlantı sağlandı. JDBC, yani Java Database Connectivity, Java dilinde veri tabanlarıyla iletişim kurmamızı sağlayan bir teknolojidir. Bu sayede, veritabanlarına bağlanıp, veri çekebilir, veri ekleyebilir ya da verileri güncelleyebiliriz. Biz, bu JDBC’yi kullanarak okul veritabanıyla sürekli iletişim halinde olduk. Mesela, öğrencilerimizin bilgilerini eklerken ya da güncellerken, Java koduyla veritabanımıza bağlanıp gerekli işlemleri yapıyoruz. Kısacası, JDBC, Java’yı veritabanı dünyasıyla buluşturuyor ve böylece verileri yönetmek, sorgulamak ve analiz etmek çok daha kolay hale geliyor. Yani, JDBC’yi kullanarak, her şeyin doğru ve hızlı bir şekilde veritabanında kaydedilmesini sağlıyoruz.

![nohu4](https://github.com/user-attachments/assets/68306866-566d-42af-81b1-959a812c1777)

#### 4. Jasper Reports ile Raporlama Sistemi

Sistemdeki verileri PDF ve Excel formatında raporlayabilmek, yazıcı çıktısı alabilmek için Jasper Reports entegrasyonunu gerçekleştirdim. Akademisyenler ders notlarını, öğrenci bilgilerini ve devamsızlıklarını belge olarak indirebiliyor. Jasper Report, Java uygulamalarında raporlama yapmak için kullandığımız bir araçtır. Yani, diyelim ki okulda öğrencilerin başarılarını ya da genel durumunu göstermek için bir rapor hazırlamak istiyoruz, işte burada Jasper Report devreye giriyor. Bu araç, veritabanındaki bilgileri alıp, onları anlaşılır, düzenli ve profesyonel bir şekilde raporlara dönüştürüyor. Biz de bu raporları hem ekranda hem de yazdırarak kullanabiliyoruz. Bir projede, öğrencilerin başarı durumlarını ya da okulla ilgili çeşitli verileri raporlara döküp, öğretmenlerimize veya yöneticilerimize sunmak için Jasper Report’u kullanmak gerçekten çok pratik oldu. Yani, verileri güzel ve düzenli bir şekilde sunmamıza yardımcı olan müthiş bir araçtır.

![nohu1](https://github.com/user-attachments/assets/e0f64f99-eeab-4231-8aa9-71ba7306c927)

##### Database Şema Oluşturma

```sql
CREATE DATABASE school;
USE school;

-- Kullanıcı (Hesap) Tablosu
CREATE TABLE account (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE,
    image VARCHAR(255) DEFAULT ''
);

-- Öğrenci Tablosu
CREATE TABLE student (
    student_id INT AUTO_INCREMENT PRIMARY KEY,
    surname VARCHAR(50) NOT NULL,
    given VARCHAR(50) NOT NULL,
    gender ENUM('Erkek', 'Kadın') NOT NULL,
    image VARCHAR(255) DEFAULT '',
    current ENUM('Devam ediyor', 'Mezun', 'Ara verdi', '') NOT NULL,
    date TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP
);

-- Örnek Veri Ekleme
INSERT INTO account (username, password, email, image) VALUES
('admin', 'admin', 'huseyinaydin99@gmail.com', 'huso.png'),
('root', 'toor', 'huseyinaydin99@outlook.com', 'huso.png');

INSERT INTO student (surname, given, gender, image, current, date) VALUES
('Eren', 'Ertaş', 'Erkek', 'eren.png', 'Mezun', '2025-03-29'),
('Erol', 'Balcı', 'Erkek', '', 'Ara verdi', '2023-06-15'),
('Hüsnü', 'Apaydın', 'Erkek', '', 'Devam ediyor', '2022-09-10'),
('Ayşe', 'Pınar', 'Kadın', '', 'Mezun', '2022-09-10');

DELIMITER //
CREATE TRIGGER before_insert_student
BEFORE INSERT ON student
FOR EACH ROW
BEGIN
    IF NEW.registration_date IS NULL THEN
        SET NEW.registration_date = CURDATE();
    END IF;
END;
//
DELIMITER ;
```

##### 6. CSS ile Modern Arayüz Tasarımı

Kullanıcı deneyimini geliştirmek için JavaFX'in CSS desteğini kullanarak gradient butonlar, hover efektleri ve özel stil tasarımları oluşturdum. CSS, görsel tasarımı belirlerken bir web sayfasının kullanıcı deneyimi (UX) ve kullanıcı arayüzü (UI) tasarımını doğrudan etkiler. Yazı tiplerinden renk şemalarına, sayfa düzeninden buton animasyonlarına kadar her şey CSS aracılığıyla şekillendirilir. CSS sayesinde, bir web sayfası estetik olarak çekici ve işlevsel hale getirilebilir, kullanıcıların sayfada gezinme deneyimi iyileştirilebilir.

Web tasarımında kullanılan CSS teknikleri, hem masaüstü hem de mobil cihazlar için optimize edilmiş modern siteler yaratmada kritik rol oynar.

![Ekran görüntüsü 2025-03-31 200834](https://github.com/user-attachments/assets/8909a036-36da-40ec-ba24-75380e096b33)

![Ekran görüntüsü 2025-03-31 200813](https://github.com/user-attachments/assets/316db0c8-a8c4-4f66-ae61-3143711eba54)
