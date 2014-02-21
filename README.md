PHP E-ticaret
============

PHP E-ticaret yazılımı, kolay kullanımlı, açık kaynak kodlu, esnek ve modüler bir e-ticaret paketidir.

##Geliştirme

Geliştirme yaparken önce kurulumu yapınız. http://book.cakephp.org/2.0/en/contributing/cakephp-coding-conventions.html adresindeki kuralları iyice okuyunuz. PHPDoc yorumlarını kesinlikle yazdığınız fonksiyonlarda kullanmalısınız.

### Kurulum

1. Paketi www dizininizin altına kopyalayın.
2. App/tmp dizinine chmod 777 vermelisiniz.
3. DB klasöründeki kullanıcı yönetimini içeren boş veritabanı ile mysql'de bi veritabanı oluşturunuz.
4. Daha sonra, Config/database.default.php dosyasını aynı klasöre database.php olarak kopyalayın ve dosyada  host, kullanıcı adı ve şifreleri değiştiriniz.
5. Kullanıcı yönetimi için www/phpeticaret/authake, kullanıcı adı ve şifre olarak da, admin ve admin giriniz.