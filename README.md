# Data-Carving-using-Scalpel
Scalpel is a file carving and indexing application that runs on Linux and Windows

# How to install 
Note: Am using kali linux for this

sudo apt install scalpel

# Editing Scalpel
After install scalpel,we will need to edit he conf file since everything is commeneted out.

This will help us in file recovering

By default, scalpel is installed in the "/etc" directory.

Navigate to that directory in your kali machine.

The full path for scalpel will either be:

1. /etc/scalpel/scalpel.conf   or 
2. /etc/scalpel.conf

check yours to see what is the full path of scalpel.

We will navigate to that directory and edit the scalpel file using any text editor of your choice.

My end i will nano. Not for particularly any reason just that i love it.

As you can see everything is commeneted, so we will need to uncomment the file formats that we want.

After uncommenting, save and exit!!!.

# Data Recovery Using Scalpel
Scalpel is quite a powerful tool that can help us in recovering deleted files.

sudo scalpel "/path/to/target/directory"



   
