## Отчет о тестировании программы Credit Card Number Validator

Краткое описание
05.07.2021 было проведено тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 3 часа


## Описание процесса тестирования


Установлен IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA
Ожидаемый результат: IntelliJ IDEA установлен  согласно Руководство по установке IntelliJ IDEA
Фактический  результат: IntelliJ IDEA установлен согласно Руководство по установке IntelliJ IDEA

Проверена работа программы Credit Card Number Validator посредством запуска в IntelliJ IDEA с разными тестовыми данными
В качестве тестовых данных использовались данные, взятые из генератора случайных номеров карт https://www.https://cardguru.io/

Были взяты  случайные номера карт 

Mastercard 

VISA

American Express

Maestro

MIR

Номера карт находятся по ссылке https://github.com/MargaritaPustovalova/j1.2/blob/main/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5.md 


Данные номера были подставлены  поочередно в код, после чего производилось нажатие на зелёную стрелку на первой строке, выбран "Run 'Main.main()'":

## Описание дефектов 

[При проверке программы Credit Card Number Validator некоторые карты не работают](https://github.com/MargaritaPustovalova/j1.2/issues/1) 

Не работают карты с номерами, не равными 16-ти знакам. 

Такие карты имеются у Maestro

## Окружение

Тестирование производилось в следующем окружении:

Windows 10 версия 10.0.18363.1256

java -version openjdk version "11.0.9.1" 2020-11-04

IntelliJ IDEA community edition 2020.03 
