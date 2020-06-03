# TLOGIN
A simple login script for termux
 [+] Information :

   Termux is a Android emulator we can run many kali linux
   tools in termux (android) so here i have created a small 
   python script which works as a login form.means it will lock
   your termux app when ever you  open termux it will ask you to
   enter username and password.if you guys enter right 
   username and password the termux will open which means you can
   use termux otherwise if you dont enter user and pass
   this script will close your termux app. so hope you like
   that .In future i will make this script more secure/
  
   Termux-Login-v1.2 

[+] warning :- if anybody want to modify this script and want to 
    upload on your own github then you guys make sure to give my original github link on your README.md as a credit..okk(TechnicalMujeeb)

[+] install and use
  
    git clone https://github.com/TechnicalMujeeb/Termux-Login.git

    cd TLOGIN

    mv README.md log.py /$HOME

    Now you want autorun this log.py so follow this

    cd ..
    cd usr/etc/
    nano bash.bashrc
    (here type) python log.py

    press ctrl + x and then y to save.

    Now open Your Termux this script is autorun and secure termux.


