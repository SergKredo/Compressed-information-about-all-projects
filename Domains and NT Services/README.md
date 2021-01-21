Основные проекты учебного курса C#./Net developer, реализованные с использованием технологии Domains and NT Services:

1. Приложение "File change tracking NT-service by Serg Kredo". Данное WPF приложение написано с использованием технологий разработки асинхронного программирования Async&Await и Domains & NT Services в .Net Framework. Приложение фиксирует изменения производимые сторонними apps над файловой системой компьютера. Релиз приложения (запускать от администратора): https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/Task2/ChangeWithFilesonDisks.exe Релиз NT службы (для анализа изменений файловой системы): https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/ServiceChangeLog/ServiceChangeLog.exe

2. Создайте приложение WindowsForms, которое позволит безопасно запускать сборки. В интерфейсе предусмотрите возможность выбора ограничения привилегий для запускаемой сборки. Возможность запускать сборки в домене. Выполнение сборки ограничено правами доступа.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/Additional%20Task/Form1.cs

3. Создайте службу Windows, которая будет мониторить жесткие диски и при изменениях файловой системы из этих дисков записывать информацию (полный путь) в текстовый файл.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson16/ServiceChangeLog/Service1.cs

