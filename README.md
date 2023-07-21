# sim-queue

Author:  Erin James Wills, ejw.data@gmail.com  

![Queueing Simulation](./images/queue-simulation.png)  
<cite>Photo by <a href="https://unsplash.com/@adriendlf?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Adrien Delforge</a> on <a href="https://unsplash.com/s/photos/checkout?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></cite>

<br>

## Overview  
<hr>  
Basic waiting line queueing system  

## Excel Simulations
1.  `queue-sim.xlsm` - Queue system that calculates arrivals and service time based on a normal distribution and generates the wait time, leaving time, and number of people in the queue.  

## R Simulations
1.  `queue_sim.ipynb` - Python (utilizing R package) version of the Excel `queue-sim.xlsm`
1.  `chained_queue_sim.ipynb` - Continuation of the `queue_sim.ipynb` that illustrates how one queue can feed into multiple other queues.  

## Python Simulations
1.  `queue_sim.ipynb` - Python version of the Excel `queue-sim.xlsm`.  Uses basic Python specifically scipy and numpy.  



## Technologies
* Excell
* Python
* R



## Installations
* R
    1.  Ensure R is installed
    1.  Ensure R is added to the Path (PC):  `C:/Program Files/R/<version>/bin`
    1.  Open Gitbash and type `r` to open the r terminal
    1.  Install package:  `install.packages('quequecomputer')`
    1.  Select download region from popup
    1.  Check that package is now available:  `libary('quequecomputer')` - no errors should occur
    1.  Close terminal and open new Gitbash and install `pip install rpy2` into your environment

```Note:  rpy2 requires R 4.0+ and Python 3.7+ and older version of Visual Studio Build Tool (like 2019) can cause install errors.  I needed to uninstall the older tool and reinstall the most recent version.  Visual Studio Build Tools 2022 works fine with R 4.2 and Python 3.10 for my setup```  

## Improvements
* use quequecomputer and for loop over the number of servers but to make it better find the average of at least 20 points for each observer.  Then plot it.  
* use quequecomputer and simulate something like a covid processing center to determine the number of people and building size.