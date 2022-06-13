# Chrome: TrueRNG via Web serial API.
Using TrueRNG in Chrome using Web Serial API.

![image](https://user-images.githubusercontent.com/1586332/173350463-565d2e9c-b947-4d4d-abdf-79a7ee4c359f.png)

There's a couple of things needed to get it working:           
Use Zadig to solve the "Access is denied" error on Windows. You need to replace the existing driver with the USB Serial (CDC) driver in Zadig.
Click "Options" and show all the devices. ENSURE you have the TrueRNG selected, you can remove the drivers for your mouse and keyboard if you're not careful!
(https://user-images.githubusercontent.com/1586332/173350524-9998f0c6-2cb5-48de-afb6-eeb97124ea07.png)

Also you can only run the code from HTTPS and after you've swapped the drivers, so it's not very "Plug and play" for any user out there from their desktop.

Online Example:
https:e/untamed.zone/TrueRNG/index.htm![settings]
