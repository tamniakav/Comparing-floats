# Comparing-floats
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Comparing_Floats
{
    class Program
    {
        static void Main(string[] args)
        {
            double firstNumber = double.Parse(Console.ReadLine());
            double secondNumber = double.Parse(Console.ReadLine());

            double difference = Math.Abs(firstNumber - secondNumber);

            double eps = 0.000001;

            bool smallDifference = true;

            if (difference > eps)
            {
                smallDifference = false;

                Console.WriteLine(smallDifference);
            }
            else
            {
                Console.WriteLine(smallDifference);
            }
        }
    }
}
