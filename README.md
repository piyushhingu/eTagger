# eTagger
Watch Out for Energy Patterns! Towards TaggingEnergy Energy-Sensitive GitHub Issues
# Description
eTagger is a Chrome extension that labels GitHub issues from Android project repositories with the associated energy patterns. More information about the energy patterns used can be found here. (https://tqrg.github.io/energy-patterns/#/)

# System Requirements
Have [Python 3.x](https://www.python.org/downloads/) installed in your system.

Steps to run
1. Clone the repository using ```git clone https://github.com/piyushhingu/eTagger.git```
2. Navigate to the **backend** folder and run ```pip3 install requirements.txt```
3. To start the server, use the command ```python backend.py```
4. Load the extension** directory in devloper mode. [Instructions for loading](https://developer.chrome.com/docs/extensions/mv3/getstarted/).

# Usage
1. Navigate to the GitHub repository of an Android project. Ex: [iNPUTmice/Conversations](https://github.com/iNPUTmice/Conversations)
2. Navigate to the [issues](https://github.com/iNPUTmice/Conversations/issues) tab to see the issues labeled with energy patterns. 

Important Links
1. [Demonstration Video](https://www.youtube.com/watch?v=hP4pWJ4AKxE)
2. [Tool Website](https://github.com/piyushhingu/eTagger.git)

# update
1. We have assigned a color to each tag based on how it interacts with the energy pattern.
2. we extand eTagger to stackoverfolw to whtch out the energy pattern in the stackoverflow query.
3. We test a number of different sentence transformer models, and whichever ones produce the best results we choose those models 
   for embedding. 
