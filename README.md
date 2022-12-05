Fork of MiniShowCase from http://minishowcase.net/ v09b142

minishowcase is a small and simple php/javascript online photo gallery, 
powered by AJAX that allows you to easily show your images online,
without complex databases or coding, allowing to have an up-and-running
gallery in a few minutes.

# Usage
 * put image or video folder to the directory `minishowcase/galleries/`
 * default mode `0` is good at browsing consistency
 * mix mode `3` is good at image mobile browsing experience
 * preset preview mode is `3`. if you need consistency, change the property in `setting.php`

# Fix
 * fix file path bug in loading spinner.gif
 * image swipe compatible with default preview mode

# Features
 * TreeView for the gallery directories
 * photoswipe plugin integration
 * flv support
 * mp4 support
 * hls support  `m3u8`
 
# BasedOn
 * Original based on http://minishowcase.net/ v09b142
 * Further based on http://people.via.ecp.fr/~jm/minishowcase-jm.html
 * Further based on https://github.com/OldSparkyMI/minishowcase
 * Further based on http://www.briancbecker.com/blog/projects/minishowcase-mod/ 
 * Player https://github.com/Bilibili/flv.js
 * Player https://github.com/videojs/video.js

# Icons
 * Plus/Minus Icon from http://www.famfamfam.com/
 
# Some idea
 * ~~Flv support~~
 * ~~Mp4 support~~
 * ~~Vedio thumbnail support~~
 * Rtmp support

Это форк форков  веб галереи minishowcase далекого 2011 года.
Галерея представляет из себя готовую автономную веб станицу которую можно встроить на сайт, или использовать ее саму по себе.
Демо можно посмотреть тут http://gallery.mygemorr.ru/
# Установка: 
*	Скачать архив. Если вы это делаете с моей страницы гита ( https://github.com/AlexanderPanshin/minishowcase ) Шмякнуть зеленую кнопку “<>Code”
И Выбрать пункт Download ZIP. 

*	Скачанный архив нужно распаковать архив в корень сайта (структура каталогов будет примерно в таком духе www/minishowcase )в таком случаи галерея будет по адресу http://адрес_вашего_сайта/minishowcase  . Если вы хотите что бы галерея была сразу при переходе на ваш домен, то следует распаковать не сам архив а содержимое папки minishowcase.
*	После распаковки галерея уже начнет функционировать . Для того что бы загрузить ваши фотографии следует скопировать папку с ними в каталог galleries.
*	Для того что бы поменять title на ваш нужно отредактировать файл settings.php который находиться в каталоге config . Следует изменить значения переменной $settings['gallery_title'] = 'Ваш тайтл';
*	В этом же фале настроек можно поменять url, вид меню и язык.
*	Хотя смена языка сломалась после того как была добавлена функция декодирования в UTF 8. Моей задачей было именно отображение русского языка, по этому вникать что сломалось я не стал.
*	Также можно изменить цветовую тему галереи $settings['use_theme'] = 'dark'; существует три возможных варианта dark, default, blue
*	Если у вас уже есть свой footer и header можете добавить их в файл add_footer.php и add_header.php
*	После установки нужно создать папку cache и присвоить ей права 777
