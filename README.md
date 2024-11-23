# hse24_hw4

[Основная часть](https://colab.research.google.com/drive/1BQtJeJQYu8ka5_e8qinDEj53rIUMEGZY#scrollTo=hECODRNGUE5x)

Часть задания с объединением всех файлов .counts по генам в один общий `ALL.counts` проделала в [Jupyter Notebook](src/minor_bioinf_hw4_2.ipynb) из-за проблем с работой Numpy в гугл коллабе

## MultiQC

<img width="861" alt="Снимок экрана 2024-11-23 в 17 48 52" src="https://github.com/user-attachments/assets/a313a34a-0e17-484e-b726-d5eab7030497">

![fastqc_per_sequence_quality_scores_plot](https://github.com/user-attachments/assets/477a53d8-d6fe-4850-8def-f858ce408f9d)


![fastqc_per_base_sequence_quality_plot](https://github.com/user-attachments/assets/ec36cc2d-9a55-4f29-8cfe-9aa229b805a9)

![fastqc_per_sequence_gc_content_plot](https://github.com/user-attachments/assets/63eda2f1-c505-4016-b854-c7bb280eab79)

![fastqc_sequence_duplication_levels_plot](https://github.com/user-attachments/assets/05a8acee-5ad3-41e3-95cb-79f27a9af789)

![fastqc-status-check-heatmap-2](https://github.com/user-attachments/assets/d1205f30-910c-4ef2-a4ab-5fbcd9cde329)

## Таблица со статистикой по каждому из 6-ти образцов:
ID образца
Тип образца (перепрограммированние или контроль)
Общее кол-во исходных чтений
Кол-во и процент чтений, которые были успешно откартированы на геном (уникально или нет)
Кол-во и процент уникально откартированных чтений
Общее кол-во чтений, которые попали на гены


| ID образца | Тип | Общее кол-во чтений | Успешно откартированные | Уникально откартированные |кол-во чтений в гене |
|-----------|-----------|-----------|-----------|-----------|-----------|
| SRR3414629  | Перепрограммированный  | Данные 3  | Данные 4  | Данные 5  | Данные 6  |
| SRR3414630  | Перепрограммированный  | Данные 9  | Данные 10 | Данные 11 | Данные 12 |
| SRR3414631 |Перепрограммированный | Данные 15 | Данные 16 | Данные 17 | Данные 18 |
| SRR3414635 | Контроль | Данные 21 | Данные 22 | Данные 23 | Данные 24 |
| SRR3414636 | Контроль | Данные 27 | Данные 28 | Данные 29 | Данные 30 |
| SRR3414637 | Контроль | Данные 33 | Данные 34 | Данные 35 | Данные 36 |


