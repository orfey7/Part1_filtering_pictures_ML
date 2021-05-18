# Исследование различных алгоритмов машинного обучения(KNN,SVM,RF)
# KNN
### На примере датасета по классификации одежды
### Исследование различных методов для задачи фильтрации изображений для дальнейшего расчета антропометрических показателей(масса человека) по снимку

##### Распределение наших данных по классам: 

![clothesClass](https://user-images.githubusercontent.com/55453859/118712290-496d4580-b829-11eb-8673-fb3dd97886bf.png)

##### Использование перебора значений гиперпараметра K - ближайших соседей для получения наилучшей точности
![knn1](https://user-images.githubusercontent.com/55453859/118712494-89342d00-b829-11eb-986c-f37dea1ce2b8.png)

![knn2](https://user-images.githubusercontent.com/55453859/118712515-8e917780-b829-11eb-9fd2-14451f6164b1.png)

![knn3](https://user-images.githubusercontent.com/55453859/118712528-90f3d180-b829-11eb-96b3-b4de6c339da4.png)

##### Cross-validation 

![knn_cross](https://user-images.githubusercontent.com/55453859/118712619-aec13680-b829-11eb-8e86-bd68bf151231.png)

Наши метрики для наилучшей модели:

![knn_roc](https://user-images.githubusercontent.com/55453859/118712686-bed91600-b829-11eb-811f-a5695bd3cac0.png)

![knn_metrics](https://user-images.githubusercontent.com/55453859/118712748-cef0f580-b829-11eb-9035-1c775f11ca97.png)

# Random Forest
##### Использование Случайного перебора для того чтобы сузить диапазон перебираемых значений для GridSearchCV.

![rfc1](https://user-images.githubusercontent.com/55453859/118712848-f051e180-b829-11eb-8806-b8baab7a90b6.png)

##### Использование GridSearchCV:
![rfc3](https://user-images.githubusercontent.com/55453859/118713048-30b15f80-b82a-11eb-89c4-01ee34b13ed5.png)

##### Метрики для оценивания полученной модели RandomForest
![rfc_roc_auc](https://user-images.githubusercontent.com/55453859/118713275-66564880-b82a-11eb-97e9-dc9cd3d92c2b.png)

![rfc_metrics](https://user-images.githubusercontent.com/55453859/118713303-6eae8380-b82a-11eb-911f-2a72f742281c.png)


# SVM 
##### Метрики:
![svm_roc_auc](https://user-images.githubusercontent.com/55453859/118713420-94d42380-b82a-11eb-91b6-8df28c397c33.png)

![svm_metrics](https://user-images.githubusercontent.com/55453859/118713441-9bfb3180-b82a-11eb-86a7-ae91f8d8c835.png)



