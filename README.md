# Goldman-Sachs-Internship


## TASK01
You must determine the following:

What type of hashing algorithm was used to protect passwords?

What level of protection does the mechanism offer for passwords?

What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?

What can you tell about the organization’s password policy (e.g. password length, keyspace, etc.)?

What would you change in the password policy to make breaking the passwords harder? 


## Resources:
[Password cracking explained (techniques described in 2013 still haven’t changed)](https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/)

[Password salting](https://en.wikipedia.org/wiki/Salt_(cryptography))

[Hash functions ](https://en.wikipedia.org/wiki/Cryptographic_hash_function)

[Password cracking tools ](https://en.wikipedia.org/wiki/Password_cracking#Software)

[Password strength checker ](https://howsecureismypassword.net/)

## Commands

```bash
sudo hashcat -m 0 hash.txt -o crack.txt rockyou.txt 
```

## Usage

```bash
sudo hashcat -m 0 hash.txt -o crack.txt rockyou.txt --show
```
```bash
sudo cat crack.txt
```

