ДЗ № 2: работа с mdadm
  Описание домашнего задания
  1) добавить в Vagrantfile еще дисков
  2) сломать/починить raid;
  3) собрать R0/R5/R10 на выбор;
  4) прописать собранный рейд в конф, чтобы рейд собирался при загрузке;
  5) создать GPT раздел и 5 партиций.

Для проверки представлен Vagrantfile и скрипт build-raid.sh.
В Vagrantfile добавлено 4 sata диска и пропискан скрипт (build-raid.sh) для сборки из этих дисков raid10. 
В скрипт build-raid.sh добавлены комментарии с описанием комманд.
Добавил конфигурационные файлы виртуальной машины mdadm.conf и fstab.
