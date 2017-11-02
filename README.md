#This is a simple name changing script for photos.  Ideally, you will want to use this script when you have 
#a directory containing a ton of photos.  For example, I take A LOT of photos with my phone.  Those photos 
#almost always wind up in one of three folders on my mass storage device, and they have gotten to the point were 
#the naming convention by the phone is beginning to repeat itself.  I originally wrote a script in BASH that 
#randomly changed the filename for these photos and it worked great.  The principal is the same, I am merely 
#converting everything from BASH to Python.
#
#Please be aware, this script does NOT prepend with any relivant data; ie Date, Time, Mood Swing, etc.  It is 
#merely random numbers.  This script will prepend with 9 random numbers, along with a underscore, followed by
#the original file name.  All non image file extensions will not be altered.  This script only works with:
#
#.jpg
#.jpeg
#.JPG
#.png
#.gif
#
#However, none of this is a hard and fast rule, you can alter this script to work with any extension (such as 
#txt or tiff or whatever).
