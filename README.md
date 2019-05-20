# nodeemp
Simple node emp using mongodb as the back end for linux boxes. To maintain list of users and there access
# Stock holders
1)Admin - Able to add all kind of users and all kind of access</br>
2)Community manager - Able to add new users and maintain there attentance and there details</br>
3)Members - Able to edit there detail and able to see there attentance.</br>
# Steps to install
1)Make sure that your mongodb is running  on your local machine</br>
https://docs.mongodb.com/manual/administration/install-on-linux </br>
2)Make sure that the machine has node js</br>
https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04

# Follow thease commands
</br>
sudo mkdir new</br>
cd new</br>
git init</br>
git remote add origin https://github.com/arunwebber/nodeemp.git</br>
git pull origin master</br>
[Wait till the download is completed]</br>
sudo npm install</br>
[Wait till the installation is completed]</br>
sudo node ./bin/www</br>
[In terminal it will show 'App startted Port: 3000']</br>

# Cheers

Once it is startted go to the browser and type
http://localhost:3000/employees/</br>

There you can add edit delete employees

