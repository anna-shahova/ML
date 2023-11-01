# ML

Датасет:https://www.cs.toronto.edu/~kriz/cifar-100-binary.tar.gz.

**Задача**: обучить классификатор цветных изображений с помощью свёрточной (не полносвязной архитектуры) сетиискусственных нейронов.

**Требования:**
1. Объяснить, какие элементы вашей сети зависят от количества цветов, какие — от количества классов.
2. Обучить модель. Объяснить место в модели каждого слоя, обосновать выбор гиперпараметров (можно ссылаться напримеры кода в Сети, но в любом случае нужно объяснить словами). 
3. Сравнить качество предсказания при обучении на 20 широких классах с предсказаниями при обучении на 100 узких классах,обобщив предсказания по узким меткам до метки их широкого класса в соответствии с таблицей:

| Метка широкого класса | Метка узкого класса |
| ------------- | ------------- |
| aquatic mammals | beaver, dolphin, otter, seal, whale |
| fish | aquarium fish, flatfish, ray, shark, trout |
| flowers | orchids, poppies, roses, sunflowers, tulips |
| food containers | bottles, bowls, cans, cups, plates |
| fruit and vegetables | apples, mushrooms, oranges, pears, sweet peppers |
| household electrical devices| clock, computer keyboard, lamp, telephone, television |
| household furniture | bed, chair, couch, table, wardrobe |
| insects | bee, beetle, butterfly, caterpillar, cockroach |
| large carnivores | bear, leopard, lion, tiger, wolf |
| large man-made outdoor things | bridge, castle, house, road, skyscraper |
| large natural outdoor scenes | cloud, forest, mountain, plain, sea |
| large omnivores and herbivores | camel, cattle, chimpanzee, elephant, kangaroo |
| medium-sized mammals | fox, porcupine, possum, raccoon, skunk |
| non-insect invertebrates | crab, lobster, snail, spider, worm |
| people | baby, boy, girl, man, woman |
| reptiles | crocodile, dinosaur, lizard, snake, turtle |
| small mammals | hamster, mouse, rabbit, shrew, squirrel |
| trees | maple, oak, palm, pine, willow |
| vehicles 1 | bicycle, bus, motorcycle, pickup truck, train |
| vehicles 2 | lawn-mower, rocket, streetcar, tank, tractor |

4\. Исследовать с помощью графиков метрики предсказания для каких узких классов более всего отличаются от метрик их болеешироких классов. Выдвинуть предположение о причине возможного отличия.

5\. У вас должен получиться .ipynb файл с объяснениями, оформленными в отдельных текстовых блоках.6. После готовности блокнота .ipynb преобразуйте его в  программу на Питоне (.py) так, чтобы после обучения модели онаавтоматически экспортировалась бы в файл (см. например, https://www.tensorflow.org/guide/keras/serialization_and_saving).
