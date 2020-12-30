*Introduction*
======================
I needed to do private RSA Encryption with private key to achieve non-repudiation without digitally signing a payload.
I found https://travistidwell.com/jsencrypt/ based on Tom Wu's @ http://www-cs-students.stanford.edu/~tjw/jsbn/.
It seemed that these libraries where not maintained anymore at the end of 2020.

I forked JSEncrypt to maintain it and keep it clean.

I added working Private Key Encryption and fixed paddings for interoperability with Pkcs1Encoding by BouncyCastle (tested with C# version).

Feel free to open issues and pull requests.

*TODO*
=======================

- Clean and refactor some code.
- Security audit.
- Write a wiki.

*How to use this library*
=======================

Look to https://github.com/michaeldisaro/jsencrypt/blob/master/demo/index.html to see how encryption works.
This page is also able to generate keys for you on client side.
Private Key is PKCS#1 encoded, Public Key is PKCS#8 encoded.

*Other Information*
========================

Look to https://github.com/travist/jsencrypt/blob/master/README.md for the original documentation.

