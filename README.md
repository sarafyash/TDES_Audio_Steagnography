# Audio_Steagnography
Two way audio encryption by 
  1. Triple DES Algorithm.
  2. Fernet Algorithm

## 1. For Triple DES Algorithm :
### Sender
First take the user input that has to be encrypted. After taking the input, load the audio file in which text will be encrypted.
After that encrypt the text file in audio file by using mapping and frame adjustement.
Then use Triple DES Algorithm to encrypt the audio file in which text is encrypted.
By this we have encrypted the text in audio and , even the audio file is encryptes.
This ensures the security of the text and maintains the confidentiality.
The Sender can now send the file.

### Receiver
The receiver receives the encrypted audio. The receiver first decrypts the audio and then apply the reverse stegnography to get the main text.
This is all done by having a shared pair of keys.
