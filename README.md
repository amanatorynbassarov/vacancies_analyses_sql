# **Проект. Анализ вакансии HeadHunter**


##  **Описание проекта**

Наш проект включает в себя несколько этапов:
* знакомство с данными;
* предварительный анализ данных;
* детальный анализ вакансий;
* анализ работодателей;
* предметный анализ.


## **Краткая инфорация о данных**

Таблица ***vacancies***

* id - ID вакансии
* name - Название вакансии
* key_skills - Ключевые навыки
* schedule - Тип рабочего графика
* experience - Требования к опыту
* employment - Тип трудоустройства
* salary_from - Нижняя граница зарплаты
* salary_to - Верхняя граница зарплаты
* area_id - ID региона вакансии
* employer_id - ID работадателя


Таблица ***areas***

* id - Идентификатор города
* name - Название города 


Таблица ***employers***

* id - Номер работадателя
* name - Название работадателя
* area - Регион регистрации


Таблица ***industries***

* id - ID сферы деятельности
* name - Название сферы деятельности

Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.

Таблица ***employer_industries***

* employer_id - ID работадателя
* industry_id - ID сферы деятельности 

### **Какой кейс решаем?**
Используя 4 таблицы(vacancies, areas, industries, employers) понять рынок вакансии на сайте hh


### **Что практикуем?**
Писать красивые и логически значимые запросы, правильно интерпретировать результаты запроса, корректно задавать вопросы и находить взаимосвязь в данных.
 

