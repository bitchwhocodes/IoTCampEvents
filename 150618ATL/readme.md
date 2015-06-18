# IoT Camp - Atlanta, GA - 06/18/2015 #



EVAL LINK: http://aka.ms/ioteventGA


---

## WiFi Info ##

**PLEASE DO NOT USE THE WIFI HEAVILY.  THIS IS NOT THE TIME TO DOWNLOAD VIDEO TORRENTS!  IF YOU NEED VISUAL STUDIO 2013 SEE ME, DON'T DOWNLOAD IT!**

| SSID:     | msiotcamp     | 
| ---       | ---           |
| **PWD:**  | **msiotcamp** | 

If you have an Ethernet connection, you can plug one of the cables on the tables in.  We will be using those later for the devices though. 


## Presenter Info

Stacey Mulcahy<br/>
stacey.mulcahy@microsoft.com<br/>
@bitchwhocodes<br/>
http://thebitchwhocodes.com<br/>

## Lab Resources
We are working from a fork from Bret Stateham, a SR Technical Evangelist from San Diego. Thank you Bret.
Bret Stateham<br/>
Bret.Stateham@microsoft.<br/>
http://BretStateham.com<br/>

---

## Links ##

| Site                          | Link                     | 
| ---                           | ---                      |
| Bret's  Connect the Dots Fork | http://aka.ms/bsctd      | 
| HOL Videos                    | http://aka.ms/ctdholvids | 
| TweetHeart Video              | http://aka.ms/tweetheart | 
| TweetHeart Tutorial           | http://aka.ms/tweettutorial | 
| Channel 9 Videos 		        | https://channel9.msdn.com/Niners/bitchwhocodes | 

---

## Slides ##

You can grab them from the [Slide Deck](/150618ATL/Slides) folder in this same repo.

## Connect The Dots Fork ##

The live [connectthedots.io] repo has some issues, and doesn't inclue the Hands-On Lab documents for todays events.  

**Make sure you use Bret Stateham's fork of the Connect the Dots Repository:**

http://aka.ms/bsctd


## Hands-On Labs ##

1. [Overview](https://github.com/BretStateham/connectthedots/tree/master/HOLs)
2. [Azure Prep](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/AzurePrep) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
3. [Connect the Dots Sample Web Site](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/WebSite) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
4. [Arduino with SparkFun Weather Shield](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/GatewayConnectedDevices/Arduino%20UNO/Weather/WeatherSheildJson)
5. [Raspberry Pi Field Gateway](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/Gateways/GatewayService)
6. [Gadgeteer with FEZ Spider](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/DirectlyConnectedDevices/NETMF/ConnectTheDotsGadgeteer)

---

## USB Sticks ##

There are some USB Sticks that have the large downloads you may need on them.  

**IF YOU TAKE ONE, PLEASE *COPY* THE CONTENTS TO YOUR COMPUTER THEN PASS IT ON**

**PLEASE RETURN THE USB DRIVES WHEN YOU ARE DONE**
---

## Bret's Event Hub and Web Site Info ##

If you are having problems getting your Azure Backend to work, you can try pointing at mine.  Just make sure that 

1. You give your sensors a unique name so you can see it on my page 
2. Give your sensors a unique GUID
3. Both of the above would be in either your Arduino source code, or in the Gadgeteer source code, depending on which type of device you are using.  s

|  Item           | Value                                             | 
| ---             | ---                                               |
|Service Bus Name:|ctdatlsm-ns                                          |
|Event Hub Name:  |ehdevices                                          |
|Key Name:        |D1                                                 |
|Key:             |DUxOk2/kIDfZrb6LZwczZZiXD/Va5cw+C7ZA5GwJz4M=		  |
|URL Encoded Key: |DUxOk2%2FkIDfZrb6LZwczZZiXD%2FVa5cw%2BC7ZA5GwJz4M%3D |
|Web Site URL:    |http://ctdatlsm.azurewebsites.net/                |	
|tcpdump info     | http://www.networkworld.com/article/2225683/cisco-subnet/raspberry-pi-as-a-network-monitoring-node.html | 
