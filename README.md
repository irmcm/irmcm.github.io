# irmcm.github.io

Sayfayı ilk açtığımızda bizi arka plan resimli, 2 reklamlı transparan bir form ekranı karşılıyor. 

Menü seçenekleri ve reklamlar bizi boş sayfalara yönlendiriyor.

Bulunduğumuz sayfa üstteki menü kısmındaki "Home" bölümüne aittir. Home'a bastığınızda sayfanın yenilendiğini göreceksiniz. 

Form kısmında tek satırda iki input olanları class="form-group double-input" olarak tanımladım. Diğerleri ise radio-group dışında "form-group" olarak tanımlandı. İlk başta uyarı mesajları sadece altta çıkacak şekilde basit bir tanımlama yapmıştım ama sonrasında her text type için ayrı ayrı uyarı çıkmasının daha iyi olacağını düşündüm. O sebeple de <small></small> tagleri arasında error message tanımı yaptım. AreaCode için dropdown olmalıydı ama özellikle bir api bağlantısı istememiştiniz. O kısım kafamı karıştırdı, ancak hard coded yapmak istemediğimden 10 tane areacode ile api bağlantısı yaptım. 

Fetch kısımlarında derste yaptığımız örnek üzerinden gittim.

Submit öncesi validationlar için ayrı ayrı her form tanımını kontrol ettim. Boş olmaları durumda üstte tanımladığımız error messageları hepsi için ayrı ayrı olarak tetikleniyor. Email ve telefon numarasında da format kontrolü yapılıyor. Bir sıkıntı yoksa register butonu ile register olunuyor. Bu işlem sonrasında yeni bir sayfaya yönlendiriliyoruz. Bu sayfayı da önceki sayfa şeklinde yaptım, yalnızca onay mesajı bulunuyor. Bu sayfada menüdeki "Home" tuşuna basıldığında tekrardan forma ulaşabiliyoruz. 

Ayrıca iyi yapılandırılmış bir stil tanımlaması yapmak adına detaylıca css dosyamı hazırladım. 
