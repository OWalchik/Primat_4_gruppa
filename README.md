// testcpp.cpp : Этот файл содержит функцию "main". Здесь начинается и заканчивается выполнение программы.
//

#include <iostream>

int main()
{
    setlocale(LC_ALL, "Rus");
    


    bool flag = true;

    std::cout << "Тип данных: bool \n";
    std::cout << "Объем: " << sizeof(flag) << " байт \n";
    std::cout << "\n";

    char char_x = 12;

    std::cout << "Тип данных: char \n";
    std::cout << "Объем: " << sizeof(char_x) << " байт \n";
    std::cout << "Мин: " << CHAR_MIN << "\n";
    std::cout << "Макс: " << CHAR_MAX << "\n";
    std::cout << "\n";

    unsigned char  char_u = 222;

    std::cout << "Тип данных: unsigned char \n";
    std::cout << "Объем: " << sizeof(char_u) << " байт \n";
    std::cout << "Мин: " << 0 << "\n";
    std::cout << "Макс: " << UCHAR_MAX << "\n";
    std::cout << "\n";

    short short_x = 20000;

    std::cout << "Тип данных: short \n";
    std::cout << "Объем: " << sizeof(short_x) << " байт \n";
    std::cout << "Мин: " << SHRT_MIN << "\n";
    std::cout << "Макс: " << SHRT_MAX << "\n";
    std::cout << "\n";


    unsigned short short_u = 60000;

    std::cout << "Тип данных: unsigned short \n";
    std::cout << "Объем: " << sizeof(short_u) << " байт \n";
    std::cout << "Мин: " << 0 << "\n";
    std::cout << "Макс: " << USHRT_MAX << "\n";
    std::cout << "\n";

    int int_x = 20000;

    std::cout << "Тип данных: int \n";
    std::cout << "Объем: " << sizeof(int_x) << " байт \n";
    std::cout << "Мин: " << INT_MIN << "\n";
    std::cout << "Макс: " << INT_MAX << "\n";
    std::cout << "\n";

    unsigned int int_u = 30000;

    std::cout << "Тип данных: unsigned int \n";
    std::cout << "Объем: " << sizeof(int_u) << " байт \n";
    std::cout << "Мин: " << 0 << "\n";
    std::cout << "Макс: " << UINT_MAX << "\n";
    std::cout << "\n";

    long long_x = 310;
    
    std::cout << "Тип данных: long \n";
    std::cout << "Объем: " << sizeof(long_x) << " байт \n";
    std::cout << "Мин: " << LONG_MIN << "\n";
    std::cout << "Макс: " << LONG_MAX << "\n";
    std::cout << "\n";

    unsigned long long_u = 10000000000;

    std::cout << "Тип данных: unsigned long \n";
    std::cout << "Объем: " << sizeof(long_u) << " байт \n";
    std::cout << "Мин: " << 0 << "\n";
    std::cout << "Макс: " << ULONG_MAX << "\n";
    std::cout << "\n";

    long long l_long_x = 100000;

    std::cout << "Тип данных: long long \n";
    std::cout << "Объем: " << sizeof(l_long_x) << " байт \n";
    std::cout << "Мин: " << LLONG_MIN << "\n";
    std::cout << "Макс: " << LLONG_MAX << "\n";
    std::cout << "\n";

    unsigned long long l_long_u = 100000000;

    std::cout << "Тип данных: unsigned long long \n";
    std::cout << "Объем: " << sizeof(l_long_u) << " байт \n";
    std::cout << "Мин: " << 0 << "\n";
    std::cout << "Макс: " << ULLONG_MAX << "\n";
    std::cout << "\n";


    float float_x = 1234567890.123;

    std::cout << "Тип данных: float \n";
    std::cout << "Объем: " << sizeof(float_x) << " байт \n";
    std::cout << "Мин: " << FLT_MIN << "\n";
    std::cout << "Макс: " << FLT_MAX << "\n";
    std::cout << "\n";

    double double_x = 3.14159;

    std::cout << "Тип данных: double \n";
    std::cout << "Объем: " << sizeof(double_x) << " байт \n";
    std::cout << "Мин: " << DBL_MIN << "\n";
    std::cout << "Макс: " << DBL_MAX << "\n";
    std::cout << "\n";

    char char_alf = 'Д';

    std::cout << "Тип данных: char \n";
    std::cout << "Объем: " << sizeof(char_alf) << " байт \n";
    std::cout << "Мин: " << CHAR_MIN << "\n";
    std::cout << "Макс: " << CHAR_MAX << "\n";
    std::cout << "\n";


    
    std::cout << char_alf;

    return 0;
}
