# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП факультета ВМК МГУ, осенний семестр 2025/2026
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2025/2026"

<p align="center">
<img src="https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/kernel_trick.jpg" height=400pt>
</p>

:white_check_mark: **Курс сдается через систему [anytask](https://anytask.org/course/1125). Инвайт можете получить у преподавателя**


:white_check_mark: **Полезные ссылки:**

* Текущие связанные курсы
    * [Курс практикум на эвм](https://github.com/mmp-practicum-team/mmp_practicum_fall_2025)
    * [Общий курс по МЛ](https://github.com/MSU-ML-COURSE/ML-COURSE-25-26)

* Материалы прошлых лет:
  * [Материалы древних времен](https://github.com/esokolov/ml-course-msu)
  * [Вышкинский аналог курса](https://github.com/esokolov/ml-course-hse)
  * [Курс лекций по ММРО 20/21 (в те времена он читался эксклюзивно для ММП)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Общий курс по МЛ 21/22](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)
  * [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)
  * [Курс ММРО 20/21, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)
  * [Курс ММРО 21/22, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021)
  * [Курс ММРО 22/23, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022)
  * [Курс ММРО 23/24, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2023)
  * [Курс ММРО 24/25, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024)

# Правила выставления оценок

:white_check_mark: **По этому курсу (ММРО) в конце семестра будет экзамен**

Общая оценка по нему выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/formula.png)
, где 

* Check — 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs — min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + конкурсы + теор.дз) (без бонусов)>
* Exam — оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (5)** _лабораторные работы (4) и теор. дз. (1)_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 4-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 3-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor — округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

:white_check_mark: **По курсу лекций в конце семестра будет зачет без оценки**

Для получения этого зачета вам необходимо сдать **не менее 3-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов))

# Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 4 сентября  | Семинар 1 | Введение в курс. Pandas. Разведочный анализ данных |  [Ноутбук с семинара](Seminars/Seminar1_pandas.ipynb) | [Легкая домашка на пандас](Homeworks/Homework1)   |
| 11 сентября  | Семинар 2 | Метрическая парадигма машинного обучения. KNN. Проблемы метода и практические применения | [Конспект](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_2_KNN_konspekt.pdf) |  ¯\\\_(ツ)\_/¯ |
| 18 сентября  | Семинар 3 | Функциональные парадигмы машинного обучения. Линейная регрессия. Градиентный спуск. Sklearn. | [Ноутбук](Seminars/Seminar_3_linregr_notebook.ipynb) Конспект (скоро будет) | [Домашнее задание](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Homeworks/Homework2/homework-practice_02-linregr.ipynb) |
| 25 сентября | Семинар 4 | Векторное дифференцирование | [Конспект](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_4_MatVecDiff.pdf) |  ¯\\\_(ツ)\_/¯ |
| 2 октября | Семинар 5 | Логистическая регрессия: оценивание вероятностей и вывод функционала, калибровка вероятностей | [Конспект](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_5_log_reg.pdf)  | [Домашнее задание](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Homeworks/Homework3/matvec-diff.pdf) |
| 9 октября | Семинар 6 | Задача оптимизации. Теорема Каруша-Куна-Таккера. Решение задач. | [Теория](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_6_conditionat_optimization/theory.pdf) [Задачи](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_6_conditionat_optimization/tasks.pdf) [Обучение Lasso регрессии](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_6_conditionat_optimization/lasso_traning.pdf) | ¯\\\_(ツ)\_/¯ |
| 16 октября | Семинар 7 | Ядровые обобщения методов, задачи на ядра, аппроксимация ядер | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_7_kernel_methods.pdf) |  ¯\\\_(ツ)\_/¯ |
| 23 октября | Семинар 8 | Метрики качества классификации, ROC-AUC | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_8_bin_classification_metrics.pdf) | [Домашнее задание](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/tree/main/Homeworks/Homework4) |
| 30 октября | Семинар 9 | Логическая парадигма машинного обучения. Решающее дерево. Вывод критериев информативности для деревьев. Реализация на практике. | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_9_decision_tree.pdf) |  ¯\\\_(ツ)\_/¯ |
| 6 ноября | Семинар 10 | Разложение ошибки на смещение и разброс | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/bias_variance_tradeoff_sem.pdf) |  ¯\\\_(ツ)\_/¯ |
| 13 ноября | Семинар 11 | Вывод градиентного бустинга | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Seminars/Seminar_11_ensembles.pdf) |  ¯\\\_(ツ)\_/¯ |
| 20 ноября | Семинар 12 | Почему градиентный бустинг так устроен |  | [Домашнее задание 4](https://github.com/mmp-mmro-team/mmp_mmro_fall_2025/blob/main/Homeworks/Homework5/hw_practice_4.ipynb) |
| 27 ноября | Семинар 13 | Имплементации градиентного бустинга |  |  ¯\\\_(ツ)\_/¯ |
| 4 декабря | Семинар 14 | Бонусный семинар | |  ¯\\\_(ツ)\_/¯ |
