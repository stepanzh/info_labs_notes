# Домашнее задание
1. Проработать [лабораторную №2](http://cs.mipt.ru/algo/lessons/lab2.html);
2. Выполнить контест из этой лабораторной.

# Организация рабочего процесса
_прежде чем начать что-то устанавливать, прочтите эту главу целиком_

Для запуска и написания кода `Python` понадобится 2 программы: интерпретатор языка `Python` и текстовый редактор.

Скачать `Python` можно с [официального сайта](https://www.python.org/).
В разделе загрузок выберете вашу операционную систему (Windows, Linux, MacOS) и последнюю версию языка (на момент написания заметки это `Python 3.7.4`).

__В процессе установки на Windows не забудьте поставить галочку напротив включения Python в переменную PATH.__
Так вы сможете запускать программы на Windows из терминала (`cmd`, `PowerShell`) аналогично тому, как мы запускали программы на лабораторных в `bash` терминале.

## Текстовые редакторы
Далее, для __написания__ кода необходим текстовый редактор.
Самый простой из них уже установлен в Windows и это `Блокнот` (`Notepad`), в случае linux это обычно `gedit`.
Однако, `Блокнот` не имеет подсветки синтаксиса, т.е. не будет выделять цветом конструкции языка.

Известные мне редакторы, сделанные для написания кода:
- gedit - простой [оконный](https://ru.wikipedia.org/wiki/%D0%93%D1%80%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81_%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F) редактор, которым мы пользовались на лабе имеет полезные расширения, вроде мультикурсора, разбиения окон для просмотра двух файлов сразу, сниппеты... Стабильно работает на linux системах, на других не пробовал;
- Sublime Text 3, Atom - мощные (если изучить функционал) расширяемые оконные редакторы, несмотря на мощность, не пугают неподготовленного пользователя;
- __(hardcore)__ nano, emacs, vim - прежде чем пользоваться, придётся их изучить :) Изначально существуют в виде [консольных версий](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81_%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%BE%D0%B9_%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8), но есть и оконные аналоги.

Можете поискать скриншоты редакторов и выбрать понравившийся.

В них, однако, потребуется в настройках выставить опцию замены знака табуляции на 4 пробела, чтобы раз и навсегда не вылетало от `Python` ошибок отступа.
Обычно эти опции называются `Ширина табуляции (Tab width)` (выставить 4 знака) и галочка `Использовать пробелы вместо табуляции (Use spaces instead of tabulation)`.

## Интегрированные среды разработки
Чтобы не переключаться между окнами текстового редактора и терминала, программисты придумали специальные программы, содержащие в себе эти функции сразу.
Имя им "Интегрированная среда разработки" или IDE.

IDE существует великое множество, отличаются широтой встроенных (интегрированных) инструментов.
Соответственно, эти программы довольно тяжёлые как по размеру, так и по скорости работы и обладают перегруженным интерфейсом, который будет пугать первое время, при этом 99% возможностей нам не понадобятся.

Ниже я привожу список знакомых мне IDE:
- IDLE - поставляется вместе со скачиванием `Python`, поищите его в папке, куда установили интерпретатор;
- __(рекомендую)__ Spyder IDE - среда разработки для написания кода на `Python`. _Почему?_ - не столь перегруженная, есть в компьютерных классах, и вам не придётся привыкать к разным инструментам;
- Jupyter Notebook - построен на базе [iPython](https://ru.wikipedia.org/wiki/IPython), интерпретаторе `Python`, позволяющем запускать кусочки кода. Кажется, есть у нас классах;
- PyCharm - сильная перегруженная (в нашем контексте) IDE, даётся бесплатная подписка при использовании аккаунта почты @phystech.edu;
- VSCode - хорошая перегруженная (в нашем контексте) IDE от Microsoft для самых разных языков программирования.

# Дополнительно: основы `Python 3`
Официальная документация языка находится [здесь](https://docs.python.org/3/).
Можете поискать русские переводы, хотя лучше начать изучать английский.

Почитайте про типы данных и что с ними можно делать: `int`, `float`, `str`.

Запустите в интерактивном режиме Python и получите документацию вызовом функции `help`.
Например:
```python
>>> help(input)
>>> help(print)
>>> help(str.split)
```

Постарайтесь понять структуру документации: назначение функции, её аргументы.
Поэкспериментируйте с изученными функциями.