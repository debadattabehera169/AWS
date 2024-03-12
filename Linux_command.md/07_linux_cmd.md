|S.NO |commands |output |
|--- |--- |--- |
|01 |**chmod o-r test.txt** |change the permission or deny for others to only read the file  |
|02 |**chmod user u+x test.txt** |give the user the permission to execute |
|03 |**chmod go+rwx test.txt** |give group and other to read, write and execute permisson |
|04 |**chmod ugo+w test.txt or chmod a+w test.txt** |to give user group and other we can simply write a(for all) |
|05 |**chmod 764 test.txt** |to give user all permission, group to read and write permission and for others read permission |
|06 |**chmod 1764 test.txt** |here if we give any group to execute permission. then all the user present in the sm group can manipulate other user's file also for this we place a octalone (1) before the 764 permission given |