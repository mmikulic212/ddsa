# DCS Dedicated Server Automation
Small AutoIT app to control DCS Dedicated server automatically including updates. 
User can setup restart intervals and use webhooks to notify Discord server about status of DCS server.

## Install
Just copy exe file anywhere in your computer

## Usage

Define DCS Base dir path in "Settings -> DCS Path"
Define Restart interval in "Settings -> Restart Interval"
You can autorun DCS when application is started

App buttons are self explanatory.

- Button "Update and Start DCS" - App will start DCS_updater.exe
- Button "Kill DCS" - App will kill DCS application

## Example
![alt Example image](ddsa_example.png)

## Settings
Settings are pernamently saved in dcsdsa.ini in <Documents> folder.

## TODO (sometime)
- automatic update confirmation
- webhooks
