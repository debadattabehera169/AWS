|S.NO |commands |output |
|--- |--- |--- |
|01 |**mkdir test** | make directory having name test |
|02 |**mkdir -p test1/test2** | create both test1 directory and test2 directory inside test1 |
|03 |**mkdir -p tmp/xyz/{a/{a1,a2,a3},b/{b1,b2,b3}}** | it create two directory a and b and also create 3 more directory in each |
|04 |**rmdir test** | remove directory having name test |
|05 |**rm -r xyz** | remove recursively(means dlt all the file present inside it) the xyz directory |
|06 |**rm -rv test** |remove the test directory and also gives the  verbose(v) that test directory is removed |
|07 |**mkdir test/test1/test2 -rv** | it remove only test2 and gives the verbose,rm cmd is used to dlt file or folder |
|08 |**rm -rvf** |remove forcefully and gives verbose |
|09 |**ls, ls-a, ls-l,ls ~. ls-lh, ls /, ls -l /b** |show all the list of current folder, show all the hidden file, show all the file in long format.shows all the file present in home directory. shows long files in human readable file. shows all file in root directory, shows all the file in root directory starting from b |
|10 |**- --- --- --- 1 owner group_owner size date file_name** |-(show us file(-),directory(d),link(l)) ---(user) ---(group) ---(others) gives read, write and execute permission (1)it shows us inode table |
|11 |**ln -s /tmp/ ~/my_tmp_shortcut** | create short cut of any file in main folder(~) |
|12 |**cp test.txt ~/** |copied test.txt fiel to destination file ,here dest fiel is home |
|13 |**cat ~/copy.txt** | check by opening the file copy.txt is present in home or not |
|14 |**cp test.txt test1.txt test2.txt test_dir** | copy all the files into the test_dri |
|15 |**mv test_dir/ test** | it will move all the content to the test folder (if exist) or it will rename the folder |
|16 |**ln -s mydir/ ~/test** |we cant create short link of dir but cant create a hardlink ,incase we after creation of soft link if we dlt the folder and click on softlink it will never open thats called **dangling problem** |
|17 |**ln -s /temp/ /temp/rf** |here we are creating a softlink inside that file, it will open that endlessly again and again |