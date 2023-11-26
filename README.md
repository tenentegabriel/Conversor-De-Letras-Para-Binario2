# Conversor-De-Letras-Para-Binario2

#include <iostream>
#include <bitset>

int main()
{
	while (true)
	{
		char letter;
		std::cin >> letter;
		std::bitset<8> binary(letter);

		std::cout << "O Codigo Binario De " << letter << "  e: " << binary << std::endl;
	}
	return 0;
}
