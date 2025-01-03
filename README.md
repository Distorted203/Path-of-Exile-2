
## For .exe installation:

1. Extract Files
2. Launch Application and click "Select Log File"
3. Navigate to the Client.txt file in the Path of Exile Folder

 # If you are Steam:
   - Steam --> steamapps --> common --> Path of Exile 2 --> logs --> client.txt

 # If you are using the GGG Launcher:
   - Go to where Path of Exile 2 Install folder is
   - Path of Exile 2 --> logs --> client.txt

4. Click "Select Sound File"
   - Select the provided PoE1 Alert Sound.mp3 file
   - Or you can use a custom sound of your choosing
   - Supports .mp3 or .wav files.

5. Enable.


## Notes:
- The .exe file may trigger antivirus warnings because it is unsigned. It is safe to use and the source code is available for review.
- You can hit the "x" on the top right and it will minimize to tray. You do not need to keep the application window open.
- A config file will be created upon selecting your files. This is to save your settings for future use.



## For Python (.py) file, below is the list of dependencies required:

pillow==11.1.0
pygame==2.6.1
PyQt6==6.8.0
pystray==0.19.5


## Installation

1. Download the .zip file extract it.
  
2. Navigate to directory

   cd <PoE2_Chat_Alert_Python>

3. Create and activate a virtual environment (optional but recommended):

   # Windows
 
   python -m venv .venv
   .\.venv\Scripts\activate

   # Mac/Linux
 
   python3 -m venv .venv
   source .venv/bin/activate

4. Install the required dependencies:

   pip install -r requirements.txt

5. Run the script:

   python PoE2_Chat_Alert.py