# Отчёт о тестировании приложения CreditCardNumberValidator

## Краткое описаниe:

14.12.2001 было проведено тестирование приложения CreditCardNumberValidator в режиме отладчика.

На тестирование затрачено: 0.1 часа

В результате тестирования выявлены следующие дефекты:
* <shttps://github.com/den369/hwmoneytransfer/issues/1>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Чек лист из задачи № 1

В качестве тестовых данных использовались номера карт с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html
* CreditCard 4254380532485266
* CreditCard 4556779549958584
* finalbalance с ожидаемым результатом 2500000000

Тестирование производилось в следующем окружении:
* ОС - Windows 10 20H2 x64
* Java version - 11.0.12
* JDK - IntelliJ IDEA Community Eition 2021.3