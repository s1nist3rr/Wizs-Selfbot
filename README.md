# This is a New Project which is currently still being worked on! 

Message Vexy#9999 on discord to report bugs, if you need help or if you have a suggestion

# Setup
### Setup Video will be posted soon!
- Download Python 3.8 from here: https://www.python.org/downloads/release/python-380/
- Extract .zip file onto your desktop and open install.bat
- Open config.json and fill in all information required
- Open launch.bat and enjoy!!

# Legality

Everything you can see here has been made for educational purposes and proof of concepts. I do not promote the usage of my tools, I do not take responsability on the bad usage of this tool.




##### I will not be help responsable for anything that happens to you, and your discord account.

# Q&A
- Q: **`SSL Certificate Error`**
- A: Just install [CRT File](https://crt.sh/?id=2835394). Then run it and install. (This is common and it was a certificate that expired May 30th 2020. But a new one came out so install it.). If you wanna go into further detail then head to [SITE](https://support.sectigo.com/Com_KnowledgeDetailPage?Id=kA03l00000117LT).  
- Q: **`Module Missing`**
- A: Just run `pip install -r requirements.txt` in console. This insures that all modules required for Snaxes are installed and up to date!
- Q: **`Windll not found`**
- A: Snaxes uses some windows features from modules. Example windll from ctypes. windll is used to add the console title. You can remove the title setters in-order to fix it.
- Q: **`TypeError: __new__() got an unexpected keyword argument 'deny_new'`**
- A: This error occured on an old installation of discord.py to fix simply run :`pip install -U discord.py` this updates discord.py!
