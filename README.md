# cbpi-GoogleSheets
## Introduction
CraftBeerPi plugin to upload sensor and actor data to Google Spreadsheet. Will make a new sheet for each "Brew Name"

## Required packages to install:
- `sudo apt-get install python` Installing python3 (if not available, e.g. in Raspian Lite)
- `sudo apt-get install python-pip` Installing pip (if not available)
- `sudo pip install gspread` Google Spreadsheets Python API "https://pypi.org/project/gspread/"
- `sudo pip install PyDrive` Wrapper library of google-api-python-client "https://pypi.org/project/PyDrive/"

## Usage
1. Install repo packages listed above
2. Install plugin via the Plugins section in Craftbeerpi (hopefully done)
3. Update the parameters listed below with required values
- **GSheet_Ferm_Address** is your google spreadsheet address for your fermentation. E.g "https://docs.google.com/spreadsheets/d/1ZAj40B5GVSwPAkJa2ST34etrhrtnfgndhDQ44vRA5bt-OU/edit#"
- **GSheet_Auth** is a Wordpress username to post data as  (must be an author)
- **Wordpress_Password** is your wordpress password
- **Wordpress_Tag** is a tag which is appended to each post from CraftBeerPi
- **Wordpress_Category** is a category which is appended to each post from CraftBeerPi
4. Restart CraftBeerPi & have a beer :)

## Credits
- Marcel https://github.com/suterma/WeatherPress
- Atle https://github.com/aravndal/ThingSpeak
