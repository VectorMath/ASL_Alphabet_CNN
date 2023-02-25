# Классификация изображений ASL

**ASL_Alphabet_CNN -** пет-проект по разработке свёрточной нейронной сети на PyTorch, с целью распознования обозначения жестов.

## Структура проекта
  * **data:** директория с данными
    * **asl_alphabet_test -** набор единичных жестов для проверки обученной нейронной сети
    * **asl_alphabet_test -** набор изображений для обучения
    * **pretrained_model -** директория с экспортированной обученной нейронной сетью AslAlphabetCNN
  * **docs:** директория с изображениями для оформления readme
  * **Alphabet Classification.ipynb -** нотбук со всей работой
  
  ## Результат
  
  В ходе работы удалось создать свёрточную нейронную сеть и протестировать её со следующими показателями метрик:
   * [Train] Accuracy - 99%
   * [Test] Accuracy - 99%
   
   <p align="center">
  <img src="https://github.com/VectorMath/ASL_Alphabet_CNN/blob/master/docs/concept.png" />
</p>

   <p align="center">
  <img src="https://github.com/VectorMath/ASL_Alphabet_CNN/blob/master/docs/architecture.png" />
</p>
