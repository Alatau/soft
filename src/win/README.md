# Читай меня

Список программ и ссылок под Windows и wine.
Преимущество отдано свободному, проверенному, популярному софту.
Программы только бесплатные или с пробными периодами.
Это личные заметки.

## Среды выполнения и библиотеки

Программы нужные для выполнения других программ.

* JDK и JRE от ORACLE.
http://www.oracle.com/technetwork/java/javase/downloads/index.html
	* Для нормальной установки добавить переменные среды:
	```
		В конец Path добавить: %JAVA_HOME%\bin
		
		Создать новые переменные среды:
		JAVA_HOME = c:\Program Files\Java\jdk1.8.0_77
		JDK_HOME = c:\Program Files\Java\jdk1.8.0_77
		JRE_HOME = c:\Program Files\Java\jre1.8.0_77
	```
* python 2.7 https://www.python.org/download/releases/2.7/
	* библиотека, для графических http://www.wxpython.org/
* vcredit (Visual Studio Runtime)
	* Microsoft Visual C++ 2008 Redistributable Package (x86) https://www.microsoft.com/en-us/download/details.aspx?id=29
	* Microsoft Visual C++ 2008 Redistributable Package (x64) https://www.microsoft.com/ru-ru/download/details.aspx?id=15336
	* Visual C++ для Visual Studio 2013  https://www.microsoft.com/ru-RU/download/details.aspx?id=40784

#### Кодеки и библиотеки

* K-Lite Codec Pack - код закрыт, сборка кодеков http://www.codecguide.com/download_kl.htm
* ffmpeg - набор библиотек для конвертации, изменения, сжатия, передачи видео. Нужен для некоторых видеоконвертеров. Но можно и конвертировать просто из командной строки https://ffmpeg.org/download.html
	* Прмер конвертирование: http://stackoverflow.com/questions/13560852/convert-mp4-to-maximum-mobile-supported-mp4-using-ffmpeg
		
## Видео/Аудио

#### Плеера

* VLC - аудио/видео плеер, играет сетевые источники, умеет вещать видео в том числе изображение рабочего стола (в том числе в локальную сеть)
http://www.videolan.org/vlc/download-windows.html
* SMPlayer - более быстрый и стабильный чем VLC, но с менее удобным интерфейсом (оболочка для mplayer), слегка глючный интерфейс
* PotPlayer - код закрыт, но работает гораздо быстрее и стабильнее VLC, а интерфейс удобнее. Он красивее чем SMPlayer
http://potplayer.daum.net/
* Media Player Classic - Home Cinema (MPC-HC) - известный и быстрый плеер https://mpc-hc.org/downloads/
	* Black Edition (MPC-BE) - форк, заявлено больше возможностей, но странный, мало информации, мало обзора отличий, хотя тема о нём есть на официальном сайте Media Player Classic - Home Cinema https://sourceforge.net/projects/mpcbe/

#### Видео редакторы и конверторы

* Shotcut видеоредактор
http://www.shotcut.org/bin/view/Shotcut/Download
* kdenlive
https://kdenlive.org/en/download/

## Графика

#### Редакторы

* Gimp - аналог Photoshop http://www.gimp.org/downloads/
* krita - рисовалка из KDE https://krita.org/en/download/krita-desktop/
* Blender - 3d анимация https://www.blender.org/
* Adobe CS6 (в том числе Photoshop CS6) можно скачать свободно и бесплатно,
но законно использовать их могут только те кто купил ключи
https://helpx.adobe.com/x-productkb/policy-pricing/cs6-product-downloads.html
* LibreCAD - свободная программа для создание чертежей
http://librecad.org/cms/home.html

#### Просмотр и конвертация

* XnView - удобна, код закрыт, просмотр и конвертация http://www.xnview.com

## Сети

#### Браузеры

