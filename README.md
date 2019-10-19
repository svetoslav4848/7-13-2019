# 7-13-2019
задачи
задача 1

using System;

namespace grade
{
    class Program
    {
        static void Main(string[] args)
        {
            double grade = double.Parse(Console.ReadLine());
            if (grade >= 5.50)
            {
                Console.WriteLine(" Excellent ");
            }

            else if (grade >= 4.50)
            {
                Console.WriteLine(" Very Good ");
            }

            else if (grade >= 3.50)
            {
                Console.WriteLine(" Good ");
            }

            else if (grade >= 2.50)
            {
                Console.WriteLine(" Medium ");
            }

            else if (grade >= 2.00)
            {
                Console.WriteLine(" Terrible ");
            }
        }
    }
}

задача 2
---------------------------------------------------------------------------------------------------------------------------------

using System;

namespace contry___language
{
    class Program
    {
        static void Main(string[] args)
        {
            string contry = Console.ReadLine();

            if (contry == "USA")
            {
                Console.WriteLine("language is English");
            }

               else if(contry == "England")
            {
                Console.WriteLine("language is English");
            }
            if (contry == "Mexico")
            {
                Console.WriteLine("language is Spanish");
            }
            else if (contry == "Spain")
            {
                Console.WriteLine("language is Spanish");
            }
            else if (contry == "Argentina")
            {
                Console.WriteLine("language is Spanish");
            }
            else
            {
                Console.WriteLine("Unknow");
            }
}
                }
            }
        
    
--------------------------------------------------------------------------------------------------------------------------------

