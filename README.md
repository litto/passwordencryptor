# Password Encryptor

Password Encryptor Small library for PHP Website

## How to Install?

You can install by using command

composer require litto/passwordcrypto

## How to Use?

        $txtPassword="test@123";
        $key    =   rand(0,9999).rand(111,999);
        $crypt  = new Crypt; 
        $crypt->crypt_key($key);// Get encryption key
        $password = $crypt->encrypt($txtPassword);  // encrypt username

