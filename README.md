# Coordinates :
﻿using System;

public class Program
{
    public static void Main()
    {
        double st, min, sek, wynik;

        Console.WriteLine("Podaj stopnie:");

        st = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("Podaj minuty:");

        min = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("Podaj sekundy:");

        sek = Convert.ToDouble(Console.ReadLine());

        wynik = st + (min / 60) + (sek / 3600);

        Console.WriteLine("Koordynaty w formacie dziesiętnym to " + wynik);

    }
}
