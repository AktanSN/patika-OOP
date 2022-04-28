# Hayvanat Bahçesi Yönetimi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.
````
1. Hayvanlar:

2. Atlar (atlar, zebralar, eşekler vb.),

3. Kedigiller (kaplanlar, aslanlar vb.),

4. Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

5. Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
tür adı, ağırlığı, yaşı vb.

6. Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()

7. Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
````
Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

## UML Diyagramı
![photo](https://user-images.githubusercontent.com/58556840/165862771-82e2ce07-f8f0-44eb-b0b9-3a89e2bfaf88.png)
