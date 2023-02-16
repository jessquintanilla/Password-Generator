# Password-Generator
Generate easy and memorable passwords. Based off of the XKCD password scheme, this simple password generator takes in variables for the amount of words, numbers, symbols, and characters to create a unique password. Randomized words and sequences creates endless possibilities. 

![image](https://user-images.githubusercontent.com/98177563/219258080-59249059-2a1c-4430-b3de-fab427068648.png)

 ```
  usage: pwgen [-h] [-w WORDS] [-u UPPERCASE] [-n NUMBERS] [-s SYMBOLS] [-c CHARACTERS]
        
            Generate a secure, memorable password
            
            optional arguments:
                -h, --help            show this help message and exit
                -w WORDS, --words WORDS
                                      include WORDS words in the password (default=0)
                -u UPPERCASE, --uppercase UPPERCASE
            capitalize the first letter of CAPS random words
                                      (default=0)
                -n NUMBERS, --numbers NUMBERS
                                      insert NUMBERS random numbers in the password
                                      (default=0)
                -s SYMBOLS, --symbols SYMBOLS
                                      insert SYMBOLS random symbols in the password
                                      (default=0)
                -c CHARACTERS, --characters CHARACTERS
                                      insert CHARACTERS random symbols in the password
                                      (default=0)
  ```
  
  Example Usages:
  ```
 pwgen -w 4 -u 3 -n 2
 Excelle$ncies8Petulant7Archivinghindquarters

 pwgen --words 2 --symbols 5 --characters 2
 veggies&=Yxpatters`-]
  ```
