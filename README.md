# Home Assistant Ökofen Pellematic Compact REST-Template (Ökofen JSON-Interface)

A template how to integrate a Ökofen Pellematic Compact via JSON Interface to Home Assistant.

Step 1: Go to your Ökofen Pellematic Compact -> Touchscreen -> Open General Settings -> Network Settings -> Scroll down -> Activate JSON Interface
Step 2: Copy the template and enter your IP-Address (Pellematic), Port & Password
Step 3: Go to HomeAssistant, open your configuration.yml and insert the template
Step 4: Restart HomeAssistant & enjoy

Naming:                       JSON-Identifier
  - HeatingCircuit            hk[x] -> e.g. hk1
  - BufferTank                pu[x] -> e.g. pu1
  - HotWaterCircuit           ww[x] -> e.g. ww1
  - PellematicHeater          pe[x] -> e.g. pe1

Feel free to extend the template and add meaningfull identifiers. Iam happy if you contribute.

