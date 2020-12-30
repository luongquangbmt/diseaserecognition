# Disease Recognition
- Create a VM from Google Cloud Platform with Centos OS

- Login to the VM  
ssh -i ~/.ssh/id_rsa quang@130.211.228.122  (user name is different, IP address is different)

- Create two python environments DEV and PROD by the script in scripts/CreateEnvironment.txt  
. CreateEnvironment.txt  
If you install any new package, please add the name to the scripts   

- Activate the DEV enviroment
conda activate DEV  

Data is downloaded from kaggle
https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data
