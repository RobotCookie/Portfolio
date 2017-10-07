Welcome To My Development Portfolio Here You Will Find All My Projects
>RobotCookie

<a name="my-projects">My Projects</a>
---
- ### [Voltage APKs](#voltage)
- ### [Wattage PC Games](#wattage)
- ### [Student Database](#sdatabase)
- ### [Code OS](#codeos)
- ### [Auto Clicker](#autoclicker)
- ### [More Coming Soon](#my-projects)
___

<a name="voltage">Voltage APKS</a>
---
[Website Link](http://www.voltage.ga)


#### Voltage APKs Is A Website To Give Out Paid2Free, 'Hacked' ,and Legit Andriod Apps

## Code Listed Here (index.html)
~~~html
<html>
<head>
<link rel="stylesheet" href="css.css">
<link rel="shortcut icon" href="voltage.png">
<title>Voltage APKs</title>
</head>
<body>
<article>
<h1><b>WELCOME TO THE FREE APK WEBSITE</h1></b>
<h1><b>IMPORTANT. PLEASE DOWNLOAD THE BELOW APP TO MAKE OUR APPLICATIONS WORK. ITS LIGHT AND DOESN'T TAKE UP MUCH STORAGE SPACE.</h1></b>
<a href="https://drive.google.com/file/d/0ByMdsW56iQiRSFpvcms5bmtLbzQ/view"><i>HERE</i></a>
<h2>We constantly update our APK’s and we even have hacked versions where you can get everything for free on the HACKED section of our website</h2>
<br>We hope you enjoy this website for Android users, by Android Users!</br>
  <center>
    <h2>Check Out Our <a href="http://www.wattage.ga">PC Website</a> for free Windows games and software!</h2>
<article>
<hr>
<a href="/"><img src="home.png" onmouseover="this.src='homem.png';" onmouseout="this.src='home.png';" /></a> <a href="normal"><img src="legit.png" onmouseover="this.src='legitm.png';" onmouseout="this.src='legit.png';" /></a> <a href="hacked"><img src="hacked.png" onmouseover="this.src='hackedm.png';" onmouseout="this.src='hacked.png';" /></a> <a href="paid2free"><img src="paid.png" onmouseover="this.src='paidm.png';" onmouseout="this.src='paid.png';" /></a>
</article>
<hr>
<img src="android-logo-89F9AA29D5-seeklogo.com.png">
  <div class="Advert">
  <h4>Sponser Custom Network Minecraft Sever</h4>
  <img src="advert.gif" >
  <h4>IP = bbfms.aternos.me</h4>
  </div class="advert">
</body>
</html>
~~~


<a name="wattage">Wattage PC Games</a>
---
[Website Link](http://www.wattage.ga)


#### Wattage PC Games Is A Website To Give Out Paid2Free PC Games

## Code Listed Here (index.html)
~~~html
<!DOCTYPE html>
<html>
<head>
  <link href="main.css" rel="stylesheet">
<title>Wattage Windows PC Games</title>
</head>
<body>
  <script>
window.addEvent('domready', function() {
    document.body.addEvent('contextmenu',function(e) {
        e.stop();
    });
});
</script>
  <center>
    <div class="menu">
      <a href="http://wattage.ga" id="home">|Home| </a>
      <a href="games" id="games">|Games| </a>
      <a href="software" id="software">|Software| </a>
      <a href="contact" id="contact">|Contact & Requests|</a>
    </div class="menu">
<h1>Wattage Windows PC Games - For Free</h1>
    <h2>Check Out Our <a href="http://voltage.ga">APK Website</a> for free android games</h2>
  </center>
</body>
</html>
~~~

<a name="sdatabase">Student Database (WIP)</a>
---
[Repo Link]()


#### This Was A HW Set To Create A Database For A Teacher To Log Students

## Code Listed Here (teacher.py)
~~~python
#Robot Coookie
#6.10.17
#Ultimate School Database

import pickle

f = open('settings.pckl', 'rb') #Tests if program is first time launch
obj = pickle.load(f)
f.close()

if obj == int(0):
    username = str(input('What Do You Want Your Username To Be? '))
    password = str(input('What Do You Want Your Password To Be? '))
    f = open('d#1.pckl', 'wb') #Saves Username
    pickle.dump(username, f)
    f.close()
    f = open('d#2.pckl', 'wb') #Saves Password
    pickle.dump(password, f)
    f.close()
    obj = obj+1
    f = open('settings.pckl', 'wb')#Sets First Time Launch To Complete
    pickle.dump(obj, f)
    f.close()
else:
        f = open('d#1.pckl', 'rb') #Loads Username
        user = pickle.load(f)
        f.close()
        f = open('d#2.pckl', 'rb') #Loads Password
        pw = pickle.load(f)
        f.close()
        u = str(input('Enter Username: '))
        if u == user: #Checks If Username Is Correct
            p = str(input('Enter Password: ')) #Checks If Password Is Correct
            if p == pw:
                import GUI.py
        else:
            print('Incorrect')
~~~

<a name="codeos">CodeOS (DIS)</a>
---
[Repo Link]()


#### This is an OpenSUSE Based OS Designed For Uninterupted Coding. **It Is Now Discontinued**

## Info Dump (.vmx file)
~~~
#!/usr/bin/env vmware
config.version = "8"
tools.syncTime = "true"
uuid.action = "create"
virtualHW.version = "9"
displayName = "Code_OS.x86_64-0.0.2"
memsize = "512"
guestOS = "suse-64"
scsi0.present = "true"
scsi0.sharedBus = "none"
scsi0.virtualDev = "lsilogic"
scsi0:0.present = "true"
scsi0:0.fileName = "Code_OS.x86_64-0.0.2.vmdk"
scsi0:0.deviceType = "scsi-hardDisk"
ethernet1.present = "true"
ethernet1.addressType = "generated"
ethernet1.virtualDev = "e1000"
ethernet1.connectionType = "bridged"
ethernet1.allow64bitVmxnet = "true"
ide0:0.present = "true"
ide0:0.deviceType = "cdrom-raw"
ide0:0.autodetect = "true"
ide0:0.startConnected = "true"
powerType.powerOn = "soft"
usb.present = "true"
powerType.powerOff = "soft"
powerType.reset = "soft"
priority.grabbed = "normal"
priority.ungrabbed = "normal"
powerType.suspend = "soft"
~~~
