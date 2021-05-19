# VK-Demotivator-Bot
Бот, который создает мемы-демотиваторы из заданого текста и картинки
## Команды

- **<префикс> <перенос на новую строку> фраза 1 <перенос на новую строку>  фраза 2** - делает мем из прикрепленной картинки и текста
## Префиксы:
- **!gen, !d, !ген, !д**
## Пример:
![alt tag](https://sun9-46.userapi.com/impg/rOKfUPNId0kTG4HgBEd2k6bo-A2u6fbKTbSiAg/zzOvqyU0Fy0.jpg?size=527x738&quality=96&proxy=1&sign=ce73bb953119b3c33e70a5a8142ebb46 "Пример тут")

## Настройка бота для группы
Заполняем поля файла **config.py**:
```
TOKEN = '' - токен группы бота
GROUP_ID = - айди группы бота
```

Для получения **айди группы** переходим в нужную группу:
```
-> Управление
-> Настройки
-> Адрес сообщества
-> Номер сообщества
-> club*цифры*
-> Копируем только цифры
```
Для получения **токена группы** переходим в нужную группу:
```
-> Управление
-> Настройки
-> Работа с API
-> Создать ключ
-> Выставляем галочки и создаем
```
Также нужно настроить Long Poll API для бота:
```
-> Управление
-> Настройки
-> Работа с API
-> Long Poll API
-> Long Poll API: Включено + Версия API: 5.92
-> Типы событий
-> Выставляем галочки
```
И последний шаг:
```
-> Управление
-> Сообщения
-> Сообщения сообщества: Включены
-> Настройки для бота
-> Возможности ботов: Включены
-> Разрешать добавлять сообщество в беседы - ставим галочку
```
