## Salesforce Wear Pack for Samsung Gear 2

<p align='center'>

  <img src="https://raw.githubusercontent.com/developerforce/WearablePack-SamsungGear2/master/images/samsung-watch-and-phone-3.png?token=626337__eyJzY29wZSI6IlJhd0Jsb2I6ZGV2ZWxvcGVyZm9yY2UvV2VhcmFibGVQYWNrLVNhbXN1bmdHZWFyMi9tYXN0ZXIvaW1hZ2VzL3NhbXN1bmctd2F0Y2gtYW5kLXBob25lLTMucG5nIiwiZXhwaXJlcyI6MTQwMjcwNzU3Mn0%3D--76b8409ae656dac6b71a00427177960c1c1fb7c4" />    

    
</p>

This Salesforce Wear Pack is for <a href="http://developer.samsung.com/samsung-gear" target="_blank"> Samsung Gear 2</a> Wearable and includes an architecture overview article along with a sample application to get you started building applications which integrate Salesforce with Samsung Gear 2.


Samsung Gear <a href="http://www.samsung.com/global/microsite/gear/gear2_design.html" target="_blank">wearables</a> like Gear 2, Gear 2 neo, etc., all need a 'host' android app through which they communicate with the external World. 

<p>Because of the way Samsung Gear 2 works, you will be building two apps: 

<ol>
<li>An Android App that talks to Salesforce and authenticates user. </li>
<li>A Tizen <b>web</b> app that communicates with the android app and displays info on the watch.</li>
</ol>
</p>
   

<p align="center">

  <img src="https://raw.githubusercontent.com/developerforce/WearablePack-SamsungGear2/master/images/high-level-architecture.png?token=626337__eyJzY29wZSI6IlJhd0Jsb2I6ZGV2ZWxvcGVyZm9yY2UvV2VhcmFibGVQYWNrLVNhbXN1bmdHZWFyMi9tYXN0ZXIvaW1hZ2VzL2hpZ2gtbGV2ZWwtYXJjaGl0ZWN0dXJlLnBuZyIsImV4cGlyZXMiOjE0MDI3MDc5OTd9--3c7597a4a523059428f1b7478b0dddf0358e59cc"/>  
  </img>
</p>

####Compatibility
One caveat is that these android apps must be running in a compitable Samsung phones or tablets and won't work on devices from other manufacturers like Google or LG. See the list of compatible devices <a href="http://www.samsung.com/global/microsite/gear/gear2_features.html" target="_blank">here</a> (scroll down to the bottom).

##Tizen OS
<p align='center'>
<a href="http://tizen.org" target="_blank"> 
  <img src="https://raw.githubusercontent.com/developerforce/WearablePack-SamsungGear2/master/images/tizen-logo.png?token=626337__eyJzY29wZSI6IlJhd0Jsb2I6ZGV2ZWxvcGVyZm9yY2UvV2VhcmFibGVQYWNrLVNhbXN1bmdHZWFyMi9tYXN0ZXIvaW1hZ2VzL3RpemVuLWxvZ28ucG5nIiwiZXhwaXJlcyI6MTQwMjY5OTUwMH0%3D--07da3d5e3a69067179645a9dd66eaa3d3c1d44dc" height="150px"/>  
  </img>
  </a>
  </p>
Samsung Gear 2 watch itself doesn't run Android Operating System. Instead it runs on Samsung's open-source <a href="http://tizen.org" target="_blank">Tizen OS</a> that's built in C++. Tizen OS allows people to build apps in either HTML5 or C++ (native). However Samsung Gear 2 only allows us to build HTML5 apps.

<h2>Getting Started</h2>



###Today Example App
 To help you get started this repo comes with a [sample](https://github.com/developerforce/WearablePack-SamsungGear2/tree/master/samples/TodayApp) app called "TodayApp". It has a simple android app that does authentication and sends Salesforce user's "Today's meetings" to the watch from Salesforce Calendar. 

  <img src="https://raw.githubusercontent.com/developerforce/WearablePack-SamsungGear2/master/images/tizen-gif2.gif?token=626337__eyJzY29wZSI6IlJhd0Jsb2I6ZGV2ZWxvcGVyZm9yY2UvV2VhcmFibGVQYWNrLVNhbXN1bmdHZWFyMi9tYXN0ZXIvaW1hZ2VzL3RpemVuLWdpZjIuZ2lmIiwiZXhwaXJlcyI6MTQwMjcwMTMwMn0%3D--a6836c43ba95027eb793aaf8cccf7f5e263c39a4"/>  
  </img>



To get started, go through the instructions on the readme inside the [TodayApp sample](https://github.com/developerforce/WearablePack-SamsungGear2/tree/master/samples/TodayApp).


