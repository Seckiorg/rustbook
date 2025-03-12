# Rust Programlama Dili

[Rust Programlama Dili](title-page.md)
[Ön söz](foreword.md)
[Tanıtım](ch00-00-introduction.md)

## Başlangıç

- [Başlarken](ch01-00-getting-started.md)
    - [Kurulum](ch01-01-installation.md)
    - [Merhaba, Dünya!](ch01-02-hello-world.md)
    - [Merhaba, Cargo!](ch01-03-hello-cargo.md)

- [Öngörme Oyunu Programlayalım](ch02-00-guessing-game-tutorial.md) # Öngörü

- [Yaygın Programlama Kavramları](ch03-00-common-programming-concepts.md)
    - [Değişkenler ve Değişebilirlik](ch03-01-variables-and-mutability.md)
    - [Veri Türleri](ch03-02-data-types.md)
    - [İşlevler (Fonksiyonlar)](ch03-03-how-functions-work.md)
    - [Yorumlar](ch03-04-comments.md)
    - [Denetim akışı](ch03-05-control-flow.md)

- [İyeliği kavramak](ch04-00-understanding-ownership.md)
    - [İyelik nedir](ch04-01-what-is-ownership.md)
    - [Başvuru ve Ödünç İşleyişi](ch04-02-references-and-borrowing.md)
    - [Dilim türü](ch04-03-slices.md)

- [İlişkili Verileri Biçimlendirmek için Yapıları Kullanma](ch05-00-structs.md)
    - [Yapıları Tanımlama ve Örnekleme](ch05-01-defining-structs.md)
    - [Yapıları Kullanan Örnek bir Program](ch05-02-example-structs.md)
    - [Yöntem (Metot) Söz Dizimi](ch05-03-method-syntax.md)

- [Sayımlar ve Örüntü Eşleme](ch06-00-enums.md)
    - [Sayım Tanımlama](ch06-01-defining-an-enum.md)
    - [`match` Denetim Akışı Yapısı](ch06-02-match.md)
    - [`if let` ile Kısa Denetim Akışı Yapısı](ch06-03-if-let.md)

## Temel Rust Okuryazarlığı

