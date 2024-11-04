# Black screen with the blinking underscore - VMware Virtual machine

## Description:
    I had an issue regarding my Virtual kali linux machine, everytime after my kali goes to sleep mode, it looses the GUI and I see only black screen with the blinking underscore.

## Solution that I foud:
    I pressed ctrl + alt + F2 and entered into my account:
        
        sudo apt-get update && sudo apt-get dist-upgrade -y

    after running this command, I got all updates and my GUI in kali linux returned back!