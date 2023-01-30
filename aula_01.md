internal class Program
{
    private static void Main(string[] args)
    {
        int x;
        int y;
        int w;
        Console.WriteLine("Informe o primeiro valor:");
        x = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Informe o segundo valor:");
        
        y = Convert.ToInt32(Console.ReadLine());
        w = x + y;
        Console.WriteLine("resposta "+ w);
        
    }
}