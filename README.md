# WebChat

This is an installer script for the awesome work by Craig, KM6LYW. This script will
install his WebChat service and give you an easy to use CLI interface.

Craig's work can be found on [Github](https://github.com/craigerl/aprsd)

WebChat allows you to send messages using the APRS protocol from any web browser.

# Install
Open your terminal and paste the following line
	git clone https://github.com/km4ack/webchat.git $HOME/webchat && bash $HOME/webchat/install
The install script will install custom config files for WebChat that supports Direwolf & the Mobilinkd
TNC. It will also walk you through configuring WebChat with your call sign and location. This install
script will only configure the WebChat plugin for APRSD. It will configure WebChat for **RF only**. While 
APRSD can be configured to run over aprs.is and other plugins, that is beyond the scope of this script.

# Supported Platforms
This script has been tested on Linux Mint 21.1 and a Pi 4 4GB model running Pi OS 64bit. **Note:** Installation on a Pi will take
a while and may seem stuck at some points. Patience will be needed.

# Help
See [help.txt](https://github.com/km4ack/webchat/blob/main/help.txt)