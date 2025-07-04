ChirpR OS - T Deck Pro

Current Version: 1.6.5


<div align="center">
<img src="https://github.com/user-attachments/assets/9367ba6f-826e-461f-8b4f-c66a7aee98ee" width="300" alt="ChirpR OS Logo">
</div>

A preview of the firmware im working on for the Lilygo T Deck Pro. I have used the test firmware examples from the device as a guide to build upon. ***Please note i do all of this in my spare time, so updates etc wont all ways be scheduled, although if people would like to help make this the best firmware for the T Deck Pro, i would love people to join and contribute!***

***DISCLAIMER - This firmware has been developed for the Audio variant of the T Deck Pro (Not the 4G version). As the firmware has been built off the test firmware, it handles the component detection in the exact same way - You are free to test this firmware on your device if you have the 4G version, however you do so at your own risk and do so knowing the music player will not generate which may cause system failure. I will not accept any responsibility for device failure or bricking (however this is extremley difficult to acheive). I dont own a 4G version to test this as of yet, however if there is enough interest and i can get some feed back from 4G version users if they test it, i can see what i can do to patch the 4G version to enable it to boot etc if required. I will order a 4G version when i can afford it. No work is being planned on 4G development for this device, now, or in the future.***

***What is ChirpR OS?***

ChirpR OS is a firmware designed for the Lilygo T-Deck Pro hardware platform that transforms your device into a powerful communication hub with e-paper display technology. Built specifically for long-range messaging, remote communication, and outdoor adventures where traditional devices may fail. The design philosophy was centered around ease of use and functionality.

Core Features & Applications

📱 17 Built-in Applications - ChirpR OS comes packed with a comprehensive suite of applications:

📡 Messages - LoRa Messaging (coming soon!)	

🧮 Calculator - Full-featured calculator	

🎵 Music - Audio player with headphone support

⚙️ Settings - System configuration and settings

📍 GPS - Real-time location logging	

📝 Notes - Text note taking	

🎤 Voice - Audio recording/playback	voice notes

⌚ Watch - ChirpR OS Watch connectivity coming soon! (T Watch S3 Plus)

📶 WiFi - Network connectivity	

📁 Files - SD card file management	

📅 Calendar - Basic Calendar

💪 Health - Fitness tracking (steps) utilising the onboard AI chip to generate health insights.

🔵 Bluetooth - Device pairing	(over BLE)

👥 Contacts - Contact management	

🔔 Alarms - Basic Alarm System

🚶 Steps - Step counter with goals

🌐 MeshCore - Mesh networking (coming soon!)		



ChirpR OS transforms your T-Deck Pro into the ultimate communication device for:

🏕️ Off-grid adventures

🚨 Emergency preparedness

🏭 Industrial applications

🛡️ Privacy-focused communication

🔬 IoT and maker projects


Ready to revolutionise how you communicate? Stay tuned for further progress!

ChirpR OS - Where e-paper meets long-range communication. When the grid goes down, we stay connected. 🌐⚡📡


***Progress Reports***

**Please ignore the screen burn in  - this is my first time working with e-paper displays! I learnt very quickly what NOT to do!! its a dev device anyway ;)***

I am currently preparing MeshCore's LoRa implementation which will require a rework the UI for e-paper to setup, register and send messages via LoRa. This will not be included in the first beta test builds.

A big shout out to Andy at MeshCore for graciously allowing me to implement MeshCore's Mesh Network instead of building one from the ground up! This will significantly reduce development time!

***BETA TESTING IS OPENING WITHIN THE NEXT 2 WEEKS - STAY TUNED FOR MORE UPDATES***

Below is whats been implemented so far:

***UPDATE Friday July 4 @ 12.00 PM - Version 1.6.5***

A small adjustment has been made to the move apps function, which now includes 3 new icon packs! Users now have the choice of the standard icons, simple, modern or funky icon packs, then can continue to rearrange the apps to their prefrences! Icon themes persist across reboot. Again this one kept me up for the last few days but its in and working!

