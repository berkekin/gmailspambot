# gmailspambot
EN: This Python code sends emails to a target email address using a Gmail account and Selenium. It's a spam bot and was last updated on August 20, 2023, in beta version. For issues or suggestions, please contact us.

Here's what you need to do (I strongly recommend using PyCharm):

Python Installation: If you don't have Python installed on your computer, download and install it from the official Python website.

Installing the Selenium Library: After installing Python, open your command prompt or terminal and install the Selenium library with the following command:

Downloading ChromeDriver: Selenium requires a "driver" to control the Chrome browser, which must match your Chrome version. You can download ChromeDriver from the official page. Save the chromedriver.exe file in a location easily accessible on your computer.

Preparing the Code:

Replace YOUR_GMAIL@gmail.com and YOUR_PASSWORD with your Gmail credentials in the code.
Replace hedef_email@domain.com with the email address you want to send emails to.
If you saved chromedriver.exe in a different location, specify that location in the code. However, you can skip this step as the code uses webdriver.Chrome(), which will automatically use the ChromeDriver from your PATH.
Security Note: Writing your Gmail password directly in the code is not secure. It's recommended to use more secure methods (e.g., secret keys or environment variables) to store your password when using this code in a real application.

Gmail Settings: Gmail may block access to your email account for less secure apps. To make this code work, you may need to enable "Allow less secure apps" in your Gmail account settings. However, note that this can decrease the security of your account, so only change this setting if you're sure about what you're doing.





TR:selenium kullanarak gmail hesabı ile hedef mail adresine e postalar gönderir spam bot kodudur. 20.08.2023 güncellenmiştir beta versiyondadır sorun öneri için lütfen iletişime geçin
bunları yapmanız gerek! (Pycharm kullanmanızı şiddetle öneriyorum):

(gönderilecek spam mail içeriğini kodda ayarlayabilirsiniz. adet ise 25 varsayılan olarak ayarladım artırmak veya azaltmak isterseniz Pycharm kullanarak yapabilirsiniz)

Python Kurulumu: Eğer bilgisayarınızda Python kurulu değilse, Python'ın resmi web sitesinden indirip kurun.

Selenium Kütüphanesinin Kurulumu: Python kurulumunu tamamladıktan sonra, komut satırını veya terminali açın ve aşağıdaki komutu çalıştırarak Selenium kütüphanesini kurun:

ChromeDriver İndirme: Selenium, Chrome tarayıcısını kontrol etmek için bir "driver" gerektirir. Bu driver, Chrome sürümünüze uygun olmalıdır. ChromeDriver'ı resmi sayfasından indirebilirsiniz. İndirdiğiniz chromedriver.exe dosyasını bilgisayarınızda kolayca erişebileceğiniz bir yere kaydedin.

Kodun Hazırlığı:

Kodda belirtilen YOUR_GMAIL@gmail.com ve YOUR_PASSWORD kısımlarını kendi Gmail bilgilerinizle değiştirin.
hedef_email@domain.com kısmını e-posta göndermek istediğiniz adresle değiştirin.
Eğer chromedriver.exe dosyasını farklı bir konuma kaydettiyseniz, kodda bu konumu belirtmelisiniz. Ancak bu kodda doğrudan webdriver.Chrome() kullanıldığı için bu adımı atlayabilirsiniz, çünkü ChromeDriver otomatik olarak PATH'ten alınacaktır.
Güvenlik Uyarısı: Gmail hesabınızın şifresini kodda doğrudan yazmak güvenli değildir. Bu nedenle, bu kodu gerçek bir uygulamada kullanırken daha güvenli yöntemler (örn. gizli anahtarlar veya ortam değişkenleri) kullanarak şifrenizi saklamanız önerilir.

Gmail Ayarları: Gmail, daha az güvenli uygulamaların e-posta hesabınıza erişmesini engelleyebilir. Bu nedenle, bu kodun çalışması için Gmail hesabınızda "Daha az güvenli uygulama erişimine izin ver" seçeneğini etkinleştirmeniz gerekebilir. Ancak bu, hesabınızın güvenliğini azaltabilir, bu nedenle bu ayarı sadece ne yaptığınızdan emin olduğunuzda değiştirin.
