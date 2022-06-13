# Chrome: TrueRNG via Web Serial API.
Using TrueRNG in Chrome using Web Serial API.                
This little webpage (linked at the bottom of this readme) has a "Connect" button to select the TrueRNG device. Once selected the page connects to it, and starts reading the random numbers produced as an array of unsigned 8 bit values every few milliseconds.                  
Meanwhile an animation loop running at 60 FPS takes any new random values that have been created and writes them in sequence to the "Pixel display box". Once the box is filled, it cycles around again so you can see the steady in-flow of random data being read in.            
All from the comfort of your browser via plain JavaScript!                   
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
https://untamed.zone/TrueRNG/index.htm