![IMG_20250704_112632506_HDR](https://github.com/user-attachments/assets/9222cc17-1558-41b9-98f0-3c02b32ad6c8)

![IMG_20250704_112639805_HDR](https://github.com/user-attachments/assets/26d6dc84-f955-4587-bae1-05e0c2aabe6d)

![IMG_20250704_112931638_HDR](https://github.com/user-attachments/assets/56b30af5-b831-4120-abd8-ae8b74cd7151)

![IMG_20250704_113036155_HDR jpg](https://github.com/user-attachments/assets/dffa1133-5553-4926-8ba7-20ff812c0397)

![IMG_20250704_113036155_HDR jpg](https://github.com/user-attachments/assets/d3cbbc9d-d7b4-47ba-98f4-59d251c0205b)

Now the final customisation feature is in, i need to finlaise eveything else in the firmware and polish a few features and its ready for testing!!!

**Update 30 June 2025 @ 10:13pm - Version 1.6.4***

Have finally implemented the move apps function. Hold down on an app and the Move App's modal appears. Hit start and complete the grids on both pages and hit save and it will recreate the apps screen to your prefrence and persist through reboots. Lists are dynamic and remove already selected options. This has kept me awake for a few days but its finally in!

![IMG_20250630_220233282_PORTRAIT](https://github.com/user-attachments/assets/65472f2c-6108-43c6-9be3-8826c6d2b92e)

![IMG_20250630_220333797_PORTRAIT](https://github.com/user-attachments/assets/a792f964-e08d-41fa-8c80-c15652c91adf)

![IMG_20250630_220402324_PORTRAIT](https://github.com/user-attachments/assets/cb4bc99c-60ca-4c2f-bc5b-0d92576982e4)

![IMG_20250630_220513377_PORTRAIT](https://github.com/user-attachments/assets/21db15aa-6ec8-4d93-bfd3-a817cf600816)

![IMG_20250630_220533929_PORTRAIT](https://github.com/user-attachments/assets/d924f857-3c51-4759-9d7b-d43bcbcfd742)

Update to battery critically low shutdown. Shuts system down at 3% and displays the below and turns the device off.

![IMG_20250630_080411156_HDR_PORTRAIT](https://github.com/user-attachments/assets/6b870e6d-c53a-4c51-9252-d050f5ccaac8)

First beta release due by Sunday 6 July at the latest!

***Update 29 June 2025 @ 9:54pm - Version 1.6.3***

BLE functionality has now been built in for the T Watch intergration.

![IMG_20250629_213631142_HDR_PORTRAIT](https://github.com/user-attachments/assets/ff2172ce-e164-42c0-a6ce-04dc6cb3bbf6)

Updated the About icon and have changed the information available. Now contains unique device name (based on hashed and truncated mac addresses)

![IMG_20250629_213616292_HDR_PORTRAIT](https://github.com/user-attachments/assets/37606d8e-06da-4499-bd99-5c8070f25959)


![IMG_20250629_213559857_HDR_PORTRAIT](https://github.com/user-attachments/assets/96e9e556-705f-47ae-ba06-e79906d220bc)

Have implemented a boot intervention for plugging the device in. To stop the system from just booting, it now brings up a menu to charge the device only or start the system. If charge is seletced it will take you to the charge screen which shows the time and charge status and a start system button. A power icon is in the corner to switch device off.

![IMG_20250629_213757001_HDR_PORTRAIT](https://github.com/user-attachments/assets/46fb1ec5-be9d-452b-81e9-3e9af108a22d)

![IMG_20250629_214922868_HDR_PORTRAIT](https://github.com/user-attachments/assets/2251a7b7-3640-4b6d-b873-66ed960bba8d)

Health has now got a small bar graph showing steps for the week so far as progress.

![IMG_20250629_213703272_HDR_PORTRAIT](https://github.com/user-attachments/assets/0610046a-75a0-4be0-b6f1-f0a780c81667)

Also a critical battery feature has been put in place to stop battery degredation if the device is left and runs out of battery. it now shuts down and puts a similar message on the screen to the power off mode, that advises the user the device battery is critically low and they need to charge their battery.A few other smaller fixes under the hood.

A few days left until the first beta version is released! Stay tuned!!

***UPDATE 25 June 2025 @ 6:08pm - Version 1.5.0***

Have implemented the last of the icons - Health, Calendar and MeshCore

![IMG_20250625_180645216_HDR](https://github.com/user-attachments/assets/017ed4a4-51d7-4d9f-aed9-78c32851ed18)

Health uses the steps counter and onboard AI chip to generate health insights and tracking. This will be further linked with the T Watch S3 Plus once firmware development begins in a few weeks (waiting for the device to arrive so i can start)

![IMG_20250625_180709990_HDR](https://github.com/user-attachments/assets/a54e957b-553a-4852-a875-5b9a481487aa)

Have put a toggle in Lock Screen Settings to turn off/on "turn display off after 3 mins with no action on lockscreen" for further power savings.

![IMG_20250625_180742093_HDR](https://github.com/user-attachments/assets/3e547cb8-a93e-4246-b9c5-6fc6c7008215)

Other smaller fixes under the hood have been completed (date removed from top bar to reduce crowding - still available on home screen, lock screen and quick settings panel) Final work on a few of the apps needs to be completed and tested, and then its ready for beta testing!

Beta firmware will be ready in the next week or 2 so stay tuned!

***UPDATE 24/06/2025 @ 10.50PM - Version 1.4.1***

Have finalised first boot setup to include all fields for time and date settings.

![IMG_20250624_210824202_HDR](https://github.com/user-attachments/assets/dbb741e8-6eef-4339-9943-5c1fd06ca3a3)

![IMG_20250624_210922517_HDR](https://github.com/user-attachments/assets/d5bd1f57-bc83-4cb8-b4cf-081809a3d31c)

![IMG_20250624_210938876_HDR](https://github.com/user-attachments/assets/c73cf1d1-4501-4e4c-8977-1a38e1b783bc)

Removed the top bar line from apps menus

![IMG_20250624_211217716_HDR](https://github.com/user-attachments/assets/315d8499-ad04-4a03-bcbe-9bf470bb5e2a)

Added new icons for upcoming features

![IMG_20250624_211448548_HDR](https://github.com/user-attachments/assets/ea3e8d97-fb43-4541-b1c1-7096ec2ea64d)

New lock screen pin unlock option. create pin in settings and swipe up on lock screen to show pin modal

![IMG_20250624_224708132_HDR](https://github.com/user-attachments/assets/1cff0f05-969f-4785-afdc-31be0caa6ba6)

Have implemented further power saving on the lockscreen. When unused for 3 mins while on the lockscreen it clears the display and turns the display off, and wakes up with touch/keyboard press

![IMG_20250624_225143810_HDR](https://github.com/user-attachments/assets/854459f4-3462-419b-9dfe-5800d0c6a1af)

Excited to share this with you soon!


***UPDATE 17/06/2025***

Apologies, end of financial year has drawn me aeay from the project temporarily, but development will resume next week after EOFY has closed. stay tuned!

***UPDATE 06/06/2025 7.05am Version 1.30***

Complete time unification system implemented and step counter settings now has a new app. Time Zone settings will be added to first boot setup

![IMG_20250606_070546385_HDR](https://github.com/user-attachments/assets/27e9a397-7fb2-4fc6-a92d-5185b679e4ef)

![IMG_20250606_070253829_HDR](https://github.com/user-attachments/assets/9a47bc69-f0a0-475f-b4aa-25981b371c79)

New Quick Settings Panel by swiping down on the home screen (to be implemented across all screens)

![IMG_20250606_070046907_HDR](https://github.com/user-attachments/assets/a342ee38-3333-4837-8dd4-a361a25bbf86)

New music controls added to the lockscreen with dynamic icon. Touh icon to open music modal on the lockscreen

![IMG_20250606_070203085_HDR](https://github.com/user-attachments/assets/b884ff01-a1b2-4d8e-b1f4-381e77062f2f)

![IMG_20250606_070212392_HDR](https://github.com/user-attachments/assets/627112f9-c642-4d77-8c81-a1acc3b65860)

Stay tuned for the next update!

____________________________________________________________________________________________________________________


***UPDATE 02/06/2025 515pm - Version 1.2.1**

Implemented setup screen on first boot. Can select an avatar for your card in the contacts menu and set name.

![IMG_20250602_170309780](https://github.com/user-attachments/assets/7f87d69d-62d5-421d-8071-efe1579627bc)

Avatar Selection Modal:

![IMG_20250602_170352325](https://github.com/user-attachments/assets/52cbd5ef-58c1-43a8-b94e-fc4518fe2fdc)

Almost complete UI overhaul - fonts have been updated and refreshed. I have also add 3 "Favourites" apps that can be changed in the settings menu to select 3 fave apps to show on the home screen and have updated the page indicator style to a rounded square.

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

