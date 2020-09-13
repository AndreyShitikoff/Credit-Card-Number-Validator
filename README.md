# Отчёт о тестировании "Credit Card Number Validator"

**Краткое описание**

10.09.2020 было проведено модульное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

**Ожидаемый результат:**

При введении валидных номеров карт результат OK.

**Фактический результат:**

При введении следующих номеров карт результат FAIL:

* *Visa* 4539160726697333275
* *JCB* 3542347232442295092

[Issue](https://github.com/AndreyShitikoff/Credit-Card-Number-Validator/issues/1)

**Описание процесса тестирования**

В процессе тестирования использовались следующие программы.

* OpenJDK 11

В качестве тестовых данных использовался генератор карт на сайте [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)


Тестирование производилось в следующем окружении:

* Windows 10 PRO
* OpenJDK 11