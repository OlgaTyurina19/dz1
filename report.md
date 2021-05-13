# Отчёт о тестировании ДЗ 1
## Краткое описание
09.05.2021 - 09.05.2021 было проведено функциональное тестирование приложения **ДЗ 1**.
 
На тестирование затрачено: 1,5 часа
 
В результате тестирования выявлены следующие дефекты:
 
[Номер банковской карты из 14 цифр не проходит валидацию](https://github.com/OlgaTyurina19/dz1/issues/1)
 
[Номер банковской карты из 15 цифр не проходит валидацию](https://github.com/OlgaTyurina19/dz1/issues/2)
 
[Номер банковской карты из 14 цифр не проходит валидацию](https://github.com/OlgaTyurina19/dz1/issues/3)
 
 
## В качестве тестовых данных использовались данные из следующего источника: https://www.freeformatter.com/credit-card-number-generator-validator.html
 
1. Diners Club - Carte Blanche:
  30489943417963 Expected result: Result is OK
 
2. Diners Club - International:
  36985691331664 Expected result : Result is OK
 
3. American Express (AMEX):
  343070942499558 Expected result : Result is OK
 
4. VISA:
  4929988777834629 Expected result: Result is OK
5. Discover:
  6011348882440669 Expected result: Result is OK
6. Visa Electron:
  4913133420177385 Expected result: Result is OK
7. MasterCard:
  2221001939727159 Expected result: Result is OK
8. JCB:
  3530765035262691 Expected result: Result is OK
9. InstaPayment:
  6381791785144833 Expected result: Result is OK
10. Diners Club - North America:
  5599401762474332 Expected result: Result is OK
11. Maestro:
  0604237841963240 Expected result: Result is OK
 
## Тестирование производилось в следующем окружении:
 
1. Google Chrome
  Версия 90.0.4430.93 (Официальная сборка), (64 бит)
2. 11 версия Java