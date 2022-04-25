# Исследование объявлений о продаже квартир

*Статус проекта:*  
Проект завершен.

*Описание и цели:*  
Мы имеем данные из агентства недвижимости. Это архив объявлений о продаже недвижимости в Санкт-Петербурге и близлежащих районах, собранных за последние несколько лет. 
Нам нужно будет научиться определять рыночную стоимость недвижимости, определить самые важные параметры, влияющие на неё. Это позволит построить автоматизированную систему, способную обнаруживать аномалии и мошенническую деятельность.

*Инструменты:*  
Pandas, Matplotlib, Numpy

*Выводы:*  
- Основной параметр - total_area (общая площадь). Он имеет сильный коэффициент корреляции Пирсона. Таким образом, total_area оказывает наибольшее влияние на цену квартиры.
- "floor_level" и "rooms" также имеют влияние. Между "total_area" и "rooms" существует тесная связь. "total_area" увеличивается, "rooms" также увеличивается.
- "cityCenters_nearest" имеет влияние, но это не имеет значения, когда мы рассматриваем центр города.
- "total_area", "ceiling_height" больше в центре города. Также здесь есть квартиры от 2-х комнат и выше.