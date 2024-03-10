
|S.NO |commands |output
|--- |--- |--- |
|01 |users |show all username |
|02 |sudo adduser test1 |asking the details then user created |
|03 |clear |to clean the terminal |
|04 |id |show the  id of the user |
|05 |groups |show all groupname |
|06 |su test1 |switch user enter password and enter |
|07 |exit |exit form test1 user to dev user |
|08 |sudo usermod -a -G sudo test1 |append(-a) the  test1 file to the sudo group(-G) to give sudo privilage |
|09 |sudo addgroup group_test1 |a new group as test1 created |
|10 |sudo usermod -g group_test1 test1  |changing the primary group of any user existing in that group |
|11 |groups test1 |cross-check the user name |
|12 |sudo delgroup group_test1 |but here we cant delete as this is the primary group,for this first delete the user then delete the  group |
|13 |sudo deluser test1 |ask for password then delete the user, then use the above cmd for dlt the grp |
|14 |useradd |adduser cmd internally use the ($ useradd) cmd ,if we directly use it ,it will never ask any password create the user |
|15 |userdel |all are same as useradd ,we use adduse cmd bcz its more userfriendly |
|16 |groupadd |all are same as useradd ,we use adduse cmd bcz its more userfriendly |
|17 |groupdel |all are same as useradd ,we use adduse cmd bcz its more userfriendly |
|18 |passwd |inside the user enter this cmd and enter old password and new password to change the password |
|19 |sudo passwd test5 |to change the password of any file enter this cmd from administartor and change password |
