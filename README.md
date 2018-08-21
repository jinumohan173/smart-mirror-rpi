# smart-mirror-rpi
this project helps u to make a, smart mirror which u can interact with it.



for installing magic mirror in raspberry pi dont use sudo infront of it

bash -c "$(curl -sL https://raw.githubusercontent.com/roramirez/MagicMirror-Module-Template/master/create_module.sh)"

it take lots of time u can have a coffe

after installing navigate to Magicmirror directory



cd MagicMirror/
after that

 
cd MagicMirror/npm start

wait for few seconds ur magic mirror will appear

to coustomize the mirror copy my config file from repo and replace it in Magicmirror directory
and change the two modules of news feed to get tamil/malyalam news update 

in this config file you can get weather of coimbatore(taiml nadu),
and indian calender.


replace all files and restart magic mirror 
by 

cd MagicMirror/npm start


