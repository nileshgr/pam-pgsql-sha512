# PAM PgSQL with SHA512 password hashing

Originally the PAM PgSQL module doesn't support SHA512 passwords. 
This is just a fork of the code which adds the support using UNIX 
crypt() function.

