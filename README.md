<h1>raspi4-intrusion-detection</h1>


<h2>Description</h2>
This Project aims to transform a Raspberry Pi 4 into a powerful Intrusion Detection System (IDS) using Suricata.Which we will use to monitor network traffic and implementation of network 
security at a smaller scale.
<br />


1. **Setting Up of Rasberrypi4:** To install a Linux distribution on a Raspberry Pi using Etcher, follow these steps:
   
  Download the desired Linux image and Etcher software.
  Open Etcher, select the Linux image, choose the target SD card, and click "Flash" to create a bootable SD card for your Raspberry Pi.

2. **Installation:** Install Suricata on your Raspberry Pi 4 using the following commands:  
   ```bash
   sudo apt update
   sudo apt install suricata
   ```
3. **Config Suricata:** Configure Suricata by following these steps:
      ```bash
      sudo nano /etc/suricata/suricata.yaml

      ```
      ![configSuricata](https://github.com/pramoddhayapule/raspi4-intrusion-detection/assets/72139404/ca3d564b-3625-4671-adfd-e955065b405a)

   In this config file you make chages like ip address and network interface you want to monitor.

   ![Config File crpd](https://github.com/pramoddhayapule/raspi4-intrusion-detection/assets/72139404/e7ae9b50-4cc6-406d-a242-aef631369309)

4. **Execution of Suricata:** To Start/Status/Stop Suricata use the following commands:  
   To Start:
    ```bash
   sudo systemctl start suricata
   ```
   To Check Status:
    ```bash
   sudo systemctl status suricata
   ```
    To Stop:
     ```bash
   sudo systemctl stop suricata
   ```
     ![SuricataStatus](https://github.com/pramoddhayapule/raspi4-intrusion-detection/assets/72139404/52de2afe-462c-4b11-bd05-0d8fc29d6618)


5. **To Monitor Network Traffic/Attacks:**
All the network logs are logged in suricata folder known as fast.log so if the attack or any network requests are made to this ip addr are stored in this log file as you can see below we made a ping request from another same network workstation it got logged.
![Screenshot_2024-01-05_07-58-23](https://github.com/pramoddhayapule/raspi4-intrusion-detection/assets/72139404/b0559c8e-a49c-4b08-a215-769d50f20626)

   
    





<h2>Hardware</h2>
- <b>Rasberry pi4</b> 


<h2>Environments Used </h2>

- <b>Linux</b>
- <b>Suricata IDS</b>

