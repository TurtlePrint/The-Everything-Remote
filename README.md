# The Ultimate Everything Remote

Modifications made to the Everthing Remote to make it the Ultimate Everythign Remote
- Pogo pins for charging
- Removed one of the hardware pull up resistors and added a voltage divider circuit in its place, still retaining button use but now also accuarate battery metrics
- Removed GPIO15 Button and replaced with a WS2812 LED pixel for notifications (And a built in flash light mode)
- Enablded contious press mode on specific buttons to enable holding volume up or down

I'm still working on files and will get them uploaded when done.

<img width="1151" height="1018" alt="image" src="https://github.com/user-attachments/assets/0bd6daff-3f87-42ff-a269-1e25a8250d1b" />

<img width="551" height="1176" alt="image" src="https://github.com/user-attachments/assets/ee3f532f-f0ac-485d-9715-eec5b9755518" />

<img width="866" height="151" alt="image" src="https://github.com/user-attachments/assets/db9a5f2b-f90a-42ae-bc96-a318463362c1" />


# Below is from the original project

A simple universal remote designed for ESPHome - simple to assemble for beginners and experienced tinkerers alike! 

[![Video](https://img.youtube.com/vi/Pe_ozZkrRAw/maxresdefault.jpg)](https://www.youtube.com/watch?v=Pe_ozZkrRAw)


## 📦 Features

- 24 configurable buttons (single press + long press)
- Works over Wi-Fi using ESPHome
- Sends `button_pressed` events to Home Assistant
- Deep sleep support for ultra-low power usage
- Easy to build
- 3D printable, customisable enclosure

---

## YAML

Looking for the YAML for your remote? Here you go!


## Hardware

[Printable Files](https://www.printables.com/model/1281626-everything-remote-esp32-powered-universal-remote)

[Bill of Materials](https://github.com/TheStockPot/TheEverythingRemote/blob/main/Bill%20Of%20Materials.md)

---

## Tutorial Video

[![Video](https://img.youtube.com/vi/JU_7mb1ue7o/maxresdefault.jpg)](https://www.youtube.com/watch?v=JU_7mb1ue7o)


---

## Button -> GPIO Layout

![Button_GPIO](https://github.com/user-attachments/assets/2e815270-fa7c-42a7-87e6-7fd56a0b1cad)
