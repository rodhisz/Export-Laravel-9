## Laravel 9 User Export 

Source : [techsolutionstuff Laravel 9 Export](https://techsolutionstuff.com/post/how-to-export-excel-file-in-laravel-9)

### Note :
(Jika kalian mengikuti tutorial dari link diatas)

1 - Install Laravel Excel sesuai yang ada di web resminya akan error maka dari itu install seperti dibawah ini :

    composer require maatwebsite/excel --with-all-dependencies

2 - ketika menggunakan `PHP artisan tinker` akan muncul shell dan masukan ini :

    User::factory()->count(500)->create()

untuk membuat data dummy sebanyak 500 data

3 - Di route ada pemanggilan nama fuction yang salah
