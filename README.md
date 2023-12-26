# Linux_Case1
Case_study


Create a new user Tom

sudo useradd -m -s /bin/bash -c "Tom" Tom

Tom’s Password & modify his shell

sudo passwd Tom
sudo chsh -s /bin/bash Tom

Commands for creating two groups

sudo groupadd project_group
sudo groupadd project1_group

Command to add Jane and Tom to the project_group

sudo usermod -aG project_group Jane
sudo usermod -aG project_group Tom

Commands to create Linux Repo

sudo mkdir /opt/Linux
sudo chown :project_group /opt/Linux
sudo chmod 770 /opt/Linux

Commands to create notes folder

sudo mkdir /opt/notes
sudo chown :project1_group /opt/notes
sudo chmod 775 /opt/notes

Commands to create research folder 

sudo mkdir /opt/research
sudo chown :project1_group /opt/research
sudo chmod 750 /opt/research
![image](https://github.com/Visi07/Linux_Case1/assets/125524720/568eff81-a37a-482f-bbff-2faf727a875e)
