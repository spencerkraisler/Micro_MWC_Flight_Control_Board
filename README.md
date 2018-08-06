# Micro_MWC_Flight_Control_Board

The Micro MWC Flight Control Board is a microcontroller used in quadcopters, microdrones, etc. It has 4 built-in ESCs (motor drivers), an accelerometer, gyroscope, radio antenna, barometer, GPS, IMU, and a built-in back massager.

I'm building a microdrone as a summer project, and I want to code the controllers from the ground up for fun (I really enjoy control theory and want to learn more about it).

Although there are libraries (the best imo being the MultiWii library) that can easily set up this FC to control your microdrone, there seems to be near zero useful tutorails on how to access the various components on this board. People with little experience in microcontrollers who also want to code controllers and other things might have trouble. I sure did.

As a result, I built this repository to store some scripts I made or found online that were really helpful in understanding the Micro MWC Flight Control Board.

The code used on this board is identitcal to the code used on the Arduino. 
To flash it, open up the Arduino IDE and select 'Arduino Pro or Pro Mini' on the board. 
