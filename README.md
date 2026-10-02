Forza Horizon 6 - DLSS Frame Generation на RTX 20
Сборка: upstream dlssg_for_sm86 0.3.5, runtime 310.1

Файлы в этой папке
- version.dll - прокси-загрузчик Frame Generation
- dlssg_sm86.ini - настройки мода

Установка вручную
1. Полностью закройте Forza Horizon 6.
2. Скопируйте version.dll и dlssg_sm86.ini в папку с forzahorizon6.exe.
3. Запустите игру через Steam.
4. В настройках графики включите NVIDIA DLSS Frame Generation. На RTX 20 серия может быть обозначена как DLSS Frame Generation; предел сборки 310.1 - до 4x.

Важно
Используйте именно эти два файла. Не копируйте dinput8.dll и файлы старого dlssg_for_sm75: прежний вариант вызывал аварийный сбой FH6.

Откат
Закройте игру и удалите из папки игры version.dll и dlssg_sm86.ini. Оригинальный nvngx_dlssg.dll игры этим набором не заменяется.

Источник сборки и история выпусков:
https://github.com/sdli1995/dlssg_for_sm86/releases/tag/0.3.5
