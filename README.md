# hse24_hw4

## [Основная часть](https://colab.research.google.com/drive/1BQtJeJQYu8ka5_e8qinDEj53rIUMEGZY#scrollTo=hECODRNGUE5x)

Часть задания с объединением всех файлов .counts по генам в один общий `ALL.counts` проделала в [Jupyter Notebook](src/minor_bioinf_hw4_2.ipynb) из-за проблем с работой Numpy в гугл коллабе

### MultiQC

<img width="861" alt="Снимок экрана 2024-11-23 в 17 48 52" src="https://github.com/user-attachments/assets/a313a34a-0e17-484e-b726-d5eab7030497">

![fastqc_per_sequence_quality_scores_plot](https://github.com/user-attachments/assets/477a53d8-d6fe-4850-8def-f858ce408f9d)


![fastqc_per_base_sequence_quality_plot](https://github.com/user-attachments/assets/ec36cc2d-9a55-4f29-8cfe-9aa229b805a9)

![fastqc_per_sequence_gc_content_plot](https://github.com/user-attachments/assets/63eda2f1-c505-4016-b854-c7bb280eab79)

![fastqc_sequence_duplication_levels_plot](https://github.com/user-attachments/assets/05a8acee-5ad3-41e3-95cb-79f27a9af789)

![fastqc-status-check-heatmap-2](https://github.com/user-attachments/assets/d1205f30-910c-4ef2-a4ab-5fbcd9cde329)

### Таблица со статистикой по каждому из 6-ти образцов:
ID образца
Тип образца (перепрограммированние или контроль)
Общее кол-во исходных чтений
Кол-во и процент чтений, которые были успешно откартированы на геном (уникально или нет)
Кол-во и процент уникально откартированных чтений
Общее кол-во чтений, которые попали на гены


| ID образца | Тип | Общее кол-во чтений | Успешно откартированные | Уникально откартированные |кол-во чтений в гене |
|-----------|-----------|-----------|-----------|-----------|-----------|
| SRR3414629  | Перепрограммированный  | 21106089  | 20863369 (98.86%)  | 18573565 (88.00%)  | 16224313  |
| SRR3414630  | Перепрограммированный  | 15244711  | 15077019 (98.90%) | 13320505 (87.38%) | 11583775 |
| SRR3414631 |Перепрограммированный | 24244069 | 23965262 ((98.85%) | 21159606 (87.28%) | 18613501 |
| SRR3414635 | Контроль | 20956475 | 20715476 (98.85%) | 18637053 (88.93%) | 16463013 |
| SRR3414636 | Контроль | 20307147 | 20073615 (98.85%) | 18032679 (88.80%) | 15942667 |
| SRR3414637 | Контроль | 20385570 | 20149097 (98.84%) | 18043406 (88.51%)| 15914380 |

  

 
## [Бонусная часть](https://colab.research.google.com/drive/11zx_fQMrDTV6K8V2WZbAD34aR3GhTJSO?usp=sharing) Графики из анализа DESeq2 

### MAplot, показывает Log2FC для генов
![Unknown-5](https://github.com/user-attachments/assets/b6b4dbdc-6f8a-463d-9c1a-c64a09c569af)

### Тепловая карта зависимости экспрессии генов контрольных и репрограммированных образцов
![Unknown-4](https://github.com/user-attachments/assets/fbbe564f-3657-4e87-900e-a097bbe68d56)

### Тепловая карта 20 наиболее дифференциально экспрессированных генов
![Unknown-6](https://github.com/user-attachments/assets/e337b442-5b99-4d81-9c53-9abf779094d1)

### Графики "Normalized counts" для генов, значимо поменявших свою экспрессию 
![Unknown-7](https://github.com/user-attachments/assets/3975ce3c-9131-4aae-bdb6-a3d5dddf62e5)

![Unknown-8](https://github.com/user-attachments/assets/d151818c-e96a-4d0b-8b9e-56d3da619c5b)
