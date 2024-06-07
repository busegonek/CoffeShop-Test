# CoffeeShop-.NET-CORE-MVC-Projesi

Bu proje, bir kahve dükkanının çevrimiçi platformunu oluşturmak için ASP.NET Core (MVC) kullanılarak geliştirilmiştir.

## Kullanılan Teknolojiler

Bu proje, aşağıdaki teknolojiler ve araçlar kullanılarak geliştirilmiştir:

- **HTML**: Sayfa yapısının oluşturulması için kullanılmıştır.
- **CSS**: Sayfaların stil ve görünümü için kullanılmıştır.
- **Bootstrap**: Hızlı ve duyarlı tasarım için kullanılmıştır.
- **ASP.NET Core MVC**: Web uygulamasının geliştirilmesi için kullanılmıştır.
- **C#**: Sunucu tarafı kodlama için kullanılmıştır.

## Proje Yapısı

- **Views**: MVC modeli kullanılarak oluşturulan görünümler burada bulunur.
- **Controllers**: Uygulamanın yönlendirme ve iş mantığı kodları burada bulunur.
- **Models**: Veri modellemesi ve iş mantığı kurallarının tanımları burada bulunur.
- **wwwroot**: Statik dosyalar (CSS, JavaScript, görseller vb.) burada bulunur.

## Nasıl Çalıştırılır

1. Projeyi klonlayın veya indirin.
2. Visual Studio veya Visual Studio Code gibi bir IDE ile projeyi açın.
3. Proje dosyalarınızı veya terminalinizi kullanarak projenin kök dizininde bulunan `CoffeeShop.csproj` dosyasını açın.
4. Projeyi derleyin ve çalıştırın.

## Kullanılan Yapılar

Bu proje, aşağıdaki yapılar ve teknikler kullanılarak geliştirilmiştir:

### ViewData

- **Açıklama**: ViewData, bir controller'dan view'e veri aktarmak için kullanılan bir mekanizmadır. ViewData, dinamik olarak oluşturulan bir nesne aracılığıyla anahtar-değer çiftleri kullanarak veri taşır.
- **Kullanımı**: ViewData, Controller içinde bir anahtarla bir değer atanarak doldurulur ve ardından bu değerler View dosyasında ViewData["Anahtar"] şeklinde kullanılabilir.

### Section

- **Açıklama**: Section, bir layout dosyasında belirli bir bölümü tanımlamak ve her bir view dosyasında bu bölümün içeriğini değiştirmek için kullanılır. Bu, layout dosyasının belirli kısımlarını farklı view dosyaları arasında dinamik olarak değiştirmenize olanak sağlar.
- **Kullanımı**: Layout dosyasında @RenderSection("SectionAdı") şeklinde tanımlanır ve view dosyalarında @section SectionAdı { } şeklinde içerik doldurulur.

### PartialView

- **Açıklama**: PartialView, bir view'in bir parçası olan ve tekrar kullanılabilir HTML ve C# kodlarının birleşimidir. Partial view'ler, kod tekrarını önlemek, bakımı kolaylaştırmak ve kodu parçalara bölmek için kullanılır.
- **Kullanımı**: PartialView, View dosyasında @Html.Partial("_PartialViewAdı") veya @await Html.PartialAsync("_PartialViewAdı") şeklinde çağrılarak kullanılır.
