# mysqlOptim
Speed up your mysql export/import

# Installation

git clone https://github.com/alexJouni/mysqlOptim.git


#Copy mysqlOptin to /usr/local/bin

sudo cp mysqlOptim  /usr/local/bin/

#Using mysqlOptin

$mysqlOptim  file.sql



#Export/import database :

mysqldump --opt  -q -u=username -p database > dumbfile.sql;
mysqlOptim  dumbfile.sql;
mysql --user=username --password database < dumpfile.sql


