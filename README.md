# 270219
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp2
{
    class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine("Please type two numbers");
        
            int a = Convert.ToInt32(Console.ReadLine());
            

            int b = Convert.ToInt32(Console.ReadLine());
            



            if (a / b == 0) 
                {
                Console.WriteLine(a / b);
                } 
            else (a /b ! ==0)
               {
                Console.WriteLine("Please Type another two numbers");
               
               }
        }
    }
}
