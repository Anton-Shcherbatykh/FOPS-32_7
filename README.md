# Домашнее задание к занятию "Кластеризация и балансировка нагрузки" - `Щербатых А.Е.`
## Задание 1
Запустите два simple python сервера на своей виртуальной машине на разных портах

Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](https://github.com/netology-code/sflt-homeworks/blob/main/2)

Настройте балансировку Round-robin на 4 уровне.

На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### Выполнение
1. Два simple python сервера запущены
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_7/blob/main/screenshots/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.jpg)
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_7/blob/main/screenshots/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_2.jpg)
2. Установлен и запущен HAProxy, но при внесении изменений в конфигурационный файл (прилагаю) возникает ошибка (см.скрин).
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_7/blob/main/screenshots/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_3%20%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B0.jpg)
   Читал статью тут [ссылка](https://www.haproxy.com/blog/how-to-enable-health-checks-in-haproxy) - никаких упоминаний, что что-то сделал не так.
   Прошу помочь разобраться с проблемой. Видео лекции пеерсмотрел несколько раз.
