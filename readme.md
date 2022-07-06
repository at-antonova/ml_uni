## Задачи по машинному обучению, ПИ 3 курс

Тут собраны задания с курсов "Технологии компьютерного зрения", "Математические методы анализы данных", "Построение скроринговых моделей с использованием методов машинного обучения"

### computer_vision - задания для курса "Технолгии компьютерного зрения"

Для большинства заданий были даны шаблоны, на лекциях и семинарах разбирались основы машинного обучения (градиентный спуск, kNN), нейросети (FCN, CNN, ResNet, autoencoder) для решения задач компьтерного зрения. На файлы большого размера даны ссылки в Google Colab.

- Linear_classifier.ipynb -- реализация простой линейной классификации
- FCN.ipynb -- реализация полносвязной нейросети
- CNN.ipynb -- реализация сверточной нейросети, отображение accuracy и loss с помощью Tensorboard. [Colab](https://colab.research.google.com/drive/1YR9Hfi9GiBHou0OHZqCyZRc_ciB1F2ig?usp=sharing)
- Resnet.ipynb -- реализация остаточной нейросети ResNet. [Colab](https://colab.research.google.com/drive/1ET912Q4JQLKC_Rc50HUmz8cDNWjwFzB3?usp=sharing)
- Segmentation.ipynb -- сегментация изображения на базе UNet на датасете с фотографиями документов, необходимо отделить документ от фона. [Colab](https://colab.research.google.com/drive/1UBvSD4WTwQz87Ix5jtac4WevgHwMASwJ?usp=sharing)
- Tracking.ipynb -- YOLOv5 + SORT для реализации трекинга людей на видео

### ml_course - задания с курса "Математические методы анализа данных"

- 2 -- Линейная регрессия, регуляризация Lasso, Ridge, GridSearch, реализация градиентного спуска для модели линейной регрессии, FullGD vs SGD vs Momentum
- 3 -- Logit model, SVM, NLP - распознование автора текста: леммантизация pymorphy2 + TF-IDF векторизация + бинарная и мультиклассовая класиификация
- 4 -- Decision Tree Regressor с нуля, ансамблевые методы, xgboost
- 5 -- PCA, t-SNE, кластеризация, kNN с нуля, EM-algorithm for GMM с нуля

### scoring_models - задания с курса "Построение скоринговых моделей с использованием методов машинного обучения"

- opt_binning.ipynb -- код к докладу про применение библиотеки OptBinning для задачи кредитного скоринга с построением скоринговых карт
