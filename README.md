# FGOApp-Release

Public repo for FGOApp releases.  I had to make private because of bots.  
This is an app that seeks to streamline FGO damage and refund calculations.

## Usage
This app is designed to be easy to understand.  
Some things to note:
* Non conditional passive skills effects have been taken into account during calculations.  
This mean the quick buff from passives like "Riding B" has already been taken into account for units with quick NPs.  
* This means conditional passive skills like "Ultimate One" from Arcueid will not be accounted for.
* The latest strengthens have been applied for each server.
* Effects from NPs are not accounted for.
* Swiping to and from tabs automatically updates values in there if they are changed.
* If there are no buffs for a buff slot, leave it empty.
* Buff slots where two icons are present and a (-) means negative values are allowed.

## Credits
All data and values are obtained from AtlasAcademy.  
Without them, this project would not be possible.
I take no credit for any values present in the app but all software is written by me.
Special thanks to [@Andell](https://github.com/Andell4301) for his feedback and help.

### Open source
I will make this project open source once I am confident that the code is robust enough.
