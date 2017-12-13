# cemcnc
A robotic vacuumless cleaner with Arduino

Software scenario:

1- An Android app done with Appinventor ("vision.apk") takes the coordinates from an image as pixels, stores them at Firebase.
2- A python jupyter notebook takes the coordinates from Firebase, produces GCODE and send them back to Firebase. 
3- Vision.apk sends GCODE from Firebase to Arduino with bluetooth. 

Problem : to merge step 1 and step 2 in one Appinventor app.
