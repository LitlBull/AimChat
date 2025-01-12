# AimChat
IRC Messenger Project

Overview

AimChat is a Python-based application that allows users to securely communicate via IRC channels with encrypted messages. 
The application features user authentication, contact management, and secure message exchange. 
It is designed to connect automatically to an IRC server and simplifies user interaction with IRC protocols.

Features

User Management:

Create a new username or log in with an existing one.

Store user credentials securely with SHA-3 hashing and Fernet encryption.

IRC Connectivity:

Automatically connects to the configured IRC server.

Identifies users with NickServ and supports joining private channels.

Message Encryption:

Encrypts messages using Fernet for secure transmission.

#Contact Management:

Add and view contacts within the application.

#Installation Tarball:

Optionally, generate a tarball for easy deployment to other devices.

#Prerequisites

Python 3.6 or higher

Internet connection

IRC server access (configured for irc.oftc.net in the script)

##Dependencies

#The following Python libraries are required:

tkinter

cryptography

irc

#The application installs these dependencies automatically on startup.

#Installation

From Source

#Clone the repository:

git clone https://github.com/username/Aim_Chat.git
cd Aim_Chat

#Run the script:

python AimChat.py

#Using Tarball

#Download the Aim_Chat.tar.gz from the GitHub repository.

#Extract the tarball:

tar -xzvf Aim_Chat.tar.gz
cd Aim_Chat

#Run the script:

python AimChat.py

##Usage

#Launch the Application

#Run the script using Python:

python main.py

##Features

#Create Username / Log In:

Enter a username and password to create an account or log in with existing credentials.

#Add Contacts:

Add contacts by their username.

#Send Messages:

Select a contact and send an encrypted message.

#View Contacts:

View a list of all added contacts.

#Configuration

IRC Server: The application connects to irc.oftc.net on port 6667.

#Default Channel: The application joins the #aim423 channel. You can modify this in the connect_irc function.

Channel Password: Update the channel_password variable in the script if required by the IRC server.

#License

This project is licensed under the MIT License. See the LICENSE file for details.

#Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

#Support

For issues, please open an issue on the GitHub repository.
