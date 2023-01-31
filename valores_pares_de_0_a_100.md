internal class Program
{
    private static void Main(string[] args)
    {
        Console.WriteLine("Contrua um programa em c# que imprima todos os números pares entre 0 e 100");

        for(int x=0; x<=100; x++ )
        {
            if (x % 2 == 0)
            {
                Console.WriteLine(" " + x);
            }
           
        }
    }
}