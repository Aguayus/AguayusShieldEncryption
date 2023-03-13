# Aguayus Shield Encryption
- A process to obfuscate the result of an encryption, to protect from brute force.
- Aguayus Shield Encryption modify the output of encryption process like AES or RSA, that means that the Key CAN NOT BE RECOVERED BY BRUTE FORCE
- Aguayus Shield Encryption has random output length that means that cannot be predictable
- Aguayus Shield Encryption is not based on maths because the maths is the way to calculate the key

## Context 
 I am a simple student that I am investigating about how I can protect the actual encryptation systems likes AES or RSA to avoid that the Key used for encryption will be obtained by Brute Force.
 
 ## How thats work ?
 ![Aguayus Process](Aguayus%20Diagram.png)
 
 Ok at now how I can recover to obtain the original encrypted data to decrypted normaly with the correct key? Sorry but thats is a secret ;)
 
 I know that the output looks like Base64 but if you decoded, you discovered that looks like base64 but is not a real base64.
 
 Here is the Api
 [Documentation](https://app.swaggerhub.com/apis/ADMIN_150/AguayusShieldEncryption/1.0.0) in case offline or not working you can download [AguayusApi.yaml](https://raw.githubusercontent.com/Aguayus/AguayusShieldEncryption/main/AguayusApi.yaml)
 
 Here is the [Postman Collection](https://raw.githubusercontent.com/Aguayus/AguayusShieldEncryption/main/Aguayus.postman_collection.json)
 
 
 Please try the challenge that I offer in the Api. 
 
 For suggestions an Ideas please create an Issue.
 
 Thanks
