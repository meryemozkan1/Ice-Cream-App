<h1> Ice-Cream-App</h1>

Bu proje, dondurma çeşitlerinin ve fiyatlarının görüntülenmesini sağlayan bir uygulamadır. Kullanıcılar, mevcut dondurma seçeneklerini görebilir ve her bir dondurmanın fiyatını öğrenebilirler.<br>

<h1> Özellikler </h1>

- Farklı dondurma çeşitlerini listeleme <br>
- Her dondurma çeşidinin fiyatını görüntüleme <br>
- Kullanıcı dostu arayüz <br>
- Dondurma fiyatlarının kolayca güncellenmesi <br>

<h1> Kütüphaneler </h1>

- React <br>
- json-server <br>
- bootstrap <br>
- axios@^0.27.2 <br>
- @testing-library/user-event@14.0 <br>

<h1> Selectors -Seçiciler </h1>

- Test içerisinde jsx elementlerini çagırmaya yarayan methodlar -screen nesnesi aracılığı ile kullanılır <br>

- https://testing-library.com/docs/queries/byrole <br>

<h1> Matchers -Kontrolcüler </h1>

- expect komutu ile birlikte kullanıla ve bir elementin üzerindeki beklentimizi kontrol eden methodlar.(Rengi kırmızıdır |inout tiklenmiştir.| buton aktiftir.|yazı içeriği sudur | fonsiyon çağrılmıştır.| dizinin uzunluğu 5'tir.) <br>

- https://github.com/testing-library/jest-dom
  diğer kontroller <br>
- https://jestjs.io/docs/using-matchers <br>

<h1> Test Geliştirme Süreçleri</h1>
<hr>

<h2>TDD (Test Driven Development)</h2>

- Önce testler yazılır, sonrasında işlevler kodlanır <br>

- red to green <br>

- Artısı, testler bit yük gelmez.Gelistirme sürecinin bir parçası olur. Testleri yazarken dinamik yapının algoritmesini oluşturduğumuz için işlevi daha hızlı kodlarız <br>

<h2>BDD (Behaviour Driven Development)</h2>

- Önce özellik/ işlev geliştirilir daha sonra testleri yazılır. <br>

- 100% test covarage <br>

<h1> FireEvent</h1>
<hr>

- rtl içerisinde gelen olay tetikleme metodu <br>

- Gerçek kullanıcıdan uzak tepkiler verdiği için yerini userEvent'e bıraktı -tetiklenen olaylar gerçek bir insanın tepkisinden çok daha hızlı bir şekilde aniden gerçekleştiği için testlerde tutarsızlıklara ve beklenmedik sonuçlara yol açabiliyor <br>

<h1> UserEvent</h1>
<hr>

- firevent'in modern/gelişmiş versiyonu -tetiklediğimiz olaylar firivent gibi doğrudan tetiklenmesi yerine gerçek bir kullancı simüle ederek belirli bir gecikmenin ardından tetiklenir. -kullanılması için kütüphanenin projeye kurulması gerekir -async çalıştığı için async await ile kullanılır <br>

<h1> Ekran Görüntüsü</h1>

![](images/ice.cream.gif)
