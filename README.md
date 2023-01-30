# Верстаем видеоплеер
Данный проект находится в разработке, вы можете ознакомиться с плеером по [ссылке](https://norgius.github.io/layout_video_player/player/index.html). Он проигрывает стандартное видео, ссылка на которое зашита в `js код`.

## Разработка
Для удобства последующей разработки можете запустить плеер через `Python` библиотеку.

Вам потребуется `Python3` (версии не ниже `3.6`). Установите необходимые зависимости командой:
```
pip install -r requirements.txt
```
Для запуска сайта в режиме отладки перейдите в корневую директорию проекта и запустите в консоли команду:
```
livereload -p 8000 player/
```
Теперь `плеер` будет работать по адресу http://127.0.0.1:8000/ и вы сможете вносить изменения в код и сразу видеть изменения.