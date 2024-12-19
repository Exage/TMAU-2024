<p align="center">Министерство образования Республики Беларусь</p>
<p align="center">Учреждение образования</p>
<p align="center">«Брестский государственный технический университет»</p>
<p align="center">Кафедра ИИТ</p>
<br><br><br><br>
<p align="center">Лабораторная работа №3</p>
<p align="center">По дисциплине “ТиМАУ”</p>
<p align="center">Тема: “Работа с контроллером AXC F 2152”</p>
<br><br><br>
<p align="right">Выполнил</p> 
<p align="right">Студент 3-го курса</p>
<p align="right">Группы АС-64</p>
<p align="right">Котковец К.В.</p>
<p align="right">Проверил</p>
<p align="right">Иванюк Д.С.</p>
<br><br><br>
<p align="center">Брест 2024</p>

---

# Лабораторная работа №3. Работа с контроллером AXC F 2152
## Цель работы

В рамках этой лабораторной работы необходимо ознакомиться с основами платформы PLCnext. Используя Visual Studio, следует создать проект с приветственным сообщением "Hello PLCnext from AS0xxyy!", выполнить его сборку и проверить работоспособность на тестовом контроллере.

## Задание
1. Изучить информацию о платформе PLCnext.
2. Ознакомиться с руководством пользователя.
3. Создать тестовый проект "Hello PLCnext from AS0xxyy!" в Visual Studio, собрать его и протестировать на контроллере.

## Ход выполнения
Для выполнения лабораторной работы создаём проект hello_PLCnext в Visual Studio.

Настраиваем подключение к контроллеру и конфигурируем сеть, после чего проверяем успешность подключения.

![](images/connect.png)

![](images/check.png)

Подключаемся к контроллеру с помощью программы PuTTY Configuration.

![](images/PuTTY.png)

Авторизуемся, введя логин и пароль.

![](images/login.png)

Используем WinSCP для связи с контроллером.

![](images/WinSCP.png)

Загружаем собранный проект в корневой каталог контроллера, изменяем разрешения для запуска и запускаем проект, чтобы увидеть результат.

![](images/hello_PLCnext_properties.png)

## Вывод
В результате лабораторной работы изучены основы платформы PLCnext, создан и собран тестовый проект, а также продемонстрирована его работоспособность на тестовом контроллере.