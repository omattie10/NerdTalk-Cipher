# NerdTalk-Cipher
A simple but secure and *as far as i'm aware* unique cipher that scrambles based on its extended ASCII assignment, I might make a unicode varient one day but theres some issues regarding it just looking like a jumbled mess
on the topic of it looking like a jumbled mess, due to the way that extended ascii works some characters are unreadable on some programs or appear the same, this means its difficult to write it normally while staying on extended ascii so I have included a normal ASCII version for writing letters by hand, do not use this one unless you actually have to as extended ascii is more secure due to it being harder to read

**This is by no means secure, although it is fairly secure**, don't use it for sending military secrets or encrypting drives, use AES instead. It can be modified to be more secure by changing the salt function a bit and making the key encrypt / decrypt differently based on the length of the keyword or something which is might do for nerdtalk-002 when I release that.

![image](https://github.com/user-attachments/assets/1aa02317-97a7-4aeb-9ade-88d362ca6cb1)
![image](https://github.com/user-attachments/assets/14c270de-27c8-4310-bb01-df06fb6e90fe)

btw its space and caps sensitive due them having unique extended ascii values so when you copy and paste the encoded message to decode it, make sure to remove a space at the front.
