php-bc-faucet
====================

php plugin for BlackCoin faucet 

Just place blackcoin.conf in blackcoin data folder (change password, user etc.). 
Edit settings in index.php as required. Make sure you are running php + MySQL. 

MySQL needs simple table with structure:

receiving_ip (varchar), receiving_addr (varchar), amount(double), time(long)
