# C Basics    
## Data Types     
| data type | description |          
|---|---|         
| int | use to store whole numbers |        
| float | use to store decimal numbers with single precision |       
| double | use to store decimal numbers with double precision |      
| char | use to store a single character |          
| bool | use to store a true or a false value |           
| void | indicates that no value is returned or stored |          

## format specifiers 
| format specifiers | description |
|---|---|
| %d | used for signed integers |
| %u | used for unsigned integers |
| %o | used for octal integers |
| %x | used for hexa-decimal integer in lower case |
| %X | used for hexa-decimal integer in upper case |
| %f | used for floating point number |
| %e | used for floating point number in scientific notation |
| %c | used for single character |
| %s | used for string |
| %ld | used for long integer |

## input/output functions
- scanf() - used to take input from the user
- printf() - used to display output
- getchar() - used to read a single character
- putchar() - used to display a single character
- fgets() - used to read a line of text
- puts() - used to display a string 

## escape sequences 
| escape sequence | meaning | example |
|---|---|---|
| \n | new line | printf("hello\nworld"); |
| \t | tab | printf("hello\tworld"); |
| \a | alert (beep) | printf("hello\aworld"); |
| \\ | backslash | printf("\\"); |
| \b | back space | printf("hello\bworld"); |

## precision 
precision is specified by placing a dot (.) followed by the number of digits  to be displayed after the decimal point, before f.
### for examaple 
- %.2f - displays two digits after the decimal point
- %.4f - displays four digits after the decimal point 

