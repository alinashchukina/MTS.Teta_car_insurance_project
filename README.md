# MTS.Teta Сar insurance project

## Прогнозирование возникновения страховых случаев по данным автострахования для резервирования денежных средств на возмещение по страховым случаям.

### 1.  Выбор проекта

Проект будет реализован в сфере автострахования. Рынок страхования демонстрирует свой рост в 2021 году. Ведущие компании на российском рынке активно внедряют технологии искусственного интеллекта в свой бизнес. Каждая компания хочет предложить своим клиентам более выгодные условия страховых взносов, рационально расходовать свои денежные средства заложенные в бюджет.

Благодаря проекту мы планируем снизить средства, заложенные в бюджет на возмещение по страховым случаям. Модель будет предсказывать вероятность наступления страхового случая. Благодаря этому компания сможет:
* Рационально планировать бюджет компании на выплаты по страховым случаям
* Минимизировать риски нехватки денежных средств на выплату страховых случаев
* Предложить клиентам оптимальную стоимость страховых взносов

Зная в дальнейшем параметры клиентов, сможем создать сервис, который:
* Автоматически рассчитывает сумму страховых взносов
* Персонализировано подбирает клиенту лучший тариф

 
### 2.  Бизнес и математическая постановки задачи

Цель проекта - Создать сервис, благодаря которому мы сможем:
Рационально планировать бюджет на возмещение денежных средств по страховым случаям и рассчитывать оптимальную стоимость страховых взносов для клиентов компании.

Успешность внедрения проекта, мы сможем определить по уровню лояльности клиента, притоку новых клиентов компании, освободившимся денежным средствам при планировании бюджета с помощью сервиса.

В проекте требуется спрогнозировать возникновение страховых случаев у автовладельцев. Следует оптимизировать метрику Recall, так как в страховом бизнесе важно получить верхнюю оценку по выплатам, то есть хорошо уметь определять все страховые случаи.

### 3.  Выбор набора данных

В этом проекте используются данные, предоставленные платформой Kaggle: [Car Insurance Data](https://www.kaggle.com/sagnik1511/car-insurance-data), с помощью которых исследуется поведение клиентов страховой компании, выдающей автомобильные страховки. На основании социально-демографических данных, исторических данных о пользовании автомобилем и других предоставленных данных о клиенте определяется факт и вероятность требования страховой выплаты.

### 4.  Валидация данных и оценка потенциала

Исследование данных и построение baseline модели приведено в ноутбуке [Car_claims_prediction.ipynb](https://github.com/alinashchukina/MTS.Teta_car_insurance_project/blob/main/Car_claims_prediction.ipynb).

### 5.  Оценка экономического эффекта

Оценка экономического эффекта приведена в ноутбуке [Economic_effect_estimation.ipynb](https://github.com/alinashchukina/MTS.Teta_car_insurance_project/blob/main/Economic_effect_estimation.ipynb).

**Проект выполнили:**

Константин Майоров

Юлия Фокина

Алина Щукина
