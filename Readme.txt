In this educational project, I will apply supervised learning to build a model that determines the region where oil extraction will yield the highest profit.


Let's assume that I work for an oil extraction company and need to decide where to drill a new well. The typical steps for selecting a location are as follows:


* Collect characteristics of wells in the preferred region, such as oil quality and reserves volume.
* Build a model to predict the reserves volume in new wells.
* Select wells with the highest predicted values.
* Determine the region with the maximum total profit from the selected wells.


I have datasets with oil samples from three regions. The characteristics for each well in the region are already known. I will build a model to determine the region that will yield the highest profit. Additionally, I will analyze potential profits and risks using the Bootstrap technique.


Important conditions:


* Only linear regression will be suitable for training the model.
* During the exploration of a region, 500 points are studied, and the best 200 points are selected for development using machine learning.
* The budget for well development in the region is 10 billion rubles.
* At current prices, one barrel of oil brings in a revenue of 450 rubles. The revenue per unit of product is 450,000 rubles since the volume is given in thousands of barrels.
* After assessing the risks, only regions with a probability of loss less than 2.5% should be considered. Among them, the region with the highest average profit is selected.




В этом учебном проекте я буду применять машинное обучение с учителем (Supervised Learning) для построения модели, которая будет определять регион, где добыча нефти принесёт наибольшую прибыль. 


Моделирование ситуации:


Допустим, я работаю в нефтедобывающей компании. Нужно решить, где бурить новую скважину. Шаги для выбора локации обычно такие:


* В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
* Строят модель для предсказания объёма запасов в новых скважинах;
* Выбирают скважины с самыми высокими оценками значений;
* Определяют регион с максимальной суммарной прибылью отобранных скважин.


У меня есть датасеты с  пробами нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Построю модель для определения региона, где добыча принесёт наибольшую прибыль. А так же проанализирую возможную прибыль и риски техникой Bootstrap.
Важные условия:


* Для обучения модели подойдет только линейная регрессия.
* При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.
* Бюджет на разработку скважин в регионе — 10 млрд рублей.
* При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.
* После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью.