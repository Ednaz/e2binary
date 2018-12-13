# e2binary
Поддержка https://tvfaq.net && https://gisclub.tv && https://giclub.tv

Бинарники предназначены для поддержки модулей CI+ на официальных имиджах OpenPli https://openpli.org/download/
Поддерживаемые модели ресиверов:
gi et1x000;
lunix3-4k;
vuduo;
vuduo2;
vuduo4k;
vusolo;
vusolo2;
vusolo4k;
vusolose;
vuultimo;
vuultimo4k;
vuuno;
vuuno4k;
vuuno4kse;
vuzero4k

Для замены бинарника останавливаем энигму командой в телнет init 4

Меняем бинарник по пути /usr/bin/ , проверяем права у бинарника 755

Файл enigma.pyo ложим по пути /usr/lib/enigma2/python/

Далее reboot

Не забываем делать привязку модуля по провайдеру в плагине commoninterfaceassignment, если используем ЭМУ.

В файле srcdate прописана дата компиляции бинарника, его копировать в ресивер не нужно.
