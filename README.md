TR

1. Adım
Projeyi oluşturmak istediğiniz kalsörde arama çubuğuna "cmd" yazın ve açın 

2. Adım
"composer create-project laravel/laravel example-app (İstediğin isimi verebilirsiniz) " 
Komutunu yapıştırın.

3. Adım
cmd ekranında cd example-app  (projenizin adı)
ardından  " code . " komutu ile VsCode ile projeniz açın
 
4. Adım
 " .env " dosyasını bu şekilde güncelleyin

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example-app (projenizin adı)
DB_USERNAME=root
DB_PASSWORD=

5. Adım
Xampp programını çalıştırıp 
"Apache" ve "Mysql"  servislerini çalıştırın.Ardından localhost paneline giderek yeni database oluşturun ve projenizin (.env dosyasında yazan)
ismi yazıp oluşturun.

6. Adım
ctrl + shift+ é tuş kombinasyonu ile terminali açın ve komutu çalıştırın
composer require larave/breeze --dev

7. Adım
Kurulum bittikten sonra komutu çalıştırın
php artisan breeze:install
Çıkan ;
Which Breeze stack would you like to install?
  Blade with Alpine ........................................... blade  
  Livewire (Volt Class API) with Alpine .................... livewire  
  Livewire (Volt Functional API) with Alpine .... livewire-functional  
  React with Inertia .......................................... react  
  Vue with Inertia .............................................. vue  
  API only ...................................................... api  

Bu alanda => "blade" yazın

 Would you like dark mode support? (yes/no) [no]
❯Bu alanda => "no" yazın

  Which testing framework do you prefer? [Pest]
  Pest ............................................................ 0  
  PHPUnit ......................................................... 1  
❯Bu alanda => "0" yazın

8. Adım 
Kurulum bittikten sonra komutu çalıştırın
"php artisan migrate"

9. Adım
Kurulumdan sonra sırasıyla 
"npm install" ve "npm run dev" komutlarını çalıştırın

10. Adım 
ctrl + shift+ é tul kombinasyonu ile terminali açın ve komutu çalıştırın
"php artisan serve"
çıkan bağlantıya "ctrl + click" ile tarayıcıda açın.

Ve Auth sisteminiz artık hazır

-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------

Eng

Step 1
Type "cmd" in the search bar in the folder where you want to create the project and open it

Step 2
Paste the command "composer create-project laravel/laravel example-app (You can give it any name you want) "

Step 3
On the cmd screen, open your project with VsCode using cd example-app (your project name)

Step 4
Update the " .env " file like this

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example-app (your project name)
DB_USERNAME=root
DB_PASSWORD=

Step 5
Run the Xampp program and run the "Apache" and "Mysql" services. Then go to the localhost panel and create a new database and write the name of your project (in the .env file) and create it.

Step 6
Open the terminal with the ctrl + shift + é key combination and run the command
composer require larave/breeze --dev

Step 7
Run the command after the installation is complete
php artisan breeze:install
Results;
Which Breeze stack would you like to install?
Blade with Alpine ............................................ blade
Livewire (Volt Class API) with Alpine .................... livewire
Livewire (Volt Functional API) with Alpine .... livewire-functional
React with Inertia ........................................... react
Vue with Inertia ............................................... vue
API only ...................................................... api

Write => "blade" in this field

Would you like dark mode support? (yes/no) [no]
❯Write => "no" in this field

Which testing framework do you prefer? [Pest]
Pest ............................................................ 0
PHPUnit ........................................................ 1
❯ In this field => write "0"

Step 8
After the installation is complete, run the command
"php artisan migrate"

Step 9
After the installation, run the commands
"npm install" and "npm run dev" respectively

Step 10
Open the terminal with the combination of ctrl + shift + é tul and run the command
"php artisan serve"
Open the resulting link in the browser with "ctrl + click".

And your Auth system is now ready
