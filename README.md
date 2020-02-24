# DexcomTasker
Tasker script to read glucose value from dexcom g6 app on android and sending to an watch via watchmaker

## Requirements
* [Tasker](https://tasker.joaoapps.com/) - Automation for Android
* [Tasker Plugin AutoNotification](https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification) - Plugin to handle notifications
* [WatchMaker](https://getwatchmaker.com/) - Create Watchfaces for different type of watches

## Configure Tasker
You an configure your tasker by yourself or import the xml file.

### Create an Profile
First create an new profile by select time
![select time](https://github.com/mx11de/DexcomTasker/blob/master/Screenshot_20200224-151606_Tasker.jpg)
and than an interval of 5 minutes for the hole day.
![select interval](https://github.com/mx11de/DexcomTasker/blob/master/Screenshot_20200224-151630_Tasker.jpg)

### Create an Task
Second create a new task an name it...
![name it](https://github.com/mx11de/DexcomTasker/blob/master/Screenshot_20200224-151706_Tasker.jpg)

![task part 1](https://github.com/mx11de/DexcomTasker/blob/master/Screenshot_20200224-151713_Tasker.jpg)
![task part 2](https://github.com/mx11de/DexcomTasker/blob/master/Screenshot_20200224-151722_Tasker.jpg)

You can use the [dexcom.xml](https://github.com/mx11de/DexcomTasker/blob/master/dexcom.xml) for an import.

## Watchmaker
Use your favorite watchface an add the variables
* {tglucose]
* {tdelta}
* {tbgtime}

or use my [watchface](https://getwatchmaker.com/watch/sBJsJUDb48)
