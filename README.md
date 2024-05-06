MongoDB - bu hujjatlar bilan ishlashga yo\'naltirilgan ma\'lumotlar
bazasini boshqarish tizimi, ya\'ni bizda jadvallar bo\'lishi shart emas.
MongoDB NoSQL malumotlar bazasi turiga kiradi, u JSONga o\'xshash
hujjatlar va ma\'lumotlar bazasi sxemasidan foydalanadi, bu shuni
anglatadiki biz MongoDB da ishlash uchun SQL so\'rovlarini bilishimiz
shart emas. MongoDB C++ tilida yozilgan. MongoDB da Odatiy SQL dagi
jadvallar yo\'q, aksincha unda kolleksiyalar bor. Kolleksiyalar, SQL
dagi jadvallarning analogi hisoblanadi, lekin ular jadvallarga o\'xshab
aniq bir strukturaga ega emas. \-\-\-\-\-\-\-\-\-\-\-\-\-- \

MongoDB Ierararxiyasi

1\. Klaster(Cluster). Bu MongoDB ierarxiyasining eng yuqori darajasi.
Klaster ma\'lumotlarni saqlash va qayta ishlash uchun birgalikda
ishlaydigan bir nechta ma\'lumotlar bazasidan iborat. 2. Ma\'lumotlar
bazasi(DataBase) Har bir MongoDB klasterida bir nechta ma\'lumotlar
bazalari bo\'lishi mumkin. Ma\'lumotlar bazasi to\'plamlar va indekslar
uchun mantiqiy konteynerdir. Ma\'lumotlar bazasi ichida ma\'lumotlar,
shuningdek, foydalanuvchilar, kirish huquqlari va konfiguratsiya
parametrlari kabi meta ma\'lumotlar saqlanadi. 3. To\'plam(Collection)
To\'plam ma\'lumotlar bazasida joylashgan va hujjatlar uchun
konteynerdir. Bu so\'rovlar ishlashini yaxshilash uchun indekslanishi
mumkin bo\'lgan tartiblangan hujjatlar to\'plamini ifodalaydi.
To\'plam(Collection) turli tuzilmalarning hujjatlarini o\'z ichiga
olishi mumkin, shuningdek, ma\'lumotlarni oddiy va samarali saqlash va
tashkil etishni ta\'minlaydi. 4. Hujjat(Document) Hujjat to\'plamda
joylashgan va MongoDBda ma\'lumotlar birligini ifodalaydi. U
kalit-qiymat juftliklaridan iborat bo\'lib, bu erda kalitlar
maydonlarning nomlari va qiymatlar ma\'lumotlarning o\'zi. MongoDB-dagi
hujjatlar turli tuzilmalarga ega bo\'lishi mumkin va ularning formati
qat\'iy sxemani talab qilmaydi, bu esa ma\'lumotlar bazasini yanada
moslashuvchan va masshtabli qiladi.
