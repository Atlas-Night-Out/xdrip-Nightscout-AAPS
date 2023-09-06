<!-- this is  on github server!
docs made by D.Galloway 2019- 2021-->

# Bolus on Ticwatch Pro 5 Watch from AAPS Watch faces

Diabetes !102 Years 1921 - 2023

## Summary
To be able to bolus from your watch, you are first going to have installed xdrip+ and have it setup and working on your Phone. You will also have to make your own WearOS.APK file and installed that onto your watch by sideloading it. You do this at your own risk. There is no warrenty on this  I have made a video showing how to do this and I will also  add a document to help you setup when I get time too! So stay tuned! (Grammer corrected by Berni Warren Thank you!)

## Step 1 What you will already needed to have done before you go any further! 

1. You will need to installed xdrip+ onto your Phone and working, so its getting reading from your CGM. See <br>
[Install xdrip±](../xdrip/xdrip%20-%20install.md#install-xdrip_1) <br>

2. Important notes Please use Android Studio Version 2020.3.1 or newer to build the apk.
Windows 10 32-bit systems are not supported by Android Studio 2020.3.1 <br>

Make your own copy of AAPS_3.1.0.3.APK file in Android Studio. And then have it AAPS 3.1.0.3.APk file installed onto your Phone and working with xdrip+,  then within the ConfigBuilder you need to enable the Wear plugin. <br>
<img width="400" height="auto" border="0" align="center"  src="/my-project/img/AAPS/Android_3.1.0.5 App Main.jpg" title="Android_3.1.0.5 APP.Main"/> <Br><br>

You can copy the code from Github into Android Studio from <a href=" https://github.com/nightscout/AndroidAPS" target="_blank" title="Git Hub Repository">AAPS</a> https://github.com/nightscout/AndroidAPS  to make your own AAPS.APK file to install onto your phone.<br>

You can see my video on how to do this process from https://youtu.be/VwG-rOolBDM  but you will need to choose Android_3.1.0.5 APP.Main instead of wear when Generate a signed Bundle! For the Software version, later you will make a wear.APK file for your watch Faces.<br>

<img width="300" height="auto" border="0" align="center"  src="/my-project/img/AAPS/config_wear settings.jpg" title="Config Builder - Wear"/> <img width="300" height="auto" border="0" align="center"  src="/my-project/img/AAPS/Config Builder wear wear settings.jpg" title="Config Builder - Wear - Wear Setting"/> <br>

3. Settings added into xdrip+ for you to get readings onto your watch.<br>

4. Make your own WearOs APK file and transfered to your Android Mobile Device.(will add instruction later on this)<br>

5. Your APK file you have just created In Android Studio will need to be sideloaded onto your Watch. You will also need to install xdrip+ onto your watch with sideloading it too, with Wear Installer  2 for both of them ( By Malcolm Bryant) <br>


## *Step 2 Instructions*
1. First  double Click on BG Readings icon on which ever Watch Face you are using for AASP. There are a few to choose from. <br>
## Watchfaces available <br>
<img width="300" height="auto" border="0" align="center"  src="/my-project/img/AAPS/AAPS(v2).png" title="AAPS(v2)"/>    <img width="300" height="auto" border="0" align="center"  src="/my-project/img/AAPS/AAPS (Digital Style).png" title="AAPS (Digital Style)"/><br>
<br>AAPS(v2)  AAPS (Digital Style)

<img width="300" height="auto" border="0" align="center"  src="/my-project/img/AAPS/AAPS (Large).png" title="AAPS (Large)"/>AAPS (Large)

<img width="400" height="auto" border="0" align="center"  src="/my-project/img/AAPS/Double Click readings icon icon.jpg" title="(BG) Blood Readings Icon"/><br>

