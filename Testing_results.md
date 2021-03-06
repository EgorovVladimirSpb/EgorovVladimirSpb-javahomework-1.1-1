# Отчёт о тестировании AdoptOpenJDK11 wtih Hotspot 11.0.9.11 (x64)

## Краткое описание

17.11.2020  было проведено тестирование документации и тестирование установки приложения AdoptOpenJDK11 wtih Hotspot 11.0.9.11 (x64)

На тестирование затрачено: 5 минут

В результате тестирования дефекты не выявлены

Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Тест кейс 

В качестве тестовых данных использовались данные 
по ссылке - [инструкция](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

* [Данные с ожидаемым результатом](https://docs.google.com/spreadsheets/d/1gf3RNgkOM4Rb_4Bhwu6ruGrTKqhwQw81KZofPPor-z4/edit?usp=sharing)

Тестирование производилось в следующем окружении:

* Windows version 1909 (OS Build 18363.1198)
* openjdk version "11.0.9" 2020-10-20
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9+11)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+11, mixed mode)

# Отчёт о тестировании KeyValidator.class

## Краткое описание
17.11.2020  было проведено тестирование документации приложения KeyValidator

На тестирование затрачено: 10 минут

В результате тестирования выявлены следующие дефекты:

* [Неверный вывод приложения при запуске](https://github.com/EgorovVladimirSpb/EgorovVladimirSpb-javahomework-1.1/issues/1)
* [Неверные значения для валидных ключей](https://github.com/EgorovVladimirSpb/EgorovVladimirSpb-javahomework-1.1/issues/2)
* [Неверные значения для невалидного ключа](https://github.com/EgorovVladimirSpb/EgorovVladimirSpb-javahomework-1.1/issues/3)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

* Тест кейс 

В качестве тестовых данных использовались данные по ссылке - 
[инструкция](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

* [Данные с ожидаемым результатом тест на запуск и совместимость](https://docs.google.com/spreadsheets/d/16M8zyd88noJruVl7f_LTnCVcroyeusKBqtNBw3ap6s8/edit?usp=sharing)
* [Данные с ожидаемым результатом тест на соответствие документации](https://docs.google.com/spreadsheets/d/1CRn7eY9Mf6INc4fZFepChhfi2aKHEzKQHZWTK_U7irw/edit?usp=sharing)

Тестирование производилось в следующем окружении:

* Windows version 1909 (OS Build 18363.1198)
* openjdk version "11.0.9" 2020-10-20
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9+11)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+11, mixed mode)
* git version 2.29.2.windows.2
