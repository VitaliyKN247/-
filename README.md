# - Hello World!


/* написать программу, которая из имеющихся массива строк формирует массив строк, длинна, которых меньше или равна 3 символам */


string[] S;
Console.WriteLine("Введите массив строк через пробел");
string symvol = Console.ReadLine()!;
S = symvol.Split(' ')!;
var result = new string[S .Length];
var realSize = 0;
