namespace ConsoleApp1_arreglos
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
            // Declaración de arreglos
            string[] empleados = { "Martha", "Maria", "Esther", "Abigail", "Marcela" };
            string[] departamentos = { "Cocina", "Ama de llaves", "Mantenimiento", "Gerencia", "Administración" };
            string[] combinados = new string[empleados.Length];

            Console.WriteLine("Resultados:\n");

            // Combinación de empleados y departamentos
            for (int i = 0; i < empleados.Length; i++)
            {
                combinados[i] = $"{empleados[i]} - {departamentos[i]}";
                Console.WriteLine(combinados[i]);
            }

            Console.WriteLine("\nPrcione la tecla de su preferencia para fializar ...");
            Console.ReadKey();


        }
    }
}
