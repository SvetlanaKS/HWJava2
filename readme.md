# Отчёт о тестировании Money Transfer

## Краткое описание

21.07.21 - 21.07.21 было проведено санитарное тестирование приложения Money Transfer.

На тестирование затрачено: 1 ч

В результате тестирования выявлены следующие дефекты:
* [Итоговая сумма баланса после перевода средств неверная](https://github.com/SvetlanaKS/HWJava2/issues/1#issue-949465735)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [тест-кейс](https://docs.google.com/spreadsheets/d/1ECr2cl12dBfzuPoF2iUJHk95YOhEce9ftCevJ3CKbwc/edit?usp=sharing)



В качестве тестовых данных использовались входные данные задачи:
* переменная типа int, значение - 2_000_000_000 
* переменная типа int, значение - 500_000_000
* переменная для хранения итогового значения - тип int - 2_500_000_000

Тестирование производилось в следующем окружении:
* Windows 10 Pro версия 21H1 64-разрядная операционная система,процессор x64
* Java version "11.0.11" 2021-04-20