
# .NET Core API Projesi :tw-1f4e2:

Bu proje, .NET Core kullanılarak oluşturulmuş RESTful bir API örneğidir. Modern web uygulamaları ve servis mimarileri için temel oluşturmayı amaçlar.

### Teknolojiler :tw-1f4fb:
:tw-1f31f: Orm: EF
:tw-1f31f: Auth: JWT
:tw-1f31f: Infra: Vertical Slice
:tw-1f31f: DB: PostgreSQL
:tw-1f31f: Cache: Redis
:tw-1f31f: Validation: FluentValidation
:tw-1f31f: DI Helper: Carter
:tw-1f31f: CQRS: MediaTR

### Önkoşullar :tw-1f4ce:

Projeyi çalıştırmak için aşağıdakilere ihtiyacınız var:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- Bir metin editörü veya [Visual Studio](https://visualstudio.microsoft.com)
- [Docker](https://www.docker.com/products/docker-desktop/)
- [PostgreSQL IDE](https://www.pgadmin.org/)
- [Redis IDE](https://goanother.com/)
- [EF Cli](https://learn.microsoft.com/en-us/ef/core/cli/dotnet)

### Docker Kurulumları :tw-1f40b:
- postgreSQL:
- redis:

### Kurulum :tw-1f4a3:

Projeyi lokal makinenize klonlayın:

```bash
git clone https://github.com/fromturkiye/template-api.git
```

dotnet dizinine gidin:

```bash
cd dotnet
```

Gerekli NuGet paketlerini yükleyin:

```bash
dotnet restore
```
-> postgresql ve redis in çalıştığından emin olmalıyız.

Uygulamayı çalıştırın:

```bash
dotnet run
```

### Projeyi Docker'da Çalıştırma :tw-1f40b:
- build:
- run:

### Kullanım :tw-1f47d:

Bu bölüm, API'nin temel kullanım örneklerini içerir.

Örneğin, bir GET isteği:

```bash
curl -X GET "http://localhost:5000/api/values" -H "accept: */*"
```


### API Dokümantasyonu :tw-1f4cb:

API dokümantasyonu için [Swagger](https://swagger.io) kullanılmıştır. Dokümantasyona erişmek için tarayıcınızda `http://localhost:5000/swagger` adresini ziyaret edin.

### Testler :tw-1f4a9:

Proje, birim testleri içerir. Testleri çalıştırmak için:

```bash
dotnet test
```

## Katkıda Bulunma :tw-1f525:

Projeye katkıda bulunmak isteyenler için yönergeler.

1. Fork'layın
2. Feature branch'i oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing-feature'`)
4. Branch'inize Push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## Lisans :tw-1f4dc:

Bu proje MIT Lisansı altında lisanslanmıştır - daha fazla detay için [LICENSE.md](https://github.com/fromturkiye/template-api/blob/master/LICENSE) dosyasına bakın.

## Teşekkürler :tw-1f64f:
- Tüm katkıda bulunanlara teşekkürler

Projeyi incelediğiniz için teşekkürler! Sorularınız veya önerileriniz varsa, lütfen bir issue açın.
