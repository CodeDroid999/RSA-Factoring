### RSA-Factoring-Challenge
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
