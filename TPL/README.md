Основные проекты учебного курса C#./Net developer, реализованные по технологии TPL(Task Parallel Library):

1. Создайте массив чисел размерностью в 1 000 000 или более. Используя генератор случайных
чисел, проинициализируйте этот массив значениями. Создайте PLINQ запрос, который
позволит получить все нечетные числа из исходного массива.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson14/Additional%20Task/Program.cs


2. Создайте два метода, которые будут выполняться в рамках параллельных задач. Организуйте
вызов этих методов при помощи Invoke таким образом, чтобы основной поток программы
(метод Main) не остановил свое выполнение.
Код проекта: https://github.com/SergKredo/ITVDN-Csharp_Professional_MyProjects/blob/master/Lesson14/Task%202/Program.cs
