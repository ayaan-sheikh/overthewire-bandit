# Overthewire-bandit
![image](https://user-images.githubusercontent.com/94873357/149216623-26ed1eb1-5103-4ec6-8c1d-b24d20e7cb48.png)
Bandit - overthewire is a great CTF game in order to learn the basics. This writeup will contain ways in which I have tackled all levels.
The link for the ctf can be found here - https://overthewire.org/wargames/bandit/


**Level 0:**

![image](https://user-images.githubusercontent.com/94873357/149216707-f567fde2-b331-4f3d-a2ec-95e9e6340c3e.png)

connect to bandit.labs.overthewire.org, on port 2220 using given credentials ie; username - bandit0 and password - bandit0

![image](https://user-images.githubusercontent.com/94873357/149354659-7e5088cd-fa5c-4d33-a110-f00b4374b145.png)

**ssh bandit0@bandit.labs.overthewire.org -p 2220**
\n Now that we are connected, look for next clue given in the website. As highlighted the password for next level is store under a file called readme. lets list the files using ls -alps command (use the man page to understand more about the options)

**ls -alps**

![image](https://user-images.githubusercontent.com/94873357/149356411-4ffad94c-7371-4d67-8f52-44078aaa3050.png)

**cat readme**

![image](https://user-images.githubusercontent.com/94873357/149356538-37b1395f-3d8d-42ec-a34e-8cd737e3e737.png)

We got the password for next level.



**Level 1:**

![image](https://user-images.githubusercontent.com/94873357/149216742-bd994f58-4b3b-47f0-8fb0-c15ac6df78b2.png)



![image](https://user-images.githubusercontent.com/94873357/149216767-27fee159-605e-4bb1-a1f5-7e1dccb8035b.png)


![image](https://user-images.githubusercontent.com/94873357/149216801-7d12a572-c5da-46ac-8797-a253b1923aad.png)


![image](https://user-images.githubusercontent.com/94873357/149216832-19a6db9d-e330-4311-94e7-9b831361b361.png)


![image](https://user-images.githubusercontent.com/94873357/149216853-8cadb905-18d1-41c5-b240-609a1ff783b0.png)


![image](https://user-images.githubusercontent.com/94873357/149216879-a91060c2-c950-4162-bc21-bae1526d6898.png)


![image](https://user-images.githubusercontent.com/94873357/149216898-21a98385-42cd-47ff-a086-8ca1cd2f7ed6.png)


![image](https://user-images.githubusercontent.com/94873357/149216926-9849c581-c497-438e-a64a-3655b9c9cbe5.png)


![image](https://user-images.githubusercontent.com/94873357/149216947-86471da2-421f-475e-b8c0-b305057d69bd.png)


![image](https://user-images.githubusercontent.com/94873357/149216969-fd606367-7890-43c3-bbf5-9ae6e3d97da2.png)


![image](https://user-images.githubusercontent.com/94873357/149216992-e6a76004-93a2-419d-8043-29b662f1f192.png)


![image](https://user-images.githubusercontent.com/94873357/149217014-8ad7d53e-1152-4bde-93ae-0d542ed73322.png)


![image](https://user-images.githubusercontent.com/94873357/149217029-b091de88-d415-4f24-aa3b-24de01aec9be.png)


![image](https://user-images.githubusercontent.com/94873357/149217055-bb8eab8f-80a6-463b-b4ed-0e31bf339d9d.png)


![image](https://user-images.githubusercontent.com/94873357/149217071-e81c1d68-e3d0-4d08-a348-79b3f9601453.png)


![image](https://user-images.githubusercontent.com/94873357/149217093-8773f656-9b52-40df-b06f-8419974b195f.png)


![image](https://user-images.githubusercontent.com/94873357/149217114-a040f121-b54a-4b65-99e5-d6f91a8c7126.png)


![image](https://user-images.githubusercontent.com/94873357/149217137-0ab56e8c-e2ba-4f75-b074-14b48d47dd28.png)


![image](https://user-images.githubusercontent.com/94873357/149217163-fb6be456-2867-474e-8f61-b45e07b2acef.png)


![image](https://user-images.githubusercontent.com/94873357/149217182-66a6610a-a39e-4569-acdf-9dba580266fe.png)


![image](https://user-images.githubusercontent.com/94873357/149217217-34ac15a5-1f47-49ba-acc7-69496b6319d8.png)


![image](https://user-images.githubusercontent.com/94873357/149217248-fb3c9312-5285-480e-9aca-c0805be95ddf.png)


![image](https://user-images.githubusercontent.com/94873357/149217269-ff45c90b-04d8-4529-9331-8c12e4f115ab.png)


![image](https://user-images.githubusercontent.com/94873357/149217286-c72b6dbe-9326-4957-bceb-d71403ed18ab.png)


![image](https://user-images.githubusercontent.com/94873357/149217306-38d41f61-050d-490a-abc9-b2dd36d29d4f.png)


![image](https://user-images.githubusercontent.com/94873357/149217323-cfc422e0-7832-4dc3-83c8-8e403e4229c2.png)


![image](https://user-images.githubusercontent.com/94873357/149217341-67a94a41-4b0b-4ad7-861b-cc0f44ed0aeb.png)


![image](https://user-images.githubusercontent.com/94873357/149217367-da017acf-cd5e-45da-adff-6d80eb699814.png)


![image](https://user-images.githubusercontent.com/94873357/149217390-294333c0-abfd-44a7-ab59-38d2dc7c5812.png)


![image](https://user-images.githubusercontent.com/94873357/149217411-2e675ea4-d7c1-4852-aa1d-04befab5eb91.png)


![image](https://user-images.githubusercontent.com/94873357/149217438-026dac10-7caf-4d76-b079-8a9407b5a73a.png)


![image](https://user-images.githubusercontent.com/94873357/149217460-f0793c9d-8c2f-4f92-8478-0f2a7d6befa7.png)


![image](https://user-images.githubusercontent.com/94873357/149217480-043b3fbf-3de0-48e6-b96b-420b28747c6b.png)


