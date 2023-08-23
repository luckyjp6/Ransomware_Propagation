# Ransomware_propagation
Sending ransomware to the victim machine on another machine. The program does:
- Create a compressed virus and attach it to the ransomware worm.
- Cracks the victim machine's password by launching a dictionary attack and then replaces the original ```cat``` with infected one.
- Once the victim machine executed the infected ```cat```, the picture on the machine will be encrypted.

## Usage
- ```make```: Add executable privileges to our executables.
- ```attack_server <port>```: Open a server for ransomware worm.
- ```make run```: Launch the crack attack.
## Demo
https://user-images.githubusercontent.com/96174316/236848207-ed20a517-5ab5-440a-bf5a-c78813564319.mp4
