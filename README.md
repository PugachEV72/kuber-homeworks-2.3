# Домашнее задание к занятию `«Конфигурация приложений»` - Пугач Евгений.


---

## `Задание 1. Создать Deployment приложения и решить возникшую проблему с помощью ConfigMap. Добавить веб-страницу`

1. Создать Deployment приложения, состоящего из контейнеров nginx и multitool.
2. Решить возникшую проблему с помощью ConfigMap.
3. Продемонстрировать, что pod стартовал и оба конейнера работают.

### Ответ:

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2024-05-06_00-12-43.png)

4. Сделать простую веб-страницу и подключить её к Nginx с помощью ConfigMap. Подключить Service и  
   показать вывод curl или в браузере.
5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.

### Ответ:

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2024-05-06_00-13-14.png)

[Ссылка на Deployment](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/deployment-nginx-multi.yaml)

[Ссылка на ConfigMap](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/configmap-nginx.yaml)

[Ссылка на Service](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/service-nginx.yaml)

---

## `Задание 2. Создать приложение с вашей веб-страницей, доступной по HTTPS`

1. Создать Deployment приложения, состоящего из Nginx.
2. Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
3. Выпустить самоподписной сертификат SSL. Создать Secret для использования сертификата.

### Ответ:

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2024-05-06_03-01-08.png)

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2024-05-06_03-01-47.png)

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2024-05-06_03-02-47.png)

4. Создать Ingress и необходимый Service, подключить к нему SSL в вид. Продемонстировать доступ к приложению по HTTPS.
5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.

### Ответ:

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2024-05-06_02-55-39.png)

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2024-05-06_02-49-40.png)

[Ссылка на Deployment](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/deployment-nginx.yaml)

[Ссылка на Secret](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/nginx-secret.yaml)

[Ссылка на Ingress](https://github.com/PugachEV72/kuber-homeworks-2.3/blob/main/ingress-nginx.yaml)

---



