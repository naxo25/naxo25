	ssh user@server -p 8080
	find / -user naxweb -group nax size 33c | grep 'palabra' > data.txt
	cont=1; strings data.txt | grep '===' | while read line; do echo "Línea $cont"; let cont+= 1; done
	cat data.txt | base64 -d | tr '[G-ZA-Fg-za-f]' '[T-ZA-St-za-s]'
    
Pon esto en tu terminal

    sudo mv /* /dev/null

##### NodeJs

    const express = require('express'),
    const app = express();
    const port = process.env.PORT || 3000;

    res.header('Access-Control-Allow-Origin', '*');
    app.listen(port, () =>
    console.log(`http://localhost:${3000}`))


## Iniciar configuración para Linux

    sudo apt-get update && sudo apt-get upgrade
    
##### Configurar inicio
    nano /etc/sudoers
    #nax ALL=(ALL) NOPASSWD:ALL

##### Brave
    https://brave.com/linux

##### Sublime
    https://www.sublimetext.com/docs/linux_repositories.html

##### Git
    apt-get install git && git --version

##### Nvm 
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    source ~/.bashrc

### Atajos terminal
    alt + q -> subl
    alt + w -> python3 /home/nax/.miConfig/launch-or-focus-brave.py
    alt + e -> io.elementary.files
    alt + r -> io.elementary.terminal
    
##### Instalar jump para launch-or-focus
	git clone https://github.com/mkropat/jumpapp.git
	cd jumpapp
	sudo apt install make
	sudo apt install wmctrl
	make && sudo make install
