# 4ЕИТ_A6
ШИФРА РАДНОГ ЗАДАТКА: 4ЕИТ–А6

 НАЗИВ РАДНОГ ЗАДАТКА: Израда десктоп апликације: Половни аутомобили

 Агенција за продају половних аутомобила исказала је потребу за аутоматизацијом претраге расположивих возила. На конкурсу је ваша фирма изабрана за извођача посла и поделом задужења добили сте задатак да реализујете део апликације који се односи на измену података о аутомобилима у бази (у случају када се због иницијалног погрешног уноса јавила потреба за корекцијом), као и модул за проверу броја расположивих возила у оквиру задатих критеријума пређене километраже. Поред продаје откупљених возила, агенција почиње да се бави и посредовањем у продаји, тако да је потребно проширити саму базу могућношћу чувања неких додатних података.

 На основу спецификације дате у Прилогу задатка урадити следеће:

 Дизајнирати десктоп апликацију у циљу задовољења захтева;
 Повезати десктоп апликацију са базом података;
 Креирати упите за манипулацију подацима у бази података;
 Тестирати функционалности десктоп апликације;
 Модификовати структуру базе података у складу са захтевима корисника;
 Написати упутство корисницима о коришћењу апликације;
 ЕР дијаграм, бекап базе и апликацију запамтити на десктопу рачунара, у фолдеру Матурски_испит_4ЕИТ\Име_Презиме\4ЕИТ_A6, где се као име и презиме уноси име ученика.

 Предвиђено време за израду задатка је 180 минута.

 По истеку максималног времена задатак се прекида и бодује се оно што је до тада урађено.

 У оквиру времена за израду задатка ученик може да одустане од даљег рада, при чему се бодује оно што је до тада урађено.

 Прилоге преузети из фолдера 4ЕИТ на десктопу рачунара. Дијаграм почетне структуре базе дат је као Прилог_4ЕИТ_А61.

Резервна копија почетног стања базе дата је као Прилог_4ЕИТ_А62. Архива слика и икона дата је као Прилог_4ЕИТ_А00.

 ПРИЛОГ:

 

 Креирати форму која има три таба. На првом табу се приказују подаци о свим расположивим моделима аутомобила. Подаци о моделима аутомобила приказује се у listBox контроли.

 На почетку ни један модел није селектован, а уносом шифре у одговарајуће поље и кликом на дугме са иконом лупе у листи се проналази модел са унетом шифром, селектује се и подаци о њему приказују у левом делу форме. Ако модел са унетом шифром не постоји, селекција се склања и контроле у левом делу форме се ресетују на иницијалне вредности.



Уколико су произвођач или назив селектованог модела погрешно унети, могу се изменити уносом нових вредности. Кликом на дугме Измени, врши се корекција вредности у бази. Ако је измена успешно одрађена, освежити листу и селектовати измењен модел. Ако измена није начињена, послати поруку кориснику.

 Дугме Изађи затвара целу апликацију.

 

 Други таб форме организовати као на скици. Кликом на дугме Прикажи, потребно је приказати расположиви број возила сваког од произвођача. Треба разматрати податке само за возила чије је годиште производње у задатом интервалу година и која су максимално прешла дату километражу.

 На трећем табу је исписано кратко корисничко упутство и документација о апликацији.

 Због бављења посредовањем у продаји, у базу је потребно додати могућност да се чувају подаци о тренутним власницима аутомобила (име, презиме, телефон, адреса, да ли се ради о првом власнику). Сваки аутомобил може да има само једног власника. Такође је потребно додати могућност памћења почетне понуђене цене за возило, са тим што треба обезбедити да се не може унети нелогична вредност (цена не може бити мања од нуле).

 Креирати дијаграм и бекап стања проширене базе.
