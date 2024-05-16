# OpenCTI by CyberAngel9

Before I begin, I want to give full credit to 0xBEN and everyone behind the OpenCTI GitHub project. 

OpenCTI Github
```
https://github.com/OpenCTI-Platform
```

0xBEN Walk-Through
```
https://benheater.com/proxmox-running-opencti/
```

I set up OpenCTI on a Debian ISO, utilizing Docker Engine, Docker Swarm, Portainer, and OpenCTI Connectors, all within a VMware virtual machine. To achieve this, I used Git Bash and established an SSH connection to the Debian server. Certain configurations were necessary on the Debian server to enable SSH access and facilitate the setup process.


0xBEN's walkthrough is generally straightforward, with only a few necessary configurations that may seem a bit confusing, especially for first-time users. However, with some trial and error, I successfully set up OpenCTI and configured server Connectors to display data on the dashboard.


OpenCTI is an open-source cyber threat intelligence platform that combines a knowledge management database with data visualization and context management for observables and indicators. You can easily access and analyze data by employing connectors to gather data within the OpenCTI interface. The dashboard offers an organized layout for visualizing and interacting with the collected information.


Connectors play a crucial role in linking to the database and fetching data for viewing in OpenCTI. There are five distinct types of connectors: External Import, Internal Enrichment, Internal Export File, Internal Import File, and Stream. I opted for the External Import connector. Some of these connectors require an API, an OpenCTI Token, and a Connector ID. After obtaining all the necessary information, the process becomes as simple as copying and pasting it into Portainer under the stack details. Once the stack is updated, the data will start populating in OpenCTI, although it's important to note that some data uploads may take a while.

Overall, my first experience with an open-source cyber threat intelligence platform went quite well. Additionally, I found it particularly advantageous that I can add as much data as I need, provided I have sufficient storage capacity.

### The Connectors in use
![OpenCTI Connected](https://github.com/cyberAngel9/OpenCTI-Project/assets/82012925/72595e98-11a4-4dcc-87fd-24a26d01f74e)

### My Dashboard 
![image](https://github.com/cyberAngel9/OpenCTI-Project/assets/82012925/fc5c6d1e-ecd0-455c-98ac-32f47dc7801e)
