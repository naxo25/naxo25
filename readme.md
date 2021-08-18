    const myProfile = {
      Distros: ['elementary OS', 'ArchLinux' ],
      VueJs: { 
        Versions: [2,3], 
        stateManager: ['Vuex','reactive'],
        router: 'Vue-router',
        backend: 'Firebase',
        framework: 'Quasar', 
        deploy: ['Android', 'TV', 'Spa', 'Ssr', 'Electron'],
        experience: {
          https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase
          https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase-V2
          https://cl.estadio.com/
        }
      },
      ReactJs: {
        example: https://codesandbox.io/s/jolly-dew-c3ymz
      },
      NodeJs: {
        framework: 'express',
        database: 'MySql',
        frontend: 'VueJs',
        experience: https://github.com/naxo25/nodejs-mysql-vue
      },
      Js: { 
        experience: {
          https://github.com/naxo25/Responsive-Tables-Api-Pokemons-Css-Js
          https://github.com/naxo25/App_Toma-Turnos
        }
      },
      U: {
        python: https://github.com/naxo25/Trabajo-de-Titulo-UTFSM,
        jqueryPhp: https://github.com/naxo25/Practica
        usm: https://github.com/naxo25/UTFSM
      },
      others: {
        youTube: https://www.youtube.com/channel/UClJr019QbaWJy3klKDOenXQ
        github: https://github.com/naxo25
        site: https://nacholabraweb.000webhostapp.com
        Tutoriales: https://nacholabraweb.000webhostapp.com/Tutoriales/#/Linux
        otherCodes: https://github.com/naxo25/misc
      }
    };

    const express = require('express'),
    const app = express();
    const port = process.env.PORT || 3000;

    res.header('Access-Control-Allow-Origin', '*');
    app.listen(port, () =>
    console.log(`http://localhost:${3000}`))


## Init config for linux

    sudo apt-get update && sudo apt-get upgrade
    nano /etc/sudoers
    nax ALL=(ALL) NOPASSWD:ALL

#### Git
    apt-get install git && git --version

#### Brave
    https://brave.com/linux

#### Sublime
    https://www.sublimetext.com/docs/linux_repositories.html

#### Nvm 
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    source ~/.bashrc 
    nvm install 14
    nvm use 14

#### Yarn
    npm install --global yarn
