## RU Описание

![Иллюстрация проверки квитанций в паре с PDF-парсером](/check-bills-complete-demo.gif){: width="600" height="auto"}

Excel-инструмент для проверки корректности коммунальных начислений на основе данных из квитанций.

## Проблема

Проверка коммунальных платежей вручную требует времени: нужно искать тарифы, разбираться в расчетах и сверять данные по каждой услуге. На практике это редко делается.

## Решение

Создан Excel-файл с заранее настроенной логикой расчётов, который автоматически сверяет объёмы, тарифы и итоговые суммы с фактическими начислениями.

## Функции

- Проверка объёма, тарифа и суммы
- Автоматический расчет ожидаемого начисления
- Подсветка отклонений
- Хранение истории начислений
- Аналитика по периодам

## Инструменты

- Excel

## Как это работает

1. Выбирается период, данные из квитанций вставляются в Excel
2. Файл автоматически пересчитывает начисления и показывает отклонения

Вместо ручного ввода данных, PDF-парсер извлекает нужные значения из PDF-квитанций в сводную таблицу. [ => ссылка на репозиторий](https://github.com/alinaaleks/automations/tree/main/pdf-bill-parser)

## Результат

- Быстрая проверка всех квитанций в одном месте
- Выявление ошибок и переплат
- Экономия времени

---

## EN Description

An Excel tool for verifying utility bill calculations based on data extracted from invoices.

## Problem

Manual verification of utility bills is time-consuming: tariffs must be checked across multiple sources, and each service has its own calculation logic. As a result, most bills go unchecked.

## Solution

An Excel-based system with predefined calculation logic that automatically validates usage, tariffs, and final charges against actual bill data.

## Function

- Validation of consumption, tariff, and total charges
- Automatic calculation of expected values
- Highlighting discrepancies
- Historical data storage
- Period-based analytics

## Tech Stack

- Excel

## How it works

1. Select time period, import the data from the bills
2. The model recalculates and highlights differences

Instead of manually entering data, the PDF-parser extracts the necessary values from PDF bills into a summary table. [ => link to repository](https://github.com/alinaaleks/automations/tree/main/pdf-bill-parser)

## Result

- Centralized verification of all bills
- Detection of errors and overcharges
- Time savings
