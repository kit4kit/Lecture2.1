# Отчёт о тестировании приложения Lecture2.1

## Краткое описание

Создана программа, которая хранит в себе баланс VIP клиента, сумму перевода на счет и вычисляет итоговую сумму на балансе. 
Все значения int. Общая сумма после пополнения должна составлять 2 500 000 000, но при в результате -1794967296
 

## Описание тестов

Проводилось позитивное тестирование. Были введены целочистелнные числа во все позиции int

## Результаты

1. % успешных/не успешных тестов
2. Ссылки на баг-репорты

## Общие рекомендации

Нужно использовать в результате long, вместо int. Так как число больше 2,14 миллиарда.