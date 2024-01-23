# Practic14

    using System;
    using System.Collections.Generic;
    using System.Linq;
    using System.Text;
    using System.Threading.Tasks;

namespace Practic14
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Задание 1. Вывести на экран в столбик первые 10 натуральных чисел (циклы с условием, цикл с параметром)
            /*
            Console.WriteLine("Задание 1. Вывести на экран в столбик первые 10 натуральных чисел (циклы с условием, цикл с параметром)");
            int i = 0;
            while (i < 10)
            {
                Console.WriteLine(i);
                i++;
            }
            Console.WriteLine();



            for (int j = 0; j < 10; j++)
            {
                Console.WriteLine(j);
            }
            Console.ReadLine();
            */
            


            //Задание 2. Вывести на экран целые числа из интервала от 1 до n (цикл с параметром)
            /*
            Console.WriteLine("Задание 2. Вывести на экран целые числа из интервала от 1 до n (цикл с параметром)");
            Console.WriteLine("Введите число n");
            int n = Convert.ToInt32(Console.ReadLine());
            for (int j = 1; j <= n; j++)
            {
                Console.WriteLine(j);
            }
            Console.ReadLine();
            */




            //Задание 3. Вывести в столбик 5 раз слово «Привет!» (циклы с условием)
            /*
                Console.WriteLine("Задание 3. Вывести в столбик 5 раз слово «Привет!» (циклы с условием)");
                int i = 0;
                while (i < 5)
                {
                    Console.WriteLine("Привет!");
                    i++;
                }
                Console.ReadLine();
                Console.Clear();
            */



            //Задание 4. С использованием цветового оформления консоли:
            //а) вывести на экран горизонтальную строку из 18 символов;
            /*
            Console.ForegroundColor = ConsoleColor.Gray;
            Console.BackgroundColor = ConsoleColor.Green;
            for (int i = 0; i < 18; i++)
            {
                Console.Write("*");
            }
            */
            //б) вывести на экран вертикальную строку из 25 символов.
            /*
            Console.WriteLine();
            for (int i = 0; i < 25; i++)
            {
                Console.WriteLine("*");
            }
            Console.ReadLine();
            */

        }

    }
    
}
