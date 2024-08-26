# OSINT CHALLENGE
## TRYHACKME CTF ROOM
*https://tryhackme.com/r/room/ohsint*

### Description
What information can you possible get with just one image file?
- Download the image and find hidden clues to follow the trail

### Walkthrough
- Open Kali Linux machine, navigate to THM and download the image file.
![image to reveal](windows.png)

- We will need to use the exiftool tool to reveal some metadata. Open a terminal and use the command **exiftool /home/kali/Downloads/windows.jpg**

- The returned results in the terminal are very useful. We can the image is copyrighted to *OWoodflint*.
![metadata](metadata.png)

- This is our first clue, we now need to use some online searching techniques to find some more information about OWoodflint. 

- By doing a search of the name, we are returned 2 web links that are directly linked...

*Twitter*
![Twitter account](twitter.png)
   -
