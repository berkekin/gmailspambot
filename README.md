# gmailspambot
selenium kullanarak gmail hesabı ile hedef mail adresine e postalar gönderir spam bot kodudur. 20.08.2023 güncellenmiştir beta versiyondadır sorun öneri için lütfen iletişime geçin
bunları yapmanız gerek! (Pycharm kullanmanızı şiddetle öneriyorum):

Python Kurulumu: Eğer bilgisayarınızda Python kurulu değilse, Python'ın resmi web sitesinden indirip kurun.

Selenium Kütüphanesinin Kurulumu: Python kurulumunu tamamladıktan sonra, komut satırını veya terminali açın ve aşağıdaki komutu çalıştırarak Selenium kütüphanesini kurun:

ChromeDriver İndirme: Selenium, Chrome tarayıcısını kontrol etmek için bir "driver" gerektirir. Bu driver, Chrome sürümünüze uygun olmalıdır. ChromeDriver'ı resmi sayfasından indirebilirsiniz. İndirdiğiniz chromedriver.exe dosyasını bilgisayarınızda kolayca erişebileceğiniz bir yere kaydedin.

Kodun Hazırlığı:

Kodda belirtilen YOUR_GMAIL@gmail.com ve YOUR_PASSWORD kısımlarını kendi Gmail bilgilerinizle değiştirin.
hedef_email@domain.com kısmını e-posta göndermek istediğiniz adresle değiştirin.
Eğer chromedriver.exe dosyasını farklı bir konuma kaydettiyseniz, kodda bu konumu belirtmelisiniz. Ancak bu kodda doğrudan webdriver.Chrome() kullanıldığı için bu adımı atlayabilirsiniz, çünkü ChromeDriver otomatik olarak PATH'ten alınacaktır.
Güvenlik Uyarısı: Gmail hesabınızın şifresini kodda doğrudan yazmak güvenli değildir. Bu nedenle, bu kodu gerçek bir uygulamada kullanırken daha güvenli yöntemler (örn. gizli anahtarlar veya ortam değişkenleri) kullanarak şifrenizi saklamanız önerilir.

Gmail Ayarları: Gmail, daha az güvenli uygulamaların e-posta hesabınıza erişmesini engelleyebilir. Bu nedenle, bu kodun çalışması için Gmail hesabınızda "Daha az güvenli uygulama erişimine izin ver" seçeneğini etkinleştirmeniz gerekebilir. Ancak bu, hesabınızın güvenliğini azaltabilir, bu nedenle bu ayarı sadece ne yaptığınızdan emin olduğunuzda değiştirin.
