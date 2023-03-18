<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://cdn.cdnlogo.com/logos/t/34/tailwind-css.svg" width="400" alt="Laravel Logo"></a></p>

# Project Overview
Static Website for Cloud Computing Club Competition Regional DKI Jakarta

Project Link : <a href="https://itclub.my.id" target="_blank">https://itclub.my.id</a>

Technology :
- [TailwindCSS](https://tailwindcss.com/).
- [AOS](https://michalsnik.github.io/aos/).

Wireframe : https://whimsical.com/it-club-69-A2VtcXFe2VDtDADSfwYVoh (Password : 12345678)

## Step by step installation
#### 1. Clone this repository
```
git clone https://github.com/0x1m4o/Industry-Project.git
```
or 
#### Download the zip file
![download zip](https://github.com/0x1m4o/Industry-Project/blob/main/public/img/image.png)

#### 2. Go to directory 
```
cd Industry-Project
```

#### 3. Install dependency with composer and npm
```
composer install
```
```
npm install
```

#### 4. Copy the content of ```.env.example``` file then create ```.env``` file and paste to ```.env``` file

#### 5. Create Database with the same name as ```DB_DATABASE``` from   ```.env``` file

#### 6. Run migration
```
php artisan migrate:fresh --seed
```

#### 7. Link the storage to public folder
```
php artisan storage:link
```

#### 8. Start the server and vite
```
php artisan serve
```
```
npm run dev
```

## Authors

- [@badzlan](https://github.com/badzlan)
- [@ridwanalfarezi](https://github.com/ridwanalfarezi)
