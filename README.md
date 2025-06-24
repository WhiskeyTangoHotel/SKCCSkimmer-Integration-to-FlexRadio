# SKCCSkimmer-Integration-to-FlexRadio
See source code and details at:
SKCCSkimmer Integration to FlexRadio

SKCC Skimmer program is remarkably well done.   However, we wanted a less verbose output to the screen.  
We also wanted to quickly jump to the active frequency when SKCC Skimmer identified a TARGET or GOAL we set.   
We accomplished this by "butchering" Mark K7MJG's perfectly functioning code with our hack code for the 
Flex Radio 6400.   The modified code shown below runs on an Ubuntu PC in the shack.   
When a TARGET or GOAL is found pressing the ENTER key sends commands to the FlexRadio to tune to 
the active frequency to ready for the QSO.  
