# h-seyin-yasal
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("1.Sayıyı Giriniz : ");
            int x = Convert.ToInt32(Console.ReadLine());
            Console.Write("Binary karşılıgı");
            Console.Write(Convert.ToString(Convert.ToUInt32(x), 2));
            Console.Write("2.sayıyı giriniz:");
            int y = Convert.ToInt32(Console.ReadLine());
            Console.Write("binary karsılıgı:");
            Console.WriteLine(Convert.ToString(Convert.ToInt32(y), 2));
            Console.WriteLine();

            Console.Write("binary toplamı :");
            Console.WriteLine(Convert.ToString(Convert.ToInt32(x + y), 2));
            Console.Write("ondalık sonuc :");
            Console.WriteLine(Convert.ToString(Convert.ToInt32(x + y)));
            Console.ReadKey();


        }
    }
}
