# Chrome: TrueRNG via Web Serial API.
Using TrueRNG in Chrome using Web Serial API.                
https://developer.mozilla.org/en-US/docs/Web/API/Web_Serial_API                      
![image](https://user-images.githubusercontent.com/1586332/173351307-cce7d198-f512-478a-8990-a72b4c13a745.png)


![image](https://user-images.githubusercontent.com/1586332/173350463-565d2e9c-b947-4d4d-abdf-79a7ee4c359f.png)

There's a couple of things needed to get it working:           
Use Zadig to solve the "Access is denied" error on Windows. You need to replace the existing driver with the USB Serial (CDC) driver in Zadig.
Click "Options" and show all the devices.         
**ENSURE** you have the TrueRNG selected, as you can accidently remove the drivers for your mouse and keyboard if you're not careful!
![image](https://user-images.githubusercontent.com/1586332/173350849-04c52fa1-8e71-4b0e-9191-4bf78e325522.png)


Also you can only run the code from HTTPS and after you've swapped the drivers, so it's not very "Plug and play" for any user out there from their desktop.

Online Example:
https:e/untamed.zone/TrueRNG/index.htm![settings]
