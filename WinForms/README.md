Основные проекты учебного курса C#./Net developer, реализованные по технологии WinForms(Windows Forms):

1. Один из последних своих научных IT проектов. Это микс двух языков программирования - облегченные C++ на платформе ардуино и C#./Net. Приложение "Choper by Serg Kredo" реализовано в WinForms. Задача стояла автоматизировать некие элементы в экспериментальной установке (сервопривод с различными датчиками) для научной деятельности в голографии. Реализовано полнофункциональное приложение плоттер на языке C#, способное отображать данные с датчиков платы ардуино в виде кривых. Для сглаживания кривых применялись различные фильтры: Калмана, бегущая средняя, медиана. Весь массив полученных данных можно сохранять в текстовом формате с последующей обработкой в специальных редакторах. В приложении использовалась технология асинхронного программирования Async&Await. Код проекта: https://github.com/SergKredo/Arduino-C-Windows-Forms-/blob/master/ServoApp/Form1.cs и скетч ардуино: https://github.com/SergKredo/Arduino-C-Windows-Forms-/blob/master/SketchArduino/SketchArduino.ino


2. Новый улучшенный релиз десктопной версии приложения "Reflector by Serg Kredo" с возможностью выбора типов сборки, членов типа и информации об атрибутах типов и членов типа.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson7/Task%203_New%20Reflector/Form1.cs


3. Создание программы конвертера температуры в Windows Forms. Конвертер температуры автоматически делает пересчет в градусы Цельсия, Фаренгейты и Кельвин. В приложении пользователю предоставлен доступ к сборке в корне папки Debug приложения. В этом приложении используется механизм позднего связывания при создании экземпляра объекта с использованием только рефлексии.
Приложение: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Task4_converter/ConverterTemperature.rar
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Task4_converter/Form1.cs


4. 
