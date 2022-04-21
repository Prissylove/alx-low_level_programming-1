0. 98 Battery st.
1.2. Don't swap horses in crossing a stream

4. This report, by its very length, defends itself against the rist of being read
 
6. I do not fear computers. I fear the lack of them

8. I do not fear computers. I fear the lack of them

A good engineer thinks in reverse and asks himself about the stylistic consequences of the components and systems he proposes : A C function that reverses a string.
Prototype: void rev_string(char *s);
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 5-main.c 5-rev_string.c -o 5-rev_string

Half the lies they tell about me aren't true : A C function program that prints every other character of a string, starting with the first character, followed by a new line.
Prototype: void puts2(char *str);
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 6-main.c 6-puts2.c -o 6-puts2

Winning is only half of it. Having fun is the other half : A C function that prints half of a string, followed by a new line.
Prototype: void puts_half(char *str);
The function should print the second half of the string.
If the number of characters is odd, the function should print the last n characters of the string where n = (length_of_the_string - 1) / 2)
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 7-main.c 7-puts_half.c -o 7-puts_half

Arrays are not pointer : A C function program that prints n elements of an array of integers, followed by a new line.
Prototype: void print_array(int *a, int n);
Where n is the number of elements of the array to be printed.
Numbers must be separated by comma, followed by a space.
The numbers should be displayed in the same order as they are stored in the array.
You are allowed to use printf.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 8-main.c 8-print_array.c -o 8-print_array

strcpy : A C function program that copies the string pointed to by src, including the terminating null byte (\0), to the buffer pointed to by dest.
Prototype: char *_strcpy(char *dest, char *src);
Return value is the pointer to dest.
FYI: The standard library provides a similar function: strcpy. Run man strcpy to learn more.
Read more here about strcpy.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 9-main.c 9-strcpy.c -o 9-strcpy
