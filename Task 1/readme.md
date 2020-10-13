## «Проектирование простого интерфейса средствами Windows Forms: создание программы «Словарь»»

Программа выполнена в среде разработки microsoft visual studio 2017 с помощью Windows Form. Приложение написано для операционной системы Windows. 

Начальный экран программы выглядит следующим образом:![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

Главный экран представляет из себя окно, содержащее:

·    Панель инструментов с тремя кнопками

·    Окно ввода (сверху)

·    Окно вывода (снизу)

·    Кнопка перевода

 

Панель инструментов выражена тремя кнопками. Нажав на первую идет перевод с английского на русский, нажав на вторую идет перевод с русского на английский, а третья - выход из программы.

·    En -> Ru; 

·    Ru -> En;

·    Exit.

 

Программа предоставляет возможность перевода слов с русского на английский язык, и с английского - на русский. 

Переход с английского на русский:

 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

 

Переход с русского на английский:

 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg)![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image010.jpg)



 

Кнопка «Выйти из программы». 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image012.jpg)

Кстати, в программе также есть tooltips (всплывающие подсказки). При наведении на какой-либо элемент в окне всплывает следующее: 

 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image014.jpg)![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image016.jpg) 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image018.jpg)![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg)

 

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image024.jpg)



 

В нашем словаре имеются следующие слова:

| car    | машина  |
| ------ | ------- |
| dog    | собака  |
| mother | мама    |
| girl   | девушка |
| father | папа    |
| cat    | кошка   |

 

База слов реализована в файлах EnRuDict.dat  и RuEnDict.dat.

Теперь введем какое-нибудь слово на русском из базы словаря

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image026.jpg)

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image028.jpg)

Аналогично для английского:

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image030.jpg)

 

Если введенного слова нет в словаре, то программа выдаст:

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image032.jpg)

### Приложение

Схема файла OganyanVar2Slovarik

![img](file:///C:/Users/OgRob/AppData/Local/Temp/msohtmlclip1/01/clip_image033.jpg)