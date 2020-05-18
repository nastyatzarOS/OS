## Часть 1
# Начало: установка ОС и настройка RAID и LVM
- Создаем виртуальную мшину с характеристиками: 1gb ram, 1 CPU, 2 hdd - (sdd1, sdd2), SATA контройлер настроен на 4 порта
- Скриншот 1 - настройка разметки дисков
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/1.png)
- Скриншот 2 - первое разделение дисков
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.png)
- Скриншот 3 - указание места для RAID
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.png)
- Скриншот 4 - настройка RAID
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/4.png)
- Скриншот 5 - начало установки и настройки LVM
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/5.png)
- Скриншот 6 - середина настройки LVM
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/6.png)
- Скриншот 7 - конечная настройка и установка LVM
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/7.png)
- Скриншот 8 - результат настройки и установки LVM
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/8.png)
- Скриншот 9 - установка GRUB на первый диск (sda)
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/9.png)
- Скриншот 10 - первая информация о дисках
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/10.png)
- Скриншот 11 - первая информация о RAID
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/11.png)
- Скриншот 12 - первая информация о pvs, vgs, lvs
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/12.png)

## Часть 2
- Скриншот 2.1 - реакция ОС на удаление ssd1
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.1.jpg)
- Скриншот 2.2 - виртуальная машина не работает
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.2.jpg)
- Скриншот 2.3 - проверка статуса RAID после удаления ssd1
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.3.jpg)
- Скриншот 2.4 - реакция виртуальной машины на добавление ssd3
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.4.jpg)
- Скриншот 2.5 - добавление в RAID ssd3
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.5.jpg)
- Скриншот 2.6 - результат в mdstat
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.6.jpg)
- Скриншот 2.7 - результат задания №2
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/2.7.jpg)

## Часть 3
- Скриншот 3.1 - информация о дисках после удаления ssd2
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.1.png)
- Скриншот 3.2 - информация в mdstat после удаления ssd2
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.2.png)
- Скриншот 3.3 - информация после добавления ssd4
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.3.png)
- Скриншот 3.4 - информация после копирования файлов в таблицу на ssd4
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.4.png)
- Скриншот 3.5 - информация после монтирования boot на ssd4
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.5.png)
- Скриншот 3.6 - информация после создания нового RAID массива
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.6.png)
- Скриншот 3.7 - изменение pvs до и после создания zip тома
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.7.png)
- Скриншот 3.8 - информация о дисках после после создания zip тома
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.8.png)
- Скриншот 3.9 - var, root, var находится на md0
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.9.jpg)
- Скриншот 3.10 - результаты после перемещения LV
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.10.png)
- Скриншот 3.11 - информация о дисках только после добавления
всех новых
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.11.png)
- Скриншот 3.12 - информация о дисках после копирования таблицы файлов и sda1
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.12.png)
- Скриншот 3.13 - информация после добавления ssd5 в RAID и увеличения размеров на общих дисках
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.13.png)
- Скриншот 3.14 - размер sda(e)2=md127
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.14.png)
- Скриншот 3.15 - размер VG увеличился
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.15.png)
- Скриншот 3.16 - информация об увеличении размеров root и var
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.16.png)
- Скриншот 3.17 - конечный результат работы с ssd
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.17.png)
- Скриншот 3.18 - информация о дисках после создания логического тома
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.18.png)
- Скриншот 3.19 - информация о дисках после форматирования разделов
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.19.png)
- Скриншот 3.20 - информация о дисках после переформатирования var-логов
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.20.png)
- Скриншот 3.21 - изменение файла fstab
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.21.png)
- Скриншот 3.22 - последняя проверка pvs, lvs, vgs
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.22.png)
- Скриншот 3.23 - последняя проверка и информация о дисках
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.23.png)
- Скриншот 3.24 - последняя проверка о RAID
![Image alt](https://github.com/nastyatzarOS/OS/blob/master/Lab2/screen/3.24.jpg)
