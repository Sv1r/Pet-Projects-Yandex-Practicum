# Определение возраста покупателей

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.

## Вывод

Исходные данные, представленные в виде **7591** фотографий с маркировкой возрастов. Исходя из распределения целевого признака в текущем датафрейме содержатся широкий диапазон возрастов - от **0** до **100**. При первичном осмотре было выявление применение различных методов аугментации изображений.

Таким образом, наша нейронная сеть на основе модели **ResNet50** за пять эпох модель показала весьма неплохой результат - **7.0152** на последней эпохе.
