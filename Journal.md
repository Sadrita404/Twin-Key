
| Title | Twin Key |
| :-- | :---|
|Author |Sadrita Neogi|
|Type | Split Keyboard |


## June 24th : Research about the micro controller for the keyboard

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

**Total Time Spent - 2.4hr**

---

## June 26th : Started with the schematic of the PCB

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


**Final Schematic**

<img width="816" height="584" alt="9" src="https://github.com/user-attachments/assets/5d4243cc-0cbb-4ddf-a844-39298fd08a2e" />


**Total Time Spent - 3.5hr**

---

## June 28th : Done With the PCB tracing 

So previously I have completed a schematic of the PCB and I take one day gap because I was not in my hometown, so after coming I went to look at the schematic, and then I realise that I need to do a lot of work like I have just made the schematic now I need to import that schematic into PCB designing. Then I need to trace all the pads. So today I will do all of that hopefully completed that, like the main problem is the DRC check error,  I don't know. I have done completing all the traces, but suddenly it's showing error. Hopefully, I will try my best this time. I will do it with all my concentration so that nothing gets out and all the pads should be routed.

**updating PCB from schematic**

<img width="1099" height="634" alt="10" src="https://github.com/user-attachments/assets/05511e62-70db-40a1-ab16-3f000932e0ef" />


<img width="620" height="685" alt="11" src="https://github.com/user-attachments/assets/8b20f169-b127-4fbf-97e9-38b4910e06e6" />

<img width="800" height="536" alt="12" src="https://github.com/user-attachments/assets/1488a06a-5989-4e26-ad09-734ba373739f" />

<img width="631" height="420" alt="13" src="https://github.com/user-attachments/assets/ed480f51-0b51-4a90-806b-fec13ffdb595" />

<img width="804" height="538" alt="14" src="https://github.com/user-attachments/assets/c8b634fa-db51-4df8-a11e-b5e42d977984" />

Finally, after a lot of time, I have finally completed the PCB designing part steal the PCB looks bit more like normal. I need to add some silk screen to the PCV, I will do it on the next day because today, I am so tired doing all the PCB tracing, and the copper layer is too much


**all pads are routed**

<img width="438" height="102" alt="15" src="https://github.com/user-attachments/assets/4bec9dd9-dea1-4b2d-a7da-823a72043e5d" />




**Total Time Spent - 4.6hr**

---

## July 2nd : Completing the rest of the PCB part

So today I started making the pcb more good looking by adding the silk screen into the pcb and I have export the PCB step file for the case design that I need to make for this PCb .
I make the PCB silk screen simple because when I will solder all the parts like the switches all this will not be visible to use so I think I think it will be better to make the PCB clean 

**adding my name to the PCB**

<img width="379" height="171" alt="16" src="https://github.com/user-attachments/assets/2e3dba17-18e3-47bb-9fe1-21f6f4a8cff0" />

<img width="1339" height="759" alt="17" src="https://github.com/user-attachments/assets/de9d599f-221e-4ec5-acae-eff229fe3c97" />

<img width="1458" height="832" alt="18" src="https://github.com/user-attachments/assets/612e96b2-491a-4fd4-9c76-96b3dabb7da2" />

**Hack Club Logo added to the PCB**


<img width="1443" height="839" alt="19" src="https://github.com/user-attachments/assets/0fdf2e87-6c22-4f0b-b533-27ac7e40ba35" />

<img width="672" height="399" alt="20" src="https://github.com/user-attachments/assets/33479a83-93a3-4735-9262-44c18bae875b" />

#### DRC Check - yaa No error after tracing all the pads correctly 

<img width="1129" height="778" alt="21" src="https://github.com/user-attachments/assets/7316a74b-0f14-4039-85fd-cb74c94adb42" />

<img width="988" height="592" alt="22" src="https://github.com/user-attachments/assets/c17ddec4-1fcc-4698-8c4c-e2710af596fa" />

**Final look**

#### Left 

<img width="801" height="531" alt="23" src="https://github.com/user-attachments/assets/95bf7f78-ffd9-4398-934b-871854b6ba8c" />


#### Right 

<img width="801" height="534" alt="24" src="https://github.com/user-attachments/assets/0a2c15c3-277a-4d47-b491-884c112d76b1" />

**plotting the Garber file**

<img width="1383" height="811" alt="25" src="https://github.com/user-attachments/assets/64f46db0-911e-4060-b444-47c031d44bfb" />

**Total Time Spent - 1.8hr**

---

## July 3rd : Working on some errors 

So I have added one extra rows in the keyboard schematic so that I can reduece the Macro layer in the firmware and I have more room to add the key mapping in the first layer to add the basic needs of an keyboard ..

<img width="623" height="237" alt="Screenshot 2026-07-06 at 11 00 37 AM" src="https://github.com/user-attachments/assets/362f3292-20a6-425b-a520-efb1cb5668b0" />


Next I went to the JLC pcb to just check what will be the cost of my PCB after production 

**Also I have generate the gerber file again with this changes**

<img width="1438" height="808" alt="bill 1" src="https://github.com/user-attachments/assets/a82511cd-6f98-437a-8ff9-4aaf6e155ccb" />



For today I will not do any work as I need to do my school work now and suddenly I thought to add one extra row in the keyboard so that's whay I am just making this amout of progress today hopefully, done something based in the coming days..

**Total Time Spent - 0.5hr**

--






