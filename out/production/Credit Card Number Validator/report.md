# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

02.10.2021 - 02.10.2021 было проведено позитивное тестирование основного функционала приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не принимает валидный 15-ти значный в номере карты](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/issues/1#issue-1014204014)
* [Не принимает валидный 19-ти значный номер карты](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/issues/2#issue-1014204788)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Данные для тестирования: валидные номера кредитных карт сгенерированные сайтом [freeformatter.com] (https://www.freeformatter.com/credit-card-number-generator-validator.html#validate)
* [Программа Credit Card Number Validator](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/blob/master/src/Main.java)
* [Скрин ошибки с 15-ти значным номером](https://drive.google.com/file/d/1Pl2gQweL_d9RqbI5SgGj4sPqidQF2DP6/view?usp=sharing)
* [Скрин ошибки с 19-ти значным номером](https://drive.google.com/file/d/1V4WX_IKBZpVqkHjUCRTw40HOmOT2Wpq9/view?usp=sharing)

В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#validate):
* 370178502210046
* 3545007693067950069

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* Openjdk version "11.0.12" 2021-07-20
* IntelliJ IDEA Communiti Edition 2021.2.2