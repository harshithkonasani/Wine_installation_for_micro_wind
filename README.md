# Wine_installation_using_micro_wind
This repository has steps for installing wine_software in Ubuntu

## Install the Desktop.rar file attached and extract them. 

//Open your ubuntu terminal and type the folllowing command in order

sudo apt update  
sudo apt install wine  
sudo apt install winetricks  </br>
// To create wine prefix     </br>
WINEPREFIX=/home/students/newwineprefix winecfg  <br/>

//  Make sure that installation directory has permission user permissions. if not give the permissions    </br>

winetricks vcrun6  


## If there is any issue in opening the wine window and terminal displays path not owned by you
//follow the below steps 

step 1: Go to export_Microwind Folder present inside extracted Desktop.rar </br>
step 2: Open the folder in Terminal  
stap 3: Enter the following command   

  **command : sudo wine Microwind2.exe**


**note: Do not manually enter the following above command, instead type wine and M and press tab.**