* Firefox https://www.mozilla.org/en-US/firefox/new/
* Firefox ESR - версия с длительным сроком поддержки https://www.mozilla.org/en-US/firefox/organizations/faq/
* Firefox Developer Edition - для разработчиков https://www.mozilla.org/en-US/firefox/developer/all/
* TorBrowser - обход блокировок, выход в сеть через прокси, отключен сборк статистики
https://www.torproject.org/
* Chromium - на его основе делается Chrome (только x32 версии) https://download-chromium.appspot.com/?platform=Win&type=snapshots
* google chrome, код частично закрыт http://portableapps.com/apps/internet/google_chrome_portable
* Opera - код частично закрыт, зато сжимает трафик, что при тарифах по трафику незаменимо, можно выбрать при установке "установить на USB" и получить портативную версию http://www.opera.com
* Vivaldi - код частично закрыт, много настроек (вкладки вертикально сбоку, поведение и т.д.) https://vivaldi.com/

* Менее официальные браузеры (неизвестно качество):
	* UnGoogled Chromium - вырезан сбор статистики https://github.com/Eloston/ungoogled-chromium/releases

#### Менеджеры загрузок

* Free Download Manager - свободный менеджер загрузок
http://www.freedownloadmanager.org/
* uGet - менеджер загрузок
http://ugetdm.com/downloads
* aria2 - консольная утилита с множеством опций для загрузки
https://aria2.github.io/

#### Торренты

* qbittorrent http://www.qbittorrent.org/

#### Обмен сообщениями

* Pidgin - свободный мессенджер с поддержкой множества форматов, с плагином OTR устойчив к прослушиванию. Через плагины может работать со Skype в текстовом режиме https://pidgin.im/download/
	* множество плагинов для поддержки OTR, Skype, Telegram и т.д. https://developer.pidgin.im/wiki/ThirdPartyPlugins#OfficialPlugins
* Skype - код закрыт, но распостранен очень широко http://www.skype.com/en/download-skype/skype-for-computer/
	* как вариант можно использовать веб версию (в том числе на смартфонах включив "полную версию сайта") https://web.skype.com/
* Viber - код закрыт, аналог Skype http://www.viber.com/en/
* LINE - код закрыт, аналог Skype http://line.me/ru/
* Tox - видеосвязь, код открыт, шифрование данных https://tox.im/
	* Antox - его мобильный вариант для Android https://github.com/Antox/Antox
* Wire - код открыт. Имеет end-to-end шифрование https://wire.com/
* jitsi - клиент XMPP, SIP, видеосвязь, написан на Java https://jitsi.org/
* Linphone - SIP клиент http://www.linphone.org/
* Rambox - одна программа на все мессенджеры (WhatsApp, Messenger, Skype, Telegram и т.д.)
* Vine - код закрыт, может создавать короткие ролики для их добавления в сообщения, интегрироваться с Twitter (владелец: Twitter)
* Instagram - код закрыт, для обмена фото и видео (владелец: Facebook)
* Facebook - код закрыт, для работы с сетью Facebook https://play.google.com/store/apps/details?id=com.facebook.katana
* ВКонтакте - код закрыт, для работы с сетью ВКонтакте https://play.google.com/store/apps/details?id=com.vkontakte.android
* WhatsApp Messenger - код закрыт, популярный мессенджер с заявленным частичным шифрованием https://play.google.com/store/apps/details?id=com.whatsapp
* Telegram - код открыт только для клиента, популярный мессенджер с функциями соц. сети и ботами в чатах, которые могут работать в качестве например торрент сайт. Заявлено шифрование для приватных чатов https://telegram.org/
* Slack - код закрыт, для группового общения и обмена файлами, часто используется в корпорациях https://slack.com/

* Онлайн веб-чаты (в том числе видео):
	* https://room.co
	* https://talky.io/
	* https://appear.in/
	* https://web.skype.com/
	* https://meet.jit.si/
	* https://web.ciscospark.com/#/signin

#### Почтовые клиенты

* Thunderbird https://www.mozilla.org/en-US/thunderbird/
* Claws Mail - легкий почтовый клиент
http://www.claws-mail.org/downloads.php?section=downloads

