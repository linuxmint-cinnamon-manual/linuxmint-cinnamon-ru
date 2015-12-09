---
title: "Linux Mint: установка"
---

Сравнение инсталлятора дистрибутива с театральной вешалкой настолько старо,
что никто уже не помнит автора (вашему покорному слуге почему-то кажется, что
это был именно он). И за минувшие пятнадцать лет оно не столько даже
затёрлось, сколько потеряло силу. В наши дни любой дистрибутив, претендующий
на внимание так называемых конечных пользователей, располагает удобной, более
или менее функциональной программой установки самого себя, иногда даже
красивой. Тем более что удачные решения в этой области имеют обыкновение
расползаться по всяким клонам и ремиксам.

Именно так случилось некогда с инсталлятором Ubuntu — десять лет назад его
установка в пять кликов сыграла не последнюю роль и в распространении этого
дистрибутива по пользовательским десктопам, и в образовании многочисленных
прямых, косвенных и откровенно примазавшихся родственников, вплоть до
«дистрибутивов с нескучными обоями».

В числе родственников... нет, не примазавшихся, а настоящих, но пошедших
другим путём, был и дистрибутив Mint. Сейчас не время обсуждать его
взаимоотношения с прародительской Ububtu, но программу установки он
унаследовал от неё практически без изменений. По крайней мере, до недавнего
времени макроскопических различий в инсталляторах этих систем не наблюдалось.

Честно говоря, их не наблюдается и сейчас, с выходом версии Mint 17, а затем и
Mint 17.1 — формально отличий в установке с Ubuntu 14.04 нет. Так что о чём
тут говорить, спросите вы меня? Отвечу: говорить действительно не о чем — это
нужно видеть. Точнее, делать своими руками — и наблюдать за результатом. Ибо
даже скриншоты, которыми я на этой странице практически и ограничусь, не в
силах передать того ощущения лёгкости и плавности, которое испытывает истинный
применитель при установке этого дистрибутива.

Итак, установка Mint'а запускается из Live-режима его работы, являющегося
следствием загрузки с соответствующего носителя — DVD или, что
предпочтительно, флешки (или SD-карты). Кстати, не обязательно слушать того,
кто будет убеждать вас закатать iso-образ на твердотельный носитель с помощью
всяких специальных утилит. С этой задачей прекрасно справляется такая команда:

```console
# dd if=path3/linuxmint-17.1-cinnamon-64bit.iso of=/dev/sd? bs=8M
```

