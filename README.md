# Resolution of the 'Eli' Cyberdefenders Challenge

### The challenge is available at https://cyberdefenders.org/blueteam-ctf-challenges/98

## 1. The folder to store all your data in - How many files are in Eli's downloads directory?

find . -type d -name 'Downloads'

![image](https://user-images.githubusercontent.com/60743836/185504185-200664d6-288e-45c0-8bab-549cf4dc92e1.png)

Answer: 6

## 2. Smile for the camera - What is the MD5 hash of the user's profile photo?


## 3. Road Trip! - What city was Eli's destination in?

![image](https://user-images.githubusercontent.com/60743836/185508181-2b73144f-9fb7-41f2-a95b-4ca890ed88ce.png)

Answer: Plattsburgh

## 4. Promise Me - How many promises does Wickr make?

find . -name '*Promises*'



![image](https://user-images.githubusercontent.com/60743836/185509074-5b66a448-faea-48fa-9369-795795a8074e.png)

Answer: 9

## 5. Key-ty Cat - What are the last five characters of the key for the Tabby Cat extension?

grep -rnw '.' -e '[tT]abby [cC]at'

![image](https://user-images.githubusercontent.com/60743836/185509539-c73158d7-33d3-44d3-94ee-35a6e87ccfb0.png)
Answer: DAQAB

## 6. Time to jam out - How many songs does Eli have downloaded?

find . -type f -name '*.mp3'

![image](https://user-images.githubusercontent.com/60743836/185510303-d4761e40-7aab-4179-8b84-bdc428da6105.png)

Answer: 2

## 7. Autofill, roll out - Which word was Autofilled the most?

## 8. Dress for success - What is this bird's image's logical size in bytes?

ls -l 2021CTF-Chromebook/2021CTF-Chromebook/decrypted/mount/user/Downloads/tux.png

![image](https://user-images.githubusercontent.com/60743836/185511832-9b6b4f8b-b6b2-4987-a86a-5e3fe184e23a.png)

Answer: 46,791


## 9. It's about the journey, not the destination - How many miles would the trip have been if Eli had taken a long way?

![image](https://user-images.githubusercontent.com/60743836/185512025-937b9fba-0afb-4a3c-b6c0-6e5e558e14ef.png)

Answer: 81.2

## 10. Repeat customer - What was Eli's top visited site?

![image](https://user-images.githubusercontent.com/60743836/185512657-af7858dd-38b9-4963-a9ba-06e2f16109b6.png)

Answer: protonmail.com

## 11. Vroom Vroom, What is the name of the car-related theme?

![image](https://user-images.githubusercontent.com/60743836/185517449-72c2409f-55ff-46ac-9201-4e86266394dc.png)

Answer: Lamborghini Cherry

## 12. You got mail - How many emails were received from notification@service.tiktok.com?

grep -rnw '.' -e 'notification@service.tiktok.com'

![image](https://user-images.githubusercontent.com/60743836/185514446-a86a69d2-9422-48a4-b986-1fc711221584.png)

Answer: 6


## 13. Hungry for directions - Where did the user request directions to on Mar 4, 2021, at 4:15:18 AM EDT

![image](https://user-images.githubusercontent.com/60743836/185514816-4c514645-1943-45e8-b407-f9762f9e4d73.png)

Answer: Chick-fil-A

## 14. Who defines essential? - What was searched on Mar 4, 2021, at 4:09:35 AM EDT

![image](https://user-images.githubusercontent.com/60743836/185515036-746cab92-07a7-4206-944c-ce452ca5daab.png)

Answer: is travelling to get chicken essential travel

## 15. I got three subscribers, and counting - How many YouYube channels is the user subscribed to?

![image](https://user-images.githubusercontent.com/60743836/185515159-41f1a7af-a3ef-4fab-aee9-82749708fd61.png)

Answer: 0

## 16. Time flies when you're watching YT - What date was the first YouTube video the user watched uploaded?

![image](https://user-images.githubusercontent.com/60743836/185515341-9ccb3695-7b3f-403c-8e2d-984f51312b53.png)

Answer: 27/01/2021

## 17. How much? - What is the price of the belt?

![image](https://user-images.githubusercontent.com/60743836/185513633-1af51ef4-078b-4a4a-9ee5-1230a1051a64.png)

Answer: 98.5

