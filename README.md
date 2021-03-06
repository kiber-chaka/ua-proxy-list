# Список сайтов, заблокированных в Украине (для [SwithyOmega](https://github.com/FelisCatus/SwitchyOmega))
[![GitHub license](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://raw.githubusercontent.com/Psykukumber/ua-proxy-list/master/LICENSE) [![Twitter feedback](https://img.shields.io/badge/feedback-twitter-blue.svg)](https://twitter.com/psykukumber) [![Telegram feedback](https://img.shields.io/badge/feedback-telegram-blue.svg)](https://t.me/psykukumber)

Данный список предназначен для использования в програмной связке Chromium/Firefox + [SwithyOmega](https://github.com/FelisCatus/SwitchyOmega) + [Shadowsocks](https://shadowsocks.org). С его помощью проксируется трафик только к заблокированным сайтам, в то время, как ко всем остальным - идет напрямую.

## Использование

_Только для Chrome. Если вы пользуетесь Firefox, используйте [эту инструкцию.](https://github.com/Psykukumber/ua-proxy-list/wiki/Firefox-Configuration)_

### Первый способ 

1. Установите [SwithyOmega](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif) и пропишите в него адрес вашего SOCKS5-прокси
2. Откройте настройки SwitchyOmega > Profiles > auto proxy
3. Нажмите кнопку "Add a rule list". В разделе "Switch Rules" найдите графу "Rule list rules" и выберите ваш профиль прокси.
4. В поле "Rule List URL" вставьте ссылку:
```
https://raw.githubusercontent.com/Psykukumber/ua-proxy-list/master/sites.sorl
```
затем нажмите "Apply changes"

5. Переключите активный профиль на "auto switch"

### Второй способ

1. Установите [SwithyOmega](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif) и пропишите в него адрес вашего SOCKS5-прокси
2. Откройте настройки SwitchyOmega > Profiles > auto proxy
3. Нажмите кнопку "Add a rule list". В разделе "Switch Rules" найдите графу "Rule list rules" и выберите ваш профиль прокси.
4. В поле "Rule List Text" вставьте содержимое из файла sites.sorl, затем нажмите "Apply changes"
5. Переключите активный профиль на "auto switch"

_Обратите внимание, что для первого способа доступна возможность автоматического обновления. Расширение будет переодически проверять список по ссылке и самостоятельно его обновлять. В случае со вторым способом вам придется обновлять список самостоятельно._

## Что делать, если в списке не хватает какого-то сайта?

Вы можете открыть новый тикет в багтрекере или направить мне пулл реквест и я постара.сь добавить новый сайт в список как можно скорее. Если же вы не хотите ждать, то можете добавить сайт самостоятельно в настройках расширения.

## У меня есть вопрос...

Напишите мне в [Твиттер](https://twitter.com/psykukumber) или [Телеграм](https://t.me/psykukumber)

## Отказ от ответственности

ФАЙЛЫ В ЭТОМ РЕПОЗИТОРИИ РАСПРОСТРАНЯЕТСЯ В ФОРМАТЕ "КАК ЕСТЬ". ИСПОЛЬЗУЯ ДАННЫЕ СПИСКИ, ИНСТРУКЦИИ ИЛИ ИХ ЧАСТИ ВЫ СОГЛАШАЕТЕСЬ С ТЕМ, ЧТО ОСОЗНАЕТЕ ВСЕ ВОЗМОЖНЫЕ ПОСЛЕДСТВИЯ И ИСПОЛЬЗУЕТЕ ИХ НА СОБСТВЕННЫЙ СТРАХ И РИСК. АВТОР НЕ НЕСЕТ ОТВЕТСТВЕННОСТИ ЗА ПОТЕРЮ ДАННЫХ, ВЗЛОМЫ УЧЕТНЫХ ЗАПИСЕЙ, ВЫХОД ОБОРУДОВАНИЯ ИЗ СТРОЯ, ПРОБЛЕМЫ С ПРАВООХРАНИТЕЛЬНЫМИ ОРГАНАМИ И СПЕЦСЛУЖБАМИ, ТЕРРОРИСТИЧЕСКТЕ АКТЫ, ВОЙНЫ, ЗЕМЛЕТРЯСЕНИЯ, НАВОДНЕНИЯ, ЦУНАМИ, РЕВОЛЮЦИИ, МАССОВОЕ ВЫМИРАНИЕ РЫБЫ, СМЕРТЬ ВАШЕЙ СОБАКИ, ВТОРЖЕНИЕ ИНОПЛАНЕТЯН, ОСКОРБЛЕНИЯ В ТВИТТЕРЕ, ИЗБРАНИЕ ПРЕЗИДЕНТОМ ИДИОТА, ПРЕЖДЕВРЕМЕННОЕ НАЧАЛО СУДНОГО ДНЯ, КОЛЛАПС СОЛНЦА В ЧЕРНУЮ ДЫРУ, ТЕПЛОВУЮ СМЕРТЬ ВСЕЛЕННОЙ А ТАКЖЕ ПОЛНУЮ НЕСПОСОБНОСТЬ ПРОЧИТАТЬ И ОСОЗНАТЬ НАЗНАЧЕНИЕ, СМЫСЛ И СУТЬ ДАННОЙ ИНСТРУКЦИИ И ЛЮБЫЕ ДРУГИЕ ВОЗМОЖНЫЕ ПОСЛЕДСТВИЯ.
