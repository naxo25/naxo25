### Hi!, i am fullStack developer 👋

    const mySo = {
      Distros: ['elementary OS', 'ArchLinux' ],
      getDistros(){
        return this.Distros
      },
      helloWord(msg = 'Hi!, i am fullStack developer 👋'){
        return msg
      },
      getAll() { return [this.getDistros(), this.helloWord()] }
    }

      console.log(mySo.getAll())

      const express = require('express'), app = express(),

      fullStackDeveloper = {
        VueJs: { 
          Versions: [2,3], 
          stateManager: ['Vuex','reactive'],
          router: 'Vue-router',
          backend: 'Firebase',
          framework: 'Quasar', 
          deploy: ['movil','tv','web'],
          exp: 

  [App-Chat-Quasar-VueJs-Firebase](https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase)
  
  [App-Chat-V2-Quasar2-VueJs3-Firebase](https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase-V2)

  [Demo Web](https://nacholabraweb.000webhostapp.com/pwa/EjApp)

      },


        ReactJs: {
          Versions: ['Hooks'],
          stateManager: ['Redux','useContext'],
          exp: 

  [https://codesandbox.io/s/jolly-dew-c3ymz](https://codesandbox.io/s/jolly-dew-c3ymz)

        },
        NodeJs: {
          Versions: '>10',
          framework: 'express nodeJs',
          database: 'mySql',
          frontend: 'vueJs',
          exp: 

  [Github fullStack nodejs-mysql-vue](https://github.com/naxo25/nodejs-mysql-vue)

        },
        Js: { 
          exp: 

  [Tabla css bank](https://github.com/naxo25/Responsive-Tables-Api-Pokemons-Css-Js)

  [App toma turnos](https://github.com/naxo25/App_Toma-Turnos)

        },
        U: {

  [python](https://github.com/naxo25/Trabajo-de-Titulo-UTFSM)

  [jqueryPhp](https://github.com/naxo25/Practica)

  [usm](https://github.com/naxo25/UTFSM)

        },
        others: {

  [youTube](https://www.youtube.com/channel/UClJr019QbaWJy3klKDOenXQ)

  [github](https://github.com/naxo25/)

  [site](https://nacholabraweb.000webhostapp.com/)

  [Tutoriales](https://nacholabraweb.000webhostapp.com/Tutoriales/#/Linux)

        }
      };

      console.log(fullStackDeveloper);

      app.get('/', function(req, res) {
        res.header('Access-Control-Allow-Origin', '*');
        res.send(fullStackDeveloper) });

      app.listen(process.env.PORT || 3000, () =>
        console.log(`http://localhost:${3000}`))

# formated

    sudo apt-get update && sudo apt-get upgrade

    # nano /etc/sudoers 
    # nax ALL=(ALL) NOPASSWD:ALL

    # git
    apt-get install git
    git --version

    # brave
    sudo apt install apt-transport-https curl

    sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg

    echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list

    sudo apt update

    sudo apt install brave-browser

    # sublime 4
    wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -

    sudo apt-get install apt-transport-https

    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

    sudo apt-get update
    sudo apt-get install sublime-text

    # nvm 
    # curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    # source ~/.bashrc 
    # nvm install 16 
    # nvm use 16

    # yarn
    # npm install --global yarn
