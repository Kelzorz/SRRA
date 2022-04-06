
## SRRA
___
A personal project to display 1v1 ladder statistics that are not typically displayed in Starcraft: Remastered.

### Features
---
- Ladder match history and match statistics (APM/EAPM)
- Personal competitive ladder statistics such as:
  - Overall ladder win ratio
  - Win ratio per match ups 
  - Average actions per minute
  - Average effective actions per minute
- APM graph (apm per ladder game)

### Requirements
---
You need icza's screp replay parser to use this program.

You can find it here https://github.com/icza/screp.
### Configuration
---
Set up a file `config.ini` with:
- The path to screp
- The path to your autosave folder
- Your ladder usernames
```
[PATHS]
PATH = C:\Users\<YourUserName>\Documents\StarCraft\Maps\Replays\AutoSave\screp.exe
AUTOSAVE_LOCATION = C:\Users\<YourUserName>\Documents\StarCraft\Maps\Replays\AutoSave

[USERNAMES]
YOUR_LADDER_NAMES = ["guy_in_the_chat", "guy_in_the_chat2"]
```

### Demonstration
---
[Video](https://drive.google.com/file/d/1pUE9jZYeYYBwP7FSofkpvysc0jAkOZHg/view?usp=sharing).


### Limitations
---
This project is desgined to work only for 1v1 ladder matches.
This is due to the fact that personal ladder match statistics are missing from Starcraft: Remastered.
Some statistics exist but are poorly implemented.