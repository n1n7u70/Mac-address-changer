# Mac-address-changer
`Mac-address-changer` a simple bash script to change the mac address of your linux system. it will change the mac address of your linux system to a randomly every time you run the script. so 
you can use it to change your mac address to a random valid one every time you connect to a new network.
## Install
`Mac-address-changer` requires `macchanger` to be installed on your system. You can install it using the following command:
```bash
sudo apt install macchanger
```
## Usage

`Clone` the repository.

```bash
git clone https://github.com/n1n7u70/Mac-address-changer.git
```
`cd` into the directory `Mac-address-changer`.
```bash

cd Mac-address-changer
```
give permission to the file `mac.sh`.
```bash
chmod +x mac.sh
```
Run the file `mac.sh`.
```bash
./mac.sh
```
## Note
`mac.sh` is configured for ethernet devices `eth0`.
if you want to change the mac address of wlan0 you need to change the ``eth0`` to ``wlan0`` in ``mac.sh``

**Show some ❤️ and star the repo to support the project**
