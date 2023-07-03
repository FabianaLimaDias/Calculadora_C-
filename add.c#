using System;
using System.Collections.Generic;
using System.Linq;
using System.Runtime.Remoting.Channels;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp3
{
    class Calculadora
    {
        static void Main(string[] args)
        {
            int numero1, numero2;
            int desconto;
            int resultadoSoma;
            int resultadoMultiplicacao;
            int resultadoDesconto;

            char resp;

            while (true)
            {
                Console.WriteLine("\nCalculadora Simples");
                Console.WriteLine("1. Somar dois números");
                Console.WriteLine("2. Multiplicar dois números");
                Console.WriteLine("3. Desconto");
                Console.WriteLine("4. Sair");

                Console.Write("Escolha uma opção: ");
                resp = Console.ReadKey().KeyChar;
                Console.WriteLine();

                if (resp == '1')
                {
                    Console.WriteLine("Digite dois números inteiros para soma: ");
                    numero1 = int.Parse(Console.ReadLine());
                    numero2 = int.Parse(Console.ReadLine());
                    resultadoSoma = numero1 + numero2;
                    Console.WriteLine("A soma dos dois números é: " + resultadoSoma);
                }
                else if (resp == '2')
                {
                    Console.WriteLine("Digite dois números inteiros para multiplicação: ");
                    numero1 = int.Parse(Console.ReadLine());
                    numero2 = int.Parse(Console.ReadLine());
                    resultadoMultiplicacao = numero1 * numero2;
                    Console.WriteLine("O resultado da multiplicação é: " + resultadoMultiplicacao);
                }
                else if (resp == '3')
                {
                    Console.WriteLine("Digite o valor do produto: ");
                    numero1 = int.Parse(Console.ReadLine());
                    desconto = int.Parse(Console.ReadLine());
                    resultadoDesconto = numero1 - (numero1 * desconto /100);
                    Console.WriteLine("O desconto obtido é: " + resultadoDesconto);
                }
                else if (resp == '4')
                {
                    Console.WriteLine("Saindo...");
                    break;
                }
                else
                {
                    Console.WriteLine("Opção inválida. Tente novamente.");
                }
            }
        }
    }
}
