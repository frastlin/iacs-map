# Welcome to the mud map created for the IACS 2018 at OCAD!

## Getting started
1. Install python 2.7 32 bit
2. Download this repository
3. Go to the unzipped repository and type: pip install -e evennia
4. Type: evennia start

### Restarting The Server After It Has Been Shut Down

1. Open Anaconda prompt
2. Navigate to the folder using Anaconda prompt
3. Type the following two lines:
set CONDA_FORCE_32BIT=1    
conda activate evennia  
4. Type: evennia start
5. Visit:  
http://localhost:4001/webclient/    


### Detailed Getting Started
1. Download python using [Miniconda](https://conda.io/miniconda.html)
2. Go to the start menu or applications and type: anaconda prompt. An application should show up. If it doesn't, restart your computer.
3. Once Anaconda prompt is open, type the following lines (hit enter after each one):
set CONDA_FORCE_32BIT=1  
conda create --name evennia python=2.7  
Some text will show and it will ask you if this is what you want. type "y" and hit enter.
4. Type: conda activate evennia
5. [Download the zip file of this repository](https://github.com/frastlin/iacs-map/archive/master.zip)
6. Unzip the file (we'll assume it's on your Desktop) and get the path to the unzipped folder. On windows, press alt+d in Windows explorer and copy that long path. It will look something like: "C:\\Users\\YourName\\Desktop\\iacs-map-master"
7. Go back to your Anaconda prompt and navigate to the unzipped folder. You type cd by the name of the folders you want to go to. At the end, the: (evennia) C:\\Users\\YourName\\ should match the path you copied. Try typing cd, space, then paste the path you copied and hit enter. If it works, you will see the path change. If it doesn't, you will see an error. If you get the error, try typing the path one folder at a time. It will look like this: cd Desktop, cd iacs-map-evennia.
8. Once you are in the iacs-map-master folder, queue up about 5-10 minutes of Youtube videos and type: pip install -e evennia
9. After all those packages finish installing, type: evennia start
10. Visit the web client at:  
http://localhost:4001/webclient/  
and create an account or log in with your account.

### Troubleshooting

The above is very basic, if you need help, read the [Evennia getting started documentation](https://github.com/evennia/evennia/wiki/Getting-Started)


# Getting started With Evennia

From here on you might want to look at one of the beginner tutorials:
http://github.com/evennia/evennia/wiki/Tutorials.

Evennia's documentation is here:
https://github.com/evennia/evennia/wiki.

Enjoy!
