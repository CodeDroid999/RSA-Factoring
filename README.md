### RSA-Factoring-Challenge
# Description
This project is designed to factorize as many numbers as possible into a product of two smaller numbers. It works perfectly for that except the case of bignums (numbers bigger than long long unsigned integers) please any contribution towards making this project work for bignums will be highly appreciated.

Information
HTTPS uses Secure Socket Layer to encrypt data that is transferred between client and server. SSL uses the RSA algorithm, an asymmetric encryption technology. The precise details of how the algorithm works is complex, but basically it leverages the fact that whilst multiplying two large prime numbers together is easy, factoring the result back into the constituent primes is very, very hard. How all SSL/RSA encryption works is:

The server generates two large prime numbers, and multiplies them together. This is called the "public key". This key is made available to any client which wishes to transmit data securely to the server. The client uses this "public key" to encrypt data it wishes to send. Now because this is an asymmetric algorithm, the public key cannot be used to decrypt the transmitted data, only encrypt it. In order to decrypt, you need the original prime numbers, and only the server has these (the "private key"). On receiving the encrypted data, the server uses its private key to decrypt the transmission.

In the case of you browsing the web, your browser gives the server its public key. The server uses this key to encrypt data to be sent to your browser, which then uses its private key to decrypt.

So yes all data transmitted to/from server over HTTPs is encrypted and encrypted well. Typical SSL implementations use 128 or 256 digits for their keys. To break this you need a truly vast amount of computing resources.
# RSA-Factoring-Challenge
We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

### Topics
RSA
How does HTTPS provide security?
Prime Factorization
Why RSA?
## Requirements
You can choose the language of your choice.
OS needs to be Standard Ubuntu 20.04 LTS/

RSA Factoring Challenge
\
0.Factorize all the things!
#### 0\. Factorize all the things!#advanced

Factorize as many numbers as possible into a product of two smaller numbers.

-   Usage:`factors <file>`
    -   where`<file>`is a file containing natural numbers to factor.
    -   One number per line
    -   You can assume that all lines will be valid natural numbers greater than 1
    -   You can assume that there will be no empy line, and no space before and after the valid number
    -   The file will always end with a new line
-   Output format:`n=p*q`
    -   one factorization per line
    -   `p`and`q`don't have to be prime numbers
    -   See example
-   You can work on the numbers of the file in the order of your choice
-   Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
-   Time limit: Your program will be killed after 5 seconds if it hasn't finish
-   Push all your scripts, source code, etc... to your repository
    -   we will only run your executable`factors`

#### 1\. RSA Factoring Challenge#advanced

RSA Laboratories states that: for each RSA number`n`, there exist prime numbers`p`and`q`such that

`n`=`p`×`q`. The problem is to find these two primes, given only`n`.

This task is the same as task 0, except:

-   `p`and`q`are always prime numbers
-   There is only one number in the files

How far can you go in less than 5 seconds?

-   Read:[RSA Factoring Challenge](https://intranet.hbtn.io/rltoken/8F5ClnjOFgDcNZXxeyrHxg "RSA Factoring Challenge")
