# Nifi

### Steps to export template:
1. First need to save template you want to export, if it is not already saved. 
2. For that, right click on process group you want to export -> Click on `Create template`-> Add name `Test template` -> Add description -> `test` -> click `create`-> `ok`.
3. Go to top right corner bar, Click `Templates`-> Click on `Download` icon on right hand corner near to delete icon.

### Steps to import template:
1. In Nifi flow process group -> CLick on `Upload Template` icon -> Click on `Select Template maginifying glass button` -> select template you want to import -> Click on `upload` button -> if you see Sucess `Template successfully imported -> Click `ok`.
2. Then. drag and drop template icon on nifi canvas -> Choose template you just exported -> Click on `Add` button.

#### How to start nifi in terminal:
= Start
- cd /opt/nifi
- ./nifi.sh run

#### How to start nifi registery:
-cd /opt/nifi-registry/bin
-sudo ./nifi-registry.sh start
# to stop 
- sudo ./nifi-registry.sh stop
