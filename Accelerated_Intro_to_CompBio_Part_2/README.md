# Accelerated Introduction to Computational Biology for Biologists: Part 2
Part 2 of the "Accelerated intro to Computational Biology for Biologists" course for the Master's Programme in Computational Biology, Universidad Politecnica de Madrid. This covers the first 2 weeks (~24 hours) of material, taught by Mark Wilkinson. 

In this part of the course we cover:
   * Jupyter Notebooks (a bit more detail)
   * Introduction to Docker
   * Introduction to Databases (mySQL), including Docker installation
   * SQL (and perhaps other kinds of DBs, time permitting)
   * Introduction to Python


# UPM Computational Biology Master's Programme
# Bioinformatics Programming Challenges

A BioRuby-based bioinformatics course (still under-development - not recommended for ANY purpose!)

## 3 ways to run this course:

** CURRENTLY DISABLED ** 1)  Binder is a way to interact with the Jupyter notebooks inside of this repository - try it!  
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CBGP-UPM-INIA-PUBLIC/Bioinfo_ProgrammingChallenges/master)

2)  If you use Docker, you can <code>docker pull</code>, and then <code>docker run</code> this course as a Docker image as follows:

     <code>docker pull  markw/upm_compbio_masters_programme</code>

     <code>docker run -p 9000:9000 -it markw/upm_compbio_masters_programme jupyter notebook --ip 0.0.0.0 --port 9000</code>
     
     Open the link displayed to begin browsing the (interactive) course in your Web browser.
    

3)  Download the VM Ware image that has additional software such as Komodo edit and BlazeGraph installed (see instructions below)


## UPM Students - INSTRUCTIONS

Dear Students, 

You will take this course using a VMWare Virtual Machine.  You should do the following:

0. CREATE AN ACCOUNT ON GitHub (this website) if you haven't already got one...
1. Download VMWare Player (if you haven't already got it): https://my.vmware.com/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/14_0
2. You should download the VMWare Virtual Machine that I have created for this course, which is in this Zenodo deposit:  https://doi.org/10.5281/zenodo.1147435
3. Unzip the virtual machine
4. Start VMWare Player and select the virtual machine - start it (PASSWORD IS osboxes.org)
5. In the top-right corner of the VM Desktop, you can select either US-style or Spanish-style keyboard
6. Browse to:  https://github.com/CBGP-UPM-INIA-PUBLIC/Accelerated_Intro_to_CompBio_Part_2
7. In the top-right corner, click "Fork", to make a copy of this repository in your own GitHub account
8. Browse to the copy in your GitHub account (you should already be there after Forking)
9.  Click the big green "Clone" button and copy the address to your clipboard
10. open a terminal window in your Virtual Machine
11. type:  <code>git clone http://github.com/yoruaccountname/Accelerated_Intro_to_CompBio_Part_2.git</code>  (whatever you copied in step 9)
12. after it is cloned, cd into the "Lectures" folder and type <code>jupyter notebook</code> to start the interactive Jupyter session
13.  Browse to Lesson 1 and... let's get started!


