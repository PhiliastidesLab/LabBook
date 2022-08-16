# LabBook-wiki-

In this repository you can read the Wiki for common admin tasks. Connecting to the grid, to office computer from home, etc. 

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
* To open another Matlab, type `matlab &` in the same terminal (to run on the same node), or open a new terminal and repeat the above steps entering a new node number (e.g. ssh compute-1-21).

# _EEG info_

EEG preprocessing and analysis pipelines 

For detailed EEG recording information Glasow Uni library has an electronic version of: Luck, S. (2014). An introduction to the event-related potential technique. Chapter 5.Basic Principles of ERP Recording. MIT press.

Info on EEG cap with 64 electrodes with electrode potision and numbers 

## EEG cap 64. Brain vision [doc](https://github.com/PhiliastidesLab/EEG_folders/blob/main/BC-64.pdf)

## Cap usage [log](https://docs.google.com/spreadsheets/d/1uSCQBgyfLt5m5uFhFGr-5tHs48YUQIHV/edit?usp=sharing&ouid=107561805852058488076&rtpof=true&sd=true)

## Convert EEG to BIDS format: https://github.com/sccn/bids-matlab-tools.git

