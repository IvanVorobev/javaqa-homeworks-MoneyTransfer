﻿# Отчёт о тестировании программы MoneyTransfer

## Краткое описание

03.05.2020 было проведено тестирование программы MoneyTransfer

На тестирование затрачено: 0,5 часа

В результате тестирования работы программы MoneyTransfer выявлен следующий дефект:
* [Программа MoneyTransfer неправильно рассчитывает итоговое значение](https://github.com/IvanVorobev/javaqa-homeworks-MoneyTransfer/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Отчет о тестировании
* Баг-репорт в Issues


В качестве тестовых данных при проверке программы использовались данные из легенды [Задача №1 - Money Transfer](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):

```
* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
* переменная для хранения итогового значения - тип int
```

## Ожидаемый результат:

отображение в нижней части программы IntelliJ IDEA правильного значения итоговой суммы:

2500000000


## Тестирование производилось в следующем окружении:
* Windows 10
* IntelliJ IDEA COMMUNITY 2020.1
* openjdk version "11.0.7" 2020-04-14
* git version 2.26.0.windows.1

## Общие рекомендации:
Использовать long вместо int 