# kvas

cd /tmp && curl -O https://raw.githubusercontent.com/ninjamax1917/kvas/refs/heads/main/main/list.lst && kvas import list.lst

**Удаляем старую версию**
kvas uninstall full

**Удаляем "битый" билд**
opkg remove kvas

- reboot

**Переходим в tmp**
cd /opt/tmp

**Очищаем**
rm -i \*

или

find /opt/tmp -type f -delete

**Запускаем установку**
opkg install

**После перезагрузки настраиваем заново**
kvas setup

**Может быть полезен**
kvas reset
