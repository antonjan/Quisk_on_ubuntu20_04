# Quisk_on_ubuntu20_04
This will have the source code of how to get Quisk working on Ubuntu 20.04 With hackrf and rtl-sdr dongle
# Required Dependency
Python3 and Pip for Python 3

sudo apt-get install python3-wxgtk4.0 ## Use this for Python3, or get the most recent version
sudo apt-get install libfftw3-dev
sudo apt-get install libasound2-dev
sudo apt-get install portaudio19-dev
sudo apt-get install libpulse-dev
sudo apt-get install python-dev
sudo apt-get install libpython2.7-dev
sudo apt-get install python3-dev
sudo apt-get install libpython3-dev
sudo apt-get install python-usb
sudo apt-get install python3-usb
sudo apt-get install python-setuptools
sudo apt-get install python3-setuptools
sudo apt-get install python-pip
sudo apt-get install python3-pip

Then run the pip commands below
  python3 -m pip install --upgrade quisk 
  sudo -H pip install --upgrade pip
  sudo -H pip install --upgrade setuptools
  sudo -H pip install --upgrade wxPython
  sudo -H pip install --upgrade pyserial
  sudo -H pip install --upgrade quisk

# Running Quisk
I had to run python3 with sudo and explisit python path to quisk for it to work.

  sudo python3 /usr/lib/python3/dist-packages/quisk/quisk.py
  
  Then setup your hackrf config in the setup page
  ![hackrf config](Quisk_audio_hackrf_4.png?raw=true "hackrf config")<br>
  Screenshot 2
  ![hackrf config](Quisk_audio_hackrf_5.png?raw=true "hackrf config")<br>
  
  The batfile is what I used to start quisk
