using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Unidad_I
{
    class Program
    {
        static void Main(string[] args)
        {


            // Tipos de datos compuestos 
            #region Array

            // Declaración de arreglos de diferentes tipos de datos

            // Arreglo de enteros sin inicializar
            int[] aiNumeros1 = null;
            // Arreglo de enteros con tamaño definido (valores por defecto: 0)
            int[] aiNumeros2 = new int[5];

            // Arreglo de enteros con valores iniciales
            int[] aiNumeros3 = { 0, 1, 2, 3, 4, 5 };
            aiNumeros3[1] = 600;
            for (int i = 0; i < aiNumeros3.Length; i++)
            {
                Console.WriteLine("Ingresa un numero para el indice {0}:", i);
                aiNumeros3[i] = int.Parse(Console.ReadLine());
            }

            for (int i = 0; i < aiNumeros3.Length; i++)
            {
                Console.WriteLine("{0}:{1}", i, aiNumeros3[i]);
            }

            // Arreglo de cadenas sin inicializar
            string[] asCadenass1 = null;

            // Arreglo de cadenas con tamaño definido (valores por defecto: null)
            string[] asCadenass2 = new string[5];

            // Arreglo de cadenas inicializado con valores vacíos
            string[] asCadenass3 = { string.Empty, string.Empty, string.Empty, string.Empty, string.Empty };

            for (int i = 0; i < asCadenass3.Length; i++)
            {
                Console.WriteLine("ingresa una cadena");
                asCadenass3[i] = Console.ReadLine();
            }
            for (int i = 0; i < asCadenass3.Length; i++)
            {
                Console.WriteLine(asCadenass3[i]);
            }

            // Arreglo de dobles sin inicializar
            double[] adDecimales1 = null;

            // Arreglo de dobles con tamaño definido (valores por defecto: 0.0)
            double[] adDecimales4 = new double[5];

            // Arreglo de dobles con valores iniciales
            double[] adDecimales3 = { .0, .1, .2, .3, .4, .5 };

            // Arreglo de flotantes sin inicializar
            float[] afDecimales = null;

            // Arreglo de flotantes con tamaño definido (valores por defecto: 0.0f)
            float[] afDecimales2 = new float[5];

            // Arreglo de flotantes con valores iniciales
            float[] afDecimales3 = { .0f, .1f, .2f, .3f, .4f, .5f };

            // Arreglo de booleanos sin inicializar
            bool[] abCondiciones1 = null;

            // Arreglo de booleanos con tamaño definido (valores por defecto: false)
            bool[] abCondiciones2 = new bool[5];

            // Arreglo de booleanos con valores iniciales
            bool[] abCondiciones3 = { true, false, true, true, true };

            #endregion

            #region Strings

            Console.WriteLine("Ingresa una cadena:");
            // Declaración de una cadena de texto
            string texto = /*"  Hola, mundo!  "*/ Console.ReadLine();
            #region Manipulación

            // Elimina los espacios en blanco al inicio y al final de la cadena
            Console.WriteLine(texto.Trim());

            // Convierte la cadena a mayúsculas
            Console.WriteLine(texto.ToUpper());

            // Convierte la cadena a minúsculas
            Console.WriteLine(texto.ToLower());

            // Reemplaza la palabra "Hola" por "Adiós" en la cadena
            Console.WriteLine(texto.Replace("Hola", "Adiós"));

            // Inserta la cadena "Hey " en la posición 2
            Console.WriteLine(texto.Insert(2, "Hey "));

            // Elimina todos los caracteres desde la posición 5 en adelante
            Console.WriteLine(texto.Remove(5));


            #endregion

            #region Búsqueda y Comparación

            // Verifica si la cadena contiene la palabra "mundo"
            Console.WriteLine(texto.Contains("mundo"));

            // Verifica si la cadena comienza con un espacio
            Console.WriteLine(texto.StartsWith(" "));

            // Verifica si la cadena termina con "! "
            Console.WriteLine(texto.EndsWith("! "));

            // Devuelve la posición en la que aparece la palabra "mundo"
            Console.WriteLine(texto.IndexOf("mundo"));

            // Devuelve la última posición en la que aparece la letra 'o'
            Console.WriteLine(texto.LastIndexOf("o"));

            #endregion

            #region División y Unión

            // Divide la cadena en un array de palabras usando el espacio como separador
            string[] palabras = texto.Split(' ');

            // Une las palabras del array en una sola cadena separada por guiones
            Console.WriteLine(string.Join("-", palabras));

            #endregion

            #region Conversión

            // Convierte la cadena en un array de caracteres
            char[] caracteres = texto.ToCharArray();

            // Muestra la cantidad de caracteres en la cadena
            Console.WriteLine(caracteres.Length);

            #endregion

            #region Formato

            // Variables para usar en el formato de cadena
            string nombre = "Carlos";
            int edad = 25;

            // Usa string.Format para generar una cadena con variables
            Console.WriteLine(string.Format("Hola {0}, tienes {1} años.", nombre, edad));

            // Usa interpolación de cadenas para el mismo propósito
            Console.WriteLine($"Hola {nombre}, tienes {edad} años.");

            #endregion

            #endregion
        }
    }
}
