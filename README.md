# 010101
double a, b, s;
            char c;
            s = 0;
            a = double.Parse(Console.ReadLine());
            b = double.Parse(Console.ReadLine());
            c = Console.ReadKey().KeyChar;
            if (c == '+')
            {
                s = a + b;

            }
            else if (c == '-')
            {
                s = a - b;
            }
            else if (c == '*')
            {
                s = a * b;
            }
            else if (c == '/')
            {
                s = a / b;
            }
            Console.WriteLine("\n"  +s);