#### FTP, WebDav, SCP Клиенты

* FileZilla - клиент и сервер для FTP
https://filezilla-project.org/
* WinSCP - клиент SCP, WebDav, FTP. Удобно пользоваться для WebDav https://winscp.net
* Сyberduck - клиент FTP, SFTP, WebDAV, S3, Backblaze B2, Azure & OpenStack Swift, Amazon S3, Google Disk https://cyberduck.io/
	* mountainduck - программа для доп. монтирования дисков, как обычных

#### Удаленное управление

* UltraVNC - подключение удаленного управления по VNC http://www.uvnc.com/downloads/ultravnc.html
	* Mirror Driver - драйвер который должен улучшить передачу (так и не помог) http://www.uvnc.com/downloads/mirror-driver.html
* TeamViewer - код закрыт, удаленное управление, удобная программа https://www.teamviewer.com/ru/
* Steam In-Home Streaming - встроенное в Steam удаленное управление для игр (можно свернуть игру и управлять) http://store.steampowered.com/
* Удаленный рабочий стол Chrome  - (может работать по локалке, но входить нужно через интернет), задержки но видео показывает сносное
https://chrome.google.com/webstore/detail/chrome-remote-desktop/gbchcmhmhahfdphkhkmpfmihenigjmpp?hl=ru
	* дополнительно устанавливается программа на сервер
* PuTTY - SSH клиент с расширенными возможностями
http://www.putty.org/
* KiTTY - более функциональный аналог PuTTY


#### Другое

