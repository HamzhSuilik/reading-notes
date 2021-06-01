# Encryption, decryption, and cracking

## Encrypting a message using The Caesar Cipher 
The encryption process is done by replacing each original letter with a different letter in the alphabet by shifting the alphabet by a certain amount

Encryption: scrambling the data according to a secret key (in this case, the alphabet shift).

For Example if we have the letter a and shifting key 4 : the encrypt value of ‘a will be e : (1:b,2:c,3:d,4:e)

## Decrypting a message
Decryption: recovering the original data from scrambled data by using the secret key.

The message is decoded in the same way as encryption, but the offset is reversed

## Cracking the cipher :
Code cracking: uncovering the original data without knowing the secret, by using a variety of clever techniques.

There are three main techniques are used for Cracking the cipher:
- frequency analysis
- known plaintext
- brute force

## Caesar cipher
It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet
It is an old encryption method that relies on offsetting the characters in the message by a certain amount. When the message is received, the characters are re-shifted in reverse depending on the amount of offset agreed upon between the sender and receiver.
This method was safe in the past due to people's ignorance of cryptography, but today it is easy to break this encryption because the number of offset possibilities is limited, which is 25

In the event that the hacker knows that the message is encrypted using the Caesar cipher, the decryption will be easy, even if he does not know the encryption key



