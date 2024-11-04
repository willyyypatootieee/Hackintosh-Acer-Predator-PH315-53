# I'm not using Hackintosh anymore, so it will no longer be maintained.
## EFI-Hackintosh-Acer-Predator-PH315-53 ( MacOS Ventura )
<h1> Highly Recommend you to build the EFI for your device on your own 
and only use this for reference even though you have the same device as mine since, when something fails you will be on your own.</h1>

This EFI was used for Mac OS Ventura, didn't test yet on Monterey, Big Sur, or Mojova. should work with older mac os versions as well but may need few tweaks.

Specification : 

- I7-10870H 8C 16T
- 32GB DDR4 2993MHz
- RTX 2060 6GB
- Intel UHD Graphics 630
- Samsung MZVLB512HBJQ-00007
- Adata SX6000NLP
- Killer Wifi Ax1650i (201NGW)

Confirmed Work:
* Apple Services ( imesssage, facetime )
* QE/CI of Intel® UHD Graphics 630
* Internal Microphone, Internal Speaker and Headphone
* Power Management
* USB Ports
* TrackPad with multi gesture
* Battery Indicator
* Restart, Sleep and Shutdown
* Webcam
* Type C port
* Battery Limit to 80% with acer care center on windows
* Brightness
* Brightness Up and Down
* Keyboard Brightness Up and Down ( not rgb, by default is blue color. but if u want to u can boot into windows and restart it. )
* WiFi + Bluetooth
* Turbo Button ( only boost both fans cpu & gpu )
* etc;
  
Not Working :
- Nvidia RTX 2060 ( optimus didnt work on mac os )
- hdmi ( connected through dedicated gpu )
- microphone through cable audio jack
- Samsung MZVLB512HBJQ-00007 ( didn't support )
- apple exclusive feature like carside, airdrop.

didn't test yet :
- mini display port
- ethernet port

  
Bug :
* if u want use HDMI on windows, u should reboot ur laptop twice.  
* if the brightness slider on lowest, the screen gonna be black, to fix this u need to
restart ur laptop
* sometimes the webcam mic kinda noisy

# Screenshot

![Screenshot 2023-09-19 at 11 20 27](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/66102c62-b375-491c-a348-fdf180f6f304)
![Screenshot 2023-09-19 at 11 15 14](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/bf1e0f48-6f6b-419f-8db9-24e34c005d27)
![Screenshot 2023-09-19 at 11 16 11](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/1d754cd5-f03a-4e69-b57a-c4e3f38b436e)
![Screenshot 2023-09-19 at 11 16 48](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/cc1e8f08-70ff-47eb-b3e3-e9e4a3ade2ca)
![Screenshot 2023-09-19 at 11 17 25](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/3acaac1e-34bb-4b3f-951e-b31ba6b62c11)
![Screenshot 2023-09-19 at 11 17 54](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/a098b1c1-ebd4-4ab3-874e-7b4bf8075946)
![Screenshot 2023-09-19 at 11 18 09](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/1a0e437a-8a1c-43e6-80cb-226dbaad3564)
![Screenshot 2023-09-19 at 11 18 42](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/2f5043e6-1742-4ae8-84a0-05d7b88d2045)
![Screenshot 2023-09-19 at 11 18 50](https://github.com/23illy/Hackintosh-Acer-Predator-PH315-53/assets/71692311/77b281db-f43a-4b54-8522-01c3db6b8a8e)
