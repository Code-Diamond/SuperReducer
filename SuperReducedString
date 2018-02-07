using System;
using System.Collections.Generic;
using System.IO;
using System.Linq;
class SuperReducedString
{
    public static string reducedString;
    public static int flagCounter=0;
    public static string startingString;
    public static void Main(String[] args)
    {
        while (true)
        {
            Console.Write("input:");
            startingString = Console.ReadLine();
            reducedString = startingString;
            
            for (int i = 0; i < 28; i++)
            {
                SuperReducer(reducedString);
            }

            DisplayResult();
                
            Console.ReadLine();
        }
    }

    public static void DisplayResult()
    {
        //Console.WriteLine("Original: " + startingString);
        //Console.WriteLine("Reduced : " + reducedString);

        if(reducedString=="")
        {
            Console.WriteLine("Empty String");
        }
        else
        {
            Console.WriteLine(reducedString);
        }
    }
    
    public static void SuperReducer(string inputString)
    {

        inputString = inputString.Replace("aa", "");
        inputString = inputString.Replace("bb", "");
        inputString = inputString.Replace("cc", "");
        inputString = inputString.Replace("dd", "");
        inputString = inputString.Replace("ee", "");
        inputString = inputString.Replace("ff", "");
        inputString = inputString.Replace("gg", "");
        inputString = inputString.Replace("hh", "");
        inputString = inputString.Replace("ii", "");
        inputString = inputString.Replace("jj", "");
        inputString = inputString.Replace("kk", "");
        inputString = inputString.Replace("ll", "");
        inputString = inputString.Replace("mm", "");
        inputString = inputString.Replace("nn", "");
        inputString = inputString.Replace("oo", "");
        inputString = inputString.Replace("pp", "");
        inputString = inputString.Replace("qq", "");
        inputString = inputString.Replace("rr", "");
        inputString = inputString.Replace("ss", "");
        inputString = inputString.Replace("tt", "");
        inputString = inputString.Replace("uu", "");
        inputString = inputString.Replace("vv", "");
        inputString = inputString.Replace("ww", "");
        inputString = inputString.Replace("xx", "");
        inputString = inputString.Replace("yy", "");
        inputString = inputString.Replace("zz", "");
        reducedString = inputString;
    }

}
