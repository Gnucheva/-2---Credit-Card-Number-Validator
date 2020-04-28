# Отчёт о тестировании установки IntelliJ IDEA под Windows 64 bit 

28.04.2020 было проведено тестирование установки приложения IntelliJ IDEA на Windows 10Pro 64 bit 

На тестирование затрачено: 30 минут.

В результате тестирования выявлены следующие дефекты:
* [Нерабочая ссылка в руководстве по установке IntelliJ IDEA](https://github.com/Gnucheva/-2---Credit-Card-Number-Validator/issues/1)
* [Шаг №19 в Руководстве по установке IntelliJ IDEA повторяется два раза](https://github.com/Gnucheva/-2---Credit-Card-Number-Validator/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

Тестирование производилось в следующем окружении:
* Windows 10Pro 64 bit 
* Chrome 

# Отчёт о тестировании программы Credit Card Number Validator.

28.04.2020 было проведено исследовательское тестирование программы Credit Card Number Validator.

На тестирование затрачено: 2 часа.

В результате тестирования выявлены следующие дефекты:
* [Ошибка при валидации American Express](https://github.com/Gnucheva/-2---Credit-Card-Number-Validator/issues/3)
* [Ошибка при валидации карт Maestro , JSB и Visa 18-19 чисел в номере карты.](https://github.com/Gnucheva/-2---Credit-Card-Number-Validator/issues/4)
* [Принимает невалидные номера карт Visa и MasterCard](https://github.com/Gnucheva/-2---Credit-Card-Number-Validator/issues/5)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* сайт генерации номеров кредитных карт [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные c сайта генерации [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

1.Валидные данные карт : 
* 4485544349069586
* 5398684047710561
* 4026487049622526

2.Невалидные данные : 
* 370609033109828             
* 4024007122071769104
* 4222222222222220 

Тестирование производилось в оружении:
* Windows 10 Pro 64 bit
* Java version 11
