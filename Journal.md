
| Title | Twin Key |
| :-- | :---|
|Author |Sadrita Neogi|
|Type | Split Keyboard |


## July 2nd : Research about the micro controller for the keyboard

Today I went in Google and search about the different kind of micro controller that I can use in the split keyboard that is cheap and easily available. Also, that can be easily programmable, and everyone can recreate this.

<img width="1444" height="799" alt="1" src="https://github.com/user-attachments/assets/864a63e2-6df0-433e-af0d-0e2bd86af3df" />


<img width="1208" height="658" alt="2" src="https://github.com/user-attachments/assets/d57b5153-fcb6-4e90-80a3-602e657eca6a" />


<img width="1096" height="720" alt="3" src="https://github.com/user-attachments/assets/9e56914f-4b94-4a0f-9753-a09ae8c8d764" />


<img width="1443" height="806" alt="4" src="https://github.com/user-attachments/assets/feed8c69-63ae-490a-a234-e09090836874" />


<img width="1434" height="731" alt="5" src="https://github.com/user-attachments/assets/a09c376a-ec3e-4588-9f68-2c84fd3f316c" />

So after reading through all of the data sheet and the pin out for each of the micro controller since it would be an split keyboard, so I doesn't need maximum number of pin out point like **raspberry pi pico** so for that reason to make it  cost-effective, I am going with **RP2040-Zero** micro controller and **RP2040-Tiny**
And the type of keyboard that I am building for that, I think it should be enough to give the power distribution, and also it can be easily done with the key mapping features

#### Now the keyboard layout 

<img width="956" height="454" alt="image" src="https://github.com/user-attachments/assets/e11b36cf-84cb-42a0-82b1-86de41e1667a" />

<img width="2572" height="970" alt="image" src="https://github.com/user-attachments/assets/f6cacd84-885d-41b8-aae7-2ecb24d28d06" />

I have also went online to see the types of the split keyboard layout that are widely used , but I want to be make one custom for me , I will try to design my own ..

**Total Time Spent - 1.5hr**

---

## July 3rd : Started with the schematic of the PCB

So in the previous day, I have already selected the micro controller and pretty much about the layout of the keyboard. So today I will going to make the schematic for the PCB so that I can start working on the PCB board and I can start working on rest of the thing that can be done only after making the schematic because schematic is the first part for making any PCB and for me taking the right footprint from the library with matching it to the data sheet will take me a lot of time, and I finally managed to get all of this.


**RP2040-Zero**

<img width="614" height="596" alt="6" src="https://github.com/user-attachments/assets/069f2f8f-5fd9-4f2d-a69e-0e5c75b8bf59" />


**PJ-320A TRRS Jack**

<img width="515" height="432" alt="7" src="https://github.com/user-attachments/assets/dec6c5af-67dc-4650-b6a2-555c3f4661e4" />

**All the Keysss..**

<img width="619" height="639" alt="8" src="https://github.com/user-attachments/assets/b0bdf918-9cfe-4009-8cbd-f0f74e170b05" />


#### So during researching about the keyboard, I found out an crucial problem like when we general make split keyboard, we make two PCB for each of the side one for left side and one for right side and when we order the PCB we get five, which is the minimum order quantity but I think that is kind of a wastage when we don't really use the rest of the PCB, so the layout that I will be working on is quite interesting . We will get the five PCBs and we can use each of the PCBs for left and right side by turning it upside down like it can it was working like a reversible PCB so we can use any PCB for left or right hand side, so by this we can reduce the wastage of the PCB. Also, it will easy to make the case and the PCB like I need to just work only for one of the PCBs and I can get it fabricated and I can use it for the both sides, so that's my plan.

## Inspo
<img width="1432" height="797" alt="Screenshot 2026-07-06 at 9 58 13 AM" src="https://github.com/user-attachments/assets/b6a7bb06-933b-4efc-bced-081435317c08" />

<img width="709" height="648" alt="Screenshot 2026-07-06 at 9 59 05 AM" src="https://github.com/user-attachments/assets/c6ea2f83-6bc6-4a8a-83ed-295e32b07c51" />


**Total Time Spent - 3.5hr**
