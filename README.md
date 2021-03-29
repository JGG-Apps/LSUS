# LSUS
Linux Server Update Services (LSUS) is a project that have the main goal to give a centralized console to manage updates on Linux machines.

This project is actualy started in this concept:

Linux client machine: An agent application that collect information about the machine (Name, IP Adress, Ditribution Name, Distribution Version, How much updates are pending to install through his update mecanism (Ex.: Under Debian, Ubuntu, etc. what report "apt-get upgrade" on missing updates then send these informations to a centralized server).

Linux centralized server: A Web-based console with a database where the client machines had pushed their status. A combinated process could also collect data from disribution providers to get the latest updates available, EOL information, etc. 

This tool is not in the goal to change the mecanism of updates distribution, just give a easier tool for IT administrators when many Linux machines have to be supported.
