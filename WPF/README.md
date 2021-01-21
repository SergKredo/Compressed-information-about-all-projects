Основные проекты учебного курса C#./Net developer, реализованные по технологии WPF(Windows Presentation Foundation):

1. Приложение "File change tracking NT-service by Serg Kredo". Данное WPF приложение написано с использованием технологий разработки асинхронного программирования Async&Await и Domains & NT Services в .Net Framework. Приложение фиксирует изменения производимые сторонними apps над файловой системой компьютера.
Релиз приложения (запускать от администратора): https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/Task2/ChangeWithFilesonDisks.exe
Релиз NT службы (для анализа изменений файловой системы): https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/ServiceChangeLog/ServiceChangeLog.exe


2. Приложение "Currency Info by Serg Kredo" позволяет найти текущую информацию о курсах валют в банках и обменниках Украины. В программе реализованы технологии асинхронного программирования (Async&Await) и паттерна проектирования MVVM (Model-View-ViewModel). Также применены фильтры для автоматизации процессов поиска курса валют.
Релиз приложения: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson15/Currency%20Info/Currency%20Info.exe


3. Новый улучшенный релиз приложения "File Finder, editor, archiver, color constructor by SergKredo v.2" поисковика файлов на компьютере. Программа имеет такие улучшенные характеристики:
- возможность производить глубокий и по единичный поиск файлов как с указанным расширением, так и по всему массиву (более 100 основных встречающихся в Windows 10 форматов расширений);
- добавлена возможность в окне отображения программы просматривать текстовую информацию основных часто встречающихся форматов файлов: .txt, .pdf, .rtf, .doc, .docx, .html, .dat, .log, .xps и т.д.;
- добавлена возможность создавать пользовательский цветовой дизайн элементов интерфейса программы.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson3/SeacherAndTextViewer/MainWindow.xaml.cs


4. Приложение для поиска файлов, отображения информации о файлах и архиватор в настольной версии на C#. Алгоритм программы позволяет обойти защиту доступа к системным каталогам до уровня 4. Приложение для поиска файлов занимает в 3 раза меньше времени, чем стандартный поисковик из Windows10. Эффективность поиска составила около 100%. Удалось найти все тестовые файлы. Также в приложении есть возможность просматривать данные текстовых файлов. И в завершение проекта добавлена возможность сжатия файлов двумя способами.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson3/SearchEngineInWPF/MainWindow.xaml.cs


5. Приложение "StopWatch by SergKredo" выводит показания секундомера. Окно имеет кнопки запуска, остановы и сброса секундомера. Для реализации секундомера использовался паттерн MVP.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Essential_MyProjects/tree/master/Lesson12_Homework/StopWatch(Task3)

