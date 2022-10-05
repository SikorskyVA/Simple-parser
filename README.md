Вам необходимо написать функцию, которая будет основана на поиске по сайту habr.com. Функция в качестве параметра должна принимать список запросов для поиска (например, ['python', 'анализ данных']) и на основе материалов, попавших в результаты поиска по каждому запросу, возвращать датафрейм вида:
<дата> - <заголовок> - <ссылка на материал>
В рамках задания предполагается работа только с одной (первой) страницей результатов поисковой выдачи для каждого запроса. Материалы в датафрейме не должны дублироваться, если они попадали в результаты поиска для нескольких запросов из списка.
