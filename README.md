# Flex-clite
Lexical analyzer which converts program to series of tokens
The code recognises the following tokens:
  Integer 
  Float
  Keyword ( if , else , while , for , int , float )
  Identifier 
  Assignment ( = )
  Comparison ( == , < , > , <= , >= )
  Operator ( + , - , * , / )
  Open and closed brackets ( { , } )
  Open and closed paren ( ( , ) )
  semicolon ( ; ) 
The code also ignores whitespaces , tab , newline and comments.

  
# Code Execution
1) Run the flex code using flex command 
  $ flex get_tokens.l

2) Now a file lex.yy.c will be generated. Run generated c code using the command
  $ gcc lex.yy.c -ll

3) Give filename as a argument to a.out   
  $ ./a.out Sampleprogram.c

4) An output file named flex_output.txt is generated which has tokens followed by token values.
