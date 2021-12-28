# Отчёт о тестировании приложения CreditCardNumberValidator

## Краткое описаниe:

18.12.2001 было проведено тестирование приложения CreditCardNumberValidator эквивалентными валидными значениями.

На тестирование затрачено: 0.5 часа

В результате тестирования дефектов выявлено: номера кредитных карт платежной системы American Express (AMEX) не воспринимаются приложением, как валидные.

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* Чек лист из задачи № 2

В качестве тестовых данных использовались номера карт платежных систем: VISA, Mastercard, American Express (AMEX), с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html
### VISA:
* CreditCard 4254380532485266
* CreditCard 4556779549958584
### MasterCard:
* CreditCard 5451276346956476
* CreditCard 5326373071031881
### American Express (AMEX):
* CreditCard 345737515919547
* CreditCard 349673488650585
* CreditCard 372623567348957

Тестирование производилось в следующем окружении:
* ОС - Windows 10 20H2 x64
* Java version - 11.0.12
* JDK - IntelliJ IDEA Community Eition 2021.3