* youtube-dl - скачивание с youtube.com файлов, файлов плейлистов в различных форматах
и множеств других возможностей https://rg3.github.io/youtube-dl/download.html
(как качать https://forum.mozilla-russia.org/viewtopic.php?id=58848)
* HTTrack Website Copier - скачивание сайтов целиком https://www.httrack.com/
* Wireshark - снифер https://www.wireshark.org/download.html
* Open Broadcaster Software - открытая программа для интернет вещания https://obsproject.com/
	* MonoServer - можно направить поток вещания на него, а к нему подключить множество пользователей (организовать вещание)
* RetroShare - программа для p2p имеет чаты, каналы, форум, обмен файлами, видео звонки (фактически соц. сеть). Обмен происходит только с другими пользователями которым это разрешил лично пользователь (ключи GPG) https://retroshare.github.io/
* ZeroNet - p2p сайты (просмотр сайтов в торрентах) https://zeronet.io/
* https://github.com/MrS0m30n3/youtube-dl-gui - gui для youtube-dl в том числе под windows

## Оффис

#### Текстовые редакторы

* Notepad++ универсальный блокнот, удобен и для программирования https://notepad-plus-plus.org/ <br>
  Плагины:
  * встроенный плагин dspellcheck (установить словари, включить проверку одновременно нескольких языков)
  * TextFx - набор инструментов для преобразования текста в кучу форматов и кодировок, просмотр статистики (количества слов и тд), валидации, вырезания и вставки спец символов, лишних пробелов.
  * цветовая схема для markdown https://github.com/Edditoria/markdown_npp_zenburn
* Atom - убогий и тяжелый редактор, но среди плагинов может попасться что-то интересное https://atom.io
* Visual Studio Code - тяжелый для блокнота, но из него можно сделать IDE через плагины. Поддерживает много форматов файлов, встроенная удобная поддержка markdown, множество удобных плагинов https://code.visualstudio.com
* Geany - аналог Notepad++ http://www.geany.org/Download/Releases  
	Плагины:
	* http://plugins.geany.org/downloads.html
* Vim - текстовый редактор для программистов с удобными сочетаниями клавиш
http://www.vim.org/download.php
* Kate - редактор текста и кода из KDE под Windows (тянет с собой kde и занимает много оперативы) https://kate-editor.org/get-it/
* Sublime Text - код закрыт, редактор кода, отличается хорошей подсветкой языков. В бесплатной версии иногда выскакивает реклама https://www.sublimetext.com/
	
#### Разные

* Sumatra PDF - быстрый просмотрщик PDF, ePub, MOBI, CHM, XPS, DjVu, CBZ, CBR
http://www.sumatrapdfreader.org/free-pdf-reader.html
* WinDjView - быстрый просмотрщик djvu http://windjview.sourceforge.net/
* WinMerge - сравнение документов в двух панельном окне http://winmerge.org/
* CoolReader - чтение книг, версия 2 имеет более удобный и красивый интерфейс https://sourceforge.net/projects/crengine
* FBReader - читалка книг https://ru.fbreader.org/

#### Офисные пакеты

* Microsoft Office Trial пробная версия, код закрыт, но замены нету
https://www.microsoft.com/en-us/evalcenter/evaluate-office-professional-plus-2013
* LibreOffice - свободный оффисный пакет, но многие форматы отображает плохо
https://www.libreoffice.org/download/libreoffice-fresh/
* onlyoffice - ещё один открытый оффис, может лучше читать MS Office документы http://www.onlyoffice.com/ru/download-desktop.aspx
* WPS Office - код закрыт, один из лучших бесплатных офисов https://www.wps.com/

## Диски и файлы

#### Архиваторы

* 7zip - архиватор 7z, zip, tar и др. http://www.7-zip.org/
* 7zip zstd - с поддержкой архиваторов семейства LZ, можно установить целиком или как плагин к 7zip
(т.е. поддерживает больше форматов чем обычный 7zip) https://github.com/mcmilk/7-Zip-zstd
* Universal Extractor - поддерживает множество форматов http://legroom.net/software/uniextract
* PeaZip - свободный архиватор, множество форматов http://www.peazip.org/
* Lessmsi - распаковывает .msi файлы https://github.com/activescott/lessmsi

#### Файловые менеджеры

* Total Commander - двухпанельный менеджер, код закрыт, но с хорошей репутацией http://www.ghisler.com/
	* Тут плагины http://www.ghisler.com/plugins.htm#filesys
	* WebDAV - плагин для работы с webdav
	* Cloud - плагин для работы с яндекс.диск, гугл.диск, box, dropbox, OneDrive
* Double Commander - двухпанельный менеджер, имеется некоторая поддержка плагинов от Total Commander (много нереализованных функций)
http://doublecmd.sourceforge.net/

#### LiveCD/USB

* UNetbootin создание LiveUSB из Linux образа диска для флэшки  https://unetbootin.github.io/
* официальная утилита для создания LiveUSB из Win7 http://www.microsoft.com/en-us/download/windows-usb-dvd-download-tool
* Rufus может создавать установочные LiveUSB в том числе с WinXP https://rufus.akeo.ie/
* GRUB и создание загрузочной Windows флэшки из Ubuntu - Если нужно сделать загрузочный диск с Windows из под Ubuntu (Linux). Можно использовать этот способ и из под Windows, если установить в неё GRUB http://onetransistor.blogspot.com.by/2014/09/make-bootable-windows-usb-from-ubuntu.html

#### Восстановление информации

* TestDisk - консольная утилита восстановления удаленных файлов, фактически единственная свободная
http://www.cgsecurity.org/wiki/TestDisk

#### Эмуляторы дисководов и виртуальные диски

* DAEMON Tools Lite - код закрыт, лучший из бесплатных эмуляторов дисководов
http://www.daemon-tools.cc/rus/downloads
    * ultimate версию с поддержкой полной эмуляции дисковода и скрытием факта эмуляции можно только купить, она платная (хотя пиратские версии есть на торрентах)
* ImDisk Toolkit - это версия с дополнительными опциями (динамическое подстраивание размера виртуального диска под свободную оперативную память, синхронизация файлов с диском при отключении, блокировка выгрузки виртуального диска в файл подкачки и т.д.) от другого разработчика https://sourceforge.net/projects/imdisk-toolkit/
	* ImDisk Virtual Disk Driver - на её основе сделан ImDisk Toolkit, может создавать виртуальный диск в быстрой оперативной памяти http://www.ltr-data.se/opencode.html/
* AMD Radeon™ RAMDisk - код закрыт, может создавать виртуальный диск в оперативной памяти, а при выключении сбросывать его содержимое на диск. Из минусов: сама занимает 100 мб в оперативной памяти, диски больше 4Гб только в платной версии

#### Работа с cd и образами

* InfraRecorder - запись дисков http://infrarecorder.org/?page_id=5

#### Другое

* Ant Renamer - групповое переименование файлов
http://www.antp.be/software/renamer

## Шифрование

#### Менеджеры паролей

* KeePassXC Password Manager https://keepassxc.org

#### Шифрование дисков

* VeraCrypt - шифрует диски целиком или создает шифрованные контейнеры https://veracrypt.codeplex.com/

## Эмуляторы компьютеров, операционных систем, игровых консолей

* VirtualBox - эмулятор компьютера https://www.virtualbox.org/wiki/Downloads
* дополнение для Google Chrome через которое можно запускать программы от Android (.apk) https://developer.chrome.com/apps/getstarted_arc
* qemu - эмулятор, который эмулирует железо, разные архитектуры CPU и т.д.
* libretro - кросс платформенный эмулятор кучи консолей (ROM файлы игр, т.е. игры нужно качать отдельно) http://www.libretro.com/

## Справочники, навигация, энциклопедии, Словари

* GoldenDict - просмотр множества форматов словарей в том числе с произношением (подходят словари и от lingvo, на сегодня лучшие для русскоязычных) http://goldendict.org/download.php
	* Подборка словарей Lingvo для русского (перевод с Fr, De, It, Es) **включая** озвучивание слов и толковый словарь (для установки в GoldenDict просто указать каталог словарей в настройках) https://yadi.sk/d/R9KYaEYJ7utB2

* SAS.Planet - **похоже программа устарела** просмотр карты из разных источников с возможностью загрузки областей и просмотром только кэшированного (оффлайн) плюс множество возможностей http://www.sasgis.org/download
	* Авторы сначало не хотели открывать код, но сам код доступен под GPL v3 (не проверялось) https://bitbucket.org/sas_team/
* Stellarium - планетарий, который создаёт реалистичное трёхмерное небо http://www.stellarium.org/ru/
* Celestia - 3D модель космоса, спутников, звезд, планет, комет, галактик http://www.shatters.net/celestia/
* Google Earth - код закрыт, просмотр карт от google https://support.google.com/earth/answer/168344?hl=ru
	* существует платная версия Google Earth Pro которая может работать с GPS и показывать распечатки более высокого разрешения
* NASA’s Eyes - Код закрыт. Нечто вроде Google Earth, программа от NASA показывает температуру Земли, глубину морей, льды, углекислый газ, информацию о спутниках и солнечной системе и многое другое: https://eyes.nasa.gov

## Мыши, клавиатура, скрипты на жесты и кнопки

* [AutoHotkey](https://autohotkey.com/) - выполняет скрипты для автоматического нажатия мыши и клавиатуры. Есть собственный скриптовый язык. На разных сайтах разбросано множество всевозможных скриптов
* [MKey](http://www.seriosoft.org/) - код закрыт, переназначение клавиш клавиатуры и мыши, назначение на них программ и других действий, работа с дистанционным пультом
* [KeyMagic](https://github.com/thantthet/keymagic) - переназначение клавиш клавиатуры, неудобная настройках
* [SharpKeys](http://sharpkeys.codeplex.com/releases/view/79616) - переназначение клавиш клавиатуры

	
## Система

* Process Explorer - менеджер процессов, код закрыт, официальный
https://technet.microsoft.com/en-us/sysinternals/bb896653.aspx?f=255&MSPPError=-2147217396
* Process Hacker свободная альтернатива Process Explorer
http://processhacker.sourceforge.net/downloads.php
* Autoruns - код закрыт, менеджер автозагрузки программ и служб
https://technet.microsoft.com/en-us/sysinternals/bb963902.aspx
* HWiNFO - код закрыт, аналог Everest и AIDA информация о оборудовании http://www.hwinfo.com/download.php
* CPU-Z - код закрыт, информация о процессоре и смежном оборудовании
http://www.cpuid.com/softwares/cpu-z.html
* GPU-Z - код закрыт, инфа о видеокарте https://www.techpowerup.com/gpuz/
* ext2fsd - драйвер для работы с ext2/3/4 под Windows http://www.ext2fsd.com/
* отключение сбора статистики в Win7-10:
	* https://github.com/10se1ucgo/DisableWinTracking
* Для запуска программ с правами и скриптов администратора http://www.microsoft.com/en-us/download/details.aspx?id=7352
* DNSCrypt - шифруем DNS чтобы провайдер не вмешивался и видел только IP (номер сервера), а не конкретный адрес сайта. Так же провайдер не сможет блокировать сайты просто запретив у себя адрес в DNS https://dnscrypt.org/#dnscrypt-windows
* Набор системных утилит с закрытым кодом от компании **nirsoft**. Очень известный и популярный. http://www.nirsoft.net/utils/
	* Подменяет дату в запущенной программе (программа видит подсунутое её время). Например для браузеров. http://www.nirsoft.net/utils/run_as_date.html
* Chocolatey - пакетный менеджер как apt-get для Windows
	* ChocolateyGUI - Chocolatey с GUI https://chocolatey.org/packages/ChocolateyGUI
* FurMark - код закрыт, тест производительности видеокарты через OpenGL http://www.geeks3d.com/dlz/
* GPU Caps Viewer - код закрыт, информация о видео карте http://ozone3d.net/gpu_caps_viewer/
* CrystalDiskInfo - тест скорости записи и чтения на любой носитель http://crystalmark.info/download/index-e.html
* LICEcap - сделать анимированный GIF с записью экрана http://www.cockos.com/licecap/
* [ShareX](https://getsharex.com/downloads/) (Windows) - скриншоты, запись экрана (в том числе в gif или видео), линейка, выбор цвета, встроенный редактор скриншотов и д.р.

## Компоненты операционных систем

Microsoft удалила файлы по некоторым ссылка. Смотрите старую версию страниц по ссылка ниже в архиве https://web.archive.org и ищите по названиям и номерам версии файлов на сайте http://www.catalog.update.microsoft.com/Search.aspx?q=hotfix

* DirectX (в Win7 и выше устанавливать через систему обновлений)
https://www.microsoft.com/ru-ru/download/details.aspx?id=34429
* исправление долгого обновления Win7
	* для x32 https://www.microsoft.com/en-us/download/details.aspx?id=49542
	* для x64 https://www.microsoft.com/en-us/download/details.aspx?id=49540
	
* на самом деле дополнительный Direct X для Win 7 устанавливается по этой ссылке: https://www.microsoft.com/ru-ru/download/details.aspx?displaylang=ru&id=35

* сглаживание шрифтов для Win XP https://www.microsoft.com/typography/ClearTypePowerToy.mspx
* драйвер файловой системы exFAT для Win XP https://www.microsoft.com/ru-RU/download/details.aspx?id=19364

* Официальная сборка обновлений по апрель 2016 для Win 7 SP1
	* Фикс для установки этой сборки https://support.microsoft.com/en-us/kb/3020369
	* Win7 x64 http://download.windowsupdate.com/d/msdownload/update/software/updt/2016/05/windows6.1-kb3125574-v4-x64_2dafb1d203c8964239af3048b5dd4b1264cd93b9.msu
	* Win7 x86 http://download.windowsupdate.com/d/msdownload/update/software/updt/2016/05/windows6.1-kb3125574-v4-x86_ba1ff5537312561795cc04db0b02fbb0a74b2cbd.msu
	* после обновления можно отключить телеметрию. ТЕЛЕМЕТРИЯ ПРИЛИЧНО ЗАМЕДЛЯЕТ Win7!!! (незаметно на мощных компах)
		* http://www.overclock.net/t/1587577/windows-7-updates-list-descriptions-windows-7-8-telemetry-preparation
		* http://techne.alaya.net/?p=12499
		* http://www.dslreports.com/forum/r30348398-WIN7-Win-7-updates-to-avoid-or-be-careful-with
		
* Platform Update for Windows 7 - обновление нужно для улучшения работы GPU и некоторых программ. Оно не входит в комулятивный набор обновлений (описан выше) - https://www.microsoft.com/en-us/download/details.aspx?id=36805
* Отдельные официальные hotfix (исправления) которые больше недоступны на обычном сайте Microsoft http://www.catalog.update.microsoft.com/Search.aspx?q=hotfix

## Операционные системы

* Tails - максимально анонимная система с установленными программами
для анонимного общения и работы с сетями https://tails.boum.org/
запускать рекомендуется в эмуляторах (например VirtualBox)
или с загрузочных дисков.
* Whonix - дистр. для анонимности специально подготовленный для запуска в виртуалке https://www.whonix.org/

* Linux - в linux есть утилита gparted для разметки дисков (никогда не пользуйте разметку в windows!), утилита testdisk для восстановления файлов и систем, fdisk может исправить некоторые ошибки и изменить порядок нумерации разделов при проблемах с ними. Утилитой dd можно забэкапить диски с ошибками (имеют команду игнорирования ошибочных секторов). Чтобы проверить диск на ошибки после разметки наберите команду: ```sudo fdisk -l```
	* Kubuntu - самый удобный, но чуть глючный и чуть медленнее http://www.kubuntu.org/getkubuntu
	* xubuntu x86 - лучшее для LiveCD, запускается хорошо на старых компах
	* xubuntu x64 - быстрее всех для десктопа
	* LinuxMint x64 (есть редакции xfce, kde) - тоже самое что ubuntu, но больше предуастановленного софта
* Windows
	* Пробные версии Windows <br>
	http://www.microsoft.com/en-us/evalcenter/evaluate-windows-enterprise-insider-preview <br>
	пробная версия Win7 <br>
	http://care.dlservice.microsoft.com/dl/download/evalx/win7/x86/EN/7600.16385.090713-1255_x86fre_enterprise_en-us_EVAL_Eval_Enterprise-GRMCENEVAL_EN_DVD.iso <br>
	http://care.dlservice.microsoft.com/dl/download/evalx/win7/x64/EN/7600.16385.090713-1255_x64fre_enterprise_en-us_EVAL_Eval_Enterprise-GRMCENXEVAL_EN_DVD.iso
	* сравнить хэш суммы Windows из этого списка https://msdn.microsoft.com/ru-ru/subscriptions/downloads/default.aspx
	* Официальные бесплатные версии Windows для VirtualBox
	http://dev.modern.ie/tools/vms/windows/
	* Windows 10 Enterprise LTSB *Evaluation* x86
	http://care.dlservice.microsoft.com/dl/download/6/2/4/624ECF83-38A6-4D64-8758-FABC099503DC/10240.16384.150709-1700.TH1_CLIENTENTERPRISE_S_EVAL_X86FRE_EN-US.ISO
	* Windows 10 Enterprise LTSB *Evaluation* x64
	http://care.dlservice.microsoft.com/dl/download/6/2/4/624ECF83-38A6-4D64-8758-FABC099503DC/10240.16384.150709-1700.TH1_CLIENTENTERPRISE_S_EVAL_X64FRE_EN-US.ISO
	* для восстановление Wi10 Eval может понадобиться оффициальный ключ VTNMT-2FMYP-QCY43-QR9VK-WTVCK
	
	* Win 10 Enterprise Eval, build от числа: 20 September 2016 http://care.dlservice.microsoft.com/dl/download/2/5/4/254230E8-AEA5-43C5-94F6-88CE222A5846/14393.0.160715-1616.RS1_RELEASE_CLIENTENTERPRISEEVAL_OEMRET_X64FRE_EN-US.ISO

