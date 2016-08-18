# phpseclib - PHP Secure Communications Library

[![Build Status](https://travis-ci.org/phpseclib/phpseclib.svg?branch=master)](https://travis-ci.org/phpseclib/phpseclib)

MIT-licensed pure-PHP implementations of an arbitrary-precision integer
arithmetic library, fully PKCS#1 (v2.1) compliant RSA, DES, 3DES, RC4, Rijndael,
AES, Blowfish, Twofish, SSH-1, SSH-2, SFTP, and X.509

* [Download (1.0.3)](http://sourceforge.net/projects/phpseclib/files/phpseclib1.0.3.zip/download)
* [Browse Git](https://github.com/phpseclib/phpseclib)
* [Code Coverage Report](http://phpseclib.bantux.org/code_coverage/master/latest/)

<img src="http://phpseclib.sourceforge.net/pear-icon.png" alt="PEAR Channel" width="16" height="16">
PEAR Channel: [phpseclib.sourceforge.net](http://phpseclib.sourceforge.net/pear.htm)

## Documentation

* [Documentation / Manual](http://phpseclib.sourceforge.net/)
* [API Documentation](http://phpseclib.bantux.org/api/master/) (generated by Sami)

## Support

Need Support?

* [Checkout Questions and Answers on Stack Overflow](http://stackoverflow.com/questions/tagged/phpseclib)
* [Create a Support Ticket on GitHub](https://github.com/phpseclib/phpseclib/issues/new)
* [Browse the Support Forum](http://www.frostjedi.com/phpbb/viewforum.php?f=46) (no longer in use)

## Installing Development Dependencies

Dependencies are managed via Composer.

1. Download the [`composer.phar`](https://getcomposer.org/composer.phar) executable as per the
   [Composer Download Instructions](https://getcomposer.org/download/), e.g. by running

    ``` sh
    curl -sS https://getcomposer.org/installer | php
    ```

2. Install Dependencies

    ``` sh
    php composer.phar install
    ```

## Contributing

1. Fork the Project

2. Install Development Dependencies

3. Create a Feature Branch

4. (Recommended) Run the Test Suite

    ``` sh
    vendor/bin/phpunit
    ```
5. (Recommended) Check whether your code conforms to our Coding Standards by running

    ``` sh
    vendor/bin/phing -f build/build.xml sniff
    ```

6. Send us a Pull Request
