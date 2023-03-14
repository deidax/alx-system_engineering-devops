for anybody trying to do the last advanced task, here's some hints: 
the task is about adding two values of base *water* and *stir.*.
*water* is a word that has *5* characters, and the only characters that can be used are *w,a,t,e,r* (just like binary you can only use 0 and 1 here you can only use w,a,t,e,r).
*stir.* is a word that has *5* characters, and the only characters that can be used are *s,t,i,r,.*
now the task is asking *two numbers* stored in *$WATER* and *$STIR*, but the example that the task is showing is not numbers but just some random letters. so first we should convert those letters to numbers. how? simply replace using *tr*
*water* = 01234 (each letter represent a number starting from 0), samething for *stir.*
so ewwatratewa will become 3001.. and so one after that you should convert that number to base 5 because *water* is based on *5* characters (you do the same thing for *stir.*) and then you add both result.
final step is to convert that output to base *bestchol* (notice it has *8* characters), how? convert your output to base 8 (think of printf and *o*ctal, octal is base 8). and then replace the numbers with the correct characters.

