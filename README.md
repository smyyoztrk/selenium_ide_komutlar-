# selenium_ide_komutlar-

SELENIUM IDE KOMUTLARI
ASSERT
•	Checked : Bu komut, belirtilen checkbox'ın seçili (checked) durumda olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Editable : Bu komut, belirtilen metin giriş alanının düzenlenebilir durumda olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Not checked : Bu komut, belirtilen checkbox'ın seçili (checked) olmamasını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Not editable : Bir web sayfasındaki bir metin giriş alanının düzenlenemez (non-editable) olduğunu doğrulamak için kullanılır. Bu komut, belirtilen metin giriş alanının düzenlenemez durumda olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Not present : Belirtilen bir HTML öğesinin sayfa üzerinde bulunmamasını doğrulamak için kullanılır. Bu komut, belirtilen öğenin sayfada var olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Not selected value : Bir açılır kutu (dropdown) öğesinin belirli bir değere sahip olmadığını doğrulamak için kullanılır. Bu komut, belirtilen dropdown öğesinin seçili değere sahip olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Not text : Bir öğenin belirli bir metin içermediğini doğrulamak için kullanılır.
•	Present : Belirtilen bir HTML öğesinin sayfa üzerinde bulunup bulunmadığını doğrulamak için kullanılır. Bu komut, belirtilen öğenin sayfada var olup olmadığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Selected label : Bir dropdown (açılır kutu) öğesinde belirli bir değerin seçili olduğunu doğrulamak için kullanılır. Bu komut, belirtilen dropdown öğesinin seçili olan değeri kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Selected value : Bir dropdown (açılır kutu) öğesinde belirli bir değerin (value) seçili olduğunu doğrulamak için kullanılır. Bu komut, belirtilen dropdown öğesinin seçili olan değeri kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Assert text : Bir HTML öğesinin içeriğinin belirli bir metni içerip içermediğini doğrulamak için kullanılır. Bu komut, belirtilen HTML öğesinin metin içeriğini kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Assert title : Bir web sayfasının başlığının (title) belirli bir metni içerip içermediğini doğrulamak için kullanılır. Bu komut, sayfanın başlığını kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
•	Assert value : Bir HTML form öğesinin değerinin belirli bir metni içerip içermediğini doğrulamak için kullanılır. Bu komut, belirtilen form öğesinin değerini kontrol eder ve doğrulama başarılıysa devam eder, aksi takdirde bir hata mesajı alırsınız.
 VERIFY : Assert ile benzer komutlara sahiptir; ancak, verify’de doğrulama başarısız olsa bile testin devam etmesine izin verir. Bu sayede, bir hata durumunda bile testin geri kalan kısmının çalışmasına olanak tanır ve testin tamamlanmasını sağlar. 

STORE 
•	Text : web sayfasındaki bir HTML öğesinin metin içeriğini alarak bir değişken içinde saklar (store) ve daha sonra bu değeri kullanmak üzere bir değişkene atar.
•	Title : web sayfasının başlığını (title) alarak bir değişken içinde saklar (store) ve daha sonra bu değeri kullanmak üzere bir değişkene atar.
•	Value : Bir HTML form öğesinin değerini alarak bir değişken içinde saklar (store) ve daha sonra bu değeri kullanmak üzere bir değişkene atar.

WAİT FOR
•	Editable : Bu komut, bir metin giriş alanının etkileşimli hale gelmesini bekler ve ardından testin devam etmesine izin verir.
•	Not editable : Bu komut, belirtilen metin giriş alanının düzenlenemez hale gelmesini bekler ve ardından testin devam etmesine izin verir. "waitForNotEditable" komutu, özellikle dinamik web sayfalarında veya bir önceki işlemin tamamlanmasını beklerken testin stabil ve güvenilir olmasına yardımcı olabilir.
•	Not present : Bir HTML öğesinin sayfa üzerinde bulunmamasını bekler. Bu komut, belirtilen öğenin sayfada var olmamasını bekler ve ardından testin devam etmesine izin verir.
•	Not visible : Bir HTML öğesinin sayfa üzerinde görünmez olmasını bekler. Bu komut, belirtilen öğenin sayfada görünmez hale gelmesini bekler ve ardından testin devam etmesine izin verir.
•	Present : Bir HTML öğesinin sayfa üzerinde bulunmasını bekler. Bu komut, belirtilen öğenin sayfada görünür olmasını bekler ve ardından testin devam etmesine izin verir.
•	Visible : Bir HTML öğesinin sayfa üzerinde görünür hale gelmesini bekler. Bu komut, belirtilen öğenin sayfada görünür hale gelmesini bekler ve ardından testin devam etmesine izin verir.
•	Text : Bir HTML öğesinin belirli bir metni içerir hale gelmesini bekler. Bu komut, belirtilen öğenin sayfa üzerinde belirli bir metni içerir hale gelmesini bekler ve ardından testin devam etmesine izin verir.
