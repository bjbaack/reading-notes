# Autor: Bradley Baack
## Description: Lab06 reading notes
###
1) What is an ISO File?
  - 
ChatGPT
An ISO file is a digital copy of the contents of a CD, DVD, or Blu-ray disc, encapsulating everything from the data to the file system structure. It's commonly used for distributing software, operating system installations, and backing up physical media.
2) How do you write an ISO file to a CD, DVD, or removable media (like a thumb drive)?
  - Use the Disk Utility. Open Disk Utility, go to "File" > "Open Disk Image" to mount the ISO, then click "Burn" after inserting a blank disc into your drive.
    for a dd comand - dd if=path/to/your.iso of=/dev/sdx bs=4M
3) How do you create an ISO file?
  - you can either burn it to a cd or you can just transfer it to a thumb drive or have it written on the disc via an ap. 
4) How do you mount an ISO file?
Mounting an ISO file is usually as simple as opening the file with something called a "disc emulator" and then choosing a drive letter that the ISO file should represent. Even though this drive letter is a virtual drive, Windows sees it as a real one, and you can use it as such, too.
## Things I want to know more about
n/a


###
Sources
https://www.lifewire.com/iso-file-2625923
