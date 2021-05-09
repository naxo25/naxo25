### Hi!, i am developer 👋

    const mySo = {
      Distros: ['elementary OS', 'ArchLinux' ],
      getDistros(){
        return this.Distros
      },
      helloWord(msg = 'Hi!, i am developer 👋'){
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

  [Github Quasar Chat](https://github.com/naxo25/App-Chat-Quasar-VueJs-Firebase)

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
