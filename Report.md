# Отчёт о тестировании приложения Credit Card Number Validator
## Краткое описание
26.10.2020-27.10.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.
На тестирование затрачен 1 час.

В результате тестирования был выявлен дефект:
* [Карты American Express определяются как невалидные](https://github.com/Kisnik/Credit-Card-Number-Validator/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* чек-лист на основе номеров кредитных карт, полученных на сайте https://cartoved.ru/common/generator-kreditnyh-kart.html

В качестве тестовых данных использовались номера кредитных карт, полученных на сайте https://cartoved.ru/common/generator-kreditnyh-kart.html

* 5404366939920423 - валидный MasterCard
* 5404366939920422 - невалидный MasterCard
* 5404364820970599 - валидный MasterCard
* 5122178037285885 - валидный MasterCard
* 4252854597433595 - валидный Visa
* 4328712826669134 - валидный Visa
* 4241411741690788 - валидный Visa
* 4241411741690789 - невалидный Visa
* 375641959979186 - валидный American Express
* 345709889638730 - валидный American Express


Тестирование производилось в следующем окружении:
* 64-разрядная ОС Windows 10 версия 2004
* версия Java 11.0.8