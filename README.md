# frequency-of-word-is
using System; <br>
namespace Exercises<br> 
{ <br>
 class FrequencyIS <br>
 { <br>
  static void Main(string[] args) <br>
  { <br>
   int count=0; <br>
   string inputString;<br> 
   Console.WriteLine("\n----------- Frequency of word 'is' ----------"); <br>
   Console.Write("\n Enter the input string: "); <br>
   inputString = Console.ReadLine(); <br>
   char[] separator = { ',', ' ', '.' , '!', '\n' }; <br>
   string testString = inputString.ToLower(); <br>
   String[] outcomes = testString.Split(separator); <br>
   foreach(String s in outcomes) <br>
   { <br>
    Console.WriteLine(s); <br>
    if(s == "is") <br>
     count++; <br>
   } <br>
   Console.WriteLine("\n Number of 'is' in '" + inputString + "' is: " + count);<br>
  }<br>
 }<br>
}<br>
