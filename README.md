
<div align="center">
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td align="center" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/8942e808-1710-489f-a4be-4ef55905c665" width="100%" max-width="800px" alt="Rough Layout For The PCB" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 500;">
      </td>
    </tr>
  </table>
</div>


|Title | Twin Key |
|:-- |:--|
|Author | Sadrita Neogi|

# Website for Twin Key go check it out - [Live URL](https://twin-keyboard.vercel.app/)



### what I have built

This split keyboard is basically fixes everything annoying about standard typing. We took the logic of an ortholinear grid (where everything is predictable) and mashed it together with a column stagger that actually matches how long your fingers are. For me this type of form factor keyboard is good for long hours of typing.


### Why I choose this project?
So behind choosing this project is basically I love split keyboard and the way it just fold and compact. It is easy to carry and it is good for writing for long hours, so I wanted to make one for myself not to buy it but to make it for myself and customisable, so this is the reason I choose this project.


### what I have learned

Through out making this project I have learned a lot of thing but the main that I gain strengh is listed below 

* PCB design using KiCad
* Mechanical keyboard architecture
* KMK scripting
* Fusion 360 CAD Work 
* How to choose Part's for project in budget


### Features 

* It's an 18 - 18 layout Split Keyboard .
* The connection between two keyboard are using 3.5mm TRRS to TRRS Cable.
* The main micro controller of this keyboard is RP2040-Zero and RP2040-Tiny.
* The PCB of this keyboard is reversible so that we can reduce the PCB wastage.
* This is an wired Keyboard 
* This Keyboard is made for good ergonomic
* QMK Firmware support for this keyboard 
* Hot-swappable ( for every keys )
* This is a low profile keyboard 
* Custom 3d printed case and top plate

### Components Used in this Build 

| Item |
| --- |
| PCB (MOQ 5) |
| RP2040-Zero (left side) |
| RP2040-Tiny (right side) |
| Kailh Choc v2 Low Profile Switches |
| Kailh Choc PG1350 Hot Swap Sockets |
| CFX MX Low Profile Keycaps |
| 1N4148 SOD-123 SMD Diode |
| PJ-320A TRRS Jack |
| M2×3 heat-set threaded inserts |
| M2×5 countersunk screws |
| 3.5mm TRRS to TRRS cable |
| Type-C to Type-C cable |


## Firmware

Precompiled VIA-enabled firmware:

