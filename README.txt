Name: EXIF Forensics

Description: The user is presented with a JPEG image of a blackbox. Their objective is to find the city of where the
image was taken using forensic tools. Once found, the user will then enter the location and the flag will be generated.

Solution: Using an EXIF tool (ie exiftool), view the EXIF metadata of the image. While viewing, you will notice a user comment that has a Timestamp and GPS coordinates
followed by a message from The Penguin. Upon entering the coordinates that were given on a map, you will see that these take you to a location in the middle of the Arctic Ocean.
This is obviously not the right location since there is no city here. Upon further observation, you see the time zone is KGT (Kyrgyzstan Time). Now that we know the timezone, we can now 
narrow down where the city has to be. Our first guess would be in Kyrgyzstan. Upon looking at a map we will see the GPS coordinates of several cities. Just by looking at these coordinates,
we will see that they are somewhat similar to the ones given in the message but they are in reverse order! (Silly Beta software...) Now if we enter the coordinates in reverse, we wil see that
the city at these coordinates is Kyzyl-Kiya, which is our key!


Key: Kyzyl-Kiya