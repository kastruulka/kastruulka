public static void Main()
    {
        int length = GetLength();

    }
    static int GetLength()
    {
        Console.Write("Введите размер множества (1-8): ");
        int userInput = Convert.ToInt32(Console.ReadLine());

        if(userInput < 1 || userInput > 8)
        {
            Console.WriteLine("Неверный размер множества. Повторите ввод.");
            return GetLength();
        }
        return userInput;
    }

#я ничего не понимаю
+ как блять работает эта хуета
