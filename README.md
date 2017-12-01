# Kicrypt
A secured Password hashing algorithm for PHP.

##Usage:

* First include the lib in your file
* $hash = $kicrypt->hash('password'); //The password to be hashed
* $isGood = $kicrypt->verify('password', $hash); //Comparing the password
