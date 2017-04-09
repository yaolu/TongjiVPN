# TongjiVPN
Script for running juniper vpn in command line. This script requires sudo privilege for creating tunnel


## Usage
Replace username and host address with your own in the vpn.sh script
Then run the following command

```bash
bash vpn.sh
```

or
```bash
sudo python juniper-vpn.py --host VPN_Server
                           --username YOUR_USER_NAME 
                           --stdin DSID=%DSID% openconnect 
                           --juniper %HOST% 
                           --cookie-on-stdin
```

## Dependency
- Openconnect

   For the installation of the latest version, try the following code if your system is Ubuntu or debian based system
   ```bash
   sudo add-apt-repository ppa:openconnect/daily
   sudo apt-get update
   sudo apt-get install openconnect
   ```
