# engAraDictionaryFrom_ArabEyes
English - Arabic dictionary MySQL database based on WordList from ArabEyes Team 


قاعدة بيانات SQL للقاموس الانجليزي العربي  المقدم من مجموعة عيون عربية

جزيل الشكر والتقدر لمجموعة عيون عربية وخصوصا

احمد الرشيدان

اسامة خياط


for more info @usef_ksa on Twitter


المصدر


https://sourceforge.net/projects/arabic-wordlist/




طريقة الاتسخدام



mysql -u root -p

CREATE DATABASE engAraDictionary;

use engAraDictionary;

source /path/engAraDictionary.sql

show tables;

select * from engAraDictionary limit 3;
