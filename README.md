# Aguayus Shield Encryption
- A process to obfuscate the result of an encryption, to protect from brute force.
- Aguayus Shield Encryption modify the output of encryption process like AES or RSA, which means that the Key CAN NOT BE RECOVERED BY BRUTE FORCE
- Aguayus Shield Encryption has random output length, means that cannot be predictable
- Aguayus Shield Encryption is not based on mathematics since mathematics is used to calculate the key*

## Context 
 I am a student researching how to enhance the security of encryption systems such as AES or RSA, to prevent the key used for encryption from being obtained through brute force.
 
 ## How thats work ?
 ![Aguayus Process](Aguayus%20Diagram.png)
 
Okay, but how can I recover the original encrypted data and decrypt it normally with the correct key? Sorry, but that is a secret ;)
 
I know that the output looks like Base64, but if you decode it, you'll find out that it's not a real Base64 format
 
 Here is the Api
 [Documentation](https://app.swaggerhub.com/apis/ADMIN_150/AguayusShieldEncryption/1.0.0) in case offline or not working you can download [AguayusApi.yaml](https://raw.githubusercontent.com/Aguayus/AguayusShieldEncryption/main/AguayusApi.yaml)
 
 Here is the [Postman Collection](https://raw.githubusercontent.com/Aguayus/AguayusShieldEncryption/main/Aguayus.postman_collection.json)
 
 
 Please try the challenge that I offer in the Api. 
 
 For suggestions an Ideas please create an Issue.
 
 Thanks
