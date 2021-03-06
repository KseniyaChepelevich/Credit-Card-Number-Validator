# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

02.10.2021 - 02.10.2021 было проведено позитивное тестирование основного функционала приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не принимает валидный 15-ти значные номера карт American Express](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/issues/1#issue-1014204014)
* [Не принимает валидные 19-ти значные номера карт](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/issues/2#issue-1014204788)
* [Не принимает валидные 14-ти значные номера карт](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/issues/3#issue-1016654653)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Данные для тестирования: валидные номера кредитных карт сгенерированные сайтом [freeformatter.com] (https://www.freeformatter.com/credit-card-number-generator-validator.html#validate)
* [Программа Credit Card Number Validator](https://github.com/KseniyaChepelevich/Credit-Card-Number-Validator/blob/master/src/Main.java)

В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#validate):
* 370178502210046, 346122283206535, 376368327056500, 377216842939735, 373435689853650, 378177906238688 (15-ти значные номера American Express);
* 4532606174328577589, 4539336115458298514, 4303740869642871419 (19-ти значные номера Visa);
* 6011263828426766595, 6011626378637231437, 6011593271467831898 (19-ти значные номераDiscover);
* 3537182688759471899, 3589090127782666839, 3531353185827900237 (19-ти значные номера JSB);
* 36921834033255, 36669943489765, 36230088600623 (14-ти значные номера Diners Club - International);
* 30030247498109, 30147888645150, 30238993359959 (14-ти значные номера Diners Club - Carte Blanche)

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* Openjdk version "11.0.12" 2021-07-20
* IntelliJ IDEA Communiti Edition 2021.2.2