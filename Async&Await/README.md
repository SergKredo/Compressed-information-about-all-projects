Основные проекты учебного курса C#./Net developer, реализованные по технологии Async&Await:

1. Десктопные версии приложений: "File change tracking NT-service by Serg Kredo", "Currency Info by Serg Kredo", "Choper by Serg Kredo".

2. Переделайте дополнительное задание из урока №11 с использованием конструкции async&await
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson15/Additional%20Task/Program.cs

3. Создайте WPF приложение, разместите в окне TextBox и две кнопки. При нажатии на первую
    кнопку в TextBox выводится сообщение «Подключен к базе данных» при этом в обработчике
    установите задержку в 3-5 сек для имитации подключения к БД, также данная кнопка запускает
    таймер, который с периодичностью в несколько секунд выводит в TextBox сообщение «Данные
    получены». При нажатии на вторую кнопку по аналогии с первой отключаемся от базы (с
    задержкой), выводим сообщение и останавливаем таймер.
    Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson15/Task2/MainWindow.xaml.cs
