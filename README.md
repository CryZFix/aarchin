# Описание
Этот скрипт не задумывался, как обычный установочный с большим выбором DE, разметкой диска и т.д. И он не предназначет для новичков. Он предназначет для тех, кто ставил ArchLinux руками и понимает, что и для чего нужна каждая команда. 

Его цель - это моментальное разворачиванеи системы со всеми конфигами. Смысл в том что, все изменения вы делаете предварительно в самом скрипте и получаете возможность быстрой установки ArchLinux с вашими личными настройками.

Изначальный автор скрипта по ссылке https://github.com/ordanax/

Видео с демонстрацией работы скрипта https://www.youtube.com/watch?v=nvVF_qKDUeM

# Установка 
1) Скачать и записать на флешку ISO образ Arch Linux https://www.archlinux.org/download/
2) Скачать и запустить скрипт командой:

   ```bash 
   wget git.io/al_fast_installer.sh && sh al_fast_installer.sh
   ```
   или
   
    ```bash
   curl -OL git.io/al_fast_installer.sh && sh al_fast_installer.sh
   ```

# ВНИМАНИЕ!
Автор не несет ответственности за любое нанесение вреда при использовании скрипта. Используйте его на свой страх и риск или изменяйте под свои личные нужды.

Скрипт затирает диск dev/sda в системе. Поэтому если у вас есть ценные данные на дисках сохраните их. Если вам нужна установка рядом с Windows, тогда вам нужно предварительно изменить скрипт и разметить диски. В противном случае данные и Windows будут затерты.

Если вам не подходит автоматическая разметка дисков, тогда вам, предварительно нужно сделать разметку дисков и настроить скрипт под свои нужды (программы, XFCE config и т.д.)
Смотрите пометки в самом скрипте.

# В разработке принимали участие:
Алексей Бойко https://vk.com/ordanax

Степан Скрябин https://vk.com/zurg3

Михаил Сарвилин https://vk.com/michael170707

Данил Антошкин https://vk.com/danil.antoshkin

Юрий Порунцов https://vk.com/poruncov

# Контакты
Наша группа по Arch Linux https://vk.com/arch4u
