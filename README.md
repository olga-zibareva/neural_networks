# learning_tasks

Учебные задачи поэтапного конструирования нейронных сетей.  

## Полносвязные сети
### Обучение многослойной сети (GPU)
**1_fcnn_clothes**  
Задание. Постройте и обучите нейронную сеть на наборе данных с предметами одежды. Для этого создайте в коде три функции:
- загрузки обучающей выборки `load_train()`,
- создания модели `create_model()`,
- запуска модели `train_model()`.
Добейтесь того, чтобы значение `accuracy` на тестовой выборке было не меньше 85%.

## Свёрточные сети
### Алгоритм Adam
**2_cnn_clothes_adam**  
Задание. Постройте и обучите свёрточную нейронную сеть на наборе данных с одеждой. Для этого создайте в коде три функции:
- загрузки обучающей выборки `load_train()`,
- создания модели `create_model()`,
- запуска модели `train_model()`.
Добейтесь того, чтобы значение `accuracy` на тестовой выборке было не меньше 87%.  

### Свёрточные сети для классификации фруктов
**3_cnn_fruits_adam**  
Задание. Постройте и обучите свёрточную нейронную сеть на наборе данных с фруктами. Для этого создайте в коде три функции:
- загрузки обучающей выборки `load_train()` (теперь она вернёт загрузчик данных),
- создания модели `create_model()`,
- запуска модели `train_model()`.
Добейтесь того, чтобы значение `accuracy` на тестовой выборке было не меньше 90%.
У вас есть ограничение: модель должна обучиться за час.
Для выполнения задания будет использована полная версия датасета с фруктами. Путь к ней уже указан в прекоде.

### ResNet в Keras
**4_resnet_fruits**  
Задание. Постройте и обучите архитектуру `ResNet` на наборе данных с фруктами. Добейтесь того, чтобы значение `accuracy` на тестовой выборке было не меньше 99%.
У вас есть ограничение: модель должна обучиться за полчаса.