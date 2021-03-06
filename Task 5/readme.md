## «Разработка игровых проектов с использованием Unity 2D. Создание игры «Ловилка»»

​     Программа выполнена в среде разработки Unity 2D. Приложение написано для операционной системы Windows.

 

**Суть игры «Ловилка»**

 

На платформе располагается игрок. Он может двигаться влево или вправо до границы платформы. В данной программе игрок выглядит как цилиндр (шляпа). С неба падают 2 вида объектов: бомбы и шары. Наша задача поймать как можно больше шаров и как можно меньше бомб. За каждый пойманный шар мы получаем 10 очков, за бомбу - минус 10. Ваш счет написан справа от центра платформы. Программа сопровождается музыкой, при поимке шара идет «удачный звук», при поимке бомбы - «неудачный».

 

**Реализация:**

Так выглядит рабочая среда программы.

![img](../md_src/clip_image002.jpg)



 

Объекты в данной программе:

![img](../md_src/clip_image003.jpg)

Score - текст, показывающий ваш счет

Player - цилиндр

Sky - небо

Ground - платформа

Ball - шары, постоянно появляющиеся рандомно

Bomb - бомбы, постоянно появляющиеся рандомно

Spawner и RightSide - места, между которыми появляются шары и бомбы

LeftWall и RightWall - левая и правая границы, за которые не может зайти игрок

Спрайты и скрипты см в **Приложении**.



 

Начало игры:

![img](../md_src/clip_image005.jpg)

Ловим шар и получаем +10 ( теперь у нас станет 40).

![img](../md_src/clip_image007.jpg)

Ловим бомбу и получаем -10 ( станет 60)

![img](../md_src/clip_image009.jpg)

![img](../md_src/clip_image011.jpg)

 

Игра не очень замысловатая. В моей модификации объекты падают быстро, но цилиндр двигается тоже быстро. Набил 350 очков и вспомнил, что пора делать Task6.

![img](../md_src/clip_image013.jpg)

### Приложение

Спрайты:

![img](../md_src/clip_image015.jpg)

 

Скрипты:

 ![5](C:\Users\OgRob\Desktop\C#\C_sharp_1st_term\md_src\5.PNG)

**itemChecker****:** скрипт проверяет, поймали ли мы шар/бомбу.  Отвечает за ваш счет и за звук.

**itemSpawn:** скрипт рисует шары/бомбы на одной высоте с рандомно выбранной первой координатой

**PlayerMove****:** скрипт отвечает за движение цилиндра влево-вправо

**timeDestroyer:** скрипт удаляет объекты из сцены 