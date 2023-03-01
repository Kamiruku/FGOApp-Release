# FGOApp-Release

This is the public repository containing releases for "FGOApp". This is an Android application that is designed to calculate servant's NP damage and refund. Support for card calculations is currently being worked on.

## Usage
* All buff values are in percentages.
* Passive skill effects have already been taken into account for during calculations.   
This mean the quick buff from passives like "Riding B" has already been taken into account for units with quick NPs.  
However, conditional passive skills like "Ultimate One" from Arcueid will not be accounted for.
* The latest strengthens for servant NP's for each server are applied during calculations. 
* Any effects from NPs are not accounted for. This is because these buffs can be nullified and can be conditional.
* Swiping to and from tabs automatically updates values in there if they are changed.
* SE mod buff works as a percentage value of 100%. For example, Gilgamesh has a 150% SE mod against servants. This means he does 50% more damage towards servants - not 150% more. For the calculator, input 150% instead of 50%.
* Buff slots where two icons are present and a (-) means negative values are allowed.

## Credits
All data and assets are obtained from AtlasAcademy.  
Without them, this project would not be possible.
I take no credit for any assets or data present in the app.  
Special thanks to [@Andell](https://github.com/Andell4301) for his feedback and help.

### Open source
I will make this project open source once I am confident that the code is robust enough.
