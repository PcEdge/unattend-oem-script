# Цель проекта
Главная задача проекта - создать универсальный файл autounattend.xml, с помощью которого можно упростить установку Windows. Файл должен быть совместимым с Windows 7, 8, 8.1, 10, 11, а также совместим как с x86 так и x86_64 системами.

# Описание
Скрипт для автоматизации установки Windows 11. Сделано с помощью https://schneegans.de/windows/unattend-generator/
Особенности:
- Скрытие и отключение новостей и интересов на панели задач
- Установка обоев
- Установка курсора
- Установка приложения
- Установка информации о производителе
- Добавлена функция "Стать владельцем" в контекстное меню
- Включение отключения питания USB устройства при извлечении
- Отключение автоматической перезагрузки при BSOD

# Папка $OEM$
Для правильной работы скрипта требуется папка $OEM$, которая должна находится в папке "sources" в ISO образе.
В ней имеются доп. файлы и инсталляторы приложений.
