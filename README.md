# Week 9 - Honeypot

Time spent: **15** hours spent in total

> Objective: Learn about Network Security by attacking and being attacked at vulnarable networked resources. Multiple Honey Pot VM instances were created to demonstrate it.

## Honeypots Deployed
1. dionaea (x 3)
2. snort
3. wordpot
4. p0f

I deployed the honeypots and left it on for about 2 days to gather my results.

## Any issues you encountered
The github clone link was broken in the instructions I had to find the right one myself to set up MHN.

## Overview setup
I followed the instructions given for this lab to set up Google Cloud Platform. I created six VMs. One VM for admin control and the other five for deplying the honeypots.

### GCP Setup
1. Follow the instructions given on the lab to set up GCP.
2. I set up 6 Vms for honeypot deployment. 3 of the VM's were `dionaea`. The other three were `snort`, `wordpot`, and `p0f`

## A summary of the data collected: number of attacks, number of malware samples, etc

### GCP VMs
![](https://github.com/ayushyamitabh/Week9-CodePath-Cybersecurity/blob/master/gcloud.gif)

### Sensors
![](https://github.com/ayushyamitabh/Week9-CodePath-Cybersecurity/blob/master/sensors.PNG)

### Attack Stats and Report
![](https://github.com/ayushyamitabh/Week9-CodePath-Cybersecurity/blob/master/stats.PNG)
![](https://github.com/ayushyamitabh/Week9-CodePath-Cybersecurity/blob/master/attacks.gif)

## Resources
GIFs created with [EZ Gif](https://ezgif.com)

## License

    Copyright [2018] [Ayushya Amitabh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
