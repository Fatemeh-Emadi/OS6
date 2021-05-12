# OS6
آزمایشگاه سیستم عامل 
تمرین 6

1)showing list in descending order
ls -S:

 لیست کردن همه پرونده ها و مرتب سازی آن ها بر اساس اندازه به طور 
              پیش فرض خروجی را به ترتیب نزولی نمایش می دهد

ls -t:

فایل ها و فولدر ها را بر اساس زمان اصلاح به طور نزولی مرتب می کند

2)put password on a rar file

First-> sudo apt install rar   ( install rar )

Second-> mkdir testfile   (create a file)

Third->rar a testfile.rar testfile (rar the file)

Fourth-> rar a -p testfile.rar  (with  a -p can put password)

 rar a (filename).rar : 

فشرده کردن فایل

rar a -p : 

قراردادن پسورد روی فایل فشرده 

3)put password on a zip file

First-> sudo apt install zip ( install zip)

Second->mkdir testfile (create a file)

Third-> zip -re testfile.zip testfile 

ابتدا یک فایل ایجاد کردیم سپس از دستور زیر استفاده کردیم

zip -re (filename.zip) 

این دستور به ما این امکان را می دهد که بر روی فایل زیپ خود 
                                  پسورد ایجاد کنیم  


4) nano  arguments 

nano -g:show cursor in file browser and help text

nano -l:show line numbers in front of the text

nano -V:print version information
