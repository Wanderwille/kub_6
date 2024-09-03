# Домашнее задание к занятию «Хранение в K8s. Часть 1» - Подус Сергей

### Задание 1 

**Что нужно сделать**

Создать Deployment приложения, состоящего из двух контейнеров и обменивающихся данными.

1. Создать Deployment приложения, состоящего из контейнеров busybox и multitool.
2. Сделать так, чтобы busybox писал каждые пять секунд в некий файл в общей директории.
3. Обеспечить возможность чтения файла контейнером multitool.
4. Продемонстрировать, что multitool может читать файл, который периодоически обновляется.
5. Предоставить манифесты Deployment в решении, а также скриншоты или вывод команды из п. 4.

------

### Задание 2

**Что нужно сделать**

Создать DaemonSet приложения, которое может прочитать логи ноды.

1. Создать DaemonSet приложения, состоящего из multitool.
2. Обеспечить возможность чтения файла `/var/log/syslog` кластера MicroK8S.
3. Продемонстрировать возможность чтения файла изнутри пода.
4. Предоставить манифесты Deployment, а также скриншоты или вывод команды из п. 2.


## Ответ: 

### Задание 1

1. Манифест находится в папке src

![Scrin 1](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube6/busybox.png)

4. 

![Scrin 2](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube6/multitool.png)

### Задание 2

1. Манифест находится в папке src

![Scrin 3](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube6/demonset.png)

3. 

![Scrin 4](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube6/syslog-data.png)

