% A Gentle Introduction to IoT Protocols: MQTT, CoAP, HTTP & WebSockets  
% Antonio Almeida and Jaime González-Arintero  
% June 14, 2017

------------------

<!--This image was provided by the organizers to encourage the attendees to rate the session. There's a similar image at the end of the presentation. Instead of Markdown, HTML is used to make sure the picture is adequately scaled.-->

<p style="text-align:center;">
<img src="assets/intro-ams17.png" alt="GOTO Rate Intro" style="width: 100%"/>
</p>

## Warning: we'll go fast!

<p style="text-align:center;">
<img src="assets/full-speed-ahead.gif" alt="Full speed ahead" style="width: 70%"/>
</p>

## Visionaries

### >_ On-line Man-Computer Communication, 1962

<p style="text-align:center;">
<img src="assets/visionaries-on-line-man-machine.png" alt="On-line Man-Computer Communication" style="width: 80%"/>
</p>


## Visionaries

### >_ The Computer as a Communication Device, 1968

<p style="text-align:center;">
<img src="assets/visionaries-computer-as-a-communication-device.png" alt="The Computer as a Communication Device" style="width: 80%"/>
</p>


## Arpanet

<p style="text-align:center;">
<img src="assets/arpanet.png" alt="Arpanet" style="width: 80%"/>
</p>



## Why more protocols?

<p style="text-align:center;">
<!-- Use the image from La Dolce Vita -->
<img src="assets/why-more-protocols.jpg" alt="Why more protocols?" style="width: 80%"/>
</p>


## Connected devices

### >_ Some figures...

<p style="text-align:center;">
<img src="assets/machines-go-online.png" alt="Machines Go Online" style="width: 60%"/><blockquote style="float:right">-MIT Technology Review, 2014</blockquote><br clear="all" />
</p>


## Connected devices

### >_ Some figures...

* 14 bn connected devices | Bosch SI
* 50 bn connected devices | Cisco
* 309 bn IoT supplier revenue | Gartner
* 1.9 tn IoT economic value add | Gartner
* 7.1 tn IoT solutions revenue | IDC

> _By 2020, component costs will have come down to the point that connectivity will become standard feature, even for processors costing **less than $1**._  
- Peter Middleton, Gartner


## Constrained devices

<br/>

* IETF Definition: **[`tools.ietf.org/html/rfc7228`](https://tools.ietf.org/html/rfc7228)**
* Limited processing power
* Unreliable networking
* Low power _(so they can run on batteries)_


## Internet: A definition

<br/>
<br/>

> "A computer network consisting of a worldwide network of computer networks that use the TCP/IP network protocols to facilitate data transmission and exchange."


## Several types of networks & protocols &mdash; industrial

<p style="text-align:center;">
<img src="assets/industrial-protocols-overview.jpg" alt="Industrial protocols overview" style="width: 80%"/>
</p>


## Other protocols &mdash; building management

<p style="text-align:center;">
<img src="assets/bms-protocols-overview.jpg" alt="BMS protocols overview" style="width: 70%"/>
</p>


## _Edge_ has devices &mdash; _Cloud_ has servers

<br/>

<p style="text-align:center;">
<!-- image for edge + cloud --> 
<img src="assets/edge-cloud.png" alt="Edge and cloud" style="width: 80%"/>
</p>


## Edge 

<p style="text-align:center; font-size:40px;">
devices != gateways
</p>

<br/>

* Devices talk to other **devices northbound and southbound** 
* Gateways talk to the **cloud northbound and devices southbound**
* Device to device **(D2D)**
* Device to cloud **(D2C)**

------------------