- [Paketler, Kasalar ve Birimler (Modül) ile Büyüyen Tasarılarımızı Yönetme](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)
    - [Paketler ve Kasalar](ch07-01-packages-and-crates.md)
    - [Kapsam ve Gizliliği Denetlemek için Birimlerin Tanımlanması](ch07-02-defining-modules-to-control-scope-and-privacy.md)
    - [Birim (Modül) Ağacında Ögeye Başvurma Yolları](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
    - [`use` ile Yolları Kapsama Almak](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
    - [Birimleri (Modülleri) Ayrı Dosyalara Ayırma](ch07-05-separating-modules-into-different-files.md) # Birim?

- [Yaygın Derlemler](ch08-00-common-collections.md)
    - [Yöneylerle (Vektörler) Değer Dizelgelerini Saklama](ch08-01-vectors.md) # yöney
    - [UTF-8 ile Kodlanmış Metni Dizgilerle Saklama](ch08-02-strings.md)
    - [Karma Eşlemelerde (HashMap) İlişkili Açkı-Değer Eşleri Saklama](ch08-03-hash-maps.md) # (key-value pair)

- [Yanlışlık (hata) İşleme](ch09-00-error-handling.md)
    - [`panic!` ile Kurtarılamaz Yanlışlıklar](ch09-01-unrecoverable-errors-with-panic.md)
    - [`Result` ile Kurtarılabilir Yanlışlıklar](ch09-02-recoverable-errors-with-result.md)
    - [`panic!`lemek ya da `panic!`lememek](ch09-03-to-panic-or-not-to-panic.md)

- [Genel Türler, Nitelikler (Trait) ve Yaşam Süreleri](ch10-00-generics.md)
    - [Genel Veri Türleri](ch10-01-syntax.md)
    - [Nitelikler: Paylaşımlı Davranışı Tanımlama](ch10-02-traits.md)
    - [Başvuruları Yaşam Süreleri ile Doğrulama](ch10-03-lifetime-syntax.md) # Başvuruların Geçerliliğini Yaşam Süreleriyle Denetleme

- [Kendiliğinden İşleyen Sınamalar Yazmak](ch11-00-testing.md) # Özdevimli, özişler
    - [Sınamalar Nasıl yazılır](ch11-01-writing-tests.md) # Sınamalar
    - [Sınamaların Nasıl Çalışacağını Denetlemek](ch11-02-running-tests.md)
    - [Sınama Düzeninin Sağlanması](ch11-03-test-organization.md)

- [G/Ç Tasarısı: Komut Satırı Programı Yazmak](ch12-00-an-io-project.md) # cli
    - [Komut Satırı Argümanlarını Üstlenmek](ch12-01-accepting-command-line-arguments.md) # beğımsız değişken?
    - [Dosya Okumak](ch12-02-reading-a-file.md)
    - [Birimselliği (Modülerliği) ve Yanlışlık İşlemeyi iyileştirmek için Yeniden Düzenlemek](ch12-03-improving-error-handling-and-modularity.md)
    - [Sınama Güdümlü Geliştirmeyle Kütüphanenin İşlevselliğini Geliştirmek](ch12-04-testing-the-librarys-functionality.md) # Odaklı?
    - [Ortam Değişkenleriyle Çalışmak](ch12-05-working-with-environment-variables.md)
    - [Yanlışlık İletilerini Ölçünlü Çıktı (StdOut) Yerine Ölçünlü Yanlışlığa (StdErr) Yazmak](ch12-06-writing-to-stderr-instead-of-stdout.md) # yanılgı

## Rustça Düşünmek

- [İşlevsel (Fonksiyonel) Dil Özellikleri: Yineleyiciler ve Kapanışlar](ch13-00-functional-features.md) # kapama, kapatma
    - [Kapanışlar: Ortamlarını yakalayan Adsız İşlevler (Anonim fonksiyonlar)](ch13-01-closures.md)
    - [Yineleyiciler ile Bir Dizi Ögeyi İşleme](ch13-02-iterators.md)
    - [G/Ç Tasarımızı İyileştirme](ch13-03-improving-our-io-project.md)
    - [Başarım Karşılaştırma: Döngülere karşı Yineleyiciler](ch13-04-performance.md)

- [Cargo ve Crates.io Üzerine](ch14-00-more-about-cargo.md)
    - [Yayım Belgileri (Profil) ile Kurgulamayı (Build) Özelleştirme](ch14-01-release-profiles.md) # kurgulama
    - [Crates.io'ya Kasa Yayımlama](ch14-02-publishing-to-crates-io.md)
    - [Cargo Çalışma Alanları](ch14-03-cargo-workspaces.md)
    - [`cargo install` ile Crates.io'dan İkilikler (binary) kurma](ch14-04-installing-binaries.md) # Derlenmişler?
    - [Cargo'yu Özel Komutlarla Genişletmek](ch14-05-extending-cargo.md)

- [Akıllı Göstericiler (Pointers)](ch15-00-smart-pointers.md) # İşaretçi? Gösterge
    - [`Box<T>` Kullanarak Öbekteki Veriyi Gösterme](ch15-01-box.md)
    - [`Deref` Niteliğiyle Akıllı Göstericilere Olağan Başvurular gibi Davranmak](ch15-02-deref.md) # İşleme
    - [`Drop` Niteliğiyle Temizlik Aşamasında Kod Çalıştırmak](ch15-03-drop.md)
    - [`Rc<T>`, Başvuru Sayımlı Akıllı Gösterici](ch15-04-rc.md)
    - [`RefCell<T>` ve  İç Değişebilirlik Örüntüsü](ch15-05-interior-mutability.md) # Yapısı
    - [Başvuru Döngüleri Bellek Sızdırabilir](ch15-06-reference-cycles.md)

- [Korkusuz Eşzamanlılık](ch16-00-concurrency.md)
    - [Kodu Eşzamanlı Çalıştırmak için İş Parçacıklarını Kullanmak](ch16-01-threads.md)
    - [İş Parçacıkları Arasında Veri Aktarmak için İleti Geçirmek](ch16-02-message-passing.md) # İleti Geçirme
    - [Durum Paylaşımlı Eşzamanlılık](ch16-03-shared-state.md)
    - [`Sync` ve `Send` Nitelikleriyle Genişletilebilir Eşzamanlılık](ch16-04-extensible-concurrency-sync-and-send.md) # Uzatılabilir

- [Async and Await](ch17-00-async-await.md)
    - [Futures and the Async Syntax](ch17-01-futures-and-syntax.md)
    - [Concurrency With Async](ch17-02-concurrency-with-async.md)
    - [Working With Any Number of Futures](ch17-03-more-futures.md)
    - [Streams](ch17-04-streams.md)
    - [Digging Into the Traits for Async](ch17-05-traits-for-async.md)
    - [Futures, Tasks, and Threads](ch17-06-futures-tasks-threads.md)

- [Rust'ın Nesne Yönelimli Programlama Özellikleri](ch18-00-oop.md)
    - [Nesne Yönelimli Dillere Özgü Özellikler](ch18-01-what-is-oo.md)
    - [Ayrı Türde Verilere Olanak Tanıyan Nitelik Nesnelerini Kullanma](ch18-02-trait-objects.md)
    - [Nesne Yönelimli Tasarım Örüntüsü Uygulanması](ch18-03-oo-design-patterns.md)

## Advanced Topics

- [Örüntüler ve Eşleme](ch19-00-patterns.md)
    - [Örüntülerin Kullanılabileceği Tüm Yerler](ch19-01-all-the-places-for-patterns.md)
    - [Çürütülebilirlik: Bir Örüntünün Eşleşip Eşleşemeyeceği](ch19-02-refutability.md) # Çürütülebilirlik, Yanlışlanabilirlik
    - [Örüntü Söz Dizimi](ch19-03-pattern-syntax.md)

- [Gelişmiş Özellikler](ch20-00-advanced-features.md)
    - [Güvenliksiz Rust](ch20-01-unsafe-rust.md) # Korunmasız
    - [Gelişmiş Nitelikler](ch20-03-advanced-traits.md)
    - [Gelişmiş Türler](ch20-04-advanced-types.md)
    - [Gelişmiş İşlevler ve Kapanışlar](ch20-05-advanced-functions-and-closures.md)
    - [Makrolar](ch20-06-macros.md)

- [Bitirme Tasarısı: Çoklu İş Parçacıklı Web Sunucusu Yazmak](ch21-00-final-project-a-web-server.md)
    - [Tek İş Parçacıklı Web Sunucusu Yazmak](ch21-01-single-threaded.md)
    - [Tek İş Parçacıklı Sunucumuzu Çoklu İş Parçacıklı Sunucuya Çevirmek](ch21-02-multithreaded.md)
    - [İncelikli Kapatma ve Temizlik Aşaması](ch21-03-graceful-shutdown-and-cleanup.md)

- [Ekler](appendix-00.md)
    - [A - Açkı Sözcükler](appendix-01-keywords.md)
    - [B - İşleçler ve Simgeler](appendix-02-operators.md)
    - [C - Türetilebilir Nitelikler](appendix-03-derivable-traits.md)
    - [D - Kullanışlı Geliştirme Araçları](appendix-04-useful-development-tools.md)
    - [E - Baskılar](appendix-05-editions.md)
    - [F - Kitabın Çevirileri](appendix-06-translation.md)
    - [G - “Gecelik Rust” ve Rust'ın Perde Arkası](appendix-07-nightly-rust.md)

- [Özenli Türkçe](tr-00.md)
    - [Terim ve Kavramlar](tr-01-terminology.md)
    - [Dışlanmış Çeviriler ve Türkçeleştirme](tr-02-left-out.md)