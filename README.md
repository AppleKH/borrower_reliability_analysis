# Анализ влияния семейного положения и количества детей на погашение кредита

## Описание проекта
Этот проект выполнен для кредитного отдела банка с целью исследования, влияет ли семейное положение и количество детей клиента на погашение кредита в срок. Результаты исследования помогут при построении модели кредитного скоринга, которая оценивает способность потенциального заёмщика вернуть кредит.

## Использованные инструменты и библиотеки
- Python
- Pandas
- PyMystem3
- Collections
- Jupyter Notebook

## Описание данных
Датасет содержит следующие столбцы:
- `children`: количество детей в семье
- `days_employed`: общий трудовой стаж в днях
- `dob_years`: возраст клиента в годах
- `education`: уровень образования клиента
- `family_status`: семейное положение
- `gender`: пол клиента
- `income_type`: тип занятости
- `debt`: наличие задолженности по кредитам
- `total_income`: ежемесячный доход
- `purpose`: цель получения кредита

## Шаги предобработки данных
1. **Заполнение пропущенных значений**
2. **Изменение типов данных**
3. **Удаление дубликатов**
4. **Лемматизация целей кредита**
5. **Категоризация данных**

## Ключевые выводы
1. **Влияние семейного положения**:
   - Самый высокий процент задолженности наблюдается у неженатых/незамужних клиентов (10.17%).
   - Наименьший процент задолженностей у вдовцов/вдов (6.77%).

2. **Влияние количества детей**:
   - Наименьший риск задолженности наблюдается у клиентов без детей (7.58%), а наибольший у тех, у кого двое детей (9.84%).

3. **Влияние уровня дохода**:
   - Клиенты с доходом более 500к имеют самый низкий уровень задолженности (6.31%).

4. **Влияние целей кредита**:
   - Самый высокий процент невыплат — по кредитам на автомобиль (9.55%).
   - Кредиты на жильё имеют самый низкий процент задолженности (7.08%).

## Заключение
Исследование показало, что семейное положение и количество детей влияют на вероятность погашения кредита. Эти данные могут использоваться для улучшения моделей кредитного скоринга и более точной оценки рисков для банков.
