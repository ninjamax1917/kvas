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

**Качаем рабочую версию**
curl -sOfL https://github.com/qzeleza/kvas/blob/main/ipk/kvas_1.1.9-beta_3_all.ipk

**Запускаем установку**
opkg install

**После перезагрузки настраиваем заново**
kvas setup
