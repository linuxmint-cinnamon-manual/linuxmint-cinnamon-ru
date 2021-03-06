---
title: "Mint и Cinnamon: обзор среды"
---

Предыдущий очерк мы завершили тем, что после удачной установки отправили
машину на перезагрузку. После которой, проскочив меню GRUB'а (в случае одной
системы по умолчанию оно не выводится), оказываемся в дисплейном менеджере MDM
с предложением авторизоваться:

[ ![Изображение23](http://alv.me/wp-content/img/im_cin_img/cinnamon_001-572x463.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_001.png)

По принятии этого предложения перед нами предстаёт рабочий стол Cinnamon с
экраном приветствия:

[ ![Изображение24](http://alv.me/wp-content/img/im_cin_img/cinnamon_002-572x463.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_002.png) [ ](http://alv.me/wp-
content/img/2014/12/cinnamon_002.png)

И о дисплейном менеджере, и об экране приветствия случай поговорить ещё будет.
Нынешний эе очерк будет посвящён интерфейсу рабочего стола Cinnamon, так как
именно там в основном будет проходить деятельность применителя, избравшего
соответствующую редакцию дистрибутива Mint.

### Cinnamon. Общий вид

При первом своём запуске Cinnamon выглядит более чем традиционно – перед нами
самый обычный рабочий стол с управляющей панелью, на которой имеется кнопка с
подписью Меню (или Menu, в зависимости от локализации):

[ ![Изображение25](http://alv.me/wp-content/img/im_cin_img/cinnamon_003-572x463.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_003.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_003.png)
             
В отличие от GNOME Shell'а или Unity, здесь сразу ясно, что делать дальше. Во-
первых, можно щёлкнуть правой кнопкой мыши по рабочему столу, чтобы увидеть
его контекстное меню:

[ ![Изображение26](http://alv.me/wp-content/img/im_cin_img/cinnamon_004.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_004.png)

Здесь почти всё понятно без комментариев, пару слов можно сказать только про
два пункта:

  * Добавить десклеты – добавление на рабочий стол мини-приложений (подробнее об этом будет сказано в следующем очерке); 

  * Открыть как администратор – вызов, после ввода пароля, файлового менеджера Nemo с правами суперпользователя. 

Во-вторых, щёлкнув правой же кнопкой мыши по свободному полю управляющей
панели, можно заняться её настройками (о чём будет разговор в соответствующем
очерке):

[ ![Изображение27](http://alv.me/wp-content/img/im_cin_img/cinnamon_005.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_005.png)

Или, уже с помощью левой кнопки, вызвать одно из приложений, пиктограммы
запуска которых уже имеются на панели. По умолчанию их не густо – браузер
Firefox, унаследованный от GNOME терминал и файловый менеджер Nemo:

[ ![Изображение28](http://alv.me/wp-content/img/im_cin_img/cinnamon_006.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_006.png)

Но пополнить панель иконками приложений первой необходимости труда не составит
– и со временем я расскажу, как.

Наконец, в-третьих, можно обратиться к главному меню Cinnamon для знакомства
со всем изобилием установленного софта:

[ ![Изображение29](http://alv.me/wp-content/img/im_cin_img/cinnamon_007-572x496.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_007.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_007.png)

Но обзор штатных приложений дистрибутива будет дан в соответствующем очерке.

Как и во всех современных рабочих средах, в Cinnamon'е можно задействовать
несколько виртуальных рабочих столов. В терминах этой среды они называются
рабочими областями (Workspaces), и по умолчанию их два. Переключение между
рабочими областями – комбинациями клавиш `Control+Alt+Right`/`Left`.

Есть и другие способы переключения между рабочими областями, и количество их
можно увеличить до любого разумного предела. Но это относится уже к категории
настроек, которым будет посвящён отдельный очерк.

### Управляющая панель

Если на рабочем столе (точнее, в рабочих его областях) происходят основные
события, то управление этими событиями в значительной мере осуществляется с
панели – в других средах её часто называют главной, или управляющей. Но в
Cinnamon её принято называть без определений, поскольку здесь она обычно
имеется в единственном экземпляре. Хотя в принципе в нём может быть включена и
вторая панель, о чём речь пойдёт в очерке о настройках.

Положение панели по умолчанию – вдоль нижней части экрана, хотя её можно
переместить и наверх. И разделяется она на следующие части (слева направо):

  * кнопка главного меню (опять же – обычно просто Меню);

  * область запуска приложений (Panel Launcher) с пиктограммами – как уже было сказано, по умолчанию их всего три;

  * область открытых приложений (Window list); 

  * область системных сообщений (Notifications); 

  * системный лоток (System Tray), куда помещаются пиктограммы «перманентно работающих» приложений; 

  * несколько пиктограмм разного назначения – список открытых окон (Windows Quick List) и подключаемых накопителей (Removable Drives), модуль сетевых соединений, регулятор громкости, часы, индикатор раскладки клавиатуры, пиктограмма менеджера обновлений. 

[ ![Изображение30](http://alv.me/wp-content/img/im_cin_img/cinnamon_008.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_008.png)

Кроме того, имеется «пользовательская кнопка» – она показывает сведения о
текущем аккаунте, вызывает системные настройки, через неё блокируется экран и
переключаются пользователи, осуществляется вход в так называемый «гостевой»
сеанс, а также выполняется завершение сеанса работы, перезагрузка машины и её
выключение:

[ ![Изображение31](http://alv.me/wp-content/img/im_cin_img/cinnamon_009.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_009.png)

Все области и кнопки панели представляют собой так называемые апплеты – мелкие
программки, не способные к самостоятельному функционированию. Некоторые из
этих апплетов (Panel Launcher, Window list, System Tray) представляют собой
контейнеры для помещёния в них других пиктограмм (запуска, открытых окон, и
так далее), другие же существуют как бы сами по себе.

Апплеты могут добавляться на панель и удаляться с неё. Содержимое апплетов-
контейнеров добавляется или автоматически (System Tray, Window list), или
вручную (Panel Launcher). Удаление апплетов-контейнеров приводит к
исчезновению всего их содержимого. Элементы из лаунчера можно удалять по
одному, содержимое лотка и области приложений – вместе с закрытием
соответствующих программ.

### Главное меню

Центральным (хотя и левым крайним) элементом панели является, безусловно,
главное меню, с которым и настало время ознакомиться подробнее. На первый
взгляд оно ничем не отличается от обычных менюшек «пускового» типа, с их
страшной многоступенчатой иерархией. Однако если вглядеться в соответствующий
скриншот ещё раз – различия обнаруживаются, и весьма существенные:

[ ![Изображение32](http://alv.me/wp-content/img/im_cin_img/cinnamon_010-572x495.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_010.png)

Перво-наперво, обратим внимание на колонку пиктограмм вдоль левого края поля
меню:

[ ![Изображение33](http://alv.me/wp-content/img/im_cin_img/cinnamon_011.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_011.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_011.png)

Набор их в сборке Cinnamon для Mint включает иконки для запуска:

  * браузера Firefox; 

  * менеджера программ mintinstall; 

  * Центра управления (он же – Системные настройки); 

  * терминала; 

  * файлового менеджера Nemo. 

Кроме того, имеются значки блокировки экрана, выхода из сеанса и завершения
работы. Конечно, к последним действиям можно получить доступ и через User
Applet панели, но там его ещё надо разглядеть и до действий докопаться, а тут
они всегда на виду.

Не менее примечательна поисковая строка в верхней части экрана – она
предназначена для поиска приложений. Но не простого, а золотого инкрементного.
То есть, введя в ней последовательность символов libre, мы получим список
только тех пунктов меню, которые её содержат, то есть компонентов LibreOffice:

[ ![Изображение34](http://alv.me/wp-content/img/im_cin_img/cinnamon_012-572x508.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_012.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_012.png)

То есть строка поиска в меню Cinnamon тихо и скромно, без шума и пыли
выполняет ту же функцию, что и пресловутый Dash в Unity (и его аналог в GNOME
3). Правда, с её помощью нельзя устанавливать программы или искать «парнуху» в
Интернете – но не больно-то и хотелось.

А вот искать по русским словам – с некоторыми ограничениями можно. Введя,
например, слово редактор, мы увидим приложения, содержащие его в своём имени:

[ ![Изображение35](http://alv.me/wp-content/img/im_cin_img/cinnamon_013-572x499.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_013.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_013.png)

А на слово текст ответом будет список приложений, содержащих его и в описании:

[ ![Изображение36](http://alv.me/wp-content/img/im_cin_img/cinnamon_014-572x502.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_014.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_014.png)

На мой взгляд, сказанного уже достаточно, чтобы проникнуться величием среды
Cinnamon. Однако это ещё не всё – оно проявляется и в управлении окнами.
Однако прежде чем говорить на эту тему – остановимся на вопросе, как эти окна
открывать.

### Вызов приложений

Открываются окна обычно вместе с запущенными в них приложениями. Способов же
запуска последних в Cinnamon, как и во всех современных десктопах, несколько.

Первый, наиболее универсальный – запуск из командной строки терминала путём
ввода соответствующей команды. Однако обычно полноразмерное терминальное окно
использовать для этого не целесообразно, его вполне можно заменить панелью
мини-терминала – она вызывается обычной для всех десктопов комбинацией клавиш
`Alt+2`:

[ ![Изображение37](http://alv.me/wp-content/img/im_cin_img/cinnamon_015.png)
](http://alv.me/wp-content/img/2014/12/cinnamon_015.png)

До некоторого времени панель мини-терминала в Cinnamon не блистала
функциональностью – в ней не было ни автоподолнения, ни истории команд,
имелась только возможность ввести команду руками или вставить её из буфера.
Однако в Cinnamon 2.6 все эти прелести появились. Историю команд можно, как и
в шелле, просмотреть с помощью стрелок `Up` и `Down`. И автодополнение команды
происходит после набора первых трёх символов её имени, в случае альтернатив
выводя все доступные варианты:

[ ![Изображение38](http://alv.me/wp-content/img/im_cin_img/cinnamon_015a.png)
](http://alv.me/wp-content/img/2015/02/cinnamon_015a.png)

Правда, при вызове панели минитерминала блокируются как любые любые действия
мышью, так и ввод с клавиатуры. Открывается она всегда по центру, и
перемещёнию не поддаётся. Так что пользоваться этой панелью не всегда удобно.
Однако её возможности сполна, а то и с лихвой, заменяются функциями строки
инкрементного поиска в главном меню, о которой только что говорилось. Именно
она становится основным инструментом запуска приложений для тех применителей,
которым, как автору этих строк, проще набрать несколько символов из имени
программы, нежели, подобно Баяну, «мысью рыскать» в её поисках по менюшному
древу. Тем более, что привычные программы, вызываемые давно памятными
командами, в меню, тем более русифицированном, могут носить самые неожиданные
имена, и потому опознаваться с трудом.

Сразу по вызове главного меню мышью или хоткеем (в Cinnamon, как и в Unity,
для этого по умолчанию зарезервирована левая win-клавиша, она же `Super_L`),
строка поиска находится в фокусе ввода, и можно начинать набор имени
приложения. Только нужно помнить про раскладку клавиатуры: как бы ни было
настроено её наследование (о чём речь пойдёт в одном из следующих очерков), в
этой строке она всегда будет наследоваться от раскладки последнего активного
окна, а не от раскладки по умолчанию.

Разумеется, для запуска приложений можно пользоваться и главным меню
непосредственно, тем более что некоторые из них (браузер, терминал, Центр
управления, файловый менеджер), как только что говорилось, вынесены в нём на
отдельную панель в виде кнопок быстрого запуска. А вот остальные программы в
меню уже надо поискать – тем более что, повторяю, там они могут именоваться
весьма причудливо.

Благо, пиктограммы наиболее востребованных приложений из меню можно поместить
в Launcher на главной панели, на рабочий стол или в пункт Избранное. Для этого
достаточно щёлкнуть правой кнопкой на имени нужной программы и из контекстного
меню выбрать требуемый пункт:

[ ![Изображение39](http://alv.me/wp-content/img/im_cin_img/cinnamon_016-572x497.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_016.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_016.png)

Кроме того, иконки приложений можно просто перетаскивать мышью из меню в
Launcher. Причём – сразу в желаемое его место, тогда как при автоматическом
помещёнии иконок они попадают в его конец, и их перетасовка потребует
дополнительных телодвижений.

Как только что было сказано, пиктограммы запуска приложений можно поместить и
на рабочий стол, и запускать их оттуда. Однако я этим способом никогда не
пользуюсь — он кажется мне неудобным, и и рабочего стола у меня обычно не
видать за распахнутыми окнами.

Вот теперь, разобравшись с запуском приложений и открытием вмещающих их окон,
можно переходить и к управлению последними.

### Управление окнами

В предыдущем разделе очерка речь шла о способах запуска приложений, в этом же
поговорим о способах управления приложениями, которые уже запущены. Поскольку
мы (пока ещё) живём в системе, которая официально называется `X Window System`,
то большая часть приложений запускается в её окнах. Так что в основном
применителю придётся иметь дело с ними.

Вид окон с запущенными приложениями зависит от темы рабочего стола, стиля окон
и других индивидуальных настроек. Но по умолчанию они выглядят примерно так:

[ ![Изображение40](http://alv.me/wp-content/img/im_cin_img/cinnamon_017-572x463.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_017.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_017.png)

Управление окнами подразумевает в первую очередь переключение между ними. Что
можно сделать несколькими способами. Первый, напрашивающийся, щелчком любой
кнопкой мыши в области окна. В этом случае окну передаётся фокус и оно, как
принято говорить, «поднимается», то есть оказывается на первом плане. Просто
перевод курсора мыши на другое окно переводит его в фокус (то есть оно может
скроллироваться), но не поднимает.

Как можно видеть на скриншоте, в одной рабочей области может быть открыто
несколько окон, которые могут частично или полностью перекрываться. И тогда
универсальный универсальный способ переключения между окнами, существующий во
всех графических средах, – комбинация клавиш `Alt+Tab`. Удержание её в нажатом
состоянии выводит ленту значков открытых окон, с миниатюрой для окна
активного:

[ ![Изображение41](http://alv.me/wp-content/img/im_cin_img/cinnamon_018-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_018.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_018.png)

Третий способ переключения между окнами – область Window List на управляющей
панели:

[ ![Изображение42](http://alv.me/wp-content/img/im_cin_img/cinnamon_019-572x30.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_019.png)

Есть ещё переход в режим масштабирования рабочей области, но по умолчанию этот
способ отключен, поэтому я вернусь к нему чуть позже.

Сказанное относится к переключению между окнами, расположенными в одной
рабочей области. Но они могут пребывать и в разных областях – как мы помним,
по умолчанию их две. И в этом случае один из способов переключения между ними,
имеющийся «из коробки» – апплет Windows Quick List (в последних версиях
Cinnamon он помещён на панели по умолчанию):

[ ![Изображение43](http://alv.me/wp-content/img/im_cin_img/cinnamon_020-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_020.png)

Второй же – переход в режим Expo через один из «горячих углов», о чём также
будет говориться вскоре.

Теперь посмотрим, что можно делать с самими окнами. В строке заголовка каждого
окна, кроме самого заголовка, в правой его части можно видеть три управляющие
кнопки (слева направо): сворачивания, максимизации/восстановления исходного
размера, закрытия – назначение их очевидно.

Кое-какие манипуляции с окнами можно выполнять и кликами мыши по строке
заголовка. Так, двойной щелчок левой её кнопкой вызывает максимизацию окна,
повторение его – восстанавливает исходный размер. Тот же двойной клик, но уже
правой кнопкой сворачивает окно на панель задач. Для средней кнопки
предусмотрен только одинарный клик – он «опускает» окно на задний план.

Лишь закрыть окно нельзя кликами мыши по строке заголовка. Но это делается
(если не обращаться к штатному меню запущенного в окне приложения) комбинацией
клавиш `Alt+F4` – подобно `Alt+Tab`, она также универсальна для почти всех
графических сред (или вообще всех современных?). Кроме того, закрыть окно
можно из его собственного меню – оно вызывается щелчком правой кнопки мыши по
строке заголовка, и содержит такие пункты:

[ ![Изображение44](http://alv.me/wp-content/img/im_cin_img/cinnamon_021-572x463.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_021.png)

Назначение первых четырёх и последних двух пунктов абсолютно понятно. А вот о
тёх «средних» пару слов сказать можно. Отметка Закрепить на переднем плане –
это запрет перекрытия данного окна другими. А пункты Всегда на видимом рабочем
месте и Только на этом рабочем месте (включён по умолчанию) – альтернативны:
при включении первого окно будет «кочевать» вслед за перемещёниями
пользователя по рабочим областям.

### Тайлинг окон

Всё, что было только что сказано относительно управления окон, не покажется
чем-то необычным применителю любого современного десктопа и приверженцам
подавляющего большинства оконных менеджеров. А вот сейчас речь пойдёт о вещи
более неожиданной – о тайлинге окон. Это – та самая вторая особенность (после
строки поиска в меню), которая столь восхитила меня в Cinnamon'е.

Для начала – пара слов о том, что такое тайлинг. Он основывается на той же
идее, что и консольная утилита screen или двухпанельные файловые менеджеры –
потомки командира Norton'а – расщеплении экрана на ряд независимых областей, в
каждой из которых локализуется окно с запущенным в нём приложением. Это
подобно покрытию пола кафелем (tiling), чем и порождена аллюзия.

При этом понятие управления окнами как бы лишается смысла – тайлинговые
системы управляют не столько окнами, сколько теми самыми областями экрана, в
которых окна открываются. Области эти (в чём-то они похожи на фреймы, некогда
популярные среди web-дизайнеров) могут быть статическими, с жёстко
определёнными размерами, и динамическими, при котором их размеры изменяются
при масштабировании окон запущенных в них приложений. В Cinnamon реализована
первая модель.

Конечно, тайлингом удивить пользователей менеджеров окон типа Awesome
сотоварищи не легче, чем испугать ежа голой... эээ... спиной. Однако во
времена не очень больших экранов я этой идеей не проникса (парадигма «одно
приложение – одна рабочая область» была мне ближе). А ко времени мониторов
больших и широкоэкранных тайлинг подоспел и в десктопах – в Xfce и KDE. Однако
в сравнении с Cinnamon'овским тайлинг в них выглядит что плотник супротив
столяра. Ибо предусматривает расщепление экрана только на две области – по
горизонтали или по вертикали. В Cinnamon'е же возможности тайлинга намного
богаче.

Начать с того, что в Cinnamon'е окна можно «тайлить» не только на поэкрана –
например, по вертикали:

[ ![Изображение45](http://alv.me/wp-content/img/im_cin_img/cinnamon_022-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_022.png)

Или, если хочется, по горизонтали:

[ ![Изображение46](http://alv.me/wp-content/img/im_cin_img/cinnamon_023-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_023.png)

Но есть и «четвертиночный» вариант разбивки экрана:

[ ![Изображение47](http://alv.me/wp-content/img/im_cin_img/cinnamon_024-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_024.png)

А подчас даже

...получается в ответе

Два землекопа и две трети

Примерно как на этом скриншоте:

[ ![Изображение48](http://alv.me/wp-
content/img/im_cin_img/cinnamon_025-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_025.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_025.png)

Тайлинг окон не препятствует существованию на его фоне окон обычных:

[ ![Изображение49](http://alv.me/wp-content/img/im_cin_img/cinnamon_026-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_026.png)

Вот только, к сожалению, средства «тайлить» окна на произвольные области
экрана на предусмотрено. Однако и без этого область его использования
достаточно широка, в чём мы убедимся после рассмотрения средств управления
тайлингом.

### Управление тайлингом

Тайлинг окон может выполняться двумя способами – посредством мыши и с
клавиатуры. Как обычно, первый – легче, то есть «ленивей», второй – быстрее и
эффективней. Замечу в скобках: как обычно, это вовсе не означает оценки в
терминах товарища Маяковского. Иногда «хорошо» – это лениво развалясь в
кресле, елозить мышью по экрану, а иногда – напрягать пальцы рады быстроты
выполнения неких действий.

Рассмотрим сначала тайлинг мышью, выполняемый над окном с положением и
размерами, соответствующими умолчаниям десктопа:

[ ![Изображение50](http://alv.me/wp-content/img/im_cin_img/cinnamon_027-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_027.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_027.png)

При подтаскивании окна мышью к верхней границе экрана оно занимает верхнюю же
его половину:

[ ![Изображение51](http://alv.me/wp-content/img/im_cin_img/cinnamon_028-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_028.png)

Аналогичное движение к нижней границе экрана разворачивает окно на нижнюю его
половину:

[ ![Изображение52](http://alv.me/wp-content/img/im_cin_img/cinnamon_029-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_029.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_029.png)

Перемещёние окна к боковой стороне экрана «тайлит» его на левую

[ ![Изображение53](http://alv.me/wp-content/img/im_cin_img/cinnamon_030-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_030.png)

или правую половины, в зависимости от стороны «подтаскивания»:

[ ![Изображение54](http://alv.me/wp-content/img/im_cin_img/cinnamon_031-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_031.png) [ ](http://alv.me/wp-content/img/2014/12/cinnamon_031.png)

Если передвинуть окно в любой из углов дисплея, оно займёт соответствующую его
«четвертинку»:

[ ![Изображение55](http://alv.me/wp-content/img/im_cin_img/cinnamon_032-572x321.png) ](http://alv.me/wp-content/img/2014/12/cinnamon_032.png)

То есть всё просто, но... Предположим, что при сочинении текста в текстовом
редакторе (или word-процессоре) появилось желание параллельно бросить взгляд
на картину, призванную этот текст иллюстрировать: в этом случае тайлинг
посредством мыши потребует отрыва руки от клавиатуры и переноса её на спину
грызуна. И вот тут-то на помощь и придёт тайлинг с клавиатуры, который
осуществляется комбинацией из двух пальцев – клавиши `Super` (она же – левая
Win) и одной из стрелок управления курсором.

Опять же подвергнем издевательствам исходное окно с умолчальными параметрами.
Комбинация `Super+Right` развернёт её на правую половину экрана, `Super+Left` –
вернёт в исходное состояния. Из которого комбинацией `Super+Left` оно
развернётся на левую половину, а последующий `Super+Right` – возвратит взад. Из
положения «половинка справа» комбинация `Super+Up` превратит окно в
«четвертинку» в правом верхнем углу, `Super+Down` – «четвертинку» в правом
нижнем.

Принцип, я думаю, понятен: `Super` плюс стрелка в любую сторону – окно на
соответствующую половинку экрана, `Super` плюс стрелка в обратную – возврат в
исходное положение, `Super` плюс стрелка из «половинного» состояния – перевод в
состояние «четвертиночное». Запомнить это не сложно, навык до рефлекторного
уровня приобретается очень быстро. А как его можно применить на практике –
сейчас увидим.

### Тайлинг на практике

Всё это очень блаародно – вправе сказать читатель, – но в чём преимущество
тайловых окон перед обычными? Долгое время ответа на этот вопрос у меня не
было, тем более, что я окнами почти не пользовался: во всё ширь каждого
десктопа у меня было открыто одно приложение. Пока не опробовал тайловый режим
– сначала в Xfce 4.10, где он незатейлив, а затем и в среде Cinnamon, в
которой, как я пытался показать на предыдущих страницах, он куда более
изощрён.

Тем не менее, объяснить преимущества тайловых окон над масштабированными
довольно трудно – это надо попробовать самому и оценить. Для меня оно
выразилось в возможности мгновенно перейти от сочинения текста в полноэкранном
режиме к режиму параллельного просмотра текста, иллюстраций к нему, файловой
иерархии и так далее. И сделать это лёгким движением даже не руки, а двух
пальцев.

Причём параллельным просмотром нескольких окон можно не ограничиваться. А,
например, перетаскивать мышью или просто копипастить горячими клавишами
картинки из файлового менеджера или вьювера изображений в word-процессор.
Аналогичным образом можно перетаскивать из теста документации в командную
строку терминала примеры командных конструкций. Или, наоборот, команды или
исходники сценариев – помещать в сочиняемый текст.

Конечно, всё это можно сделать и при традиционном расположении окон, но прошу
поверить на слово брату незабвенного Голубкова:

> Так лучше, Лёня.

В общем, обращение с содержимым окон становится похожим на работу с
двухпанельными файловыми менеджерами a la Midnight Commander. Или даже с
четырёхпанельными: возможно, кое-кому из читателей памятен «пай-мальчик» – Pie
Commander, незаконный четырёхглазый отпрыск командира Norton'а...

Правда, в двух- и тем более в «четырёхплиточной черепице» становится
мучительно больно за бесцельно расходуемое экранное пространство, занятое в
каждом окне строкой меню. И возникает сожаление об отсутствии возможности
встроить его в главную управляющую панель, как это делается по умолчанию в
Unity. Но увы – нет в жизни совершенства, ибо нет в Cinnamon такой
возможности. Иначе он безусловно достиг бы высшей степени совершенства, а его
разработчики имели бы полное право впасть в нирвану.

### Интерфейс Cinnamon: краткий итог

В этом очерке были описаны особенности интерфейса Cinnamon, которые
представляются мне наиболее существенными. Пора подводить итоги.

В своём современном виде Cinnamon наделён всеми функциями, присущими остальным
десктопам. Причём реализованными если не идеально, то близко к тому. А две из
них в сочетании оказываются почти уникальными. Это – строка инкрементного
поиска в меню и развитый тайлинг. Обе они представлены и в Unity, и Xfce, и в
KDE. Но в первой среде пресловутый Dash как раз функционально перегружен,
предусматривая поиск в Интернете не только всякой ерунды, типа программ и
пакетов, но и весьма важной и разнообразной «парнухи». В Xfce строка поиска по
меню как раз зарыта в дебрях её минитерминала. Ну а в KDE эта строка есть
только в «меню современного вида», которое само по себе многим (в том числе и
автору этих строк) представляется неудобным. Что же до тайлинга – как я уже
отметил, его реализация в Cinnamon среди всех десктопов превзойдённа.

При этом всё сказанное в этой части касалось особенностей Cinnamon'а по
умолчанию. Но особенно ярко они заиграют после соответствующих настроек,
которым будут посвящены следующие очерки.