- Flash `twin_key_sadrita.uf2` under [Firmware/](Firmware/) to the RP2040 MCUs.
- Load the [via.json](https://github.com/Sadrita404/Twin-Key/blob/main/Firmware/QMK/keyboards/twin_key/via.json) file in `Design` tab for [VIA](https://usevia.app) configuration.

QMK source is available under [firmware/QMK/keyboards/Twin-Key](https://github.com/Sadrita404/Twin-Key/tree/main/Firmware/QMK/keyboards/twin_key).



### Journal - [Journal.md](https://github.com/Sadrita404/Twin-Key/blob/main/Journal.md)


<div align="center">

| | Building Process | |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/a658099e-e0c1-4440-b17c-a0f4168fa6ed" width="100%" /> | <img src="https://github.com/user-attachments/assets/0d5e2b55-575e-4615-b95c-1178ef51f906" width="100%" /> | <img src="https://github.com/user-attachments/assets/fed89f04-1a26-4528-b030-14e272187758" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/1d4ac166-9032-4e8b-81b3-bca63945b287" width="100%" /> | <img src="https://github.com/user-attachments/assets/b6106557-6cc1-422f-a06e-9819eab307c9" width="100%" /> | <img src="https://github.com/user-attachments/assets/f7200940-218c-4f83-afef-82e2102ea0ec" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/f8e1f592-66fa-409a-b0b4-051ae611a034" width="100%" /> | <img src="https://github.com/user-attachments/assets/5a249239-1e32-498f-a827-63e4aadc1099" width="100%" /> | <img src="https://github.com/user-attachments/assets/47df6155-37a1-4970-b3b0-dc0a216bca05" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/f624a89b-4721-4e76-8dbb-bac5cc366549" width="100%" /> | <img src="https://github.com/user-attachments/assets/5bb80604-8176-4b06-afb1-6173f0ba5527" width="100%" /> | <img src="https://github.com/user-attachments/assets/5fb7f6c9-f681-4d75-a019-6ad055f45853" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/fa758cdd-f25e-40b3-84ce-19535d9a558c" width="100%" /> | <img src="https://github.com/user-attachments/assets/c6b458a8-6334-46f0-a84a-aca449889995" width="100%" /> | <img src="https://github.com/user-attachments/assets/08be6f78-4e54-4cc7-bbab-1bea4a3e0a39" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/2c8e80d8-f91f-4fe6-9530-d7986ebdfde0" width="100%" /> | <img src="https://github.com/user-attachments/assets/ef49495b-dbca-4ef3-8490-e93663a01857" width="100%" /> | <img src="https://github.com/user-attachments/assets/20116e59-085e-4cf9-a5f6-f96ec94b4eec" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/95a5a9b9-6e2a-4ded-8b3d-5261e04bc6d9" width="100%" /> | <img src="https://github.com/user-attachments/assets/a5fd5569-5b7d-42e2-9519-cb96d44845f7" width="100%" /> | <img src="https://github.com/user-attachments/assets/3483d5a9-e958-44a3-8ec0-04c7cbdfa462" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/c7fb158a-cfd8-45f8-b0ec-8ae7ba9352a8" width="100%" /> | <img src="https://github.com/user-attachments/assets/f1764ff6-8be8-4e82-a9f6-b893cfb4bb53" width="100%" /> | <img src="https://github.com/user-attachments/assets/2367de9e-3259-4ea0-b6bf-c1e8562f7fe7" width="100%" /> |




<div align="center">
  <h2> Final PCB </h2>
  <table border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
    <tr>
      <!-- FRONT SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/a4178a2c-75d3-4db2-8528-6f2520c6f13e" width="100%" alt="Front Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Left Side
        </div>
      </td>
      <!-- SPACER FOR GITHUB MOBILE DEGRADATION -->
      <td width="2%">&nbsp;</td>
      <!-- BACK SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/11a62ee8-de7c-49f5-a1b0-233c9f363e79" width="100%" alt="Back Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Right Side 
        </div>
      </td>
    </tr>
  </table>
</div>
</div>


## Final Render 

<div align="center">

<img src="https://github.com/user-attachments/assets/4e8f50fd-025e-4cc5-ae18-0321aeed9e14" width="100%" style="border: 4px solid #ccc; border-radius: 6px; margin-bottom: 15px;" alt="render 1" />

<img src="https://github.com/user-attachments/assets/e759321b-a368-4c93-a1c9-36371b1dd2f1" width="100%" style="border: 4px solid #ccc; border-radius: 6px; margin-bottom: 15px;" alt="render 2" />

<img src="https://github.com/user-attachments/assets/63603048-2754-44f4-a2a2-ea6382959d3f" width="100%" style="border: 4px solid #ccc; border-radius: 6px; margin-bottom: 15px;" alt="render 3" />

</div>




<div align="center">
  <h2> Bill of Materials </h2>
</div>

| Component Name | Purpose | Qty | Unit Price | Total Price | Source Link |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **PCB (moq5)** | The Main Board | 5 | $1.54 | $7.70 | [JLC PCB](https://jlcpcb.com/) |
| **RP2040-Zero (left side)** | Micro Controller | 1 | $4.43 | $4.43 | [Robu](https://robu.in/product/waveshare-rp2040-zero-without-header/) |
| **RP2040-Tiny (right side)** | Micro Controller | 1 | $6.26 | $6.26 | [Robu](https://robu.in/product/waveshare-rp2350-tiny-development-board-based-on-rp2350a-dual-core-dual-architecture-microcontroller/?gad_source=1&gad_campaignid=17413441824&gbraid=0AAAAADvLFWfMmG_4cBVpxgNEEXfCiOFrF&gclid=CjwKCAjwpK3SBhASEiwAtV1SPJrBF3sV-JAP5m2gTerZJ6Riy5xOkoX3tXxzK_EEo8mEBhyrUuSYEhoCxZoQAvD_BwE) |
| **Kailh Choc v2 Low Profile Switches** | The switches to press | 40 | $0.63 | $25.00 | [Neomacro](https://neomacro.in/products/kailh-choc-v2-low-profile-switches?variant=51316563345686) |
| **Kailh Choc PG1350 Hot Swap Sockets** | To put the switches | 40 | $0.18 | $7.00 | [Neomacro](https://neomacro.in/products/kailh-choc-pg1350-hot-swap-sockets) |
| **CFX MX Low Profile Keycaps** | For the Switches | 1 | $26.30 | $26.30 | [Neomacro](https://neomacro.in/products/cfx-mx-low-profile-keycaps) |
| **1N4148 SOD-123 SMD Diode** | For the PCB Board | 40 | $0.03 | $1.00 | [Stackskb](https://stackskb.com/store/1n4148-sod-123-smd-diode/?srsltid=AfmBOooo4zZ2FHq_nIucF0OJiEtuzsTc2tOnpuoy_xhe-UcQ5pIkwrEd) |
| **PJ-320A TRRS Jack** | For the Wire Connection | 2 | $0.50 | $1.00 | [Stackskb](https://stackskb.com/store/pj-320a-jack/) |
| **M2×3 heat-set threaded inserts** | For fixing the case | 20 | $0.02 | $0.40 | [Self Sourced](https://onlyscrews.in/products/m2-x-3mm-brass-threaded-inserts?srsltid=AfmBOorVSTwK3G5H08PBTqA47STmoCIWA4xz0boRvR8ihsL0Kdnwk8F5) |
| **M2×5 countersunk screws** | For fixing the case | 20 | $0.03 | $0.60 | [Self Sourced](https://onlyscrews.in/products/m2-5-x-16mm-phillips-csk-ss-304-screw-dia-2-5mm-length-16mm?currency=INR&country=IN&variant=51158557393209&stkn=6e84ebfba1b8&utm_source=google&utm_medium=cpc&utm_campaign=sales_pmax&utm_id=23949204632&utm_term={adgroup}&gad_source=1&gad_campaignid=23953886635&gbraid=0AAAAA9sP2STwTW01fCxMnAJNjH3poMXxs&gclid=CjwKCAjwpK3SBhASEiwAtV1SPAjy69mRkSBp_vrUqPKL9_t7nT_D9hi1XdFlchSsnUIymW6eQlEjZhoCIz4QAvD_BwE) |
| **3.5mm TRRS to TRRS Cable** | For the keyboard connection | 1 | $4.80 | $4.80 | [Amazon](https://www.amazon.in/IVON-3-5mm-Cable-Microphone-Compatible/dp/B0G2BPJMXV/ref=asc_df_B0G2BPJMXV?mcid=5a927b15325338dfaab07d284616b26d&tag=googleshopdes-21&linkCode=df0&hvadid=709962856313&hvpos=&hvnetw=g&hvrand=12409040854364914229&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9301294&hvtargid=pla-2469077957225&psc=1&hvocijid=12409040854364914229-B0G2BPJMXV-&hvexpln=0&gad_source=1) |
| **Type C to Type C Cable** | For the micro controller | 1 | $2.00 | $2.00 | [Amazon](https://www.amazon.in/HAMMER-Braided-Chraging-Compatible-Enabled/dp/B0CXM7FCHC/ref=asc_df_B0CXM7FCHC?mcid=86690e5813223229bb0806b69069995d&tag=googleshopdes-21&linkCode=df0&hvadid=710073091892&hvpos=&hvnetw=g&hvrand=168727803120444090&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9301294&hvtargid=pla-2302558369595&hvocijid=168727803120444090-B0CXM7FCHC-&hvexpln=0&gad_source=1&th=1) |
| **3D Print** | For the Case | 1 | $0.00 | $0.00 | [#printing-legion](https://printlegion.hackclub.com/) |
| **Shipping** | Including PCB shipping | - | - | $13.40 | - |
| **Total** | | | | **$99.89** | |
| **Round Off Budget** | | | | **$100** | |

I have provided the links for the parts I will be self-sourcing, so that if readers want to recreate this, they will be able to get all the parts.This is also updated on the [bom.csv](/bom.csv)


## Copyright and License
Copyright (c) 2026 Sadrita Neogi. All rights reserved.

All files are licensed under the MIT license. For more information, see the [LICENSE](LICENSE).

Project Under Hack Club

