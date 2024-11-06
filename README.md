# kvas-allow-domains

Список доменов для настройки маршрутизации через [KVAS](https://github.com/qzeleza/kvas) для роутеров Keenetic
Источник диапазонов [rockblack](https://rockblack.su/vpn/dopolnitelno/diapazon-ip-adresov)

# Импорт на роутер

Для импорта списка на роутер с поддержкой KVAS

    cd /tmp && curl -O https://raw.githubusercontent.com/subbotaaa/kvas-allow-domains/main/ip.lst && kvas import ip.lst

    cd /tmp && curl -O https://raw.githubusercontent.com/subbotaaa/kvas-allow-domains/main/twitter.lst && kvas import twitter.lst
