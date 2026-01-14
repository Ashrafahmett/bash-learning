
i'm curruntley learning bash script and i'll share the knowledge i gaind thorough this project

let's start with basic

cd: you gonna use this commend when you need to folder like desktop or user 

cd .. you gonna use this one you need to left the folder like you went to folder dektop but how you gonna left that's whay we need to use cd .. and make sure to put space on in it becuse if you just put cd.. it's not gonna work

ls.. this one you gonna use when you need to list all files for example you went folder desktop so how do you know what inside desktop that's why we need ls

pwd... this is gonna tell you where are you in curruntly like when open your terminal and you want to go the folder dowloands how do you know you are inside the folder so this why we need to do pwd

and right now le's script small bash , 

we gonna start with shebang #!/bin/bash

then echo, echo is output dont' worry i'll write the script after i'll explain to you what it's

echo " hello sir" it's mut have a space onless is not going, to work.

have fun with echo write a lot and see what is going to open

after just make another folder using the commend line 

mkdir bash.sh

cd bash.sh

first look where you are and guess what we gonna use yes your right we gonna use pwd

then you can use cd to your folder , get it


#so lt's make small script askin the user he's name and age


#!/bin/bash


echo "hello sir what's you name" name
read name

echo "wellcom $name "

echo "what's is your name?" age

read age

echo "you are $age year old wow that's cool!"




#this script we make he gonna ask the users what is thair name and age


read is vairable and we used to sort the data and output the name of the user




#ok se we used read how we can make it in one line?


read -p "hello what's your name?" name

see, we use it one oline and my you may wondring why we did,t use the echo ! beacuse se use it the read variable to read the text and we don't have to say echo"



ok let's make script using read variable,



#/bin/bash

read -P "hello user what's your name" name

echo "$name wow that's a good name"

read -P and if may ask what's your age" age

echo "$age you are very young wow"


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


ok let me introduce with -s 

-s you gonna use when you need to hide something like user password le's make one


#/bin/bash


read -p "hello user put your username"username

echo "$username"

sleep 1


read sP-"please put your user name"

........................................................................................................................


right now let's talk about ,,if 




#!/bin/bash

age=18

if [ $age -ge 18 ]; then
  echo "You are an adult"
else
  echo "You are under 18"
fi#!/bin/bash
echo "🐍 Python | 💻 Cybersecurity"
echo "📚 Learning every day"
echo "🏋️ Gym • Code • Build"




#!/bin/bash

echo "What is your name?"
read name

echo "Hello $name 👋"
echo "Today is: $(date)"














