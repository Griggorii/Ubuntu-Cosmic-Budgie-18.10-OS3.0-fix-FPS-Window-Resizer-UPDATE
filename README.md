# Ubuntu 16.04 (не для 18.10)

Download etc.zip https://github.com/Griggorii/Ubuntu-Cosmic-Budgie-18.10-OS3.0-fix-FPS-Window-Resizer-UPDATE/blob/master/etc.zip

Run terminal command

sudo rm -rf /etc/X11/xorg.conf.d

sudo rm -rf /etc/xdg/autostart

Replace inpack in / zip etc.zip  

/etc/X11/xorg.conf.failsafe

/etc/default/grub

/etc/xdg/autostart

Firefox fix tutorial https://www.youtube.com/watch?v=nlJFJchdNVI

su

&& update-initramfs -u && update-grub

Reboot

На 16.04 можно поставить самый новый Kodi TV как поставить ниже

Kodi TV 18.0 

sudo apt purge kodi

sudo apt remove --purge kodi kodi-bin

sudo apt purge kodi kodi.bin

sudo add-apt-repository ppa:team-xbmc/unstable

rm -rf ~/.kodi

rm -rf /usr/lib/x86_64-linux-gnu/kodi/

sudo update && sudo apt install kodi

Мой конфиг для kodi https://www.youtube.com/watch?v=_p5mTuj_Etc 

Kodi TV 18.0 FIX Python cryptography fix https://www43.zippyshare.com/v/zP9bjO29/file.html

Youtube My Opera Html5 https://www26.zippyshare.com/v/060fcm9r/file.html https://www.youtube.com/html5 если на ютубе типа будет говорить что у вас в моей 16.04 нету html 5 , запускать с бинарника opera поставив в свойствах запуска как программы или командой chmod новая опера у них почему то не показывает html5 , а моя показывает , но учтите должна быть моя сборка https://www.youtube.com/watch?v=e3EGMEC1wqA

Opera можно заменить в /usr/lib/x86_64-linux-gnu/ но тогда гит хаб перестает редактироваться , значит придётся так пока пользоваться пока не выпустят вот такую opera как я дал с поддержкой html5 и допилят поддержку git

Я скомпилировал Pulse Effects новой версии и по идее должно работать и на 16.04 https://www.youtube.com/watch?v=Z5E2Bsou0Nw скачать подключить flatpak репы и потом сделать как на видео , на сколько я помню из тем только принимает адвйту темную , но видел что когда манжаро прибрала у них уже и темы работали

В общем по скорости мой дистрибутив 16.04 обгоняет другие , надо делать из моего дистрибутива новинку , а другие пока отложить так как там невероятные торможения в браузере при открытии нескольких вкладок и вообще по скорости даже если в игры кто будет играть на слабой машине то это лучший вариант 16.04 это не говоря про посмотреть видео.
Я начинал делать свои дистр так это с команд на 17.10 tar cvpjf backup.tar.bz2 --exclude=/proc4 --exclude=/mnt --exclude=/sys / --exclude=/lost+found --exclude=/tmp --exclude=/backup.tar.bz2 и раскатывал на это на 16.04 потом видимо попало в руки тех кто сделал этот дистрибутив под свой бренд , но уже более тормознутый , а надо было держаться моего подхода и дать мне всю копилку что бы я раскидывал деньги на задания и тогда бы получилась операционка будущего , а так пусть сами занимаются оно и понятно там все зависимости сместились и mime выдавало тоже сдвиг ассоциации хотя за счет этой технологии может быть и нашлось что то лучшее , вот это получено в ходе моих экспериментов сошедшей с рельс программы текстового редактора germinate https://drive.google.com/file/d/1FnNW0cy2FSqpQ9BhhNm143SN4C_BRbFx/view

Итог получили копилочку которую едят не те люди замедляющие работу над сверх легкой оболочкой как у андроида , своей оберткой поверх что бы выдать как хау ноу.
