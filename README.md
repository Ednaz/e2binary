# e2binary

Поддержка https://tvfaq.net && https://gisclub.tv && https://giclub.tv

#### Бинарники предназначены для поддержки модулей CI+ на официальных имиджах OpenPli https://openpli.org/download/ 

## Поддерживаемые модели ресиверов:

* gi et11000
* gbquad4k
* gbue4k 
* lunix3-4k
* lunix4k
* vuduo
* vuduo2
* vuduo4k
* vusolo
* vusolo2
* vusolo4k
* vusolose
* vuultimo
* vuultimo4k
* vuuno
* vuuno4k
* vuuno4kse
* vuzero4k

Для замены бинарника останавливаем энигму командой в телнет `init 4`

Меняем бинарник по пути `/usr/bin/` , проверяем права у бинарника `755`

Файл `enigma.pyo` ложим по пути `/usr/lib/enigma2/python/`

Для ресиверов gi et11000, gbquad4k, gbue4k, lunix3-4k, lunix4k, vuduo, vusolo, vuultimo, vuuno
скопируйте сертификаты в `/etc/ssl/certs/` и присвойте им права **777**

Далее reboot

Для автоматической установки используем установочный пакет

![enigma2-plugin-systemplugins-ciplusinstall_1.6-r0-openpli_7.0-release_7.1-release_all.ipk](https://github.com/Ednaz/e2binary/blob/master/enigma2-plugin-systemplugins-ciplusinstall_1.6-r0-openpli_7.0-release_7.1-release_all.ipk?raw=true)

#### Не забываем делать привязку модуля по провайдеру в плагине commoninterfaceassignment, если используем ЭМУ.
