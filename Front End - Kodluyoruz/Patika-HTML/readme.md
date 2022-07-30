# Ödev 2

## Google Ana Sayfasını Tasarlamak

```
Hepimiz her gün Google kullanıyoruz ve çok işimize yarıyor değil mi? Her gün Google'da milyonlarca arama yapılıyor ve hatta siz de bu sayfaya gelmek için Google'ı kullanmış olabilirsiniz. Peki Google'ın geçmişten günümüze nasıl geliştiğini hiç merak ettiniz mi?

Google 1996 yılında kuruldu ve ilk versiyonunu 1998 yılında yayınladı. 1998, çok uzun bir süre önce değil mi? İlk versiyonu ile şu anki versiyonu arasında büyük fark var tabii ki. Peki size Google'ın ilk versiyonunu gösterebileceğimizi söylesek ne hissederdiniz?

İnternetteki gelmiş geçmiş bütün web sitelerini görebileceğiniz Wayback Machine adında bir web arşivi bulunmakta. Google 1998 linkinden Google'ın ilk versiyonu nasılmış görebilirsiniz. Oldukça garip öyle değil mi? Garip olmasının yanında bu sizin HTML bölümündeki üçüncü ve son ödeviniz olacak. Bu sayfayı tasarlamanızı istiyoruz.

Bu sayfada şu ana kadar öğrendiğiniz her şeyi kullanabilirsiniz. Bu sizin HTML becerilerinizi oldukça iyi bir şekilde geliştirmenizi sağlayacaktır.
googlehomepage

Butonların çalışmaması hiç sorun değil. Sadece tasarımsal olarak bu görüntüye benzesin ve aşağıdaki linkler çalışıyor olsun yeterli.
Tasarladığınız bölümler ile alakalı kodunuzda açıklama satırlarına yer veriniz.
Sayfa ile alakalı detaylara sayfanın üzerine sağ tıklayıp "İncele/Inspect" diyerek ulaşabilirsiniz.
Bu logo'yu kullanabilirsiniz.
İleride göreceğimiz CSS'den sonra Google'ın bugünkü halini de tasarlayacağız. Ama öncelikle bakalım Larry Page ve Sergey Brin başlangıçta nasıl yapmışlar!

Hepinize başarılar ve kolay gelsin!
```


### Linkler

> <a href="https://app.patika.dev/emrevaljean" target="_blank">Patika Profilim için</a>
> <a href="https://app.patika.dev/emrevaljean" target="_blank">wikipedia</a>
> <a href="https://app.patika.dev/emrevaljean" target="_blank">web.archive.org</a>

<hr>

```
<!-- 
<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ödev 2</title>

    <style>
        .container {
        width: 90%;
        height: 100%;
        margin: 15 px auto;
        padding: 30 px;
        text-align: center;
        }
        .center {
            

            display:block;
            text-align: center;
        }
        div {
            width: 90%;
            border: 0 px;
        }
        img {
            width: 351px;
            aspect-ratio: auto 351px;
            height: 113px;
        }
        table {
            border-collapse: separate;
            text-indent: initial;
            white-space: normal;
            line-height: normal;
            font-weight:normal;
            font-size: normal;
            font-style: normal;
            color: -internal-quirk-inherit;
            border-spacing: 2 px;
            font-variant: normal;
        }
        
    </style>
  </head>
  <body>
    
    <div class="container">
        <div><img src="img/google.jpg" width="351px" alt="Google!">
        </div>
        <div class="center">
          <table style="border: 0 px"; width="90%>
              <tbody>
                  <tr> 
                      <td style="background-color: #EEEEEE" colspan="3"></td>
                          <div style="text-align: center">
                              <span>Search the web using Google!</span>
                          </div>
                  </tr>
              </tbody>
          </table>
          
        </div>
      </div>
    </body>
  </html> 
```