# engAraDictionaryFrom_ArabEyes
English - Arabic dictionary MySQL database based on WordList from ArabEyes Team 


<p dir="rtl">قاعدة بيانات SQL للقاموس الانجليزي العربي  المقدم من مجموعة عيون عربية</p>
<p dir="rtl">جزيل الشكر والتقدير لمجموعة عيون عربية وخصوصا</p>

<ul dir="rtl">
  <li>أحمد الرشيدان</li>
  <li>أسامة خياط</li>
</ul>


for more info [@usef_ksa](https://twitter.com/usef_ksa) on Twitter

<p dir="rtl">المصدر</p>
<p dir="rtl">https://sourceforge.net/projects/arabic-wordlist/</p>

<h2 dir="rtl">طريقة الإستخدام</h2>

```mysql 
mysql -u root -p

CREATE DATABASE engAraDictionary;

use engAraDictionary;

source /path/engAraDictionary.sql

show tables;

select * from engAraDictionary limit 3;
```
