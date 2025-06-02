# ChirpR-OS-Preview---T-Deck-Pro-
A preview of the firmware im working on for the Lilygo T Deck Pro. I have used the test firmware examples from the device as a guide to build upon. 

**Please ignore the screen burn in  - this is my first time working with e-paper displays! I learnt very quickly what NOT to do!! its a dev device anyway ;)***

This is still a major work in progress but its coming together nicely. A full e-paper refresh system has been put in place now (partial refresh for items displayed and a full refresh every 20 mins to stop burn in and ghosting)

Wifi, touch, PCM5102, keyboard, GPS, LoRa, gyroscope and display all initialising correctly on boot.

Next steps are to implement a dynamic notification area on both the lock screen and home screen to show messages/notification icon etc when the LoRa side of things is completed, as well as finish implementing the other apps i want to include:

- Step Counter Settings
- Finish Alarms off
- Calendar 
- Others

Happy for suggestions! i will see what i can do!

Would love to import meshtastics LoRa implementation and rework the UI for e-paper to setup, register and send messages via LoRa.

***Possibly open to opening this project up for help with development here on GitHub depending on the interest - feel free to share your thoughts or express interest***

Below is whats been implemented:

***UPDATE 02/06/2025 515pm - Version 1.2.1**

Implemented setup screen on first boot. Can select an avatar for your card in the contacts menu and set name.

![IMG_20250602_170309780](https://github.com/user-attachments/assets/7f87d69d-62d5-421d-8071-efe1579627bc)

Avatar Selection Modal:

![IMG_20250602_170352325](https://github.com/user-attachments/assets/52cbd5ef-58c1-43a8-b94e-fc4518fe2fdc)

Almost complete UI overhaul - fonts have been updated and refreshed. I have also add 3 "Favourites" apps that can be changed in the settings menu to select 3 fave apps to show on the home screen.

![IMG_20250602_170501826](https://github.com/user-attachments/assets/c10fea53-69c1-45ed-bd05-3477dbdd5e5c)

![IMG_20250602_170705070](https://github.com/user-attachments/assets/efd02740-17c1-4e8a-81b8-7619f7ca374d)

![IMG_20250602_170513627](https://github.com/user-attachments/assets/51405614-b40a-482a-a615-c63e07216c7d)

A new Contacts App

![IMG_20250602_170521357](https://github.com/user-attachments/assets/abf97972-538a-4130-9c15-5d462ebe07f0)

![IMG_20250602_170532518](https://github.com/user-attachments/assets/99a25b95-be20-4c59-9d7b-b149d5fd791f)

![IMG_20250602_170541406](https://github.com/user-attachments/assets/44d43bd6-0a70-46c0-8f92-cbc03f7bda20)

Updated lockscreen fonts, lock symbol and charging bolt symbol

![IMG_20250602_170559424](https://github.com/user-attachments/assets/3c2fa2d4-73b2-4fba-9c2a-4b784f691798)

![IMG_20250602_170612991](https://github.com/user-attachments/assets/5cb7ecff-be11-4bb5-b79c-d37605a2b7ed)

Stay tuned for the next update!!

_____________________________________________________________________________________________________________________


***UPDATE 01/06/2025 5.30pm - Version 1.1.0***

Power off/Ship Mode (displays and then powers the device off - like test firmware)

![IMG_20250530_222041947_HDR](https://github.com/user-attachments/assets/5eed15b5-6016-42f8-8ed2-89670fcc0471)

Boot Image

![IMG_20250530_222128827_HDR](https://github.com/user-attachments/assets/dff0acd8-fdae-42b2-9b9b-3961560b72de)

New home screen landing page - Time , date and built in step counter (currently set at 10,000 per day as goal, resets at midnight) with built in infinite scrolling between all home screen and app pages!

![IMG_20250601_171150305](https://github.com/user-attachments/assets/6e5571ec-d261-4e2b-b8b9-7cab3dc36391)

Updated apps page, with an inclusion of a voice notes app to record and save to the SD card

![IMG_20250601_171159209](https://github.com/user-attachments/assets/eaf63f83-6121-4143-bcd1-ea8ec07594dd)

![IMG_20250601_171211437](https://github.com/user-attachments/assets/d431da88-3abd-430f-9c97-4731fd4f48bf)

Updated Lockscreen with steps counter display and adaptive battery charging status on the bottom text (with charging symbol)

![IMG_20250601_171255262](https://github.com/user-attachments/assets/4a85b7c5-9080-4043-8751-c21fc587854b)

![IMG_20250601_172043308](https://github.com/user-attachments/assets/94d1084c-883f-40c3-a41d-46a92ae7993b)

Lockscreen Password has been updated to show in the middle of the adaptive field (hides the password input field after 10 seconds of inactivity)

![IMG_20250601_171308773](https://github.com/user-attachments/assets/ec8ab760-e847-4177-a0a1-c98242f3b362)

Have removed the Shutdown icon from the apps menu and have implemented hold boot for 3 seconds to trigger draw over power menu to take its place

![IMG_20250601_172842618](https://github.com/user-attachments/assets/d72c90c4-d102-43ba-801a-715c4726a88c)

Stay Tuned for the next update!!

______________________________________________________________________________________________________________________

***First Release - 30/05/2025 Version 1.0***

Homescreen (Page 1)

![IMG_20250530_222150569_HDR](https://github.com/user-attachments/assets/dc6e18e5-1545-4c6b-a725-56dcee0b7e06)

Homescreen (Page 2)

![IMG_20250530_222204259_HDR](https://github.com/user-attachments/assets/681e69b6-3376-47df-8d24-abd12b7b6939)

About Page

![IMG_20250530_222212295_HDR](https://github.com/user-attachments/assets/339aec3c-3e26-4eee-a246-0379388af15b)

Notes App

![IMG_20250530_222227839_HDR](https://github.com/user-attachments/assets/102ddb05-a8b5-4c91-a1a8-56632ceee445)

Create Note

![IMG_20250530_222237092_HDR](https://github.com/user-attachments/assets/4d86a454-3472-4488-b427-5f551c5a69c6)

Calculator App

![IMG_20250530_222248089_HDR](https://github.com/user-attachments/assets/4b6c58aa-40d7-4714-b49f-b51fef281895)

Music App

![IMG_20250530_222257249_HDR](https://github.com/user-attachments/assets/7105ac33-a88c-4aac-8213-300a4c22e9f9)

Music Player

![IMG_20250530_222304206_HDR](https://github.com/user-attachments/assets/287efb2e-d77d-4dd1-800a-fe8f3fdcd72a)

Lockscreen (password field hidden until input detected - then displays for 10 seconds - if no input then hides again after 10 seconds)

![IMG_20250530_222349150_HDR](https://github.com/user-attachments/assets/ca2d36fc-01a5-43f6-bd69-580ff4e05851)

![IMG_20250530_222355714_HDR](https://github.com/user-attachments/assets/290862fc-b1a7-40c5-aff0-5e06412e72fa)

Set Lockscreen Password (under settings)

![IMG_20250530_222428492_HDR](https://github.com/user-attachments/assets/246d2a07-f175-4d6e-8be1-e326ab426468)

