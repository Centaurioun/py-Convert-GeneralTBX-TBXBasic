# py-Convert-GeneralTBX-TBXBasic
Python port of p5-Convert-GeneralTBX-TBXBasic

## Preparing your environment
### Install Python
[Python 3.9.13](https://www.python.org/downloads/release/python-3913/) was the most recent version of Python this was tested with, but it was also working in older versions of Python 3.

On Windows it's easiest to follow the link above, then download the Windows installer (probably 64 bit, unless you know you need 32 bit) - usually found at the bottom of the page. Running the installer shouldn't take very long. **When asked, be sure to check the box asking if you want to add Python to your environment variables.**

After installing you can test by opening a terminal (cmd.exe or PowerShell, it does not matter) and typing:

```sh
python --version
```

You should see a message similar to the following:

```sh
Python 3.9.13
```


### Installing dependencies
(You can do this step in a `virtualenv` if you do not want to install globally, but it is not necessary.)

Open a terminal (cmd.exe or PowerShell, it does not matter).

Change directory to the location of this repository (or the files contained therein).

```sh
cd C:\Somewhere\On\Your\Computer\py-convert-generaltbx-tbxbasic
```

Using pip (a tool that comes with Python which can be used to install libraries), run the following command using the `requirements.txt` file in this repository.

```sh
pip install -r requirements.txt
```

You should now be ready to follow the "Usage" steps.

## Usage
Python Steamroller can be run from the command line using the following command:
```sh
python main.py [PathToFileForSteamrolling]
```

If an invalid file path is given, a warning message will be printed to the console.

Output files are formatted as follows:
```sh
"[PathToFileForSteamrolling] + Steamroller + .tbx"
```

## Legal

Python TBX Steamroller is digital property of the BYU Translation and Research Group (TRG). Questions regarding TBX, dialects, and application should be directed to the TRG. Questions regarding the Steamroller source code can be directed to its creator, Gregory Knapp, at Gregory.C.Knapp@gmail.com.
