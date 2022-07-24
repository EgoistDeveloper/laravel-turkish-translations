## Laravel 9.x Türkçe dil dosyaları

> "[Laravel Türkiye](http://laravel.gen.tr/)" tarafından Laravel 8.* sürümleri için tercüme edilen ve geliştirilen Laravel Türkçe dil dosyalarıdır.


### Dil dosyası kurulumu

#### Dosyaların kopyalanması

`tr/` dizinini `/lang/` dizini içerisine kopyalayınız, sonuç olarak `/lang/tr/` şeklinde olacaktır.

⚠️ laravel 9.x sürümlerinede çeviriler `/resources/lang` klasörü altında tutulurken artık `/lang` klasörü altında yer alıyor.

`tr.json` dosyasını `/lang/` dizini içerisine kopyalayınız, sonuç olarak `/resources/lang/tr.json` şeklinde olacaktır.

#### Laravel yazılımını Türkçe dilde kullanma

`config/app.php` dosyasındaki, `locale` kısmındaki `en` ifadesini `tr` olarak değiştiriniz. Sonuç aşağıdaki gibi olacaktır:

```php
// 'locale' => 'en',
'locale' => 'tr',
```

⚠️ Bu çeviriler çevirisi mümükün olan alanları kapsar. Uygulamanın tamamını ve paketleri etkilemez.

### Lisans

Açık kaynaklı olan bu proje [MIT lisansı][mit-url] ile lisanslanmıştır.

[mit-url]: http://opensource.org/licenses/MIT
