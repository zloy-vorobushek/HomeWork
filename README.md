# HomeWork
using System;
using System.Collections.Generic;
using System.Linq;
using System.Media;
using System.Security.Cryptography;
using System.Text;
using System.Text.RegularExpressions;
using System.Threading.Tasks;
using System.Xml.Linq;

namespace HomeWork
{
    class Program
    {
        static void Main()
        {
            Console.WriteLine("Как вас зовут?");
            string name = Console.ReadLine();
            Console.WriteLine("Сколько вам лет?");
            int age = int.Parse(Console.ReadLine());
            Console.WriteLine("Кто вы по знаку зодиака?");
            string zodiacSign = Console.ReadLine();
            Console.WriteLine("Где вы работаете?");
            string work = Console.ReadLine();
            Console.WriteLine($"Вас зовут {name}, вам {age} год, вы {zodiacSign} и работаете {work}.");
        }
    }
}
