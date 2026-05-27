## Variables 

# Data Source
Where is the data coming from?
Music Service, Controller, Line- in source, Music Library, Phone.

# DataPlayer : 
Where is it supposed to get to?
Sonos Device

# Data Path: 
How is getting there?
Network/ Topology
HDMI, Sonosnet, Ethernet Cable, Line Source to player, Router/Gateway, Internet.

* Direct Routing: path that device use to.

Steps: 

* Identify which variable is causing the issue.
* Troubleshoot related to variables

   - Data Source: Tried with different (Spotify, TV)
   - Data Player: Tried different speaker
   - Data Path: Req Topology, Tried different cables, review config on Router.


Steps
- Review LED Status 
- Get Diagnostic to confirm its getting an IP
- Tried with another controller
- Review router configuration

## Reasons for Failures

# Topology 

Difference between a switch and managed switch (Managed can be handle by IT more than 6 ports)
Double NAT 

# Router Settings/Faults

MAC filtering
Access control
Client/AP isolation 
Airtime Fairness
Guest Network
Broadcast failures
Multicast failures
DHCP 

# Environment

Obstacles Distance from Ap
Interference (printer, cameras)
Shared channel Interference (Same Channel)
Adjacent Channel ( Channel)

# LED TEST SEQUENCE
1.Solid red: indicates the start the LED Diagnostic Sequence

2.Flashing white: The number of flashes indicates the 2.4GHz channel (e.g. 6 flashes = channel 6). For SUB/Surround satellite operating on 5 Ghz channel do not flash. If satellite is currently working on the 2.4 GHz channel flash white the same number of times as the channel number. Verify that the WiFi channel number matches your HouseHold's configured channel number. Note: Players connected to a 5GHz WiFi network would not be expected to flash white during this step.

3.Solid amber: indicates that the player has received a DHCP assigned address.
   Flashing amber: indicates that the player has failed to obtain a DHCP address and instead has reverted to an Auto IP address.

4.Solid green: indicates that the Ethernet interface is up.
   Flashing green: indicates that the Ethernet interface is down.

5.Solid white: indicates that the player believes that it can communicate a house hold. Flashing white: indicates that it cannot communicate with a house hold.

6.Solid red: indicates the end of the sequence and starts it again.

# Troubleshoot can connect to Sonos

Speaker cannot associate to existing system with the Controller

When to association

* Sonos app is opened
* Join a new controller 
* Setting up new Sonos system 

In regards to association issues, the variables are:

Data Source: The controller
Player: The associating player
Data Path: Topology

Review LED Test
Confirm if its Station Mode or Sonosnet
Is there any other devices?
How they are connected
If the Sonosnet is faulty tried with different player
If they are no connected to IP(Topolgy)

## HOME THEATER

CEC Allows to control HT with TV control and Voice controller

# No Audio

- Verify the physical connection 
- Confirm the cable on both ends
- If optical cable, verify light
- Logical Address 5 allow sonos to first 
- Internal Audio Source Disable 
- System Audio mode Enable
- ARC enable 
- CEC  enable 

# Cold reboot 
Disconnect the TV and soundbar from power and the optical cable or HDMI
Also if the TV has other things connected on the back disconnect them while we test this
Then turn on the Soundbar
Connect the Optical cable/HDMI back on both ends make sure it's well seated IF Using an HDMI Make sure it goes in the ARC/eARC port on the TV
Plugback in the TV
Also if the TV has other things connected on the back disconnect them while we test this

# Audio Cutting Out 

- The TV, the cable or the player
- Check TV audio settings
- Confirm What codec
- Check AnacapaHT(msj LSE:Stream reset spdif on stop)
- Switch from PCM to DD 
- Swap HDMI

# Low Volume 

- Audio Settings (Diagnostic)
- Something below 25 
- Volume limit
- Night Mode

# No audio on Satelite(surrounds)

- Another Data Source 
- Diag check Component Summary
- Review format Old movies/ TV shows/ News

# Unable to add Satelite 

- Issue with 5 GHz
- Get topology 

# Audio Dropouts 

- Data Source: Music Services, Line in, TV 
- Data Path: Wifi Router, HDMI, RCA 

Probing Questions?

Is is happening in only one unit?
LED status when the drop is happening?
What source is the cx using?
Is the user using multiple sources?
When did the use issue start?
Any network notification?
SonoNet (WiFi Sonosapp) or Station Mode ?( Wired Router)


































