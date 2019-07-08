# Codechef-Solutions-Downloader
Script to download your Codechef solutions locally on your PC.

##Please ensure that you are logged out from Codechef and have 0 existing sessions before running this script.
 
### Requirements
Platform: Linux
Python version >=3.6.5

### Installation

Build from Source:
```sh
$ git clone https://github.com/reachanihere/Codechef-Solutions-Downloader
$ cd Codechef_Solutions_Downloader
$ pip install -r requirements.txt
$ cp conf_example.py conf.py
```
Edit conf.py with your credentials.

To run:
```sh
$ python3 codechef.py
```

Note: Only your latest submission is downloaded for every completely and partially solved problem.
