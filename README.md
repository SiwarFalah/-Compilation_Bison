# -Compilation_Bison

nput: tennis_input.txt

output: Woman with greatest number of wins at Wimbledon: Martina Navratilova (9 wins)

To run this program:

1. make - flex tennis.lex , bison -d tennis.y , gcc -o tennis lex.yy.c tennis.tab.c

2.  ./tennis tennis_input.txt
