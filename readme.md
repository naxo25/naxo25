    const myProfile = {
      Distros: ['elementary OS', 'ArchLinux' ],
      VueJs: { 
        Habilities: [Vue2, Vue3, Quasar, Vuex, reactive, Vue-router, Firebase],
        Deploy: [Android, Smart-TV, Spa, Ssr, Electron],
        Experience: {
          Estadio TNT Sports (Web): https://cl.estadio.com
          Estadio TNT Sports (LG): https://www.linkedin.com/feed/update/urn:li:activity:6839580386524233728
          CFGym (Web mobile): https://nacholabraweb.000webhostapp.com/pwa/EjApp/
          naxChat Web móvil V1: https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase
          naxChat Web móvil V2: https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase-V2
          naxChat Android: https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase/blob/main/dist/Android/naxChat_Capacitor.apk
        }
      },
      ReactJs: {
        https://codesandbox.io/s/jolly-dew-c3ymz
      },
      NodeJs: {
        https://github.com/naxo25/nodejs-mysql-vue
      },
      Js: { 
        https://github.com/naxo25/Responsive-Tables-Api-Pokemons-Css-Js
        https://github.com/naxo25/App_Toma-Turnos
      },
      U: {
        python: https://github.com/naxo25/Trabajo-de-Titulo-UTFSM,
        jQuery-Php: https://github.com/naxo25/Practica
        Utfsm: https://github.com/naxo25/UTFSM
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
    
# Atajos terminal
    alt + q -> subl
    alt + w -> python3 /home/nax/.miConfig/launch-or-focus-brave.py
    alt + e -> io.elementary.files
    alt + r -> io.elementary.terminal
