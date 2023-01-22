# WORKSHOP CYBERSECURITY, FOCUS ON SOCIAL ENGINEERING

## LIST OF THE TOOLS NEEDED AND HOW TO INSTALL THEM

Before going on, please run :

    sudo apt upgrade
    sudo apt update

### MSFVENOM & MSFCONSOLE
    sudo apt install metasploit-framework

### SET
    sudo apt install set

### MR.HOLMES (optional)
    git clone https://github.com/Lucksi/Mr.Holmes.git
    cd Mr.Holmes
    chmod +x install.sh
    ./install.sh

During the installation phase, the program will ask you few informations.
For the WHO-IS-XLMAPI-KEY, PROXY LIST and other technical stuff about the DATABASE you can say no or let the fields empty, except if you want to keep the tool after using it.

To check if the programs are correctly installed please try :
    msfvenom -h
    msfconsole -h
    setoolkit, then ctrl+C
    sudo python3 MrHolmes.py (in your Mr.Holmes directory), then crtl+C
