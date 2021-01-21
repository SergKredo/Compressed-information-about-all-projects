Основные проекты учебного курса C#./Net developer, реализованные по технологии WinForms(Windows Forms):

1. Один из последних своих научных IT проектов. Это микс двух языков программирования - облегченные C++ на платформе ардуино и C#./Net. Приложение "Choper by Serg Kredo" реализовано в WinForms. Задача стояла автоматизировать некие элементы в экспериментальной установке (сервопривод с различными датчиками) для научной деятельности в голографии. Реализовано полнофункциональное приложение плоттер на языке C#, способное отображать данные с датчиков платы ардуино в виде кривых. Для сглаживания кривых применялись различные фильтры: Калмана, бегущая средняя, медиана. Весь массив полученных данных можно сохранять в текстовом формате с последующей обработкой в специальных редакторах. В приложении использовалась технология асинхронного программирования Async&Await. Код проекта: https://github.com/SergKredo/Arduino-C-Windows-Forms-/blob/master/ServoApp/Form1.cs и скетч ардуино: https://github.com/SergKredo/Arduino-C-Windows-Forms-/blob/master/SketchArduino/SketchArduino.ino


2. Новый улучшенный релиз десктопной версии приложения "Reflector by Serg Kredo v.2" с возможностью выбора типов сборки, членов типа и информации об атрибутах типов и членов типа.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson7/Task%203_New%20Reflector/Form1.cs


3. Создание программы конвертера температуры в Windows Forms. Конвертер температуры автоматически делает пересчет в градусы Цельсия, Фаренгейты и Кельвин. В приложении пользователю предоставлен доступ к сборке в корне папки Debug приложения. В этом приложении используется механизм позднего связывания при создании экземпляра объекта с использованием только рефлексии.
Приложение: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Task4_converter/ConverterTemperature.rar
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Task4_converter/Form1.cs


4. Реализовал десктопную версию приложения "Reflector by SergKredo v.1". Приложение позволяет раскрывать основные метаданные С#./Net сборки с расширениями (exe, dll), определять основные типы данных (классы, классы generics, статические, nested классы, интерфейсы, структуры, делегаты, перечисления и т.д.), их члены (поля, методы, конструкторы, свойства и т.д.) с последующим сохранением в файл.
Приложение: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Additional%20Task/Reflector%20by%20SergKredo.exe
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson6/Additional%20Task/Form1.cs


5. Было огромное желание написать аналог простого калькулятора как в Windows 10. Приложение калькулятор в Windows 10 написан на C++ и до сих пор продолжает дополняться новыми, более сложными функциями. На выполнение этой задачи у меня ушло больше месяца. Программа написана на языке C# в Windows Forms с использованием шаблона проектирования MVP (Model View Presenter) и имеет около 3 тысяч строк кода. Выполняет операции аналогично калькулятору в Windows 10.
Код проекта: https://github.com/SergKredo/Calculator-as-Windows10/blob/master/Presenter.cs


6. Создайте приложение WindowsForms, которое позволит безопасно запускать сборки. В интерфейсе предусмотрите возможность выбора ограничения привилегий для запускаемой сборки. Возможность запускать сборки в домене. Выполнение сборки ограничено правами доступа.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/Additional%20Task/Form1.cs



