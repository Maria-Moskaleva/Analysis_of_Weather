# Analysis_of_Weather
South Africa is the great place for getting Private Pilot License. I'm going to analyze of Weather Conditions in the city of Port Elizabeth. This analysis will help people choose the greater period for start studying.

Южно-Африканская Республика является популярным местом для получения лицензии пилота. Первый этап  — это получение PPL (Private Pilot License). Минимальное количество налета для получения PPL - 40 часов. Такое количество часов налета можно получить за 3-4 месяца. Однако этот срок может увеличиться из-за неподходящих погодных условий. 

Цель моего проекта — проанализировать данные о погоде в городе Порт Элизабет за последние 10 лет (2013—2023 гг.) и найти оптимальное время* для обучения в авиационной школе. 

*На длительность обучения влияют и другие факторы: бюрократия, доступность самолетов, выходные, праздники и т.д. В данном проекте я буду оценивать только влияние погоды.

В данном анализе пригодной для полета погодой будет считаться погода, которая отвечает следующим условиям:
1) Wind < 20 kts
2) Cross Wind < 8 kts
3) Max Gust Factor < 5 kts
4) Cloud Base > 1500 ft.
5) Visibility > 5000 m

Данные ограничения являются погодными минимумами для Solo Circuts в соответствии с Civil Aviation Act: Regulations - Part F. 

Для выполнения анализа я воспользовалась данными с сайта https://mesonet.agron.iastate.edu/. DataFrame состоит из трех колонок: 
1) station — код аэродрома
2) valid — дата и время 
3) metar — авиационный метеорологический код для передачи сводок о фактической погоде на аэродроме

![image](https://github.com/Maria-Moskaleva/Analysis_of_Weather/assets/137688162/1b7bed9f-48b5-438a-b965-71d8acc02348)


