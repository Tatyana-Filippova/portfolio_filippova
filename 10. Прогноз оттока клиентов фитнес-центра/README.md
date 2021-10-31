# Прогнозирование оттока клиентов сети фитнес-центров
Исследование проведено для сети фитнес-центров с целью снизить процент оттока клиентов. Для решения поставленных задач изучены обезличенные данные анкет клиентов, данные об абонементах и посещениях клиентов.  
___
## Задачи проекта  
* Выявить закономерности в поведении клиентов, предшествующем оттоку  
* Построить модель для прогноза оттока клиентов  
* Дать рекомендации по удержанию клиентов 
  
## Стек технологий  
Анализ проведен с помощью возможностей языка программирования Python с использованием библиотек:  
```python
import pandas as pd
import numpy as np

# визуализация данных
import matplotlib.pyplot as plt
import seaborn as sns

# построение моделей
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn.cluster import KMeans
from scipy.cluster.hierarchy import dendrogram, linkage

from sklearn.metrics import accuracy_score, precision_score, recall_score, roc_auc_score, silhouette_score
```
## Результаты исследования  
Построена модель прогноза оттока клиентов в следующем месяце с помощью алгоритма логической регрессии (показала наилучшие метрики).  
  
Выделены 5 кластеров клиентов и даны подробные описания типичного пользовательского поведения и других данных для каждого.  
  
Даны рекомендации по улучшению качества работы с клиентами с учетом особенностей каждого кластера.  
____
Аналитик: Филиппова Татьяна  

Статус проекта: завершен

*Проект выполнен в рамках обучения в Яндекс.Практикуме на курсе Data Analyst*
