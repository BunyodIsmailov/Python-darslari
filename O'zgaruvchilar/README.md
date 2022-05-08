**Python o'zgaruvchisi nima?** 
  - Keling, o'zgaruvchi nima ekanligini rasmiyroq aniqlashdan boshlaylik:


**O'zgaruvchan**
  - O'zgaruvchidan keyinroq murojaat qilish mumkin bo'lgan ma'lumotlarni saqlash uchun foydalaniladi

> Demak, o‘zgaruvchi bu, masalan, hisob-kitob natijasini nomlash uchun foydalanadigan narsadir. Yoki, boshqacha qilib aytganda, biz o'sha hisoblash natijasini o'zgaruvchiga belgilashimiz mumkin. Biz cheksiz miqdordagi o'zgaruvchilarni yaratishimiz mumkin; biz ularga o'ziga xos nomlar berganimizga ishonch hosil qilishimiz kerak.


**Python o'zgaruvchisini e'lon qilish**
  - Birinchi o'rinda __REPL__-ni ochib olishim kerak
  	- ПУСК+R knoplarini bosish orqali  terminal (cmd)-ni ochib olamiz
  	  - agarda siz Python o'rnatgan bo'lsangiz oddiy **python** so'zini yozing va __Enter__-ni bosing

![ПУСК+R](images/1.png)


Biz REPLda chaqirilgan Python o'zgaruvchisini (rasmiy ravishda o'zgaruvchini e'lon qilish deb ataladi) natija yaratamiz. Ammo buni qilishdan oldin, biz Python qanday natija ekanligini bilishini tekshirib ko'ramiz:

![natija](images/2.png)


> Python sizga xatolar haqida ma'lumot beradi. Birinchi ikkita qatorga e'tibor bermang va uning o'rniga haqiqiy xatoga e'tibor qarating. Python xabar beradi: name 'natija' is not defined. Python xatolar, agar siz qayerga qarashni bilsangiz, juda foydali bo'ladi. Shuning uchun men sizga bittasini ko'rsatmoqchi edim. Oxir-oqibat, siz o'zingiz kod yozishingiz kerak bo'ladi va xatolarga duch kelish, afsuski, ishning katta qismidir. Xatolarni shifrlash foydali mahorat bo'ladi!

Keling, o'zgaruvchining nomini e'lon qilamiz natija va unga qiymat berib sinab ko'raylik:
![natija](images/3.png)


Bosqichma-bosqich shunday bo'ladi:
- Python topshiriq deb ataladigan narsani ko'radi: biz 2 * 5 natijasini chaqirilgan o'zgaruvchiga belgilaymiz natija. Topshiriqlar qulay tarzda “is” deb ataladigan “=” belgisi bilan bajariladi. Shunday qilib, biz Python-ga aytdik: men e'lon qilamanki natija, bu 2 * 5 ifodasining natijasidir.

- Keyinchalik, biz yozamiz natija.

- Python buni buyruq sifatida tan olmaydi, shuning uchun u bu nomga ega o'zgaruvchi bor yoki yo'qligini aniqlashga harakat qiladi. Bor va biz unga 10 tani tayinladik. Demak, bu chiziq ekranda chop etilgan 15 raqamiga baholanadi.



**O'zgaruvchilarni nomlash**

> Misolda biz umumiy nomni tanladik  natija, lekin siz o'zingizga mos deb hisoblagan har qanday nomni tanlashingiz mumkin. Umumiy qoida sifatida, har doim uning mazmunini eng yaxshi tavsiflovchi o'zgaruvchi nomini tanlang. Ushbu amaliyot sizning kodingizni yanada o'qilishi va tushunishni osonlashtiradi. Agar biz bu erda xarid qilish savatining umumiy narxini hisoblaganimizda, masalan, yaxshi nom bo'lar edi savdoning_umumiy_narxi.

> O'zgaruvchilar nomlaridagi belgilar sonini kamaytirmang. savdoning_umumiy_narxi kabi qisqartmalar o'rniga toza, o'qilishi mumkin bo'lgan ismlarga ega bo'lish yaxshiroqdir sun. Tez orada bilib olganingizdek, yaxshi kod muharriri oʻzgaruvchilar nomlari kabi narsalarni avtomatik tarzda toʻldiradi, shuning uchun agar sizni tashvishlantirayotgan boʻlsa, ularni toʻliq kiritishingiz shart emas.



**Ifodalarda o'zgaruvchilardan foydalanish**
  - Python o'zgaruvchilari tilning muhim qismidir, chunki siz ularni boshqa iboralarda ham ishlatishingiz mumkin: