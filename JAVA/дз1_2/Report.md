﻿# Отчет о тестировании Credit Card Number Validator

## Credit Card Number Validator - приложение, проверяющее валидацию номера банковской карты.

26.10.2020 проведено функциональное тестирование функционала Credit Card Number Validator.

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:

* Ошибка при вводе валидного номера банковской карты https://github.com/marosi13/homework_1_2/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md


В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html

* Result for 4556275484248040: OK
* Result for 4256970201509921: OK
* Result for 5577814895512719: OK
* Result for 5173963069475423: OK
* Result for 3589531595201598: OK
* Result for 4026447373542237: OK
* Result for 6762462857888421: OK
* Result for 4539248513701593011: OK
* Result for 6011812826785075638: OK
* Result for 30294632265347: OK
* Result for 30428375182968: OK

Тестирование производилось в следующем окружении:

* Win7 Professional 64-bit OS
* Java: openjdk version "11.0.9"
