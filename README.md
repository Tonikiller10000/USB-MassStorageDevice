# USB MassStorageDevice


This project is an USB mass storage made with:
- 2x K9GAG08U0E 16GB NAND flash memory chips (32GB total) 
- lateral switch for read-only operation mode 
- an ST72681 memory controller 
- LD3985 3.3V regulator
- 12MHz crystal resonator
- other passive components

After testing the board with an 220nF THT ceramic capacitor because the SMD did not arrived in time, I made some improvisations trying to fix it, and
 it still `does not work`. It seems like the memory chip and the controller ic\`s are not compatible so 
 `I will have another look on this project in the distant future` with different components.

<img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/3DModel.png"/>

<img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/proiectareV2.png"/>


Schematic:

<img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/schematic2.png"/>

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/stk3.jpg" ></td>
    <td><img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/stk5.jpg" ></td>
    <td><img src="https://github.com/Tonikiller10000/USB-MassStorageDevice/blob/main/USB_MassStorageDevice_Pictures/stk6.jpg" ></td>
  </tr>
 </table>


Datasheets:
- NAND: https://pdf1.alldatasheet.com/datasheet-pdf/view/104019/STMICROELECTRONICS/ST72681.html
- Controller: https://pdf1.alldatasheet.com/datasheet-pdf/view/1134995/SAMSUNG/K9GAG08U0E.html
- Regulator: https://pdf1.alldatasheet.com/datasheet-pdf/view/85490/STMICROELECTRONICS/LD3985.html




