#INSTALL
---------

1. Скопируйте файлы проекта в директорию вашего HTTP сервера.

2. Установите права на запись для папки collector/data для пользователя от которого запущен HTTP сервер.

3. Отредактируйте файл config.php

4. В конфигурации monit (https://mmonit.com/monit/documentation/monit.html#MANAGE-YOUR-MONIT-INSTANCES) укажите путь для отправки данных:

set mmonit http://ip-or-hostname-of-the-web-server/mMonit-free/collector/index.php