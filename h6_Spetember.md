

## x) Read and summarize 

## 2.3 ONE-WAY FUNCTIONS
- one-way functions are fundamentals building blocks for the most protocols.
- one-way functions are relatively easy to compute, but significantly harder to reverse.
- a trap-door one-way function is special type of one-way function, one with a secret trapdoor,  it is easy to compute in one direction if you kno the secret , but to compute if you don't.

## 2.4 ONE-WAY HASH FUNCTIONS
- A one-way hash function has many names: compression function, contraction function, message digest, fingerprint, cryptographic checksum, message integrity check (MIC), and manipulation detection code (MDC).
- a hash function is a function that takes avariable-length input string and convert it to fixed-length output string.
- hash functions are typically many-to-one, we cannot use them to determine with certainty that the two strings are equal, but we can use them to get a reasonable assurance of accuracy.
- Given a hash value, it is computationally unfeasible to find a pre-image that hashes to that value
- a message authentication code (MAC) is a one-way hash functions with the addition of code, herer the key verfies the hash value.

##  a) Install Hashcat

![Screeshot](hashcat_install.png)

![Screeshot](hashcat_2.png)

![Screeshot](hashcat_3.png)

![Screeshot](hashcat_4.png)


##  b) Cracking the hash



![Screeshot](cracked_1.png)

![Screeshot](cracked_2.png)

![Screeshot](cracked_3.png)

1. At first , i used the hadid to the mode of the hash
2. After that i used the hashcat with mode 0 and get password in a file called "solved1'
3. An finally i used the cat command to get the value , which was "disobey"

   








