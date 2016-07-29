# [pika launcher](https://telegram.me/pika_launcher)


**An advanced and powerful launcher cli bot based on [yagop/telegram-bot](https://github.com/yagop/telegram-bot) licensed under the [GNU General Public License](https://github.com/SEEDTEAM/TeleSeed/blob/master/LICENSE)**.

[![https://telegram.me/Blackwolf_admin](https://img.shields.io/badge/💬_mohamad-developer-blue.svg)](https://telegram.me/Blackwolf_admin) 
[![https://telegram.me/open_sources](https://img.shields.io/badge/💬_telegram-channel-green.svg)](https://telegram.me/open_sources) 

# مزایا

* **آپتایم 99 درصدی ربات شما**
* **! آپتایم 100 درصدی خود ربات لانچر**
* **افزایش دقت ربات آنتی اسپم و آنتی تبلیغ شما**
* **بهبود کیفیت گروه های ربات**
* **!و یا نام های مشابه steady.sh افزایش دقت ربات در ریپلی ها به دلیل حذف عامل آن یعنی**

# توضیحات

خیلی از شما دوستان یک مشکل بزرگ دارید که رباتتون افلاین میشه و خیلی مشکلات ایجاد میکنه و باید بدانید 
! که یه ربات خوب به پلاگین و سورسش نیست ، بلکه به مدت آنلاین بودنش هست 

.این ربات به دلیل اینکه از ورژن سه تله سید ساخته شده و سوپرگروه ساپورت نمی کنه ، خودش هرگز اف نمیشه مگر به خاطر سرور خودتون

* **مرحله اول**

خب اول از همه سورس فایل منیجر تله سید رو نصب کنید
>###**[file-manager-bot](https://www.github.com/blackwolfadmin/server-manager)**
>>حتما ایدی ربات لانچر رو داخلش به عنوان ادمین قرار بدید
>>>این ربات نقش کنترل سرور شما رو داره که ربات لانچر ما به اون وصل میشه
>>>>ربات فایل منیجر را داخل همون یوزر از سرور ران کنید که ربات آنتی اسپمتون داخلش ران هست


* **مرحله دوم** 

به پوشه رباتتون اضافه کنید که نقش یک لانچ رو داشته باشه **[launch](http://telegram.me/open_sources/3)** در این قسمت شما باید یک فایل به نام 

>##[Download launch file](http://telegram.me/open_sources/3)
>> فایل رو به پوشه اصلی رباتتون اضافه کنید 
>>>اسم یوزر سرور خودتون رو جاش بزارید **serveruser** به جای pika.comf پوشه را باز کنید و داخل فایل 
>>>> !دست نزنید telegrambotpath نکته : به 

**!خیلی از شما به اشتباه فکر میکنید باید به جای این کلمه داخل این پوشه ، اسم پوشه ربات خودتون رو بزارید که کاملا اشتباه هست**

* **مرحله سوم**

:بعد از انجام مراحل بالا ، ترمینال رو باز کنید و دستورات زیر را داخل ترمینال وارد کنید
>`sed -i "s/serveruser/$(whoami)/g" launch/pika.conf`
>>مثل قبل نام یوزر سرور را قرار دهید ، **serveruser** به جای 

سپس

`sed -i "s_telegrambotpath_$(pwd)_g" launch/pika.conf`
`sudo cp launch/pika.conf /etc/init/`

:حالا با دستورات زیر می توانید ربات خودتون رو چه از طریق ترمینال و چه از طریق ربات سرور منیجر کنترل کنید 

`sudo start pika` _to start pikabot_
`sudo stop pika` _to stop pikabot_
`sudo restart pika` _to restart and make new process for pikabot_
