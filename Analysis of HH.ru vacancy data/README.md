# Анализ данных вакансий сайта HH.ru

##### Описание проекта
1. Заказчик: Рекрутинговое агентство  
2. Цель проекта: предоставить рекрутинговому агентству детализированный и обоснованный анализ различий в вакансиях для Data Analysts и Data Scientists. Это позволит агентству лучше понимать требования и ожидания рынка труда для этих позиций, а также улучшить процесс подбора подходящих кандидатов.
3. Задачи: Выявить различия в предлагаемых вакансиях для Data Analystsи Data Scientists.

Исходные данные
1. Данные получены из API сайта HH.ru
2. Период предоставленных данных:

    Data Analysts:  
    min дата - 13.02.2024  
    max дата - 11.06.2024 

    Data Scientists:  
    min дата - 29.02.2024  
    max дата - 11.06.2024   

3. Для анализа дополнительно использовался сайт HH.ru


##### Описание данных

`id` - Уникальный идентификатор вакансии.<br>
`name` - Название вакансии.<br>
`published_at` - Дата публикации.<br>
`alternate_url` - Ссылка на вакансию.<br>
`type` - Статус вакансии на момент получения данных от api и передачи 
их в базу. <br>
`employer` - Работодатель.<br>
`department` - Работодатель, отдел.<br>
`area` - Регион места работы.<br>
`experience` - Требуемый опыт работы.<br>
`key_skills`- Ключевые навыки, в том числе найденные при анализе <br>
`полного` текста вакансии. Поле генерируется после получения 
информации от api. <br>
`schedule` - График работы.<br>
`employment` - Тип занятости.<br>
`description` - Описание вакансии.<br>
`description_lemmatized` - Лемматизированное описание вакансии.<br>
`salary_from` - Нижняя граница предлагаемой заработной платы.<br>
`salary_to` - Верхняя граница предлагаемой заработной платы.<br>
`salary_bin` - Категория зарплаты.<br>
`key_skills_from_key_skills_field` - Ключевые навыки из поля вакансии
`key_skills`.<br>
`hard_skills_from_description` - “Твердые” навыки, найденные при 
обработке полей с навыками. Поле генерируется после получения 
информации от api. soft_skills_from_description - “Мягкие” навыки, 
найденные при обработке полей с навыками. Поле генерируется после 
получения информации от api.<br>
`soft_skills_from_description` - “Мягкие” навыки, найденные при обработке полей с навыками. Поле генерируется после получения информации от api. При желании можно дополнить.

В распоряжении предоставлены два файла в формате xlsx:

 - vacancies_da.xlsx  - вакансии Data Analysts
 - vacancies_ds.xlsx  - вакансии Data Scientists
 
