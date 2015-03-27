# HelpGen4Android
Original design doc:https://docs.google.com/document/d/19-aWqSz1EyZfOj5J2f3KFOwYuK2JRJLWmbsz5uXisVE
1.Purpose
This software is trying to help android App developers to automatically generate wiki based help pages in their apps.

2.Prerequisite
BeatifulSoup library 4.2.0 is required
Your wiki must be mediawiki powered

3.Manual:
1. Make sure your mediawiki site has a template page like this:
     https://www.timecat.info/wiki/index.php/TimeCat:Doc:Help

2. Change the parameters in 'config.py' and run this script to generate the new configuration file
     You could modify outputDir to specify where you want help files to be downloaded
     You could also modify templateURL

3. run the HelpGen.py script to get the result

Issues:
1. Right now, the tool only works with Mediawiki beacause our parsing is specialized designed for mediawiki


