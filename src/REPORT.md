# Отчёт о тестировании "Реализация функциональности валидации номера банковской карты"

## Краткое описание
Дата начала 04.02.2021 - Дата окончания 05.02.2021 было проведено Функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 5 часов

В результате тестирования дефекты не выявлены

## Описание процесса тестирования

В качестве тестовых данных использовались данные [Generated credit cards from MasterCard](https://www.getcreditcardnumbers.com/generated-credit-card-numbers), [Тестовые карты](https://developer.rbk.money/docs/payments/refs/testcards/), выдуманные данные
пше

- American Express, 342769013816514 - FAIL
- American Express, 345784320846986 - FAIL
- American Express, 348217653600115 - FAIL
- American Express, 376109720302525 - FAIL

  
- MasterCard, 5274458324094158 - OK
- MasterCard, 5106561760265051 - OK
- MasterCard, 5431475342854439 - OK
- MasterCard, 5256424865926424 - OK
  

- Diners Club, 36577581109449 - FAIL
- Diners Club, 36488125269402 - FAIL
- Diners Club, 30239628506857 - FAIL
- Diners Club, 30367673545676 - FAIL


- Visa, 4024007125975622 - OK
- Visa, 4024007180109612 - OK
- Visa, 4024007167224483 - OK
- Visa, 4532482539518794 - OK


- MIR, 2201382000000013 - OK
- MIR, 2201382000000015 - FAIL
- MIR, 2201382000000018 - FAIL
- MIR, 2201382000000023 - FAIL



### Тестирование производилось в следующем окружении:

- Windows 10, 64
- версия Java 11.0.10
