# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

06.11.2021 - 07.11.2021 было проведено функциональное тестирование, смок-тест

На тестирование затрачено: 23:05 - 01:43
В результате тестирования выявлены следующие дефекты:

* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/1
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/2
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/3
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/4
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/5
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/6
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/7
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/8
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/9
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/10
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/11
* https://github.com/Stacyde/Credit-Card-Number-Validator---17/issues/12

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Фейковые номера банковских карт - https://www.freeformatter.com/credit-card-number-generator-validator.html
* Код валидации номера банковской карты - https://github.com/netology-code/javaqa-homeworks/tree/master/intro

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* 4916158263987134 - Result is OK
* 4716463696992848 - Result is OK
* 4485341904074463118 - Result is FAIL
* 2720990632319627 - Result is OK
* 5407191604717111 - Result is OK
* 5562144982342557 - Result is OK
* 379851254489528 - Result is FAIL
* 378147181183958 - Result is FAIL
* 344607703666856 - Result is FAIL
* 6011821129340165 - Result is OK
* 0112477628307638426 - Result is FAIL
* 6011419793326774 - Result is OK
* 3541630956240117 - Result is OK
* 3529637160844822336 - Result is FAIL
* 3545427792587546 - Result is OK
* 5510935672924569 - Result is OK
* 5424099261323892 - Result is OK
* 5453308913814016 - Result is OK
* 30475595478015 - Result is FAIL
* 30537961836587 - Result is FAIL
* 30570496362944 - Result is FAIL
* 36002014190668 - Result is FAIL
* 36086298247179 - Result is FAIL
* 36360292574130 - Result is FAIL
* 6759417984160495 - Result is OK
* 5020882029889116 - Result is OK
* 6761539715116482 - Result is OK
* 4026204074014150 - Result is OK
* 4175003655810252 - Result is OK
* 4175005844812883 - Result is OK
* 6399635945432432 - Result is OK
* 6384725976534565 - Result is OK
* 6389126843334161 - Result is OK

Тестирование производилось в следующем окружении:
* Windows 7 Максимальная
* Java version "11.0.11" 2021-04-20