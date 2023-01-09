# Home Assistant Ökofen Pellematic Compact REST-Template (Ökofen JSON-Interface)

*************************************
Meanwhile i developed a Home Assistant Integration -> Feel free to use: https://github.com/dominikamann/oekofen-pellematic-compact
*************************************

A template how to integrate a Ökofen Pellematic Compact via JSON Interface to Home Assistant.

Step 1: Go to your Ökofen Pellematic Compact -> Touchscreen -> Open General Settings -> Network Settings -> Scroll down -> Activate JSON Interface
Step 2: Copy the template and enter your IP-Address (Pellematic), Port & Password
Step 3: Go to HomeAssistant, open your configuration.yml and insert the template
Step 4: Restart HomeAssistant
Step 5: Go to your dashbard, add a new card and insert code from homeassistant_card_multivalue.yml
Step 6: After saving the file all sensor values are visible in your dashboard  

Naming:                       JSON-Identifier
  - HeatingCircuit            hk[x] -> e.g. hk1
  - BufferTank                pu[x] -> e.g. pu1
  - HotWaterCircuit           ww[x] -> e.g. ww1
  - PellematicHeater          pe[x] -> e.g. pe1
  - System                    system

![grafik](https://user-images.githubusercontent.com/29973737/194421559-d1842fad-5209-4be3-bc7d-591227b2ee68.png)

Feel free to share, change, extend & contribute.
