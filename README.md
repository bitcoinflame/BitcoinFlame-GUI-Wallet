# BitcoinFlame GUI Wallet

This is a fork of the **Sumokoin GUI Wallet**: https://github.com/sumoprojects/SumoGUIWallet
It is changed to be compatible with BitcoinFlame.


1. Install dependencies (with Python 2.7):

	* Generally, you can use Python `pip` to install required components:
		
			pip install PySide, requests, psutil
	
	* or
			
			pip install -r requirements.txt 
	
	* On some OSes, PySide may be required to install from pre-built packages. For example, on Ubuntu 16.04, install PySide with the following command:
			
			sudo apt install python-pyside


2. Build/download BitcoinFlame binaries from [BitcoinFlame repo](https://github.com/BitcoinFlame/BitcoinFlame) and put it to `Resources/bin` sub-directory.

3. Run the wallet (Python 2.7):
		
		cd /path/to/Wallet
		python wallet.py

