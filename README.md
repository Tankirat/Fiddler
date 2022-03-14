# Fiddler
## Introduction:

Fiddler is a debugging proxy software tool to used to inspect, log and alter HTTP and HTTPS traffic between client and Web Server. Fiddler as a name represents additional products including Fiddler Everywhere, Fiddler CLassic, Fiddler Core, Fiddler Cap, and Fiddler Jam. This document focuses the details on Fiddler Everywhere.

Fiddler Everywhere is the newest version in the debugging proxy which can work on macOS, Linux and Windows operating systems.

### Useful Links:

[Product](https://www.telerik.com/fiddler)

[Tutorial on Fiddler Everywhere](https://www.youtube.com/watch?v=k-Df7Aw99U4&t=262s)

[Hacking Using Fiddler](https://www.youtube.com/results?search_query=hack+fiddler)


## About proxy:
A proxy is a server application that run in between the client that making the web request and the web server which responds with the web resource. Proxy application acts a Man In the Middle and can see the HTTP/HTTPS traffic. Since the HTTPS traffic is enrcrypted to inspect the HTTPS traffic the proxy needs to install root certificate.

![Web Proxy](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Proxy_concept_en.svg/800px-Proxy_concept_en.svg.png)


## Use Cases:
* Web/Desktop/Mobile Debugging
* API Debugging
* Performance Testing
* Website analytics and Monitoring
* Malware Analysis
* Security Testing

## Features:
* Network Traffic Inspection
* Auto Responding Rules
* Mock Responses
* Visualise HTTP/HTTPS Traffic

## Demo:

### Inspect HTTP/HTTPS Traffic:

To inspect the HTTP/HTTPS traffic we first need to install the root certificate, which can be done by selecting the HTTPS options and then trusting the root certificate shown in below screenshot. 

![HTTPS Setting](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(2).png)


Now we can inspect both the HTTP/HTTPS traffic as shown below. 
![HTTPS Setting](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(3).png)


### Team Collboration:

Fiddler has very useful feature to save and share the web traffic and logs to the teams which can be shown below screen shots. 

![Save Session](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(6).png)

![Share Session](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(4).png)


### Autoresponder:

Using autoresponder user can apply specific rules on the particular URLs or requests and when request meets the rule parameters the applied rules such as Update Request Body, Update Response Body, Update URL, Manual Response, Response File, Delay Request etc. This can be shown in the below screenshot where rule is being set for youtube.com.

![Share Session](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(9).png)

![Share Session](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(8).png)

### Mobile Debugging:
Using Mobile debugging we can redirect the web traffic from the Android, or Ios mobile device to the system where fiddler is running, we have manually set the ip and the port of the system in the proxy on the mobile device then installed the fiddler CA certificate on the mobile device, Using this we are able to redirect the web traffic, both HTTTP/HTTPS requests and responses to the Fiddler proxy which can then be processed and inspected. This can be seen in the below screenshots. 

![Share Session](https://github.com/Tankirat/Fiddler/blob/main/MicrosoftTeams-image%20(10).png)




## Refrences:

[Product web resource](https://www.telerik.com/fiddler)

[About Fiddler, wikipedia](https://en.wikipedia.org/wiki/Fiddler_(software))

[About Proxy, wikipedia](https://en.wikipedia.org/wiki/Proxy_server)

[Tools and Haking, Medium](https://medium.com/swlh/hacking-the-web-with-fiddler-72d026eee6bd#:~:text=Fiddler%20allows%20you%20to%20decrypt,certificate%20and%20enabling%20HTTPS%20decryption.&text=First%2C%20start%20Fiddler%20on%20the,says%20%E2%80%9CDecrypt%20HTTPS%20Traffic%E2%80%9D.)

[Video Tutorial, Youtube](https://www.youtube.com/watch?v=k-Df7Aw99U4&t=276s)

[Haking Using Fiddler Clasic Video, Youtube](https://www.youtube.com/watch?v=EIY5GExcPf4)
