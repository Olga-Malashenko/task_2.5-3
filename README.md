# Отчёт о тестировании Приложения task_2.5-3

## Краткое описание

16.01.2022 было проведено тестирование приложения task_2.5-3

На тестирование затрачено: 20мин.

В результате тестирования выявлены следующие дефекты:
* Приложение не проходит цель плагина checkstyle [Ссылка на issue](https://github.com/Olga-Malashenko/task_2.5-3/issues)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию Домашнее задание к занятию «Выстраивание процесса непрерывной интеграции (CI): Github Actions. Покрытие кода с JaCoCo, статический анализ кода: CheckStyle, SpotBugs»
Задача 3. "Внедряем стандарты кодирования"](https://github.com/netology-code/javaqa-homeworks/tree/master/ci#%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA-%D0%B7%D0%B0%D0%BD%D1%8F%D1%82%D0%B8%D1%8E-%D0%B2%D1%8B%D1%81%D1%82%D1%80%D0%B0%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%B0-%D0%BD%D0%B5%D0%BF%D1%80%D0%B5%D1%80%D1%8B%D0%B2%D0%BD%D0%BE%D0%B9-%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%B8-ci-github-actions-%D0%BF%D0%BE%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B5-%D0%BA%D0%BE%D0%B4%D0%B0-%D1%81-jacoco-%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D0%BA%D0%BE%D0%B4%D0%B0-checkstyle-spotbugs)







В качестве тестовых данных использовались данные:
[legacy код](https://github.com/netology-code/javaqa-code/tree/master/2.5_ci)

Ожидаемый результат: BUILD SUCCESS

Фактический результат: BUILD FAILURE

Тестирование производилось в следующем окружении:

* Windows 10 Home, 64
* Java SE 11
* junit-jupiter 5.8.2
* maven-checkstyle-plugin 3.1.2
