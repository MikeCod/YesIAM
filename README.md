# YesIAM

## Dependencies
Upgrade your pip version :
```
python3 -m pip install --upgrade pip
```
### Windows
Install the dependencies for Windows with the command :
```
python3 -m pip install -r requirements.txt
```
Then, install YesIAM with the Windows installer.
### Linux
If you want to use cron, you can instead install the dependencies with the command :
```
python3 -m pip install -r requirements_linux.txt
```
Then, run this command to add the cron process :
```
python3 ./yesiam.py --add
```
Finally, move the file `yesiam.py` to the folder `/opt/`