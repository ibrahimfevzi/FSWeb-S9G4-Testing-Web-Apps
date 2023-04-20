Test Senaryoları

1- iletişim formu hatasız yükleniyorsa.
2- başlıkta h1 elemanı bulunuyorsa. 2 tane assert ekleyin, eğer header dökümanda bulunuyorsa, başlık doğru test içeriğine sahipse.
3- kullanıcı Ad bölümüne 5 karakterden az bir şey yazarsa bileşen 1 hata mesajı içeriyorsa. async/await ve state değişimini gözlemlemek için doğru girdileri kullandığınıza emin olun.
4- kullanıcı hiçbir inputu doldurmadıysa ÜÇ hata mesajı render edildiğinde.
5- kullanıcı email bölümünü doldurmadığında bileşen BİR hata mesajı render ettiğinde.
6- eğer kullanıcı geçersiz bir mail girerse "email geçerli bir email adresi olmalıdır." hata mesajı render edildiğinde.
7- form soyad girilmeden gönderilirse "soyad gereklidir." hata mesajı render edildiğinde.
8- mesaj inputu girilmediğinde ama ad,soyad ve email geçerli değerlerle form gönderildiğinde hata mesajı gösterilmiyorsa.
9- kullanıcı tüm inputları geçerli bir şekilde doldurup gönderdiğinde tüm değerler görüntüleniyor.
