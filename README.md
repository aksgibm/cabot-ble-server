# CaBot BLE Server

BLE server to monitor/control [CaBot](https://github.com/cmu-cabot/cabot)

# Install

```
echo "CABOT_NAME=gt1" > .env
echo "CABOT_START_AT_LAUNCH=1" >> .env
sudo ./install.sh
```

# Uninstall

```
sudo ./uninstall.sh
```


# Environment Variables
```
CABOT_NAME                  # cabot name
CABOT_BLE_ADAPTOR           # default is 'hci0'
CABOT_START_AT_LAUNCH       # default is 0, launch cabot system if 1 at start up
```
