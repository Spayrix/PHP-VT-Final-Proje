
## Hedef Kitle Analizi Ve Pazarlama

Laravel ve Mysql kullanılarak geliştirdiğim bir hedef kitle analizi ve pazarlama projesidir.(Proje yarım kalmıştır)
Bu proje farklı ürünlere ilgi duyan hedef kitlenin analiz edildiği ve ona göre kullanıcıya ürünün pazarlandığı, kupon bilgilerinin bildirim olarak gönderildiği bir satış sistemidir.

- Profil Bilgileri bulunur.
- Kullanıcı girdiği bilgilere göre (yaş,cinsiyet,vs.) ürünü pazarlamayı hedefler.
- Kullanıcı aldığı ürünün(ör : parfüm) kullanım süresinin geçmesi üzerine, kullanıcıya kupon veya bildirim gönderir.
- Sepete eklenen ürünün alınmaması fakat sepette durması üzerine kulllanıcıya bildirim gönderir.
- Bu proje hem hedef kitleyi hem de satıcıyı memnun etmek üzerine kurulmuş ; bu sebeple kullanıcıların siteye ilgi duyması sağlanmaya çalışılmış satıcının da daha fazla ürün satması amaçlanmıştır.


## Projede Kullanılan Gereksinimler:
- Composer version 2.7.9
- PHP 8.2.4
- PHP tabanlı web projeleri geliştirmek için yaygın olarak kullanılan bir yerel sunucu çözümü. (Xampp veya tercihen başka bir uygulama)

## Kurulum
1. Cmd'den kurmak istediğiniz klasör yolunu belirtip depoyu klonlayın 
git clone https://github.com/Spayrix/ip-2.git
2. .env dosyanızı ayarlayın
3. Gerekli paketleri yükleyin
composer install
npm install
4. Projede kullanılacak benzersiz anahtarınızı üretin
php artisan key:generate
5. Proje için gerekli paketleri çalıştırın
npm run dev
6. Sanal sunucunuzu yarattıktan sonra şu kodu konsolunuzda şu kodu yazın
php artisan serve
7. Daha sonra açılan server http kodunuza tıklayıp tarayıcınızdan siteyi açın.

### Projede Kullanılan teknolojiler (Kullanılan diller, kütüphaneler ve araçlar.)
- Node.js
- Php laravel
- MySQL


## Projede kullandığım uygulamalar
- Jetbrains : PhpStorm
- Jetbrains : Datagrip

---------------------------------------------------------------------------------------------------------------------
## Target Audience Analysis and Marketing

This is a target audience analysis and marketing project developed using Laravel and MySQL. *(The project is incomplete)*  
The project analyzes the target audience interested in different products and markets products to users accordingly, while sending coupon information as notifications in a sales system.

### Features
- Includes profile information.
- Targets marketing based on user-provided information (e.g., age, gender, etc.).
- Sends coupons or notifications to users when the usage period of a purchased product (e.g., perfume) expires.
- Sends notifications to users if a product is left in the cart without being purchased.
- The project aims to satisfy both the target audience and sellers. It is designed to attract users to the platform while helping sellers increase their sales.

---

## Project Requirements:
- Composer version 2.7.9
- PHP 8.2.4
- A local server solution widely used for PHP-based web projects (XAMPP or another preferred application).

---

## Installation
1. Specify the folder path where you want to install the project using the command line and clone the repository:
   git clone https://github.com/Spayrix/ip-2.git
2. Set up your .env file.
3. Install the required dependencies
composer install  
npm install
4. Generate a unique application key
php artisan key:generate
5. Run the necessary packages for the project
npm run dev
6. After creating the virtual server, start the application with the following command
php artisan serve
7. Open the generated server HTTP link in your browser to access the site

## Technologies Used (Languages, Libraries, and Tools)
- Node.js
- PHP Laravel
- MySQL

## Tools Used in the Project
- JetBrains: PhpStorm
- JetBrains: DataGrip

 
   


