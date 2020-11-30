LauncherRuntime
---------------------
В данном репозитории находятся файлы нашего рантайма для GravitLauncher. Протестированная версия лаунчера - 5.1.8, работа на более поздних версиях не гарантируется.

### Установка

Клонируем репозиторий и перемещаем рантайм в лаунчер

```sh
$ cd ${launcherdir}/srcRuntime
$ mv runtime runtime_old
$ git clone https://github.com/RangeMC/runtime
```
:information_source: Плейсхолдер `${launcherdir}` нужно заменить на путь к лаунчеру.

Собираем лаунчер с новым рантаймом

```sh
$ screen -x ${screen}
$ build
```

:information_source: Плейсхолдер `${screen}` нужно заменить на название скрина лаунчсервера.

### Итоговый результат

![javaw_8m6jfq6Lnt](https://user-images.githubusercontent.com/47789168/100612890-ba28b000-3324-11eb-80a2-0ed28b818b3a.png)

