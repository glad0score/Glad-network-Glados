#GLADOS - BLOCKCHAIN NETWORK

Glados is a cryptocurrency born from the blockchain of the same name, you can also call it glad.


##HOW MINE CRYPTO?

You can mine with these following data:

Tutorial - Mine for blocks with Microsoft Windows
Mine for blocks with your Windows wallet and the following instructions.

Click here to download the file glad-qt-windows.zip.

Open File Explorer and go to your downloads directory.

Extract the zip file glad-qt-windows.zip

Open "Run" with the keyboard shortcut winkey + r.

Enter the following text behind "Open": notepad

Press on the button "OK".

Paste the following into notepad:




 **
   ___rpcuser=rpc_glad
   ___rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
   ___rpcallowip=127.0.0.1
   ___listen=1
   ___server=1
   ___addnode=node1.walletbuilders.com
   **
   
   
   
   
   Click on the menu item "File" -> "Save As...".

The open dialog box will appear, click on "Save as type" and select the option "All Files (*.*)".

Enter the following text behind "File name": glad.conf

Click on the menu bar, type the following text %appdata% and press on the enter key. enter

Create the folder Glad and open the folder.

Press on the button "Save".

Create a new file with the keyboard shortcut ctrl + n.

Paste the following into notepad:




**
___@echo off
___set SCRIPT_PATH=%cd%
___cd %SCRIPT_PATH%
___echo Press [CTRL+C] to stop mining.
___:begin
___glad-cli.exe generate 1
___goto begin
**



Next going to wallet>setup>options>network , proxy :127.0.0.1 : port: 23599 




