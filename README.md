# JIRA_APP
Atlassian Jira plugin geliştirirken, türkçe kaynak olarak kullanılabilecek bir proje.

## Ön Bilgi
Atlassian Jira Plugin geliştirebilmek için, 
1. giriş seviyesi HTML, 
2. CSS ve JavaScript bilmeniz gerekmektedir, 
3. Jira hakkında bilgi sahibi olmanız önemli :) 
4. Node.JS deneyiminiz olması geliştirme yapmanızı kolaylaştıracaktır.

## Geliştirme Ortamı
1. IDE Editörü kullanmanız geliştirme yapmanızı kolaylaştıracaktır, ben [VSCode](https://code.visualstudio.com/download) tavsiye ederim.
2. PC nize [Node.JS](https://nodejs.org/) kurulumu yapmanız gerekmektedir. Ayrıca Node.js ile birlikte gelen npm'ye de ihtiyacınız var.
3. Yerel geliştirme ortamınızı internete tünellemek için, yani kendi pc nizden yayın yaparak jira da test yapabilmeniz için [ngrok](https://ngrok.com/download) kurmalısınız.
4. [NGROK](https://dashboard.ngrok.com/signup) üyeliğinizi yapın.

## Başlamadan Önce
1. Testlerinizi yapabilmeniz için [buradan](http://go.atlassian.com/cloud-dev) kendinize bir test jira ortamı oluşturun. 
2. [Burada](https://developer.atlassian.com/cloud/jira/platform/getting-started-with-connect/#step-2--enable-development-mode-in-your-site) anlatıldığı gibi geliştirme modunuzu aktifleştirin.
3. Gerekli kütüphaneleri node.js için kurun.
NGROK kurulumu
```
npm install -g ngrok 
```
NGROK tan aldığınız tokeni tanımlayın
```
ngrok authtoken <token>
```

Tebrikler, artık uygulama geliştirmeye başlayabilirsiniz.

Eğer bana soru sormak isterseniz.
#### Berk Emre ALTAN

[LinkedIn](https://www.linkedin.com/in/berkemrealtan/)

berkemrealtan@gmail.com
