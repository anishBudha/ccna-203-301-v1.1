- need to connect to through the console port, using an RJ 45 adapter.
- using rollover cable.
- once connected through the cable, use a terminal emulator like putty with the default settings.
- speed or baud rate 9600 bits per second.
- data bits 8 bits and stop bits 1 bit.
- Parity (to know errors) to none and flow control to none.
- user mode or user EXEC mode.
- `enable` to go to privileged exec mode.
- `en` is the short for enable.
- `configure terminal` or `conf t` to go to global configuration mode.
- to enable password to the use `enable password yourpassword`
- if failed three times with wrong password, user will be denied.
- `password?` gives you possible commands and `password ?` gives you options followed by the command.
	- `service password-encryption` inside `conf t` encrypt the password.
	- current passwords and future passwords will be encrypted.
- `enable secret yourpassword` to use more hard encryption to the password.
- `do show run` to run command in lower privilege or mode.
- `exit` to exit the mode you are in.
- `running-config` is stored in RAM and used in the running session.
- `startup-config` is stored in persistent memory and used when the device boots up.
- `show running config` example of `show` command.
- `copy running-config startup-config`
- `hostname yourprefferedname` to rename the device. 
#### Quiz
1. a, Rollover cable
2. c, Caps Lock is on
3. a, enable secret command
4. c, You must enter the enable secret only
5. b, configure terminal
#### Lab
1. `enable` or `en`
2. `exit` 
3. `hostname R1 `
4. `configure terminal` or `conf t`
5. `do show` or `show`
6. `enable password CCNA`
7. `service password-encyrption`
8. `enable secret Cisco`
9. `copy running-config startup-config`