# which
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace switch
{

   internal class Program 
    {
    	
        public static void Main() 
        {
           int ch;
           string continue;
           do
           {
           	int per;
           	Console.WriteLine("Enter your percentage:");
           	per=Convert.ToInt32(Console.ReadLine());
           	Console.WriteLine("Enter your choice(1-above10%)(2-above 60%)(3-above 50%)");
           	switch(ch)
           	{
           		case 1:
           		Console.WriteLine("you got DISTINCTION with:"+per);
           		breck;
           		case 2:
           		Console.WriteLine("you got with:"+per);
           		breck;
           	}
        }
    }
}
