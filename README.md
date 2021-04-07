# 1NT18IS076_kaushal_B_NPLab
A documentation repo for recording day to day progress of NP Lab 6th sem.

# To install:
Visit [here](https://www.nsnam.org/releases/ns-3-30/download/) to download the source code. Unzip the tar file and continnue with the procedure below.

# To run:

```bash
sudo su
cd ns-all [TAB]
cd ns [TAB]
cd scratch [TAB]

[Write your program]

cd ..
./waf
./waf --run scratch/filename [without extension]
cd ..
export QT_X11_NO_MITSHM=1
cd netanim-3.108 [TAB] # see to it that you visit the right folder
./Netanim [TAB]

# now open the xml file saved in the GUI, and click on the run button
# configure the options, like keep the speed as 'slow', to observe the packet
```

This is how you run a program in this repository on the lab computers.
