# Flex-clite
Lexical analyzer which converts program to series of tokens <br/>
The code recognises the following tokens: <br/>
  Integer  <br/>
  Float  <br/>
  Keyword ( if , else , while , for , int , float )  <br/>
  Identifier  <br/>
  Assignment ( = )  <br/>
  Comparison ( == , < , > , <= , >= )  <br/>
  Operator ( + , - , * , / )  <br/>
  Open and closed brackets ( { , } ) <br/>
  Open and closed paren ( ( , ) ) <br/>
  semicolon ( ; )  <br/>
The code also ignores whitespaces , tab , newline and comments. <br/>

  
# Code Execution
1) Run the flex code using flex command  <br/>
  $ flex get_tokens.l <br/>

2) Now a file lex.yy.c will be generated. Run generated c code using the command <br/>
  $ gcc lex.yy.c -ll <br/>

3) Give filename as a argument to a.out </br>
  $./a.out Sampleprogram.c <br/> 
 

4) An output file named flex_output.txt is generated which has tokens followed by token values. <br/>
