# Program Encrypter  
## Summary   
This is file encrypting program for specified time.  

![alt text](https://github.com/JaeguKim/ProgramEncrypter/blob/master/ProgramEncrypter/summary.png)   
  
## Background  
Some parents may want their children to restrict some specific software for specific time. I decided to develop file encryption program which encrypts any file with key for specific time. The encrypted programs can be decrypted with key you entered before the timer is expired. I was inspired by Randomware which was popular at 2019.
  
## Main Function   
1. id, password, file decryption key are encrypted with RSA algorithm(public key and private is hardcoded for now)  

![alt text](https://github.com/JaeguKim/ProgramEncrypter/blob/master/ProgramEncrypter/rsa.png)  
  
2. This program uses token-based authentication.  

![alt text](https://github.com/JaeguKim/ProgramEncrypter/blob/master/ProgramEncrypter/jwt_auth.png)  
  
3. when storing password to database, hash algorithm is used.  
  
![alt text](https://github.com/JaeguKim/ProgramEncrypter/blob/master/ProgramEncrypter/hash.png)
  
4. when encryting file, AES algorithm is used.  
  
![alt text](https://github.com/JaeguKim/ProgramEncrypter/blob/master/ProgramEncrypter/aes_encrypt.png)

## Demonstration Video
[link](https://www.youtube.com/watch?v=DKc-Dy6k1Hc)
