# Отчёт о тестировании "Credit card Number Validator"

## Краткое описание

03.07.2020 - 03.07.2020 
* установка IntelliJ IDEA
* smoke test приложения "Credit card Number Validator"
* было проведено функциональное тестирование приложения "Credit card Number Validator".


На тестирование затрачено: 0.2 час

В результате тестирования выявлены следующие дефекты:

* https://github.com/usoltsevjr/Validators/issues/4
* https://github.com/usoltsevjr/Validators/issues/5
* https://github.com/usoltsevjr/Validators/issues/6
* https://github.com/usoltsevjr/Validators/issues/7

## Описание процесса тестирования
#### В процессе тестирования использовались следующие артефакты:

* Руководство по установке IntelliJ IDEA
* Тест кейс №3
* Баг-репорт


#### В качестве тестовых данных использовались данные из "https://www.freeformatter.com/credit-card-number-generator-validator.html" :

Visa:
* 4556626728803497
* 4916396675119009
* 4556892854017768076

Maestro:
* 6761020383750134
* 6762837137309480

MasterCard:
* 2720999811799707
* 5200440062902486

American Express
* 345155455674750
* 376945521331068

Diners Club - International:
* 36253365205759
* 36281863209858

* А также оставить оставить данную строку "пустой"

#### Тестирование производилось в следующем окружении:

* Windows 10 x64 
* Java 11.0.7