Символ решётки тут символизирует, что она должна быть дана от имени
администратора (то есть в Ubuntu и её клонах — в форме

```console
$ sudo dd...
```

и так далее. Имя входящего файла образа выбрано так потому, что дальнейший
рассказ у меня пойдёт исключительно о Cinnamon-редакции соответствующего
релиза. Хотя, надо отметить, что установка MATE- и Xfce-редакций ничем не
отличается, только инсталлятор редакции с KDE имеет некоторую специфику,

Вместо знака вопроса следует подставить литеру своего твердотельного
устройства — подчёркиваю, именно устройства целиком, а не раздела на нём. Ну а
значение `bs` (размер блока записи) взято с потолка: если не задать этот
параметр, запись будет идти блоками по 512 байт, и это будет очень медленно и
печально.

Конечно, использование для записи iso-образа на флешку/карточку всякого рода
графических утилит тоже не возбраняется. Важно только помнить, что многие из
них — дистрибутив-специфичны. Этому вопросу на Блогосайте посвящена
специальная статья: [Дистро в твёрдом теле](http://alv.me/?p=7245).

Так или иначе, но флешка будет записана и с неё произойдёт загрузка системы —
автоматически, если в ходе её ничего не делать, или, если в течении 10 секунд
нажать любую клавишу, из такого меню:

[ ![Изображение2](http://alv.me/wp-content/img/im_cin_img/install_001-572x483.png) ](http://alv.me/wp-content/img/2014/12/install_001.png) [ ](http://alv.me/wp-content/img/2014/12/install_001.png)

После чего мы оказываемся в live-среде Cinnamon — пора бросить на неё взгляд,
пока беглый:

[ ![Изображение3](http://alv.me/wp-content/img/im_cin_img/install_002-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_002.png)

Вдаваться в её рассмотрение сейчас не стоит — для этого у нас будет много
времени после установки, к которой и приступаем. Как нетрудно догадаться,
запуск инсталлятора осуществляется щелчком на пиктограмме с соответствующей
подписью — `Install Linux Mint`. И начинается процесс с предложения выбрать язык
установки — по умолчанию английский:

[ ![Изображение4](http://alv.me/wp-content/img/im_cin_img/install_003-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_003.png)

Однако, если у вас нет непреодолимого отвращения к языку родных осин, но есть
желание без лишних трудозатрат иметь корректно локализованную систему,
выбирайте русский, не пожалеете. Это будет язык не только интерфейса
инсталлятора, но и грядущей инсталлированной системы:

[ ![Изображение5](http://alv.me/wp-content/img/im_cin_img/install_004-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_004.png) [ ](http://alv.me/wp-content/img/2014/12/install_004.png)

Русификация Cinnamon до недавнего времени была далека от идеала, и со смесью
нижегородского с оксфордским приходилось сталкиваться сталкиваться довольно
часто. Однако в версии 2.4 ситуация резко улучшилась, и языковый микст можно
увидеть только в единичных случаях.

Далее выдвигаются претензии к объёму свободного места и подключению к
Интернету — приведённой цифрой первого и потребностью во втором нынче испугать
трудно:

[ ![Изображение6](http://alv.me/wp-content/img/im_cin_img/install_006-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_006.png) [ ](http://alv.me/wp-content/img/2014/12/install_006.png)

Следующий этап — разметка диска. Здесь надо действовать по амбициям и
амунициям, так что просто прокомментирую пукты соответствующего меню:

[ ![Изображение7](http://alv.me/wp-content/img/im_cin_img/install_007-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_007.png)

Очевидно, что отмеченный по умолчанию пункт `Стереть диск и установить Linux
Mint` подходит только для установки на «чистый» носитель или такой, содержимым
которого можно безболезненно пожертвовать. Причём именно всего устройства, а
не какого-либо его раздела, ибо в этом варианте диск будет переразмечен
полностью, начиная с таблицы разделов.

Об установке системы на шифрованный раздел (пункт второй) сказать ничего не
могу, так как никогда не пробовал (и сомневаюсь в необходимости в обычных
«настольных» условиях). Установка с использованием `LVM` (`Logical Volume Manager`)
показалась мне не очень прозрачной, и я её тоже не опробовал. Но со
временем расскажу, как задействовать `LVM` в уже инсталлированной системе. И
потому я всегда выбираю `Другой вариант`: он подразумевает разметку диска
вручную. Как её выполнить — говорено и переговорено на бесчисленных ресурсах в
Сети: тут всё зависит от ситуации, потребностей и возможностей. Так что просто
приведу несколько скриншотов, иллюстрирующих самый простой случай — разметку
одиночного «чистого» на два раздела — корневой и под будущий домашний каталог
(каковой, кстати, в умолчальном первом варианте не создаётся).

Итак, перед нами чистый, неразмеченный диск:

[ ![Изображение8](http://alv.me/wp-content/img/im_cin_img/install_008-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_008.png)

Можно видеть, что ни одна из кнопок манипуляции разделами (`+`, `-`, `Change`) не
активизирована, ибо диск наш лишён таблицы разделов. Которую и надо в первую
очередь создать, нажав соответствующую кнопку. Ответом будет предупреждение о
том, что все ранее существовавшие разделы будут уничтожены. Поскольку их всё
равно нет, соглашаемся на это:

[ ![Изображение9](http://alv.me/wp-content/img/im_cin_img/install_009-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_009.png) [ ](http://alv.me/wp-content/img/2014/12/install_009.png)

В результате будет создана таблица разделов в стиле `MSDOS`. Создание GPT-
разметки не предусмотрено, но если диск был предварительно размечен в этом
стиле — он прекрасно воспримется инсталлятором.

Теперь активизируется кнопка с плюсиком — очевидно, что она служит для
создания разделов. Однако, прежде чем заняться этим делом, бросим взгляд на
строку Устройство для установки системного загрузчика, каковым на скриншоте
выступает `/dev/sda`. То есть загрузчик будет установлен в MBR первого диска,
что для «чистой» однодисковой (и к тому же виртуальной) конфигурации вполне
естественно. А вот в случае какой-либо уже установленной системы, особенно при
наличии двух и более дисков, этот момент требует внимания.

Дело, однако, в том, что первый диск (то есть устройство `/dev/sda`) будет по
умолчанию целевым для установки загрузчика вне зависимости от того, на какой
диск и или раздел устанавливается Mint, что в большинстве таких случаев не
только не нужно, но и прямо вредит здоровью сосуществующих систем. И потому
надо ни в коем случае не забыть выбрать из выпадающего меню нужное устройство
— MBR диска или PBR раздела, целевых при установке Mint.

К сожалению, вообще отказаться от установки загрузчика нельзя, даже когда он
заведомо лишний, и Mint предполагается загружать через загрузчик какой-либо
иной системы. Эта багофича унаследована от Ubuntu, где существует испокон
веков. Но можно обмануть установщик, подсунув ему в качестве целевого MBR
какого-либо «левого» устройства, например, старой ненужной флешки или SD-
карты, каковые потом просто извлекаются, как-будто так и было.

Вот теперь со спокойной душой можно приступать к созданию разделов, нажав
кнопку с плюсиком. Проделываем эту процедуру сначала для корневого раздела:

[![Изображение10](http://alv.me/wp-content/img/im_cin_img/install_010-572x463.png)](http://alv.me/wp-content/img/2014/12/install_010.png)

А затем для раздела под будущий каталог `/home`:

[ ![Изображение11](http://alv.me/wp-content/img/im_cin_img/install_012-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_012.png) [ ](http://alv.me/wp-content/img/2014/12/install_012.png)

И в результате получаем вот такую картину:

[ ![Изображение12](http://alv.me/wp-content/img/im_cin_img/install_013-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_013.png)

По умолчанию в обоих случаях предлагается файловая система Ext4. Если она
почему-либо не устраивает — можно ознакомиться со списком доступных, он
включает все нативные файловые системы Linux'а, кроме ReiserFS:

[ ![Изображение13](http://alv.me/wp-content/img/im_cin_img/install_011-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_011.png)

Должен заметить, что на стадии установки в Mint не только нельзя создать,
скажем, программный RAID (в отличие от Ubuntu, в которой это уже
предусмотрено): нельзя даже установить систему на softRAID, созданный
заблаговременно, инсталлятор его просто не увидит. Впрочем, в дальнейшем,
после установки, ни подключить существующий RAID, ни слздать его заново труда
не составит, о чём будет говориться в соответствующем очерке.

Как можно было видеть, в приведённой схеме разметки отсутствует раздел
подкачки. О чём и будет сообщено на следующей стадии:

[ ![Изображение14](http://alv.me/wp-content/img/im_cin_img/install_014-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_014.png) [ ](http://alv.me/wp-content/img/2014/12/install_014.png)

Нужен такой или нет — вопрос спорный и многократно обсуждавшийся. На мой
взгляд, при памяти от 4 ГБ в большинстве случаев, кроме некоторых специальных,
не нужен. Так что можно продолжать — это действие вызовет последнее китайское
предупреждение:

[ ![Изображение15](http://alv.me/wp-content/img/im_cin_img/install_015-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_015.png) [ ](http://alv.me/wp-content/img/2014/12/install_015.png)

Смысл его в русском переводе может показаться не вполне внятым. Он сводится к
тому, что все действия по разметке диска будут выполнены только сейчас, но
после этого возврат к прошлому станет невозможным — до сих пор установку можно
было в любой момент прервать, сохранив исходное состояние диска.

Поскольку бояться нам нечего, нажимаем кнопку `Продолжить`. И, после некоторого
времени, требующегося на разметку и создание файловых систем, совершаем
последние манипуляции — настройку часов, клавиатуры и создание
пользовательского аккаунта.

С выбором часового пояса всё понятно без комментариев — при выборе русского
языка инсталляции он будет московским и подразумевать установку «железных»
часов по UTC:

[ ![Изображение16](http://alv.me/wp-content/img/im_cin_img/install_016-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_016.png) [ ](http://alv.me/wp-content/img/2014/12/install_016.png)

Так что обитателям более иных городов и весей нашей необъятной Родины следует
не забыть внести нужные изменения — это можно сделать, просто ткнув курсором
мыши в район Петропавловска Камчатского (Улан-Удэ, Новосибирска — нужное
дописать).

А вот вопрос с раскладкой внимания заслуживает: выбранная сейчас, она
останется и в инсталлированной системе. Опять же при выборе русского языка
инсталлятора по умолчанию и раскладка клавиатуры предлагается русская — в
данном случае под этим понимается вариант winkeys:

[ ![Изображение17](http://alv.me/wp-content/img/im_cin_img/install_017-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_017.png) [ ](http://alv.me/wp-content/img/2014/12/install_017.png)

Он устроит большинство применителей — но не таких старых «печатно-машинистов»,
как автор этих строк. Что же, никто не запрещает выбрать вариант `Typewriter Legacy` — 
это раскладка советских пишущих машинок, почему-то объявленная
устаревшей. И даже опробовать его в деле, переключаясь с латиницы на кириллицу
через `Alt+Shift`:

[ ![Изображение18](http://alv.me/wp-content/img/im_cin_img/install_018-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_018.png) [ ](http://alv.me/wp-content/img/2014/12/install_018.png)

Смены переключателя раскладок на стадии установки не предусмотрено — её можно
будет поменять потом, средствами Cinnamon. Зато установленная сейчас раскладка
сохранится после установки не только в Иксах, но и в «голой» консоли. Причём
даже такая нетипичная, как при моём выборе. Это чуть ли не уникальный случай —
в других дистрибутивах для консоли раскладку `Typewriter Legacy` мне приходилось
изготавливать самому.

В деле создания пользовательского аккаунта всё очевидно. Замечу только, что
раскрывать своё подлинное имя здесь не обязательно — это поле можно просто
оставить пустым. А вот задать имя компьютера необходимо — без этого не
активизируется кнопка `Продолжить`. Впрочем, в большинстве случаев оно может
быть произвольным. Ну а требовать ли от самого себя пароль для входа в систему
или нет — дело чести, подвига и геройства личной паранойи:

[ ![Изображение19](http://alv.me/wp-content/img/im_cin_img/install_019-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_019.png) [ ](http://alv.me/wp-content/img/2014/12/install_019.png)

После этого начинается собственно установка, то есть перенос системы на
целевой носитель:

[ ![Изображение20](http://alv.me/wp-content/img/im_cin_img/install_020-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_020.png)

В Ubuntu это делается весьма неторопливо. В инсталляторе же Mint едва
успеваешь заварить себе кофий или выкурить сигарету, как обнаруживаешь на
экране вот такое сообщение:

[ ![Изображение21](http://alv.me/wp-content/img/im_cin_img/install_021-572x463.png) ](http://alv.me/wp-content/img/2014/12/install_021.png)

После которого только и остаётся, что перезагрузиться. Правда, после этого
будет ещё одно сообщение:

[ ![Изображение22](http://alv.me/wp-content/img/im_cin_img/install_022-572x366.png) ](http://alv.me/wp-content/img/2014/12/install_022.png)

Если установка проводилась с DVD-диска, он будет извлечён из привода
автоматически, и Enter можно нажимать сразу. Если с флешки или SD-карты —
соответствующее устройство желательно предварительно удалить. Ну а что
получилось в результате инсталляции — будет рассказано в следующем очерке.
