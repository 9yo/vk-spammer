# Vk-spammer
Просто спаммер...
Установка спаммера:

```
pip install vk-spammer
```

### Запуск

```
vk-spammer
```

В скрипте укажите свой логин и пароль от ВК. Далее, Вас спросят, хотите ли вы сохранить свои данные для входа, чтобы в будущем не вводить их снова.
После всего этого вас спросят id пользователя, которого вы хотите заспамить. Атака началась.

Чтобы удалить данные авторизации, запустите спаммер с параметром -r.

### Изменение сообщений

Чтобы изменить сообщения, которые спамер будет отправлять, запустите спаммер с аргументом -e (--editmessages)

```
vk-spammer -e
```

Это запустит текстовый редактор (На Windows это будет блокнот, на Linux это будет nano).
Каждая строчка текста будет отдельным сообщением.

### Изменение задержки

По умолчанию, задержка между сообщениями равна 4 секундам. Чтобы поменять этот параметр, при запуске спаммера, укажите колисчество секунд задержки через параметр -d (--delay)

```
vk-spammer -d 4
```

Удачи.
