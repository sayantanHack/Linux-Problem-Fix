# Grub Rescue

### The grub rescue is sometimes makes us in very trouble.There have a sollution to it. Follow the steps bellow:

Step 1: ls {for checking the drives partitions}

Step 2: ls (hd0,msdos1) {selecting the proper root partition}

Step 3: It will show the file partition type 

Step 4: set {for checking the default boot settings}

Step 5: set root=(hd0,msdos1) {selecting the proper partition for root settings}

Step 6: set prefix=(hd0,msdos1)/root/grub

Step 7: insmod normal

Step 8: Normal
