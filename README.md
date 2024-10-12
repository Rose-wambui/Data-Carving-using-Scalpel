# Data-Carving-using-Scalpel
Scalpel is a file carving and indexing application that runs on Linux and Windows

# How to install 
Note: Am using kali linux for this

sudo apt install scalpel

# Editing Scalpel
After installing scalpel,we will need to edit the conf file since everything is commeneted out.

This will help us in file recovering

By default, scalpel is installed in the "/etc" directory.

Navigate to that directory in your kali machine.

The full path for scalpel will either be:

1. /etc/scalpel/scalpel.conf   or 
2. /etc/scalpel.conf

check yours to see what is the full path of scalpel.

Mine is located in this location
![image](https://github.com/user-attachments/assets/94f4843a-2202-4b8b-8b19-13829c857bc1)

We will navigate to that directory and edit the scalpel file using any text editor of your choice.

My end i will use nano. Not for particularly any reason just that i love it.
command ##sudo nano scalpel.conf 

As you can see everything is commeneted, so we will need to uncomment the file formats that we want.
![image](https://github.com/user-attachments/assets/fb300a37-ff38-4e1b-a407-fc2bbc6acfca)

Here i have uncommented everything i wanted.
![image](https://github.com/user-attachments/assets/2f6a0431-ddab-44e3-98a2-d8a45445979b)

After uncommenting, save and exit!!!.

# Data Recovery Using Scalpel
Scalpel is quite a powerful tool that can help us in recovering deleted files.

This is the command i used to recover files from that drive.
sudo scalpel /dev/sda4 -b -o ~/Desktop/scalpel_recovered_files/
![image](https://github.com/user-attachments/assets/0417b2dc-2f30-4b1a-8182-a27dc3643f15)

Afer navigating to the directory where i stored my recovered files, you can see them here.
![image](https://github.com/user-attachments/assets/77b25913-244e-4f33-95fb-c03781ead591)

From that we recovered the following files:
![image](https://github.com/user-attachments/assets/7bdab5a1-f4d9-4096-8e64-5a4b224ddc65)


I Ran the command against other disk in my system and recoverd some pdf.
![image](https://github.com/user-attachments/assets/0f3843c1-41cd-4654-b300-dcbc8701e8c7)



   
