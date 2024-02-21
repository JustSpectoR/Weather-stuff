# Weather-stuff
sudo mcedit playbook.yml
1) Установка nmap или его обновление
2) Копирование списка сайтов назначения
3) Запуск nmap по скопированному файлу назначений
4) Сбор и вывод результатов

sudo mcedit targets.txt
Здесь сами файлы пунктов назначения

ansible-playbook ./playbook.yml --diff --ask-become-pass
Покажет что изменилось и сделает с sudo (спросив сначала его пароль)