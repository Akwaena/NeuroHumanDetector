# NeuroHumanDetector
Комбинированный школьный проект по информатике по разработке определителя человеческого силуэта

Школьный комбинированный проект «Нейросетевая система определения человеческого силуэта»


1. Абстракт:
Основной задачей проекта является разработка программы на основе технологии нейросетей с помощью языка программирования Python. Программа должна в реальном времени определять наличие человека в видеопотоке, дистанцию до него, его скорость и направление перемещения в определенном количестве измерений, а также выдавать пользователю дополнительную информацию, в зависимости от варианта программы.

2. Применяемые технологии:
При разработке крайне вероятно использование далее перечисленных библиотек Python. Для проведения продвинутых математических выражений будет использована библиотека math. В проекте вероятно понадобится использование функций генерации псевдослучайных чисел из библиотеки random. Для создания удобного интерфейса возможно использование библиотек PyQt или PyGame. Для реализации самого электронного мозга программы будут использованы библиотеки OpenCV, Tensoflow или их аналоги.

3. Вариант реализации программы №1:
Название варианта – Система Помощи в Наведении (СПН).
Данный вариант программы предназначен для помощи в наведении и обнаружении противника пехоте или для управления вооружением противопехотных роботов или воздушных дронов.
Программа должна выполнять все функции, описанные в абстракте, а кроме того, описывать вокруг силуэта человека прямоугольник, подписывать направление передвижения (только право-лево для пехоты или роботов и в двух измерениях для воздушных дронов), скорость передвижения. Дополнительно надо выполнять расчеты упреждения для выстрела (точку приземления снаряда, время полета снаряда и положение движущейся цели в момент прилета снаряда)

4. Вариант реализации программы №2:
Название варианта – Автомобильная Система Определения Пешеходов (АСОП).
Данный вариант программы предназначен для определения во входном видеопотоке пешеходов. Программа должны вычислять расстояние до пешехода, упреждать его перемещения, просчитывать примерный тормозной путь автомобиля и сопоставлять его с дистанцией и упреждением движения пешехода. Кроме того, опционально определение остальных дорожных объектов и дорожной разметки и соответствующие им вычисления.

5. Вариант реализации программы №3:
Название варианта – Программа Определения внешних Данных человека для Систем Видеонаблюдения (ПОДСВ).
Данный вариант программы предназначен для определения человека на видеопотоке с камеры видеонаблюдения, а также по возможности определение его лица и внешних примет и сравнение их с данными из базы. 


