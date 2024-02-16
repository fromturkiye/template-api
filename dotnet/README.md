
# .NET Core API Projesi :loudspeaker:

Bu proje, .NET Core kullanılarak oluşturulmuş RESTful bir API örneğidir. Modern web uygulamaları ve servis mimarileri için temel oluşturmayı amaçlar.

### Teknolojiler :bulb:
:star: Orm: EF
:star: Auth: JWT
:star: Infra: Vertical Slice
:star: DB: PostgreSQL
:star: Cache: Redis
:star: Validation: FluentValidation
:star: DI Helper: Carter
:star: CQRS: MediaTR

### Önkoşullar :paperclip:

Projeyi çalıştırmak için aşağıdakilere ihtiyacınız var:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- Bir metin editörü veya [Visual Studio](https://visualstudio.microsoft.com)
- [Docker](https://www.docker.com/products/docker-desktop/)
- [PostgreSQL IDE](https://www.pgadmin.org/)
- [Redis IDE](https://goanother.com/)
- [EF Cli](https://learn.microsoft.com/en-us/ef/core/cli/dotnet)

### Docker Kurulumları :whale:
- postgreSQL:
- redis:

### Kurulum :bomb:

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

### Projeyi Docker'da Çalıştırma :whale:
- build:
- run:

### Kullanım :skull:

Bu bölüm, API'nin temel kullanım örneklerini içerir.

Örneğin, bir GET isteği:

```bash
curl -X GET "http://localhost:5000/api/values" -H "accept: */*"
```


### API Dokümantasyonu :thought_balloon:

API dokümantasyonu için [Swagger](https://swagger.io) kullanılmıştır. Dokümantasyona erişmek için tarayıcınızda `http://localhost:5000/swagger` adresini ziyaret edin.

### Testler :hankey:

Proje, birim testleri içerir. Testleri çalıştırmak için:

```bash
dotnet test
```

## Katkıda Bulunma :fire:

Projeye katkıda bulunmak isteyenler için yönergeler.

1. Fork'layın
2. Feature branch'i oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing-feature'`)
4. Branch'inize Push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## Lisans :page_facing_up:

Bu proje MIT Lisansı altında lisanslanmıştır - daha fazla detay için [LICENSE.md](https://github.com/fromturkiye/template-api/blob/master/LICENSE) dosyasına bakın.

## Teşekkürler :pray:
- Tüm katkıda bulunanlara teşekkürler

Projeyi incelediğiniz için teşekkürler! Sorularınız veya önerileriniz varsa, lütfen bir issue açın.
