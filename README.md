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



<h2>Hardware</h2>
- <b>Rasberry pi4</b> 


<h2>Environments Used </h2>

- <b>Linux</b>
- <b>Suricata IDS</b>

