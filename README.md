# LabBook-wiki-

In this repository you can read the Wiki for EEG lab guidelines and common admin tasks, such as connecting to the grid, to office computer from home, etc. 

# Using the EEG lab

Everyone accessing the EEG lab (241) should follow the guidelines in this document [EEG_lab_guidelines.doc](https://github.com/PhiliastidesLab/LabBook-wiki-/blob/main/eegLab241_guidelines.docx)  

# One Drive setup and Map Driver
How to allow OneDrive as a disk on your office computer. Download OneDrive and install. Sometimes (after an update) the icon will be in the start menu but the app won't open. This may solve it:
https://www.winhelponline.com/blog/onedrive-launch-nothing-happens-disablefilesyncngsc/

How to add a folder with your project (from the grid) on your computer - [here](https://github.com/PhiliastidesLab/LabBook-wiki-/blob/main/Map_drive1.png).

# _The Grid for faster analysis_
How to connect to the grid, choose a node, and use matlab - [here](https://raw.githubusercontent.com/PhiliastidesLab/LabBook-wiki-/main/gird_connect1.png).
Read more about the grid [here](https://support.psy.gla.ac.uk/index.php/inst/grid).

🔶 Running LDA on the grid allows to run multiple Matlab sessions at the same time. This is useful, when for example you'd like to reduce the time to run multiple participants. 
* Go to the grid (via TightVNC on Windows or RealVNC on a Mac). 
* Open a terminal and type `ssh compute-1-20`. In this example the node number is 1-20. Activity of nodes can bee seen [here](http://ccn00.psy.gla.ac.uk/ganglia/).
* Then in the same terminal type `matlab &`. This will open a Matlab window. 

# _while on the grid you can run multiple matlab files (and scripts) at the same time!_
* To open another Matlab, type `matlab &` in the same terminal (to run on the same node), or open a new terminal and repeat the above steps entering a new node number (e.g. ssh compute-1-21).


# _EEG info_

EEG preprocessing and analysis pipelines 

For detailed EEG recording information Glasow Uni library has an electronic version of: Luck, S. (2014). An introduction to the event-related potential technique. Chapter 5.Basic Principles of ERP Recording. MIT press.

Info on EEG cap with 64 electrodes with electrode potision and numbers 

## EEG cap 64. Brain vision [cap file.pdf](https://github.com/PhiliastidesLab/LabBook-wiki-/blob/main/BC-64-X28_Philiastides.pdf)  

## Cap usage [log](https://docs.google.com/spreadsheets/d/1uSCQBgyfLt5m5uFhFGr-5tHs48YUQIHV/edit?usp=sharing&ouid=107561805852058488076&rtpof=true&sd=true)

## Convert EEG to BIDS format: https://github.com/sccn/bids-matlab-tools.git

# BlackBox Toolikt
This toolkit is available in the EEG/MEG labs to test the timings of the stimulation and EEG triggers. 
This document contains brief instructions to help with setting up the BlackBox Toolkit, as we often find ourselves having to relearn the process each time [Instructions for BlackBox Toolkit.docx](https://github.com/PhiliastidesLab/LabBook-wiki-/blob/main/Instructions%20for%20BlackBox%20Toolkit.docx)  
While is still recommended checking the full manual (full manual here https://www.blackboxtoolkit.com/docs/pdf/UserGuideV2.pdf ), there are a few details that aren't fully covered in it and you might find the doc above helpful.
