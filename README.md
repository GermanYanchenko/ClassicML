# ClassicML
<br>
Описание работы:
<br>
&nbsp;&nbsp;&nbsp;&nbsp; Предоставлен набор данных от телекоммуникационной компании. В данных содержится информация о почти шести тысячах пользователей, их демографических характеристиках, услугах, которыми они пользуются, длительности пользования услугами оператора, методе оплаты, размере оплаты. 
<br>

&nbsp;&nbsp;&nbsp;&nbsp; Cтоит задача проанализировать данные и спрогнозировать отток пользователей (выявить людей, которые продлят контракт и которые не продлят).Работа включает в себя следующие пункты: 
1. Описание данных. 
2. Исследование зависимостей и формулирование гипотез. 
3. Построение моделей для прогнозирования оттока на основе проверенных гипотез и выявленных взаимосвязей. 
4. Сравнение качества полученных моделей. 
<br><br>
Набор данных выглядит следующим образом:
![alt text](https://github.com/GermanYanchenko/ClassicML/blob/main/sample/ML_classic.png?raw=true)
![alt text](https://github.com/GermanYanchenko/ClassicML/blob/main/sample/ML_classic1.png?raw=true)
<br>
Были исследованы следующие алгоритмы:
<br>
kNN, LogisticRegression, DesisionTreeClassifier, GradientBoostingClassifier, RandomForestClassifier и SupportVectorClassification.
<br>
Также реализован stacking, в качестве мета-алгоритма используется XGBoost.
<br>
Метрика качества - AUC-ROC
<br>
Для прогназирование оттока клиентов в рамках данной работы лучше всего себя показала модель градиентного бустинга деревьев (GradientBoostingClassifier)
<br>
У моделей метода опорных векторов (SVC) и логистической регрессии (LogisticRegression) метрика качества AUC-ROC получилась соизмеримой с моделью градиентного бустинга деревьев.<br><br>

![alt text](https://github.com/GermanYanchenko/ClassicML/blob/main/sample/metric.png?raw=true)
<br>
![alt text](https://github.com/GermanYanchenko/ClassicML/blob/main/sample/ML_classic2.png?raw=true)
