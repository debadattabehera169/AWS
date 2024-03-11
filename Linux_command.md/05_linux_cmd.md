|S.NO |commands |output |
|--- |--- |--- |
|01 |**touch .dummy.txt** |create a hidden file |
|02 |**ls -a**|show all the fiels including hidden files |
|03 |**touch -a 0927023724 .dummy.txt** |modify the modification date |
|04 |**wc linuxcmd.txt** |it will shows us number of lines, no words, no of chars |
|05 |**wc -l linuxcmd.txt** |shows only line of file like this use wc -c for char, wc -w for words |
|06 |**cut -f 1 test5.txt** |it will show the first word of the sentence written in test5.txt file (in this all words are separated with tab) (f for field) |
|07 |**cut -f 2-5 test5.txt** |it will show all the word from 2nd to 5th |
|08 |**file test5.txt** |shows the types of file |
|10 |**who** |show the details of user |
|11 |**sort test1.txt**|sort all the content of the test1.txt file |
|12 |**sort -o result.txt -u test1.txt test2.txt**|it merge two file and gives the ans in sorted order in output file i.e.  result.txt (-u)is used for unique value |
|13 |**cat test5.txt**|shows the content of the  existing file |
|14 |**cat Dev**|it act like a input device and return dev also as my input value is that. and press ctrl+c ,if we place ctrl+d it will repeat the value |
|15 |**cat >std_out.txt**|after pressing enter what we are giving input it will store in std_out.txt file at end enter ctrl+d  (<) this is used to show output |
|16 |**ls >ls_out.txt**|we can store all the output in a single file |
|17 |**cat >new_1_txt <old_1_txt**|it will read from old_1_txt and gives the output in new_1.txt file |
|18 |**ls**|in this bydefault we hv ls 1. ls 0 means std input, ls 1 means std output, ls 2 means std errors |
|19 |**lssss 2>error2.txt**|as we give 2 vaue so it will store all the error cmd in error2.txt file |
|20 |**cat >test1.txt**|as we use single >symbol it will replace all the content of test1.fiel with new one |
|21 |**cat >>test1.txt**|it append all the new content with old content |
|22 |**lsss >> output.txt 2>&1**|it will show our error cmd in output section |
|23 |**ls  sort**|in this output of ls cmd is used as input of sort cmd,bcz of table i cant givethe bar symbol.but bet ls and sort the bar is present |
|24 |**who >who.txt**|create a hidden file |
