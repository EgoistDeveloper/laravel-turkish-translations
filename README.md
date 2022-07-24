# Laravel 9.x için Türkçe dil dosyaları

> "[Laravel Türkiye](http://laravel.gen.tr/)" tarafından Laravel 8.* sürümleri için tercüme edilen ve geliştirilen Laravel Türkçe dil dosyalarıdır.


## Dil dosyası kurulumu

`tr/` dizinini `/lang/` dizini içerisine kopyalayınız, sonuç olarak `/lang/tr/` şeklinde olacaktır.

⚠️ laravel 9.x sürümlerinede çeviriler `/resources/lang` klasörü altında tutulurken artık `/lang` klasörü altında yer alıyor.

`tr.json` dosyasını `/lang/` dizini içerisine kopyalayınız, sonuç olarak `/resources/lang/tr.json` şeklinde olacaktır.

## Laravel'i Türkçe dilinde kullanma

`config/app.php` dosyasındaki, `locale` kısmındaki `en` ifadesini `tr` olarak değiştiriniz. Sonuç aşağıdaki gibi olacaktır:

```php
// 'locale' => 'en',
'locale' => 'tr',
```

⚠️ Bu çeviriler çevirisi mümükün olan alanları kapsar. Uygulamanın tamamını ve paketleri etkilemez.

## Daha fazla çeviri eklemek için

Github'da [Laravel-Lang](https://github.com/Laravel-Lang) gibi bazı topluluklar farklı alanların çevirileri için birlikte çalışıyor. Daha kapsamlı çeviriler için [lang](https://github.com/Laravel-Lang/lang) paketini ve HTTP durum kodlarının çevirisi için de [
http-statuses](https://github.com/Laravel-Lang/http-statuses) paketini önerebilirim.

## Lisans

Açık kaynaklı olan bu proje [MIT lisansı][mit-url] ile lisanslanmıştır.

[mit-url]: http://opensource.org/licenses/MIT
