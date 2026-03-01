# اسکریپت KING (شاه)
اسکریپت شاه ، ابزار نصب آسان تانل paqet با امکان نصب افلاین پکت و ابزارهای مورد نیاز بر روی سرور ایران، مدیریت تانل ها و سرویس ها، تغییر پیکربندی و پورت های تانل


# MAKE IRAN GREAT AGAIN
<img width="1361" height="431" alt="image" src="https://github.com/user-attachments/assets/da8418ef-196b-4fba-8088-25eb7aa5cd15" />

## آموزش استفاده 
1.  فایل اسکریپت را بر روی سرورهامنتقل کنید
    - برای خارج از دستور دریافت از گیت هاب و برای ایران از لینک دانلود آن را دریافت و روی سرور ایران خود آپلود کنید.
 
  
  
          wget -O shah "https://raw.githubusercontent.com/ToolSeRF/KING-Paqet-Tunnel-Manager-with-offline-mode/main/shah?$(date+%s)" && chmod +x shah && bash ./shah


  [برای دانلود فایل اینجا کلیک کنید ](https://github.com/ToolSeRF/KING-Paqet-Tunnel-Manager-with-offline-mode/releases/download/v1/shah)
      
2. سپس با استفاده از گزینه ی 1 باینری و ابزارهای مورد نیاز برای paqet را روی سرور خود نصب کنید
    - از دو حالت آفلاین مود و آنلاین مود برای نصب می توانید استفاده کنید.
    - در روش آفلاین مود می توانید فایل را از لینک هایی که در پایین قرار دارند و مربوط به سیستم عامل شما هستند دانلود کنید و در /root/ سرور خود آپاود کنید. نسخه minimal معمولا کفایت میکنه، نسخه فول جهت اطمینان تمام پیش نیازها رو پشتیبانی میکنه.
    - همچنین میتوانید بدون آپلود فایل دانلود را به لینک داخلی که برای دانلود فایل قرار داده شده بسپارید، هر دو مورد امکان پذیر است.
3.  سپس در سرور خارج با استفاده از منوی شماره 2 پیکربندی مربوط به تانل را انجام دهید.



### آموزش ایجاد تانل با استفاده از خط فرمان
برای استفاده از خط فرمان ابتدا راهنمای خط فرمان را پایین این صفحه مطالعه کنید ساده ترین راه استفاده از این دو دستور ساده با تغییر پارامترهاست
````
# kharej side
./shah kharej 44 8443 4 fast 1300 auto --firewall --start

#iran side
./shah iran 44 "8443=8443 80=8080" 10.10.20.10 8443 4 fast 1300 auto YOUR_KEY_HERE --start

#kharej manual mode
./shah kharej 44 8443 4 manual 1300 auto \
  --key YOUR_KEY_HERE \
  --kcp-nodelay 1 --kcp-interval 10 --kcp-resend 2 --kcp-nc 1 \
  --kcp-rcvwnd 4096 --kcp-sndwnd 4096 \
  --kcp-smuxbuf 8388608 --kcp-streambuf 4194304 \
  --firewall --start

#iran manual mode
./shah iran 44 "8443=8443 80=8080" 10.10.20.10 8443 4 manual 1300 auto YOUR_KEY_HERE \
  --kcp-nodelay 1 --kcp-interval 10 --kcp-resend 2 --kcp-nc 1 \
  --kcp-rcvwnd 2048 --kcp-sndwnd 2048 \
  --kcp-smuxbuf 6291456 --kcp-streambuf 3145728 \
  --start
````

### آموزش ایجاد تانل با استفاده از منو


4.  بعد از آن روی سرور ایران با گزینه ی شماره 3 پیکربندی مربوط به سرور ایران را انجام دهید.
    - برای پورت فوروارد از این حالت استفاده کنید 8443=8443 5252=6262 و چندین پورت رو میتونید با فاصله وارد کنید.
5.   برای مدیریت سرویس ها از گزینه ی 4 استفاده کنید. میتوانید پورت ها را ویرایش، اضافه یا پیکربندی را کامل تغییر دهید، همچنین وضعیت سرویس ها را مدیریت کنید.
6.   برای پرفرمنس بهتر از گزینه 5 آپتیمایزر استفاده کنید.
7.   برای پاکسازی کامل تانل ها و حذف باینری از گزینه ی 6 استفاده کنید.


در صورت نیاز میتونید فایل ها رو دستی از این لینک دانلود کنید و به سرور منتقل کنید
  [لیست لینک ها ](https://raw.githubusercontent.com/ToolSeRF/KING-Paqet-Tunnel-Manager-with-offline-mode/refs/heads/main/deps-bin-iran-uploader-url)


# با امید آزادی ایرانمان در چند روز آینده

## حمایت
TRX/TRC20   ````TN5yCqCULRzCJeqC8ut4vSvi1yDMLT6BAH````

USDT/BEP20 ````0x1675c55831AA4c4576581Bbc10c479a0F49a9440````

TON ````UQCWlTueguogfztqY_VkdJgYtZgbTd-3bjbvWRKaqCKyFlXD````
